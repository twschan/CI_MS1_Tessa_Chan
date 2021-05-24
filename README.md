# <h1 align="center">Tessa Chan</h1>
![Mock Up](docs/mockup/mock-up.png)

A deployed link to the website can be found [here](https://twschan.github.io/CI_MS1_Tessa_Chan/)

## Goal For this Project
Welcome to Tessa Chan Designs! This is a portfolio website showcasing range of her past and latest projects as a graphic designer.
On this site you can find relevant information you need as a visitor, which grouped together in an appealing and accessible on a 
range of devices. The website is personalised by providing some information about the designer and images of her past and latest projects.

## Contents

* [User experience (UX)](#user-experience-(ux))
     + [User Goals](#user-goals)
     + [Site Owner Goals](#site-owner-goals)
* [User Requirements and Expectations](#user-requirements-and-expectations)
    + [Requirements](#requirements)
    + [Expectations](#expectations)
*  [Design Choices](#design-choices)
    + [Colour Scheme](#colour-scheme)
    + [Typography](#typography)
    + [Icon](#icon)
    + [Imagery](#imagery)
    + [Structure](#structure)
*  [Wireframes](#wireframes)

  * [Features](#features)
     + [Existing Features](#existing-features)
     + [Features to Implement in the future](#features-to-implement-in-the-future)

  * [Technologies](#technologies)
     + [Languages Used](#languages-used)
     + [Libraries Frameworks and Programs Used](#libraries-frameworks-and-programs-used)

  * [Testing](#testing)

  * [Deployment](#deployment)

  * [Credits](#credits)

  * [Acknowledgements](#acknowledgements)



---
# User experience (UX)

### User Goals
* A website filled with valuable content 
* Website should be easy to use on a desktop, tablet and mobile
* Appealing visual elements
* Contact details should be easy to find
* A form to contact designer directly from site
* Website with creative call-to-actions
* Easy to navigate throughout the site to find content 

#### First Time Visitor Goals
1. As a First Time Visitor, I want to easily understand the main purpose of the site and learn more about the designer.
2. As a First Time Visitor, I want to easily find out information about the designer.
3. As a First Time Visitor, I want to be able to find the website is easily accessible and stand out from other designers.
4. As a First Time Visitor, I want to locate their social media links to see their followings on social media to determine how trusted and known they are.
5. As a First Time Visitor, I want to find information about her projects and various images about her designs.
6. As a First Time Visitor, I want to be able to reach out to the designer via the website.


#### Returning Visitor Goals
7. As a Returning Visitor, I want to find information and updates about her latest projects.
8. As a Returning Visitor, I want to find the best way to get in contact with the designer with any questions I may have.
9. As a Returning Visitor, I want to be able to get a downloadable CV of the site owner to easily share with others.

#### Site Owner Goals
10. As a site owner, I want users to see projects that showcase skills and growth.
11. As a site owner, I want to connect to potential jobs and projects.
12. As a site owner, I want users to be able to contact the site owner easily for hire opportunities, collabrations and networking.

### User Requirements and Expectations

#### Requirements
* Easy to navigate by using the navigation menu
* Appealing visual elements
* Clear information about the designer
* Relevant content about each projects
* Easy way to contact the designer

#### Expectations
* When clicking on links e.g social media, I expect the page to open in a seperate browser.
* I expect a message to be entered when submitting the contact form and that the form has been submitted correctly.
* I expect the navigation links to work properly so that it takes me to wherever I want to go.
* Clear information on each projects.

#### [Back to top](<#contents>)
---

# Design Choices

The style will be based on a minimalistic and simplicity approach that shows of the designer's
projects and make it more eye catching, a website that is subtle with good readability also an easy flow and navigation.
As this is a personal portfolio for the designer, the main inspiration and 
decisions will come from the designer own personal designs.

### Colour Scheme
The colour scheme are mostly muted tones to give the subtleness to the website and also to make the images stand out.

![colour scheme](docs/wireframe/colour-scheme.jpg)
* #F2F2F2 Light Gray - Primary background-colour use to bring attention to design 
elements, good for dark on light designs.
* #E7E1D3 Beige - Secondary background-colour can go well with lighter tone images.
* #FDEADD Pale Orange - Overlay colour on buttons when hovered or selected and call-to-actions buttons.
* #5B5B5B Dark Gray - Header and text colour use on light designs.

### Typography 
To keep a modern style and for easy readability, the font used are Montserrat for headings
and Raleway for general text with Sans Serif as the fallback font incase for any reason the font isn't being
imported into the site correctly. These are taken from [Google](https://fonts.google.com/?preview.size=26&preview.text_type=custom&preview.text=TESSA%20CHAN) fonts library.

### Icon
I have decided to implement icons, using the [Font Awesome](https://fontawesome.com/) library.
The icons are designer's social media, a back-to-top arrow and hamburger icon for smaller media.

### Imagery
Imagery is important for a graphic designer portfolio, so choosing good images will
catch the users attention. All of the projects, logo and private owned images are from 
the site owner and the portrait used are the site owner photo.

### Structure
This website will consist four seperate pages a homepage (index.html), portfolio page, about page and a contact page with a contact form and also a link to download CV.
I have will be using [Bootstrap](https://getbootstrap.com/) to create an overall structure 
for the website, a Modal component to create the contact form and Carousel component for images for 
the homepage, the navigation bar will also be fixed on top. A responsive design will be added to the navbar and on small/mobile devices it will
condense into a hamburger icon that will have a toggle to view the nav menu and it's associated links.
This will save screen space and keep to conventions users are expecting.
#### [Back to top](<#contents>)
---

# Wireframes
The wireframes are created by using the program [Balsamic](https://balsamiq.com/wireframes/). I created the mobile 
wireframe first so I get a rough idea what I want it to look like on a small media then moved onto tablet then desktop.

* Desktop Wireframe [View](https://github.com/twschan/CI_MS1_Tessa_Chan/blob/master/docs/wireframe/desktop-wireframe.pdf)
* Tablet Wireframe [View](https://github.com/twschan/CI_MS1_Tessa_Chan/blob/master/docs/wireframe/tablet-wireframe.pdf)
* Mobile Wireframe [View](https://github.com/twschan/CI_MS1_Tessa_Chan/blob/master/docs/wireframe/mobile-wireframe.pdf)

#### [Back to top](<#contents>)
---

# Features

## Existing Features

### Navigation

1. I have used Bootstrap to create a responsive navbar and implemented as well the hamburger icon for mobile devices to be more user-friendly. 
![Hambuger Icon](https://github.com/twschan/CI_MS1_Tessa_Chan/blob/master/docs/features/feature-1-hamburger.png)
2. I decided to keep the navbar fixed on the top of the page, so user can easily navigate to other pages. ![Fixed Navbar](https://github.com/twschan/CI_MS1_Tessa_Chan/blob/master/docs/features/feature-1-navbar.png)

**User stories covered by this feature:**

User story 3: As a First Time Visitor, I want to be able to find the website is easily accessible and stand out from other designers.

### Carousel - slideshow of images

1. I have decided to implement a Carousel across the index page, in order to make user curious about the designers portfolio. As it shows a few images at a time of her works. ![Carousel](https://github.com/twschan/CI_MS1_Tessa_Chan/blob/master/docs/features/feature-2-carousel.png)

**User stories covered by this feature:**

User story 1: As a First Time Visitor, I want to easily understand the main purpose of the site and learn more about the designer.

### Introduction - Hello

1. Just a short Introduction about the designer herself. ![Introduction](https://github.com/twschan/CI_MS1_Tessa_Chan/blob/master/docs/features/feature-3-hello.png)
2. I have chosen to use icons from font awesome to showcase her skills of what she can do as a designer. ![Skills icon](https://github.com/twschan/CI_MS1_Tessa_Chan/blob/master/docs/features/feature-3-icons.png)

**User stories covered by this feature:**

User story 1: As a First Time Visitor, I want to easily understand the main purpose of the site and learn more about the designer.

User story 2: As a First Time Visitor, I want to easily find out information about the designer.

### Book Now & Modal

1. For the modal this will be used in the index page and the about page. This allow users to book a job with the designer by opening up a modal form. ![Modal](https://github.com/twschan/CI_MS1_Tessa_Chan/blob/master/docs/features/feature-4-modal.png) ![Book now button opens up modal](https://github.com/twschan/CI_MS1_Tessa_Chan/blob/master/docs/features/feature-4-aboutpage.png)
2. The book now button is also placed in the index page at the top. ![Top book now](https://github.com/twschan/CI_MS1_Tessa_Chan/blob/master/docs/features/feature-4-top.png)
3. And bottom so the user won't need to scroll back up to find the button. ![Bottom book now](https://github.com/twschan/CI_MS1_Tessa_Chan/blob/master/docs/features/feature-4-bottom.png)

**User stories covered by this feature:**

User story 2: As a First Time Visitor, I want to easily find out information about the designer.

User story 4: As a First Time Visitor, I want to locate their social media links to see their followings on social media to determine how trusted and known they are.

User story 6: As a First Time Visitor, I want to be able to reach out to the designer via the website.

User story 11: As a site owner, I want to connect to potential jobs and projects.

User story 12: As a site owner, I want users to be able to contact the site owner easily for hire opportunities, collabrations and networking.

### Portfolio page

1. Here I used a grid from Bootstrap and card components with text overlay. It was more challenging, I implemented 9 images of the designer's work. By making sure I have used the correct grid system and responsive on all media also the images are spread evenly across the page. ![Portfolio](https://github.com/twschan/CI_MS1_Tessa_Chan/blob/master/docs/features/feature-5-portfolio.png)
2. Then for the text overlay which provides information with a hover effect. ![Text Overlay](https://github.com/twschan/CI_MS1_Tessa_Chan/blob/master/docs/features/feature-5-overlay.png)

**User stories covered by this feature:**

User story 5: As a First Time Visitor, I want to find information about her projects and various images about her designs.

User story 10: As a site owner, I want users to see projects that showcase skills and growth.

### About page

1. A photo of the designer with a hover effect and a link titled 'Show more' which will take the user to her portfolio page. ![Show more](https://github.com/twschan/CI_MS1_Tessa_Chan/blob/master/docs/features/feature-6-aboutpage.png)
2. Also a brief description about her, with background information and her education. ![About](https://github.com/twschan/CI_MS1_Tessa_Chan/blob/master/docs/features/feature-6-aboutme.png)
3. Below the text there will also be a book now button with a modal pop up. ![Bottom book now](https://github.com/twschan/CI_MS1_Tessa_Chan/blob/master/docs/features/feature-4-aboutpage.png)

**User stories covered by this feature:**

User story 1: As a First Time Visitor, I want to easily understand the main purpose of the site and learn more about the designer.

User story 2: As a First Time Visitor, I want to easily find out information about the designer.

User story 4: As a First Time Visitor, I want to locate their social media links to see their followings on social media to determine how trusted and known they are.

User story 6: As a First Time Visitor, I want to be able to reach out to the designer via the website.

### Contact page

1. I have provided contacts and location details on the left. ![Contact details](https://github.com/twschan/CI_MS1_Tessa_Chan/blob/master/docs/features/feature-7-contactdetails.png)
2. On the right is a contact form which users can fill in if they would like to get in contact with the site owner.![Contact form](https://github.com/twschan/CI_MS1_Tessa_Chan/blob/master/docs/features/feature-7-contactform.png)
3. I have also included a 'download CV' link for the user to download the CV on a new page. ![CV link](https://github.com/twschan/CI_MS1_Tessa_Chan/blob/master/docs/features/feature-7-cvlink.png)

**User stories covered by this feature:**

User story 1: As a First Time Visitor, I want to easily understand the main purpose of the site and learn more about the designer.

User story 2: As a First Time Visitor, I want to easily find out information about the designer.

User story 3: As a First Time Visitor, I want to be able to find the website is easily accessible and stand out from other designers.

User story 6: As a First Time Visitor, I want to be able to reach out to the designer via the website.

User story 8: As a Returning Visitor, I want to find the best way to get in contact with the designer with any questions I may have.

User story 9: As a Returning Visitor, I want to be able to get a downloadable CV of the site owner to easily share with others.

User story 11: As a site owner, I want to connect to potential jobs and projects.

User story 12: As a site owner, I want users to be able to contact the site owner easily for hire opportunities, collabrations and networking.

## Features to Implement in the future

* Open images into another link with more details about each projects
* To implement the email function to deliver the messages from the user to the site owner. As well as letting the user verify their email
* Add a pricelist page, so user can see how much is the cost
* Possibly testimonials/references of the user to enhance more credibility and trust
* Interactive map for location with a link to google maps

#### [Back to top](<#contents>)
---
# Technologies

## Languages Used

* [HTML5](https://en.wikipedia.org/wiki/HTML5)
* [CSS3](https://en.wikipedia.org/wiki/CSS)
* [JavaScript](https://en.wikipedia.org/wiki/JavaScript)

## Libraries Frameworks and Programs Used
* [Bootstrap](https://getbootstrap.com/docs/4.6/getting-started/introduction/)
  + To initial layout and styling before customising it
* [Font Awesome](https://fontawesome.com/)
  + Skills icons on homepage and social media icons in footer
* [Google Fonts](https://fonts.google.com/)
  + Used to import the Montserrat and Raleway fonts
* [Git](https://git-scm.com/)
  + Version control
* [Gitpod](https://www.gitpod.io/)
  + Used for editing my code
* [Balsamiq](https://balsamiq.com/)
  + Wireframes creation
* [Am I responsive?](http://ami.responsivedesign.is/)
  + This was used to generate the image of the website on different media
* [Tiny JPG](https://tinypng.com/)
  + To optimised the images I used on my site to minimise loading time 
* [Chrome devtools](https://developer.chrome.com/docs/devtools/)
  + This was used throughout development to troubleshoot, try out changes before changing codes, to test responsiveness and for testing performance of the final site with lighthouse.
* [Favicon](https://favicon.io/)
  + To make the site favicon
* [Colormind](http://colormind.io/)
  + Was used to display the colors shown in the color scheme section

#### [Back to top](<#contents>)

---
# Testing 

Further testing information and reports can be found [here](TESTING.md).

---
# Deployment

### Project creation
Navigate to the [template](https://github.com/Code-Institute-Org/gitpod-full-template) and click 'Use this template'. Put in Repository name (CI_MS1_Tessa_Chan) and check the include all branches checkbox. Then navigate to the new [repository](https://github.com/twschan/CI_MS1_Tessa_Chan).

The following commands were used for version control throughout the project: 
+ ```git status``` (check which files have been modified or added, and ready to be committed)
+ ```git add . ``` or ```git add <filename>``` (add all changed files, or specific files within the project directory to be committed)
+ ```git commit -m "[TYPE] Reason"``` (commit changes to the local repository)
+ ```git push``` (push all committed changes to Github Repository)

### Deployment to Github pages

1. Push project to Github. Navigate and log into the Github site.
2. Go to repositories and select the one associated to the project: [CI_MS1_Tessa_Chan](https://github.com/twschan/CI_MS1_Tessa_Chan).
3. On the main repository, click "Settings" and scroll to "Github pages".
4. Under "Source" select "Master Branch" and click "Save".
5. Click on the link to go to the live deployed page.

The live link for the site is here [https://github.com/twschan/CI_MS1_Tessa_Chan](https://github.com/twschan/CI_MS1_Tessa_Chan)

### Create a local clone

1. Open Github and navigate to repository [here](https://github.com/twschan/CI_MS1_Tessa_Chan).
2. Click the code drop down menu.
3. Options:
* Download the ZIP file, unpack locally and open with IDE.
* Copy git URL from HTTPS dialogue box.
4. Open your chosen IDE and open terminal in a directory.
5. Use ```git clone``` command with the copied git URL after.
6. Clone of the project is created locally on your machine.

### Fork Project 

1. Navigate to the Github Repository you want to [fork](https://github.com/twschan/CI_MS1_Tessa_Chan).
2. On the top right of the page under the header, click the fork button.
3. Creates a duplicate of the full project in your Github Repository.

#### [Back to top](<#contents>)
---
# Credits
## Code

* WSC Schools for [responsive navbar](https://www.w3schools.com/howto/howto_js_responsive_navbar_dropdown.asp) and [CSS forms](https://www.w3schools.com/css/css_form.asp) 
* Bootstrap responsive modal adapted from [Codepen](https://codepen.io/DivisonMusic/pen/ewgrPB)
* Stack Overflow for [modal pop up to appear infront](https://stackoverflow.com/questions/34755770/modal-appear-behind-fixed-navbar) and not behind fixed navigation bar. For [customising style](https://stackoverflow.com/questions/20854035/is-it-possible-to-customize-style-of-bootstrap-modal) on the modal and how it appears.
* Ways to optimise images for better web design and SEO on [Jimdo](https://www.jimdo.com/blog/optimize-website-images-for-better-design-seo/#:~:text=If%20you're%20wondering%20about,saved%20and%20uploaded%20as%20JPGs.) guide.
* Image hover overlay used in my portfolio page with the help of [
System 22 I.T. Solutions](https://www.youtube.com/watch?v=g5ewPg9kZxc&t=941s&ab_channel=System22I.T.SolutionsSystem22I.T.Solutions) youtube videos.
* Bootstrap 4 carousel to be more responsive on different media [
System 22 I.T. Solutions](https://www.youtube.com/c/System22Net/search?query=bootstrap%20carousel) youtube videos.
* Creating a [circular background](https://markheath.net/post/font-awesome-circle-background) for font awesome icons.
* A guide written on [CSS tricks](https://css-tricks.com/guides/) for flexbox, media queries and grid.

## Media

### All images, portfolio and text content are owned by the site owner.

#### [Back to top](<#contents>)
---

# Acknowledgements
* To my sister Tessa Chan for letting me use this opportunity to develope a website for her and feedback on this project.
* I would like to thank my mentor Mo Shami for all his feedback, advice and support throughout our project calls.
* Thanks to the Code Institute slack community of students for their helpful advice, guidance and support. 

#### [Back to top](<#contents>)