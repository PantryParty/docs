---
layout: default
title: Configure HomeAssistant
nav_order: 5
parent: Getting Started
---

# Configure HomeAssistant

Home Assistant provides an ingress wrapper to Grocy which prevents third part apps
from accesses APIs of addons. The following instructions will make the Grocy app
available outside of the HomeAssistant ingress wrapper.


| Start by clicking the Supervisor link on the sidebar, then select the installed Grocy addon. | ![Step1](./assets/hass_step1.png)  |
| Then enter the configuration page. | ![Step2](./assets/hass_step2.png)  |
| First disable ssl by changing the configuration to `ssl: false` (1).<br> Correct configuration SSL for Grocy through HA is beyond the scope of these instructions. <br>Next save the configuration (2). <br><br>Below the configuration box select a host port for the web interface (3). Pick a high number but a number below 65000. <br>Then save the network configuration (4) | ![Step3](./assets/hass_step3.png)  |
{: .constrain-images-in-table }

Following the steps above should automatically restart your Grocy installation.
After Grocy reboots it will be available on the same host/IP but on the new port you
specified.

If you normally access HomeAssistant from http://home-assistant:8123 and you
selected port 2345 in step 3 above, you should now be able to access the Grocy
Web UI at http://home-assistant:2345. You should then use http://home-assistant:2345/api
for the Grocy configuration of PantryParty.
