# AospExtended ROM
## Official devices application

Before opening a pull request to add your device into our list of official devices, you should know a few simple things:

### 1. Hosting

Our files are hosted on [Android File Host](http://androidfilehost.com/), this means you must have a developer account to host the builds of your device.

The folder must be in **hidden mode**, so our [Download portal](https://downloads.aospextended.com/) can manage statistics correctly.

### 2. Changelog
For each new version, you need to upload the changelog to this repository in the device specific folder.

The file name must be in this format: **yyyyMMdd-Hm.txt**

### 3. Over-The-Air (OTA) updates
Our system is automatic, you should not worry about updating some script, just upload the new build to your Android File Host device folder and send a pull request with the changelog in this repository.

**Note:** New builds can take up to 30 minutes to appear on the site and in the OTA application.

### 4. JSON parameters
| Param | Description | Required |
|--|--|--|
| name | Device name | Yes |
| brand | Device manufacturer | Yes |
| codename | Device codename, eg: falcon | Yes |
| afh_folder | URL of your hidden AFH folder, eg: https://www.androidfilehost.com/?w=files&flid=240377 | Yes |
| maintainer_name | Your name | Yes |
| maintainer_url | Your personal URL, eg: https://github.com/ishubhamsingh/ or https://forum.xda-developers.com/member.php?u=5566914 | No  |
| xda_thread | XDA thread URL, eg: https://forum.xda-developers.com/2015-moto-g/development/rom-aospextended-rom-v1-0-t3482475 | No |

**Please format your JSON code properly, [here](https://jsonformatter.curiousconcept.com/).**

### 5. Build type
You need to add 'export EXTENDED_BUILD_TYPE=OFFICIAL' in your build environment so that the OTA app will be included in your build.

### 6. Device tree
Maintainers should upload their device trees on https://github.com/AospExtended-Devices

**Important Links:**

- [Our Website, Downloads and Usage Statistics](http://www.aospextended.com/) 
- [Our Github](https://github.com/AospExtended/)  
- [Gerrit Code Review](http://gerrit.aospextended.com/) 
- [Documentation, Official Devices & Thread Template](https://github.com/AospExtended/Documentation_and_thread-template/) 
- [Apply for Offiical devices](https://github.com/AospExtended/official_devices) 
- [Help us translate AospExtended ROM and bring it to the world!](http://translate.aospextended.com/)
- [Telegram Channel](https://telegram.me/aospextended/) 
- [Theme Resources](https://github.com/AospExtended/AEX-Scripts/) 
- [Extended Devices](https://github.com/AospExtended-devices/) 
- [Settings - About us section](https://github.com/AospExtended/platform_packages_apps_Settings/blob/8.1.x/res/values/ex_maintainers.xml)
- [Markdown editor ](http://dillinger.io/) 
- [Markdown cheatsheet ](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)  
- [Gerrit Manual for AospExtended OS](http://gerrit.aospextended.com/Documentation/index.html/) 
- [AospExtended Gallery](https://aospextended.imgur.com/) 
- [Facebook page!](https://www.facebook.com/aospextended/) 

