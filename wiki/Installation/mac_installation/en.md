# Playing on macOS
This page is designed to help you run Titanic, if you are using a Macintosh computer.
For this guide you'll need the following files:

- A client from the site
- The latest wineskin (the file will be in a zip on the GitHub.)
- A supported macintosh from the list below

1. Make sure your Mac is running a operating system above High Sierra, as it is required for the best performance and this guide. Although it might run on High Sierra, most browsers don't support GitHub. **Important! If your Mac is running any Catalina version below `10.15.5`, you'll need to disable System Integrity Protection (SIP).**

Therefore, in order to run osu!mac on macOS Catalina `10.15.0` to `10.15.4` you need to disable SIP.

To disable SIP, do the following:

Restart your computer in Recovery mode.

Turn on your Mac and immediately press and hold these two keys: Command (⌘) and `R`.

Release the keys when you see an Apple logo, spinning globe or other startup screen.

You may be prompted to enter a password, such as a firmware password or the password of a user who is an administrator of this Mac. Enter the requested password to continue.

Launch Terminal from the Utilities menu. It should be in the menu bar at the top of your screen.

Run the command `csrutil disable`.

Restart your computer. You can do so from the top menu bar (just like you would normally.)

Once you have SIP disabled, let it boot up normally, login, and you can then begin to install osu!.


**For the best performance, please make sure your Mac is a 2011 or higher.** A 2008 or higher will run it, but 2011 or higher is recommended. It also has to support 32/64 bit capabillites.

1. Grab the whole package by clicking on "Code" and then "Download as ZIP". This will make it all into one big file. It is a big one, so please be patient on the download time as it can vary depending on your internet.
2. Go to the [Titanic downloads page](https://osu.titanic.sh/download/). Choose a client you'd like to use (Protip, scroll to see more clients). Once you have chosen one, download it and wait for it to finish downloading. 
3. Move the two files to the desktop and then extract them. Once extracted, head into the package on the osu! application by right/left clicking and clicking on Show Package Contents. Do not touch or go inside any other folders. There should be a "Wineskin" application in there. Once found, click on it. There should be 3 options: "Install Software", which is what we want to do, "Set Screen Options", and "Advanced". Click on "Install Software" and click on the second option. Navigate to where the folder is and click on it.
Head in to the osu! app again and locate a folder called "drive_c". Then navigate to the folder "Program Files" (not the x86 one) and then make a alias by right clicking on the client folder and then clicking on Make Alias. After it is made, drag it to the desktop and delete the alias in the folder. This will work, it is a link in a way to the folder. 
Go into Wineskin, then click on "Install Software". Click on the top option and then locate the alias. After clicking on the alias, find the `.exe` file and click on it.

It will say that it is busy, but it will launch and it should ask you for your credentals. If you have them. Login or create your account on the website.