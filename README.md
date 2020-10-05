# **tech4u**

[tech4u](https://tech-4-u.herokuapp.com/)  This website is an tech E-Commerce website where users can buy different kind of smart devices and accessories.
Users can shop by making their own profile as well can shop anonymously without having to make a profile.  
Users can buy products instantly by selecting and adding products from the product page to shopping bag.
Users can make fully secure payment using stripe which is fully funtional and user recieve a confirmation e-mail with all the details including ordernumber. 
 
## Contents Table

1. [**UX**](#ux)
 - [**Project Purpose**](#project-purpose)
 - [**Design**](#design)
 - [**Wireframes**](#wireframes)

2. [**Features**](#features)
 - [**Existing Features**](#existing-features)
 - [**Features to implement**](#features-to-implement)

3. [**Technologies Used**](technologies-used)

4. [**Testing**](#testing)

5. [**Deployments**](#deployments)

6.  [**Credits**](#credits)
  - [**Contents**](#contents)
  - [**Images**](#images)
  - [**Help with code**](#help-with-code)
  - [**Acknowledgements**](#acknowledgements)

## Purpose
The purpose of the project is to build a django based full-stack site which is fully funtional and based around business logic with centrally controlled database.

The other main purposes were to allow user to search for the items with keyword and by categories as well and provide user a simple and easy way to naigate around the 

website so they can check all the products available and buy them with or without profile.

### Design

The design of the page is simple and easy to move around, it is intuitive as well as colours are light which improves user experience.

- #### Design layout

    - The Design layout of the whole project has been inspired by code institute boutique ado project as it is quite simple and easy to use.  

- #### Fonts
    
    - The font **'Roboto'** was used as it is simple and easy to read also it is commonly used on popular websites.

- #### Colours
    
    - The color scheme of the project is white, #555 grey and black
    
- #### Styling

    - styling of the app is also inspired by boutique ado project
    
- #### Website Pictures

The hero image on the home page has been taken from sublum template by colorlib and the product images has been taken from currys.co.uk website
    
### Wireframes

Wireframes were made using print screen.

## Features

### Existing Features

### Home page
Home page includes a nice and elegant backgroung image of Apple magic mouse with nice color combination and with new collection hero text and shop now button to help users
to check all the products available.

### Products page
Contains all the available products with different product categories
Product can be sort by: Category, Price, Rating and Name.

### Product Detail page
User can view the product detail, with description and rest of product info. 
Update quantity and "Add to bag" button available to add products to bag or continue shopping to go to all product page.

### Login / Register / Logout pages
Login page with option to register if someone is not a member yet, login and logout.

### Product Management
Admin and superuser allowed to add, edit, or delete products. If not loged in as user or admin not able to access this option.

### Profile page
If the user is logged in, there is a Profile page, where the user can check their order history.

### bag page
After a product is added to the bag, the user can view the containt of the bag here, update or delete products from the bag.
From here user can go to Checkout page to arrange card payment (Stripe), also login or sing up options available from this page.

### Checkout page
User will see a Form to fill in all details for Payment with card and Order History.
Options to go to payment or update bag in case user want to change/remove product or product quantity before complete order.

### Order confirmation
After payment user view a Thank you page with order confirmation and delivery information. Automatically user receive an email with purchase history.
Or continue shopping button option.

## User Experience
### User Stories:
 User:

* As a User, I want to be able to view the site on multiple devices. (mobile/tablet/desktop).
* As a user I would like to be able to search to a keyword and sort products by price, name, category, or rating in order to find what I need.
* As a user I would like to read more details about a product after clicking on it.
* As a user I would like to be able to find information about my previous orders.
* As a user I would like to be able to contact tech4u Shop with my questions.
* As a user I would like to be able to register on the site.
* As a user, I want to checkout using card payment.
* As a User, I want to recieve email confirmation with details of my purchase.
* As a User, I want to see products reviews

(Application Owner/Administrator):

* As a Admin , I want to I want to be able to login to an administration panel.
* As a Admin , I want to provide all the customers information they need online so that they do need to call and email.
* As a Admin , I want to easily take payment from customers
* As a Admin , I want to automatic email notifications for my customers
* As a Admin , I want to be able to add new retreats
* As a Admin , I want to be able to edit retreats
* As a Admin , I want to be able to add new yoga classes
* As a Admin , I want to be able to edit yoga classes

Registers (Logged in) User:

* As a Registered User, I want to have the ability to Login to the site via my registered details.
* As a Registered User, I want to create and edit a profile.
* As a Registered User, I want to be able to see my previous purchases
* As a Registered User, I want to be able to view my bag and any items I currently have awaiting payment in my bag.
* As a Registered User, I want to be able to items currently added to my bag.
* As a Registered User, I want to have the ability to Logout of the application.


### Languages:
* HTML5
* CSS3
* JavaScript
* Python 3.8

### Libraries, frameworks, tools used:
* Bootstrap 4 framework was used for developing a responsive, mobile-first website.
* Django 3.1 as python web framework used for rapid development, maintainable, clean design.
* jQuery JavaScript library to simplify HTML DOM manipulation.
* Google Fonts Used Noto Sans fonts.
* FontAwesome as icon provider.
* Stripe made it possible to receive payments.
* Psycopg2 as database adapter for the Python.
* Gunicorn or Green Unicorn, a WSGI server implementation used to run Python web application.
* Gitpod was used as a code editor.
* Git Version control.
* Github used as a Git repository hosting service.
* Heroku is a container-based cloud Platform, I used Heroku to deploy this app.
* Unsplash Used to find the background images and some products images.
* W3C Validator Used to check the validity of my HTML and CSS.
* PEP 8 Online Validator Used to check my Python code.
* Nicepage to create mockups.
* Compressjpg to compress all my images.
* AWS S3 Bucket as a cloud storage.
* Boto3 to make use of Amazon S3.
* Pillow for saving image file formats.
### Databases:
* PostgreSQL database service provided directly by Heroku.
* SQlite3 provided by Django.

## Testing
Testing has been carried out by using the app on different browser which includes Chrome , firefow , safari and internet explorer
the site has been tested on different smart devices as well which include samsung s80+ , iphone 11 and ipad pro

* Home page:
 Click on button **Shop Now**, goes to Product page, shows  Products, OK.

* Navigation:
Click on "logo": **tech4u Shop**, goes to home page. OK Search by keyword, trying **search** "tray", goes to products including "Tray" on description or name. OK
Click on **My Account**, opens **My Profile**, **Logout**, **Register** and **Login**. All links work. OK
Click on **Bag**, opens products in bag. If not products added to the bag, opens page to click on "Keep Shopping". OK
Click on **Products** opens search by: Price, Rating, Categotry. Click on each and all of them make a correct selection of products base on criteria. OK
Click on **Accessories** opens all accessories products 
Click on **Smart tech** opens all smart tech options and shows correct selection in all options. OK
Click on **Special offeres** opens up the whole product range. OK
Number of products found visible in all categories, OK.
Click on **Sorting by**: Price (low to high), Price (high to low), Rating (low to high) or (high to low) , Name (A-Z) or (Z-A), Category (A-Z) or (Z-A). Working Ok.
* **All Products**, shows all products (24 found). OK Including: Image, description, price, rating and category.
* Click on any product, opens **Product detail** to view more details about the product and option to **Add product** to bag or update quantity. OK.
Click on **Keep Shoping** goes to All products. OK

* Click on bag opens **Shoping bag** to view what we will buy, delivery cost included (10%) and if it is more than 50$ USD free. OK 
Possible to remove product or update quantity. OK
Click on Keep Shopping goes to All Products. OK
Click on **Secure Checkout** goes to:

* **Checkout Form** mandatory to fill in all details, if not meessage info. OK
  Checkbox to save profile from order working OK. 

  Click on **Update bag** goes back to Shopping bag.

  Click on **Complete Order** goes to checkout_success page, with Order Confirmnation and email send to the user. OK

  Click on **Continue Shopping** goes to All Products. OK
  Payment tested using card numbers:
    No authentication (default U.S. card): 4242 4242 4242 4242.
    Authentication required: 4000 0027 6000 3184.

* **My Profile**, opens order/delivery history. OK
Click on **Update information** to change profile records. OK

* Register, Login and Logout. Working with deficiencies. To fix in future.

* Email received with order confirmation and delivery info. OK.
* Pop up Alerts about different functions (suscess, info, error, alerts...) added and work properly. OK 

### Code Validation
CSS was validated using W3C CSS Validation Service.

HTML was validated using W3C Markup Validation Service.

Python code was validated using PEP8 online checker.

### Defensive design
Warning messages were used when user entered already taken username at registration, or wrong password/username when signing in.

## Deployment to Heroku

Steps to deploy to Heroku:
1.  Heroku.com click on New and Create new app.
2.  Named as: tech4u-shop. Region selected: Europe.
3.  In Resources tab, search and add Heroku Postgres. Select Hobby Dev (free)and click Provision.
4.  In Settings click on Reveal Config Vars and copied the value of DATABASE_URL in Gitpot setting.
5.  Back to Gitpod in the Terminal install dj_data_base_url and psycopg2-bunary, typing: pip3 install psycopg2-binary and pip3 install dj_database_url.
6.  Created a requirements.txt file using the terminal command pip3 freeze > requirements.txt. Make sure Heroku installs all our apps requirements checking requirements.txt file.
7.  Go to settings.py and add import dj_database_url and update DATABASES = {'default': dj_database_url.parse(os.environ.get('DATABASE_URL'))} in the database settings.
8.  Env.py update, os.environ.setdefault("DATABASE_URL", "postgres://postgres key -  from Heroku").
9.  Migrate all changes to Postgres database typing: python3 manage.py makemigrations and then python3 manage.py migrate.
10. In the Terminal, to load data categories use python3 manage.py loaddata categories and python3 manage.py loaddata products.
11. Create a super user: python3 manage.py createsuperuser. User name added, email and password.
12. Install unicorn typing: pip3 install gnicorn in the Terminal to act as webserver and freeze that into our requirements file typing: pip3 freeze > requirements.txt.
13. Create Procfile, insert: echo web: gunicorn ms4.wsgi:application.
14. Git add ., git commit and git push.

To connect AWS: 
1.  Log in to Amazon AWS, went to S3 and created a new S3 bucket (tech4u-shop)
2.  Returned to terminal window and run sudo pip3 install django-storages and pip3 install boto3. Went to settings.py and added storages to INSTALLED_APPS.
3.  Also in settings.py the following lines are added:

        AWS_STORAGE_BUCKET_NAME = 'tech4u-shop'
        AWS_S3_REGION_NAME = 'eu-west-1'
        AWS_ACCESS_KEY_ID = os.environ.get('AWS_ACCESS_KEY_ID')
        AWS_SECRET_ACCESS_KEY = os.environ.get('AWS_SECRET_ACCESS_KEY')
        AWS_S3_CUSTOM_DOMAIN = f'{AWS_STORAGE_BUCKET_NAME}.s3.amazonaws.com'
    
        # Static and media files
        STATICFILES_STORAGE = 'custom_storages.StaticStorage'
        STATICFILES_LOCATION = 'static'
        DEFAULT_FILE_STORAGE = 'custom_storages.MediaStorage'
        AWS_DEFAULT_ACL = None
        MEDIAFILES_LOCATION = 'media'
    
        # Override static and media URLs in production
        STATIC_URL = f'https://{AWS_S3_CUSTOM_DOMAIN}/{STATICFILES_LOCATION}/'
        MEDIA_URL = f'https://{AWS_S3_CUSTOM_DOMAIN}/{MEDIAFILES_LOCATION}/'
    
4.  Update env.py with AWS keys (these keys are from S3).
5.  Create custom_storages.py at the top level:
6.  Returned to terminal window and run python3 manage.py collectstatic
7.  Returned to Heroku. In Settings clicked on Reveal Config Vars button, and added all the following config vars from env.py:

![Heroku Config Var](/media/HerokuConfigVar.PNG)

8. Git push Heroku master to finish and deploy to Heroku.
9. Clicked to Deploy tab, then GitHub, searched for my repository and clicked to Connect button.
Heroku will be updated automatically from Github repository.

#### As summary:
 + My up
   1. requirements.txt
   2. Procfile
   3. DB Connection
   4. S3 Connection
   5. Environment Variables
   6. Github
+ Heroku
   1. Database
   2. Config Vars (Environment Variables)
   3. Deploy (Github)
+ AWS
   1. S3 Buckets
   2. IAM (Security)
