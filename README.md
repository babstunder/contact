<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Contact Us</title>

  <link rel="stylesheet" href="css/bootstrap.css">
  <link rel="stylesheet" href="css/contact-us-desktop.css">
  <link rel="stylesheet" href="css/footer.css">
  <link rel="stylesheet" href="css/nav.css">
  <link href="https://fonts.googleapis.com/css2?family=DM+Sans:wght@500&display=swap" rel="stylesheet">
  <script src="https://kit.fontawesome.com/c5e8748bc2.js" crossorigin="anonymous"></script>

</head>
<nav class="navbar navbar-expand-sm bg-light fixed-top">
      <a class="navbar-brand" href="#">
        <img src="img/layer1.png" alt="image"
      /></a>
      <div class="menu-btn">
        <div class="menu-btn__burger"></div>
      </div>
      <div class="navbar-collapse navv" id="navbarResponsive">
        <ul class="navbar-nav ml-auto" id="ham">
          <li class="nav-item">
            <a class="nav-link" href="#home">LEND</a>
          </li>

          <li class="nav-item">
            <a class="nav-link" href="#course">BORROW</a>
          </li>

          <li class="nav-item">
            <a class="nav-link" href="#features">ABOUT</a>
          </li>

          <li class="nav-item">
            <button type="button" class="btn btn-danger nav-btn">Login</button>
          </li>
        </ul>
      </div>
    </nav>
<body class="contactFormBody">
  <div class="contactUsHeader d-flex justify-content-center">
    <div>
      <h1>Contact Us</h1><hr class="titleHr"/>
      <p>
        Feel free to contact us anytime we will get back <br />
        to you at soon as possible
      </p>
    </div>
  </div>
  <div class="contactUsContent d-flex justify-content-center">
    <div class="contactDetailsList">
      <div class="media bg-white mb-3 py-2 px-4 borderDesign">
        <span class="iconPack align-self-center mr-3"><i class="fas fa-phone-alt"></i></span>
        <div class="media-body">
          <h5 class="mt-0 mb-0">Phone Number</h5>
          <span class="lightColour">(+234) 81 770 47279</span> 
        </div>
      </div>
      <div class="media bg-white mb-3 py-2 px-4 borderDesign">
        <span class="iconPack align-self-center mr-3"><i class="fas fa-envelope"></i></span>
        <div class="media-body">
          <h5 class="mt-0 mb-0">Email Address</h5>
          <span class="lightColour">example@gmail.com</span>
        </div>
      </div>
      <div class="media bg-white mb-3 py-2 px-4 borderDesign">
        <span class="iconPack align-self-center mr-3"><i class="fas fa-map-marker-alt"></i></span>
        <div class="media-body">
          <h5 class="mt-0 mb-0">Location</h5>
          <span class="lightColour">Plot 1, Awolowo Way, Ikeja, Lagos</span>
        </div>
      </div>
      <div class="media bg-white mb-3 py-2 px-4 d-flex justify-content-between borderDesign">
        <span class="fbIconPack align-self-center"><i class="fab fa-facebook-f"></i></span>
        <span class="iconPack align-self-center"><i class="fab fa-instagram-square"></i></span>
        <span class="iconPack align-self-center"><i class="fab fa-twitter"></i></span>
        <span class="iconPack align-self-center"><i class="fab fa-linkedin-in"></i></span>
      </div>
    </div>
    <div class="contactUsForm bg-white borderDesign">
      <h5>Send a Message</h5>
      <p class="lightColour">Do you have anything you waant to tell us? Get in touch with us today</p>
      <form>
        <div class="form-row">
          <div class="form-group col-md-6">
            <label class="darkColour1">Full Name</label>
            <input type="text" class="form-control darkColour2" placeholder="Input full name" required>
            <p class="errorDisplayer"></p>
          </div>
          <div class="form-group col-md-6">
            <label class="darkColour1">Email Address</label>
            <input type="email" class="form-control darkColour2" placeholder="Input email address" required>
            <p class="errorDisplayer"></p>
          </div>
        </div>
        <div class="form-row">
          <div class="form-group col-md-6">
            <label class="darkColour1">Phone Number</label>
            <input type="tel" class="form-control darkColour2" placeholder="Input phone number" required>
            <p class="errorDisplayer"></p>
          </div>
          <div class="form-group col-md-6">
            <label class="darkColour1">Subject</label>
            <input type="text" class="form-control darkColour2" placeholder="Input subject" required>
            <p class="errorDisplayer"></p>
          </div>
        </div>
        <div class="form-group">
          <label for="exampleFormControlTextarea1" class="darkColour1">Message</label>
          <textarea class="form-control darkColour2" id="exampleFormControlTextarea1" rows="7"  placeholder="Input message" required></textarea>
          <p class="errorDisplayer"></p>
        </div>
        
        <div class="d-flex">
          <button type="submit" class="btn btn-danger contactValidBtn">Send Message</button>
        </div>
      </form>
    </div>
  </div>
  <footer class="footer">
      <div class="footer-li">
        <div class="left">
          <ul>
            <li><img src="img/Group 3005.png" alt="" /></li>
            <li>address</li>
            <li>email address</li>
            <li>phone</li>
          </ul>

          <div>
            <ul class="footer-icons">
              <li>
               <a href="#"><img src="img/Vector (1).png" alt="" /></a> 
              </li>
              <li ><a href="#"><img src="img/Vector (2).png" alt="" /></li></a>
              <li><a href="#"><img src="Vector (3).png" alt="" /></a></li>
            </ul>
          </div>
        </div>

        <div class="right">
          <ul>
            <h4>RESOURCES</h4>
            <li>Why choose FundMyLaptop</li>
            <li>How P2P Lending works</li>
            <li>About FundMyLaptop</li>
            <li>Contact Us</li>
          </ul>
        </div>
      </div>
      <div class="container mt-4 bottom">
        <p>2020 &copy; Copyright All Rights Reserved</p>

        <ul>
          <li>FAQ</li>
          <li>Privacy Policy</li>
          <li>Terms & Conditions</li>
        </ul>
      </div>
    </footer>
     <script src="js/jquery.js"></script>
    <script src="js/bootstrap.js"></script>
    <script src="js/popper.js"></script>
    <script src="js/navBar.js"></script>

    <script src="js/jquery.js"></script>
    <script src="js/bootstrap.js"></script>
    <script src="js/popper.js"></script>
  <script src="js/validateContactForm.js"></script>
</body>
</html>