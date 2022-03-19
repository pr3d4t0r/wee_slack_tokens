# wee_slack_tokens

## Experimental

This tool extracts the session token and d-cookie to ensure that the <a 
href='https://github.com/wee-slack/wee-slack' target='_blank'>wee-slack</a>
plug-in for WeeChat can access the Slack service.


## Quick start guide

1. Download `wsharvest` to your local file system
1. `chmod +x wsharvest`
1. Update `FIREFOX_DEFAULT_PROFILE_ID` with the correct profile ID; see the
   variable `FIREFOX_DATA` for the full path
1. Run `./wsharvest`
1. Paste the registration string in the WeeChat command line

This script copies the registration string to the Mac keyboard.

---

