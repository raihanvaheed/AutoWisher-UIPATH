# AutoWisher-UIPATH 
![Logo](https://github.com/raihanvaheed/AutoWisher-UIPATH/blob/master/AuttoWish%20logo.png)

Made a UIPath robot to read data from an excel and deliver messages on instagram or whatsapp based on the specified date mentioned
* Note: Currently the project remains as a script which runs on UIPath studio, hence only machines with windows installed will be able to download the sofware directly. Other OS will require to install the software on a virtual machine. 

## Installation
### Downloading the software
1. Go to https://cloud.uipath.com/portal_/register and make an account or log in to your account
2. Press the button on the right side bar which says download studio/sudio x
3. Run the install wizard and choose community edition
4. Use UIPath Studio

### Setting up the browser extension (Chrome)
Follow this UIPath guide
https://docs.uipath.com/studio/v2016.2/docs/installing-the-chrome-extension-for-uipath-studio

## How to use the UIPath Robot
### Excel File 
The current exccel file contains the usernames of the development team and the date of creation. Change the excel file to the details you require to send messages to.

### Whatsapp (Sequence.xaml)
1. Write the contact names* of the people you wish to mention on the first column of sheet 1, the messsage you wish to send on the second column and the date you wish to send it on (in DD-MM-YYYY format) in the third column
* Note: Write the full contact names as similar names may be pulled otherwise
2. Run the UIPath robot. Alternatively you can run the robot at 12:01AM everyday and it will automatically check if there is a event tha requires a message to be sent that day

### Instagram (Insta.xaml)
1. Write the username* of the people you wish to mention on the first column of sheet 1, the messsage you wish to send on the second column and the date you wish to send it on (in DD-MM-YYYY format) in the third column
* Note: Write the exact username
2. Run the UIPath robot. Alternatively you can run the robot at 12:01AM everyday and it will automatically check if there is a event tha requires a message to be sent that day

* NOTE: You require the UIPath extension to be on your Chrome browser 

## Future Plans
Our team is hoping to convert this scriptt into a function foor calendars or messaging applications available on all devices. 
We also hope to host the robot on a cloud computer (secure with your logins) and run every day at 12:05 AM or a specified time


