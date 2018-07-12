# README
Mac OSX Script to periodically delete your cached credentials in the OSX Certificate Store

This script will periodically clean your AWS CodeCommit credentials.

Refer to http://docs.aws.amazon.com/codecommit/latest/userguide/setting-up-https-unixes.html

Look especially at step 3.3 - This script will automate the process of removing the cached credentials resulting in your authentication failing.

More information regarding Apple Script: https://developer.apple.com/library/mac/documentation/AppleScript/Conceptual/AppleScriptLangGuide/introduction/ASLR_intro.html

# Installation Instructions

1. Clone this project on your Mac
2. Run the following in a Terminal:

	$ cp -vf  AWS-CodeCommit-Git-Password-Delete.scpt ~/Library/Scripts/

3. Open the Apple's "Script Editor" application
4. Open the Script Editor Preferences
5. Ensure that "Show Script menu in menu bar" is selected (you should see the icon in the menu bar)
6. Click the script menu icon in the menu bar - you should see the `AWS-CodeCommit-Git-Password-Delete` script at the bottom
7. Click the `AWS-CodeCommit-Git-Password-Delete` to start the application
8. You should see a turning gear in the menu bar indicating that the script is running


