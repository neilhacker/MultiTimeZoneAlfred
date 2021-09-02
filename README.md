# MultiTimeZoneAlfred
This is based off the workflow by Dean Jackson from this thread: https://www.alfredforum.com/topic/16680-paste-different-timezones-hotkey-using-selected-time-text/

Changes inspired by tweet by Devon: https://twitter.com/devonzuegel/status/1433507909808316425

Basically write some time in a format like "12:45pm" select this text the press hotkey and it will convert it to "12:45am PT / 3:45am ET / 8:45am GMT". If you go into the alfred workflow you can change the actual timezones you want and the ordering.

Currently to make this work you need to include minutes as well not just have something like 4pm as this won't work with the current regex check.
