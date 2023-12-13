<h1 align="center">Gabbosh Travelblog</h1>


I'd like to start this with the preface that this is an unfinished project, as I've underestimated the time I had left for this project as I thought it was due 4 days later than the actual deadline. This website is based on the walkthrough project "I think therefore I blog". I made as a blog where I can share my own travelstories. It is the fourth project in the Code institute Full Stack Developer program. 
The website is for my family and friends that want to see what I'm up to during my travels. The website comes with an account registration and a contact form where anyone can contact me regarding any topics on my blog.
         
[View the live project here.](https://gabbosh-travelblog-6ba49b37d1ec.herokuapp.com/)


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
          - For the visitors to be able to see the blogposts I make
          - For the visitors to be able to see who is running the blog
        
    -   #### Returning Visitor Goals
        - Be able to see any new blogposts
        - Be able to like and comment on posts by registering an account
        

-   ### Agile methodology
    - The principles of agile methodology were utilized during the project. By assigning user stories to issues and taking advantage of the GitHub Kanban board functionality, the necessary goals and priorities throughout the project could be well defined. In addition, labels were used to further define the priority of each user story in the Kanban board.  

-   ### Design
    - Discuss theme
    I wanted to have quite bright colours inspired by Asia as that is my favorite travel destination.
    
     - Colours  
        - I'm using a Sakura pink as the background colour, along with whites towards the edges, and black as it has good visibility as a text. I'm also using a lotus blue colour to complement the pink and whites.
     - Font  
        - I'm using Roboto and Lato from [Google fonts](https://fonts.google.com/)
     - Images  
        - The images are all taken by me, the author, from my travels and a stockphoto from Code Institute as a placeholder. 

-   ### Wireframes  
    - I did not have the time to create any as I was planning to change the layout from the original template.

-   ### Database Schema  
    - I did not have the time to draw up a database schema before the deadline. 

## Features  

### Navbar  
- The navbar shows all the sections that the user can enter and provides a quick and easy means of navigating the site. 


![Navbar](/readme-images/navbar.png)  


### Contact  
- The contact section includes a form where the user can contact the owner of the website. 

![Contact](/readme-images/contactform.png)  

### Register/login  
- I have two pages, one where a user can register for an account, and one where they can login
&nbsp;  

![register](/readme-images/register.png)
![login](/readme-images/login.png)  


### Footer  
- The footer contains links to my social media.
&nbsp;  

![Footer](/readme-images/footer.png)  


### Future Features
  - An about page where I can have information about myself as the blog owner.
  - Add further functionality in my contact model so that I can send a reply directly from there instead of just viewing the content.
  - Different layout than the template I used
  - Creating an account and logging in with either google account/facebook account

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

### Programs & Tools

- [Google Fonts:](https://fonts.google.com/)
  - Was used to to incorporate font styles.  
- [Bootstrap](https://getbootstrap.com/)
  - Was used to create the front-end design.
- [GitPod:](https://gitpod.io/)
  - Gitpod was used as IDE to commit and push the project to GitHub.
- [GitHub:](https://github.com/)
  - Was used for all storing and backup of the code pertaining to the project.


## Testing  
I have done testing throughout the project.
- The user can create an account and login without any errors.
- The user can like comments without any errors. In the backend I can see the likes.
- The user can comment on posts without any errors. In the backend I can approve or not approve posts.
- The user can use the contact form without any errors. In the backend I can view all the replies, and see their email details.
- The admin can create a post, with pictures without any errors. I can also edit the posts after the creation.

### Bugs

#### Fixed Bugs

|Bug | Solution | Status |
|----|:---------|:-------|
|The url for my contact template did not work at all| It took me a good 8 hours to find out what was wrong. I only had a post function and not a get function in my class, so I went ahead and fixed that. | Fixed |
|My css file I have did not work | I had to add a staticfiles_dirs to the settings.py | Fixed |
|At one point in my workspace everything broke, all my styling disappeared and the admin didnt work. | I panicked but luckily I had not commited nor pushed any changes from the time it was broken, so I pushed the previous changes and opened up a new workspace. | Fixed |



#### Remaining Bugs
  - No known bugs remaining

## Deployment

### Forking the GitHub Repository
1. Go to [the project repository](https://github.com/Jikazu/gabbosh-travelblog)
2. In the right most top menu, click the "Fork" button.
3. There will now be a copy of the repository in your own GitHub account.


### Running the project locally
1. Go to [the project repository](https://github.com/Jikazu/gabbosh-travelblog)
2. Click on the "Code" button.
3. Choose one of the three options (HTTPS, SSH or GitHub CLI) and then click copy.
4. Open the terminal in you IDE program. 
5. Type `git clone` and paste the URL that was copied in step 3.
6. Press Enter and the local clone will be created. 

### Alternatively by using Gitpod:
1. Go to [the project repository](https://github.com/Jikazu/gabbosh-travelblog)
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
  - [Django Documenation](https://www.djangoproject.com/) was used to provide examples of code solutions and Django functionality.
  - [Bootstrap Documenation](https://getbootstrap.com/) was used to provide examples of Bootstrap functionality and building blocks.
  - [Code Institute walkthrough](https://codeinstitute.net/) as inspiration and code examples, the code institute walkthroughs "Hello Django" and "I Think Therefore I Blog" was used.

### Content

### Media
  - The images in the project comes from me.
  - The text in the project also comes from me.

### Acknowledgements

  - My Code Institute Mentor for feedback and suggestions.
  - The Code Institute Slack community.

  [Back to top](#toc)