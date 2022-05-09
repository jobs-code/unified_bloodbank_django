# unified_bloodbank_django
unified bloodbank webapp using django
as final project in Future Reday talent Virtual internship
project demo video:
https://www.loom.com/share/8914dd82cce34fadb24c4372aae8330d

## Services used
Azure SQLServer
Azure Sql Database
Azure app service (for hosting)
Azure bot service(for bot)
Azure LUIS(language understand)
Azure QnA maker

## Unified-Blood-Bank-Management-System


### Walk through the web app
Homepage
![image](https://user-images.githubusercontent.com/39452651/167288621-d187d47a-1d66-485b-ad84-58c31a5b105e.png)
Walkthrough the nav panel
## About
info about blood donation
![image](https://user-images.githubusercontent.com/39452651/167288703-4f93906f-c12f-494e-8703-c824e35a446b.png)

## Donor Registration
Where users register new donors
![image](https://user-images.githubusercontent.com/39452651/167288743-1c7bb552-b4b3-4557-a5ce-862214b23e9f.png)

## Search
Here we can search for nearby donors by select blood group place and city
![image](https://user-images.githubusercontent.com/39452651/167288815-d41426fc-67a5-48d8-8619-b241c0c3e0a4.png)

## Login
For admin and hospitals
![image](https://user-images.githubusercontent.com/39452651/167288839-2b675bbe-0fdc-488f-b157-f9d25fdb4738.png)
![image](https://user-images.githubusercontent.com/39452651/167288873-36c96f02-dec2-437f-8f6b-3d2fd64fc9fd.png)
add delete datas,users and groups

## Contact
to reach out 
![image](https://user-images.githubusercontent.com/39452651/167288909-42f3f466-34ac-4151-9e9e-5762efa5ab6d.png)

## UBBOT
Bot that clarify all blood donation related queries.
![image](https://user-images.githubusercontent.com/39452651/167288953-27ecc350-245d-4a69-98fc-7aa48e67b549.png)

Admin credentials 
user:admin
pass:admin@root

### How to run a App manually

### Create a virtual environment 

Download python & pip

### download requirement file

```$ pip install -r requirement.txt```

then 

```$ python manage.py migrate```

```$ python manage.py createsuperuser```

### start the app

```$ python manage.py runserver```

Open browser, <http://localhost:8000>

### stop the app

           Ctrl+C

