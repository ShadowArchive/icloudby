## FAQs:

* This method uses Checkra1n Exploit to Bypass iOS iCloud Activation Lock even after Restart / Respring and Reset, It wipes out the iCloud Account on the iPhone / iOS Software and Recaches the Old System up alive, due to this. The method also Backs Up the iOS Setup.app or renames it for Removal of the Activation Lock, You can also use another Account on the iPhone after Refresh but never update it to the Latest due to Restrictions like that of so on Serial Number locked into the iPhone Mechanism from its Original Owners, Whatever you do; Unless tested, Just dont update it until further Updates.

* This method was also tested on iPhone 5s till iPhone X (never heard, but some say they did it) using iOS 12.2 till 12.3.2 but never on iOS 12.3.3 and yes it requires Mac OSX 10.9.5 to Mac OSX Catalina and Mojave; So better use Hackintosh if you dont have a Mac Book or Mac PC. Dont worry, Theres a Virtualbox and VM Suite available for use called Ra1nst0rm.

## Commands:

Paste this into the first terminal window:

( 1 ):
* ./tcprelay.py -t 44:2222

## Script Command:

Paste this into the second terminal window:

( 1 ):
* ssh root@localhost -p 2222

( 2 ):
* mount -o rw,union,update /

( 3 ):
* echo "" >> /.mount_rw

( 4 ):
* mv /Applications/Setup.app /Applications/Setup.app.crae

or

* mv /Applications/Setup.app /Applications/Setup.app.orig

( 5 ):
* uicache --all

( 6 ):
* killall backboardd

# Copyright:

* This method was developed by AppleTech752, AppleDemo, and Exploit3d, recompiled successfully by Xin Snowflakes.

## Credits to the Peeps above, and of course axi0mX for the Original Developer.
