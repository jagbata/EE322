# Lab 4

In this lab I attempted to complete the Django installation process.

I went to [Django Tutorial](https://docs.djangoproject.com/en/1.8/howto/windows/#:~:text=Django%20can%20be%20installed%20easily,version%20in%20the%20command%20prompt.)
in order to learn how to properly download the program. 

I had to do the same for the [Django Rest](https://www.django-rest-framework.org/) installation. The step that said to add 'rest framework' to INSTALLED APPS gave me some trouble
because I did not know what this meant. Looking through the files that were in the project, I found one called *settings.py* 

I realized that I could open this using nano, so that is what I did. After opening the file, I added what I needed to.
A similar process was neccessary for the *urls.py* file. 

The **stevens** project was successfully created after following the steps, but I came across a problem when I tried to view the website.

The website said that there was no location data. After looking further into this, I found that I needed to add a **Google Maps API** (or something of the sort).

I tried to find my API key, but it said I needed to add my *Billing Account Info*. I was relectant to do this but finally caved, after which the Billing Account refused to accept my information.

At that point I decided to stop the project and try again later
