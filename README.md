# **tech4u**

[tech4u](https://tech-4-u.herokuapp.com/)  This website is an tech E-Commerce website where users can buy different kind of smart devices and accessories.
Users can shop by making their own profile as well can shop anonymously without having to make a profile.  
Users can buy thing instansly with adding and buy them direct from the shopping bag and user recieve a confirmation e-mail as soon as user make a purchase.
Users can make fully secure payment using stripe which fully funtional and user recieve a confirmation e-mail with all the details including ordernumber. 
 
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

##User Experience
###User Stories:
Generic (Guest/Public) User:

* As a User, I want to be able to view the site on multiple devices. (mobile/tablet/desktop).
* As a user I would like to be able to search to a keyword and sort products by price, name, category, or rating in order to find what I need.
* As a user I would like to read more details about a product after clicking on it.
* As a user I would like to be able to find information about my previous orders.
* As a user I would like to be able to contact tech4u Shop with my questions.
* As a user I would like to be able to register on the site.
* As a user, I want to checkout using card payment.
* As a User, I want to recieve email confirmation with details of my purchase.
* As a User, I want to see products reviews

Business (Application Owner/Administrator) User:

As a Business User, I want to I want to be able to login to an administration panel.
As a Business User, I want to attract new customers.
As a Business User, I want to provide all the customers information they need online so that they do need to call and email.
As a Business User, I want to seemless booking system for customers
As a Business User, I want to easily take payment from customers
As a Business User, I want to automatic email notifications for my customers
As a Business User, I want to be able to add new retreats
As a Business User, I want to be able to edit retreats
As a Business User, I want to be able to add new yoga classes
As a Business User, I want to be able to edit yoga classes
Registers (Logged in) User:

* As a Registered User, I want to have the ability to Login to the site via my registered details.
* As a Registered User, I want to create and edit a profile.
* As a Registered User, I want to be able to see my previous purchases
* As a Registered User, I want to be able to view my Cart and any items I currently have awaiting payment in my Cart.
* As a Registered User, I want to be able to items currently added to my bag.
* As a Registered User, I want to have the ability to Logout of the application.


## Technologies Used

- This project uses HTML, CSS, JavaScript and various different technologies to work as helpers to the languages.
- #### [Gitpod](https://www.gitpod.com)
    - **Gitpod** is an IDE used to develop the website.
- #### [Bootstrap](https://www.bootstrapcdn.com/)
    - **Bootstrap** is used to create easier & cleaner responsiveness in addition with helping maintain padding and margins.
    - It's also used to include modal features to the website to give it a professional look.
- #### [Google Fonts](https://fonts.google.com/)
    - **Google Fonts** has been used to provide clean and eye-catching fonts to the website.
- #### [JQuery](https://jquery.com)
    - **JQuery** has been used to simplify DOM manipulation.
- #### [Font Awesome](https://www.bootstrapcdn.com/fontawesome/)
    - **Font Awesome** has been used to add icons to the website.
- #### [GitHub](https://github.com/)
    - **Github** is used: 
    1. As a remote backup of code used in the project.
    2. As a remote server for another user to see the code used in the project.
    3. For users to view the deployed version of the website. The deployed version can be viewed [here!](https://github.com/MarzDell/full-stack-frameworks-with-django)
- #### [Python3](https://www.python.org/downloads/)
    - **Python3** was used to compile and utilise the logic for the project.
- #### [Django 2.2](https://www.djangoproject.com/)
    - **Django** is used as my Python web framework.
- #### [Stripe API](https://stripe.com/docs/api)
    - **Stripe API** is used to make secured payments at the checkout.
- #### [Whitenoise](http://whitenoise.evans.io/en/stable/)
    - **Whitenoise** is simplified static file serving for Python web apps.
- #### [PostgreSQL](http://whitenoise.evans.io/en/stable/)
    - **PostgreSQL** is used as relational SQL database plugin via Heroku.
- #### [Heroku](https://www.heroku.com/)
    - **Heroku** This is a cloud platform where the project is deployed to. The website can be viewed [here!](https://marzdell-antiques.herokuapp.com/)