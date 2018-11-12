# Node-Red-Complete-House

Welcome to my "Node Red Complete House System"...it consists of a few differemt aspects of my home:
1: Presence detection setting house occupancy with guest mode
2: House hibernation (Rob Tait) with actionable notifications along with work hours to not disturb the wife
3. Watchdog system to email/alert if cameras, alarm systems, temp sensors go offline...as well as keeping Node Red running (Rob Tait)
4. Systems check on demand or auto on alarm set with announcements
5. Alarm system with all sorts of annoucements, actionable notifications
6. Blue Iris camera feeds in HA and MQTT triggers firing snapshot notifications...can also work as motion light triggers at night

Note:
This project requires ***Node Red*** and the ***"Alexa as a media player"*** script by Keaton Taylor successfully running....
Keaton's Github..... https://github.com/keatontaylor
Direct Link to Script... https://github.com/keatontaylor/custom_components/blob/master/media_player/alexa.py

The script alexa.py should be saved to your config/custom_components/media_player folder
and at minimum the media_player entry and options entered into configuration.yaml for it to work, restart!

Note: You may have to try a couple times to get the Captcha to work...just enter a few random letters and submit for a fresh photo.

**A Special Thank You! to Keaton Taylor for this amazing script, without it none of this would be possible.**

***If you haven't joined the DrZzs Home Automation and Tech Hacks facebook group and found this by other means...please join!***

Obviously...this is all set to my devices and their respective names...you will have to put quite a bit of work in on your end.
