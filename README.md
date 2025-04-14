# Bootstrap-Website
Created a website using bootstrap
<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Bootstrap Components</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha2/dist/css/bootstrap.min.css" rel="stylesheet"
    integrity="sha384-aFq/bzH65dt+w6FI2ooMVUpc+21e0SRygnTpmBvdBgSdnuTN7QbdgL+OapgHtvPp" crossorigin="anonymous">
  <style>
    .feature-icon {
      width: 4rem;
      height: 4rem;
      border-radius: 0.75rem;
    }
  </style>
</head>

<body>

<nav class="navbar navbar-expand-lg bg-body-tertiary">
    <div class="container-fluid">
      <a class="navbar-brand" href="#"><img src="./cake shop.jpg" alt="cake img" height="30">Buy Now</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent"
        aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarSupportedContent">
        <ul class="navbar-nav me-auto mb-2 mb-lg-0">
          <li class="nav-item">
            <a class="nav-link active" aria-current="page" href="#">Home</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">About</a>
          </li>
          <li class="nav-item dropdown">
            <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false">
              Services
            </a>
            <ul class="dropdown-menu">
              <li><a class="dropdown-item" href="#">Action</a></li>
              <li><a class="dropdown-item" href="#">Another action</a></li>
              <li>
                <hr class="dropdown-divider">
              </li>
              <li><a class="dropdown-item" href="#">Something else here</a></li>
            </ul>
          </li>
        </ul>
        <form class="d-flex" role="search">
          <input class="form-control me-2" type="search" placeholder="Postcode" aria-label="Search">
          <button class="btn btn-outline-success" type="submit">Check</button>
        </form>
      </div>
    </div>
  </nav>


  <div class="px-4 pt-5 my-5 text-center border-bottom">
    <h1 class="display-3 fw-bold text-body-emphasis">Cake It Now</h1>
    <h2 class="display-5">It’s sweet, it’s fluffy, it’s delicious🍰</h2>
    <div class="col-lg-6 mx-auto">
      <p class="lead mb-4">At my cake shop, we specialize in creating exquisite and delectable cakes that cater to a variety of tastes and occasions.
        Our skilled bakers use only the finest ingredients to ensure each cake is not only visually stunning but also rich in flavor.
        Whether it's a wedding, birthday, or any special event, we offer a diverse selection of designs and flavors to meet our customers' unique preferences.
        Our commitment to quality and customer satisfaction sets us apart, making every celebration memorable with our delightful confections.
      </p>
      <div class="d-grid gap-2 d-sm-flex justify-content-sm-center mb-4">
        <button type="button" class="btn btn-primary btn-lg px-3 me-sm-3">Get Cake</button>
        <button type="button" class="btn btn-primary btn-lg px-3 me-sm-2">Get Decorations</button>
        <button type="button" class="btn btn-primary btn-lg px-3 me-sm-3">Contact Us</button>
      </div>
    </div>
    <div class="overflow-hidden" style="max-height: 30vh;">
      <div class="container px-5">
        <img src="./main cake.jpg" class="img-fluid border rounded-3 shadow-lg mb-4" alt="cake image" width="500"
          height="400" loading="lazy">
      </div>
    </div>
  </div>

  <div class="container px-2 py-2" id="featured-3">
    <h2 class="pb-2 border-bottom">Why Purchase From Us?</h2>
    <div class="row g-4 py-5 row-cols-1 row-cols-lg-3">
      <div class="feature col">
        <div
          class="feature-icon d-inline-flex align-items-center justify-content-center text-bg-primary bg-gradient fs-2 mb-3">
          <img src="./briefcase.svg" alt="briefcase" height="30">
        </div>
        <h3 class="fs-2">Flavours</h3>
        <p>Different people have different choices at cake it now we keep this on the top
        so that any customer with any choice should be satisfied to see our variety of flavours in cake
        and pastries giving them multiple options to choose from</p>
        <a href="#" class="icon-link">
          Check Flavours
          <img src="./chevron-right.svg" alt="chevron-right">
        </a>
      </div>
      <div class="feature col">
        <div
          class="feature-icon d-inline-flex align-items-center justify-content-center text-bg-primary bg-gradient fs-2 mb-3">
          <img src="./chevron-right.svg" alt="bus-front" height="30">
        </div>
        <h3 class="fs-2">Hygiene</h3>
        <p>At cake it now we maintain the highest level of hygiene considering our customer's health
        and giving them the best buying experience.</p>
        <a href="#" class="icon-link">
          Check the making
          <img src="./chevron-right.svg" alt="chevron-right">
        </a>
      </div>
      <div class="feature col">
        <div
          class="feature-icon d-inline-flex align-items-center justify-content-center text-bg-primary bg-gradient fs-2 mb-3">
          <img src="./chat-square-heart.svg" alt="chat-square-heart" height="30">
        </div>
        <h3 class="fs-2">Affordable Prices</h3>
        <p>At our core, we believe that buying should be an exciting and positive experience,
          not a stressful one. By providing affordable prices along with discounts we hope to
          be pocket friendly the way people think about moving and still provide the best.</p>
        <a href="#" class="icon-link">
          Check Price Options
          <img src="./chevron-right.svg" alt="chevron-right">
        </a>
      </div>
    </div>
  </div>
  <div class="container">
    <div id="carouselExampleIndicators" class="carousel slide">
      <div class="carousel-indicators">
        <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="0" class="active"
          aria-current="true" aria-label="Slide 1"></button>
        <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="1"
          aria-label="Slide 2"></button>
        <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="2"
          aria-label="Slide 3"></button>
      </div>
      <div class="carousel-inner">
        <div class="carousel-item active">
          <img src="./1070236.jpg" class="d-block w-100" alt="couple">
        </div>
        <div class="carousel-item">
          <img src="./983077.jpg" class="d-block w-100" alt="dog">
        </div>
        <div class="carousel-item">
          <img src="./390899.jpg" class="d-block w-100" alt="family">
        </div>
      </div>
      <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleIndicators"
        data-bs-slide="prev">
        <span class="carousel-control-prev-icon" aria-hidden="true"></span>
        <span class="visually-hidden">Previous</span>
      </button>
      <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleIndicators"
        data-bs-slide="next">
        <span class="carousel-control-next-icon" aria-hidden="true"></span>
        <span class="visually-hidden">Next</span>
      </button>
    </div>
  </div>

  <div class="container">
    <footer class="row row-cols-1 row-cols-sm-2 row-cols-md-5 py-5 my-5 border-top">
      <div class="col mb-3">
        <a href="/" class="d-flex align-items-center mb-3 link-body-emphasis text-decoration-none">
          <svg class="bi me-2" width="40" height="32">
            <use xlink:href="#bootstrap"></use>
          </svg>
        </a>
        <p class="text-body-secondary">© 2023</p>
      </div>

      <div class="col mb-3">

      </div>

      <div class="col mb-3">
        <h5>Section</h5>
        <ul class="nav flex-column">
          <li class="nav-item mb-2"><a href="#" class="nav-link p-0 text-body-secondary">Home</a></li>
          <li class="nav-item mb-2"><a href="#" class="nav-link p-0 text-body-secondary">Features</a></li>
          <li class="nav-item mb-2"><a href="#" class="nav-link p-0 text-body-secondary">Pricing</a></li>
          <li class="nav-item mb-2"><a href="#" class="nav-link p-0 text-body-secondary">FAQs</a></li>
          <li class="nav-item mb-2"><a href="#" class="nav-link p-0 text-body-secondary">About</a></li>
        </ul>
      </div>

      <div class="col mb-3">
        <h5>Section</h5>
        <ul class="nav flex-column">
          <li class="nav-item mb-2"><a href="#" class="nav-link p-0 text-body-secondary">Home</a></li>
          <li class="nav-item mb-2"><a href="#" class="nav-link p-0 text-body-secondary">Features</a></li>
          <li class="nav-item mb-2"><a href="#" class="nav-link p-0 text-body-secondary">Pricing</a></li>
          <li class="nav-item mb-2"><a href="#" class="nav-link p-0 text-body-secondary">FAQs</a></li>
          <li class="nav-item mb-2"><a href="#" class="nav-link p-0 text-body-secondary">About</a></li>
        </ul>
      </div>

      <div class="col mb-3">
        <h5>Section</h5>
        <ul class="nav flex-column">
          <li class="nav-item mb-2"><a href="#" class="nav-link p-0 text-body-secondary">Home</a></li>
          <li class="nav-item mb-2"><a href="#" class="nav-link p-0 text-body-secondary">Features</a></li>
          <li class="nav-item mb-2"><a href="#" class="nav-link p-0 text-body-secondary">Pricing</a></li>
          <li class="nav-item mb-2"><a href="#" class="nav-link p-0 text-body-secondary">FAQs</a></li>
          <li class="nav-item mb-2"><a href="#" class="nav-link p-0 text-body-secondary">About</a></li>
        </ul>
      </div>
    </footer>
  </div>


<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha3/dist/js/bootstrap.bundle.min.js"
    integrity="sha384-ENjdO4Dr2bkBIFxQpeoTz1HIcje39Wm4jDKdf19U8gI4ddQ3GYNS7NTKfAdVQSZe"
    crossorigin="anonymous"></script>
</body>

</html>
