﻿# Date.IsLeapYear
Indicates whether this date falls in a leap year.
***
function (optional dateTime as nullable any) as nullable any
***
# Descrition 
Indicates whether the given datetime value <code>dateTime</code> falls in is a leap year. 
 <ul>
        <li><code>dateTime</code>: A <code>date</code>, <code>datetime</code>, or <code>datetimezone</code> value to be evaluated.</li>        
      </ul>
# Category 
Date
# Examples 
Determine if the year 2012, as represented by <code>#date(2012, 01, 01)</code> is a leap year.
```
Date.IsLeapYear(#date(2012, 01, 01))
```
> true
***