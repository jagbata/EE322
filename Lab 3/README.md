# This is Lab 3

A friend of mine told me that I should make a virtual environment because it is safer to download things into a virtual environment rather than changing your system settings
I did not know how to create a virtual environment *at all* let alone creating one using a terminal
I was able to research how to do that and all that stuff and I *think* it worked 

~~I found that there was a problem identifying the libraries even though they were installed. I will come back to this~~

I was able to do everything using ubuntu. This method creates an Ubuntu venv for windows and allows you to operate as if you were using Ubuntu

### What the Commands Do:
**python3 julian.py**

~~TBD~~

This prints the calendar date and then the Julian date. It also has a modified Julian Date that cut off the first two digits

***python3 date_example.py***

This prints the date in yyyy-mm-dd, then in mm-dd-yy. It says the day of the week, the month, the year and then what day it is relative to the start of the semester 
and the end of the semester

***python3 datetime_example.py***

This prints the time down to the millisecond twice, then it seems like it prints the time in UTC (it is 5 hours ahead of NYC time)
It then prints the time using Day of week Month day and the time. It prints the date in yyyy-mm-dd followed by the time. It then prints the UTC time in 
this same format


***python3 time_example.py***

This prints the time every 10 seconds (this never ends it seems... I ended this after 5 minutes)

***python3 sun.py 'New York'***

~~TBD~~

This gives info about the time zone, latitude and longitude. It also says when dawn started, the sunrise and noon (I'm guessing when the sun was highest over NY)

***python3 moon.py***
~~TBD~~

This lists the different moon phases

***python3 coordinates.py 'SC Williams Library'***

~~TBD~~
Tells you the location of SC Williams Library: its town, district, county, country and coordinates
This one is in Canada, that's interesting

***python3 address.py '40.74480675, -74.02532862031404'***

~~TBD~~

Finds what is located at those coordinates. This one is the library on our campus


***python3 cpu.py***

~~TBD~~

Tells you info about your cpu: how many cores, cpus and how much each cpu is being used

***python3 battery.py***

This tells you if you your laptop battery status: the percentage, *how long it it needs to finish charging?* and if it is plugged in 

***python3 documentstats.py document.txt***

Tells you how frequent words appear in the document and the frequency
