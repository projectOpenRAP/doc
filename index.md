---
layout: default
---
![Thumbnail of openRAP](static/openRapLogo.png)
# [](#header-1)
OpenRAP stands for Open Resource Access Point. OpenRAP is an open source software initiative to develop a modular & scalable localised CDN platform. Open Offline Localised CDN software is written to be hardware agnostic. Open source software community can use, validate and contribute to project.

## [](#header-2)Installation



## [](#header-2)Running

## [](#header-2)Configuration

Introduction
This document describe the end user manual and  admin operations on the openRAP platform. 

End user Manual
An end-user of specific mobile app, that comply  with openRAP, do not need to do any additional operations. The end-user just need to connect to the openRAP WiFi hotspot and use the mobile application normally.
Admin Operations
Admin Login 

Admin can login to openRAP device, by browsing URL http://admin.edgecdn.com:8008/. Admin login id is “root” and admin login password is root by default. It is strongly recommended to change the admin password after the first login.

File Upload

File upload the default landing page after login. One can also visit the file upload page using  the menu on any page. The file upload page is shown in the figure 2.
In this page, following operations can be performed:
View the list of media files currently loaded in the system, displayed automatically when page is open.
Add Files: Upload files from the local device (laptop or phone) to the openRAP
Delete Files: Delete a set of files or delete all files
Add files from USB: If an USB flash is plugged into the openRAP devices, all the relevant media files from the USB flash memory can be uploaded to the openRAP device
Download the files to USB: The telemetry data from the openRAP device can be downloaded to USB that is plugged into openRAP device

SSID modification
From the menu, one can navigate to the SSID modification page. SSID modification page is illustrated in the figure 3.

SSID is the name of the WiFi network, which phone or tablet devices connect to. The name should be text or numbers. It is advised to avoid special characters in name. SSID modification page offers following function
View the current SSID, which is displayed as the page loads up. 
Modify the SSID, admin can type in the new SSID and save it, by clicking on change SSID
Change the openRAP device to host mode, so the device can connect to any of the WiFi access points in the vicinity. To change to host mode, admin need to input the name of the AP to connect to and also the password if any. 
Captive portal modification 
This page allows admin to customize the captive portal displayed when user get connected to openRAP WiFi network. Captive portal is the page or pop-up that is displayed on phones/laptops when user connects to specific WiFi network. This page can include information about the WiFi network, how to download the mobile app and how to use the openRAP facilities. Captive portal page is illustrated in the figure 4.

The captive portal customization page allows following functionalities:
Add a logo to the captive portal
Set the heading of the captive portal page
Set the description of the captive portal page
Add a APK (app package) for user to download

Change Global Variables
OpenRAP is very  customizable, admin can control various functional aspect of openRAP by setting right parameters. The change globle variable page, helps set these paramaters. The change global variable page is illustrated in the figure 5. In this page, parameters that can be set and the meaning of each parameter is listed in table 1.
 
Paramater
Meaning
cdn_url
URL to pull the offline content into the box
accepted_extension
Define the type of extension accepted via file upload
config_json_name
Json file for start up page of the app
 Telemetry
Location where telemetry is dumped on openRAP
profile_name
App profile name
usb_dir
Directory name in the USB to upload data from
Table 1: Paramater set and meaning 
Superuser tasks

      
Admin can add users, delete users and manage users. User management can be done via superuser tasks. Super user task page is shown in the Figure 6. In the page, admin can
View the user in the system, which is displayed when the page loads.
Delete users
Edit permission of users
Create new user

Edit user permissions

Users in openRAP system has permissions to perform various tasks. Admin user can manage the user permissions. By clicking on Edit permission button in User management page, admin can manage the permissions via Change Permission Page  as show in figure 7. 
In the page, admin can update specific user permission to 
Modify Captive portal
Delete Files
Download files to USB
Upload files to USB
Upload files from a device
Modify Global Variables
Modify SSID

Change Password
Change password page allows admin to change the  admin password. It is advised to maintain the admin password safe and password must be combination of text, numbers and special characters. Change password scree is simple, and shown in figure 8.


## [](#header-2)Adding Media
## [](#header-2)Helping teaching
## [](#header-2)Contributions
## [](#header-2)Community 
## [](#header-2)Additional Information




```
copyright project openRAP
```
