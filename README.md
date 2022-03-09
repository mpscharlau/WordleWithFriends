# WordleWithFriends
A desktop application to play Wordle™ with friend submitted words. Includes options to change word length and number of guesses among other things to keep the game interesting!

# Overview
Words and game settings are declared on a google sheet and are loaded into the application on startup. At application startup, you will be prompted to enter the "Sheet ID", with will direct the application to the correct google sheet. This is done so games or sessions can be played with multiple groups of people. In the Beta version, there is a text document named SheetID.txt that has the Sheet ID for you to copy. Note, progress, scores, and other data is currently not stored outside of the application; each time the application is closed and reopened, a fresh game begins.

NOTE: Your antivirus _may_ flag this application as a possible threat because it does not recognize the application, it is new, and/or it was downloaded from the internet. As a general PSA, remember to only download and run software on your computer from sources that you know and trust.

Python source code was converted into standalone applications using auto-py-to-exe [Windows] and py2app [Mac].

# Installing on Windows
On github, click the green "Code" button > Download ZIP.

Extract the zipped folder. In the windows folder you will find the WordleWithFriends.exe and SheetID.txt.

Move the Windows folder to your desired location.

You may delete the SourceCode and MacOS files.

Remember, SheetID.txt contains the Sheet ID for you to copy into the game.

# Installing on Mac
On github, click the green "Code" button > Download ZIP.

Open the folder. In the MacOS folder you will find the WordleWithFriends application and SheetID.txt.

Move the MacOS folder to your desired location.

You may delete the SourceCode and Windows files.

Apple will not let you run this application by clicking on it (see the NOTE above).

Instead, command-click to bring up the context menu and select open.

Remember, SheetID.txt contains the Sheet ID for you to copy into the game.


# Reporting Bugs and Submitting Suggestions
Reaching out to me directly is prefered however, you may also leave a note on the Bugs and Suggestions sheet in the game's google sheet.
