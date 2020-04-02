This is my first Milestone Project as part of the Code Institute's Diploma in Software Development.

## Mark Cavendish - Professional Cyclist

This website is designed to profile the professional cyclist, Mark Cavendish. It offers users a platform to learn more about who Mark is, keep up-to-date with his racing schedule & results as the season progresses and get an insight into his life both on and off the bike, as documentated through his various social channels.

*NB for C.I. assessment purposes - it has been my intention to develop this website for a friend who is an up-and-coming semi-professional cyclist in Ireland. However, as a result of some unexpected personal circumstances I was unable to engage with him throughout the project duration, to consider content and obtain suitable images. I therefore retained the concept but pivoted my approach to producing a website for Mark Cavendish, given my own knowledge and readily available content/resources.*

## (1) UX

The website has been designed for a range of users - from those who are cycling enthusiasts and fans of Mark Cavendish, to those who are trying to learn about who Mark is for the first time. Whatever the user background, they should hopefully find the website format engaging and easy to navigate, and the content informative.

The consolidated platform enables users to learn about Mark's past success, follow his latest racing schedule, explore his social channels and, as appropriate, easily contact Mark to discuss the potential of a commercial partnership.

#### User Stories
As a new user of this website, I want to be able to:
* intuitively understand the flow of the content and format.
* quickly understand how to navigate through the website.
* be engaged through content styling, format and content.

As a new or repeat user who is an "active" cycling fan, I want to be able to:
* easily locate information on Mark's latest racing result.
* access more in-depth reporting on the race through a link to an relevant external website.
* easily see the next event in which Mark is scheduled to race.

As a new user who wants to learn more about Mark, I want to be able to:
* easily find information about who Mark is, including his background in cycling.
* readily access his various social channels to learn more about Mark and his day-to-day life.

As a new user who is a potential collaboration partner with Mark, I want to be able to:
* easily find information about who Mark is, including his background in cycling.
* readily access his various social channels to learn more about Mark's lifestyle and assess whether he would be a good fit to work with.
* have available a simple mechanism/feature by which I can make initial contact with Mark/his team.

### Wireframes
Wireframes for this website can be accessed in my wireframes folder within this github repository - [my wireframes](https://github.com/MichaelpHann/UCFD-Milestone-Project/tree/master/wireframes)

## (2) Features

### Layout
The website was designed with simplicity in mind, whilst being immediately engaging for the user. Having several features/sections on the main hompeage allows the user to easily find a point of particular interest. The subsequent two pages provide for more specific use functions.

### Font
There are two fonts used throughout the website - "Muli" and "Quicksand". Both are engaging, easy to read and versatile. A variety of letter spacing has been used throughout the website.

### Existing Features
* *Navigation Bar* - This has been sourced from Boostrap with adhoc styling applied. The navbar is implemented in a consistent manner across all three website pages. It is device responsive and the menu items will collapse into a dropdown menu depending on device size. The MARK CAVENDISH header/title acts as an alternative homepage link/menu option.

* *Racing jumbotrons & external links* - The two racing subsections are created through implementation of Bootstrap jumbotrons, with adhoc styling applied. These jumbotrons are device responsive. The external links direct the user to relevant additional information.

* *Social image carousel & social links* - The image carousel hs been sourced from Boostrap with adhoc styling applied. The feature controls allow users to click through images or return to a previous image. The carousel is device responsive.

  * Social links have been included on the Homepage in the *Social* section and as part of the footer in the other two website pages. Although asymmetric in terms of location of the social links on the Homepage versus the other two pages, I have attempted to connect them visually through use of the same bold colour.

* *Collaboration Button* - This offers a clear direction to users and brings them to the dedicated contact/collaboration page. The hover colour change indicates illustrates to the user that the button is active/responsive.

* *Contact page form* - This form has been sourced from Boostrap with adhoc styling applied. It has been styled in a way to offer clear instructions through the use of placeholders in each input section. The hover colour change prompts the user to click the button to submit. THere are form validations in each input section, including the requirements for a valid email format.

### Features left to implement
* As per original wireframes, I think a dedicated, interactive Racing page would be a valuable additional feature. It could allow the user a more indepth insight into Mark's racing season, perhaps including a dashboard with, for example, power output during the race which is a commonly tracked metric.
* A mechanism to periodically refresh/update images (and perhaps tweets) from Mark's social channels, rathering than having to manually load the images.
* Appropriate architecture/mechanism to caputre submitted form inputs.
* The tables in the profile section have been constructed using key/value pairs, rather than using a standard table format. This was a conscious decision as it would be nice to add additional responsiveness to these sections/features particularly across device types - i.e. that tehy would not necessarily remain in tabular format.

## (3) Technologies Used

* This project has been completed using HTML & CSS programming languages.

### Libraries / other technologies used
This project uses:
* **Bootstrap 4.3.1** to simplify elements of the website structure and improve its responsiveness - [Bootstrap](https://getbootstrap.com/)
* **Googe Fonts** to style the website fonts - [Google Fonts](https://fonts.google.com/)
* **Fontawesome 5.11.2** to style the website with icons - [Font Awesome](https://fontawesome.com/)

### Tools used
* **Gitpod** - was used to build the website.
* **Github** - was used to store project code remotely.
* **[Google Chrome Developer Tools](https://developers.google.com/web/tools/chrome-devtools)** - was used to test the device responsiveness of the website.
* **[Canva](https://www.canva.com/)** - was used to format and resize website images.

## (4) Testing

### User Testing
**Manual User Testing** was the primary method of testing during this project. A number of people were asked to visit the website using a variety of devices (both mobile and tablet) throughout the latter stages of the project. This testing and feedback was invaluable in uncovering bugs and finalising design/format.

Throughout the build I used Google Chome Developer tool to assess and amend device responsiveness of the website.

### Validator Tools Used
The following are websites used to validate the HTML and CSS code:
* [W3C HTML Validator](https://validator.w3.org/)
* [W3C CSS Validator](https://jigsaw.w3.org/css-validator/)

### Scenario Testing
1. Navigation Bar - Homepage, Profile page, Contact page
   1. Go to top of the homepage.
   2. Try to navigate to other pages using buttons indicated.
   3. Repeat step (ii) when on each page.
   4. Go to either Profile or Contact page. Try to return to the homepage by clicking MARK CAVENDISH icon.
   5. Repeat step (iv) for other page (either Profile or Contact).

2. Homepage - Racing section - external links
   1. Go to "Racing" section on the homepage.
   2. In the left/top jumbotron (depending on screen size), click the link and verify you are directed to an external website.
   3. In the right/bottom jumbotron (depending on screen size), click the link and verify you are directed to an external website.

3. Homepage - image carousel
   1. Go to the image carousel on the homepage.
   2. Click on the forwards/backwards icons and verify that you can navigate through the images.

4. Social Links - Homepage, Profile page, Contact page
   1. For each page go to the social link icons.
   2. Click on each of the 3 social media account icons and verify that you are taken to the relevant social media account.
  
5. Homepage - Collaboration button
   1. Go to "Collaboration" section on the homepage.
   2. Click on the 'Get in Touch' button and verify you are directed to the Contact page.
  
6. Profile page - Awards pictures/links
   1. Go to the Profile page
   2. Click on the image presented beneath/next to the first award narrative and verify that you are directed to an external website.
   3. Click on the image presented beneath/next to the second award narrative and verify that you are directed to an external website.
  
7. Contact page - form
   1. Go to the Contact page
   2. Try to submit an empty form and verify that an error message about required fields appears.
   3. Try to submit a completed form without a valid email address format and verfiy that a specific error message appears.

**Bugs identified**
* When hovering over the Instagram and Twitter social icons (on each page) a small line appears to the bottom right of the image.

## (5) Deployment
This project was developed using GitPod, with the repository stored on GitHub.

* The GitHub repository is [here](https://github.com/MichaelpHann/UCFD-Milestone-Project)
* The website is live [here](https://michaelphann.github.io/UCFD-Milestone-Project/)

### This website was deployed on GitHub Pages by undertaking the following steps:
1. Navigate to the repository - https://github.com/MichaelpHann/UCFD-Milestone-Project
2. In the GitHub header/navigation ribbon, select the "Settings" option.
3. Scroll down the page to the GitHub pages subsection.
4. Click on the "Source" dropdown and select "master branch".
5. Click to confirm selection.
6. The website should now be live on GitHub pages, with a link shown immediately above at the top of the GitHub Pages subsection.

### Instructions to run the project locally:
You must first ensure:
  * you have installed a preferred IDE, such as [VS Code](https://code.visualstudio.com/)
  * you have installed [Git](https://git-scm.com/)
 
1. Navigate to the project repository [here](https://github.com/MichaelpHann/UCFD-Milestone-Project).
2. Select the green "Clone or download" dropdown button.
3. Highlight the URL provided or click the button to copy the URL.
4. Open your terminal.
5. Navigate to the working directory where the cloned repository will be placed.
6. In the command line type "git clone" then paste the previously copied URL immediately after.
7. Press Enter.

For more information or guidance, please see the relevant help section [Cloning a Repository](https://help.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository)

## (6) Credits

### Content
* All narrative content has been written by the developer.
* As disclosed in this file, a number of template features, e.g. Navbar, Jumbotron, Carousel, have been sourced from Bootstrap, with adhoc styling applied by the developer.

### Media
* Images throughout the website have been sourced via Google Images but are being used for educational/assignment purposes only.

### Acknowledgements
I would like to thank my mentor, [Sandeep Aggarwal](https://github.com/asandeep), for his constructive feedback and guidance throughout the project.
