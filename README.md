# IO-Math-Lessons_Pythagora's-theorem #


The live website of Pythagora's theorem lesson can be viewed [here](https://emusat2021.github.io/Lesson---Pythagoras-Theorem/)

todo image https://imgbb.com/

1st milestone project: User-Centric Frontend Development - [Code Institute](https://codeinstitute.net/) assignment project.

This is an non profit organisation "IO Math Lessons" who provides websites with math lessons.
The math lessons are intended to be used for pupils in secondary school (5th to 9th grade) in order to help them learn a math lesson more easily.
 
Pythagora's theorem is the first lesson offered by **_IO Math Lessons_**.

The lesson is presenting Pythagora's theorem as well as images for better understanding, video and exercises.

This website gives the opportunity to contact IO Math Lessons and it is providing a form to send messages with a posible lesson request.



See IO Math Lessons offical website [here]todo

# Table of Contents

1. [UX](#ux)
  * [Users stories](#users-stories)
  * [Design](#design)
2. [Features](#features)
  * [Existing Features](#existing-features)
    + [Navbar](#navbar)
    + [Images](#images)
    + [Video](#video)
    + [Forms](#forms)
    + [Description page](#description-page)
    + [Lesson and Exercises page](#lesson-and-exercises-page)
    + [Contact](#contact)
  * [Features Left to Implement](#features-left-to-implement)
3. [Technologies Used](#technologies-used)
  * [Languages Used](#languages-used)
  * [Frameworks, Libraries, Programs Used & other tools](#frameworks--libraries--programs-used---other-tools)
4. [Testing todo](#testing-todo)
5. [Deployment](#deployment)
6. [Credits](#credits)
  * [Code](#code)
  * [Content](#content)
  * [Media](#media)
  * [Acknowledgements](#acknowledgements)
7. [Disclaimer](#disclaimer)

# UX
## Users stories

As a... | I want to... | To be able to...
---------|--------------|--------------
User | Understand Pythagora Theorem | To demonstrate knowledge at school
User | Practice with excercises | Test my knowledge
User | Have a readable lesson | Easily understand the info presented
User | See my test results | Have feedback on my learning progress

## Design

The goal in design was to create a website for a math lesson that is overall user friendly. 
The pupil will easily understand the info presented.
The pupil will practice with excercises.
The color of the backgroud, video, images will capture the pupil's attention to the lesson and make the lesson more interesting. 

**Wireframes**:
![Wireframes](assets/wireframes/first_page_description.png)
![Wireframes](assets/wireframes/second_page_lesson.png)
![Wireframes](assets/wireframes/third_page_exercises.png)
![Wireframes](assets/wireframes/mobiletablet.png)

# Features

## Existing Features

### Navbar
- Navbar at the top - helping user to easily navigate to diferent pages.
- Fixed navigation bar visible on every page including a dropdown menu.
### Images
Images with Pythagora's teorem which bring more ease to understand the lesson.
### Video
The video from the "Lesson" page is to capture the pupil's attention to the lesson and make the lesson more interesting.
### Forms
- Forms are used to create a test in the "Lesson and Exercises" page for the pupil to asses him/herself at the end of the lesson. 
- There are buttons that are providing correct answers, as well, for test feedback.
### Description page
Description is the *first page* of **Pythagora's theorem**. 
The following pieces of information are on this page:
* A basic presentation of Pythagora's theorem;
* Pythagora's picture;
* Formula for the theorem;
* A colorful image that presents the formula in a more pleasant way for the pupil.

### Lesson and Exercises page
Lesson and Exercises is the *second page* of **Pythagora's theorem**.
The following pieces of information are on this page:
* A lesson in which the theorem is presented with an example of how to calculate a triangle's side using the theorem.
* A video where another exemple is presented in order for pupil to understand the theorem.
* A suggestive image that presents the formula for the pupil.
* A test with three exercises where the pupil can test the knowledge of the theorem.
* Possibility for the pupil to fill in an answer calculated by him/herself.
* Possibility for the pupil to choose the correct answer.
* A suggestive image with the purpose of helping to better calculate the formula for the exercises.

### Contact 
todo

## Features Left to Implement

* One of the improvments that can be done is to provide a submit button for the "Exercises" page and use JavaScript to auto-grade the test.
* Another feature that I would like to implement back-end for contact and sign-up form to make them fully functional.

 
# Technologies Used

## Languages Used

* The app was created using HTML5 styled with custom CSS3 styles.
* The logic scripts were written in JavaScript.

## Frameworks, Libraries, Programs Used & other tools 

1. [Bootstrap 4.6:](https://getbootstrap.com/docs/4.6/getting-started/introduction/)
* Bootstrap 4.6 css was used to create the navigation bar, as well as 'Exercises' page, responsive design, etc.
2. [Google Fonts:](https://fonts.google.com/)
* Google fonts were used to import the Roboto font into the style.css file which is used on all text elements of the app.
3. [Git:](https://azure-loon-ay9p18v0.ws-eu03.gitpod.io/#/workspace/Lesson---Pythagoras-Theorem)
* Git was used for version control by commiting to local repository and pushing to GitHub.
4. [GitHub:](https://github.com/)
* GitHub was used to store the project's code after being pushed from local repository.
5. [Balsamic:](https://balsamiq.com/wireframes/desktop/#)
* Balsamic was used to create the wireframes shown above for the front end design.
6. [Markdown TOC generator](https://ecotrust-canada.github.io/markdown-toc/)
7. [Logo](https://secure.logomaker.com/myprojects)


# Testing todo
- test that navbar is fixed on mobile on all pages.
- test that navbar is fixed on larger devices on all pages.
- test that container top margin is appropriate on mobile on all pages.
- test that container top is appropriate on larger devices on all pages.
- test that navbar collapse button on small devices is displayed properly.
- test that navbar collapsed content is fully expanded on small devices.



In this section, you need to convince the assessor that you have conducted enough testing to legitimately believe that the site works well. Essentially, in this part you will want to go over all of your user stories from the UX section and ensure that they all work as intended, with the project providing an easy and straightforward way for the users to achieve their goals.
Whenever it is feasible, prefer to automate your tests, and if you've done so, provide a brief explanation of your approach, link to the test file(s) and explain how to run them.
For any scenarios that have not been automated, test the user stories manually and provide as much detail as is relevant. A particularly useful form for describing your testing process is via scenarios, such as:
1.	Contact form:
i.	Go to the "Contact Us" page
ii.	Try to submit the empty form and verify that an error message about the required fields appears
iii.	Try to submit the form with an invalid email address and verify that a relevant error message appears
iv.	Try to submit the form with all inputs valid and verify that a success message appears.
In addition, you should mention in this section how your project looks and works on different browsers and screen sizes.
You should also mention in this section any interesting bugs or problems you discovered during your testing, even if you haven't addressed them yet.
If this section grows too long, you may want to split it off into a separate file and link to it from here.

# Deployment

GitHub Pages
The project was deployed to GitHub Pages using the following steps:

1. Logged in to GitHub and located the [GitHub Repository](https://github.com/emusat2021/Lesson---Pythagoras-Theorem)
2. At the top of the Repository, located the "Settings" Button on the menu.
3. Scrolled down the Settings page until "GitHub Pages" Section was located.
3. Under "Source", clicked the dropdown called "None" and selected "Master Branch".
4. The page automatically refreshed.
5. Scrolled back down through the page to locate the now published site [link](https://emusat2021.github.io/Lesson---Pythagoras-Theorem/) in the "GitHub Pages" section.

# Credits

## Code
* Code for navbar taken from:https://getbootstrap.com/docs/4.6/components/navbar/ and eding slightly to fit project needs*/
* Code for About us page from [Code Institute-Mini Project with Bootstrap 4 ](https://github.com/Code-Institute-Solutions/resume-miniproject-bootstrap4)

## Content

* The text for page 1 and 2 was copied from the [revisionmaths.com](https://revisionmaths.com/gcse-maths-revision/trigonometry/pythagorass-theorem
)

## Media
* Background image [pinterest.com](https://www.pinterest.com/pin/256071928790233645/);
* Pythagora's picture page 1 [classicalwisdom.com](https://classicalwisdom.com/philosophy/cult-of-pythagoras/);
* Triangel image page 1 [byjus.com](https://www.google.com/search?q=byjus+pythagoras+theorem&tbm=isch&ved=2ahUKEwjBi5mmo7zvAhXSsCoKHVSLBpsQ2-);
* Triangel image page 2 [revisionmaths.com](https://revisionmaths.com/gcse-maths-revision/trigonometry/pythagorass-theorem);
* Triangel image page 3 [istockphoto.com](https://www.istockphoto.com/se/vektor/pythagoras-sats-ikon-illustration-konst-gm654108570-119009899);
* Video page 2 [revisionmaths.com](https://revisionmaths.com/gcse-maths-revision/trigonometry/pythagorass-theorem)

## Acknowledgements
•	I received inspiration for this project from X

# Disclaimer
This site is made for educational purposes only.