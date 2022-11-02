
  
  

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



# Benchmark of other's solution  
      
  
Sajib Hossain made quite a good job with his event-calendar demo case [GitHub - sajib1066/event-calendar: Django-based Event Calendar application.](https://github.com/sajib1066/event-calendar).
His chosen license was GPL3 which allows us to access and make trails.   
  
  >"sajib1066/event-calendar is licensed under the GNU General Public License v3.0"
  >[event-calendar/LICENSE at main · sajib1066/event-calendar · GitHub](https://github.com/sajib1066/event-calendar/blob/main/LICENSE)
  >### GNU General Public License v3.0
  >Permissions of this strong copyleft license are conditioned on making available complete source code of licensed works and modifications, which include larger works using a licensed work, under the same license. Copyright and license notices must be preserved. Contributors provide an express grant of patent rights.
  >  
  
Therefore we git cloned its works, all credit goes to him.   
Thx you [sajib1066 (Sajib Hossain) · GitHub](https://github.com/sajib1066)!  
  
  
  
  
## Trial of sajib1066's event-calendar  
  
The event model is a good start ;    
Sqlite is good to start with until we devise how to use workers locally against PostgreSQL API ORM and encrypt over different ORM's.   
We first use the Django embeded client which we will need to split apart later    
  
  
  
  
## How to install sajib's show case  
  
Following instructions have been tested on a windows system. It should be easy to adapt to Nix systems.  
  
1. Choose a local working dir on you PC  
2. `git clone https://github.com/dev-KC20/kp-wwaw-agenda.git
3. Create a virtual environment to isolate all dependencies  
   `python -m venv ENV  
   `ENV\Scripts\active  
4. go to try-sajib\event-calendar
   
  
## Credits and good reads.  

First not reinventing the wheel, just use it:  
  
[Django Packages : Calendar](https://djangopackages.org/grids/g/calendar/?python3=1)  
  
  
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
  

@Pascal_Fares  
[Github Organisation, teams, et projets agile en mode open source - YouTube](https://www.youtube.com/watch?v=in-zf9Hx3_k)
  

---

[Create Badges with GitHub Actions! | Simon Schneegans’ Blog](http://schneegans.github.io/tutorials/2022/04/18/badges)
