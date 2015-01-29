Cabot Pushover Plugin
=====

This plugin allows you to send alerts to Pushover. It needs an app API key, and device IDs for each user.

Installation
----
1. Activate the Cabot venv
1. Run `pip install cabot-alert-pushover`
1. Add cabot_alert_pushover to the CABOT_PLUGINS_ENABLED list in *\<environment\>*.env
1. Add `PUSHOVER_TOKEN=<YOUR_APP_KEY>`
1. Stop Cabot
1.  Run `foreman run python manage.py syncdb`
1. Start Cabot.
