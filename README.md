# Unofficial ZeroRanger port for Nintendo Switch
This is a port for ZeroRanger to Nintendo Switch. It was made around 2021, and I want to upload the latest version here.

## Why
Recently I have begun to feel some shame for creating commercial game ports of indie games. I don't like the possibility that someone didn't buy one of the games I ported because they got it for free on Switch. 
Releasing it here is actually a step to try to correct that.

the last update I made to the port was Fix 9. I am very proud of it technically with the optimizations it does and how well it plays. But on every ROM site, the most updated version I ever saw was Fix 4. Earlier versions have a number of critical bugfixes missing (if I recall correctly, one bug is a crash near a very important moment at the end of the game!)

So Fix 9 is going to be distributed here. It is encrypted in such a way that you need ZeroRanger's data.win file to decrypt it, like with Pizza Tower.
To anyone who wants the port and doesn't have the game:
- Getting it off ROM sites will get you a terrible experience
- If you buy the game you can get the version that actually works
- I'll be able to sleep soundly if you do

I just hope this shows up in the first page of search results...

In order to decrypt the .bins found in the releases tab, you must:

1. Grab the .bin from the releases tab that has a ZeroRanger version in its name that you own. You can check the version in ZeroRanger's options menu. (Make sure the distribution platform matches too)
2. Install [Python](https://www.python.org/) and download the decrypt.py script found in this repository's source code. You can do this by clicking on the file on the GitHub page, and locating the small "Download Raw File" icon above the file contents.
3. Copy the data.win from your ZeroRanger installation (Make sure it has NO MODS - it MUST be clean), the .py script and the .bin file to the same folder, and run the script.
4. Enjoy your .nsp!

By doing this you have "proven" ownership of ZeroRanger. And if the copy you used to prove ownership is pirated... That act of piracy is now also tied to the Switch port, as if you pirated it directly. You damn pirate.
