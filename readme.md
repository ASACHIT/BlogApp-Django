
# Blog Web app

A simple and complete webapp where user can create blog, create profile, update profile. & Admin can reviews blogs, approve , decline blogs. it also has Custom admin panel for admin and many more 


## Home page

![image](https://user-images.githubusercontent.com/73944456/161982121-d54c5b89-3f38-4daa-87e4-2c40e81b0eaf.png)
## Register User Page
![image](https://user-images.githubusercontent.com/73944456/161988259-bc4cad09-6686-4e3c-b6d8-278a3e042978.png)
## Updating User Profile Page
![image](https://user-images.githubusercontent.com/73944456/161988507-a4d12aec-ae08-4932-ab93-196f2dd8f066.png)

## Login page

![image](https://user-images.githubusercontent.com/73944456/161982347-c8bdecc8-cdd3-4391-8c1b-3eb69e233aee.png)

## Creating Blog Page
![image](https://user-images.githubusercontent.com/73944456/161982649-a1794465-f279-4185-8c63-ea7f0ba70bd0.png)

## Custom Admin Panel
![image](https://user-images.githubusercontent.com/73944456/161983228-2f828360-f102-4d18-9c22-2cd01439824e.png)

## Admin: Review Pending BLog
![image](https://user-images.githubusercontent.com/73944456/161984274-670d5d20-4086-4401-ae0e-14472462eb39.png)

## Admin:Blog Deleting Page
![image](https://user-images.githubusercontent.com/73944456/161984392-52fb5f23-1b09-4c3c-b859-64e6bf01bd7c.png)

## Email Verification things...
### verification mail
![image](https://user-images.githubusercontent.com/73944456/161986991-2a0cdf55-4eeb-43a2-a6e7-0a747740557a.png)
## User Verification: verification successfull
![image](https://user-images.githubusercontent.com/73944456/161987487-bc0cc4c0-5ca9-413a-b3f7-a160e6896b8b.png)
## User verification: invalid link or link already expired
![image](https://user-images.githubusercontent.com/73944456/161987591-adb0eef6-4164-44fd-976a-9a7bb681c88f.png)
## User Verification: Requesting New Verification link
![image](https://user-images.githubusercontent.com/73944456/161987830-20d33ddf-02fa-4d7c-8b21-4e38ec99a082.png)



## Installation

```bash
  git clone https://github.com/ASACHIT/BlogApp-Django.git
  cd BlogApp-Django
  pip install -r requirements.txt
  python manage.py runserver   
```
## creating a admin user

```bash
    python manage.py createsuperuser
    # input info and done
    #current admin mail:sachit@gmail.com, password:sachit   (fake mail)

 ```


## Things i learnt after creating this project

- CRUD functions on blog
- django message or notification and showing pop messages
- how authentication works, user login, logout etc
- different UI for admin and non admin user
- custom user model
- Adding Rich text editor in admin panel and frontend for creating blog
- creating a profile of user and feature to update it by same user
- proper user verification system (verifying user)
- and many more small things

