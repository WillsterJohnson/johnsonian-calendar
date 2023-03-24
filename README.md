# Johnsonian Calendar #

***THIS SPECIFICATION IS A DRAFT AND MUST NOT BE USED OR IMPLEMENTED UNTIL IT IS FINALIZED***

*What if our calendar was based on good scheduling and math instead of religion and (loosely) the moon?*

Author: Will 'Willster' Johnson
Date: 2022-12-14

## Overview ##

The Gregorian calendar the majority of the world uses today is fundamentally broken. The weeks don't work well for our work and education, the months are all different lengths, and the first of January is utterly arbitrary.

The Johnsonian calendar fixes all of these issues while remaining close enough to the Gregorian calendar for the average person to be able to switch from the latter to the former with as little trouble as possible.

## Context ##

The Gregorian calendar has many issues. A new dating system is necessary for a better and fairer world.

The Gregorian calendar's biggest issue is the length of the week. Seven days is simply a terrible number to use, it's a large and prime number which does not divide well into work and rest periods that humans can use to get the most productivity out of the fewest days of work. In our current five on two off system, our productivity is drastically reduced before Wednesday is over, and we're barely recovered on Sunday night and have spent the day under the looming shadow of the Monday to come.

The next problem is the months. Twelve does not divide neatly into 365 so we have months of different lengths, except the distribution of days is incredibly arbitrary, with February having 28 or 29 days and the other months having either 30 or 31 with no pattern or sensible reasoning for the distribution. On top of this, the names of four of the months are made simply incorrect due to "**Sept**ember" not being the **Seventh** month of the year and so on for the rest of the year, entirely due to the ego of dead emperors from millenia age.

Finally the placement of the start of the year is completely arbitrary and the particular day has no special meaning nor events beyond the ones given to it precisely for being the first day of the year. It falls painfully close to the winter solstice but stubbornly sets itself a week and a half after it.

## Goals and Non-Goals ##

The goal of the Johnsonian calendar is to provide a methodology for segmenting the Solar year into groups of days which prioritises the productivity and wellbeing of humans while staying in line with defining events of the Solar year and reasonable math with as few exceptions as possible.

The Johnsonian calendar will not be addressing the messy radix of time keeping, though there is an equally detailed and frustated paper I will be publishing as an ammendment which will aim to fix the awful mistake that is our current system of time.

## Proposed Solution ##

A Solar year is 365 days long, with every fourth year being 366 days long to accomodate the offset between the Earth's rotation and the Earth's orbit (with the exception that every 100th year is 365 days long, and every 400th year is again 366 days long).
365 has only two factors aside from itself and one; five and 73. It makes sense if we want to divide the year into equal blocks, we should have either five blocks of 73 days, or 73 blocks of five days. As 73 is quite a large number to count to each block, 73 blocks of five days is the more reasonable approach.
This gives us five day weeks, of which there are precisely 73 per year. This means the weekdays will be the exact same day of the year every year. Except for leap years, which threaten to ruin the uniform system.
To fix this, on a leap year the 73rd (final) week of the year is given an additional sixth day.

Any date system needs a concise way to write dates, using phrases like "the third day of the fifty-third week" is too long.
The Johnsonian calendar uses the following format for it's dates;

```
YYYYwNNz
```

Where `YYYY` is the year, `NN` is the week number, and `z` is the day's letter. This format borrows from other systems which use a similar written system to track days.
For example, the third day of the 53rd week in 1999 would be written as;

```
1999w53c
```

The day of the week is determined by 1=a, 2=b, 3=c, 4=d, 5=e. For the final week of a leap year which has a sixth day, that sixth day is determined by continuing the pattern; 6=f.
For example, the last day of the year 2000 would be written as;

```
2000w73f
```

The year may also be written in short form.
For example the first day of the 17th week of 2012 may be written as;

```
12w17a
```

The day may be written in short form if it is one digit (you may use "1" instead of "01") however this is ill advised as it unnecessarily makes reading the date more difficult and only saves a single character.
For example, the latter of the following pair ensures consistency throughout the year, and is easier to read;

```
12w1a
12w01a
```

The first day of the year, w01a, is defined as the day after the Winter Solstice in the Northern Hemisphere. The immediate issue here is that the solstice drifts somewhat year-on-year, being either a day earlier or a day later on occasion. For this reason, the definition of "Winter Solstice in the Northern Hemisphere" that the Johnsonian calendar uses is whichever day the astronomically defined Winter Solstice in the Northern Hemisphere most often lands on in the century surrounding the current year. Under this definition, the Winter solstice lands on the equivalent of the 21st of December in all years of the 21st century.

For example, the 22nd of December, 1995, would become the first day of the first week, 1996. Using the standard notation;

```
1995-12-22
1996w01a
```

The division of the working week for maximum productivity for minimum working days is to work three on two off.
The calculations for average working days per year are shown below for several systems;

| System         | Avg Days Worked / Year |
|:--------------:|:----------------------:|
| Gregorian 5/2  | 260.89                 |
| Gregorian 4/3  | 208.71                 |
| Johnsonian 3/2 | 219.15                 |

The Johnsonian three on two off system has about 40 fewer working days (320 fewer hours at 8hrs/day) than the traditional Gregorian five on two off system, however only 11 days more (88 more hours at 8hrs/day) than the Gregorian four on three off system, which has been of interest in 2022 for showing greater productivity than the traditional Gregorian five on two off system in recent limited studies.
There are more factors at play in the productivity of a given work system than can be reasonably put into any form of equation, however given that people who work a traditional Gregorian five on two off week often feel that by the third day they're starting to lose motivation, and that a closer ratio of work to rest has shown an improvement in overall productivity, it's likely that the Johnsonian three on two off system will be better than the tradtional Gregorian five on two off system.
