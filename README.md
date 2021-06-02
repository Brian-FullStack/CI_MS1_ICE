READ ME FILE

![Device Responsiveness](docs/features/responsive-devices.jpg)

[View Deployed Site](https://brian-fullstack.github.io/CI_MS1_ICE/)

Tabel Of Contents
-
- [Introduction](#IrishClimbingExperience)
- [UX](#ux)
    - [User Stories](#User-Stories)
    - [Site User Goals](#Site-User-Goals)
    - [Site Owner Goals](#Site-Owner-Goals)
    - [Wireframes](#Wireframes)
- [Features](#Features)
    - [Common Features](#Common-Features)
    - [Home Page](#Feature-1---Home-Page)
    - [First Time](#Feature-2---First-Time)
    - [Facilities](#Feature-3---Facilities)
    - [Events](#Feature-4---Events)
    - [Contact](#Feature-5---Contact-page)
    - [Booking Modal](#Feature-6---Booking-Modal)
    - [Features Left to Implement](#Features-Left-To-Implememt)
- [Technologies Used](#Languages,-Frameworks-and-Technologies-Used)
- [Testing](#Testing)
    - [Testing User Stories](#Testing-User-Stories)
    - [HTML Validation](#HTML-Validation)
    - [CSS Validation](#CSS-Validation)
    - [Lighthouse Testing](#Lighthouse-Testing)
    - [Bugs in Development](#Bugs-in-Development)
- [Deployment](#Deployment)
- [Credits](#Credits)
- [Media](#Media)
- [Acknowledgements](#Acknowledgements)



# Irish Climbing Experience
The aim of this project is to create a responsive website for an indoor climbing gym Irish Climbing Experience (ICE). The idea for this website came from a conversation with some climbers who expressed frustration because they didn’t have any facility where they could train during the winter months.
Irish Climbing Experience is designed to be the hub of climbing in the north west of Ireland. With the sport of climbing gaining in popularity and in 2021 being the first year for climbing to be included in the Olympic Games, ICE is set on inspiring climbers and to create a new generation of climbers in Ireland. 

# UX 
Users of this website will need an easy to navigate site which guides them to the information they are looking. It should inform users of the facilities which ICE offers as well as information on prices, opening times and booking. This website satisfies these needs and more by having a navigation bar which informs the user what page they are currently on as well as linking to the other pages that they might be looking for. The use of images which relate to what the climbing gym looks like give the user an idea of the facilities, walls and some of the equipment that the will be using when they come to the gym.

## Site Demographic
___
-	Climbers live/travel to the north west of Ireland.
-	Families
-	Couples/Friends
-	People looking for adventure.
-	People who are interested in the sport.
-	Team building groups.
-	Physically active people.
-	Problem Solvers

# Design

## Colours
 The colours that I chose to use in this site were taken from coolors.co. I used an orange and a bright blue because I wanted to use colours which envoke playfulness and friendliness in the users of the site. In both the Navigation Bar and Footer i used a darker navy/black which adds contrast for the white font.
 
  I tried to use the colours in a consistant and logical way by having:
  - All buttons and links in Blue 
  - All large paragraphs in Orange
  - Navigation and Footer in Navy/Black

![Color Pallet Used](docs/features/color-pallet.jpg)

## Images
The images I decided to use in this site all came from unsplash.com. I wanted the images used to have similar colours in them as the colour scheme that I had chosen. This is to make the site feel more cohesive and and to emphasise the companys brand colours. 

## User Stories
_________________
### Site User Goals
1. As a user I want to easily find the information that I'm looking for.
2. As a user I want to find out how much it costs to climb at this gym.
3. As a user I want to find out the opening times for this gym.
4. As a user I want to find out what facilities this gym has to offer.
5. As a user I want to be able to book a slot.
6. As a user I want to find out the location of this gym.
7. As a regular user I want to find out about up comming events.
8. As a user I want to get an idea of what climbing at this gym will be like.

### Site Owner Goals
1. As a site owner I want a professional responsive website.
2. As a site owner I want to showcase the facilities at our climbing gym.
3. As a site owner I want to have a way for customers to contact us.
4. As a site owner I want to have booking form for guests to book before thy arrive.
5. As a site owner I want to promote up coming events and training courses at our climbing. 

## Wireframes
___
Wireframes for each page as desktop, tablet and mobile can be found here:

[Home Page](docs/wireframes/Home-Page-Wireframe.jpg),
[First Time](docs/wireframes/First-Time-Wireframe.jpg),
[Facilities](docs/wireframes/Facilities-Wireframe.jpg),
[Events](docs/wireframes/Events-Wireframe.jpg),
[Contact](docs/wireframes/Contact-Wireframe.jpg)


# Features

## Common Features
There are two common features which appear on every page.
1. Navigation Bar
2. Footer

## Navigation Bar
- I desigined the navigation bar using Bootstrap 4 template. I felt that it was the best way to make navigating the site as intituive as possible.
- The navigatin bar is responsive on small screens thanks to Bootstrap 4.

![Navigation Bar](docs/features/Navigation-bar.jpg)

## Footer
- The footer is used to add extra information about Irish Climbing Experience such as: Address and links to social media.
- In keeping with the rest of the site I choose to keep the social media icons the same colour as all other bittons in the site.

![Footer](docs/features/footer.jpg)

### The user stories that this feature covers are:
1. As a user I want to easily find the information that I'm looking for.
1. As a site owner I want a professional responsive website.

## Feature 1 - Home Page
_____
The Home Page consists of four main sections.

1. Hero Image and a call to action button.
2. Carousel with images and links to other pages.
3. About Us which gives a brief overview of what the company is aiming to achieve.
4. Come Find Us aims to add relevent information about the gym.
### Section 1 - Hero Image and Call To Action
- I chose an image of a lady absailing because it is evokes the feeling people will have when they come to Irish Climbing Experience.

- The general background colours in the image are similar to the colour scheme throughout the site. 

- I used an opaque overlay to add contrast between the image the hero text.

- The call to action button is important to this section as it invites the user to make a booking.

![Hero Image and call to action](docs/features/home-screen-hero.jpg)

### Section 2 - Carousel

- This was created using a Bootstrap 4 template. Origionally I had used bootstrap cards but realised that adding a carousel added more life to this static site.

- The images and text are an indication of what the respective page is about when they follow the link.

- I replaced the default carousel controls with font awsome icons which increased contrast with the image.

![Carousel Section](docs/features/home-screen-carousel.jpg)

### Section 3 - About Us

- This section highlights what to company is about and trying to achieve. 

- I used a contrasting background for this section to make it more eye catching.

- All of the compy in this section as well as the copy throughout this site was wrote by myself.

![About Us Section](docs/features/home-screen-about.jpg)

### Section 4 - Come Find Us

- This section is designed to tell the user where the climbing gym is located and what times it is opened.

- The map is embeded from Google maps.

- I added the waiver form because I felt that the negitive space was unbalanced with the rest of the page.

- I added a font awsome download which navigates to an example waiver form. I have given the icon the same color as all other buttons/links on the site to keep consistancy thoughout the page.

![Come Find Us Section](docs/features/home-screen-come-find-us.jpg)

### The user stories that this feature covers are:
1. *As a user I want to easily find the information that I'm looking for.*
3. *As a user I want to find out the opening times for this gym.*
6. *As a user I want to find out the location of this gym.*

## Feature 2 - First Time
_____
The First Time page consists of three sections.

1. Hero Image and About section.
2. Price List section.
3. What to Expect section.

### Section 1 - Hero Image and Heading
- I used the image for this section because it shows a stricking position of a climber.
- The header text is used to make the first time user feel welcomed.
- I reused the opaque overlay on this image to increase the contrast of the text with the image in the background.

![First Time Page Hero Image](docs/features/first-time-hero.jpg)

### Section 2 - Price List
- This section is build using Bootstrap 4 cards.
- I the user gets a clear display of the prices of both members and non-members.
- I used the bootstrap class "shadow" to make the three seperate cards stand out.

![Price List Section](docs/features/first-time-price-list.jpg)

### Section 3 - What to Expect
- I used this section to give a detailed overview of exactly what first time climbers can expect when they arrive.
- I gave the background a contrasting colour to make it more eye catching.

![What to Expect Section](docs/features/first-time-what-to-expect.jpg)

### The user stories that this feature covers are:
2. *As a user I want to find out how much it costs to climb at this gym.*
8. *As a user I want to get an idea of what climbing at this gym will be like.*

## Feature 3 - Facilities
___
The Facilities Page has two sections:

1. Hero Image and About
2. Features List

### Section 1 - Hero Image and Heading
- This section gives users a brief overview of the size of the walls aswell as some of the facilities in the gym.
![facilities section hero image](docs/features/facilities-hero.jpg)

### Section 2 - Facilities List
- This section goes into more detail about each facility and type of climbing offered at Irish Climbing Experience.
- I created seperate boxes which hold an image of that particular activity and a more detailed discription of what is involved.
- The copy in this section is adapted from climbinggeargeek.com.
- This section has a contrasting background to make each box stand out. 

![Facilities List Top](docs/features/facilities-list-1.jpg)
![Facilities List Top](docs/features/facilities-list-2.jpg)

### The user stories that this feature covers are:
4. *As a user I want to find out what facilities this gym has to offer.*
2. *As a site owner I want to showcase the facilities at our climbing gym.*

## Feature 4 - Events Page
___
The Events Page consists of three sections:

1. Hero Image and Heading
2. Event Cards
3. Registration Modal
#### Section 1 - Hero Image and  Heading
 - This section lets users know what positives can come from taking part in one of the events.
 - It also lets users know that registration is required for taking part in events.

 ![Event Hero Image](docs/features/events-hero.jpg)

 #### Section 2 - Event Cards

- This section was build using Bootstrap 4 cards.
- This section gives users a place to find all the events and courses which are on in Irish Climbing Experience.
- Each card has a registration button which prompts a modal to open up.

![Event Cards](docs/features/events-cards-1.jpg)
![Event Cards](docs/features/events-cards-2.jpg)

 #### Section 3 - Registration Modal
 - This section was built using a Bootstrap 4 template.
 - This section gives users the option to register for an event.

![Registration Modal](docs/features/events-modal.jpg)

### The user stories that this feature covers are:
7. *As a regular user I want to find out about up comming events.*
5. *As a site owner I want to promote up coming events and training courses at our climbing.* 

## Feature 5 - Contact Page
___
The Contact Page consists of two sections:

1. Contact Form section
2. Registration and Waiver section

### Section 1 - Contact Form
- This section is used to let guests get in contact with the climbing gym.
- I added a shadow to this section to make it stand out from the background.

![Contact Us Form](docs/features/contact-us-form.jpg)

### Section 2 - Registration and Waiver
- This section is added for guests to be aware of any dangers that can be involved with climbing.
- I added a contrasting background to seperate this section from the form section.
- It includes a downloadable example waiver form which I obtained from amazonaws.com

![Registration and Waiver box](docs/features/contact-us-registration.jpg)
![Registration and Waiver box](docs/features/contact-us-waiver.jpg)

### The user stories that this feature covers are:
4. *As a site owner I want to have a way for customers to contact us.*
8. *As a user I want to get an idea of what climbing at this gym will be like.*

 ## Feature 6  - Booking Modal
 ___
- The Booking Modal is created using Bootstrap 4 modal template.
- This section is located on every page via the navbar.
- I added custom HTML and CSS to the Bootstrap modal to style and layout the form.
- The confirm button and rest button both use th colour scheme which is found thoughout the rest of the site.

![Booking Modal](docs/features/booking-modal.jpg)

### The user stories that this feature covers are:

5. *As a user I want to be able to book a slot.*

### Features Left to Implement
- In the future I would like to implement a members Log In page for gym members.
- I would like to add the colour coded grading chart used for specifing the route grade in the climbing gym.
- I think this page would benifit from adding a place where people can leave reviews about the climbing gym.
- I think adding a promotional video of the climbing gym would give users a great idea of what exactly this climbing gym is like.

# Languages, Frameworks and Technologies Used

- [HTML](https://html.com/html5/) is used for adding all the copy and images to each page as well as creating forms and lists.

- [CSS](https://www.w3schools.com/Css/) is used throughout this project to style the overall website.

___

- [Bootstrap 4](https://getbootstrap.com/) came in very usefull when making the site responsive across a range of devices as well as a source of information.

- [Coolers](https://coolors.co/) is wehere I fould the colour pallet used throughtout this site.

- [Font Awsome](https://fontawesome.com/) was used for adding Icons such as social icons, map pin, clock and download icon.

- [Unsplash](https://unsplash.com/) was where I got of the images on this site license free.

- [GitHub](https://github.com/) is used as a remote repository for the projects source code.

- [Git](https://git-scm.com/) was used to commit and push the code to GitHub.

- [Visual Studio Code](https://visualstudio.microsoft.com/) is the IDE i used for writing the code for this project.

- [Google Maps](https://www.google.ie/maps) was used for embeding the map in the come find us section.

- [Balsamiq](https://balsamiq.com/) was used for creating wireframes for all pages.

- [Image Resizer](https://imageresizer.com/) is where I reduced the size of the images inorder to reduce the loadtime of each page.

- [favicon.io](https://favicon.io/) is the site I used to create the site icon.

# Testing

## Testing User Stories
___
*1.  As a user I want to find out how much it costs to climb at the gym.*
| Feature | Action | Expected Result |  Actual Result |
|---------|--------|-----------------|---------------|
|Price Table in the First Time Page | To achieve this the user navigates to the First Time page in the navigation bar.| I expect that the user will find the information that they are looking for.| Worked as expected|

[See image result Here](docs/testing/testing-user-story-1.jpg)
___

*2. As a user I want to find out the opening times for this gym.*
| Feature | Action | Expected Result |  Actual Result |
|---------|--------|-----------------|---------------|
|Opening Times in the Come Find Us Section| User needs to scroll down to the Come Find Us section on the Home page |The user will find opening times for weekdays and weekends| Worked as expected|

[See image result Here](docs/testing/testing-user-story-2.jpg)
___

*3. As a user I want to find out what facilities this gym has to offer.*
| Feature | Action | Expected Result |  Actual Result |
|---------|--------|-----------------|---------------|
|Facilities Page|User will click on the Facilities link in the navigation bar| When user follows the Facilities link they will find information on all facilities avaliable at the gym| Worked as expected.|

[See image result Here](docs/testing/testing-user-story-3.jpg)
___
*4. As a user I want to be able to book a climbing slot before I go to the gym.*
| Feature | Action | Expected Result |  Actual Result |
|---------|--------|-----------------|---------------|
|Booking Button| User will click on the Booking link in the navigation bar.| When user clicks the booking button a model form will pop up for the user to book a visit.|Worked as expected.|

[See image result Here](docs/testing/testing-user-story-4.jpg)
____
*5. As a user I want to find out the location of this gym.*
| Feature | Action | Expected Result |  Actual Result |
|---------|--------|-----------------|---------------|
|Come Find Us Map. Footer Address.|User needs to scroll down to the come find us section of the home page to find a map or to the footer of any page to find the address.|When user scrolls down to the come find us section or footer they will find the address and a map of where the gym is located.| Worked as expected.|

[See image result Here](docs/testing/testing-user-story-5.jpg)
___
*6. As a regular user I want to find out about up comming events.*
| Feature | Action | Expected Result |  Actual Result |
|---------|--------|-----------------|---------------|
|Events Page|User will click on the Events link in the navigation bar| When user clicks on the Events link they will find information on upcoming events|Worked as expected|

[See image result Here](docs/testing/testing-user-story-6.jpg)

___
*8. As a user I want to get an idea of what climbing at this gym will be like.*
| Feature | Action | Expected Result |  Actual Result |
|---------|--------|-----------------|----------------|
|Site Images|User gathers a feeling of the experience they will have by going through the site|As the user navigates through the site the abundance of images and discriptive language will discribe what its like to climb in the gym.|Worked as expected.|


## Testing Site Owner Goals
___
*As a site owner I want a professional responsive website.*
| Feature | Action | Expected Result | Actual Result |
|---------|--------|-----------------|---------------|
|In built resposniveness|Site owner will view the site on Desktop, Tablet and Mobile|The site will change its display according to the device with its being viewed on|Worked as expected|

[See image result Here](docs/features/responsive-devices.jpg)

___

*As a site owner I want to showcase the facilities at our climbing gym.*
| Feature | Action | Expected Result | Actual Result |
|---------|--------|-----------------|---------------|
|Facilities Page.|The site owner will navigate to the facilities page.|Both site owner and user will find information and images about the facilities.| Worked as expected|

[See image result Here](docs/testing/testing-user-story-3.jpg)

___
*3. As a site owner I want to have a way for customers to contact us.*
| Feature | Action | Expected Result | Actual Result |
|---------|--------|-----------------|---------------|
|Contact Form|Site owner can navigate to the contact page and scroll down|The contact form will be suitable for guests getting in touch with the gym| Worked as expected|

[See image result Here](docs/testing/testing-user-story-7.jpg)
___
*4. As a site owner I want to have booking form for guests to book before thy arrive.*
| Feature | Action | Expected Result | Actual Result |
|---------|--------|-----------------|---------------|
|Booking Modal|Click on the booking button in the navigation bar|The booking button will popup a form for guest to fill out|Worked as expected|

[See image result Here](docs/testing/testing-user-story-4.jpg)

___
*As a site owner I want to promote up coming events and training courses at our climbing.*
| Feature | Action | Expected Result | Actual Result |
|---------|--------|-----------------|---------------|
|Events Page Cards| The site owner will navigate to the events page and scroll down the the cards |The events cards will have information about up comming events|Worked as expected.|

[See image result Here](docs/testing/testing-user-story-6.jpg)

### HTML Validation
___
I used [W3C Validator](https://validator.w3.org/) to validate HTML on each page.


Initally I recieved 3 errors:
1. Error 1: "Element "div" not allowed as child of element "ul" in this context."

Fix: I fixed This error by changing the "btn-group" from a "div" to a "li".

2. Error 2: "Bad value # for attribute method on element form."

Fix: I simply fixed this error by removing the method in the form tag since it is not needed for this project.

3. Error 3: "Attribute type not allowed on element textarea at this point."

Fix: I fixed this error by removing "type="text" attribute from the textarea element.

After I addressed these issues all pages passed with 0 errors and 0 warnings.

- Home

![Home No Errors](docs/testing/home-no-error.jpg)

- First Time

![First Time No Errors](docs/testing/first-time-no-errors.jpg)

- Facilities

![Facilities No Errors](docs/testing/facilities-no-error.jpg)

- Contact

![contact No Errors](docs/testing/contact-no-error.jpg)

- Facilities



![Facilities No Errors](docs/testing/facilities-no-error.jpg)

### CSS Validation
___
I used [Jigsaw CSS Validator](https://jigsaw.w3.org/css-validator/) to validate my CSS.

My CSS came back with No Errors Found.
![CSS No Errors](docs/testing/css-no-errors.jpg)

For any scenarios that have not been automated, test the user stories manually and provide as much detail as is relevant. A particularly useful form for describing your testing process is via scenarios, such as:

1. Contact form:
    1. Go to the "Contact Us" page
    2. Try to submit the empty form and verify that an error message about the required fields appears
    3. Try to submit the form with an invalid email address and verify that a relevant error message appears
    4. Try to submit the form with all inputs valid and verify that a success message appears.

### Lighthouse Testing

![Lighthouse Score](docs/testing/lighthouse-score.jpg)

### Responsiveness
Throughout this project I used Google Chrome Dev Tools to see how responsive the site was as I built it.
Once I deployed the project I used all devices available to me to see how the site worked on each one.
The devices included:
- Lenovo Ideapad C340
- Huawei P30 Pro
- iPad
- iPhone 8+


# Bugs in Development
Bug - On all pages I had a horizontal scroll bar.
Fix - To fix this I referenced Stack Overflow where I learned to add "overflow: hidden;" to the "body" in CSS.

Bug - When viewed on a tablet the Come Find Us section wasnt responsive.
Fix - To solve this issue I referenced Code Institute lesson on creating the footer in the Resume project. I was reminded to add "class-"col-12 col-md-6 col-lg-4"" to all three divs. This pushed the waiver down to a new line and put the other two divs in two col-6 on the same line.

Bug- On the Facilities pageI had trouble with two images streching on large screen sizes.
Fix - I referenced Stack Overflow and learned about "Object-fit: cover;" This has helped the image from streching too much.

Bug - Dropdown navigation menu was too hard to read on small screen sizes due to a transparent background.
Fix - To solve this problem I added a media qurey for a dark background on .navbar-collapse.

Bug - I felt that there was too many Booking buttons in the home page. When the navigation menu dropped down I felt that the buttons were too close.
Fix - I added a media query so that the Booking button in the navbar on only the Home Page would be removed. 

Bug - The Booking modal on mobiles had no way of being dismissed unless it was filled out and confirmed.
Fix - To fox this I changed the Reset Button to a Close Button so users could escape from the booking modal if they didnt want to fill out the form.

Bug - The white text on the Hero image was a little difficult to read on certain pages. 
Fix - I fixed this by adding an opaque overlay on top of each image. This increased contrast and made the text easier to read.

Bug - U

If this section grows too long, you may want to split it off into a separate file and link to it from here.

# Deployment

### Git Hub Pages
I deployed this website using GitHub pages. The process I used is as follows:
1. I logged into my Github account and selected my MS1 project from my repositories.
2. I clicked on 'Settings' in the repository.
3. In the menu on the left i clicked on 'Pages'.
4. I then clicked on 'Source'.
5. I clicked on the dropdown menu that said 'None' and then selected 'Main'.
6. After the page reloaded I clicked on the link to the deployed site.

### Forking this GitHub Repository
Follow these steps to fork the GitHub Repository
1. Log into GitHub and find the repository.
2. Click the 'Fork' button located in the top right of the page.
3. This will make a copy of the repository on your own GitHub account.

### Clone this Repository
 To make a local clone of this repository follow these steps:
 1. Log into GitHub and find the repository.
 2. Click on the 'Code' button.
 3. To clone the repository using HTTPS, copy the url.
 4. Open Git and change the current working directory to where you want the cloned directory to be made.
 5. In the terminal type 'git clone' followed by the https url.
 6. Press enter
 7. The local clone will be created.


# Credits

### Content
- The copy for this website was written by myself. 
- All of the photos used in this site were obtained from Unsplash.com
- The sample waiver form was obtained from [amazonaws.com](https://s3.amazonaws.com/craft-prod-assets/documents/2018-Sample-Waiver-and-Release.pdf)

### Code
- [W3C Schools](https://www.w3schools.com/css/css3_gradients.asp) is where I learned to place a gradient on the hr under the headers.
- [Bootstrap](https://getbootstrap.com/) is where I got code blocks for:
    - Navbars
    - Modals 
    - Cards
    - Carousel
- [Dani Krossing](https://www.youtube.com/watch?v=kPtS4vO42II) a youtube video helped me create the .htaccess file for my 404 page.
### Acknowledgements
- I gathered most of my inspiration ofr this project from my local climbing club, the experience of friends aswell as my own personal experience.
- I really appreciated the support from CI community on Slack.
- I would like to thanks to my mentor Mo from whom I received great feedback and advice throughout this project.
