---
sidebar_position: 2
---

# Office 365

## E-Mail Merge using Word Error - Microsoft Outlook for macOS
When you are using Word and Outlook to send e-mail (Merge Mail Function), sometimes you might experience the following error.
"This file needs to be opened by the Excel Workbook text converter, which may pose a security risk if the file you are opening is a malicious file. 
Choose OK to open this file only if you are sure it is from a trusted source."

There are no direct solution to this answer.  First, you should check if the Apple Mail.app is default email. Go and setup the account on Mail.app. Then go to Genernal and change the default mail  reader to Outlook.  Please check this [from Microsoft](https://support.microsoft.com/en-us/office/set-an-account-as-the-default-in-outlook-for-mac-1a085d36-db97-4230-9a40-c332364426e0?ui=en-us&rs=en-us&ad=us) or this [from Apple](https://support.apple.com/en-us/HT201607).

At the end of the link tutorial, it has how to set up default email reader. Restart you Mac. 
If still doesn't work, you will have to go to System Preferences and find privacy. 
Grant "Full Disk Access" to Word and Excel. Then after you click Yes to that pop-up, 
you can Send Merge E-Mail.  

:::caution

Please note that you can't edit/view recipients in this case. 

:::

## Power Automate Mail Merge 
支持不同收件人不同附件。
<https://www.youtube.com/watch?v=ku0NM9jhp-A&t=310s>