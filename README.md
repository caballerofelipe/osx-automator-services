# osx-automator-services
Some services meant to make life a little easier

## Toggle Hidden Files
Makes Finder toggle hidden files. Call it once and hidden files are shown, call it again and they will be hidden. Repeat if necessary.

## Create Reminder
### ...
Creates a reminder with a dialog.

### ...from Selected Text
Creates a reminder prefilling the dialog with the selected text.

### ...From Message
Creates a reminder prefilling the dialog with information about an e-mail, creates a link to the e-mail. This only works with Mail.app, an e-mail must be selected before executing the service.

## Copy Mail URI
Copies to clipboard selected e-mails information. Creates a link to the e-mail (e-mails) selected and uses information about this document for the link. If only one e-mail is selected a simple link is copied. If more than one e-mail is selected a list is created in the &lt;ol&gt; style.

## Copy File URI
Copies to clipboard the URL of a file and shows the filename full path as simple text.

## Insert Datetime
Inserts as text the date and time using the date command date '+%Y-%m-%d %H:%M:%S' (returning a string with the following format: yyyy-mm-dd hh:mm:ss).

## Spotlight delete and reindex
Runs the command '_sudo mdutil -E /_' which deletes the Spotlight index and makes it do a reindex.

## Dock enable suck minieffect
Windows in macOS can be minified using two effects Genie and Scale, there is also another hidden effect called suck, this enables it. 

Explanation Video https://youtu.be/R1Ivk-X6RZE (video not made by me).
