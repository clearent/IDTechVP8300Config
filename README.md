![Screenshot](docs/clearent_logo.jpg)

# IDTech VP8300 Configuration

:warning: Use configuration files from the config/prod folder when configuring readers to be used in the live environment.

## Release Notes

Date: 3-6-2019

VP8300 Unencrypted

* No need to extend sleep mode

* Test Config file: config/test/good_betty_03062019.json

* Firmware file: firmware/VP3300 USB NEO v1.01.116_USBHID.txt


Date: 11-20-2019

Added support for contactless

* Test Config File: config/test/vp8300_tap_20191115.json

* Firmware file: firmware/VP3300 USB NEO v1.01.175_USBHID.txt


Date: 12-10-2019

Modified the FFFC tag on the MasterCard contactless configuration group so Apple Card will work.

* Test Config File: config/test/vp8300_tap_20191210.json

Date: 12-11-2019

* Introduced two folders, one for test, one for prod.
* Updated the Ca Public keys to be the LIVE keys.

* Prod Config File: config/prod/vp8300_tap_prod_20191211.json
