# Project Plan

Team Name: The Avent Team

Pod Members: Daniel Ortiz, David Barcenas, Eva Sennrich

## Problem Statement and Description

Problem Statement:
How to have fun in a new city? This is a problem every intern will deal with, so we will build an event search + social app specifically for               professional interns who are looking to have fun AND network with other interns from other companies, best of both worlds.

Description:
The main purpose of our project is to to provide networking and excursion opportunities for professional interns looking to connect with other interns in their city, providing exploring opportunities, and help them break the ice with their own cohorts through engaging activities outside of work. As well as to provide a platform for buisnesses to seamlessly plan events for the intern cohorts of their own, guaranteed to be fun by us.

## User Roles and Personas

User Roles:
    Host
    Intern

Personas:

   Persona 1 : Phoebe, an intern at Salesforce
   Name: Phoebe Miller 
   Age: 21
   Occupation: Intern at Salesforce
   
   Phoebe is a college student from Cleveland, Ohio. She recently got accepted for an internship at Salesforce in San Francisco California. Phoebe encounters herself in a new city full of people around her age with no friends or connections, and she wants to expand her network with other interns from different companies.
   
   Persona 2 : Isaac, an intern at Crunchyroll
   Name: Issac Drew 
   Age: 23
   Occupation: Intern at Crunchyroll
   
   Isaac is a 23-year-old student who lives in Dallas Texas. He is interning at Crunchyroll in San Francisco but has always dreamed to work at Salesforce as a software engineer. He would love to have a connection that can help him achieve this by referring him to Salesforce. 
   
   Persona 3 : Mike, Program Manager of Futureforce at Salesforce
   Name: Mike Gonzalez
   Age: 30
   Occupation: Program Manager of Futureforce at Salesforce
   
  Mike is a program manager at Salesforce for the Futureforce internship at Salesforce who is assigned to create an onboarding event for the interns of this program. He would like to make this event and post it on a platform where interns can easily access it and communicate throughout a thread of comments.
  
   Persona 4 : Jane, Recruiter and Program Manager at CrunchyRoll
   Name: Jane Doe
   Age: 32
   Occupation: Recruiter and Program Manager at CrunchyRoll
   
  Jane is a recruiter and program manager at Crunchyroll looking for future candidates who want to join the company. She would like to create a casual lunch recruiting event where people can get to connect with her, expand their network and host various activities to allow the candidates an insight into the workplace.
  
## User Stories

List the current user stories you will implement: [Notion link with user stories](https://advent-app.notion.site/User-Stories-79d0cbdd1d9a43939e414bf0a25b5584)

## Pages/Screens

List all the pages and screens in the app: 
- Landing Page
- Login Page
- Register Page
- Feed Page
- Event Detail Page
- Create Event Page
- Settings Page 
- View RSVP'd Events Page
- View My Event Listings Page
- View Payment Options

Show wireframes for at least 3 of them: [Figma link](https://www.figma.com/file/zkHTcf12okEsg0OLU2AZwa/Avent-App?node-id=0%3A1)

![Landing Page](https://user-images.githubusercontent.com/85651695/180579625-bf94bab2-aefe-451d-bb03-c13503168b7e.jpg)

![Login Page](https://user-images.githubusercontent.com/85651695/180579506-6898bde9-650d-47aa-ad2f-14b29724822f.png)

![Feed Page](https://user-images.githubusercontent.com/85651695/180579539-4e1d4947-be5f-4fc0-9bdb-48fb13c66d66.png)

## Data Model

Describe your app's data model using diagrams or tables: [Figma link with data models](https://www.figma.com/file/dgE3UkEDrVKBr37VUWKzCO/Relational-Database-Diagram---Component-Kit-(Community)?node-id=3%3A728)

<img width="1297" alt="Screen Shot 2022-07-22 at 4 05 28 PM" src="https://user-images.githubusercontent.com/85651695/180579006-34df6399-a56e-47ad-87b1-4591e8832180.png">


## Endpoints

List the API endpoints you will need to implement: [Notion link with endpoints](https://advent-app.notion.site/Endpoints-50044a84683b44ed9fb6443eddf5d06d)

### Bullet List Endpoints:

- Auth route
1. POST /auth/login
2. POST /auth/register
3. GET /auth/me

- Users route
1. GET /user/:userId
2. PUT /user/:userId

- Event route
1. POST /event/create
2. GET   /event/ 
3. GET /event/:eventId
4. PUT /event/
5. DELETE /event/:eventId

- Reservations route
1. GET /reservations
2. DELETE /reservations

- Comments route
1. POST /comment/create
2. GET /comment/:commentId
3. GET /comments/:commentsectionid

### Endpoint Tables:

<img width="836" alt="Screen Shot 2022-07-22 at 3 57 57 PM" src="https://user-images.githubusercontent.com/85651695/180578564-53116bc8-1d2a-4fb6-a31b-4deea185e39d.png">

<img width="854" alt="Screen Shot 2022-07-22 at 3 58 26 PM" src="https://user-images.githubusercontent.com/85651695/180578590-41e82b6e-7a3f-4931-8c4c-31b67207c09a.png">

<img width="846" alt="Screen Shot 2022-07-22 at 3 58 54 PM" src="https://user-images.githubusercontent.com/85651695/180578619-a0ef4767-0bad-484a-a45e-d0d65b2db758.png">

<img width="851" alt="Screen Shot 2022-07-22 at 3 59 20 PM" src="https://user-images.githubusercontent.com/85651695/180578641-f9470b7e-3c0c-4b2d-a492-dfefce7ff886.png">

<img width="850" alt="Screen Shot 2022-07-22 at 3 59 44 PM" src="https://user-images.githubusercontent.com/85651695/180578673-70306194-1f9f-46e8-9cd8-885ed293f300.png">

