
## Date:24/10/2025

## AIM:
To create a simplified clone of Dribbble (https://dribbble.com/) landing page.


## DESIGN STEPS:

### Step 1:
Clone the repository from GitHub.

### Step 2:
Create Django Admin project.

### Step 3:
Create a New App under the Django Admin project.

### Step 4:
Insert the necessary CSS and JavaScript files as external in order to use Bootstrap.

### Step 5:
Create a HTML file and include the needed Bootstrap components.

### Step 6:
Publish the website in the LocalHost.

## PROGRAM :
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Dribbble Gallery</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
</head>
<body>
  
  <!-- Navigation Bar -->
  <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
    <div class="container-fluid">
      <a class="navbar-brand fw-bold" href="#">DRIBBBLE</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav me-auto">
          <li class="nav-item">
            <a class="nav-link active" href="#">Home</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Inspiration</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Find Work</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Learn Design</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Hire Designers</a>
          </li>
        </ul>
        <form class="d-flex">
          <input class="form-control me-2" type="search" placeholder="Search">
          <button class="btn btn-outline-light" type="submit">Search</button>
        </form>
      </div>
    </div>
  </nav>

  <!-- Banner Section -->
  <div class="bg-primary text-white text-center py-3">
    <h5 class="mb-2">Discover the world's top designers & creatives</h5>
    <button class="btn btn-light btn-sm">Sign Up</button>
  </div>

  <!-- Filter Section -->
  <div class="container my-4">
    <div class="d-flex justify-content-center gap-3 flex-wrap">
      <div class="dropdown">
        <button class="btn btn-outline-secondary dropdown-toggle" type="button" data-bs-toggle="dropdown">
          Shots
        </button>
        <ul class="dropdown-menu">
          <li><a class="dropdown-item" href="#">All Shots</a></li>
          <li><a class="dropdown-item" href="#">Animated</a></li>
          <li><a class="dropdown-item" href="#">Branding</a></li>
        </ul>
      </div>
      <div class="dropdown">
        <button class="btn btn-outline-secondary dropdown-toggle" type="button" data-bs-toggle="dropdown">
          Timeframe
        </button>
        <ul class="dropdown-menu">
          <li><a class="dropdown-item" href="#">Now</a></li>
          <li><a class="dropdown-item" href="#">This Week</a></li>
          <li><a class="dropdown-item" href="#">This Month</a></li>
        </ul>
      </div>
      <div class="dropdown">
        <button class="btn btn-outline-secondary dropdown-toggle" type="button" data-bs-toggle="dropdown">
          Color
        </button>
        <ul class="dropdown-menu">
          <li><a class="dropdown-item" href="#">Any Color</a></li>
          <li><a class="dropdown-item" href="#">Red</a></li>
          <li><a class="dropdown-item" href="#">Blue</a></li>
        </ul>
      </div>
    </div>
  </div>

  <!-- Gallery Section -->
  <div class="container my-5">
    <div class="row g-4">
      <div class="col-lg-3 col-md-4 col-sm-6">
        <div class="card h-100">
          <img src="web studio.png" class="card-img-top" alt="Design 1">
          <div class="card-body">
            <h6 class="card-title">Creative Studio</h6>
            <p class="card-text text-muted small">9.2K views • 1000 likes</p>
          </div>
        </div>
      </div>
      <div class="col-lg-3 col-md-4 col-sm-6">
        <div class="card h-100">
          <img src="pro.png" class="card-img-top" alt="Design 2">
          <div class="card-body">
            <h6 class="card-title">Pro  web designer</h6>
            <p class="card-text text-muted small">2.5K views • 150 likes</p>
          </div>
        </div>
      </div>
      <div class="col-lg-3 col-md-4 col-sm-6">
        <div class="card h-100">
          <img src="astro.png" class="card-img-top" alt="Design 3">
          <div class="card-body">
            <h6 class="card-title">Astronomy</h6>
            <p class="card-text text-muted small">890 views • 67 likes</p>
          </div>
        </div>
      </div>
      <div class="col-lg-3 col-md-4 col-sm-6">
        <div class="card h-100">
          <img src="brand id.png" class="card-img-top" alt="Design 4">
          <div class="card-body">
            <h6 class="card-title">Brand Identity</h6>
            <p class="card-text text-muted small">3.1K views • 201 likes</p>
          </div>
        </div>
      </div>
      <div class="col-lg-3 col-md-4 col-sm-6">
        <div class="card h-100">
          <img src="ui.png" class="card-img-top" alt="Design 5">
          <div class="card-body">
            <h6 class="card-title">UI/UX Designer</h6>
            <p class="card-text text-muted small">1.8K views • 120 likes</p>
          </div>
        </div>
      </div>
      <div class="col-lg-3 col-md-4 col-sm-6">
        <div class="card h-100">
          <img src="motion.png" class="card-img-top" alt="Design 6">
          <div class="card-body">
            <h6 class="card-title">Motion Graphics</h6>
            <p class="card-text text-muted small">4.2K views • 310 likes</p>
          </div>
        </div>
      </div>
      <div class="col-lg-3 col-md-4 col-sm-6">
        <div class="card h-100">
          <img src="illu.png" class="card-img-top" alt="Design 7">
          <div class="card-body">
            <h6 class="card-title">Illustration Lab</h6>
            <p class="card-text text-muted small">980 views • 75 likes</p>
          </div>
        </div>
      </div>
      <div class="col-lg-3 col-md-4 col-sm-6">
        <div class="card h-100">
          <img src="pro des.png" class="card-img-top" alt="Design 8">
          <div class="card-body">
            <h6 class="card-title">Product Design</h6>
            <p class="card-text text-muted small">2.9K views • 189 likes</p>
          </div>
        </div>
      </div>
    </div>
  </div>

  <!-- Footer -->
  <footer class="bg-dark text-white text-center py-4 mt-5">
    <div class="container">
      <p class="mb-0">Created by Rithika</p>
      <p class="mb-0 small text-muted mt-2">© 2024 Dribbble Clone. All rights reserved.</p>
    </div>
  </footer>

</body>
</html>
```
## OUTPUT:
<img width="1920" height="1080" alt="Screenshot (63)" src="https://github.com/user-attachments/assets/a6c794e8-28e5-4f0d-ab32-2e48de0002f2" />


<img width="1920" height="1080" alt="Screenshot (64)" src="https://github.com/user-attachments/assets/75424618-4b28-4eb1-a192-793a12ec9450" />

## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
