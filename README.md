# OctoPrint-CooldownNotification

This branch reflects a hack of the original code:
1. Trigger when the HotEnd reaches a user set temperature
2. Working on getting the ENABLED button to show on the Octoprint Navbar

## Setup

Install via the bundled [Plugin Manager](https://docs.octoprint.org/en/master/bundledplugins/pluginmanager.html)
or manually using this URL:

    https://github.com/gmccauley/OctoPrint-CooldownNotification/archive/master.zip
    
## HACK Installation
Using WinSCP or other terminal, open a session and:
Overwrite "__init__.py" located:/home/pi/oprint/lib/python3.7/site-packages/octoprint_CooldownNotification
Overwrite "CooldownNotification_settings.jinja2" located:/home/pi/oprint/lib/python3.7/site-packages/octoprint_CooldownNotification/templates

## Configuration

### Enabled
This can be used to enable/disable the plugin

### HotEnd Temperature Threshold
Define the temperature for when the GCODE is executed

### GCODE to Execute
The GCODE that is executed when the temperature threshold is reached
