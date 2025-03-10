# Pat Tech Consultants website
![Responsive mockup on different devices](./assets/images/hero-readme.png)  

PTC website is a fully responsive website for a fictional company (PTC, Pat Tech Consultants) with the purpose to attract both new consultants who wants to work with PTC and businesses who are in need of tech services/consultants. 

[Link to deployed version of website](https://patriklundstrom91.github.io/pat-tech-consultants/index.html)

## Contents  

* [User Experience](#user-experience-ux)  
  * [Business Goals](#business-goals)  
  * [User Goals / User Stories](#user-goals--user-stories)  
    * [Tech Professionals Goals](#tech-professionals-goals)  
    * [Client Goals](#client-goals)  

* [Design](#design)  
  * [Wireframes](#wireframes)  
  * [Colour Scheme](#colour-scheme)  
  * [Fonts](#fonts)  
  * [Logo](#logo)  
  * [Favicon](#favicon) 
 
* [Features](#features)  
  * [Navbar](#navbar)  
  * [Images](#images)  
  * [Information Cards](#information-cards)  
  * [Info Box](#info-box)  
  * [Testimonials](#testimonials)  
  * [Forms](#forms)  
  * [Contact](#contact)  
  * [Footer](#footer)  

* [Used Technologies](#used-technologies)  
  * [Languages](#languages)  
  * [Libraries and Frameworks](#libraries-and-frameworks)  
  * [Platforms and Software](#platforms-and-software)  
  * [Other Resources](#other-resources)  

* [Testing](#testing)  
  * [Manual Testing](#manual-testing)  
  * [Bugs](#bugs)  
    * [Fixed Bugs](#fixed-bugs)  
    * [Unsolved Bugs](#unsolved-bugs)  
  * [Code Validation](#code-validation)  
  * [Lighthouse](#lighthouse)  
  * [Waveapp Accessibility Test](#waveapp-accessibility-test)  

* [Deployment](#deployment)  
  * [Version Control](#version-control)  
  * [GitHub Pages](#github-pages)  
  * [How to Fork](#how-to-fork)  
  * [How to Clone](#how-to-clone)  

* [Credits](#credits)  
  * [Code Used](#code-used)  
  * [Images/ Media](#images-media)  

## User Experience (UX)

### Business Goals

The goal for the business is to create brand awareness and attract both new tech consultants to the company as well as attracting new clients. To have a website that provides clear information and will generate more revenue by increasing the amount of inbound leads to the company (PTC). 

So in short, as a business we want to:
* Attract new tech consultant /tech professionals
* Attract new business by marketing our services
* Attract inqueries for our services 
* create brand awareness, build trust and show that we are a legitimate business

### User Goals / User Stories

The target audience is tech professionals looking for new jobs or projects and people working in businesses in need of tech services (clients) either just for a short project or long term. The user stories ar divided in these two categories. 

#### Tech Professionals Goals

* As a tech professional I want to find information about the company and benefits of working there (must have)
* As a tech professional I want to be able to send in my application to join PTC (must-have)
* As a tech professional I want to be able to easily navigate the site on all types of devices (must-have)
* As a tech professional I want to be able to see a list of current consultant projects available (nice to have)


#### Client Goals

* As a potential client I want to easily navigate the site on all devices (must-have)
* As a potential client I want to easily find information about the services provided (must-have)
* As a potential client I want to be able to contact PTC with questions (must-have)
* As a potential client I want to be able to send a requests/inqueries for tech services (must-have)
* As a potential client I want to see testimonials from previus clients in order to make sure PTC is providing a good service (nice to have)

Of the goals above all goals are checked off with exception for list of projects, this due to limited time, but professionals can see testimonials to get an idea of what kind of clients PTC work with. 

## Design

### Wireframes

Below you can see wireframes for the website, made in Balsamiq.

* Index page  
![Wireframes for index page](assets/wireframes/wireframe-index.png)  

* Services page  
![Wireframe for services page](assets/wireframes/wireframe-services.png)  

* Join page  
![Wireframe for join page](assets/wireframes/wireframe-join.png)  

* Contact page  
![Wireframe for contact page](assets/wireframes/wireframe-contact.png)  

* Success page  
![Wireframe for success page](assets/wireframes/wireframe-success.png)  

### Colour Scheme  

The colour scheme was picked with the use of the website Coolors, I find the blue-grey colours to be fitting a tech site and they give a professional feel along with good contrast to text (white text for Royal blue and Bistre. Black text for the others)  

* [Link to Coolors website and palette](https://coolors.co/0a369d-92b4f4-cfdee7)  
![Colour scheme](assets/images/colour-scheme.png)  

### Fonts  

Google font is imported and used. Barlow is the selected main font. [Link to Google fonts](https://fonts.google.com/specimen/Barlow)

### Logo 

Logo was created with a free online tool named [freelogodesign.org](https://app.freelogodesign.org/design)  

* Same logo on all devices  
![Logo](assets/images/logo-blue.png)  

### Favicon 

Favicon, generated from logo by [favicon.io/favicon-converter/](favicon.io/favicon-converter/)  

* Favicon for browser tab  
![Favicon](assets/images/favicon-32x32.png)  

## Features

### Navbar  

All pages have the same navbar, designed to be responsive to different devices. Bootstrap navbar is used and customized so on mobile you have a menu button and on desktop you have the menu options visible as shown below:

* Mobile  
![Pic of mobile navbar](assets/images/navbar-mobile.png)  

* Mobile with open menu  
![Pic of mobile navbar with open menu](assets/images/navbar-mobile-menu.png)  

* Bigger screen, laptop or desktop. the current page is marked and same colour change when hovering other links  
![Pic of desktop navbar](assets/images/navbar-desktop.png)  

### Images   

On all pages the first thing after the navbar is a hero image with a cover-box containing a title. This hero image is unique on all pages  

* Responsive in size, centered and with no repeat
![Hero image of index page](assets/images/hero-pic-index.png)  

On index,services,join page there is also a second image in middle of the content purely for design purposes  

* Responsive in size, max 80% of screen and has a max-width  
![Example of second image](assets/images/second-pic-example.png)  

### Information Cards  

On pages index, services, join there is a card section after hero image with vital information to the target audiance. Bootstrap cards are used and redesigned. The cards stacks in a responsive way so on mobile the show on below each other and on desktop in a row instead as shown below. There is also a "pop effect" so when hovering a card it pops up a bit and gets a bigger shadow (credit to my mentor Spencer Barriball)  

* Mobile  
![Pic of cards section on mobile](assets/images/cards-index-mobile.png)  

* Desktop  
![Pic of cards section on desktop](assets/images/cards-index.png)  

* Desktop when hover over with mouse  
![Pic of cards section when hover](assets/images/cards-index-hover.png)  

### Info Box  

On index page there is a grey info box spanning the page with some facts about PTC  

* Responsive in it's design but with a max-width, cover full width up to screen size of max-width  
![Pic of info-box on index page](assets/images/info-box-index.png)  

### Testimonials  

On index page there is a testimonials section in the end so people can read about previus clients and their satisfaction. After the testimonials there is a Contact Us button that sends you to the contact page  

* Mobile  
![Pic of testimonials on mobile](assets/images/testimonials-mobile.png)  

* Desktop  
![Pic of testimonials on desktop](assets/images/testimonials-desktop.png)  

### Forms  

On services, join, contact page there are forms with validations that let you send in a request, application or message. Bootstrap forms are used and customized. Different fields are required depending on form. After sending the form you are sent to a confirmation/success page so you get confirmation on successfully sending the form. From there you can navigate back to home or anywhere else on the website. The form is responsive and stack fields below each other on mobile or some next to each other on desktop.

* Mobile  
![Pic of form on mobile](assets/images/form-mobile.png)  

* Desktop  
![Pic of form on Desktop](assets/images/form-desktop.png)  

* Application form with required CV file  
![Pic of application form](assets/images/form-application.png)  

* Send message form  
![Pic of a send message form](assets/images/form-message.png)  

### Contact  

On contact page there is a section with contact details followed by the send message form. Contact details are linked so phone has a call link and email a mailto link. Address is linked to google maps. All links have Aria-labels for accessibility.  

* All devices  
![Pic of contact details](assets/images/contact-details.png)  

### Footer  

All pages have a responsive footer with logo, phone and email followed by links to socials. Footer have 3 layouts depending on screen size and hover effect on social icons. Also have call and email links.  

* Mobile  
![Pic of footer on mobile](assets/images/footer-mobile.png)  

* Tablet  
![Pic of footer on tablet](assets/images/footer-tablet.png)  

* Desktop  
![Pic of footer on desktop](assets/images/footer-desktop.png)  

## Used Technologies

### Languages  

* HTML
* CSS

### Libraries and Frameworks

* [Bootstrap v5.3](https://getbootstrap.com/docs/5.3/getting-started/introduction/)
* [Google fonts](https://fonts.google.com/)
* [FontAwesome kit](https://fontawesome.com/search)

### Platforms and Software

* VS Code
* [Github](https://github.com/patriklundstrom91/pat-tech-consultants)
* Balsamiq

### Other Resources

* [Freelogodesign](https://app.freelogodesign.org/design)
* [Coolers](https://coolors.co/0a369d-92b4f4-cfdee7)
* [Favicon.io](https://favicon.io/)
* Images from [Unsplash](https://unsplash.com) and [Pexels](https://www.pexels.com)

## Testing

### Manual Testing

* I have manually tested the website on both Crome, Edge and Firefox on PC, only issue found is selection menu in forms on firefox, standard font shows in that specific selection dropdown instead of my selected font, in other browsers selected font shows as it should

* Tested with different sizes and simulations in chrome with tablet sizes as well as smaller and bigger sizes with good responsiveness and functionality

* Tested all buttons/links in Navbar, on the page and in the footer. Also tested hover functions and form validations on above mentioned browsers without any issues

* A friend have tested it on Safari on MacBook with no issues on design or link aspects, sent a form and got to success page and can see all icons and animations etc

* I have tested on Safari on Iphone 11 with no issues, all links/functions and validations work

* Family member have tested on Samsung Galaxy Flip 5 (android) with no issues.  

### Bugs

#### Fixed Bugs

* Button at join us box split in two rows when exanding screen.   
![Pic oc split row bug](assets/images/bug-join-button.png)  
Solution: Had to adjust col class differently for the button so it wouln't happen

* Background is not covering the corner after restyling card to straight border with border-radius: 0;   
![Pic of card corner](assets/images/bug-card-corner.png)  
Solution: Add !important on border-radius in card-header class  
![Pic of solution in card-header](assets/images/bug-card-corner-solution.png)

* Form not centered after adding max-width 700px to avoid stretching form to wide  
![Pic of form left aligned](assets/images/bug-form-not-center.png)  
Solution: add class mx-auto to add auto-margin to center it. Similar to how the buttons in other parts of the page are centered with mx-auto. 

#### Unsolved Bugs

* Form selector menu on Firefox, font doesn't show as it should, standard font shows instead, no issue on Chrome or Edge  
![Pic of wrong font in form when using Firefox](assets/images/bug-form-selector-font-firefox.png)  
Solution: unknown, form still functional so minor and purely cosmetic bug

### Code Validation

All HTML pages (index, services, join, contact, success) have been validated with [Validator.w3.org](https://validator.w3.org/nu/?doc=https%3A%2F%2Fpatriklundstrom91.github.io%2Fpat-tech-consultants%2Findex.html) without any errors or warnings

![Pic of HTML validation on index page](assets/images/test-html-validator.png)  
![Pic of HTML validation on services page](assets/images/html-validation-services.png)  
![Pic of HTML validation on join page](assets/images/html-validation-join.png)  
![Pic of HTML validation on contact page](assets/images/html-validation-contact.png)  
![Pic of HTML validation on success page](assets/images/html-validation-success.png)  

CSS have been validated with [jigsaw.w3.org](https://jigsaw.w3.org/css-validator/validator) without any errors  

![Pic of CSS validation](assets/images/test-jigsaw-css-validator.png)

### Lighthouse

I have tested the site against Lighthouse on chrome to test performance, accessibility, Best practice and SEO with good score (minor drop in accessibility due to using h4 after h2) there is also a understanding that score may vary depending on external factors  

![Pic of Lighthouse test](assets/images/test-lighthouse-desktop.png)  

### Waveapp Accessibility Test  

I have tested the site against [Waveapp](https://wave.webaim.org/) accessibility test with no errors  

![Pic of Waveapp test](assets/images/test-wave-accessibility.png)  

## Deployment  

### Version Control  

The website was created in VS Code and pushed to GitHub repository and there deployed with GitHub pages. Every push to GitHub repository can be seen so easy to fall back on earlier version if any problems with new code. Following steps were taken.

1. You push from VS code to GitHub repository by creating a repository in GitHub and then enter the given code, in VS code terminal to make a first push and also create a readme.md file.  

2. You can now push regularly to GitHub with the VS code terminal using the comands:  
git add . (press enter)  
git commit -m "commit message about changes"  (press enter)  
git push  (press enter)  

### GitHub Pages  

The website was deployed with GitHub Pages, to do so follow the following steps.  

1. Go to GitHub repository and select settings  

2. In settings select Pages  

3. In Pages you will find a section Branch with a selector with value none, change to main and save  

4. Done! Now when you push to GitHub it will get deployed online. A link to your deployed site is now available in the deployments section at GitHub  

[Link to deployed version of the PTC website](https://patriklundstrom91.github.io/pat-tech-consultants/index.html)  

### How to Fork  

1. Go to GitHub and sign in or sign up  
2. Go to the repository of this site [link here](https://github.com/patriklundstrom91/pat-tech-consultants)  
3. Press Fork button on upper right part of the page  

### How to Clone  

1. Go to GitHub and sign in or sign up  
2. Go to the repository of this site [link here](https://github.com/patriklundstrom91/pat-tech-consultants)  
3. Press the green Code button, from there you can clone or download the code as zip

## Credits  

A special thanks to my mentor Spencer Barriball who have guided me and also deserve the credit for the pop effect on the cards.  

Also thanks to Kristyna our Cohort Facilitator who have weekly calls with us and checks in making sure things are on track.  

Many of the concepts on this site is inspired by things we did as learning projects so credit to Code institute for that.  

Thanks to friends who have helped me test the website and supported me.  

Lastly I want to give credit to Bootstrap, it's a big part of the foundation of this site and it's responsiveness.  

### Code Used  

Code from [Bootstrap v5.3](https://getbootstrap.com/docs/5.3/getting-started/introduction/) have been used on the website.  

Code from my previus learning projects at Code institute have been used or used as inspiration.

### Images/ Media  

Hero image of a grey computer with code from unsplash.com
[Link to source of grey computer with code](https://unsplash.com/photos/turned-on-gray-laptop-computer-MSN8TFhJ0is?utm_content=creditShareLink&utm_medium=referral&utm_source=unsplash)

Female programmer on desktop from unsplash.com
[Link to source, female programmer on desktop](https://unsplash.com/photos/woman-wearing-black-t-shirt-holding-white-computer-keyboard-YK0HPwWDJ1I?utm_content=creditShareLink&utm_medium=referral&utm_source=unsplash)

Computer with plant aloe vera from unsplash.com
[Link to source, computer with aloe vera](https://unsplash.com/photos/black-laptop-computer-turned-on-on-table-vpOeXr5wmR4?utm_content=creditShareLink&utm_medium=referral&utm_source=unsplash)

Client meeting from unsplash.com
[Link to source, client meeting](https://unsplash.com/photos/black-smartphone-near-person-5QgIuuBxKwM?utm_content=creditShareLink&utm_medium=referral&utm_source=unsplash)

Coffee break from pexels.com
[Link to Image by Tima Miroshnichenko, coffee break](https://www.pexels.com/sv-se/foto/mat-kvinna-kontor-man-6913243/)

Hero image join us page computer on desk with speakers from unsplash.com
[Link to source Hero image computer on desk with speakers](https://unsplash.com/photos/a-macbook-with-lines-of-code-on-its-screen-on-a-busy-desk-m_HRfLhgABo?utm_content=creditShareLink&utm_medium=referral&utm_source=unsplash)

Hero image contact page unused laptop on desk from unsplash.com
[Link to source Hero image contact page](https://unsplash.com/photos/silver-macbook-pro-on-white-table-vjMgqUkS8q8?utm_content=creditShareLink&utm_medium=referral&utm_source=unsplash)

Hero image success page, laptop on wooden desk from unsplash.com
[Link to source hero image success page](https://unsplash.com/photos/a-laptop-computer-sitting-on-top-of-a-wooden-desk-8q6e5hu3Ilc?utm_content=creditShareLink&utm_medium=referral&utm_source=unsplash)  

Logo designed with [Freelogodesign](https://app.freelogodesign.org/design)  

Favicon by [Favicon.io](https://favicon.io/)

Icons by [FontAwesome kit](https://fontawesome.com/search)