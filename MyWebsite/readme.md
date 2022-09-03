======================================================================================
This will be where general notes on my website and the design process are located.
======================================================================================

======================
Resources
======================
- https://codepen.io/ollieRogers/pen/DPbRMz




======================
Skills developed
======================
- media manipulation
- javascript


=======================
Design Notes
=======================
- Obtained header font from googleapi
- used ionicons.io to source social media logos
- used adobe photoshop to make transparent background overlay


=======================
ADD LATER
=======================
- more supported video file types
- include source for the sticky code


========================
OLD CODE
========================


qq




    <nav>
    
      <label for="touch"><span><ion-icon name="reorder-three-sharp"></ion-icon></span></label>               
      <input type="checkbox" id="touch"> 
    
      <ul class="slide">
        <li><a href="#"><ion-icon name="logo-github"></ion-icon></a></li> 
        <li><a href="#"><ion-icon name="logo-linkedin"></ion-icon></a></li>
        <li><a href="#"><ion-icon name="logo-linkedin"></ion-icon></a></li>
        <li><a href="#"><ion-icon name="logo-instagram"></ion-icon></a></li>
      </ul>
    
    </nav> 






















<!DOCTYPE html>
<html>
    <head>
        <content="width=device-width, initial-scale=1">
        <link rel="preconnect" href="https://fonts.googleapis.com">
        <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
        <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@500&display=swap" rel="stylesheet">
        <link rel="stylesheet" href="mmarchettiStyle.css">
        <title>
            M Marchetti
        </title>
        <h1 class="headerCenter">
            Computer Science Student</br>
            Michael Marchetti
        </h1>
    </head>

    <body>
        <button class="button" onclick="darkMode()">Toggle dark mode</button>
        <script>
            function darkMode() {
                var element = document.body;
                element.classList.toggle("dark-mode");
            }
        </script>
        <p class="paragraph1">
            Welcome to my page under development! Please reach out to me using my socials here!
        </p>

    </body>
</html>




h1.headerCenter{
    text-align: left;
    color:#444444;
    font-family: 'Montserrat', sans-serif;
    font-size: xx-large;
}
/* button stuff*/
    .button {
        background-color: #DA0037;
        border: none;
        color: #EDEDED;
        padding: 15px 32px;
        text-align: center;
        text-decoration: none;
        display: inline-block;
        font-size: 16px;
    }

    .button:hover {
        background-color: #da003794;
        transition: background-color .2s;
    }

    body {
        padding: 25px;
        background-color: #EDEDED;
        color: #EDEDED;
        font-size: 25px;
    }
    
    .dark-mode {
        background-color: #171717;
        color: #EDEDED;
    }

.paragraph1{
    text-align: center;
    color: #444444;
    font-size: large;
    font-family: 'Courier New', Courier, monospace;
}

img.spotify{
    filter: invert(91%);
    display: block;
    margin-left: auto;
    margin-right: auto;
    border-radius: 40px;
}

h3.headerCenter{
    text-align: center;
    color:chartreuse;
    font-family: 'Courier New', Courier, monospace;
}


.bubble{
    display: block;
    margin: 0 auto;
    width: auto;
    border: 8px solid #171717;
    border-radius: 5px;
    background-color:#171717;
    justify-content: center;
}

.tablecenter{
    text-align: center;
    color:chartreuse;
    font-size: large;
    font-family: 'Courier New', Courier, monospace;
    margin-left: auto;
    margin-right: auto;
}
