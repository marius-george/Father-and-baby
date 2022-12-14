
# Father and Baby

[View the live project here.](https://marius-george.github.io/Father-and-baby/)

This is the main Father and Baby website. It is designed to be responsibe and accessible on a range of devices, making it easy to navigate for potential parents. The purpose of the website is to provide information about ingredients and recipes to make great food for babies and toddlers.

![Website Mockup](./assets/img/mockup.jpg)

## User Experience (UX)

-   ### User stories

    -   #### First Time Visitor Goals

        1. As a First Time Visitor, I want to easily understand the main purpose of the site and find a big diversity of food recipes for babies and toddlers.
        2. As a First Time Visitor, I want to be able to easily navigate throughout the site to find content and layout of the website to feel intuitive.
        3. As a First Time Visitor, I want to look for information about how to prepare the recipes and what ingredients I need.

    -   #### Returning Visitor Goals

        1. As a Returning Visitor, I want to find new recipes and try something new.
        2. As a Returning Visitor, I want to find the best way to get in contact with the owner with any questions I may have.
        3. As a Returning Visitor, I want to find good website layout simple to use and easy on the eye.

    -   #### Frequent User Goals
        1. As a Frequent User, I want to have all the recipes on the website and have easy access on them.
        2. As a Frequent User, I want to check to see if there are any new food and alergies information that parents might know.
        

-   ### Design
    -   #### Colour Scheme
        -   The two main colours used are turqoise and light grey.
    -   #### Typography
        -   The Mitr font is the main font used throughout the whole website with Sans Serif as the fallback font in case for any reason the font isn't being imported into the site correctly. Mitr is a clean font used in food websites, so it is both attractive and appropriate.
    -   #### Imagery
        -   Carousel and About Us images are from Shutterstock (https://www.shutterstock.com/). I had to edit them in Photoshop to change the resolution and resize them to fit the carousel.
        -   Recipe images are from Annabel Karmel website (https://www.annabelkarmel.com/).
        -   Logo was created and edited at (https://www.freelogocreator.com/).


*   ### Wireframes

    -   Home Page Wireframe - [View](https://ibb.co/hRnz0wC)

    -   Mobile Wireframe - [View](https://ibb.co/QDxVNwb)

    

## Features

-   Responsive on all device sizes 

-   Interactive menu bar with hambuger icon on small devices.

-   Carousel gallery on main page with 3 images that change after few seconds.

## Technologies Used

- HTML
- CSS
- Bootstrap
- Java Script

### Languages Used

-   [HTML5](https://en.wikipedia.org/wiki/HTML5)
-   [CSS3](https://en.wikipedia.org/wiki/Cascading_Style_Sheets)
-   [Bootstrap](https://en.wikipedia.org/wiki/Bootstrap)
-   [Java Script](https://en.wikipedia.org/wiki/JavaScript)

### Frameworks, Libraries & Programs Used

1. [Bootstrap 4.4.1:](https://getbootstrap.com/docs/4.4/getting-started/introduction/)
    - Bootstrap was used to assist with the responsiveness and styling of the website.
1. [Hover.css:](https://ianlunn.github.io/Hover/)
    - Hover.css was used on the Social Media icons in the footer to add the float transition while being hovered over.
1. [Google Fonts:](https://fonts.google.com/)
    - Google fonts were used to import the 'Titillium Web' font into the style.css file which is used on all pages throughout the project.
1. [Font Awesome:](https://fontawesome.com/)
    - Font Awesome was used on all pages throughout the website to add icons for aesthetic and UX purposes.
1. [Git](https://git-scm.com/)
    - Git was used for version control by utilizing the Gitpod terminal to commit to Git and Push to GitHub.
1. [GitHub:](https://github.com/)
    - GitHub is used to store the projects code after being pushed from Git.
1. [Photoshop:](https://www.adobe.com/ie/products/photoshop.html)
    - Photoshop was used to create the logo, resizing images and editing photos for the website.
1. [Balsamiq:](https://balsamiq.com/)
    - Balsamiq was used to create the [wireframes](https://github.com/) during the design process.

## Testing

The W3C Markup Validator and W3C CSS Validator Services were used to validate every page of the project to ensure there were no syntax errors in the project.

-   [W3C Markup Validator](https://jigsaw.w3.org/css-validator/#validate_by_input) - [Results](https://ibb.co/PhGB3cG)
-   [W3C CSS Validator](https://jigsaw.w3.org/css-validator/#validate_by_input) - [Results](https://ibb.co/56zSgnN)

### Testing 
1. With the website opened I made sure that when you click on the logo and Home link it goes to the homepage.
2. When clicked on the link from the navbar in the homepage all links goes to the specified page, recipes or contact us.
3. in the footer when clicked on the links all direct to the relevant webpages.
4. In the recipes page when clicked on an image it should load the full recipe page and show all relevant information.
5. In the contact us form all working and when form submited it should return Code Institute website with the correct data sent.
6. Used Chrome developers tools to resize the webpage and it was responsive at all resolutions.


### Further Testing

-   The Website was tested on Google Chrome, Mozilla Firefox, Microsoft Edge and Safari browsers.
-   The website was viewed on a variety of devices such as Desktop, Laptop, iPad, Samsung Galaxy TAB, iPhone 13 and Huawei P30 Pro.

### Bugs

- When scrooling the main page navigation bar is always fixed but does not highlight sections. When About Us section is active the fixed menu bar should highlight About link in Turqoise colour.
- Font Awesome icons does not show corectly in footer section. I still have to figure it out how to make them work. Reason is Font Awesome website changed how icons work and now they have free and paid icons.


## Deployment

1. Deployment has been made in github using the following commands:
  - git status to check the status of the files in github
  - git add . to add all modified files
  - git commit -m "example text" to index all that has been modified to the website
  - git push to upload the website in the cloud
  - python3 -m http.server in the terminal to view the page working in a separate tab of the web browser.


### GitHub Pages

The project was deployed to GitHub Pages using the following steps...

1. Log in to GitHub and locate the [GitHub Repository](https://github.com/)
2. At the top of the Repository (not top of page), locate the "Settings" Button on the menu.
    - Alternatively Click [Here](https://raw.githubusercontent.com/) for a GIF demonstrating the process starting from Step 2.
3. Scroll down the Settings page until you locate the "GitHub Pages" Section.
4. Under "Source", click the dropdown called "None" and select "Master Branch".
5. The page will automatically refresh.
6. Scroll back down through the page to locate the now published site [link](https://github.com) in the "GitHub Pages" section.

### Forking the GitHub Repository

By forking the GitHub Repository we make a copy of the original repository on our GitHub account to view and/or make changes without affecting the original repository by using the following steps...

1. Log in to GitHub and locate the [GitHub Repository](https://github.com/)
2. At the top of the Repository (not top of page) just above the "Settings" Button on the menu, locate the "Fork" Button.
3. You should now have a copy of the original repository in your GitHub account.

### Making a Local Clone

1. Log in to GitHub and locate the [GitHub Repository](https://github.com/)
2. Under the repository name, click "Clone or download".
3. To clone the repository using HTTPS, under "Clone with HTTPS", copy the link.
4. Open Git Bash
5. Change the current working directory to the location where you want the cloned directory to be made.
6. Type `git clone`, and then paste the URL you copied in Step 3.

```
$ git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY
```

7. Press Enter. Your local clone will be created.

```
$ git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY
> Cloning into `CI-Clone`...
> remote: Counting objects: 10, done.
> remote: Compressing objects: 100% (8/8), done.
> remove: Total 10 (delta 1), reused 10 (delta 1)
> Unpacking objects: 100% (10/10), done.
```

Click [Here](https://help.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository#cloning-a-repository-to-github-desktop) to retrieve pictures for some of the buttons and more detailed explanations of the above process.

## Credits

- https://www.shutterstock.com - For providing the images for the carousel.
- https://www.annabelkarmel.com - For providing the pictures of the recipes.
- https://www.freelogocreator.com - Helped me with the logo of the team.


### Content

-   Partial content was written by the developer.
-   Recipes content is from (https://www.annabelkarmel.com) website. 


### Media

-   All Images were downloaded from https://www.shutterstock.com and https://www.annabelkarmel.com websites.

