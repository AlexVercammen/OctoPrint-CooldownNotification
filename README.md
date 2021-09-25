# OctoPrint-CooldownNotification

This branch reflects a hack of the original code:
1. Trigger when the HotEnd reaches a user set temperature
2. Changed the GUI to reflect the changes
3. TO DO --> Display the ENABLED button on the Octoprint Navbar.

## Setup

Install via the bundled [Plugin Manager](https://docs.octoprint.org/en/master/bundledplugins/pluginmanager.html)
or manually using this URL:

    https://github.com/gmccauley/OctoPrint-CooldownNotification/archive/master.zip
    
## HACK Installation
Using WinSCP or other terminal, open a session and:
1. Overwrite "\_\_init\_\_.py" located: /home/pi/oprint/lib/python3.7/site-packages/octoprint_CooldownNotification
2. Overwrite "CooldownNotification_settings.jinja2" located: /home/pi/oprint/lib/python3.7/site-packages/octoprint_CooldownNotification/templates

## Configuration

### Enabled
This can be used to enable/disable the plugin

### HotEnd Temperature Threshold
Define the temperature for when the GCODE is executed

### GCODE to Execute
The GCODE that is executed when the temperature threshold is reached
