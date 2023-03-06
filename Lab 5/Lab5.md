# Lab 5

I have decided to do this project using my ubuntu terminal I spent a lot of time downloading it, so I *might as well* use it.
Plus I had very few issues when I started using it, compared to my windows terminals, but maybe I am just making mistakes

~~I just jinxed myself b/c I've been trying to set up mqtt for an hour and a half now with little success. I will come back~~

I am back now, and I saw that I had to install it using windows b/c the ubuntu virtual environment that I was using did not have the required permissions needed to run mosquitto correctly.

I have downloaded it, and after trying to follow the instructions in the GitHub, I see that for windows are slightly different.

For example, I have to run *mosquitto_sub.exe* in order to subscribe and *mosqutto_pub.exe* to publish.

Here is a pic of me getting it to work:

<img width="491" alt="image" src="https://user-images.githubusercontent.com/98117974/223190703-30b6a51d-647f-480b-baec-8a2308eef6b9.png">

I have determined that the issue I have been previously having is that my windows terminal does not properly install or identify libraries, so for the paho part I went to ubuntu 

**pubcpu.py** publishes the date, time and cpu usage
**subcpu.py** receives this data and displays it:

<img width="373" alt="image" src="https://user-images.githubusercontent.com/98117974/223191793-e47d1f59-9718-4f34-81cb-d78bded76b2a.png">

That is all for this lab

