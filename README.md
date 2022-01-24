<h1 align="center">Milestone Project 4 - Flower Beauty</h1>

[Click here to see live project](https://dp-natural-art.herokuapp.com/)

This project is a fully operational eCommerce website for a client operating small business, selling handmade art. Jewelry, wall-art, cards, coasters, etc. contain real flowers pressed into resin. Each creation is unique a no two items are the same. Artists is hoping to expand beyond the existing business model and gain new clients using this website. Since the project started as Natural Art, artists operates her current business under Flower Beauty brand.

# Table Of Contents

1. [User Experience](#user-experience)
    - [User stories](#user-stories)
    - [Design](#design)
2. [Features](#features)
3. [Technologies Used](#technologies-used)
4.  [Languages Used](#languages-used)
5.  [Frameworks, Libraries & Programs Used](#frameworks-libraries-and-programs-used)
6.  [Database](#database)
7.  [Testing](#testing)
    - [Testing User Stories](#testing-user-stories)
    - [Additional Testing](#additional-testing)
    - [Bugs and Fixes](#bugs-and-fixes)
8. [Deployment](#deployment)
    - [Heroku](#heroku)
    - [Stripe and Database](#stripe-and-database)
    - [GitHub](#github-pages)
9. [Credits](#credits)
    - [Code](#code)
    - [Content](#content)
    - [Media](#media)
    - [Acknowledgements](#acknowledgements)

# User Experience

The focus of this project is to create an online store that is easy to use and navigate, even for users that aren't frequent online users. To achive that, I decided to stick to traditional design, to something users are already familiar with, rather than than to expose the users to a design and functionality that could potentially distract them the shopping.

-   ## User stories

    -   ### First Time Visitor Goals
        1. As a First Time user, I want to enter the website and see what it offers.
        2. As a First Time user, I want to navigate the website with ease and register my account.
        3. As a First Time user, I want to check all the products the store has to offer, including new arrivals and special offers, discounts, etc.
        4. As a First Time user, I want to be able to filter products per department or per type of product to look for the exact items I am interested in.
        5. As a First Time user, I want to be able to access my shopping basket and see what it contains, the summary price, the number of items, etc.
        6. As a First Time user, I want to be able to edit the content of the shopping basket, add items to it or delete the items I no longer want.


    -   ### Returning Visitor Goals
        1. As a Returning user, I want to be able to use my registered account to login back to the website.
        2. As a Returning user, I want to use the safe checkout method with previously saved information.
        3. As a Returning user, I want to see the art that is currently sold in the store and learn about it.
    
    - ### Frequent Visitor Goals
        1. As a Frequent user, I want to be able to log back in to my account without loosing the information from the previous activity.
        2. As a Frequent user, I want to see if there are any new products added.
        3. As a Frequent user, I want to see how much I need to add to my cart to avail of the free shipping.
        4. As a Frequent user, I want to be able to leave the website without loosing the current shopping basket information, so that I am able to return later and continue on with my shopping.

-   ## Design
    -   ### Colour Scheme

        - After initial discussion with the artist, it was agreed to keep the design to bare minimum, as to not distract the customers from the products.

        - The main colors used were: Black [#000000] ,White [#FFFFFF] and shades of grey i.e. [#555]

    -   ### Typography

        - The font that I have agreed to with the artist is the IM Fell English SC with serif as backup. This was agreed to add the artistic flair to the website.

        - The font was imported from [Google Fonts](https://fonts.google.com/)

# Features

- **Main top nav bar** - Where users can surf the website and view all category, types, and all the products of the website using the same navigation option.

- **Sort field** - Users can sort all the products by price, name and category by selecting their sort options in the field.

- **Collapsible nav bar** - To help users navigate the website in smaller screens (i.e. mobile phone users).

- **Quantity update option** - Before and after Users add the product to the cart they can select the product quantity they would like to buy.

- **Toasts messages** - Toasts messages to help maintain the user informed of the actions he has taken or actions that he still is taking while using the website.

- **Session cookie user** - Saves a session cookie so Users don't need to keep login in every time they re-open the website and also keeps their cart information and cart products saved on the cookie in case they need to stop in the middle of the product hunt to do something else.

- **Delivery Information Save** - User can save his delivery information if he wants to purchase new products in the future using the same info.

- **Order History** - Under the user profile page he can check and view information about all his past orders.

# Technologies Used

A brief overview of languages, frameworks, and tools applied in this project:

- [HTML5](https://en.wikipedia.org/wiki/HTML5)
    - Markup language as the shell of the site.

- [CSS3](https://en.wikipedia.org/wiki/Cascading_Style_Sheets)
    - As the design of the site.

- [Bootstrap:](https://getbootstrap.com/)
    - To provide all its pre-built classes, grid and classes functions.

- [JavaScript](https://www.javascript.com)
   - To add interactivity to the site.

- [Python](https://pt.wikipedia.org/wiki/Python)
    - To build the backend and render the pages.

- [Django](https://www.djangoproject.com/)
    - Backend framework used to handle all backend processes such as interactions with the database, authentication and rendering of HTML templates.

# Languages Used

-   [HTML5](https://en.wikipedia.org/wiki/HTML5)
-   [CSS3](https://en.wikipedia.org/wiki/Cascading_Style_Sheets)
-   [JavaScript](https://pt.wikipedia.org/wiki/JavaScript)
-   [Python](https://pt.wikipedia.org/wiki/Python)

# Frameworks Libraries and Programs Used

1. [Bootstrap:](https://getbootstrap.com/)
    - To provide all its pre-built classes, grid and classes functions.

2. [JavaScript Validator](https://jshint.com)
    - To validate JavaScript code.

3. [Google Fonts](https://fonts.google.com/)
    - Used to import the font.

4. [GitHub](https://github.com/)
    - Used as repository for this project.

5. [Google Chrome DevTools](https://developers.google.com/web/tools/chrome-devtools)
    - Used for testing and fixing website bugs.

6. [JQuery](https://jquery.com/)
    - DOM manipulation to initiate the interactive functions from Materialize.

7. [Heroku](https://www.heroku.com/)
    - Used for this project to be build, run, and operate entirely in the cloud.

8. [Stripe](https://stripe.com/en-ie)
    -  NoSQL database used for the project.

9. [Gitpod](https://www.gitpod.io/)
    - Was the online IDE used to developed the entire project and to push changes and production to GitHub and Heroku.

10. [Markdown](https://pt.wikipedia.org/wiki/Markdown)
    - Was used for this README and to create the table of contents and code blocks.


# Testing

- I tested the website myself in Google Chrome and Braven. Further testing on Microsoft Edge and Mozilla Firefox was done by a friend, who reported no issues.

- Through the Console device toolbar it was also tested using multiple emulated devices, including Galaxy S5, iPhone 5/SE iPhone 6/7/8, iPhone X, iPad Pro, etc.

- The W3C Markup Validator and W3C CSS Validator Services:

    - [W3C Markup Validator](https://jigsaw.w3.org/css-validator/#validate_by_uri) - Validated all pages HTML by direct input. No errors were found.

    - [W3C CSS Validator](https://jigsaw.w3.org/css-validator/#validate_by_input) - No errors were found.

    - [Web Formatter](https://webformatter.com/) - Was also used for checking for any errors in HTML and CSS.

    - [JavaScript Validator](https://jshint.com) - No errors were found.

    - [PEP8 online check](http://pep8online.com/) - Succesfully passed through the PEP8 validator.

    - [Google Lighthouse](https://developers.google.com/web/tools/lighthouse#devtools) - Used to check general performance of the website.

## Database

- Throughout the development of the project and as per the course's Boutique Ado videos, I was using  Using Django SQL database SQLite and in Heroku I have used a PostgreSQL database for deployment.

### Product App

`Product` model

| Name | Database Key | Validation | Field Type|
| :-------------: |:----------------:| :--------------: | :---------: |
|Product id | id | primary_key=True | AutoField
|Category|category|null=True, blank=True, on_delete=models.SET_NULL|ForeignKey
|SKU|sku|null=True, blank=True, max_length=254|CharField
|Sizes|has_sizes|null=True, blank=True, dafault=FALSE|ForeignKey
|Name | name | max_length=254 | CharField
|Description | content | blank=False | TextField
|Price | price | max_digits=6, decimal_places=2 | DecimalField
|Rating | rating | max_digits=6, null=True, decimal_places=2 | DecimalField
|Image URL| image_url| max_length=1024, null=True, blank=True | URLField
|Image | image | null=True, blank=True | ImageField

`Category` model

| Name | Database Key | Validation | Field Type|
| :-------------: |:----------------:| :--------------: | :---------: |
|Category id | id | primary_key=True | AutoField
|Name | name | max_length=50 | CharField
|Friendly Name | friendly_name | max_length=50, null=False, blank=False | CharField

### Checkout App

`Order` model

| Name | Database Key | Validation | Field Type|
| :-------------: |:----------------:| :--------------: | :---------: |
|Order Number | order_number | max_length=32, null=False, editable=False | CharField
|User Profile | user_profile | on_delete=models.SET_NULL, null=True, blank=True | ForeignKey
|Full Name | full_name | max_length=50, null=False, blank=False | CharField
|Email | email | max_length=254, null=False, blank=False | EmailField
|Phone Number | phone_number | max_length=20, null=False, blank=False | CharField
|Country | country | null=False, blank=False | CountryField
|Postcode | postcode | max_length=20, null=True, blank=True | CharField
|City | town_or_city | max_length=40, null=False, blank=False | AutoField
|Street Address 1 | street_address1 | max_length=80, null=False, blank=False | CharField
|Street Address 2 | street_address2 | max_length=80, null=False, blank=False | CharField
|County | county | max_length=80, null=True, blank=True | CharField
|Date | date | auto_now_add=True | DateTimeField
|Delivery Cost | delivery_cost | max_digits=6, decimal_places=2, null=False, default=0 | DecimalField
|Order Total | order_total | max_digits=10, decimal_places=2, null=False, default=0 | DecimalField
|Grand Total | grand_total | max_digits=10, decimal_places=2, null=False, default=0 | DecimalField
|Original Cart | original_cart | null=False, blank=False, default='' | TextField
|Stripe PID | stripe_pid | max_length=254, null=False, blank=False, default='' | CharField

`OrderLineItem` model

| Name | Database Key | Validation | Field Type|
| :-------------: |:----------------:| :--------------: | :---------: |
|Order | order | null=False, blank=False, on_delete=models.CASCADE, related_name='lineitems' | ForeignKey
|Product | product | null=False, blank=False, on_delete=models.CASCADE | ForeignKey
|Product Size | product_size | max_lenght=2, null=False, blank=False | Charfield
|Quantity | quantity | null=False, blank=False, default=0 | IntegerField
|Line Item Total | lineitem_total | max_digits=6, decimal_places=2, null=False, blank=False, editable=False | DecimalField

### Profile App

| Name | Database Key | Validation | Field Type|
| :-------------: |:----------------:| :--------------: | :---------: |
|Order | user | on_delete=models.CASCADE | OneToOneField
|Order | default_phone_number | max_length=20, null=True, blank=True | CharField
|Order | default_street_address1 | max_length=80, null=True, blank=True | CharField
|Order | default_street_address2 | max_length=80, null=True, blank=True | CharField
|Order | default_town_or_city | max_length=40, null=True, blank=True | CharField
|Order | default_county | max_length=80, null=True, blank=True | CharField
|Order | default_postcode | max_length=20, null=True, blank=True | CharField
|Order | default_country | null=True, blank=True | CountryField

## Testing User Stories

-   ### First Time Visitor Goals
    1. As a first time user, entering the site I know by the landing page and by vieweing the "All Products" section that the website sells handmade art and jewelry.
    2. As a first time user, I can navigate via the top navigation menu to view and filter the products and to also register my account.
    3. As a first time user, I can see the all the products in the website by going to the "All products" section via the top nav bar.
    4. As a first time user, I can filter all the products by their categories or types via the top navigation bar to check the products I am most interested in.
    5. As a first time user, I can check my current cart by clicking on the Cart icon on the top menu and check the products I have added with the quantity and price.
    6. As a first time user, I can quickly and easily update my cart information by decreasing/increasing the products quantity and then clicking update or by removing a product I don't want it anymore.

-   ### Returning Visitor Goals
    1. As a returning user, I can check and sort the products by their price by using the Sort Field and selecting the Price sorting options.
    2. As a returning user, I can login back with my registered account from previous sessions.
    3. As a returning user, I can go through the checkout process with my previous information saved there.
    4. As a returning user, I can check my favorite Aircraft Models types by filtering the types I like the most via the top navigation menu.

-   ### Frequent Visitor Goals
    1. As a frequent user, I can login back to my account with all my previous information from past purchases added there and also with the order history.
    2. As a frequent user, I can quickly view all the products by going to "All Products" on the top navigation menu and seeing all the products currently in the store.
    3. As a frequent user, I can see a banner message informing if I will have to pay the shipping price with the current cart and products I have added in the cart.
    4. As a frequent user, I can quickly add the products to my cart and return to the store using the "Back to the store" button to view and add any more products to the cart.
    5. As a frequent user, I can leave the website and when I return my session is saved and I can return to vieweing the website and the products without having to login back again and without having to re-add my products to the cart.

## Additional Testing

    All testing performed via the app deployed to Heroku (on https://dp-natural-art.herokuapp.com/)

-   ### Testing index.html page:

    1. When clicking "Shop Now" I am succesfully redirected to the webstore page.

    2. Tested that the hero image is responsive to the screen size.

-   ### Testing the Products App:

    #### products.html page:
    1. On the /products/ page tested the Sort by option with: Price Ascending, Price Descending, Category Ascending, Category Descending, Name (A-Z), Name (Z-A) and made sure the sorting is working correctly for each sorte option.
    
    2. Tested the "Back to top" Button to make sure it is working.
    
    3. Tested the "Edit" and "Delete" buttons under the products to make sure they are working correctly.

    4. Tested the redirect to the product details page when we click on the product image.

    5. When clicking on the products tags we then filter the products to show all the same tags.

    6. Made sure that the success toast alert appears when a product is added to the cart.

    7. Made sure that all information being picked up from the database is showing correctly on the page.

    8. Made sure that only admins can view the edit and delete button and no unintended user can modify the product by modifying the page URL.

    #### product_detail.html page:

    1. Tested the "Edit" and "Delete" buttons to make sure they are working correctly.

    2. Tested the Increase and Decrease buttons to make sure they were working properly and that the quantity was updating accordingly.

    3. Tested both buttons "Keep Shopping" (Redirects back to /products/ page) and "Add to Cart"(add product to cart) to make sure they are working properly.

    4. Made sure that only admins can view the edit and delete button and no unintended user can modify the product by modifying the page URL.

    #### add_product.html page:

    1. Made sure that while on the adding product management page users can choose the correct selectors for Category and Type from the database.

    2. Tested both buttons "Cancel" (returns to products page) and "Add product" (to add the product to the database)

    3. Tested adding a test product and made sure the image and all the fiels were created correctly on the database.

    #### edit_product.html page:

    1. Tested that while clicking on the "Edit" button the user is redirected to the /product/edit/# page and the product information populates the forms.

    2. Tested both buttons "Cancel" (returns to products page) and "Update product" to certify they are working properly and updating the product information.

    3. Tested the toasts alert to make sure they appear to indicate that you are editing a product and also a toast success appears when you have succesfully updated the product.

-   ### Testing the Cart App and also cart.html page :

    1. Tested the Increase/Decrease button and then the "Update" button to make sure the product quantity is changing accordingly as well as the total price. This functionality was reverted back to the state where user can now only select one item. That is due to the fact that all products are unique, therefore no user can purchase multiple items of the same product. Functionality however was left in the code, as the artists asked for it, claiming they will introduce series of products. Code would need to be changed then to allow this.

    2. While Increasing/Decreasing the product quantity and clicking "Update" the Success toast should appear to inform the product quantity was updated accordinly.

    3. Tested the "Remove" button and to confirm the product is removed from the cart.

    4. Tested both the "Keep Shopping" and "Proceed to Checkout" buttons to make sure they are working.

    5. While adding a product under €50 made sure that the yellow banner informing about the free delivery is appearing.

    6. Made sure that all the information is showing correctly like product name, price, quantity, subtotal and grand total.

    6. Made sure that the session cookie is working and that it keeps saved the products inside the cart even if you close and re-open the page.

-   ### Testing checkout app and also checkout.html and checkout_success.html page:

    1. Made sure when clicking on the "Modify Cart" you get back to your cart.

    2. Tested that when you are logged in the form is populated with the User information correctly.

    3. Made sure the order summary displays correctly all the information (product name, quantity and price)

    4. Tested purchasing a product and made sure the order was created succesfully in Stripe.

    5. While clicking on "Complete order" made sure the order was completed and redirected to the checkout_success.html page

    6. On the checkout_success.html page made sure all the order information was displaying correctly and that the success toast pops to confirm the order was processed.

    7. On the checkout_success.html page tested the "Back to store" button to make sure it redirects back to the /products/ page.

    8. Made sure after the order is succesfull that the order now displays in the Order History under the My Profile page.

    9. Tested the webhooks for payment intent succeed and payment intent failed.

    10. Made sure that when the "Save this delivery information to my profile" information is selected the information is indeed saved to the user profile.

-   ### Testing profiles app and profile.html page:
    1. Tested the "Update Information" button to make sure the information is updated correctly on the database.

    2. made sure the Order History is showing all the past order accordingly.

    3. When clicking on the Order History ID made sure the past order details appears and a toast alert pops in to inform the user is viewing a past confirmation order.

-   ### Testing toasts and main-nav.html and mobile-header.html pages:
    1. Tested all the toasts information (error, info, success and warning) throug the website to make sure they are appearing accordingly.

    2. On the toast_success.html made sure the button "View your Cart" shows correctly and redirects to the cart page.

    3. While selecting a product under €50 made sure the yellow bar advising about the free shipping fee appears.

-   ### Testing main navigation and collapsible bar:

    1. On the main top navigation bar tested all the links to make sure they are working properly and also the filters.

    2. On the main top navigation bar tested the Cart and Account icongs to make sure they are working. And while checking the account it is displaying the account options correctly.

    3. Made sure that only admins the product Management option.

    4. Tested the search bar to make sure it is working properly and the page is updating with the correct search query.

    5. On the collapsible bar made sure that all links are working properly.

    6. On the the collapsible bar made sure that the Search, Cart, and My Account are working as expected and that the total cart price is also updated.

## Bugs and Fixes

1. After running flake8 command, I was presented a list of errors, of which most were either "line too long" or "xxx imported but not used". Large volume of those were removed, but I was advised by the Tutors and the author of the last few videos of the course (especially the part related to refactoring the code), to not fix the errors present in migration files. Those errors are still present in the project, but are all of rather cosmetic nature and I did not find them causing functional errors.

2. There was an issue related to requirements.txt file in this project. The problem is that when opening the workspace, each time, it is necessary to re-install the dependencies. To do this, each time I open workspace, I need to run the following commands:
- pip3 uninstall -y -r <(pip3 freeze) and then,
- pip3 install -r requirements.txt
When that is done, all seems to be working in order, I can run server via port 8000, etc. As I was explained by the Tutors, the issue is created by the recent problems with Gitpod workspace.

3. Had a problem with hero image showing up n the wensite when deployed from heroku. It turned out that image was changed and not manually added to AWS bucket. I added the image and applied the read permissions for public view.

# Deployment

## Heroku

The project was deployed on [Heroku](https://dp-natural-art.herokuapp.com/), the following steps were taken:

1. Created a requirements.txt file by typing: `pip3 freeze --local > requirements.txt` in the terminal.
2. Created a procfile.
3. Logged in to Heroku.
4. Pressed the button "new" and then "create new app".
5. Chose an app name and a region and pressed create app.
6. Went to deployment section.
7. Under deployment method pressed Github.
8. Chose the right repository in the list, pressed search and then connect.
9. Pressed enable automatic deploys under automatic deploys.
10. Click on the find more addons button.
11. Click on the Heroku Postgres button.
12. Click on install Heroku Postgres.
13. Went to settings.
14. Added all the config vars needed for the project.
15. Pressed open app.

## Stripe and Database

The first step after forking or cloning the project would be to install all dependencies needed by the system.
If the project is opened in GitPod the command in the terminal would be: `pip3 install -r requirements.txt`.
If working locally setting up a virtual environment first and after that running the `pip3 install -r requirements.txt` command.

In order for the project to work in a product environment a PostgreSQL database would need to be set up, this process might differ depending upon how you choose to deploy the site but on Heroku you would:
1. Log in to Heroku.
2. From the dashboard click the link to the app.
3. Go to resources.
4. Click on the find more addons button.
5. Click on the Heroku Postgres button.
6. Click on install Heroku Postgres.
7. Choose the Hobby dev free plan and choose your app in the list.
8. Press submit form.

If your using another way of hosting the project include an environment variable called "DATABASE_URL" which only exists in the production environment and create the connection to the database in this section in the settings.py file: if DATABASE_URL:
    DATABASES = {
        'default': dj_database_url.parse(DATABASE_URL)
    }

In order for the payment and order system to work a Stripe account needs to be created, with these steps:

1. Go to https://dashboard.stripe.com/register.
2. Enter all details and press create account.
3. Confirm your email address by following the link.
4. Create an account by pressing the top left account button.
5. Write name and press create account.
6. Navigate to developers/webhooks.
7. Click on add endpoint.
8. Enter the base URL of your website plus "/payments/confirmation/" in the URL field.
9. Choose checkout.session.completed in events to send and press add endpoint.
10. Go to developers/webhooks and click on the webhook.
11. Get the webhook signing secret by clicking click to reveal.
12. Get your Stripe API keys from developers/Stripe API
13 Store your webhook signing secret in the variable STRIPE_ENDPOINT_SECRET in settings.py.
14. Store your Stripe API secret_key in the variable STRIPE_TEST_SECRET_KEY in settings.py.
15. Add your publishable key as a string argument to the const stripe = Stripe() object in payments.js

Preferably hide your STRIPE_ENDPOINT_SECRET and STRIPE_TEST_SECRET_KEY values in environment variables if the project is to be publicly displayed.
The same goes for the rest of the settings that needs to be added to setting.py: 

SECRET_KEY : a secret key used to hash passwords etc.
EMAIL_HOST_USER : Gmail account you want to send mails from..
EMAIL_HOST_PASSWORD = App password which can be acquired by setting up two step verification and creating an app password for your Google account
DEFAULT_FROM_EMAIL = same Gmail account.

In development add an environment variable called DEVELOPMENT to use the development database.

## GitHub Pages 

**Under the repository page:**

    1. Click on Settings 
    2. Scroll down to the "GitHub Pages" section 
    3. Select the Source Branch 
    4. Click Save.

- For this project, I have used the cloud-based IDE [Gitpod](https://gitpod.io/) and [GitHub](http://github.com/) as a free git repository hosting.

    1. I started the project by creating a new Repository on GitHub and loading the [Code Institute Gitpod Template](https://github.com/Code-Institute-Org/gitpod-full-template).

    2. Installed the [Gitpod extension](https://chrome.google.com/webstore/detail/gitpod-dev-environments-i/dodmmooeoklaejobgleioelladacbeki) and on my GitHub repo I clicked on the Gitpod button to create a new Master Workspace on GitPod.

    3. After creating the workspace I developed the website using Gitpod and pushing my commits to GitHub using the following commands:
        - `git add "file-name"` - To add a file for staging.
        - `git commit -m "description-of-update"` - To commit.
        - `git push` - To push my commits to GitHub
        - I have also used extra git commands such as: 
        - `python3 -m http.server` - To run a preview of the website on the browser.
        - `git status` - To display the current state of the working directory and the staging area.

## Running locally

1. Go tho this [project repository](https://github.com/LucasCegielski/natural_art) in GitHub while signed in in your own GitHub account.
2. Click on the dropdown menu Code option.
3. Click on "Open with GitHub Desktop" to clone and open the repository locally.
4. Click on the "Choose" option and navigate to the local path where you want the cloned repository to be.
5. Click "Clone".

- [Click here](https://docs.github.com/en/free-pro-team@latest/desktop/contributing-and-collaborating-using-github-desktop/adding-and-cloning-repositories) for more cloning GitHub options.

# Credits

- [Code Institute Course](https://codeinstitute.net/) helping on setuping up the e-commerce store.

- [Font Awesome](https://fontawesome.com/icons) for the huge collection of free icons they offer.

- [Web Formatter](https://webformatter.com/) Used for formatting HTML, CSS and Javascript and also to check for errors.

- [Google Fonts:](https://fonts.google.com/) Thanks to Google for providing this huge amount of free fonts on the site.

- [Bootstrap](https://getbootstrap.com) for the large and free libraries.

## Content

-  The  details and descriptions of the products were taken from the artist Donata Panczyk, who created the products.

## Media

-  Pictures of the products in the store are photos taken by the artist herself and are of the products she created.

## Acknowledgements

- My mentor Akshat for all his help and ideas.

- Thanks to the tutors at Code Institute for all help during the course (especialy to Igor, James and Sean, for all their help and amazing input).

- Slack channel help regarding ongoingissues and problem solving ideas.

- Stackoverflow community and countless youtubers for all their input and influence.