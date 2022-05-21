# unified_bloodbank_django
unified bloodbank webapp using django

# project deploying and demo video:
https://youtu.be/_FhCsv8jAPE

## Services used
Azure SQLServer
Azure Sql Database
Azure app service (for hosting)
Azure bot service(for bot)
Azure LUIS(language understand)
Azure QnA maker

## Unified-Blood-Bank-Management-System
## Website deployment details
In azure create resource group for webapp deployment 
![image](https://user-images.githubusercontent.com/39452651/168438978-5a750c7f-082f-4713-a2a0-cd3381ddf9cc.png)
(Here i created azure app service and azure sql server and database for storing data)

after creating the resources go to the app service and select deployment center and login with github and select the project repo to deploy.
![image](https://user-images.githubusercontent.com/39452651/168439122-050a4554-c7bd-4275-b55a-462502969c4d.png)
(It will create new workflow file and start deploying)

After deployment change the database credentials for that go to azure sql database that created before and get the ip , port , username & password change it in your source code.
![image](https://user-images.githubusercontent.com/39452651/168439253-0d737be5-4bbc-4c23-8777-a7c6c4db6c3c.png)

test the web app by clicking on browse button in app service.
### for bot deployment create bot in bot framework composer
create bot in bot framework composer and sigin with you azure account and create profile for deploying
![image](https://user-images.githubusercontent.com/39452651/168439319-ed3a0596-ffe9-4051-9965-6632919310fe.png)
then you can directly deploy the bot to azure and deployment get the secret key and embed code to integrate bot into our app for that locate to the channels section select web chat there you can see the secret also add that into your source code.
![image](https://user-images.githubusercontent.com/39452651/168439464-e9f11f81-11ac-47a6-a29c-a4baf472203b.png)

That's how you can deploy and integrate your web app in microsoft azure

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


