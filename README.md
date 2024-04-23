# Resturant-
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tasty Foods</title>
    <link rel="icon" type="images/x-icon" href="./images/tasty.jpg" />
    <link rel="stylesheet" href="css/bootstrap.css">
    <link rel="stylesheet" href="style1.css">
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.1/font/bootstrap-icons.css">

</head>
<body>
    <!--Navbar-->
    <nav class="navbar navbar-expand-lg navbar-light bg-warning fixed-top">
      <div class="container-fluid">
        <a class="navbar-brand text-white fw-bold" href="#">Tasty Foods</a>
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarSupportedContent">
          <ul class="navbar-nav me-auto mb-2 mb-lg-0">
            <li class="nav-item">
              <a class="nav-link active" aria-current="page" href="#carouselExampleCaptions">Home</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#order">Orders</a>
            </li>
            <li class="nav-item dropdown">
              <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                Deals
              </a>
              <ul class="dropdown-menu">
                <li><a class="dropdown-item" href="#">Action</a></li>
                <li><a class="dropdown-item" href="#">Another action</a></li>
                <li><hr class="dropdown-divider"></li>
                <li><a class="dropdown-item" href="#">Something else here</a></li>
              </ul>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#footer" aria-disabled="true">Location</a>
            </li>
          </ul>
          <form class="d-flex" role="search">
            <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search">
            <button class="btn btn-success" type="submit">Search</button>
          </form>
        </div>
      </div>
    </nav>
    <!--Carousal-->
    <div id="carouselExampleCaptions" class="carousel slide">
      <div class="carousel-indicators">
        <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
        <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="1" aria-label="Slide 2"></button>
        <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="2" aria-label="Slide 3"></button>
      </div>
      <div class="carousel-inner">
        <div class="carousel-item active">
          <img src="./images/download.jpg" class="slide d-block w-100" alt="...">
          <div class="carousel-caption d-none d-md-block">
            <h2 class="text-dark">Kerala Meals</h2>
            <p class="text-dark">Some representative placeholder content for the first slide.</p>
          </div>
        </div>
        <div class="carousel-item">
          <img src="./images/OIP (5).jpg" class="slide d-block w-100" alt="...">
          <div class="carousel-caption d-none d-md-block">
            <h2 class="text-dark">Non Veg Items</h2>
            <p class="text-dark">Some representative placeholder content for the second slide.</p>
          </div>
        </div>
        <div class="carousel-item">
          <img src="./images/OIP.jpg" class="slide d-block w-100" alt="...">
          <div class="carousel-caption d-none d-md-block">
            <h2 class="text-dark">Variety Dosas</h2>
            <p class="text-dark">Some representative placeholder content for the third slide.</p>
          </div>
        </div>
      </div>
      <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide="prev">
        <span class="carousel-control-prev-icon" aria-hidden="true"></span>
        <span class="visually-hidden">Previous</span>
      </button>
      <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide="next">
        <span class="carousel-control-next-icon" aria-hidden="true"></span>
        <span class="visually-hidden">Next</span>
      </button>
    </div>
    <!--Order Section-->
    <div class="container" id="order">
      <h1 class="text-center">Order your Foods Now</h1>

    <div class="row">
      <div class="col-4">
        <div class="card text-center border-2 border-warning" style="width: 18rem; height: 25rem;">
        <img src="./images/meals.jpg" class="card-img-top" alt="...">
        <div class="card-body">
          <h5 class="card-title">Meals</h5>
          <p class="card-text">Kerala Sadya</p>
          <h5 class="card-title text-danger">Rs.120.00</h5>
          <a href="#" class="btn btn-primary">Order Now</a>
        </div>
      </div></div>
      <div class="col-4">
        <div class="card text-center border-2 border-warning" style="width: 18rem; height: 25rem;">
          <img src="./images/briyani.jpg" class="card-img-top" alt="...">
          <div class="card-body">
            <h5 class="card-title">Briyani</h5>
            <p class="card-text">Tasty chicken briyani</p>
            <h5 class="card-title text-danger">Rs.180.00</h5>
            <a href="#" class="btn btn-primary">Order Now</a>
          </div>
        </div>
      </div>
      <div class="col-4">
        <div class="card text-center border-2 border-warning" style="width: 18rem; height: 25rem;">
          <img src="./images/dosa.jpg" class="card-img-top" alt="...">
          <div class="card-body">
            <h5 class="card-title">Dosa</h5>
            <p class="card-text">Tasty Dosa</p>
            <h5 class="card-title text-danger">Rs.110.00</h5>
            <a href="#" class="btn btn-primary">Order Now</a>
          </div>
        </div>
      </div>


    </div>
    <div class="row my-2">
      <div class="col-4">
        <div class="card text-center border-2 border-warning" style="width: 18rem; height: 25rem;">
          <img src="./images/OIP (4).jpg" class="card-img-top" alt="...">
          <div class="card-body">
            <h5 class="card-title">Fish</h5>
            <p class="card-text">Tasty fish fry</p>
            <h5 class="card-title text-danger">Rs.180.00</h5>
            <a href="#" class="btn btn-primary">Order Now</a>
          </div>
        </div>
      </div>
      <div class="col-4">
        <div class="card text-center border-2 border-warning" style="width: 18rem; height: 25rem;">
          <img src="./images/idali.jpg" class="card-img-top" alt="...">
          <div class="card-body">
            <h5 class="card-title">Idali</h5>
            <p class="card-text">Tasty Idali</p>
            <h5 class="card-title text-danger">Rs.50.00</h5>
            <a href="#" class="btn btn-primary">Order Now</a>
          </div>
        </div>
      </div>
      <div class="col-4">
        <div class="card text-center border-2 border-warning" style="width: 18rem; height: 25rem;">
          <img src="./images/burger.jpg" class="card-img-top" alt="...">
          <div class="card-body">
            <h5 class="card-title">Burger</h5>
            <p class="card-text">Tasty Burger</p>
            <h5 class="card-title text-danger">Rs.180.00</h5>
            <a href="#" class="btn btn-primary">Order Now</a>
          </div>
        </div>
      </div>


    </div>
    </div>
    
    <!--Footer-->
    <div class ="container-fluid bg-warning" id="footer">
      <div class="row">
        <h1 class="text-center">Location</h1>
        <div class="col-6">
          <h1 class="text-white">Tasty Food Resturant</h1>
          <h4>Kochi</h4>
          <h4>Kerala</h4>
          <p>Tel:0123456</p>
          <p>Email:tasty@gmail.com</p>
          <p>www.tasty foods.com</p>
        
        </div>
        <div class="col-6">
          <img src="./images/resturant.jpg">
        </div>
      </div>



    </div>
    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.11.8/dist/umd/popper.min.js" integrity="sha384-I7E8VVD/ismYTF4hNIPjVp/Zjvgyol6VFvRkX/vR+Vc4jQkC+hVqc2pM8ODewa9r" crossorigin="anonymous"></script>

    <script src="/js/bootstrap.js"></script>
</body>
</html>
