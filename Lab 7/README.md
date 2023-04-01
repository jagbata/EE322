# Lab 7

Today we are doing Lab 7 in class. Before following along, I decided to fix the naming convention of my Labs in my repository. 
I made it so that the Lab contents were all in a *README.md* file so that they could display more easily.

First we had to sign up for **ThingSpeak**

I was unable to finish the lab in class, but I am resuming it now.

I went to the **ThingSpeak** and created the channel like I was supposed to
I copied the files and ran the *cat thingspeak_cpu_loop.py* command. The *cat* command was a type of command I hadn't seen before but it just displays the content of that file:
<img width="462" alt="image" src="https://user-images.githubusercontent.com/98117974/227787706-fb067a5e-9abb-4db0-873d-356b75b4a2bc.png">

I ran the *cat thingspeak_feed.py* command and got a similar result, but for the thingspeak_feed.py file instead 

I did not run the *python3 thingspeak_feed.py* command b/c while doing another unrelated project, I found that using **python3** generates errors with libraries and modules. The solution to this problem is simply running the same command using **py** instead of **python3**

In other projects I used my ubuntu terminal to get around this problem, but now I can stay in my Windows terminal and use **py** from now on :)

So I ran the *__py__ thingspeak_feed.py* command and was asked to enter my API key which I did

The terminal displays some info about your computer, the date and time and the repeats this every 60s.

It took me a little time to figure out how do the next part of the lab but I was able to successfully find where to enable the required APIs. 

I had to create a new [Service Account](https://console.cloud.google.com/iam-admin/serviceaccounts?project=cpudata-381816) in order to download the json file

I ran into some errors running the file, I am not sure if I didn't properly input info or something

### 4/1/23
I have revisited this lab after discussing with Professor Lu.

I created a venv so that things can run more smoothly. When I had first read the instruction saying to delete rows 2-1000, I thought it just meant to make sure they were empty.

I properly deleted them and then moved on to the next step. 

The next step was making sure that the *cpu_data.json* file was in the correct location, and after I moved it to the correct location, I also needed to change the *cpu_spreadsheet.py* file to reflect my personal json file.

I had to change the highlighted part in [this](https://github.com/jagbata/EE322/blob/main/Lab%207/cpu_spreadsheet_editing.jpg) image

Next I was able to check my [cpudata Sheets](https://docs.google.com/spreadsheets/d/1k7JH-SSujQpUDKhCvOUAEZ3F_bLpLCOzcXtoilOxX9o/edit?usp=sharing)  to see that it worked properly
