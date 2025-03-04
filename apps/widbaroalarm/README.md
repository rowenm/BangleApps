# Barometer alarm widget

Get a notification when the pressure reaches defined thresholds.

![Screenshot](screenshot.png)

## Settings

* Interval: check interval of sensor data in minutes. 0 to disable automatic check.
* Low alarm: Toggle low alarm
  * Low threshold: Warn when pressure drops below this value
* High alarm: Toggle high alarm
  * High threshold: Warn when pressure exceeds above this value
* Drop alarm: Warn when pressure drops more than this value in the recent 3 hours (having at least 30 min of data)
    0 to disable this alarm.
* Raise alarm: Warn when pressure raises more than this value in the recent 3 hours (having at least 30 min of data)
    0 to disable this alarm.
* Show widget: Enable/disable widget visibility
* Buzz on alarm: Enable/disable buzzer on alarm


## Widget
The widget shows two rows: pressure value of last measurement and pressure average of the the last three hours.

## Creator
Marco ([myxor](https://github.com/myxor))
