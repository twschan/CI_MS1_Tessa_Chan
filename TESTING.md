# Testing

## Contents
   * [Automated Testing](#automated-testing)
      + [HTML validation](#html-validation)
      + [CSS validation](#css-validation)
      + [Accessibility](#accessibility)
      + [Performance](#performance)
   * [Testing User Stories](#testing-user-stories)
   * [Manual testing]()
   * [Bugs found and resolved during development]()

## Automated Testing

### HTML Validation

The [WSC Markup Validation Service](https://validator.w3.org/) was used to validate the HTML of the website to ensure there were no syntax errors. All pages pass with 0 errors.

Click on the page name to see the results: [Home](https://github.com/twschan/CI_MS1_Tessa_Chan/blob/master/docs/validation/html-validation/html-validation-index.png) [Portfolio](https://github.com/twschan/CI_MS1_Tessa_Chan/blob/master/docs/validation/html-validation/html-validation-portfolio.png) [About](https://github.com/twschan/CI_MS1_Tessa_Chan/blob/master/docs/validation/html-validation/html-validation-about.png) [Contact](https://github.com/twschan/CI_MS1_Tessa_Chan/blob/master/docs/validation/html-validation/html-validation-contact.png)

### CSS Validation

The [WSC CSS Validation Service](https://jigsaw.w3.org/css-validator/) was used to validate the CSS of the website.

The CSS passed with [final testing](https://github.com/twschan/CI_MS1_Tessa_Chan/blob/master/docs/validation/css-validation/css-validation.png).

### Accessibility

The [WAVE WebAIM web accessibility evaluation tool](https://wave.webaim.org/) was used to ensure the website met high accessibility standards. All pages pass with 0 errors.

Click on the page name to see the result: [Home](https://github.com/twschan/CI_MS1_Tessa_Chan/blob/master/docs/validation/accessibility/WAVE-index-page.png) [Portfolio](https://github.com/twschan/CI_MS1_Tessa_Chan/blob/master/docs/validation/accessibility/WAVE-portfolio-page.png) [About](https://github.com/twschan/CI_MS1_Tessa_Chan/blob/master/docs/validation/accessibility/WAVE-about-page.png) [Contact](https://github.com/twschan/CI_MS1_Tessa_Chan/blob/master/docs/validation/accessibility/WAVE-contact-page.png)

### Performance

[Google Lighthouse](https://developers.google.com/web/tools/lighthouse/) was used to measure the performance and speed of the website. Each page passed with at least 99% score on performance, 98% on accessibility, 93% on best practices and 100% on SEO.

Click on the page name to see the result: [Home](https://github.com/twschan/CI_MS1_Tessa_Chan/blob/master/docs/validation/lighthouse-performance/index.png) [Portfolio](https://github.com/twschan/CI_MS1_Tessa_Chan/blob/master/docs/validation/lighthouse-performance/portfolio.png) [About](https://github.com/twschan/CI_MS1_Tessa_Chan/blob/master/docs/validation/lighthouse-performance/about.png) [Contact](https://github.com/twschan/CI_MS1_Tessa_Chan/blob/master/docs/validation/lighthouse-performance/contact.png)

#### [Back to top](<#contents>)
---

# Testing user Stories

### First time user

*1. As a First Time Visitor, I want to easily understand the main purpose of the site and learn more about the designer.*

Feature:
1. Find images of the site owner projects being displayed across the home page.
2. Below is a short introduction about herself, also showcasing her skills.

Action:
1. Upon loading the website first you land on is the home page a slideshow of her projects.
[Screenshot show user story](https://github.com/twschan/CI_MS1_Tessa_Chan/blob/master/docs/testing/user-1.1.png) 
2. Scroll down you find the information.  
[Screenshot show user story](https://github.com/twschan/CI_MS1_Tessa_Chan/blob/master/docs/testing/user-1.2.png)

*2. As a First Time Visitor, I want to easily find out information about the designer.*

Feature:
1. Social media links in the footer of all pages.
2. Contact page will have all the details you need to contact site owner. 

Action:
1. Scroll to the end of any page.
[Screenshot show user story](https://github.com/twschan/CI_MS1_Tessa_Chan/blob/master/docs/testing/user-2.1.png)
2. Go to contact page from the nav bar.
[Screenshot show user story](https://github.com/twschan/CI_MS1_Tessa_Chan/blob/master/docs/testing/user-2.2.png)

*3. As a First Time Visitor, I want to be able to find the website is easily accessible and stand out from other designers.*

Feature:
1. Aria labels, screen reader only text and alternative text have been used throughout the site. The use of hover indicates whats been hightlighted before you click on it and underline link shows which page you are on.
2. Shows the site owner location where her studio is based with a map.

Action:
1. Hover over the nav bar, on social links and the header 'Tessa Chan' will take you back to home page.

    [Screenshot show user story](https://github.com/twschan/CI_MS1_Tessa_Chan/blob/master/docs/testing/user-3.1.png)

    [Screenshot show user story](https://github.com/twschan/CI_MS1_Tessa_Chan/blob/master/docs/testing/User-3-1.png)

2. Go to contact page, a google map showing the location is implemented on the page. [Screenshot show user story](https://github.com/twschan/CI_MS1_Tessa_Chan/blob/master/docs/testing/user-3.2.png)


*4. As a First Time Visitor, I want to locate their social media links to see their followings on social media to determine how trusted and known they are.*

Feature:
1. Social media links are placed on the footer of all pages.

Action:
1. To locate them just scroll down, you'll see it's placed in the center of the page.
[Screenshot show user story](https://github.com/twschan/CI_MS1_Tessa_Chan/blob/master/docs/testing/user-4.1.png)

*5. As a First Time Visitor, I want to find information about her projects and various images about her designs.*

Feature:
1. All the site owner projects will be on the portfolio page and information can be found by hovering over the image.
2. On the about page, a photo of the site owner hover over and a link titled 'Show more' which will take the user to her portfolio page.

Action:
1. Go to portfolio page from the nav bar and all images is displayed in the center of the page, there is 9 projects altogether.
[Screenshot show user story](https://github.com/twschan/CI_MS1_Tessa_Chan/blob/master/docs/testing/user-5.1.png)
2. Go to about from navigation bar, on the page hover over the photo 'show more' will appear then click on it.
[Screenshot show user story](https://github.com/twschan/CI_MS1_Tessa_Chan/blob/master/docs/testing/user-5.2.png)

*6. As a First Time Visitor, I want to be able to reach out to the designer via the website.*

Feature:
1. 'Book now' modal form are placed on serveral pages. A consistent call-to-action throughout the site and drive users to contact site owner. There's also a contact form on contact page for quicker access to contact site owner.

Action:
1. To locate the 'Book now' buttons which can be found the top and button of the home page, and the bottom of the about page. For mobile users it will be placed on the bottom. [Screenshot show user story](https://github.com/twschan/CI_MS1_Tessa_Chan/blob/master/docs/testing/User-6-1.png)

   On contact page scroll down. [Screenshot show user story](https://github.com/twschan/CI_MS1_Tessa_Chan/blob/master/docs/testing/user-2.2.png)

   A modal form will also pop up when 'Book now' buttons been clicked. [Screenshot show user story](https://github.com/twschan/CI_MS1_Tessa_Chan/blob/master/docs/testing/user-6.1.png)


### Returning user

*7. As a Returning Visitor, I want to find information and updates about her latest projects.*

Feature: 
1. Future updates can be found on portfolio page when site owner decides to add more information and recent projects. And users can follow updates from site owner social media links.

Action:
1. Locate the portfolio page from the navigation bar, any updates on projects will be posted on this page. [Screenshot show user story](https://github.com/twschan/CI_MS1_Tessa_Chan/blob/master/docs/features/feature-5-portfolio.png)

   And social media links can be accessed at the bottom footer on every page. [Screenshot show user story](https://github.com/twschan/CI_MS1_Tessa_Chan/blob/master/docs/testing/user-5.1.png)

*8. As a Returning Visitor, I want to find the best way to get in contact with the designer with any questions I may have.*

Feature:
1. Contact form and contact details for any queries the user may have. 

Action:
1. Go to contact page scroll down and all details are near the end of the page. 

    [Screenshot show user story](https://github.com/twschan/CI_MS1_Tessa_Chan/blob/master/docs/features/feature-7-contactform.png) 
    
    [Screenshot show user story](https://github.com/twschan/CI_MS1_Tessa_Chan/blob/master/docs/features/feature-7-cvlink.png)

*9. As a Returning Visitor, I want to be able to get a downloadable CV of the site owner to easily share with others.*

Feature:
1. A download CV link in PDF format, which opens up in a new window can easily be saved or printed. 

Action:
1. Download CV link can be found underneath the site owner email address abd mobile on the contact page. [Screenshot show user story](https://github.com/twschan/CI_MS1_Tessa_Chan/blob/master/docs/testing/user-9.1.jpg)

### Site owner goal

*10. As a site owner, I want users to see projects that showcase skills and growth.*

Feature:
1. Portfolio page for future more projects can be added using the same format.
2. Skills page can be added to the website in the future, using for the same idea from the home page.

Action:
1. Go to portfolio page from the navigation bar all old and new projects will be on this page. [Screenshot show user story](https://github.com/twschan/CI_MS1_Tessa_Chan/blob/master/docs/features/feature-5-portfolio.png)

2. On the home page scroll down you will see a some icons, which represents skills that the site owner has of what she can do or learnt from previous experience. [Screenshot show user story](https://github.com/twschan/CI_MS1_Tessa_Chan/blob/master/docs/features/feature-3-icons.png)

*11. As a site owner, I want to connect to potential jobs and projects.*

Feature:
1. CTA 'Book now' buttons and contact form are placed throughout the pages for easy access for the user to contact the site owner. There's also social media links where the site owner can be contacted.  

Action:
1. To locate the 'Book now' buttons which can be found the top and button of the home page, and the bottom of the about page. For mobile users it will be placed on the bottom. [Screenshot show user story](https://github.com/twschan/CI_MS1_Tessa_Chan/blob/master/docs/testing/User-6-1.png)