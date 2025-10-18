

**Brooj study™**



The project is for all those who need to study but dont know the right method: the project makes use of javascript and python to help schools,tution groups, and univercitys to colaborate. 
**Decleration**
This LMS does not conflict with anyother cs50 project and uses Django Extensions, Python Extensions and More than 60% CSS is from bootstrap and 40% is custom, All images execpt BroojStudy™ Logos's are non copywrighted images taken from the internet and from sites like(freepik, pinterest, Google images etc)
## Functions of this LMS
**Distinctiveness and Complexity**
##Why this project is distinctive and complex
1. As this is the only django LMS that contains communicational feutures 
2. As this project is one of the most secure LMS's in the world using more than 100k+ Bits encryption keys with over 200 different content ports regulators 
3. This project provides student and staff management 
4. This Project makes use of off-page javascript snippets for faster loading
5. This Project makes use of G-zip compression to put less strain on the server and allow more users to interact with the site at once
6. This Project makes use of Google Recaptcha to stop bots from putting strain on the server
7. This project makes use of Off-page css to help save space and storage
**Page Functions** 
###The main content pages can be found in Main_app/templates while images and css can be found in the static folder
##In the Folder main_app you will find the:
1.Base.html which is used as the header file
2.Footer.html is the file containing end scripts and trademarks
3.form_template.html is the file containg a general page used for forms
4.index.html is the main landing page and is the one which contains links to other pages
5. sidebar_template.html(bootstrap) is the sidebar of the main site
##In the Registration folder youll find pages for user amineties (eg password change)
##In the next 2 folds youll find pages for the staff and students 
### A. Admin Users Can
1. See Overall Summary Charts of Students Performances, Staff Performances, Courses, Subjects, Leave, etc.
2. Manage Staff (Add, Update and Delete)
3. Manage Students (Add, Update and Delete)
4. Manage Course (Add, Update and Delete)
5. Manage Subjects (Add, Update and Delete)
6. Manage Sessions (Add, Update and Delete)
7. View Student Attendance
8. Review and Reply Student/Staff Feedback
9. Review (Approve/Reject) Student/Staff Leave
10.Delete/Edit 

### B. Staff/Teachers Can
1. See the Overall Summary Charts related to their students, their subjects, leave status, etc.
2. Take/Update Students Attendance
3. Add/Update Result
4. Apply for Leave
5. Email each other

### C. Students Can
1. See the Overall Summary Charts related to their attendance, their subjects, leave status, etc.
2. View Attendance
3. View Result
4. Apply for Leave
5. Email each other and staff for help 







## HOW TO RUN THIS PROJECT

### What you will need:
1. Install Python Latest Version
[ https://www.python.org/downloads/ ]

2. Install Pip (Package Manager)
[ https://pip.pypa.io/en/stable/installing/ ]


### Installation
**1. Create a Folder where you want to save the project**

**2. Create a Virtual Environment and Activate**

Install Virtual Environment First
```
$  pip install virtualenv
```

Create Virtual Environment

For Windows
```
$  python -m venv venv
```
For Mac
```
$  python3 -m venv venv
```
For Linux
```
$  virtualenv .
```

Activate Virtual Environment

For Windows
```
$  source venv/scripts/activate
```

For Mac
```
$  source venv/bin/activate
```

For Linux
```
$  source bin/activate
```

**3. Download this project**
```
Go to the repo's menu and download az zip

```
```
Un zip it in files explorer
```
Then, Enter the project
```
$  cd akbarstudy
```

**4. Install Requirements from 'requirements.txt'**
```python
$  pip3 install -r requirements.txt
```other wise 
download asgiref==3.5.2
beautifulsoup4==4.11.1
captcha==0.4
certifi==2022.12.7
charset-normalizer==2.1.1
dj-database-url==1.2.0
Django==4.1.4
django-cors-headers==3.13.0
django-environ==0.9.0
django-recaptcha==3.0.0
google==3.0.0
idna==3.4
Pillow==9.3.0
requests==2.28.1
soupsieve==2.3.2.post1
sqlparse==0.4.3
tzdata==2022.7
urllib3==1.26.13
UserManager==0.5.3
whitenoise==6.2.0
```
```

**5. Add the hosts**

- Got to settings.py file 
- Then, On allowed hosts, Use **[]** as your host. 
```python
ALLOWED_HOSTS = []
```
*Do not use the fault allowed settings in this repo. It has security risk!*


**6. Now Run Server**

Command for PC:
```python
$ python manage.py migrate
```
```python
$ python manage.py runserver
```

Command for Mac:
```python
$ python3 manage.py runserver
```

Command for Linux:
```python
$ python3 manage.py runserver
```

**7. Make A superuser**

Create Super User (HOD)
Command for PC:
```
$  python manage.py createsuperuser
```

Command for Mac:
```
$  python3 manage.py createsuperuser
```

Command for Linux:
```
$  python3 manage.py createsuperuser
```




Then Add Email and Password to the given feilds
**8. Google Recaptha**
Even though my captha key is still installed its only for localhost, if you intend to use this project then it would be recomended if you put your own in views.py aswell as login.html
**9. Build your profile**
Now you need to goto the sidebar and select profile in there you need to add your photo, information(name etc) and locatation 



Copywright 2022-current Qamar Muneer Akbar & Harvards CS50 capstone ALL WRIGHTS RESERVED
Aurthor of code : Qamar Muneer Akbar
Packages used: 
asgiref==3.5.2
beautifulsoup4==4.11.1
captcha==0.4
certifi==2022.12.7
charset-normalizer==2.1.1
dj-database-url==1.2.0
Django==4.1.4
django-cors-headers==3.13.0
django-environ==0.9.0
django-recaptcha==3.0.0
google==3.0.0
idna==3.4
Pillow==9.3.0
requests==2.28.1
soupsieve==2.3.2.post1
sqlparse==0.4.3
tzdata==2022.7
urllib3==1.26.13
UserManager==0.5.3
whitenoise==6.2.0
bootstrap™
