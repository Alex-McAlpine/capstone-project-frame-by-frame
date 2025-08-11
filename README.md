### Frame By Frame

## Table of Contents

- [Frame by Frame](#frame-by-frame)
- [Table of Contents](#table-of-contents)
    - [Introduction](#introduction)
        - [Test-account](#test-account)
    - [Repository](#repository)
    - [Agile Planning](#agile-planning)
        - [Project Board](#project-board)
        - [Wireframes](#wireframes)
        - [User Stories](#user-stories)
        - [Colour Scheme](#colour-scheme)
    - [Database](#database)
        - [Entity Relationship Diagram (ERD)](#entity-relationship-diagram-erd)
    - [Features](#features)
        - [Future-Features](#future-features)
    - [UX Design](#ux)
    - [Testing/Validation](#testingvalidation)
        -[UI/User Story Tests](#uiuser-story-tests)
        -[Unit Tests](#unit-test)
        -[HTML](#html)
            -[Base.HTML](#basehtml)
            -[About.HTML](#abouthtml)
        -[CSS](#css)
        -[Python](#python)
        -[JavaScript](#javascript)
        -[Lighthouse](#lighthouse-test)
            -[Home-page](#home-page)
            -[About-page](#about-page)
            -[Post-Detail-HTML](#post-detail-html)
    - [Deployment](#deployment)
        - [Preparing My Project For Heroku](#preparing-my-project-for-heroku)
        - [Deploying To Heroku](#deploying-to-heroku)
    - [AI Usage](#ai)
    - [Technologies](#technologies)
    - [References/Credits](#referencescreditslegal)

## Introduction 

Frame by Frame is a blog-based website developed using HTML, CSS, Bootstrap, and Python with the Django framework.

[Screenshots-of-Website]



# Test Account

Username: Tester3
Password: testaccount1


## Repository

- [GitHub Repository](https://github.com/Alex-McAlpine/capstone-project-frame-by-frame)
- [Project Board](https://github.com/users/Alex-McAlpine/projects/9)
- Deployed Heroku link: [Deployed-link](https://frame-by-frame-044462eff376.herokuapp.com/)

## Agile Planning

This project follows agile methodology, utilizing user stories, wireframes, and a Kanban board.

# Project Board

A Kanban board was used for workflow management, tracking progress, and identifying bottlenecks.

![Screenshot-of-project-board](./README%20documentation/images/Project%20board%20fbf.png)

# Wireframes

Wireframes were created in Canva.com to visualize UI layout and guide development.

![Screenshot-of-PC-Home](./README%20documentation/images/PC%20home.png)

![Screenshot-of-Mobile-Home](./README%20documentation/images/mobile%20home.png)

# User Stories

User stories were used to capture requirements from the end-user perspective and are available on the project board.

# Colour Scheme

The colour scheme was inspired by a screenshot from the movie Interstellar.

![Colour-scheme-chosen](./README%20documentation/images/Colour%20scheme.png)

![Inspiration-for-colour-scheme](./README%20documentation/images/Colour%20scheme%20inspiration.jpg)

### Database

## Entity Relationship Diagram (ERD)

The ERD was created using [Eraser.io](https://app.eraser.io/).

![Screenshots-of-ERDs](./README%20documentation/images/ERD%20Diagram.png)

### Features

Frame by Frame offers a range of interactive features designed to enhance user engagement and foster a vibrant blogging community:

- **Like/Unliking Rating System:** Users can express their opinions on blog posts by liking or unliking them. This feedback mechanism helps highlight popular content and encourages quality contributions.

![Post-not-liked](./README%20documentation/images/Post%20not%20liked..png)

![Post-liked](./README%20documentation/images/Post%20been%20liked..png)

- **Commenting:** Every post supports a comment section, allowing users to share their thoughts, ask questions, or engage in discussions with the author and other readers.

[Screenshots-needed]

- **Collaborating:** From the about section, users can fill out a collaboration form to engage with the blog author directly.

[Screenshots-needed]

- **Account Registration:** Visitors can create an account to unlock additional features. Registration is quick and secure, ensuring a personalized experience.

[Screenshots-needed]

- **Authenticated User Actions:** Registered users gain access to exclusive capabilities, including:
    - **Liking/Unliking Posts:** Interact with content by rating posts from other users.
    - **Commenting:** Participate in conversations by commenting on any post.
    - **Collaboration** Users can request a collaboration from the about page.
- **User Management:** The platform ensures that only authenticated users can create, like, or comment on posts, maintaining a safe and respectful environment.

These features collectively create an engaging platform where users can connect, share ideas, and contribute to the Frame by Frame community.

## Future Features

- **Bookmarking system**

    Allow users to save their favorite blog posts or tutorials for quick access later, making it easier to revisit important content or resources.

- **Glossary of terms**

    Provide a comprehensive list of video editing terminology with clear definitions, helping beginners and experienced users alike understand industry jargon.

- **Tutorials/Tips**

    Offer step-by-step guides and practical tips on various video editing techniques, tools, and workflows to help users improve their editing skills.

- **In-depth reviews**

    Publish detailed reviews of video editing software, plugins, and equipment, giving readers insights into the best tools and resources for their projects.


### UX

The user experience (UX) of Frame by Frame is designed to be intuitive and user-friendly, ensuring that visitors can easily navigate the blog and interact with its features:

- **Clear Navigation:** The site features a straightforward navigation bar, allowing users to quickly access key sections such as Home, Blog Posts, About, and Account options. This structure helps users find content and features without confusion.

- **Responsive Design:** The layout adapts seamlessly to different devices, providing an optimal viewing and interaction experience on desktops, tablets, and mobile phones.

- **Accessible Communication:** Each blog post includes a comment section, making it easy for users to engage in discussions, ask questions, and share feedback with both authors and other readers. The comment interface is simple and accessible, encouraging active participation.

- **Interactive Features:** Users can like or unlike posts with a single click, providing immediate feedback and helping to highlight popular content. These interactive elements are clearly visible and easy to use, enhancing engagement across the platform.

- **User Onboarding:** Account registration is streamlined, enabling new users to join the community and unlock additional features such as posting, commenting, and liking content.

Overall, the UX prioritizes clarity, accessibility, and engagement, making it easy for users to explore, communicate, and interact within the Frame by Frame blogging community. 

# Utilizing User Stories

The UX design of the project was purposefully developed based on the requirements and goals outlined in the user stories.

My Must Have user stories allowed the UX to be constantly available, to a high standard and to be improved in the future.

As a Site User, I can click on a post so that I can read the full text.

As a Site Admin I can create, read, update and delete posts so that I can manage my blog content.

As a Site User I can leave comments on a post so that I can be involved in the conversation.

As a Site Admin, I can create or update the about page content so that it is available on the site. 

As a Site User, I can click on the About link so that I can read about the site.

As a Site User I can modify or delete my comment on a post so that I can be involved in the conversation.

As a Site Admin I can approve or disapprove comments so that I can filter out objectionable comments. 

As a Site User I can register an account so that I can comment on a post.

As a Site User / Admin I can view comments on an individual post so that I can read the conversation.

As a Site Admin I can create draft posts so that I can finish writing the content later. 

As a Site Owner I can mark collaboration requests as "read" so that I can see how many I still need to process. 

As a logged in user of the website I should be able to rate (like/unlike) posts that appear on the page.

As a Site Owner I can store collaboration requests in the database so that I can review them.  

As a Potential Collaborator I can fill in a contact form so that I can submit a request for collaboration. 

As a site user, I can view a paginated list of posts so that I can select which post I want to view. 

### Testing/Validation

## UI/User Story Tests

There were a total of 19 User stories, using MoSCoW prioritisation I had 15 Must haves, 2 should haves and 2 could haves.

| User Story - MUST HAVE                                                                                                                                            | Status  |
|-------------------------------------------------------------------------------------------------------------------------------------------------------------------|---------|
| As a Site User, I can click on a post so that I can read the full text.                                                                                           | PASSED  |
| As a Site Admin I can create, read, update and delete posts so that I can manage my blog content.                                                                 | PASSED  |
| As a Site User I can leave comments on a post so that I can be involved in the conversation.                                                                      | PASSED  |
| As a Site Admin, I can create or update the about page content so that it is available on the site.                                                               | PASSED  |
| As a Site User, I can click on the About link so that I can read about the site.                                                                                  | PASSED  |
| As a Site User I can modify or delete my comment on a post so that I can be involved in the conversation.                                                         | PASSED  |
| As a Site Admin I can approve or disapprove comments so that I can filter out objectionable comments.                                                             | PASSED  |
| As a Site User I can register an account so that I can comment on a post.                                                                                         | PASSED  |
| As a Site User / Admin I can view comments on an individual post so that I can read the conversation.                                                             | PASSED  |
| As a Site Admin I can create draft posts so that I can finish writing the content later.                                                                          | PASSED  |
| As a Site Owner I can mark collaboration requests as "read" so that I can see how many I still need to process.                                                   | PASSED  |
| As a logged in user of the website I should be able to rate (like/unlike) posts that appear on the page.                                                          | PASSED  |
| As a Site Owner I can store collaboration requests in the database so that I can review them.                                                                     | PASSED  |
| As a Potential Collaborator I can fill in a contact form so that I can submit a request for collaboration.                                                        | PASSED  |
| As a site user, I can view a paginated list of posts so that I can select which post I want to view.                                                              | PASSED  |

## Unit Test

# VSCode Unit Tests
Unit tests were executed using `python manage.py test` to verify functionality and prevent bugs.

![Unit-Tests](./README%20documentation/images/Unit%20tests.png)


## HTML

HTML code was validated in VSCode with no major issues.

![VScode-terminal](./README%20documentation/images/No%20problems%20terminal.png)

# Base.HTML 

Base template passed HTML validation.

![Base.html](./README%20documentation/images/Home%20page%20HTML%20Pass.png)

# About.HTML

![About.html](./README%20documentation/images/About%20page%20html%20pass.png)

# Post-Detail.HTML

![Post-detail](./README%20documentation/images/post%20detail%20pass.png)

## CSS

CSS code passed validation, ensuring web standards and cross-browser compatibility.

![CSS-Validator](./README%20documentation/images/CSS%20Validation.png)

## Python

Python code was validated, and long lines were corrected to meet style guidelines.

# About Models.py

![About-models.py](./README%20documentation/images/About%20models.py%20PASS.png)

# About Views.py

![About-views.py](./README%20documentation/images/About%20Views.py%20PASS.png)

# Blog Models.py

![Blog-models.py](./README%20documentation/images/blog%20models.py%20PASS.png)

# Blog Views.py

![Blog-views.py](./README%20documentation/images/Blog%20Views.py%20PASS.png)

## JavaScript

JavaScript was validated using JSHint with no issues.

![JavaScript-Pass](./README%20documentation/images/JavaScript%20pass.png)

# Lighthouse Test

Lighthouse tests returned positive results.

# Home Page

![Lighthouse-test](./README%20documentation/images/Lighthouse%20tests.png)

# About Page

![Lighthouse-test2](./README%20documentation/images/lighthouse%20test%20for%20about.png)

# Post Detail HTML

![Lighthouse-test3](./README%20documentation/images/post%20details%20lighthouse.png)

### Deployment

The project is deployed to Heroku via GitHub, with environment variables and static files configured for production.


# Preparing my project for heroku

- My project was uploaded to a github repository
- Gunicorn was installed and configured
- Ensure all dependencies are listed in requirements.txt and the python version is listed in .python-version
- Configure static files and settings.py, paying special attention to disabling debugging and any other settings related to security.
- Set up and configure environmental files eg. env.py
create a Procfile. This file tells Heroku how to run your application.
- Ensure that any files that contain secret keys or other sensitive information eg. env.py is added to .gitignore and is not present in your github repo

# Deploying to Heroku

- Create heroku app
- Link github repository & Code Institute PostGres database
- Add environmental variables to heroku, such as, secret keys.
- Deploy the application

### AI

AI tools were used for brainstorming intital planning phases, colour scheme selection, code generation, troubleshooting, and validation.


### Technologies

- HTML5- for page structure.
- CSS3- for custom styling.
- Python- for the backend.
- Heroku - for hosting and deployement of this project.
- Git - for version control.
- GitHub is used for setting up and managing project repositories.
- A GitHub Project Board are utilized for effectively managing tasks, tracking project progress, and ensuring efficient implementation.



### References/Credits/Legal

- Google Fonts for typography.
- Canva.com for wireframes.
- Django- framework used to build this project.
- JSHint for JavaScript validation.
- W3C HTML and CSS validators.
- Microsoft Copilot for AI contribution and assistance.
- Bootstrap for CSS framework.
- Squoosh for reducing image sizes.
- Coolors for colour palette.
- Eraser.io for ERDs.
- FavIcon for browser icon.
- Code Institute, especially Alex Tastad, Mark Briscoe and Roman Rakic, for helping me learn and supporting my cdoing journey.


Everything used in the article posts is for educational purposes only and is not intended to infringe or steal anyones work,
all authors and original posts have been credited at the bottom of each post.