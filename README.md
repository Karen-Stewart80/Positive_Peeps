### Description

Positive Peeps is a social app that allows users to connect with each other. The problem with most social apps is the amount of trolling, negative comments and bullying that goes on between users. To solve this issue, I've created Positive Peeps, which users pledge to only create positive posts and messages and abstain from negative interactions. Allowing users to be a part of an uplifting community without the fear of harassment and negative judgement.

 ### Instructions

**Install python 3.9**\
$ apt-get install python3.9

**Clone repository**\
$ git clone https://github.com/Karen-Stewart80/Positive_Peeps.git

**Change directory into app**\
$ cd Positive_Peeps

**Install venv**\
$ pip install venv

**Create virtual environment**\
$ python3.9 -m venv venv

**Activate virtual environment**\
$ source venv/bin/activate

**Install dependencies**\
$ pip install -r requirements.txt

**Run app**\
$ python src/main.py

#### Purpose

The purpose of Positive Peeps is to create a social website that has a positive impact on it's users. Cyber bullying has had a detrimental impact on mental health, whether it be body-shaming or ridiculing or just making people feel like they aren't enough. Positive Peeps aims to create a welcoming, positive social community. People can  create  their own profile with their image, create positive vibe posts and send positive messages to each other. This allows members of all ages to feel safe online while still being able to be social.

#### Functionality/features

An interactive website 
A simple 5 page application
Email and password registration and signing in
Positive attitude and behaviour pledge when joining
Profile details and image update, read, create and delete
Posts create, read, update and delete
Messages create, read and delete
Logout feature when not in use

#### Target Audience

Positive Peeps website is targeted at users of all ages who wish to be social online away from negativity, bullying and online trolls. This includes people from a diverse range of backgrounds. For example people from all different ethnicities, sexual orientation, religious beliefs and education. Both adults and children. Everyone that wants to be a part of a positive and inclusive environment.

### Tech Stack

Front-end Technologies: HTML5, CSS, Python
Front-end Frameworks: ReactJS
Backend Technologies: Python
Backend Frameworks: Marshmellow, Jinja, Flask 
Database and Access Library: PostgreSQL
Deployment: AWS EC2


### Wireframes

Wireframes of Positive Peeps showing a Login Landing Page. A Profile Page where members can upload an image and describe themselves. A Post Page where users can create and share positive posts with other users. A Messages page where users can send private messages to each other and a Friends page displaying other users  they are connected with.

![Landing Page](docs/wireframes/Landing_wireframe.png)
![Profile Page](docs/wireframes/Profile_wireframe.png)
![Posts Page](docs/wireframes/Posts_wireframe.png)
![Friends Page](docs/wireframes/Friends_wireframe.png)
![Messages Page](docs/wireframes/Messages_wireframe.png)

### Application Architecture

Two diagrams showing the Application Architecture for the Application Positive Peeps 
This diagram shows the front end technologies in the blue box, which are HTML and CSS. It communicates with the backend in the purple box using Jinja, Flask Server  and Marshmellow. This communicates with the Database in the green box using postgreSQL.
![App Architecture](docs/app_architecture_diagram.pdf)

This diagram shows the Application AWS architecture
The user sees the frontend and it communicates with the backend that is stored in the AWS Cloud within the Availability Region and in a Virtual Private Cloud. It is in an EC2 instance so that it may expand with demand.
![AWS Architecture](docs/aws_architecture.pdf) 

### Data Flow Diagram

The Data Flow Diagram is for the Application Positive Peeps.
It demonstrates the flow of data from the External Entity, the user, throughout the application. From the User, it shows the Processes Create, Update/Add, Read and Delete for the Profiles, Messages, Friends and Posts all which have their data in their own tables. Arrows show the direction of data flow. Yellow circles are for CRUD process, pink rectangles are for data stores and the green large rectangle is for the user/external entity.

![Data Flow Diagram](docs/data_flow_diagram.pdf) 

### User Personas and user stories

3 Personas of people of our target audience, those wanting positive company online in a safe environment.

![User Personas](docs/user_personas.pdf)

Trello user stories
Screenshots of User stories of what a user wants from the Positive Peep Application. Including login features with email and password, to add and delete friends, messages and posts.etc.

![User Stories1](docs/trello_user_stories/user_story1.png)
![User Stories2](docs/trello_user_stories/user_story2.png)
![User Stories3](docs/trello_user_stories/user_story3.png)
![User Stories4](docs/trello_user_stories/user_story4.png)
![User Stories5](docs/trello_user_stories/user_story5.png)

### Task Management with Trello

List of tasks for T4A2- A and the start of tasks for the upcoming assignment T4A2 -B

![Task1](docs/trello_tasks/task1.png)
![Task2](docs/trello_tasks/task2.png)
![Task3](docs/trello_tasks/task3.png)
![Task4](docs/trello_tasks/task4.png)
![Task5](docs/trello_tasks/task5.png)
![Task6](docs/trello_tasks/task6.png)
![Task7](docs/trello_tasks/task7.png)
![Task8](docs/trello_tasks/task8.png)
![Task9](docs/trello_tasks/task9.png)
![Task10](docs/trello_tasks/task10.png)
![Task11](docs/trello_tasks/task11.png)
![Task12](docs/trello_tasks/task12.png)
![Task13](docs/trello_tasks/task13.png)










