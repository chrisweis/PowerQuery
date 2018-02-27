﻿# DateTime.IsInPreviousMinute
Indicates whether this datetime occurs during the previous minute, as determined by the current date and time on the system.
***
function (optional dateTime as nullable any) as nullable any
***
# Descrition 
Indicates whether the given datetime value <code>dateTime</code> occurs during the previous minute, as determined by the current date and time on the system.
      <ul>
      <li><code>dateTime</code>: A <code>datetime</code>, or <code>datetimezone</code> value to be evaluated.</li>
      </ul>
# Category 
DateTime
# Examples 
Determine if the minute before the current system time is in the previous minute.
```
DateTime.IsInPreviousMinute(DateTime.FixedLocalNow() - #duration(0,0,1,0))
```
> true
***