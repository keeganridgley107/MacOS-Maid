# MacOS Maid
Keegan Ridgley Macbook Air fork 

A simple shell script I run to keep my MacBook clean and patched.

## What It Does:
-   Prompt For Password If Not Root
-   Deletes Saved Wireless Networks
-   Installs Needed System Updates
-   Empties The Trash
-   Deletes All System Logs
-   Deletes The QuickLook files
-   Updates And Cleans Homebrew
-   Cleans Ruby - adding git/pip/npm
-   Removes All Docker Containers
-   Purges Memory - adding check
-   Removes known_hosts file - adding check
-   Securely Wipes Free-space - adding check 

## Usage:
-   Review for your preferences and comment out options **You** dont want.
-   Set `homessid` and `workssid` variable to stop from deleting those!

**To Run:**

```
chmod +x maid.sh
./maid.sh
```

## Important Notice
I likely dont know what I am doing and this could be done faster, better and simpler some other way. These scripts could also break your MacBook and make you cry.
