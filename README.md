![little-origami-banner](documentation\lo-banner.png)

 An introductory website aimed at informing the reader about the evolution and transition of Jiu-Jitsu throughout the world, and how anyone can start today!

 [![GitHub Last Commit](https://img.shields.io/github/last-commit/patrickaod/Little-Origami)](https://github.com/patrickaod/Little-Origami.git) ![License](https://img.shields.io/badge/License-MIT-blue)


## Table of Contents



## Overview

![Little Origami on different screen sizes](documentation\responsive-img.png)

Little Orgiami is designed to be a seemless flow of information for the reader to understand, use, and enjoy. 

This is accomplished through three static HTML/CSS pages: 

### The First Page
The home page contains a brief overview, informational videos, and a beginner's guide. The idea was to give the impression an intrested party was in the right place and to give them the confidence to find out more. 

![Little Origami Home Page](documentation\lo-home-pg.jpeg)

### The Second Page
The history page is an animated journey of jui-jitsu from Japan to Brazil before eventually being adopted by the greater world. The animations were added for depth and entertainment, however to maintain accessabilty media queries were used to reduce the scope of applicaiton. The idea was to add a follow up to homepage to get users more involved and excited in Jiu-Jitsu. Increasing the chances of triggering action within them. 

![Little Origami History Page](documentation\lo-history-pg.jpeg)

### The Final Page
The contact page allows users to send their information and a message to a server in order to foster a community around a Jui-jitsu through Little Origami. This form of this section was updated to remove the javascipt for submission to the Code Institute. The intended code can be found in the *bugs* section. 

![Little Origami Contact Page](documentation\lo-contact-pg.jpeg)

### Additional Pages 

Two additional pages were added to increse the depth and flexability. 

#### 404 Page

The 404 page enabled the early deployment and review of the site. As content was updated so to was the page. It was design to incentavise free bug reporting and was seen as a great opportunity for user relations. 

![Little Origmai 404 Page](documentation\lo-404-pg.jpeg)

#### Confirmation Page

The confimation page adds depth to form submission experience. Thanking the user for their input before returning them to Home Page; completing their journey around the site. 

An animation rotates behind the message to give the impression of a loading screen, however this is a faccade and the page refreshes to home page on a timer. 

![Little Origami Confirmation Page](documentation\lo-confimation-pg.jpeg)

## UX

The overall design of the website was to be striking but elegent. Reflective of the current trends within the martial arts online space. 

Libral use of contrasting colours, with bold images caputes the striking element. While, the fonts and flow of the overall information tries to provide an elegence to the information.  

### Colour Scheme 

A trend among martial arts website is to use red, black, and yellow on a white background. This is a nod to the white gui adorned by the different colour belts. Grey and darker shades are generally thrown in to contast these colours. The effect is an overall refined but striking website; perfect for martial arts. 

For this project, I chose to mostly follow this trend. As the most commonly used colours where black, yellow, and red. The colour palette looks as follows: 

![Little Origami Colour Palette](documentation\lo-colour-scheme.png)

### Color Choice 

I opted to use #212529 - Eerie Black as the background because it tied the websites logo, content, and design better than a lighter alternative. 

The #FFFF00 - Yellow, FF0000 - Red, & #870000 Dark red were all chose to make the website as stiking as possible. This can be seen most clearly with the logo. Blend from light to dark red, with an accompaning bright yellow brand name. I feel this accomplishes the goal of being a stiking first impression. 

As for the document the heading were used liket this ?:
- #FFFF00 was use for the all the primary links and headings. 

- #FF0000  was used for subheadings. 

- #870000 was used as a background colour. 

- #FFFFFF was used for the primary text as to keep good contrast. 

- #000000 was used in certain instances when the background was of a lighter colour. 

### Typography

The aim of the type and icons is to create a fluid reading experience in a eastern style. 

The eastern style gives an impression of elegency and refinement, but also adds ligitmacy to any martial art. As it showcases the history of it's effectiveness through the ages. Therefore, this is a very important consideration of website, and is achieved through the following fonts & icons:
 
- [Protest Revolution](https://fonts.google.com/specimen/Protest+Revolution?query=protest+revolution) was used for the logo brand and primary headings.

- [Protest Strike](https://fonts.google.com/specimen/Protest+Strike?query=protest+strike) was used for the subheadings. 

- [Roboto](https://fonts.google.com/specimen/Roboto) was used for all the plain text.

- [Font Awesome](https://fontawesome.com) icons were used throughout the site, such as the navigation icons in the header.

- [Bootstrap Native Font Stack](https://getbootstrap.com/docs/5.0/content/reboot/) was used as a back-up collection of font families.

- Sans-Sarif was used as a final redundant font. 

Protest Revolution & Strike were a great choice to represent more tranditonal eastern styles, while Roboto creates a nice reading expience for the bulk of the content. 

The Font Awesome icons were a great addition to the website adding an extra layer of refinement, especially using the east-asia-world icon for the history navigaiton link. 

## User Stories

### New Site Users

- As a new site user, I would like to enjoy reading about my hobby, so that I can have a great day.

- As a new site user, I would like to learn about Jui-Jitsu, so that I can have more confidence to start practicing.

- As a new site user, I would like to find reputable content on Jui-Jitsu, so that I know what I'm learning is legitimate.

- As a new site user, I would like to understand how I start doing this today, so that I can start today.

- As a new site user, I would like the content to be accessible to me, so that I can enjoy my hobby.

### Returning Site Users

- As a returning site user, I would like to help contribute to the community, so that I can feel connected.

- As a returning site user, I would like to keep find new features and conent, so that I can engage more.

- As a returning site user, I would like to always see what I'm expecting, so that I can keep enjoying the content I've come to love.

## Wireframes

To follow best practice, wireframes were developed for mobile, tablet, and desktop sizes.
I've used [Balsamiq](https://balsamiq.com/wireframes) to design my site wireframes.

### Mobile Wireframes

<details>
<summary> Click here to see the Mobile Wireframes </summary>

Home
  - ![screenshot](documentation/wireframes/mobile-home.png)

About
  - ![screenshot](documentation/wireframes/mobile-about.png)

Contact
  - ![screenshot](documentation/wireframes/mobile-contact.png)

</details>

### Tablet frames

<details>
<summary> Click here to see the Tablet Wireframes </summary>

Home
  - ![screenshot](documentation/wireframes/mobile-home.png)

About
  - ![screenshot](documentation/wireframes/mobile-about.png)

Contact
  - ![screenshot](documentation/wireframes/mobile-contact.png)

</details>

### Desktop Wireframes

<details>
<summary> Click here to see the Desktop Wireframes </summary>

Home
  - ![screenshot](documentation/wireframes/mobile-home.png)

About
  - ![screenshot](documentation/wireframes/mobile-about.png)

Contact
  - ![screenshot](documentation/wireframes/mobile-contact.png)

</details>

## Features

### Existing Features

- **Bootstrap 5 - Navigation bar**

    - An easy to use navigation menu, that gives user-friendly access to all the available content on the site. This benifits the users by respecting their time. Overall positively adding to their user experience.

![Little Origami Navigation Menu](documentation\lo-nav-menu.png)

- **Bootstrap 5 Carosuel - Hero Banner**

    - A striking introductory slideshow aimed at showcasing interesting aspects of Jui-Jitsu in picture form. The focal point can then be used to draw users attention to something more specific in the future. This benefit the user by giving them a sense of what the website is about. 

![A introductory slideshow](documentation\hero-banner.png)

- **Introduction**

    - The introductory section aims to inform the reader about what the websites intent is and where to go next. The benefit to the user is the speed at which they deseren their next discission.

![Home page introduction](documentation\introduction.png)

- **{{ YOUR-TITLE-FOR-FEATURE-#3 }}**

    - Details about this particular feature, including the value to the site, and benefit for the user. Be as detailed as possible!

- **{{ YOUR-TITLE-FOR-FEATURE-#3 }}**

    - Details about this particular feature, including the value to the site, and benefit for the user. Be as detailed as possible!

- **{{ YOUR-TITLE-FOR-FEATURE-#3 }}**

    - Details about this particular feature, including the value to the site, and benefit for the user. Be as detailed as possible!

- **{{ YOUR-TITLE-FOR-FEATURE-#3 }}**

    - Details about this particular feature, including the value to the site, and benefit for the user. Be as detailed as possible!

- **{{ YOUR-TITLE-FOR-FEATURE-#3 }}**

    - Details about this particular feature, including the value to the site, and benefit for the user. Be as detailed as possible!

- **{{ YOUR-TITLE-FOR-FEATURE-#3 }}**

    - Details about this particular feature, including the value to the site, and benefit for the user. Be as detailed as possible!

![screenshot](documentation/feature03.png)

### Future Features 

- **Community Support**
    - To increase the community around Little Origami the following features could be introduced:
        - Q & A Forum
        - Message Board 
        - Dojo Review 

- **Additional Animations**
    - Additional animations would be bring more of the content to life.

- **Finding a Dojo Near You**
    - Using the Google API to find dojos near the addresses of the users, to make the value propersition of the website higher.

## Tools & Technologies Used

- [Git](https://git-scm.com) used for version control. (`git add`, `git commit`, `git push`)
- [GitHub](https://github.com) used for secure online code storage.
- [VSCode](https://code.visualstudio.com) used as my local IDE for development.
- [HTML](https://en.wikipedia.org/wiki/HTML) used for the main site content.
- [CSS](https://en.wikipedia.org/wiki/CSS) used for the main site design and layout.
- [GitHub Pages](https://pages.github.com) used for hosting the deployed front-end site.
- [Bootstrap](https://getbootstrap.com) used as the front-end CSS framework for modern responsiveness and pre-built components.

## Testing

For all testing, please refer to the [TESTING.md](TESTING.md) file.

## Deployment

The site was deployed to GitHub Pages. The steps to deploy are as follows:

- In the [GitHub repository](https://github.com/patrickaod/Little-Origami), navigate to the Settings tab 
- From the source section drop-down menu, select the **Main** Branch, then click "Save".
- The page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment.

The live link can be found [here](https://patrickaod.github.io/Little-Origami)

### Local Deployment

This project can be cloned or forked in order to make a local copy on your own system.

#### Cloning

You can clone the repository by following these steps:

1. Go to the [GitHub repository](https://github.com/patrickaod/Little-Origami) 
2. Locate the Code button above the list of files and click it 
3. Select if you prefer to clone using HTTPS, SSH, or GitHub CLI and click the copy button to copy the URL to your clipboard
4. Open Git Bash or Terminal
5. Change the current working directory to the one where you want the cloned directory
6. In your IDE Terminal, type the following command to clone my repository:
	- `git clone https://github.com/patrickaod/Little-Origami.git`
7. Press Enter to create your local clone.

Alternatively, if using Gitpod, you can click below to create your own workspace using this repository.

[![Open in Gitpod](https://gitpod.io/button/open-in-gitpod.svg)](https://gitpod.io/#https://github.com/patrickaod/Little-Origami)

Please note that in order to directly open the project in Gitpod, you need to have the browser extension installed.
A tutorial on how to do that can be found [here](https://www.gitpod.io/docs/configure/user-settings/browser-extension).

#### Forking

By forking the GitHub Repository, we make a copy of the original repository on our GitHub account to view and/or make changes without affecting the original owner's repository.
You can fork this repository by using the following steps:

1. Log in to GitHub and locate the [GitHub Repository](https://github.com/patrickaod/Little-Origami)
2. At the top of the Repository (not top of page) just above the "Settings" Button on the menu, locate the "Fork" Button.
3. Once clicked, you should now have a copy of the original repository in your own GitHub account!

### Local VS Deployement 

## Credits 

### Content

## License 

MIT License

Copyright (c) 2024 Patrick O'Doherty

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.