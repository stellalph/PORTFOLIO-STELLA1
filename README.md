## A) TASK

The task here is build up a portfolio page from scratch to showcase my skills and talents to prospective employers.  I approach this task by using the core ideas that I gained from the class and tutorials and also prework research on HTML, CSS and Javascript.  I have also decided to use a little of Javascript for the navigation bar and CSS animation to meet the acceptance criteria outlined.  As this is my first portfolio page where I could show my work selection or samples for employer's viewing and in case, I do not want to overwrite my first portfolio, I give my repository name "PORTFOLIO-STELLA1".


## B) ACCEPTANCE CRITERIA

Steps taken to meet the critical requirements necessary to develop my portfolio page that satisfies a typical hiring manager:-

    1)  In the PORTFOLIO-1 folder, I have created the following files : -

         *  index.html - setting up the structure of my portfolio page according to semantic HTML rules.

         *  style.css  - where I would style the portfolio page for example, the color of the text, the style of the fonts, the spacing between paragraphs, how the columns are sized and laid out, what background images or colors are used, layout designs, variations in display for different devices and screen sizes as well a variety of other effects.
            
         *  index.js - used for performing the little function for the "hamburger" icon at the top right hand corner of the portfolio page. This would be the next step in which I would give a brief description of its usage.
            
         *  I have gathered a few images namely image-01.jpg (a recent photo of myself), image-02.jpg(the meaning motivated me), portfolio-01.jpg (my first task which have deployed on GitHub), portfolio-02.jpg to portfolio.06 are placeholder images.  

    2)  The criteria of :-
        
        GIVEN I need to sample a potential employee 's previous work 
        WHEN I load their portfolio
        THEN I am presented with the developer's name, a recent photo or avatar, and links to sections about them, their work and 
        THEN I click on the link one of the links in the navigation
        THEN the UI scrolls to the corresponding section.

        *   Click on the hamburger icon will show the different sections of navigation bar and further click on the different sections will provide a smooth scrolling down to the different sections.

        * I have structured HTML and CSS to different sections:-

          - Home (Introduction in both HTML and CSS files - where the recent photo, name and position title are located)

          - My Skills (What I do - list of skills)

          - About Me (Who I am - more details on what kind of individual and way of contacting me for further information)

          - My Work ( a showcase of my work selection using HTML, CSS, Javascript and Node.js).  At this stage, I have only one deployed application.

     3) The criteria of : -

        WHEN I click on the link to the section about their work
        THEN the UI scrolls to a section with titled images of the developer's applications.
        THEN that application 's image should be larger in size than the others
        WHEN I click on the images of the application
        THEN I am taken to that deployed application

        *   Click on the "MY WORK" button, UI will scroll to the images of placeholder images and one deployed application (the first image on the top-left).

        *   Hover over the image, the image will be larger in size than the others.

        *   Click on the first image on top left corner of My Works section will bring to my deployed application.  Please note that the rest are placeholder images and I will not provide the link.

    4)  The criteria of :-

        WHEN I resize the page or view the site on various screens and devices
        THEN I am presented with a responsive layout that adapts to my viewport

        *   I have used the concept of media query to provide the responsive layout that would cater for various screens and devices.  Please refer to my deployed site on PORTFOLIO-STELLA1
        in which portfolio page do work for smaller screens size.

    5)  Footer - I have provided my contact as a link to my email address and obtained the brand icons from Font Awesome website (free).   


 ## C)  DEPLOYMENT

 GitHub is a free cloud drive that allows to store all our projects and codes.  In case, someone accidentally deleted the work while I decided to go for a break.  Hitting undo is no longer an option.  This software allows us to go back in time.  This free cloud drive is a life-saver!  

        * Navigate to the directory where all PORTFOLIO-1 files are located
        $ ls -al to check all the files are there
        $ touch READme.md
        $ git init
        $ git status
        $ git add .
        $ git commit -m "initial commit"
    
To connect the local repository to the remote repository, create a new repository named "PORTFOLIO-1" and not clicking any of the checkbox, click on the "Create New Respository"

Copy the code to the local repository.

The URL of the GitHUB repository for this task is https://github.com/stellalph/PORTFOLIO-STELLA1.git and the URL of the deployed application is https://stellalph.github.io/PORTFOLIO-STELLA1/
