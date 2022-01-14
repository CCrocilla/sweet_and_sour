![CI logo](https://codeinstitute.s3.amazonaws.com/fullstack/ci_logo_small.png)

# **Sweet & Sour** Website


## **Overview**
<hr>
The website provides the possibility to discover new recipes and not just that! 
Internet users all around the world love to share every day experience using Social Media. Sharing images, documents, stories are part of everyday life. With this website the user will have the possibility to share one of the most beautiful thing in life… The passion for Food! Thousands of recipes will be available, each, for user convenience, categorized into 3 main sessions (Appetizer, Main, and Dessert). The best recipes are rewarded by making the Home Page in the section “Recipe of the Day!”
The website is intuitive and user-friendly, guiding the users and helping them choosing the dishes that they’d like to prepare, showing a step by step guide to prepare the most delicious food, a detailed list of the needed ingredients, the level of difficulty, including images of the finished product. In addition, checkboxes are provided for the ingredient list giving the user the possibility to easily discover what is present/missing from for the realization of the dish! The users can subscribe to a newsletter to receive regular updates and are also provided the possibilities to share their own personal recipes with the entire community.
 
[IMAGE BELOW]

<br><br>


## **Project** 
<hr>

### **User Goal**
Easy, Intuitive and User-Friendly Website!
Wide compatibility with every Browser and Devices.
Images of the final products are displayed to catch users attention (and appetite!), providing clear instructions for the realization of the dish and a detailed lists of needed ingredients.
Possibility for the user to check the ingredients in order to highlight what is missing/presents for the realization of the selected dishes (including the possibility of take a screenshot of the final list to store in your phone for your supermarket trip).
Possibility for the user to share his/her own recipes.
Newsletter available in order to receive daily, weekly or monthly recipes via email.

<br><br>


## **User Experience (UX)**
<hr>

### **User Stories**

- First Time Visitor Goals
    1. As a First Time visitor of a website dedicated to food and recipes, I need to be able to have a visual impact of the type of food and recipes sponsored by this websites, this can be obtained showing images of the finished food products.  
    2. As a First Time Visitor, I want to be able to navigate through the website and find recipes easily.
    3. As a First Time Visitor, I want to be able to a large variety of recipes.
    4. A First Time Visitor, I want to visually see the recipes and to understand their level of complexity.
    5. As a First Time Visitor, I want to find the website pleasant to the eye, visually intuitive, with catchy colours and images.
    6. As a First Time Visitor, I want to see in the foreground the necessary ingredients for the realization of the dishes. 

<br><br>

- Returning Visitor Goals
    1. As a Returning Visitor, I want to frequently be able find new recipes.
    2. As a Returning Visitor, I want to share my personal recipes with the rest of the community sharing a similar passion for cooking.
    3. As a Returning Visitor, I want to access the website through my social media account.

<br><br>

- Frequent User Goals
    1. As a Frequent User, I want to see the recipe of the day.
    2. As a Frequent User, I want to check if my recipes that I sent is displayed in the Recipes page.
    3. As a Frequent User, I want to sign up to the Newsletter in order to receive daily/weekly/monthly update on the recipes and news. 

<br><br>


## **Design**
<hr>

The webpage has been designed to provide a simple, intuitive view which is able to provide a quick overview of the necessary information needed by the user to prepare the selected recipes including images of the finished preparation and the needed ingredients and cooking times for a perfect results. 
Every page has a minimalistic structure which however contains all the relevant features in order to provide the user with a simple, clear and effective experience. 
<br><br> 

- Colour Scheme
<br>
The goal is to use a colour palette that will provide the user with a good and positive impact at a first glance, when opening the website and through the entire navigation experience. 
The list of colors is chosen to be pleasing to the eyes providing an excellent contrast that will allow the user to have prolonged navigation hours is required without tiring the eyes. 
Colour Source: 
    - [Adobe Color](https://color.adobe.com/create/color-wheel)
    - [Color Hunt](https://colorhunt.co/)
<br><br>  

- Typography
<br>
Google Fonts has been used to select the fonts for the Website. 
<br>
The Main fonts used are: 'Oxigen' and 'Viga' while the Sans-serif has been set up as fall-back in case the main font is not loaded.
<br> 
Source: 
    - [Google Fonts](https://fonts.google.com/)
<br><br>

- Image and Video
<br>
Real images have been used to show the completed recipes.
The developer selected a video for the home page of the websites. 
Sources:  
    - [Pexels](https://www.pexels.com/)
<br><br>



## **Features**
<hr>

-	Structure:
<br>
The page has been structured in an easy and user-friendly way with 7 different pages. 
The Structure of the website and the component used are listed below: 
<br><br>

-	Home Page:
<br>
The Home Page shows the logo of the website on the top left of the page and a navigation bar on the top right.
A small animation activates when the user mouse hovers on of the elements in the nav bar, highlighting the content hovered. 
The active page is underlined in the navigation bar when selected. 
Depending on the device used (if laptop, desktop, tablet or smartphone) the position of the logo and the nav bar changes moving the nav bar below the logo to adapt the view and for a highly responsive rendering. 
Those behaviour are consistent in all pages. 
Below the Logo and the Nav Bar the user will see a Hero Image characterized by a muted and in loop video that shows chefs in action. 
Below the Hero Image there will be a section dedicated to the rational and history of the website and an additional section dedicated to the Recipe of the Day.
The Recipe of the Day shows an image of the recipe and the ingredient necessary for the realization using an unordered list.
There will also be in the unordered list the checkbox for each of the ingredient in order to allow the user to flag which ingredients might be missing.
<br><br>

-	Recipes Page:
<br>
This page has Header and Footer consistent with the Home Page. 
The Recipes page is divided in Sections: Appetiser, Main Courses, and Dessert
On the top pf the page, there will be a Hero Image below the Logo and the Nav Bar. After the hero image there will be 3 different buttons that will allow the user to easily reach the different sections of the page. 
In each section there will be 3 dishes displayed with an image and the ingredients. All the recipes will be clickable element opening the recipe in a new page using the target=”_blank” functionality. 
When changing Device, the visualization of the element displayed in the row will change adapting to the selected device dimensions. 
<br><br>


-	Share Page:
<br>
This page has Header and Footer consistent with the Home Page.
The page has an image extended in the page as background on top of which there will be a Form that the user can fill to be able to send and share a recipe including an attachment button for images. 
All the fields have been set as required and the proper message is displayed to the user if the form is not filled in correctly. 
A Reset Button in order to clear the form and a Submit Button are included.
<br><br>

-	Newsletter Page:
<br>
This page has Header and Footer consistent with the Home Page.
The page is characterized by a Form that the user can fill for: First Name, Last Name, Email Address and a Radio Button to select the frequency by which the users can receive the newsletter (daily, weekly, monthly).
<br><br>

-	Thank you page:
<br>
This page will be triggered when the user clicks on the Submit Button for both the Share and Newsletter Page. 
This will be used to let the user know that the data has been inserted correctly. 
<br><br>

-	404 Error Page:
<br>
For any broken or incorrect links, the 404 Error page will be triggered. Here the user will have an image displayed in the background and a text in the image that will inform that the page is not correct. 
A Button will be present in order to allow the user to come back to the Home Page.
<br><br>  
 


## **Wireframe**
<hr>

Balsamiq has been used in order to create the wireframe.
<br>
Below you can open the accordions divided by page and by device used (desktop, tablet and smartphone).
<br>

- ## Home Page 
<details>
    <summary>Click Here for: Desktop View</summary>

</details>
<details>
    <summary>Click Here for: Tablet View</summary>
    
</details>
<details>
    <summary>Click Here for: Smartphone View</summary>
    
</details>
<br>
<br>


- ## Recipes Page
<details>
    <summary>Click Here for: Desktop View</summary>

</details>
<details>
    <summary>Click Here for: Tablet View</summary>

</details>
<details>
    <summary>Click Here for: Smartphone View</summary>

</details>
<br>
<br>


- ## Recipe 
<details>
    <summary>Click Here for: Desktop View</summary>

</details>
<details>
    <summary>Click Here for: Tablet View</summary>

</details>
<details>
    <summary>Click Here for: Smartphone View</summary>

</details>
<br>
<br>


- ## Share Page
<details>
    <summary>Click Here for: Desktop View</summary>

</details>
<details>
    <summary>Click Here for: Tablet View</summary>

</details>
<details>
    <summary>Click Here for: Smartphone View</summary>

</details>
<br>
<br>


- ## Contact Us Page
<details>
    <summary>Click Here for: Desktop View</summary>

</details>
<details>
    <summary>Click Here for: Tablet View</summary>

</details>
<details>
    <summary>Click Here for: Smartphone View</summary>

</details>
<br>
<br>


- ## Thanks You Page
<details>
    <summary>Click Here for: Desktop View</summary>

</details>
<details>
    <summary>Click Here for: Tablet View</summary>

</details>
<details>
    <summary>Click Here for: Smartphone View</summary>

</details>
<br>
<br>


- ## 404 Error Page
<details>
    <summary>Click Here for: Desktop View</summary>

</details>
<details>
    <summary>Click Here for: Tablet View</summary>

</details>
<details>
    <summary>Click Here for: Smartphone View</summary>

</details>
<br>
<br>

<br><br>


## **Technologies Used**
<hr>

The Languages used are:
 - HTML5
 - CSS3
<br><br>

### **Frameworks, Libraries & Programs Used** [Section that needs to be reviewed]
- Google Fonts:<br> 
Google fonts were used to import the font into the style.css file which is used on all pages throughout the project.

- Font Awesome:<br>
Font Awesome was used on all pages throughout the website to add icons for aesthetic and UX purposes.

- Git:<br> 
Git was used for version control by utilizing the Gitpod terminal to commit to Git and Push to GitHub.

- GitHub:<br> 
GitHub is used to store the projects code after being pushed from Git.

- Balsamiq:<br> 
Balsamiq was used to create the wireframes during the design process.
<br><br>



## **Testing**
<hr>

The testing phase have been carried out using the W3C Markup Validator and W3C CSS Validator Services. 
No errors have been identified from the W3C Markup Validator has can be seen in the screenshot below: 
<br>


IMAGE

<br><br>
No errors have been identified from the W3C CSS Validator has can be seen in the screenshot below: 


IMAGE

<br><br>

Lighthouse Validation Area
Example
<br><br>

### **Test Cases**

List of Test Cases Perfomed

Example:
| Area  | Feature | Expected Result | Status | 
| --- | --- | --- | --- |
| Home  | Read More Button | Recipe opened in a new browser tab and content displayed correctly | Pass |
|   |   |
<br><br>
			

### **Additional Tests**
Tests have been performed on Firefox, Microsoft Edge, Chrome and Safari and the result is consistent in all the browser. 
Additional tests include also the check on different devices. Here the list of device used for the tests:
* iPhone 8
* iPhone 12 Pro Max
* iPad Pro
* iPad 
* Moto 4G
* Samsung Galaxy
<br>
Bugs
List here the bugs
<br><br>



## **Development**  [Need to be modified]
<hr>

Deployment

GitHub Pages
The project was deployed to GitHub Pages using the following steps...
1.	Log in to GitHub and locate the GitHub Repository
2.	At the top of the Repository (not top of page), locate the "Settings" Button on the menu. 
o	Alternatively Click Here for a GIF demonstrating the process starting from Step 2.
3.	Scroll down the Settings page until you locate the "GitHub Pages" Section.
4.	Under "Source", click the dropdown called "None" and select "Master Branch".
5.	The page will automatically refresh.
6.	Scroll back down through the page to locate the now published site link in the "GitHub Pages" section.

<br><br>
Forking the GitHub Repository
<br>
By forking the GitHub Repository we make a copy of the original repository on our GitHub account to view and/or make changes without affecting the original repository by using the following steps...
<br>
1.	Log in to GitHub and locate the GitHub Repository
2.	At the top of the Repository (not top of page) just above the "Settings" Button on the menu, locate the "Fork" Button.
3.	You should now have a copy of the original repository in your GitHub account.

<br><br>
Making a Local Clone
<br>
1.	Log in to GitHub and locate the GitHub Repository
2.	Under the repository name, click "Clone or download".
3.	To clone the repository using HTTPS, under "Clone with HTTPS", copy the link.
4.	Open Git Bash
5.	Change the current working directory to the location where you want the cloned directory to be made.
6.	Type git clone, and then paste the URL you copied in Step 3.
$ git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY
7.	Press Enter. Your local clone will be created.
$ git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY
> Cloning into `CI-Clone`...
> remote: Counting objects: 10, done.
> remote: Compressing objects: 100% (8/8), done.
> remove: Total 10 (delta 1), reused 10 (delta 1)
> Unpacking objects: 100% (10/10), done.
<br><br>

## **Credits**
<hr>

Here the list of Credits. 