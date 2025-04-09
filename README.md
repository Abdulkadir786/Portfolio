  <!DOCTYPE html>
  <html lang="en">
  <head>
    <title>Bootstrap Example</title>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
  </head>

  <style>
    .row {
    margin-left: 0;
    margin-right: 0;
    }
  </style>

  <body data-bs-spy="scroll" data-bs-target=".navbar" data-bs-offset="100">
<div class="container">
    <div class="row" style="padding-top: 30vh; padding-bottom: 30vh;" id="home">
      <p class="display-1" style="text-align: center;">Jasdanwala Abdulkadir</p>
    </div>
</div>

    <div class="row">
      <div class="col-xll-12" style="text-align: center;">
        <button class="btn btn-outline-primary" style="padding-inline: 50px; padding-top: 10px; padding-bottom: 10px; margin-bottom: 10%;">Resume</button>
      </div>
    </div>

    <ul class="nav justify-content-center bg-dark sticky-top" style="margin-bottom: 5vh;">
      <li class="nav-item">
        <a class="nav-link" href="#home" style="color: white;">Home</a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#" style="color: white;">Resume</a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#projects" style="color: white;">Projects</a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#languages" style="color: white;">Language's</a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#about-me" style="color: white;">About-me</a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#contact-me" style="color: white;">Contact-me</a>
      </li>
    </ul> 


    <p class="display-6 mt-4" style="padding-left: 3rem;" id="projects">Projects</p>
    <div class="row">
      <div class="col">
            <!-- Carousel -->
        <div id="demo" class="carousel slide" data-bs-ride="carousel">

          <!-- Indicators/dots -->
          <div class="carousel-indicators">
            <button type="button" data-bs-target="#demo" data-bs-slide-to="0" class="active"></button>
            <button type="button" data-bs-target="#demo" data-bs-slide-to="1"></button>
            <button type="button" data-bs-target="#demo" data-bs-slide-to="2"></button>
          </div>

          <!-- The slideshow/carousel -->
          <div class="carousel-inner">
            <div class="carousel-item active">
              <img src="https://images.pexels.com/photos/459225/pexels-photo-459225.jpeg?cs=srgb&dl=daylight-environment-forest-459225.jpg&fm=jpg" alt="Los Angeles" class="d-block w-100" id="carousel">
            </div>
            <div class="carousel-item">
              <img src="https://jooinn.com/images/lonely-tree-reflection-3.jpg" alt="Chicago" class="d-block w-100" id="carousel">
            </div>
            <div class="carousel-item">
              <img src="https://th.bing.com/th/id/R.13820971a962ffbeb63a8fef36185b16?rik=vZ3lu%2blbhy6jxw&riu=http%3a%2f%2fwallup.net%2fwp-content%2fuploads%2f2016%2f03%2f10%2f319576-photography-landscape-nature-water-grass-trees-plants-sunrise-lake.jpg&ehk=6WS2p9KknQa9F%2bgAH16n44NReuUyS2rzXah2zy7kiAw%3d&risl=&pid=ImgRaw&r=0" alt="New York" class="d-block w-100" id="carousel">
            </div>
          </div>

          <!-- Left and right controls/icons -->
          <button class="carousel-control-prev" type="button" data-bs-target="#demo" data-bs-slide="prev">
            <span class="carousel-control-prev-icon"></span>
          </button>
          <button class="carousel-control-next" type="button" data-bs-target="#demo" data-bs-slide="next">
            <span class="carousel-control-next-icon"></span>
          </button>
      </div>
      </div>
    </div>
    
    <br>

    <!--Language Progress Bar-->
    <div class="mt-4 p-5 bg-white" id="languages">
      <p class="display-6">Language's</p>
      <div class="row justify-content-left" style="margin-left: 1vw; margin-right: 1vw;">
        <div class="col-sm-3" style="font-size: 1.2em; text-align: left; margin-bottom: 10px;">Html/CSS/JS</div>
        <div class="col-sm-7">
          <div class="progress" style="height: 3vh;">
            <div class="progress-bar bg-primary" style="width: 70%;"></div>
          </div>
        </div>
      </div>

      <div class="row justify-content-left" style="margin-left: 1vw; margin-right: 1vw;">
        <div class="col-sm-3" style="font-size: 1.2em; text-align: left; margin-bottom: 10px;">C</div>
        <div class="col-sm-7">
          <div class="progress" style="height: 3vh;">
            <div class="progress-bar bg-primary" style="width: 80%;"></div>
          </div>
        </div>
      </div>
    
      <div class="row justify-content-left" style="margin-left: 1vw; margin-right: 1vw;">
        <div class="col-sm-3" style="font-size: 1.2em; text-align: left; margin-bottom: 10px;">Python</div>
        <div class="col-sm-7">
          <div class="progress" style="height: 3vh;">
            <div class="progress-bar bg-primary" style="width: 90%;"></div>
          </div>
        </div>
      </div>
    </div>
    
    <!--Frameworks Progress Bar-->
    <div class="mt-4 p-5 bg-white" id="Frameworks">
      <p class="display-6">Frameworks</p>
      <div class="row justify-content-left" style="margin-left: 1vw; margin-right: 1vw;">
        <div class="col-sm-3" style="font-size: 1.2em; text-align: left; margin-bottom: 10px;">React Native</div>
        <div class="col-sm-7">
          <div class="progress" style="height: 3vh;">
            <div class="progress-bar bg-primary" style="width: 10%;"></div>
          </div>
        </div>
      </div>

      <div class="row justify-content-left" style="margin-left: 1vw; margin-right: 1vw;">
        <div class="col-sm-3" style="font-size: 1.2em; text-align: left; margin-bottom: 10px;">Bootstrap 5</div>
        <div class="col-sm-7">
          <div class="progress" style="height: 3vh;">
            <div class="progress-bar bg-primary" style="width: 60%;"></div>
          </div>
        </div>
      </div>
    </div>
    
  
 <!-- Footer -->
<div class="bg-dark text-white w-100" id="contact-me">
  <div class="container-fluid py-5">
    
    <!-- Header Section -->
    <div class="row mb-4"> 
      <div class="col-md-5">
        <p class="display-6">Contact Me</p>
        <p>+91 81288 83152</p>
        <p>abdulkadirjasdan@gmail.com</p>
      </div>
      <div class="col-md-7">
        <p class="display-6">Get in touch with me</p>

        <!-- Contact Form -->
        <form>
          <div class="mb-3">
            <input type="text" class="form-control" placeholder="Enter your name" required>
          </div>
          <div class="mb-3">
            <input type="text" class="form-control" placeholder="Email" required>
          </div>
          <div class="mb-3">
            <textarea class="form-control" placeholder="Message" rows="4" required></textarea>
          </div>
          <button type="submit" class="btn btn-primary">Send Message</button>
        </form>
      </div>
    </div>

    <!--Social Media-->
  <div class="bg-dark text-white w-100" id="social-media">
        <div class="col-12" style="text-align: center;">
          <a href="#" style="color: white; margin-right: 20px;">LinkedIn</a>
          <a href="#" style="color: white; margin-right: 20px;">GitHub</a>
          <a href="#" style="color: white;">Twitter</a>
      </div>
  </div>

  </div>
</div>


  

  </body>
  </html> 
