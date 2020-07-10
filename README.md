# AMENDMENT1
AMENDMENT1 Secure Anonymizing WiFi Hub

This is the main repository for CognitiveMetropolis. For AMENDMENT1 OS, please visit the sub-repositories to download the appropriate version. This repository will be updated with tools and software for augmenting or expanding the functionality of  CognitiveMetropolis releases. 

The AMENDMENT1 is a Secure Wifi Privacy Router built with Open Source (https://www.cognitivemetropolis.com/amendment1-is-open-source/) Software.  These repositories contain the Binary OS files and instructions for reinstallation. If you are not sure which you need, please choose the lastest (high release number). 

The torrc configuration files are examples to create different configurations. torrc_orig is what comes with the AMENDMENT1 and is a standard deployment. If you are experimenting and make a mistake this is the file you want to use to "fix" things without a full reinstall of the AMENDMENT1 OS.

torrc_iot - this limits the TOR network to addresses in the United States. It is "less anonymous" than other configurations but it will allow many IOT devices to work over TOR - which is a relative increase in your anonymity! Just update your TOR configuration with this file and start connecting your IOT Devices.

torrc_manyidentities - is an example of setting exit nodes for other countries and zones. If you *don't want* to have exit nodes in a given country, set the ones you will allow explicitly in this list. 

Don't forget to rename the file to "torrc" with you upload it to the /etc/tor directory with the Admin Interface: https://www.cognitivemetropolis.com/amendment1-user-guide/  Also, for TOR Configurations no used with the AMENDMENT1, you will not need the line "HashedControlPassword:..."

To learn more about the AMENDMENT1, please visit our main site: https://www.cognitivemetropolis.com/product/amendment1/

If, like us, you find sofware release repositories confusing use the main Open Source webpage on our site to find your download: https://cognitivemetropolis.com/pages/open-source :)
