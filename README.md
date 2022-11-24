# BinnaBot
This will be a Binnacle telegram bot, will run on python 3.9.

The bot will receive entries and save them in a text file locally and with a back up on a drive.

## Input commands

#### write -subject -input*
If no subject is specified, it will be tagged as "general"

#### read -subject -number -all
If -number is not specified, last 10 entries of the specified subject will be returned.
If -number = 0, all entries will be returned (as long as the toal entries are less than Maximum set value, max value could be 50 or 100, don´t know yet)
If -all is set, a text file with all entries of the specified subject will be returned.

**Mandatory parameters*
