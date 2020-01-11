<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>Bootstrap - Prebuilt Layout</title>

    <!-- Bootstrap -->
    <link href="css/bootstrap-4.0.0.css" rel="stylesheet">
    <link href="style.css" rel="stylesheet" type="text/css">
  </head>
  <body>
  <nav class="navbar navbar-expand-lg navbar-light bg-light"> <a class="navbar-brand" href="#"><img src="img/logo.png" width="200" height="27"></a>
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent1" aria-controls="navbarSupportedContent1" aria-expanded="false" aria-label="Toggle navigation"> <span class="navbar-toggler-icon"></span> </button>
    <div class="collapse navbar-collapse" id="navbarSupportedContent1">
      <ul class="navbar-nav mr-auto">
        <li class="nav-item active"> <a class="nav-link" href="#">Home <span class="sr-only">(current)</span></a> </li>
        <li class="nav-item active"> <a class="nav-link" href="#">Link</a> </li>
        <li class="nav-item dropdown active"> <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown1" role="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="true"> Dropdown </a>
          <div class="dropdown-menu" aria-labelledby="navbarDropdown1"> 
			  <a class="dropdown-item" href="#">ENTER 1</a> 
			   <div class="dropdown-divider"></div>
		    <a class="dropdown-item" href="#">ENTER 2</a>
            <div class="dropdown-divider"></div>
            <a class="dropdown-item" href="#">ENTER 3</a> </div>
        </li>
        <li class="nav-item active"> <a class="nav-link disabled" href="#">Disabled</a> </li>
      </ul>
      <form class="form-inline my-2 my-lg-0">
        <input class="form-control mr-sm-2" type="search" placeholder="Search" aria-label="Search">
        <button class="btn btn-outline-success my-2 my-sm-0" type="submit">Search</button>
      </form>
    </div>
  </nav>
<div id="carouselExampleIndicators1" class="carousel slide offset-xl-0 col-xl-12" data-ride="carousel" style="">
  <ol class="carousel-indicators">
    <li data-target="#carouselExampleIndicators1" data-slide-to="0" class="active"></li>
      <li data-target="#carouselExampleIndicators1" data-slide-to="1"></li>
  </ol>
    <div class="carousel-inner" role="listbox">
      <div class="carousel-item active"> <img class="d-block mx-auto" src="https://i.imgur.com/qXy3jby.png" alt="First slide" width="1615" height="471">
        <div class="carousel-caption"> </div>
      </div>
      <div class="carousel-item"> <img class="d-block mx-auto" src="https://i.imgur.com/UicOhvL.png" alt="Second slide" width="1615" height="471">
        <div class="carousel-caption"> </div>
      </div>
    </div>
  <a class="carousel-control-prev" href="#carouselExampleIndicators1" role="button" data-slide="prev"> <span class="carousel-control-prev-icon" aria-hidden="true"></span> <span class="sr-only">Previous</span></a> <a class="carousel-control-next" href="#carouselExampleIndicators1" role="button" data-slide="next"> <span class="carousel-control-next-icon" aria-hidden="true">d</span> <span class="sr-only">Next</span></a></div>
  <script src="js/jquery-3.2.1.min.js"></script>
  <script src="js/popper.min.js"></script>
  <script src="js/bootstrap-4.0.0.js"></script>
  <div class="row">
    <div class="offset-xl-1 col-xl-3">
      <div class="card col-md-4 offset-xl-1 col-xl-11"> <img class="card-img-top" src="img/45ec9c85-38ac-4596-abda-7da148c84dea.jpg" alt="Card image cap">
        <div class="card-body">
          <h5 class="card-title">item 1</h5>
          <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
          <a href="#" class="btn btn-primary">Go somewhere</a> </div>
      </div>
    </div>
    <div class="offset-xl-0 col-xl-4">
      <div class="card col-md-4 col-xl-8 offset-xl-2"> <img class="card-img-top" src="img/45ec9c85-38ac-4596-abda-7da148c84dea.jpg" alt="Card image cap">
        <div class="card-body">
          <h5 class="card-title">item 2</h5>
          <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
          <a href="#" class="btn btn-primary">Go somewhere</a> </div>
      </div>
    </div>
    <div class="col-xl-3">
      <div class="card col-md-4 col-lg-5 offset-xl-0 col-xl-11"> <img class="card-img-top" src="img/45ec9c85-38ac-4596-abda-7da148c84dea.jpg" alt="Card image cap">
        <div class="card-body">
          <h5 class="card-title">item 3</h5>
          <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
          <a href="#" class="btn btn-primary">Go somewhere</a> </div>
      </div>
    </div>
  </div>
     <div class="row">
          <div class="text-center col-lg-6 offset-lg-3 offset-xl-0 col-xl-12">
            <p>Copyright &copy; 2019 Blinkee All Rights Reserved - Privacy Policy and Terms &amp; Conditions</p>
          </div>
  </div>
    </div>
</body>

</html>
