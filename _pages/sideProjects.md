---
layout: page
main: false
title: Side Projects
permalink: /sideProjects/
---

<div class="side-projects">
    <div class="Cave-Fighter">
        <div class="container">
            <div class="header">
                <h3>Cave Fighter - Game</h3>
                <div class="icons">
                    <i class="devicon-java-plain-wordmark"></i>
                </div>
            </div>
        </div>
        <div class="container">
            <div class="row">
                <div class = "col-md-4">
                    <img src="../images/screenshot.jpg" height="300px" width="325px">
                </div>
                <div class = "col-md-8">
                    <p>Cave Fighter is a Java based game programmed utilizing the applet methods and many object oriented techniques. The game is based on Edmund McMillen’s and Florian Himsl’s, "The Binding of Isaac". The game uses a chunking algorithm to procedurally generate room layouts and fills them with random enemies in one of many predetermined patterns. This project uses abstraction when declaring things like power ups, enemies and bosses. Polymorphism is used when these classes need specialized actions for generic method calls, examples being the move and attack functionalities. These classes also used encapsulation to hide their information from the user and other classes within the project. The objective of the game is to fight through rooms until you reach the boss room. When the boss is defeated the game resets. The game states are handled with the use of enumeration. The repository for the game is located <a href="https://github.com/ryannewman2828/Cave-Fighter" target="_blank">here</a>.</p>
                </div>
            </div> 
        </div>
    </div>
    <div class="exodius-arena">
        <div class="container">
            <div class="header">
                <h3>Exodius Arena (Work in progress)</h3>
                <div class="icons">
                    <i class="devicon-angularjs-plain"></i>
                    <i class="devicon-bootstrap-plain-wordmark"></i>
                    <i class="devicon-css3-plain-wordmark"></i>
                    <i class="devicon-gulp-plain"></i>
                    <i class="devicon-html5-plain-wordmark"></i>
                    <i class="devicon-javascript-plain"></i>
                    <i class="devicon-jquery-plain-wordmark"></i>
                    <i class="devicon-mongodb-plain-wordmark"></i>
                    <i class="devicon-nodejs-plain"></i>
                    <i class="devicon-sass-original"></i>
                </div>
            </div>
        </div>
        <div class="container">
            <p>Exodius Arena is a web application that allows people to register accounts, login, add friends, send messages, make progress to unlocking characters and using those characters in a single player arena style game. This application makes use of the MEAN stack for its web technology needs. Bootstrap and JQuery are used to handle the animations/dynamic scalabilities of the project. Gulp is used as the file runner for compiling, concatinating and minifying files together. SASS is used as the CSS framework for improved styling. Jasmine is used to unit test the functionality of the server while Protractor is used for the e2e testing of the site. The repository for this project is located <a href="https://github.com/ryannewman2828/Exodius-Arena" target="_blank">here</a>. This project is a work in progress as the actual game element has not yet been implemented, but is planned to be with the use of websockets to support real time communication between the client and the server.</p>
        </div>
    </div>
    <div class="UWEvents">
        <div class="container">
            <div class="header">
                <h3>UW Events</h3>
                <div class="icons">
                    <i class="devicon-amazonwebservices-original"></i>
                    <i class="devicon-bootstrap-plain-wordmark"></i>
                    <i class="devicon-css3-plain-wordmark"></i>
                    <i class="devicon-html5-plain-wordmark"></i>
                    <i class="devicon-github-plain-wordmark"></i>
                    <i class="devicon-javascript-plain"></i>
                    <i class="devicon-jquery-plain-wordmark"></i>
                    <i class="devicon-mysql-plain-wordmark"></i>
                    <i class="devicon-php-plain"></i>
                    <i class="devicon-python-plain-wordmark"></i>
                </div>
            </div>
        </div>
        <div class="container">
            <p>The main purpose of the UW Events App was to inform students about events that are often ignored. To accomplish this, we built a centralized hub where event information is located. Students can find information about event locations and receive email reminders to attend. All event information, employer sessions, workshops, entertainment and more, is available on the site. The site pulled information about these events from RSS' feeds from multiple sites then used php to dynamically display them on the page. We registered users and stored their information in a database and used mySQL to retrieve it then we sent reminder emails to the users using a python framework. The information was stored in an Amazon web services server. For the front-end of the site HMTL 5, CSS 3, Bootstrap, jQuery and JavaScript was used to style the webpage, add animations/effects and dynamic scalability. Github was used as the version control and to allow everyone to contribute to the project. My personal responsibility for this project was being in charge of the front end. I found a starter template and did all of the styling, animating and scaling for the web application. The website can be found at <a href="http://uwevents.gq" target="_blank">uwevents.gq</a> and the repository for the website is located <a href="https://github.com/jondonas/uw-events" target="_blank">here</a>.</p>
            <p><i class="fa fa-users"></i> Jonathan Donas, Rolina Wu, Neo Chen and Wang Yang</p>
        </div>
    </div>
    <div class="Website">
        <div class="container">
            <div class="header">
                <h3>Personal Website</h3>
                <div class="icons">
                    <i class="devicon-bootstrap-plain-wordmark"></i>
                    <i class="devicon-css3-plain-wordmark"></i>
                    <i class="devicon-html5-plain-wordmark"></i>
                    <i class="devicon-javascript-plain"></i>
                    <i class="devicon-jquery-plain-wordmark"></i>
                    <i class="devicon-sass-original"></i>
                </div>
            </div>
        </div>
        <div class="container">
            <p>I personally designed this website from scratch. I used HTML 5 to arrange and produce the content on this website. I wrote all the styling for this website in Sass, which was compiled down to CSS 3. Using the Bootstrap framework I was able add dynamic scalability to the website meaning the website will automatically adapt to different sized browsers and devices. JavaScript along with jQuery were used to allow the skills in the skills tab to be loaded/unloaded on button pushes. It also has effects thanks to the jQuery animation interface.</p>
        </div>
    </div>
    <div class="P-T-G">
        <div class="container">
            <div class="header">
                <h3>Procedural Terrain Generator</h3>
                <div class="icons">
                    <i class="devicon-java-plain-wordmark"></i>
                </div>
            </div>
        </div>
        <div class="container">
            <p>The Procedural Terrain Generator is a program that generates randomized two dimensional terrain. It accomplishes this by using a fractal algorithm to break apart a line segment into two to the power of n - 1, where n is the amount of performed iterations. The repository for this project is located <a href="https://github.com/ryannewman2828/Procedural-Terrain-Generator" target="_blank">here</a>.</p>
        </div>
    </div>
    <div class="GradeBook">
        <div class="container">
            <div class="header">
                <h3>GradeBook</h3>
                <div class="icons">
                    <i class="devicon-android-plain-wordmark"></i>
                    <i class="devicon-java-plain-wordmark"></i>
                </div>
            </div>
        </div>
        <div class="container">
            <p>GradeBook is an android application I programmed in Android Studio to keep a record of a student's assignments and grades as well as calculating their term and class averages. This project records the information you enter into the text boxes as a string with identifiers within it. The storage/retrieval of the user's data is done through the use of modularization. The repository for this project is located <a href="https://github.com/ryannewman2828/GradeBook" target="_blank">here</a>.</p>
        </div>
    </div>
</div>