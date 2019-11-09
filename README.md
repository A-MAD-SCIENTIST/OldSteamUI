# Make Steam Great Again!

This was made to get rid of the new ugly Steam UI and revert it back to the old one.

You can find a VirusTotal scan of the .exe [here](https://www.virustotal.com/gui/file/409e9398c4b9eb8d62d7ac59191131133ac499b6ebaefa04d59917e72cf11af6/detection) :)

# What does it actually do?

It's quite simple really. All It does is downloads the old Steam files from the Internet and extracts them to the Steam Dir (that's why some AVs may flag it as malware).

It then replaces the old package files with the new ones. When the user clicks on 'Stop new UI', it basically changes a couple of the file attributes in Steam to 'Read Only' to stop Steam from pulling down the new packages upon relaunching Steam.exe

# Installation 

Download the EXE and place it somewhere temp. Run it and browse to the directory where Steam is installed. If you get problems you should right-click and Run As Administrator.

# Tutorial

When you have pointed the software to the Steam.exe, click on the 'Upgrade UI' button. This actually upgrades to a UI that most of us like :P

You should then follow the on-screen instructions on the software.

# How do I revert back to the new UI?

Make sure Steam is fully closed, then browse to Steam Directory and delete the 'steam.cfg' file. 

Launch Steam and it will error out, ignore and relaunch. Login, close, and relaunch again to have the new UI.
