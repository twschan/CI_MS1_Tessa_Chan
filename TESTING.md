# Testing

## Contents
   * [Automated Testing](#automated-testing)
      + [HTML validation](#html-validation)
      + [CSS validation](#css-validation)
      + [Accessibility](#accessibility)
      + [Performance](#performance)
   * [Testing User Stories](#testing-user-stories)
   * [Manual testing](#manual-testing)
   * [Bugs](#bugs)

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

## Testing User Stories

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

Expected result: 
1. To find images of projects she has done
2. To find brief information about the designer

Actual result: Both works as expected

---
*2. As a First Time Visitor, I want to easily find out information about the designer.*

Feature:
1. Social media links in the footer of all pages.
2. Contact page will have all the details you need to contact site owner. 

Action:
1. Scroll to the end of any page.
[Screenshot show user story](https://github.com/twschan/CI_MS1_Tessa_Chan/blob/master/docs/testing/user-2.1.png)
2. Go to contact page from the nav bar.
[Screenshot show user story](https://github.com/twschan/CI_MS1_Tessa_Chan/blob/master/docs/testing/user-2.2.png)

Expected result: 
1. To find working social media links that direct users to and external social media link
2. To find contact details and forms on contact page

Actual result: Both works as expected

---
*3. As a First Time Visitor, I want to be able to find the website is easily accessible and stand out from other designers.*

Feature:
1. Aria labels, screen reader only text and alternative text have been used throughout the site. The use of hover indicates whats been highlighted before you click on it and underline link shows which page you are on.
2. Shows the site owner location where her studio is based with a map.

Action:
1. Hover over the nav bar, on social links and the header 'Tessa Chan' will take you back to home page.

    [Screenshot show user story](https://github.com/twschan/CI_MS1_Tessa_Chan/blob/master/docs/testing/user-3.1.png)

    [Screenshot show user story](https://github.com/twschan/CI_MS1_Tessa_Chan/blob/master/docs/testing/User-3-1.png)

2. Go to contact page, a google map showing the location is implemented on the page. [Screenshot show user story](https://github.com/twschan/CI_MS1_Tessa_Chan/blob/master/docs/testing/user-3.2.png)

Expected result: 
1. By clicking the header brand name will take the user back to the homepage
2. To find embedded google map with location pin of the site owner location

Actual result: Both works as expected

---
*4. As a First Time Visitor, I want to locate their social media links to see their followings on social media to determine how trusted and known they are.*

Feature:
1. Social media links are placed on the footer of all pages.

Action:
1. To locate them just scroll down, you'll see it's placed in the center of the page in the footer.
[Screenshot show user story](https://github.com/twschan/CI_MS1_Tessa_Chan/blob/master/docs/testing/user-4.1.png)

Expected result: 
1. To find working social media links that direct users to and external social media link

Actual result: Works as expected

---
*5. As a First Time Visitor, I want to find information about her projects and various images about her designs.*

Feature:
1. All the site owner projects will be on the portfolio page and information can be found by hovering over the image.
2. On the about page, a photo of the site owner hover over and a link titled 'Show more' which will take the user to her portfolio page.

Action:
1. Go to portfolio page from the nav bar and all images is displayed in the center of the page, there is 9 projects altogether.
[Screenshot show user story](https://github.com/twschan/CI_MS1_Tessa_Chan/blob/master/docs/testing/user-5.1.png)
2. Go to about from navigation bar, on the page hover over the photo 'show more' will appear then click on it.
[Screenshot show user story](https://github.com/twschan/CI_MS1_Tessa_Chan/blob/master/docs/testing/user-5.2.png)

Expected result: 
1. To find site owner's portfolio with various images of her work and clear explanation about the work
2. To find the 'show more' link in the about page, takes the user to the portfolio page

Actual result: Both works as expected

---
*6. As a First Time Visitor, I want to be able to reach out to the designer via the website.*

Feature:
1. 'Book now' modal form are placed on serveral pages. A consistent call-to-action throughout the site and drive users to contact site owner. There's also a contact form on contact page for quicker access to contact site owner.

Action:
1. To locate the 'Book now' buttons which can be found the top and button of the home page, and the bottom of the about page. For mobile users it will be placed on the bottom. [Screenshot show user story](https://github.com/twschan/CI_MS1_Tessa_Chan/blob/master/docs/testing/User-6-1.png)

   On contact page scroll down. [Screenshot show user story](https://github.com/twschan/CI_MS1_Tessa_Chan/blob/master/docs/testing/user-2.2.png)

   A modal form will also pop up when 'Book now' buttons been clicked. [Screenshot show user story](https://github.com/twschan/CI_MS1_Tessa_Chan/blob/master/docs/testing/user-6.1.png)

Expected result: 
1. To find contact forms to contact the designer

Actual result: Works as expected

---
### Returning user

*7. As a Returning Visitor, I want to find information and updates about her latest projects.*

Feature: 
1. Future updates can be found on portfolio page when site owner decides to add more information and recent projects. And users can follow updates from site owner social media links.

Action:
1. Locate the portfolio page from the navigation bar, any updates on projects will be posted on this page. [Screenshot show user story](https://github.com/twschan/CI_MS1_Tessa_Chan/blob/master/docs/features/feature-5-portfolio.png)

   And social media links can be accessed at the bottom footer on every page. [Screenshot show user story](https://github.com/twschan/CI_MS1_Tessa_Chan/blob/master/docs/testing/user-5.1.png)

Expected result: 
1. To find information and updates about her latest projects

Actual result: Works as expected

---
*8. As a Returning Visitor, I want to find the best way to get in contact with the designer with any questions I may have.*

Feature:
1. Contact form and contact details for any queries the user may have. 

Action:
1. Go to contact page scroll down and all details are near the end of the page. 

    [Screenshot show user story](https://github.com/twschan/CI_MS1_Tessa_Chan/blob/master/docs/features/feature-7-contactform.png) 
    
    [Screenshot show user story](https://github.com/twschan/CI_MS1_Tessa_Chan/blob/master/docs/features/feature-7-cvlink.png)

Expected result: 
1. To find a contact form that can be submitted

Actual result: Works as expected

---
*9. As a Returning Visitor, I want to be able to get a downloadable CV of the site owner to easily share with others.*

Feature:
1. A download CV link in PDF format, which opens up in a new window can easily be saved or printed. 

Action:
1. Download CV link can be found underneath the site owner email address and mobile on the contact page. [Screenshot show user story](https://github.com/twschan/CI_MS1_Tessa_Chan/blob/master/docs/testing/user-9.1.jpg)

Expected result: 
1. To see a PDF version of the web CV to print off or download

Actual result: Works as expected

---
### Site owner goal

*10. As a site owner, I want users to see projects that showcase skills and growth.*

Feature:
1. Portfolio page for future more projects can be added using the same format.
2. Skills page can be added to the website in the future, using for the same idea from the home page.

Action:
1. Go to portfolio page from the navigation bar all old and new projects will be on this page. [Screenshot show user story](https://github.com/twschan/CI_MS1_Tessa_Chan/blob/master/docs/features/feature-5-portfolio.png)

2. On the home page scroll down you will see a some icons, which represents skills that the site owner has of what she can do or learnt from previous experience. [Screenshot show user story](https://github.com/twschan/CI_MS1_Tessa_Chan/blob/master/docs/features/feature-3-icons.png)

Expected result: 
1. To see portfolio page can be updated when needed to add more content
2. To find skills of what the designer can do for potential future jobs

Actual result: Both works as expected

---
*11. As a site owner, I want to connect to potential jobs and projects.*

Feature:
1. CTA 'Book now' buttons and contact form are placed throughout the pages for easy access for the user to contact the site owner. There's also social media links where the site owner can be contacted.  

Action:
1. To locate the 'Book now' buttons which can be found the top and button of the home page, and the bottom of the about page. For mobile users it will be placed on the bottom. [Screenshot show user story](https://github.com/twschan/CI_MS1_Tessa_Chan/blob/master/docs/testing/User-6-1.png)

Expected result: 
1. To find 'book now' buttons easily across all pages

Actual result: Works as expected

#### [Back to top](<#contents>)
---

## Manual testing

### Devices tested:

* iPhone 7 plus
* iPhone SE
* Samsung Galaxy Note 10+
* HP Pavilion 15 Notebook PC
* iPad pro
* Huawei P40 Pro
* The website was viewed with browsers: Google chrome, Safari, Microsoft edge and Firefox.

### Tests performed:

* All page links in the navigation bar are able to direct users to the correct page and no broken links are present on the navigation bar or it's collapsed version.
* Page, anchor and outbound links are able to direct users to the correct place with no broken links on desktop or mobile version.
* The 'book now' modal opens up correctly and is able to close by clicking away or clicking the close icon.
* The form on the 'book now' modal will not submit until all fields are filled out. An alert will be present when a user attempts this.
* The 'download cv link' opens up in a new window and can be downloaded
* The row of images in portfolio page collapses into single view column on mobile and two column view on tablet.
* The google map has a location pin to let users know where the site owner is based.
* The form on the contact page will not submit until all fields are filled in. An alert will be present when a user attempts this.
* The 'show more' link on the about page direct users to the portfolio page.
* All buttons display a different color or border effect when hovered in desktop view or clicked in mobile view.
* Unnescessary content does not display on mobile view.
* The 'Tessa Chan' brand header takes users back to the home page on all pages. 
* Social links in footer all open in a new page and work from all pages.

#### [Back to top](<#contents>)
---

## Bugs

### Found and Fixed

* Bug: On the about page the photo of the site owner being very distorted and squashed on mobile view.
* Fix: I was able to resolve the issue by removing the display flex property in CSS.
* Bug: On mobile view smaller than 320px devices, the footer on portfolio page does not stretch 100% width of the page.
* Fix: Increased the width % and added media query max-width: 320px for smaller devices.
* Bug: The social media icons didn't show up horizontally next to each other on mobile.
* Fix: Reduced the font-size and padding which resolved the issue immediately.
* Bug: When the screen gets smaller, the font-size of the navigation bar is too small and the collapse button goes off the screen.
* Fix: Removed display:block and updated the width to 100%. Changed font-size as well for better readability.
* Bug: On portfolio page the images was not responsive on medium and large devices, which they would overlap each other and margin gap in between them is too cramped. 
* Fix: As I wanted the larger devices to display three images in a row, I fixed the issue by re-sizing the image width and use media query of @media (min-width: 992px) and (max-width: 1199.98px).
* Bug: Page loading speed was slow. As the images on home page were too big and was not optimized for better web design and SEO.
* Fix: Optimized the jpeg images by making the file sizes smaller, then re-sized it on Pixlr.
* Bug: Carousel on home page was expanding the full width of the screen, this was causing the images to be pixelated and stretched.
* Fix: This was resolved by adding a width: 80% and margin: auto so it's aligned in the center of the page.
* Bug: Had errors on form 'labels for' attribute, I realised the mistake due to HTML validation and on web accessibility.
* Fix: The 'label for' attribute were typed in with the wrong id name, to fix the issue I went through all the modal forms and the contact form and changed it accordingly.
* Bug: Hyperlink text were not passing web accessibility standards due to colour contrast failures.
* Fix: Set color property of all 'a' tags to color light grey. 