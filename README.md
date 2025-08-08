### Frame By Frame

## Table of Contents

- [Frame by Frame](#frame-by-frame)
- [Table of Contents](#table-of-contents)
    - [Introduction](#introduction)
    - [Repository](#repository)
    - [Agile Planning](#agile-planning)
        - [Project Board](#project-board)
        - [Wireframes](#wireframes)
        - [User Stories](#user-stories)
        - [Colour Scheme](#colour-scheme)
    - [Database](#database)
        - [Entity Relationship Diagram (ERD)](#entity-relationship-diagram-erd)
    - [UX Design](#ux-design)
    - [Features](#features)
    - [Testing](#testing)
        -[UI/User Story Tests](#uiuser-story-tests)
        -[Unit Tests](#unit-test)
        -[HTML](#html)
        -[CSS](#css)
        -[Python](#python)
        -[Testing Screenshots](#testing-screenshots)
    - [Deployment](#deployment)
        - [Preparing My Project For Heroku](#preparing-my-project-for-heroku)
        - [Deploying To Heroku](#deploying-to-heroku)
    - [References](#references)
    - [AI Usage](#ai)
    - [Technologies](#technologies)


## Introduction 

Frame by Frame is a blog based website coded in HTML/CSS, utilising bootstrap frameworks and Python using Django frameworks.

[Screenshots-of-Website]

## Repository

The GitHub repo can be found here: [Git-Repo](https://github.com/Alex-McAlpine/capstone-project-frame-by-frame)

The Project Board can be found here: [Project-Board](https://github.com/users/Alex-McAlpine/projects/9)

The deployed Heroku link can be found here: [Deployed-link]

## Agile Planning

This project utilised an agile methodology for the project. Making use of user stories, wireframes and a kanban board.

# Project Board

A Kanban board is an Agile project management tool that uses columns for workflow stages and cards for tasks, helping teams track progress and identify bottlenecks.

![Screenshot-of-project-board](./README%20documentation/images/Project%20board%20fbf.png)

# Wireframes

Wireframes are an essential part of the UI design process. These simple sketches I put together in Canva.com help to bring the application to life before coding had even started. Wireframes help to visualize the placement of elements on the page and guide the development process.

The design didn't change significantly during development but additional features and details were added to enhance the application beyond the initial scope.

![Screenshot-of-PC-Home](./README%20documentation/images/PC%20home.png)

![Screenshot-of-Mobile-Home](./README%20documentation/images/mobile%20home.png)

# User Stories

User stories are a key component of agile development methodologies. They are short, simple descriptions of a feature or functionality told from the perspective of the end user. User stories help to capture the requirements of the application in a way that is easy to understand and communicate. They focus on the value that the feature will bring to the user and provide a basis for planning, development, and testing.

All my user stories can be found on the project board.

# Colour Scheme

My colour scheme was chosen from a screenshot from my favourite movie, Interstellar, which inspired me to go into video editing.

![Colour-scheme-chosen](./README%20documentation/images/colour%20scheme.png)

![Inspiration-for-colour-scheme](./README%20documentation/images/180052-film_stills-Interstellar_movie.jpg)

### Database

## Entity Relationship Diagram (ERD)

![Screenshots-of-ERDs]

### Features

Frame by Frame offers a range of interactive features designed to enhance user engagement and foster a vibrant blogging community:

- **Like/Dislike Rating System:** Users can express their opinions on blog posts by liking or disliking them. This feedback mechanism helps highlight popular content and encourages quality contributions.
- **Commenting:** Every post supports a comment section, allowing users to share their thoughts, ask questions, or engage in discussions with the author and other readers.
- **Account Registration:** Visitors can create an account to unlock additional features. Registration is quick and secure, ensuring a personalized experience.
- **Authenticated User Actions:** Registered users gain access to exclusive capabilities, including:
    - **Creating Posts:** Share your own blog entries with the community.
    - **Liking/Disliking Posts:** Interact with content by rating posts from other users.
    - **Commenting:** Participate in conversations by commenting on any post.
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


### Testing/Validation

## UI/User Story Tests

## Unit Test

## HTML

## CSS

## Python

To avoid oversaturation I've just included the more important files.

## Testing Screenshots


### Deployment

To deploy Frame by Frame, the project code is first pushed to a GitHub repository for version control and collaboration. From there, Heroku is used as the hosting platform. The repository is connected to Heroku, and necessary environment variables and dependencies are configured. After setting up static files and security settings, the application is deployed directly from GitHub to Heroku, making it accessible online.


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

I used AI in both the creative planning phase and during the coding phase. 

AI helped me brainstorm a name for the blog. On top of that, I used AI tools to come up with a colour scheme for the website.

AI was particularly helpful in speeding up certain coding sections, with its ability to create code very quickly.

AI played a key role in troubleshooting when problems did arise, in particular identifying venv issues or local packages missing.

### Technologies

- HTML5- for page structure.
- CSS3- for custom styling.
- Python- for the backend.
- Django- framework used to build this project.
- Heroku - for hosting and deployement of this project.
- Git - for version control.
- GitHub is used for setting up and managing project repositories.
- A GitHub Project Board are utilized for effectively managing tasks, tracking project progress, and ensuring efficient implementation.
- Canva.com for wireframes.
