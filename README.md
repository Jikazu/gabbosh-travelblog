<h1 align="center">Gabbosh Travelblog</h1>
<div align="center"><img src=""></div>

This website is made as a blog where I can share my own travelstories. It is the fourth project in the Code institute Full Stack Developer program. 
The website is for my family and friends that want to see what I'm up to during my travels. The website comes with an account registration and a contact form where anyone can contact me regarding any topics on my blog.
         
[View the live project here.](placeholder)


## TOC

- [User Experience (UX)](#user-experience-ux)
  - [Project goals](#project-goals)
  - [User Stories](#user-stories)
  - [Agile Methodology](#agile-methodology)
  - [Design](#design)
    - [Wireframes](#wireframes)
    - [Database Schema](#database-schema)
- [Features](#features)
  - [Future Features](#future-features)
- [Technologies Used](#technologies-used)
  - [Languages](#languages)
  - [Frameworks Libraries Programs](#frameworks-libraries-programs)
- [Testing](#testing)
  - [Bugs](#bugs)
    - [Fixed Bugs](#fixed-bugs)
    - [Remaining Bugs](#remaining-bugs)
- [Deployment](#deployment)
  - [Forking the GitHub Repository](#forking-the-github-repository)
  - [Running the project locally](#running-the-project-locally)
  - [Deploying with Heroku](#deploying-with-heroku)
- [Credits](#credits)
  - [Code](#code)
  - [Media](#media)
  - [Acknowledgements](#acknowledgements)

## User Experience (UX)
-   ### Project goals  
    The goal with this website is for me to share my pictures and stories from when I go abroad, which I do quite often. 
  
-   ### User stories

    -   #### First Time Visitor Goals
          - As a first time visitor I can read and learn about the location and history and get a feel for the restaurant.
          - As a first time visitor I can find out what kind of food they serve from their menu.
          - As a first time visitor I can find information about how to make a reservation at the restaurant.
        
    -   #### Returning Visitor Goals
        -  As a returning visitor I can create an account so I can make a reservation online.
        -  As a returning visitor I can view the menu to see if has changed.

    -   #### Frequent User Goals
        -  As a frequent visitor I can login and find my current bookings.
        -  As a frequent visitor I can change or cancel my booking in the login page.

-   ### Agile methodology
    - The principles of agile methodology were utilized during the project. By assigning user stories to issues and taking advantage of the GitHub Kanban board functionality, the necessary goals and priorities throughout the project could be well defined. In addition, labels were used to further define the priority of each user story in the Kanban board.  

-   ### Design
    - Discuss theme
    
     - Colours  
        - 
     - Font  
        -    
     - Images  
        - The images are all taken by me, the author from my travels.

-   ### Wireframes  
    - A separate document for the wireframes can be viewed here: 
      - [For Desktop view]()
      - [For Mobile view]()    

-   ### Database Schema  
    - The database design schema can be viewed below. It consists of a Booking model with a foreignKey of User that relates to the Django standard User model class.  
    ![dbschema](placeholder)  

## Features  

### Navbar  
- The navbar shows all the sections that the user can enter and provides a quick and easy means of navigating the site. The link to make a booking is enlarged to make it extra easy to find and use. 
&nbsp;  

![Navbar](placeholder)  


### Contact  
- The contact section includes all the necessary information about the restaurant that the visitor may need to know about.  
&nbsp;  

![Contact](placeholder)  

### Account signup/login  
- The account pages where the user can create an account in order to make a registration as well as login as an existing users.  
&nbsp;  

![signup](/docs/img/features/signup.png)
![login](/docs/img/features/login.png)  


### Footer  
- The footer contains the essential information about the restaurant for easy access to the most relevant contact information and social media links on all pages throughout the website.  
&nbsp;  

![Footer](/docs/img/features/footer.png)  


### Future Features
  - 

## Technologies Used

### Languages
   - Python
   - JavaScript
   - HTML5
   - CSS3

### Frameworks, Libraries, Programs
- Python Built-in Modules:
  - [os](https://docs.python.org/3/library/os.html) 

- External Packages
  - [cloudinary](https://pypi.org/project/cloudinary/1.29.0/) 
  - [dj-database-url](https://pypi.org/project/dj-database-url/0.5.0/) 
  - [dj3-cloudinary-storage](https://pypi.org/project/dj3-cloudinary-storage/0.0.6/) 
  - [Django](https://pypi.org/project/Django/3.2.14/) 
  - [django-allauth](https://pypi.org/project/django-allauth/0.51.0/)
  - [gunicorn](https://pypi.org/project/gunicorn/20.1.0/)
  - [psycopg2](https://pypi.org/project/psycopg2/2.9.3/) 

### Programs & Tools

- [Google Fonts:](https://fonts.google.com/)
  - Was used to to incorporate font styles.  
- [Bootstrap](https://getbootstrap.com/)
  - Was used to create the front-end design.
- [GitPod:](https://gitpod.io/)
  - Gitpod was used as IDE to commit and push the project to GitHub.
- [GitHub:](https://github.com/)
  - Was used for all storing and backup of the code pertaining to the project.
- [Balsamiq:](https://balsamiq.com/)
  - Was used to create wireframes
- [LucidCharts:](https://www.lucidchart.com/)
  - Was used to create the database schema.
 

## Testing  
A separate document for testing can be viewed here: [TESTING.md](docs/TESTING.md)

### Bugs

#### Fixed Bugs

|Bug | Solution | Status |
|----|:---------|:-------|
|The url for my contact template did not work at all| It took me a good 8 hours to find out what was wrong. I only had a post function and not a get function in my class, so I went ahead and fixed that. | Fixed |
|My css file I have did not work | I had to add a staticfiles_dirs to the settings.py | Fixed |



#### Remaining Bugs
  - No known bugs remaining

### Testing User Stories from User Experience (UX) Section

  -   #### First Time Visitor Goals
      - As a first time visitor I can read and learn about the location and history and get a feel for the restaurant.
        - When entering the webpage information about the restaurant is easily found by either scrolling or navigating using the links.
      - As a first time visitor I can find out what kind of food they serve from their menu.  
        - The Customer can directly find a large link to the menu when entering the webpage.
      - As a first time visitor I can find information about how to make a reservation at the restaurant.  
        - When entering the webpage the Customer can find the booking link immediately in the hero section or in the navbar.
        
  -   #### Returning Visitor Goals
      -  As a returning visitor I can create an account so I can make a reservation online.
          -  The Customer can use the signup link and quickly create an account login.
      -  As a returning visitor I can view the menu to see if has changed.  
          - When entering the webpage the Customer will find the menu first hand by clicking on the large button or scrolling.
    
  -   #### Frequent User Goals
      -  As a frequent visitor I can login and find my current bookings.  
          - As a frequent Customer can easily login upon entering the webpage. After being logged in, the Customer can view their current bookings in the navbar.
      -  As a frequent visitor I can change or cancel my booking in the login page.  
          - After being logged in, the Customer can delete their current bookings by going to the mybookings page in the navbar.



## Deployment

### Forking the GitHub Repository
1. Go to [the project repository](https://github.com/ErikHgm/FireHouse-Restaurant-Project)
2. In the right most top menu, click the "Fork" button.
3. There will now be a copy of the repository in your own GitHub account.


### Running the project locally
1. Go to [the project repository](https://github.com/ErikHgm/FireHouse-Restaurant-Project)
2. Click on the "Code" button.
3. Choose one of the three options (HTTPS, SSH or GitHub CLI) and then click copy.
4. Open the terminal in you IDE program. 
5. Type `git clone` and paste the URL that was copied in step 3.
6. Press Enter and the local clone will be created. 

### Alternatively by using Gitpod:
1. Go to [the project repository](https://github.com/ErikHgm/FireHouse-Restaurant-Project)
2. Click the green button that says "Gitpod" and the project will now open up in Gitpod.

### Deploying with Heroku

I followed the below steps using the Code Institute tutorial:

The following command in the Gitpod CLI will create the relevant files needed for Heroku to install your project dependencies `pip3 freeze --local > requirements.txt`. Please note this file should be added to a .gitignore file to prevent the file from being committed.

1. Go to [Heroku.com](https://dashboard.heroku.com/apps) and log in; if you do not already have an account then you will need to create one.
2. Click the `New` dropdown and select `Create New App`.
3. Enter a name for your new project, all Heroku apps need to have a unique name, you will be prompted if you need to change it.
4. Select the region you are working in.

#### Heroku Settings  
You will need to set your Environment Variables - this is a key step to ensuring your application is deployed properly.
1. In the Settings tab, click on `Reveal Config Vars` and set the following variables:
    - Add key: `PORT` & value `8000`
    - Add key: DATABASE_URL, this should have been created automatically by Heroku.
    - Add key: CLOUDINARY_URL and the value as your cloudinary API Environment variable e.g.
    - Add key: SECRET_KEY and the value as a complex string which will be used to provide cryptographic signing.

2. Buildpacks are also required for proper deployment, simply click `Add buildpack` and search for the ones that you require.
    - For this project, I needed to add `Python`.

####  Heroku Deployment  
In the Deploy tab:
1. Connect your Heroku account to your Github Repository following these steps:
    - Click on the `Deploy` tab and choose `Github-Connect to Github`.
    - Enter the GitHub repository name and click on `Search`.
    - Choose the correct repository for your application and click on `Connect`.
2. You can then choose to deploy the project manually or automatically, automatic deployment will generate a new application every time you push a change to Github, whereas manual deployment requires you to push the `Deploy Branch` button whenever you want a change made.
3. Once you have chosen your deployment method and have clicked `Deploy Branch` your application will be built and you should now see the `View` button, click this to open your application.


## Credits

### Code
  - [Restaurantly Boostrap theme](https://bootstrapmade.com/restaurantly-restaurant-template/) was the Boostrap theme used in the project.
  - [Django Documenation](https://www.djangoproject.com/) was used to provide examples of code solutions and Django functionality.
  - [Bootstrap Documenation](https://getbootstrap.com/) was used to provide examples of Bootstrap functionality and building blocks.
  - [Code Institute walkthrough](https://codeinstitute.net/) as inspiration and code examples, the code institute walkthroughs "Hello Django" and "I Think Therefore I Blog" was used.

### Content
  - The texts that are used for testimonials comes from [Tripadvisor](https://www.tripadvisor.com/).
  - The texts that are used for the about section comes from [Royal35](https://royal35steakhouse.com/) website.


### Media
  - The images in the project comes from the [Restaurantly Boostrap theme](https://bootstrapmade.com/restaurantly-restaurant-template/)
  - The video in the project comes from the [Restaurantly Boostrap theme](https://bootstrapmade.com/restaurantly-restaurant-template/)

### Acknowledgements
  - The tutor support team at Code Institute for their support.
  - My Code Institute Mentor for feedback and suggestions.
  - The Code Institute Slack community.

  [Back to top](#toc)