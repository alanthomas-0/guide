# DC Guide

## Introduction


Getting Started with DC
What is DC?
DC is a community driven file sharing network through which you can access games, lecture videos, slides, movies, shows, ~stuff~ from your fellow mates.
Why use DC?
I get it, you have Netflix and Amazon Prime, a loaded steam account with all the games and a high speed internet… probably. Instead of being limited by the 8GB/day (current) data limit of BITSnet, you can instead access the common resources of DC.
So DC does not count against the BITSnet limit?
Your BITSnet limit is for internet access. A simple diagram will help demonstrate this:

As you can see, since your data limit is only counted for connection to the internet, DC does not use any of your quota. Still not convinced?

8GB/day for 30 days. You can do the math.
Okay, let’s get to the good part. How do I get started?
You can use one of the popular DC clients available online. We recommend the following:
Windows: AirDC++, ApexDC
Linux: AirDC++ (Web Client), EiskaltDC++
Mac: EiskaltDC++, Any of above Windows clients on Parallels
Help me set this up! (Windows)
Alright, let’s take AirDC++ as an example. You’ll download the setup from the link above and run it. Once you’ve installed AirDC++, on the first run you’ll be asked to configure it. Follow these instructions:
Select language. English is recommended, but you’re free to explore.

Select nick. Treat this as a username, so understanding passwords and unique nicks will be easier. Enter an optional description about yourself/files you will share (more on sharing in FAQ)

Select user profile as follows

And select maximum speeds in the next step. The campus ethernet is Gigabit capable, so you should be able to download good speeds

Next we will set up the connectivity settings. This step is important, any mistakes here can prevent you from connecting to others or the hub!
Make sure the lowe checkbox is selected for “I want to configure these settings manually”

Apply the same settings as below in the next step. Specifically, deselect “Enable automatic incoming connection type detection” and consequently you will be able to change other settings. Also make sure that the first “Active mode” is below the checkbox

Finally select the folders that you wish to share. Do not select spam folders like “Program Files”, it can result in ban from the hub.

Now you are ready to connect to the hub. Once you click on finish, you will be prompted with the windows firewall prompt, make sure to click on “Allow access”

Click on Ctrl+Q. You will be asked for address, enter this: 10.3.5.69:420

Click OK to continue.
You are now connected to the Echo DC hub of BPGC. You will see the following screen:


or you might be shown the latest releases as below. Just click on the Echo tab on the lower left corner to switch to the upper screen.

Double click on any of the names on the right side to explore the files that person has shared. You can then download files with a double click or download folders with right click and “Download”
<Resharing>
A good practice is to share the files you download from DC, so that the availability of that file is improved. You can do so by sharing your DC download directory. You can view your DC download directory location by going to File > Settings > (On left side) Downloads (Expand dropdown menu) > Download locations. In my case it is “D:\DC++\Downloads\”.
The default folder will be your Windows Downloads folder, which you would not prefer sharing in case it has some personal files. Therefore we recommend you to make a folder dedicated to DC downloads and select that folder in this window.

Now add the DC download folder to your share. In the same window as above, go to “Sharing” on the left side and add the folder we used above.

Common Issues
Server asks for password
You are using a nick/username which someone else already registered. Just go back to settings and set a different nick
Application keeps displaying connection timeout
Connect your laptop to ethernet, and make sure WiFi is off
Ensure that you have the right IP address. Although this is usually fixed throughout the semester, there can be unexpected power outages or network issues that can assign a different IP address to the hub. Any updates as such will be communicated to Important Info groups
Cannot connect to other users/other users cannot connect to me
If you have enabled firewall access as before, make sure you also add the ethernet network as a private (trusted) network in settings.

Go to Network & internet in settings application (while connected to LAN, not wifi), and select the network which has Ethernet in the name or has an icon of a display with cable like below
Click on properties in above section and change network profile to private (should be first option)

Note that the text under private network mentions file sharing
Extras
<Auto Connecting to Echo on startup>
Right click on the Echo tab on lower left corner and select “Add to Favourites”

<Setting a password/reserving your nick>
Your nick is your identity to connect to the hub and you would want to make sure that only you are able to use the nickname. You can set a password to the nickname by typing !regme <password> in the chat box in Echo tab

Once you register, a new window will open from Echo confirming your registration.

Go back to the first Echo tab and click Ctrl+R to reconnect. You will now be prompted to enter the password 

To save your password so that you do not have to enter it every time you connect, follow the steps in <Auto Connecting to Echo on startup>, then click on the star icon on top to open your favourite hubs.

Then in the next window right click on Echo entry and select properties

Enter your nick and password in the window that opens up

Troubleshooting
In case of any problem try the following solutions:
Switch off antivirus/firewall
Restart your client/try using a different one
Try using another LAN cable
Factory reset network settings
Change system LAN from public to private or vice versa
Try using another nick/ensure multiple windows of the client are not open

Active and Passive modes:
In passive connection mode, DC++ will only make outbound connections to other users. All searches will be sent through the hub, and search results will be returned through the hub as well. DC++ will return a maximum of 5 search hits for a passive user. Passive users may not able to download from other passive users. Passive mode is an extra strain on hubs, so please do not use it unless you must. To find out what DC++ users are in passive mode in a hub check their tag in the list of users. Passive users will have M:P in their DC++ tag.

That being said, active mode on DC++ will make inbound and outbound connections to other users. While all searches will be sent through the hub, search results will be returned directly from active mode users and through the hub for the passive users. Active users can download from either active and passive users and get more search results. Obviously that means you can connect to a larger group of people.

However, there is ZERO difference in download/upload speed between active or passive modes.

How to switch between the two?:
In your connection settings you'll have 4 options

Direct connection=Active mode (preferred)
Firewall=Passive mode (not preferred)


Regarding downloads & unfinished folders:
(only for apex/dc++ clients)

In Apex and vanilla dc++ there's two folders,first is downloads, where your finished downloads are stored and the second one is unfinished downloads.

For this,Create a folder structure similar to following:

DC++/
    Downloads/
    Unfinished/

Set download location to the downloads folder, unfinished downloads location to unfinished folder



DC guidelines:
These are general rules we expect you to follow while using the hub, in no particular order:
Share only files which are useful to others in any way. Sharing spam folders is a big no. For absolute starters, sharing some spam can be tolerable for a small amount of time, but make sure to download content and reshare and remove the spam asap.
Use only one instance of DC from one laptop. I appreciate your wish to download from multiple people but there’s a reason why you get a warning when starting multiple instances
Share your DC Download folder! You will be able to download faster as DC downloads files in parts, the more places it finds a file, the more parts it can download parallelly.
DO NOT BE A LEECHER. Give back to the community! Don’t just disappear after downloading whatever you want. Reshare, contribute more, and develop the community.

P.S. Titan ded. Replace Titan with Echo wrt all the pics.
