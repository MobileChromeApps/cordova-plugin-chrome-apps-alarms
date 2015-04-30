# chrome.alarms Plugin

This plugin allows apps to register alarms.

## Status

Stable on Android; not supported on iOS.

## Reference

The API reference is [here](http://developer.chrome.com/apps/alarms.html).

# Release Notes

## 1.3.3 (April 30, 2015)
- Renamed plugin to pubilsh to NPM

## 1.3.2 (Mar 17, 2015)
* Remove version constraint on backgroundapp dependency due to plugman bug CB-8696

## 1.3.1 (Mar 17, 2015)
* Use component to handle background events (merged from main repo mobile-chrome-apps/android-service)

## 1.3.0 (Jan 27, 2015)
* Add callback parameters to `chrome.alarms.clear` and `clearAll` (fixes #489)

## 1.2.0 (November 17, 2014)
* Simplify chrome.alarms's java code
* chrome.alarms: Make it more robust and prevent onLaunched when onAlarm is the cause of the Activity starting up

## 1.1.0 (October 21, 2014)
- Automatically change theme to translucent on Android.
- Documentation updates.

## 1.0.1 (March 10, 2014)
- Documentation updates.
