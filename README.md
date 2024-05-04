# emailcount
Code for Google Apps Script to count Gmail emails I received yesterday
It is largely based on script from StackOverflow by Kristkun
https://stackoverflow.com/questions/68009437/counting-emails-in-gmail-in-google-sheets

Right now I have separate scripts for counting Inbox messages and Sent messages.
I decided to label all incoming mail "Received" - I did this so that if I change the status of an email to archive or otherwise move it out of Inbox on the day I receive it, it will still be counted.
Question: if I delete a message will it still be counted?
I ultimately want to trigger it so it happens automatically each day or when I press a button.