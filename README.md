# AospExtended ROM
## Official devices application

Before open a pull request to add your device into our list of official devices, you should know a few simple things:

### 1. Hosting

Our files are hosted on [Android File Host](http://androidfilehost.com/), this means you must have a developer account to host the builds of your device.

The folder must be in **hidden mode**, so our [download portal](https://downloads.aospextended.com/) can manage statistics correctly.

### 2. Changelog
For each new version, you need to upload the changelog to this repository in the device specific folder.

The file name must be in this format: **yyyyMMdd-Hm.txt**

### 3. Over-the-air (OTA) updates
Our system is automatic, you should not worry about updating some script, just upload the new build to the Android File Host device folder and send a pull request with the changelog in this repository.

**Note:** New builds can take up to 30 minutes to appear on the site and in the OTA application.

### 4. JSON params
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
