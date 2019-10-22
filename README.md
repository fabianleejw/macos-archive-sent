# macos-archive-sent

## Intro

Today I am happy to announce that macos-archive-sent is now available for all mac users all over the world. In 2011, the first Outlook for Mac was released, which featured greater compatibility and parity with Outlook for Windows than Entourage offered.

Since then, mac users have been telling us they prefer an uncrippled version of Outlook that comes with features like "AutoArchive". Customers can now continue to leverage their existing crippled version of Outlook but archive mails to their local folders with this Automator application + applscript.

## Notes

- Assumes one exchange account under outlook (script picks the first account)
- Archives emails under "Sent" folder older than 21 days to "Sent" folder under "On My Computer"
- Uses native Calendar application as schedular (No additional schedular or cron needed)

## Instructions

1. Download repo
2. Look at source if curious (open src/archive.scpt)
3. Open MacOS calendar app and create an event schedule it as often as you wish (weekly, daily etc)
4. Under alert choose "custom"  
   ![Choose custom](images/01-custom.png)
5. Select "Open file"  
   ![Choose custom](images/02-openfile.png)
6. Select "Other..."  
   ![Choose custom](images/03-other.png)
7. Select "archiveSent.app"  
   ![Choose custom](images/04-archivesent.png)
8. Select "At time of event"  
   ![Choose custom](images/05-attimeofevent.png)
9. Almost done... manually open the "archiveSent.app" to allow the OS to open the app for the first time...
