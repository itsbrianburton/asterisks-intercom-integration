# Asterisk Integration for Video Intercoms (such as the Dahua VTO)

This fork of TECH7Fox's [Asterisk Integration](https://github.com/TECH7Fox/Asterisk-integration) excellent integration is being used as a base to create an integration designed specifically for integrating with Dahua VTO (and possibly other) video doorbells.

## Roadmap
1. Tie PJSIP extensions to the browser_mod device IDs instead of creating unnecessary persons in HA.
2. Create a new SIP card designed specifically for video doorbells, specifically the Dahua VTO2202.  It will be included in the integration instead of being a separate installation.
3. Better handling of the video call to device notification flow

## Requirements
* [Asterisk Addon](https://github.com/TECH7Fox/asterisk-hass-addons)
* [Browser Mod](https://github.com/thomasloven/hass-browser_mod)


## Installation
Download using **HACS**
 1. Go to HACS
 2. Click on the 3 points in the upper right corner and click on `Custom repositories`
 3. Paste (https://github.com/itsbrianburton/asterisks-intercom-integration/ into `Add custom repository URL` and by category choose Integration
 4. Click on add and check if the repository is there.
 5. You should now see Asterisk integration. Click `INSTALL`
 6. Restart Home Assistant.
 7. Go to integrations and find Asterisk.
 8. Fill in the fields and click add. If succesful, you should now see your PJSIP/SIP devices.
