# Content Table
- [Introduction](#introduction)
- [UX](#ux)
  - [Site Purpose](#site-purpose)
  - [Site Goal](#site-goal)
  - [Audience](#audience)
  - [Communication](#communication)
  - [Current User Goals](#current-user-goals)
  - [New User Goals](#new-user-goals)
- [Design](#design)
- [Color Scheme](#color-scheme)
- [Typography](#typography)
- [Imagery](#imagery)
- [Features](#features)
  - [Navigation Bar](#navigation-bar)
  - [Landing page](#landing-page)
  - [Chalkboard](#chalkboard)
  - [Menu Page](#menu-page)
  - [Location and Events](#location-and-events-page)
  - [Concept and Story](#concept-and-story-page)
  - [Contact](#contact-page)
  - [Footer](#footer)
  - [Future Features](#future-features)
- [Testing](#testing)
  - [Testing Table](#testing-table)
  - [Validator Testing](#validator-testing)
- [Thought Of Process](#thought-of-process)

## Introduction

At Lujain's is a fictional foodtruck passion project of, as the name of the foodtruck suggests, Lujain, wich you can find consistently in the same location during the weekends and at specific events. 

At Lujain's Footruck was born from Lujain's love of cooking and sharing food with everyone, as such it's target is an audience of all ages, especially people down on their luck thanks to the affordable prices wich aim not to make a profit but rather to cover its production costs.

The goal of the website is to help the new audience to find out the concept of the Foodtruck, Lujain herself and why she started this project, what to expect in the Menu , introduce them to the social media page and the biggest reason for visiting the website for new and old users will be to provide informations about the location and events. 

![Responsive Screenshot](/assets/images/readme-images/responsive-screenshot.webp)

## UX

### Site Purpose:

To give the users a way to find information about the location, the menu and the foodtruck itself.

### Site Goal:
To regularly update the users about new locations, events and menu changes.
To bring new user's attention to the social media platforms used to inform the audience about opening times, availability, menu and location.

### Audience:
Everyone who wants to enjoy local, affordable and homecooked food.

### Communication:
The website is structured in a way that once the user lands on it, it won't be overwhelmed by information. With one scroll the user will find a summary of all pages and possible reasons of the visit, structured tightly to not let the eyes wander aimlessly. 

### Current User Goals:
- To see regular updates of the locations, of the events and of the menu.
- To give the user a way to subscribe or get in contact with the owner of the foodtruck.

### New user Goals:
- To navigate the site with ease and clearly understand the information provided.
- To inform new users about the location, events and menu.
- To inform new users about the concept of the foodtruck.
- To introduce new users to the socia media page.

## Design

### Color Scheme:
- Text Color Selection<br>
The decision to utilize black color for the text was carefully considered to ensure optimal readability and visual contrast against the background.
Choosing a high-contrast color combination, such as black text on a light background, is also a recommended practice for improving accessibility. It ensures that users with visual impairments or color vision deficiencies can easily perceive and comprehend the text. By prioritizing accessibility in the color selection, the project aims to provide an inclusive experience for all users.

- Header Color Selection <br>
The header serves as a fixed element that accompanies the user's scrolling throughout the website, to emphasize its separation from the main content and to evoke a sense of exclusivity, the "Black Russian" color was chosen. This color provides a stark contrast against the vibrant background.
This design approach ensures that the header remains noticeable and accessible at all times.

- Heading Color Selection <br>
By employing the "Smokeywhite" color for the text on black chalkboards, the design captures the feeling of a relaxed atmosphere associated with handwritten chalkboard menus. It enhances the overall theme of the food truck website, conveying a sense of homemade goodness and approachability to visitors.

- Links and logos <br>
The color #ffb018, which also happens to be the color of the logo, has been carefully chosen to create engaging hover effects for both links and the logo itself. When users hover over links or the logo, the color transitions from the default state to #ffb018 providing visual feedback indicating interactivity and confirming an action to the user.

![Colour Palette](/assets/images/readme-images/colour-palette.webp)

### Typography:
- Fredericka the Great <br>
The choice of the "Fredericka the Great" font for headings was motivated by the desire to emulate the appearance of chalkboard handwriting. This font's characteristics with its uneven strokes create an authentic and chalk-like texture evoking a sense of informality, capturing the charm associated with chalkboard writings.

- Merriweather <br>
For elements such as headers, footers and events, the "Merriweather" font was selected to establish a more professional and polished tone. This font, compared to other fonts used for the website exudes professionalism and ensures that these important elements of the website are presented in a refined manner.

- Indie Flower <br>
The "Indie Flower" font was used to instill a sense of familiarity and approachability. This was used when trying to create a more intimate and cozy atmosphere, reinforcing the concept of homecooked food and a personal connection with the audience. 

By employing these fonts strategically the design achieves a balance between the friendly and professional atmosphere.

### Imagery:
The selection of images for the website involved a combination of royalty-free images and a few notable exceptions that warrant special mention:

- Hero Image <br>
The hero image mainly features a food truck wich was sourced from a royalty-free image provider. While the image captures the essence of a food truck it is important to note that the selection was limited by the availability of royalty-free options. As a result, the chosen image might not fully align with the exact vision or specific details of the project. Despite the limitations the food truck image serves as a visual representation of a mobile kitchen and the idea of serving delicious homecooked food on the go.

- Black Hero Image/Chalkboard frame <br>
A black frame was skillfully created by VFX artist and good friend Tony Manzi. The decision to use a black frame was driven by the desire to establish a strong contrast with the background wich features a light-colored wooden cutting board. The black frame effectively creates a visually striking separation that draws the viewer's attention.

- Logo <br>
The logo for the foodtruck featuring a loaf of bread has also been skillfully designed by Tony Manzi. The choice of a loaf of bread aligns with the concept of the foodtruck offering sandwiches.

- Menu Pictures <br>
Due to the specific theme of sandwiches on a cutting board with a black background it was challenging to find royalty-free pictures. With my life partner's and owner of the fictional foodtruck, Lujain's suggestion i explored Canvas AI wich was able to generate menu pictures that met my specific requirements.

## Features 

### Navigation Bar:

  - Featured on all  pages, the navigation bar ensures that the users always know their current location and have easy acces to different sections of the site by following the user's scrolling.
  
  - The key design principle of the navigation bar is to provide clear visual cues regarding the user's location with the website by highlighting the location through the use of an underline (inspired by Love Running project).
  
  - To enhance the interactivity of the navigation bar, hovering over the links triggers a color change effect. When users hover over the logo and navigation links, the color changes to #ffb018, providing visual feedback.

  - The logo hover function has been created by positioning 2 logos on top of each other. The coloured version with a higher z-index value was positioned above the white logo while setting it's opacity to 0%. Once hovered the opacity changes to a value visible to the user creating a visual feedback and a sense of interactivity.

  - The navigation bar is designed to adapt to different screen sizes. It utilizes two "nav" elements, each with its own visibility based on the width of the viewport. Above a width threshold of 1025px wich is typical on larger screens such as desktop and laptops, the primary navigation bar is displayed.
![Primary Navigation Bar](/assets/images/readme-images/navbar.webp)

- Below a threshold of 1024px, tipycal on smaller screens such as mobile devices the navigation bar transforms into a hamburger icon, indicating the presence of a sliding menu. <br>
  The idea for this, especially the use of gradient coloring for the hamburger icon has been inspired by https://alvarotrigo.com/blog/hamburger-menu-css-responsive/ wich i later customized to adapt to the specific requirements and aesthetics of my website.
![Secondary Navigation Bar](/assets/images/readme-images/navbar-2.webp)

### Landing page:

  - The landing page includes a photograph of a foodtruck as the hero image. This enables visitors to quickly recognize and relate to a food truck website.

  - To ensure a user-friendly experience, the landing page includes four distinct, for a lack of a better definition, "summary boxes" that represent each a section of the website: menu, location & events, concept & story and contact. These boxes help the user find what they are looking for without overwhelming them with information. Each summary box is accompanied by an intuitive and interactive button. When users hover over these button the color scheme transforms providing visual feedback and highlighting an interactive object.
  ![Summary Boxes](/assets/images/readme-images/summary-box.webp)

  - The landing page has been designed with intuitive navigation in mind. It can be scrolled through with a single scroll (on a desktop/laptop size screen) and only one click is necessary to reach the goal of the visit. By minimizing the effort required to find information i prioritize a user-friendly and convenient environment. 

### Chalkboard:
  - Upon entering any page outside the landing page the users are welcomed by a black chalkboard stating the location of website. This consistency reinforces the sense of location of the user. Combined with the fixed header and the underlined active page it ensures the user never feels lost on this website.
  The font "Fredericka the Great" has been used to mimic the chalk like handwritten aspect familiar with chalkboards. 
  ![Chalkboard](/assets/images/readme-images/chalkboard-welcome.webp)

### Menu page:

  - The users landing on the menu page are specifically interested in food so i allowed the page to be longer in order to be able to present each item with its description of the ingredients and an image. This way the user can make a detailed and informed choice.
  ![Menu Item](/assets/images/readme-images/menu-item.webp)

### Location and Events page:

  - The location and events page is designed to provide users with essential information about the food truck's whereabouts and upcoming events. The page is divided into two distinct sections.  
  
  - The upper part of the page is dedicated to providing users with detailed information about the food truck's location through an embedded Google Map and a description next to it. The interactive map enables the users to visualize the area and convienently plan their visit.
  ![Location Preview](/assets/images/readme-images/location-preview.webp)

  - The lower part of the page in a separated section users can find informations about the upcoming events wich will be regularly updated. 
  ![Events Preview](/assets/images/readme-images/events-preview.webp)

### Concept and Story page:

  - The concept and story page serves as a platform to immerse users in the unique vision and values behind the food truck. This page is divided into three distinctive sections, providing information about the concept, eco-friendly practices and the story that led to the creation of the foodtruck.

  - The first section of the page introduces users to the core concept. Through a combination of images and descriptions i aim to convey the essence of the concept of the food truck: every dish is lovingly prepare in a home-cooked style. In some instances certain images have been chosen for my own personal amusement and do not depict the exact content in a literal sense (see the gnome in the snow representing "small and fresh" and the happy loaf of bread). 
  ![Concept Preview](/assets/images/readme-images/concept-preview.webp)

  - In a standalone section i placed some special emphasis on the commitment to eco-friendly practices. Here users are informed that the owner prioritizes the use of eco-friendly materials wich aligns harmonously with the overall concept of the food truck.
  ![Eco-Friendly Preview](/assets/images/readme-images/eco-friendly-preview.webp)

  - The final section of the page delves into the inspiring story behind the creation of the food truck. An image of the owner herself and the narrative enables the users to connect with the passion and dedication behind every aspect of the food truck: the unwavering will (i was waiting forever for an excuse to use this line) of delivering exceptional homemade food infused with love. 
  ![Story Preview](/assets/images/readme-images/story-preview.webp)

### Contact page:

  - The contact page server as a direct way of communication between the users and the owner. This way the users can recognize that their opinion and suggestions are valued while being rewarded for their activity with updates and informations.

  - The first section of the contact page features a contact form where users can easily get in touch to share their suggestions and feedback. By filling out the contact form a "form-dump" page opens thanking them for getting in contact. 
  ![Contact Preview](/assets/images/readme-images/contact-preview.webp)

  - The second section of the contact page features a subscribe form wich offers the opportunity of staying informed about any updates, changes to the menu, location and events. By filling out the subscribe form a "form-dump" page opens thanking them for subscribing.
  ![Subscribe Preview](/assets/images/readme-images/subscribe-preview.webp)

  - Upon submission of either form, users will be redirected to a corresponding form-dump page to confirm their submission.
  ![Form-Dump 1 preview](/assets/images/readme-images/form-dump-1-preview.webp)
  ![Fomt-Dump 2 preview](/assets/images/readme-images/form-dump-2-preview.webp)

### Footer:

  - The footer section follows the same concept as the header, creating a distinctive and consistent visual experience separating it from the rest of the website. It includes a smaller version of the logo, contact information and relevant social links. 

  - To keep consistency with the header and the rest of the website the social links also feature an interactive design in order to promote a visual feedback to the user. The social links open the associated social platform in a new tab.

  - As with the header also the footer's design is consistent in all pages giving the user a sense of familiarity when navigating the website.
![Footer Preview](/assets/images/readme-images/footer-preview.webp)

### Future Features:

- Multiple scrolling images in the landing page.
- A gallery.
- An error page with a "return to the homepage" button.

## Testing 

### Testing Table:

**TEST** | **ACTION** | **EXPECTATION** | **RESULT** 
----------|----------|----------|----------
Header - All Pages | Size down from 1920px, testing down to the minimum width for every viewport breaking point <br>(max-width:1441px, 1281px, 1141px (header only), 1025px, 769px, 646px (footer only), 481px, 361px) to 320px using Dev Tools on Chrome, Firefox and Edge. Safari has been so far tested only on mobile devices without the Dev Tool due to missing hardware | Elements look good down to 320px | Works as expected
Header - All Pages | Primary Nav Bar Buttons and Logo | Each nav element and logo take the user to the correct page, active page underline present, hover function on logo and links | Works as expected
Header - All Pages | Hidden Nav Bar,<br> Hidden Nav Bar Buttons | The nav bar slides correctly from the side, each nav element and logo take the user to the correct page, active page underline present, hover function on logo and links | Works as expected
Home Page | Size down from 1920px, testing down to the minimum width for every viewport breaking point <br>(max-width:1441px, 1281px, 1141px (header only), 1025px, 769px, 646px (footer only), 481px, 361px) to 320px using Dev Tools on Chrome, Firefox and Edge. Safari has been so far tested only on mobile devices without the Dev Tool |  Elements look good down to 320px  | Works as expected
Home Page | Internal Links | Each anchor element takes the user to the correct page, hover function on buttons inverting color | Works as expected
Menu Page | Size down from 1920px, testing down to the minimum width for every viewport breaking point <br>(max-width:1441px, 1281px, 1141px (header only), 1025px, 769px, 646px (footer only), 481px, 361px) to 320px using Dev Tools on Chrome, Firefox and Edge. Safari has been so far tested only on mobile devices without the Dev Tool | Elements look good down to 320px | Works as expected
Location&Events Page | Size down from 1920px, testing down to the minimum width for every viewport breaking point <br> (max-width:1441px, 1281px, 1141px (header only), 1025px, 769px, 646px (footer only), 481px, 361px) to 320px using Dev Tools on Chrome, Firefox and Edge. Safari has been so far tested only on mobile devices without the Dev Tool | Elements look good down to 320px | Works as expected
Location&Events Page | Embedded Google Map | Ability to interact with it on Chrome, Firefox, Edge and Safari | Works as expected
Concept&Story Page | Size down from 1920px, testing down to the minimum width for every viewport breaking point <br> (max-width:1441px, 1281px, 1141px (header only), 1025px, 769px, 646px (footer only), 481px, 361px) to 320px using Dev Tools on Chrome, Firefox and Edge. Safari has been so far tested only on mobile devices without the Dev Tool | Elements look good down to 320px | Works as expected
Contact Page | Size down from 1920px, testing down to the minimum width for every viewport breaking point <br> (max-width:1441px, 1281px, 1141px (header only), 1025px, 769px, 646px (footer only), 481px, 361px) to 320px using Dev Tools on Chrome, Firefox and Edge. Safari has been so far tested only on mobile devices without the Dev Tool | Elements look good down to 320px | Works as expected
Contact Page | Send Button for contact and subscribe form | Redirects the user to the correct page | Works as expected
Form-Dump Contact | Size down from 1920px, testing down to the minimum width for every viewport breaking point <br> (max-width:1441px, 1281px, 1141px (header only), 1025px, 769px, 646px (footer only), 481px, 361px) to 320px using Dev Tools on Chrome, Firefox and Edge. Safari has been so far tested only on mobile devices without the Dev Tool | Elemets look good down to 320px | Works as expected
Form-Dump Subscribe | Size down from 1920px, testing down to the minimum width for every viewport breaking point <br> (max-width:1441px, 1281px, 1141px (header only), 1025px, 769px, 646px (footer only), 481px, 361px) to 320px using Dev Tools on Chrome, Firefox and Edge. Safari has been so far tested only on mobile devices without the Dev Tool | Elemets look good down to 320px | Works as expected

### Validator Testing:

- HTML
  - No errors were returned when passing through the official [W3C validator]
  - Home Page ![Home Validator](/assets/images/readme-images/home-validator.webp)
  - Menu Page ![Menu Validator](/assets/images/readme-images/menu-validator.webp)
  - Location&Events Page ![Location&Events Validator](/assets/images/readme-images/location-events-validator.webp)
  - Concept&Story Page ![Concept&Story](/assets/images/readme-images/about-me-validator.webp)
  - Contact Page ![Contact Validator](/assets/images/readme-images/contact-validator.webp)
  - Form-Dump Contact Page ![Form Dump 1 Validator](/assets/images/readme-images/form-dump-validator.webp)
  - Form-Dump Subscribe Page ![Form Dump 2 Validator](/assets/images/readme-images/form-dump-2-validator.webp)
- CSS
  - No errors were found when passing through the official (Jigsaw) validator ![CSS Validator](/assets/images/readme-images/css-validator.webp)

## Thought Of Process

### Unfixed Bugs

You will need to mention unfixed bugs and why they were not fixed. This section should include shortcomings of the frameworks or technologies used. Although time can be a big variable to consider, paucity of time and difficulty understanding implementation is not a valid reason to leave bugs unfixed. 

## Deployment

This section should describe the process you went through to deploy the project to a hosting platform (e.g. GitHub) 

- The site was deployed to GitHub pages. The steps to deploy are as follows: 
  - In the GitHub repository, navigate to the Settings tab 
  - From the source section drop-down menu, select the Master Branch
  - Once the master branch has been selected, the page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment. 

The live link can be found here - https://code-institute-org.github.io/love-running-2.0/index.html 


## Credits 

In this section you need to reference where you got your content, media and extra help from. It is common practice to use code from other repositories and tutorials, however, it is important to be very specific about these sources to avoid plagiarism. 

You can break the credits section up into Content and Media, depending on what you have included in your project. 

### Content 

- The text for the Home page was taken from Wikipedia Article A
- Instructions on how to implement form validation on the Sign Up page was taken from [Specific YouTube Tutorial](https://www.youtube.com/)
- The icons in the footer were taken from [Font Awesome](https://fontawesome.com/)

### Media

- The photos used on the home and sign up page are from This Open Source site
- The images used for the gallery page were taken from this other open source site


Congratulations on completing your Readme, you have made another big stride in the direction of being a developer! 

## Other General Project Advice

Below you will find a couple of extra tips that may be helpful when completing your project. Remember that each of these projects will become part of your final portfolio so it’s important to allow enough time to showcase your best work! 

- One of the most basic elements of keeping a healthy commit history is with the commit message. When getting started with your project, read through [this article](https://chris.beams.io/posts/git-commit/) by Chris Beams on How to Write  a Git Commit Message 
  - Make sure to keep the messages in the imperative mood 

- When naming the files in your project directory, make sure to consider meaningful naming of files, point to specific names and sections of content.
  - For example, instead of naming an image used ‘image1.png’ consider naming it ‘landing_page_img.png’. This will ensure that there are clear file paths kept. 

- Do some extra research on good and bad coding practices, there are a handful of useful articles to read, consider reviewing the following list when getting started:
  - [Writing Your Best Code](https://learn.shayhowe.com/html-css/writing-your-best-code/)
  - [HTML & CSS Coding Best Practices](https://medium.com/@inceptiondj.info/html-css-coding-best-practice-fadb9870a00f)
  - [Google HTML/CSS Style Guide](https://google.github.io/styleguide/htmlcssguide.html#General)

Getting started with your Portfolio Projects can be daunting, planning your project can make it a lot easier to tackle, take small steps to reach the final outcome and enjoy the process! 