# osx-automator-services
Some services meant to make life a little easier


## Jupyter

### ...


## Reminders
### Create Reminder.workflow
Creates a reminder with a dialog.

### Create Reminder from Selected Text.workflow
Creates a reminder prefilling the dialog with the selected text.

### Create Reminder From Message.workflow
Creates a reminder prefilling the dialog with information about an e-mail, creates a link to the e-mail. This only works with Mail.app, an e-mail must be selected before executing the service.


## Mail
### Copy Mail URI.workflow
Copies to clipboard selected e-mails information. Creates a link to the e-mail (e-mails) selected and uses information about this document for the link. If only one e-mail is selected a simple link is copied. If more than one e-mail is selected a list is created in the &lt;ol&gt; style.

This creates an **RTF** link to be pasted in a program that allows formatting.

### Copy Mail URI Raw Text.workflow
Copies to clipboard selected e-mails information. Creates a link to the e-mail (e-mails) selected and uses information about this document for the link. If only one e-mail is selected a simple link is copied. If more than one e-mail is selected a simple text list is created.

This creates an **raw** link to be pasted in a program that allows formatting.


## Copy File URI.workflow
Copies to clipboard the URL of a file and shows the filename full path as simple text.


## Date and Time

### Insert Datetime and add to Clipboard.workflow
Inserts Date and Time as text. Leaves a copy in the Clipboard. The date and time are formatted using the date command `date '+%Y-%m-%d %H:%M:%S'` (returning a string with the following format: `yyyy-mm-dd hh:mm:ss` [24hour format]).

### Insert Date and add to Clipboard.workflow
Inserts Date as text. Leaves a copy in the Clipboard. The date is formatted using the date command `date '+%Y-%m-%d'` (returning a string with the following format: `yyyy-mm-dd`).

### Insert Time and add to Clipboard.workflow
Inserts Time as text. Leaves a copy in the Clipboard. The time is formatted using the date command `date '+%H:%M:%S'` (returning a string with the following format: `hh:mm:ss` [24hour format]).

### Insert Datetime.workflow
Inserts Date and Time as text. The date and time are formatted using the date command `date '+%Y-%m-%d %H:%M:%S'` (returning a string with the following format: `yyyy-mm-dd hh:mm:ss` [24hour format]).

**Note**: Prefer `Insert Datetime and add to Clipboard.workflow` as I've found it works more predictably.

### Insert Datetime (for filename).workflow
Inserts Date and Time as text. The date and time are formatted using the date command `date '+%Y-%m-%d_%H-%M-%S'` (returning a string with the following format: `yyyy-mm-dd_hh-mm-ss` [24hour format]).

## Spotlight delete and reindex.workflow
Runs the command `sudo mdutil -E /` which deletes the Spotlight index and makes it do a reindex.


## Dock enable suck minieffect.workflow
Windows in macOS can be minified using two effects Genie and Scale, there is also another hidden effect called suck, this enables it.

[Explanation Video](https://youtu.be/R1Ivk-X6RZE) (not made by me).

## (Deprecated) Toggle Hidden Files
*Note: This is now deprecated as a shortcut now exists since macOS Sierra which works much quicker: `cmd`+`shift`+`.` ([link](https://ianlunn.co.uk/articles/quickly-showhide-hidden-files-mac-os-x-mavericks/#show-hide-hidden-files-using-terminal)).*

Makes Finder toggle hidden files. Call it once and hidden files are shown, call it again and they will be hidden. Repeat if necessary.
