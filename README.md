<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>My Portfolio</title>
    <link rel="stylesheet" href="Style.css" />
    <link rel="stylesheet" href="321.otf" />
    <link rel="stylesheet" href="41.ttf">
  </head>
  <body>
    <header>
      <nav>
        <div class="left">Ana's Portfolio</div>
        <div class="right">
          <ul>
            <li><a href="/">Home</a></li>
            <li><a href="/">About</a></li>
            <li><a href="/">Services</a></li>
            <li><a href="/">Projects</a></li>
            <li><a href="/">Contact Me</a></li>
          </ul>
        </div>
      </nav>
    </header>
  </body>
  <main>
    <section class="firstsection">
      <div class="leftsection">
        Hi, My name <span class="purple">Anas</span>
        <div>I'm expertise of</div>
        <span id="element"></span>
        <hr />
        <div class="One">
          <p>
            "I am a creative and collaborative thinker who is always looking for
            new ways to improve my designs. I am also a great communicator who
            is able to work effectively with clients to understand their needs
            and create designs that meet their expectationss."
          </p>
        </div>
        <hr />
        <section class="secondsection">
          <span class="text-gray">I have done this</span>
          <h1>My Experience</h1>
          <div class="box">
            <div class="vertical"></div>
            <div class="vertical"></div>
            <div class="vertical"></div>
            <div class="vertical"></div>
          </div>
        </section>
      </div>
      <div class="rightsection">
        <img src="11.png" alt="" />
      </div>
    </section>
  </main>
  <script src="https://unpkg.com/typed.js@2.0.16/dist/typed.umd.js"></script>
  <script>
    var typed = new Typed("#element", {
      strings: ["Graphic Designer", "Vidoe Editor", "Web Developer"],
      typeSpeed: 50,
    });
  </script>
  <body></body>
</html>
