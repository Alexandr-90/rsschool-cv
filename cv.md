# Aleksandr Tarasov #

Contact Info
* _github:_  @Alexandr-90
* _e-mail:_ tarasov.alexander.v@gmail.com


## Junior FrontEnd Developer ##

* Able to build a Web presence from the ground up -- from concept, navigation, layout and programming to UX and SEO.
* Skilled at writing well-designed, testable and efficient code using current best practices in Web development.
* Fast learner, hard worker and team player who is proficient in an array of scripting languages and multimedia Web tools


### Technical Toolbox ###

**Web Tools**: JavaScript, CSS, HTML, XHTML, XML, C#, Python,  Git

**Graphic Design**: Photoshop, Lightroom, Pixelmator

### Code example of web site ###


**HTML**
```html
 <!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <meta http-equiv="X-UA-Compatible" content="ie=edge">
        <title>Blow</title>
        <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/meyer-reset/2.0/reset.css"> 
        <link href="https://fonts.googleapis.com/css?family=Montserrat:400,700,900&display=swap" rel="stylesheet">
        <link rel="stylesheet" href="style.css">
    </head>
    <body>
        <div class="wrapper">
            <header class="header">
                <div class="logo">blow</div>
                <nav class="navbar">
                    <ul>
                        <li>
                            <a href="#">home</a>
                        </li>
                        <li>
                            <a href="#">about</a>
                        </li>
                        <li>
                            <a href="#">work</a>
                        </li>
                        <li>
                            <a href="#">contact</a>
                        </li>
                    </ul>
                </nav>
            </header>
            <div class="explore">
                <button>Explore work</button>
            </div>
        </div>
        <aside class="sidebar">
            <p>get in touch have project in mind </p>
            <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 542 538" width="542" height="538">
                <defs>
                    <image width="86" height="76" id="img1" href="data:image/svg+xml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiBlbmNvZGluZz0iVVRGLTgiPz4KPHN2ZyB3aWR0aD0iMTAwcHQiIGhlaWdodD0iMTAwcHQiIHZlcnNpb249IjEuMSIgdmlld0JveD0iMCAwIDEwMCAxMDAiIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyI+CiA8cGF0aCBkPSJtNTguODcxIDU2LjYxN2gzMS4wMzl2MjcuNjMzYzAgMS45NDkyLTEuNTgyIDMuNTI3My0zLjUyNzMgMy41MjczaC03Mi43NjZjLTEuOTQ5MiAwLTMuNTI3My0xLjU4Mi0zLjUyNzMtMy41Mjczdi0yNy42MzNoMzEuMjU0djAuODk4NDRoMS4xNjAydjcuMzMyYzAgMS45NDkyIDEuNTc4MSAzLjUyNzMgMy41MjczIDMuNTI3M2g3LjkzNzVjMS45NDkyIDAgMy41MjczLTEuNTgyIDMuNTI3My0zLjUyNzN2LTcuMzMyaDEuMzc1em0zMy4yNDYtMjguODE2djIxLjYwOWMwIDEuOTQ5Mi0xLjU4MiAzLjUyNzMtMy41MjczIDMuNTI3M2gtNzcuMTc2Yy0xLjk0OTIgMC0zLjUyNzMtMS41ODItMy41MjczLTMuNTI3M3YtMjEuNjA5YzAtMS45NDkyIDEuNTgyLTMuNTI3MyAzLjUyNzMtMy41MjczaDIzLjgwOXYtNi45Mzc1YzAtMi44MjQyIDIuMjg5MS01LjExMzMgNS4xMTcyLTUuMTEzM2gxOS4zMjRjMi44MjQyIDAgNS4xMTcyIDIuMjg5MSA1LjExNzIgNS4xMTMzdjYuOTQxNGgyMy44MDljMS45NDUzLTAuMDAzOTA2IDMuNTI3MyAxLjU3NDIgMy41MjczIDMuNTIzNHptLTM0LjM5NS04LjUyMzRoLTE1LjQ0NXY0Ljk5NjFoMTUuNDQ1eiIvPgo8L3N2Zz4K"/>
                </defs>
                <style>
                    tspan { white-space:pre }
                </style>
                <g id="Page">
                    <g id="get in toch">
                        <use id="np_briefcase_907576_000000" style="opacity: 0.302" href="#img1" transform="matrix(0.46,0,0,0.46,248,136)"/>
                    </g>
                </g>
            </svg>
        </aside>
    </body>
</html>
```

**CSS**
```css
.wrapper {
    height: 100vh;
    width: 93.75%;
    background: url(./assets/images/Group\ 1.png);
    background-size: cover;
    margin-left: 6.25%;
}

.header {
    height: 120px;
    display: flex;
    justify-content: space-between;
}

.logo {
    font-size: 40px;
    line-height: 30px;
    color: #000000;
    font-family: "Montserrat";
    font-weight: 900;
    margin: 30px 0 0 30px;
}

.navbar {
    width: 480px;
    margin: 30px 30px 0 0;
}

.navbar ul {
    display: flex;
    
    justify-content: space-between;
}

.navbar ul li a {
    display: flex;
    width: 100px;
    height: 41px;
    border-radius: 20px;
    color:  #000000;
    text-decoration: none;
    align-items: center;
    justify-content: center;
    font-family: "Montserrat";
}

.navbar ul li a:hover {
    background-color: #000000;
    color: white;
}

.explore {
    margin: 450px auto 0;
    width: fit-content;
    border: none;
    box-shadow: 0px 85px 62px 29px rgba(0,0,0,0.86);
}

.explore button {
    width: 300px;
    height: 60px;
    border-radius: 30px;
    background-color: #000000;
    color: white;
    font-family: "Montserrat";
    text-transform: uppercase;
}

.sidebar {
    width: 6.25%;

    position: fixed;
    left: 0;
    top: 0;
    height: 100vh;
    display: flex;
    flex-direction: column;
    justify-content: space-between;
}

.sidebar p {
    transform: rotate( -90deg);
    width: 500px;
    margin-left: -222px;
    font-family: "Montserrat";
    margin-top: 268px;

}

@media (max-width: 800px) {
    .sidebar {
        display: none;
    }

    .wrapper {
        margin: 0;
        width: 100vw;
    }
}
```

### Soft Skills ###

**Previous job experience**: 3 years of team management (8-10 people), huge experience in process optimization, successful teamwork, quick adaptation to changes and self-learning, documentation, business correspondence in English by mail

### Experience ###

Made projects as FrontEnd developer in HTML and CSS courses
Currently working on a project with javascript in Frontend courses

## Education ##

**High Education:**

*University:* Moscow State Industrial University (MSIU)

*Department:* Economics, Management and Information Technology

*Specialization:* Organization and technology of information security

**Additional Education**

 *Course:* | *Education:*
------------ | -------------
CS50 | Programming Basics
Testing . com | QA Basics
Learn HTML | HTML Basics
Learn CSS | CSS Basics
Git | *in Progress*
Learn JavaScript | *in Progress*
Rolling Scopes School | *in Progress*


## English ##

* Studied English in Trinity College, graduated with Advanced level
* Studied English in Pimsler's corses and Effortless english corse by A. J. Hoge, to improve english speaking skills
* Practiced speaking skills while traveling abroad
* Business correspondence in English by e-mail with colleagues on previous job