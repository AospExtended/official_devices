# AospExtended OS
## Official devices application

Devices repository: https://github.com/AospExtended-Devices

Few things you should know before getting started:

### 1. Hosting

Our files are hosted on [SourceForge](Sourceforge.net), you will receive access when you join the team.

### 2. Over-the-air (OTA) updates
Our system is automatic, you should not worry about updating some script, just upload the new build to [SourceForge](Sourceforge.net) and send a pull request with the changelog and also edit your device JSON file (**builds/your_device_codename.json**) in [this](https://github.com/AospExtended-Devices/official_builds) repository. Please read the ReadMe file on that repo.

Eg: Moto G 2015 is called **osprey**, so the device JSON file is **builds/osprey.json**

**Note:** New builds can take up to 30 minutes to appear on the site and in the OTA application.

### 3. JSON parameters
| Param | Description | Required |
|--|--|--|
| name | Device name | Yes |
| brand | Device manufacturer | Yes |
| codename | Device codename, eg: falcon | Yes |
| version_code | Version code, lowercase, eg: oreo | Yes |
| version_name | Version name, will be shown on download portal, eg: Oreo | Yes |
| maintainer_name | Your name | Yes |
| maintainer_url | Your personal URL, eg: https://github.com/ishubhamsingh/ or https://forum.xda-developers.com/member.php?u=5566914 | No  |
| xda_thread | XDA thread URL, eg: https://forum.xda-developers.com/2015-moto-g/development/rom-aospextended-rom-v1-0-t3482475 | No |

**Please format your JSON code properly, [here](https://jsonformatter.curiousconcept.com/).**

### 4. Build type
You need to add 'export EXTENDED_BUILD_TYPE=OFFICIAL' in your build environment so that the OTA app will be included in your build.

### 5. Device tree
Maintainers should upload their device trees on https://github.com/AospExtended-Devices

### Important Links:

- [Website](http://www.aospextended.com/)
- [Download Center](https://downloads.aospextended.com/)
- [Blog](https://blog.aospextended.com/)
- [Gerrit Code Review](http://gerrit.aospextended.com/)
- [Apply for Official Device](https://github.com/AospExtended/Documentation_and_thread-template)
- [Telegram Channel](https://telegram.me/aospextended/)
- [Documentation, Official Devices & Thread Template](https://github.com/AospExtended/Documentation_and_thread-template/) 
- [Help us translate AospExtended ROM and bring it to the world!](http://translate.aospextended.com/)
- [Theme Resources](https://github.com/AospExtended/AEX-Scripts/) 
- [Extended Devices](https://github.com/AospExtended-devices/)
- [Gallery](https://aospextended.com/gallery)
- [Facebook page!](https://www.facebook.com/aospextended/)