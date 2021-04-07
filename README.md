# Day Trips South Wales

![Day Trips South Wales Mockup Images](assets/readme-files/mockup-image.png)

[View the live project here](https://cosminaserbanica.github.io/CI-MS1-DayTripsSouthWales/)

## Table of contents
1. [Introduction](#Introduction)
2. [UX](#UX)
    1. [Ideal User Demographic](#Ideal-User-Demographic)
    2. [User Stories](#User-Stories)
    3. [Development Planes](#Development-Planes)
    4. [Design](#Design)
3. [Features](#Features)
    1. [Design Features](#Design-Features) 
    2. [Existing Features](#Existing-Features)
    3. [Features to Implement in the future](#Features-to-Implement-in-the-future)
4. [Issues and Bugs](#Issues-and-Bugs)
5. [Technologies Used](#Technologies-Used)
     1. [Main Languages Used](#Main-Languages-Used)
     2. [Additional Languages Used](#Additional-Languages-Used)
     3. [Frameworks, Libraries & Programs Used](#Frameworks,-Libraries-&-Programs-Used)
6. [Testing](#Testing)
     1. [Testing.md](TESTING.md)
7. [Deployment](#Deployment)
     1. [Deploying on GitHub Pages](#Deploying-on-GitHub-Pages)
     2. [Forking the Repository](#Forking-the-Repository)
     3. [Creating a Clone](#Creating-a-Clone)
8. [Credits](#Credits)
     1. [Content](#Content)
     2. [Media](#Media)
     3. [Code](#Code)
9. [Acknowledgements](#Acknowledgements)
***
## Introduction

This website was designed for a fictional, but potential travel business based in South Wales whose main objective is organising day trips to famous landmarks. The purpose of the website is to create an online presence, allowing customers to find information about the business and the services provided. 

This is the first Milestone Project a student must complete as part of the Web Applications Development Program at Code Institute.

The main requirements were to make a responsive and static responsive website with a minimum of three pages using primarily **HTML5** and **CSS3**.


## UX 

### Ideal User Demographic
#### The ideal user of this website is:
- New customers
- Current customers

### User Stories
#### New Customer Goals:
1. As a new customer, I want to easily navigate through the website to find relevant information about the services provided.
2. As a new customer, I want to be able to find out easily what the business does and who provides the service.
3. As a new customer, I want to find out how the service is provided.
4. As a new customer, I want to easily find information about the quality of the service from previous customers.
5. As a new customer, I want to be able to see proof of the service, such as pictures, videos or locations.
6. As a new customer, I want to easily get in touch with the business to enquire additional information or to book the service.
#### Current Customers Goals:
1. As a current customer, I want to easily navigate through the content in order to book the service again.
2. As a current customer, I want to be able to get in touch easily with the business.
3. As a current customer, I want a dedicated area where my opinions on the service can be published.

### Development Planes
In order to develop and promote a customer-centric business whose main goal is to sell a service, the website has been designed based on:
#### Strategy
The targeted audience:
- Locals looking for a daily activity
- Locals looking to meet other people while exploring the landmarks
- Tourists visiting South Wales
- Outdoor lovers interested in nature
- Age group: suitable for any age group

The **user** can use the website to:
- Find information about the business and who runs it
- Find information about the service, such as tour details, pictures, videos and locations
- Find information about how the service has been provided from previous users
- Enquire additional information and book the service
- Get in touch with the business via social media platforms

The **business** can use the website to:
- Introduce themselseves to the user and promote the day trips options
- Add new trip options or update the service
- Attract new customers by sharing previous customers experiences
- Receive customer enquiries or booking requests
- Create an online presence in order to gain customer trust

#### Scope
After defining the strategy, the scope was developed based on the following requirements:
- **User Requirements**
     - The user will be looking for:
          - Information about what the business does
          - Information about who provides the service and how do they do it
          - Opinions on the service from previous users
          - Details of what the service includes and how the service looks like
          - Options on how to book the service or get in touch with the business
          - Options on which service to book
          - Find the business on social media
- **How the user requirements have been met**
     - The user will be able to:
          - Navigate through the site with minimum clicks in order to find the information they want
          - Be able to find links to external sites in order to:
               - Find pick-up/ drop off locations
               - Find out about additional activities provided by other business
               - Book additional activities
          - Get in touch with the business through a form that offers multiple options based on user intention
          - Get in touch with the business via social media links

#### Structure
With the previously identified strategy and scope, the ideal structure was agreed to match the following diagram:
![Site structure](assets/readme-files/structure-tree.png)

#### Skeleton
**Skeleton** has been put together using [Balsamiq wireframes](https://balsamiq.com/ "Link to Balsamiq wireframes")
- Wireframes for desktop: 
![](assets/readme-files/desktop-wireframe.PNG)
- Wireframes for Ipad:
![](assets/readme-files/ipad-wireframe.PNG)
- Wireframes for smarthphone:
![](assets/readme-files/smartphone-wireframe.PNG)

### Design

#### Colour Scheme
The main colours used throughout the website are Black for text and White for background for the first and second page. White font has been used on the Book Now page to be visible on the background image.


#### Typography
The fonts used are [Bangers](https://fonts.google.com/specimen/Bangers "Link to Bangers Google Font") for the Logo situated in the navbar with Cursive as the fallback in case of import failure and [Bree Serif](https://fonts.google.com/specimen/Bree+Serif "Link to Bree Serif Google Font") Bree Serif font  is used throughout the website with Sans Serif as the fallback font in case of import failure. 


#### Imagery
The imaages selected have been used with a main purpose of promoting the Welsh landmarks and the service provided. 

The images used for the Navbar, Pen-Y-Fan and Brecon Waterfalls sections are from personal archive.

The carousel and the Book Now background demanded good quality pictures taken at high resolution, which is why I have used images provided by [Unsplash](https://unsplash.com/ "Link to https://unsplash.com/").

The images used for the Margam Park section have been provided by [Dreamstime](https://www.dreamstime.com "Link to https://www.dreamstime.com").

## Features

### Design Features
Every page contains relevant information about the business and the service, which has been made responsive to adjust on different screen sizes:
- The **Header** contains a **logo** in the top left of the page which will redirect users back to the Home page and a **navigation bar** in the top right of the page. The **Our Trips** navigation link contains a collapsible menu which displays links to the different sections of the Our Trips page.
- On smaller screens, the navigation bar collapses into a **toggler** icon which will reveal the navigation links when clicked.
- The **Footer** contains social media icons where the user can connect with the business.
- Both the **Header** and the **Footer** are available on all pages for consistency.

<dl>
  <dt><a href="index.html" alt="Day Trips South Wales Home Page">Home Page</a></dt>
  <dd>The Home Page is divided four sections:
     <ul>
          <li><strong>The headline</strong> - Contains a "motto" text describing what a potential user would want to achieve from buying the service, the price for the service and a button redirecting the user to the second page, where the service is further described.
          </li>
          <li><strong>Carousel Container</strong> - To provide a preview of the places to visit, and also to give information in the caption about who runs the business, what the business does and how do they do it.
          </li>
          <li><strong>Meet the team</strong> - This section is meant to introduce the user to the individuals running the business. Therefore, the section contains two pictures with each member of the team and what their role is in the service. This section is being displayed as a row on desktop and as columns on smaller screens.
          </li>
          <li><strong>Testimonials section</strong> - This section contains three testimonials from previous users with the goal of providing more information to new customers. On desktop the section is being displayed as a row and as columns on smaller screens. Hover effect has been added to highlight each review.
          </li>
     </ul>
  </dd>

<dl>
  <dt><a href="our-trips.html" alt="Day Trips South Wales Our Trips Page">Our Trips</a></dt>
  <dd>The Our Trips Page is divided three sections, one for each location of the trip:
     <ul>
          <li><strong>Pen-Y-Fan</strong> - The section contains two columns, which are displayed as a row on desktop, and fall one under each other on smaller devices. One column contains Tour Details and a button which directs the user to the Book-Now page. External links have been added for further information about the pick up/ drop off locations. The other column contains a View more section, with pictures, an iframe for video and an iframe for location of the landmark.
          </li>
          <li><strong>Brecon Waterfall</strong> - The same layout as the previous section has been kept for consistency. The only difference is that in this section, the View more column is being displayed before the Tour details. This decision was taken to enhance the design.
          </li>
          <li><strong>Margam Park</strong> - The same layout as the previous sections has been kept for consistency. External links have been added for additional tours, which direct the user to the external provider.
          </li>
     </ul>
  </dd>

  <dt><a href="book-now.html" alt="Day Trips South Wales Book-Now Page">Book Now!</a></dt>
  <dd>The Book Now! page containes one background image covering the entire screen and a Bootstrap accordion for the contact form:
     <ul>
          <li><strong>Background image</strong> - This image has been selected with a customer-centric goal in mind, in order to further show the users what they can get from the booking the service.
          </li>
          <li><strong>Contact Form</strong> - For the contact form I have decided to use a Bootstrap Accordion in order to give the user two options: one for asking general qustions and one for booking the trip. This is to facilitate the contact with the business. 
          </li>
     </ul>
  </dd>
