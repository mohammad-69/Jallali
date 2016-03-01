# Jalaali Swift 2.1

A few Swift functions for converting Jalaali (Jalali, Persian, Khayyami, Khorshidi, Shamsi) and Gregorian calendar systems to each other.

## About

Jalali calendar is a solar calendar that was used in Persia, variants of which today are still in use in Iran as well as Afghanistan. [Read more on Wikipedia](http://en.wikipedia.org/wiki/Jalali_calendar) or see [Calendar Converter](http://www.fourmilab.ch/documents/calendar/).

Calendar conversion is based on the [algorithm provided by Kazimierz M. Borkowski](http://www.astro.uni.torun.pl/~kb/Papers/EMP/PersianC-EMP.htm) and has a very good performance.

This Code Is Swift 2.1 version of jallali converter.
## Install

TODO

## API

## Quick Use Or Test functionality 
let Date = String(toJalaali(GregYear!, gm: GregMonth!, gd: GregDay!))


### typealias JalaaliYear = Int

An Int representing a Jalaali year.


### typealias JalaaliMonth = Int

An Int representing a Jalaali month (1-based).


### typealias JalaaliDay = Int

An Int representing a Jalaali day.


### typealias GregorianYear = Int

An Int representing a Gregorian year.


### typealias GregorianMonth = Int

An Int representing a Gregorian month (1-based).


### typealias GregorianDay = Int

An Int representing a Gregorian day.


### typealias JulianDayNumber = Int

An Int representing a Julian Day Number


### typealias JalaaliDate = (year: JalaaliYear, month: JalaaliMonth, day: JalaaliDay)

A tuple for a Jalaali date.


### typealias GregorianDate = (year: GregorianYear, month: GregorianMonth, day: GregorianDay)

A tuple for a Gregorian date.


### func toJalaali(gy: GregorianYear)(gm: GregorianMonth)(gd: GregorianDay) -> JalaaliDate
### func toJalaali(gy: GregorianYear, gm: GregorianMonth, gd: GregorianDay) -> JalaaliDate

Converts a Gregorian date to Jalaali.


### func toGregorian(jy: JalaaliYear)(jm: JalaaliMonth)(jd: JalaaliDay) -> GregorianDate
### func toGregorian(jy: JalaaliYear, jm: JalaaliMonth, jd: JalaaliDay) -> GregorianDate

Converts a Jalaali date to Gregorian.


### func isValidJalaaliDate(jy: JalaaliYear)(jm: JalaaliMonth)(jd: JalaaliDay) -> Bool
### func isValidJalaaliDate(jy: JalaaliYear, jm: JalaaliMonth, jd: JalaaliDay) -> Bool

Checks whether a Jalaali date is valid or not.


### func isLeapJalaaliYear(jy: JalaaliYear) -> Bool {

Is this a leap year or not?


### func lastDayOfJalaaliMonth(jy: JalaaliYear)(jm: JalaaliMonth) -> JalaaliDay
### func lastDayOfJalaaliMonth(jy: JalaaliYear, jm: JalaaliMonth) -> JalaaliDay

Number of days in a given month in a Jalaali year.


## License

MIT
