
  
  

# kp-p14 Design and make a Calendar App
  

    
## Disclaimer
  
---
  
  
** Not to be used for production yet **  
  
---
  
## Introduction  
  
...
  
  
After these few months learning Python and Django with Openclassrooms, it is time to put all my learnings into an actual working Django app.  
  
When time came to choose a side-project, I dreamed a few unfeasable ideas for the 'App' but definitevely not worth increasing the climate burden to poor Earth.  
  

We're, like many others a spread over family, across regions, across countries and each travelling back and forth.   

  
So grow the idea of sharing together in a secure way where we are what we do even sometimes letting he, her ,they join in.  
  
Privacy is sensitive so we couldn't 'just' use a shared agenda hosted by one of big [`FAANG`/`NATU`/`BHATX`/`YVMOR`](https://en.wikipedia.org/wiki/Big_Tech) ; Nothing against theses services but not to be used for where-we-are-when and what-we-do.  

It seems a solution to have part of the data encrypted when hosted while decrypted only by certified back and front-end apps are accessing it.

So first step is to gather ideas on possible app usage, other's open source projects and investigate coding tools and solutions.

Next wwould be to define a scope for the solution, write down and share use cases. 

Designing the architecture relevant to the use case and no budget scope comes after.  
  
Eventually, the coding may start...  
until the first P.R ;-)  
  
  
**Having fun, Devs!**  
  
  
  
The project is intented to be open source, shared with anyone (check the `AGPLv3`, [wanted a copyleft one including hosted services](https://opensource.org/faq#which-license)).   
  
  

---
  
 
## Security and privacy  
    
We do take your privacy and your data safety very seriously. 
We intend to set several security measures to ensure nothing bad may happen to your data.  
  
All technical operations are logged and help us to prevent and identify any mis-behavior or attacks
Finally the code itself is secured by reducing the exposure of secrets to public repositories,   
  
MFA, encrypt  

----  



## Review of other Agenda solutions
      
  
Sajib Hossain made quite a good job with his event-calendar demo case [GitHub - sajib1066/event-calendar: Django-based Event Calendar application.](https://github.com/sajib1066/event-calendar).
His chosen license was GPL3 which allows us to access and make trails.   
  
  >"sajib1066/event-calendar is licensed under the GNU General Public License v3.0"
  >[event-calendar/LICENSE at main · sajib1066/event-calendar · GitHub](https://github.com/sajib1066/event-calendar/blob/main/LICENSE)
  >### GNU General Public License v3.0
  >Permissions of this strong copyleft license are conditioned on making available complete source code of licensed works and modifications, which include larger works using a licensed work, under the same license. Copyright and license notices must be preserved. Contributors provide an express grant of patent rights.
  >  
  

Therefore it could be possible to use his work.
All credits would thrn go to him, in any case Thank you [sajib1066 (Sajib Hossain) · GitHub](https://github.com/sajib1066)!  
  
  
## Why would we investigate sajib1066's event-calendar  
  
Its value for us would not be his data model but saving the tedious work of building a nice user interface for the event, daily, weekly or monthly views of the events.
Sqlite is good to start with like he did until we find out how to use workers locally against PostgreSQL API ORM. We shall also remember the encryption feature heavier to implement with different ORM.   
  
  
## How to install sajib's show case  
  
His instructions & solution have been tested on a windows system. It should be easy to adapt to Nix systems.  
  
Just follow this copy of Sajib's original instructions. It is hereunder available at try-sajib\event-calendar\README.md under the branch try-sajib.
  

# Other possible solutions to be checked

* [GitHub - linuxsoftware/ls.joyous: A calendar application for Wagtail](https://github.com/linuxsoftware/ls.joyous)
* nothing since 2019-09-01: [Files · master · Daniel F Meyer / wagtail_eventcalendar · GitLab](https://gitlab.com/dfmeyer/wagtail_eventcalendar/-/tree/master)
* a new version (relying on jquery) is available under develop branch: [GitHub - llazzaro/django-scheduler: A calendaring app for Django.](https://github.com/llazzaro/django-scheduler/tree/develop)
* nothing since 2018-05-16: [GitHub - Gagaro/wagtail-calendar: A planning calendar for wagtail](https://github.com/Gagaro/wagtail-calendar)
* about 1 year ago: [SebGen / Wagtail Agenda · GitLab](https://framagit.org/SebGen/wagtail-agenda) 
* about 1 year ago: [Alan Trick / django-agenda · GitLab](https://gitlab.com/alantrick/django-agenda)




# Credits and good reads.  

[How to enable appointment scheduling for your website or app](https://yalantis.com/blog/appointment-schedule/)
@Victor_Osadchiy

[Building an Appointment Scheduler App with Django and Fauna - DEV Community](https://dev.to/chukslord1/building-an-appointment-scheduler-app-with-django-and-fauna-2n9o)
@Chukslord


[Building an Appointment Scheduler App with Django and Fauna - DEV Community](https://dev.to/chukslord1/building-an-appointment-scheduler-app-with-django-and-fauna-2n9o)


[A Quick Overview — DjangoSchedule 1.0 documentation](https://django-scheduler.readthedocs.io/en/latest/overview.html)

[Make your complex scheduling simple with timeboard, a Python library](https://www.freecodecamp.org/news/introducing-timeboard-a-python-business-calendar-package-a2335898c697/)
@Maxim_Mamaev

[georgemarshall/django-cryptography: Easily encrypt data in Django](https://github.com/georgemarshall/django-cryptography)  
  
[How To Encrypt And Decrypt Password In Django - Python Guides](https://pythonguides.com/encrypt-and-decrypt-password-in-django/)  

   
[Using custom model fields to encrypt and decrypt data in Django | by Alfred Yang | finnovate.io | Medium](https://medium.com/finnovate-io/using-custom-model-fields-to-encrypt-and-decrypt-data-in-django-8255a4960b72)
@Alfred_Yang and @David_Petrosyan   
  

---

