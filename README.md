# Google-Aps-Script-Mail-to-SpSh

What is the script about?

  It imports mail from Gmail, performs some Regex lookup on them and then exports the output into a spreadsheet.




How does it work?

  Gmail Filters add a label to a email by specific keywords in eg. the subject. Then the script imports this mail and performs several regex lookups on the plain aswell as the html text. 
  
  
  
  
  
What should i edit if i want to use this?

  First of all you should edit your gmail seeting and disable email clustering which connects multiple emails to one. 
  then you should add some filters for Gmail which are adding labels.
  You are going to need at least 2 labels. One for which mails should be used and one "edited" label.
  In the code you have to change the following aspects: labels, regex, variables for key data and i guess you dont need the hardcoded VLookup
  


Have fun and i hope it helps you organizing your mails :)
