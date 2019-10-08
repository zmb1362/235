Stylesheet.css

* {
    font-family: Arial, sans-serif;
}
body {
  background-color: #E3E7D3;
  margin: 0;
}

/* Nav Bar */
nav ul {
  list-style: none;
  margin: 0;
  padding: 0;
  display: flex;
  flex-wrap: wrap;
  background-color: #090909;
}

nav li {
  display: block; /* May not need? */
  font-size: 30px;
  padding: 10px;
  padding-top: 25px;
  padding-bottom: 25px;
  color: inherit;
  text-decoration: none;
}

nav a {
  color: #CFE8EF;
  text-decoration: none;
}

nav li:hover {
  background-color: #694D75;
  transition: background-color 0.1s ease-in;
}

.active {
  color: #090909;
  background-color: #CFE8EF;
}

.active:hover {
  background-color: #CFE8EF;
}

/* Main Layout Design */

.logopic {
  display: block;
  margin-left: auto;
  margin-right: auto;
}

.container {
  position: relative;
  min-height: 100%;
}

.main {
  background-color: #BDC2BF;
  margin-top: 1rem;
  margin-left: 5rem;
  margin-right: 5rem;
  padding-bottom: 4.5rem;
}

main p {
  text-align: center;
  margin-top: 1em;
  margin-bottom: 1em;
  margin-left: 5em;
  margin-right: 5em;
}

main h1 {
  text-align: center;
  color: #504746;
}

main h2 {
  text-align: center;
  color: #504746;
}

main h3 {
  text-align: center;
  color: #504746;
}

#space {
  padding-top: 20rem;
  padding-bottom: 20rem;
}

.pic {
  display: block;
  margin-left: auto;
  margin-right: auto;
  margin-top: 1em;
  margin-bottom: 1em;
}

a {
  text-decoration: none;
  color: #090909;
}

/* Footer */
footer {
  background-color: #090909;
  position: absolute;
  bottom: 0;
  width: 100%;
  height: 3.5rem;
  margin-bottom: 0;
  margin-top: 1em;
}

footer p {
  font-size: 16px;
  text-align: center;
  color: #CFE8EF;
}

index.html

<!DOCTYPE html>
<html lang="en" dir="ltr">
  <head>
    <meta charset="utf-8">
    <link rel = "stylesheet" type = "text/css" href = "css/stylesheet.css"/>
    <title>Streets</title>
  </head>
  <body>
    <div class="container">
    <nav>
      <ul>
        <a href="#"><li class="active">Home</li></a>
        <a href="proposal.html"><li>About</li></a>
        <a href="documentation.html"><li>Documentation</li></a>
        <a href="project.html"><li>Play</li></a>
      </ul>
    </nav>

    <main>
        <div class="main">
          <img class="logopic" src="media/logo.jpg" alt="Logo">
          <h1>Air Head</h1>
          <hr>
            <p>
              Come try out this addictive 2D Vertical Sidescroller. Air Head is a funny looking, cartoonish game, similar to Flappy Bird! <br>
              Fly through the skies and avoid any birds or planes as you try to achieve the best highscore!
            </p>
        </div>
    </main>

    <footer>
      <p>Copyright Zachary Blair 2019</p>
    </footer>

    </div>
  </body>
</html>

proposal.html

<!DOCTYPE html>
<html lang="en" dir="ltr">
  <head>
    <meta charset="utf-8">
    <link rel = "stylesheet" type = "text/css" href = "css/stylesheet.css"/>
    <title>Streets</title>
  </head>
  <body>
    <div class="container">
    <nav>
      <ul>
        <a href="index.html"><li>Home</li></a>
        <a href="#"><li class="active">About</li></a>
        <a href="documentation.html"><li>Documentation</li></a>
        <a href="project.html"><li>Play</li></a>
      </ul>
    </nav>

    <main>
        <div class="main">
          <hr>
          <h1>Concept</h1>
            <p>Air Head is a simple 2D clicking game in which you must avoid objects in the sky as you continue floating upwards.</p>
          <hr>
          <h1>Genre</h1>
            <p>2D vertical sidescrolling game</p>
          <hr>
          <h1>Platform</h1>
            <p>Air Head will be a web based game available on all devices</p>
          <hr>
          <h1>Esthetics</h1>
            <p>Air Head features a cartoonish style with an ambient sound</p>
          <hr>
          <h1>Gameplay</h1>
            <h2>Controls</h2>
              <p>Clicking the lower half of the phone or screen will send the player downwards, you can hold it to keep it down on the lower part of the screen</p>
            <h2>Gameplay</h2>
              <h3>Goal</h3>
                <p>The goal of the game is to achieve a highscore. It is an infinite game.</p>
              <h3>Powerups</h3>
                <p>There are several powerups in the game: <br> Invincible: The player is unable to die for so many seconds while this powerup is active <br>
                   Small Head: The player gets a smaller head for a few seconds so that it is easier to dodge the objects. <br> Bigger Head: Acting as more of a
                   debuff, the player's head gets larger making it easier to hit objects flying around.
                </p>
          <hr>
          <h1>Screenshot Examples</h1>
            <img class="pic" src="media/airheadinfo.png" alt="AirHeadExample">
            <img class="pic" src="media/roguelogo.jpg" alt="Streets of Rogue">
        </div>
    </main>

    <footer>
      <p>Copyright Zachary Blair 2019</p>
    </footer>
    </div>
  </body>
</html>

documentation.html

<!DOCTYPE html>
<html lang="en" dir="ltr">
  <head>
    <meta charset="utf-8">
    <link rel = "stylesheet" type = "text/css" href = "css/stylesheet.css"/>
    <title>Streets</title>
  </head>
  <body>
    <div class="container">
    <nav>
      <ul>
        <a href="index.html"><li>Home</li></a>
        <a href="proposal.html"><li>About</li></a>
        <a href="#"><li class="active">Documentation</li></a>
        <a href="project.html"><li>Play</li></a>
      </ul>
    </nav>

    <main>
      <div class="main">
        <hr>
        <h1>Documentation</h1>
          <p>
            Many resources were used for this website, and some references to help set up the theme and design of the game. <br>
            W3 Schools helped a lot when it game to setting up the navigation bar as well as the overall layout of the web pages. <br>
          </p>
          <h2>Steps Taken</h2>
          <p>
            I first worked on the webpage itself, setting up the basics for the navigation bar and trying to structure the overall design of the website. <br>
            After this I took more of a focus towards the Game idea that I had. <br>
            I thought out the overall design and idea around it and proceeded to make the logo and a reference image. <br>
            After that was finished I added in all of the information that I typed out and included all of the reference images that inspired me.
          </p>
          <h2>About the Reference Images</h2>
          <p>
            I was inspired by Streets of Rogue and Flappy Bird. <br>
            Streets of Rogue inspired me on the 8Bit, but even more cartoonish style that it has for the game <br>
            The music and sounds that it has is definitely a good example for what I intend to have in Air Head. <br>
            Flappy Bird's overall style of infinitely navigating through a horizontal sidescroller is an easy reference <br>
            for how I imagine my game to be set up. The clicking is also an easy way to see how I somewhat intend the controls to be.
          </p>
        <hr>
        <h1>Sources</h1>
          <p>
              <a href="https://www.w3schools.com">W3 Schools</a> <br><br>
              <a href="https://streetsofrogue.com">Streets of Rogue</a> <br><br>
              <a href="https://flappybird.io">Flappy Bird</a>
          </p>
        <hr>
        <h1>Reference Images</h1>
          <img class="pic" src="media/rogueex.jpg" alt="StreetsOfRogue">
          <img class="pic" src="media/flappybird.jpg" alt="FlappyBird">
      </div>
    </main>

    <footer>
      <p>Copyright Zachary Blair 2019</p>
    </footer>
  </div>
  </body>
</html>

project.html

<!DOCTYPE html>
<html lang="en" dir="ltr">
  <head>
    <meta charset="utf-8">
    <link rel = "stylesheet" type = "text/css" href = "css/stylesheet.css"/>
    <title>Streets</title>
  </head>
  <body>
    <div class="container">
    <nav>
      <ul>
        <a href="index.html"><li>Home</li></a>
        <a href="proposal.html"><li>About</li></a>
        <a href="documentation.html"><li>Documentation</li></a>
        <a href="#"><li class="active">Play</li></a>
      </ul>
    </nav>

    <main>
      <div class="content">
        <section>
          <div class="main">
            <h1>PLAY THE PROJECT</h1>
            <p id="space">



            </p>
          </div>
        </section>
        </div>
    </main>

    <footer>
      <p>Copyright Zachary Blair 2019</p>
    </footer>
  </div>
  </body>
</html>
