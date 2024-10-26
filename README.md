# Trip2PRague
FRP Bypass method for Huawei P8Lite 2017 (PRA-LX1)


# WARNING: FOLLOW THIS GUIDE ONLY IF YOU'RE TRYING TO RECOVERY A PHONE YOU ALREADY OWN, I DO NOT CONDONE USING THIS ON A STOLEN SMARTPHONE


## explanation
This bypass uses an exploit in Google's "highlight to search" function allowing the user to access external applications outside of the OOBE with the intention of performing a ``` Clean factory reset ``` hence rewriting the FRP's check

# important caveats
This exploit requires ``` Firmware version C432 ``` [which can be downloaded here](https://androidfilehost.com/?fid=1322778262904014852)

## if you aren't on firmware revision C432 / you're unsure of what firmware revision you're on, follow these steps
```
 - extract the contents of the firmware file inside of an SD card (*must be formatted in FAT32 and AT LEAST 8 GB*)
 - insert the SD card into the phone
 - power off the phone
 - (PHONE MUST *NOT* BE CONNECTED TO A COMPUTER AND/OR CHARGING BRICK) hold power & both volume buttons
 - phone will reboot into DLOAD mode
 - after the update is complete, reboot the phone
 ```
## Step 0: preparation
- follow the instructions on screen (select the language and region etc) until you're prompted to enter a google account <br>
- click the arrow in the bottom left of the screen and you'll be prompted to enable google services like location etc, select what you want since it's not important <br>
- on the next screen, click ```set up as new```

## Step 1: exploit
- you will now be prompted to enter a huawei ID, click on "forgot password"
- on the next screen, click "account change request"
- on the "CHANGE ACCOUNT" screen, click on the hyperlinks at the bottom of the page that says ```Statement About HUAWEI ID and privacy```
- on the ```Statement About HUAWEI ID and privacy``` screen, hold your finger on any of the words on the screen
- a popup menu will appear with a bunch of options, the one we need is ```share```
- share to GMAIL (NOT "Email", that's a separate app)

## Step 2: bypass
- once inside Gmail, click on the arrow on the bottom right corner and then on "SKIP"
- you will be prompted to add an account, add a Microsoft account, use your own microsoft account OR create a burner account

Note: Microsoft account is the only account that works with this exploit, adding a google account will result in the FRP lock being triggered again and any other account simply doesn't seem to work

Note: the log-in UI could appear broken, simply rotate the device sideways or scroll your finger on the top portion of the display and mash your finger on the screen until the keyboard appears and you can enter your email and password,
unfortunately I have no fucking clue as to why the UI decided to break all of the sudden

