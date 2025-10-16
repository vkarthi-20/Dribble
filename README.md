# Project Responsive Web Design using Bootstrap
## Date:16-10-2025

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
  <title>Dribble Clone</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet">
</head>
<body class="bg-info">

  <nav class="navbar navbar-expand-lg navbar-dark bg-info">
    <div class="container">
      <a class="navbar-brand" href="#">DribbleClone</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ms-auto">
          <li class="nav-item"><a class="nav-link active" href="#">Home</a></li>
          <li class="nav-item"><a class="nav-link" href="#">Shots</a></li>
          <li class="nav-item"><a class="nav-link" href="#">About</a></li>
          <li class="nav-item"><a class="nav-link" href="#">Contact</a></li>
          <li class="nav-item"><a class="btn btn-primary ms-3" href="#">Sign Up</a></li>
        </ul>
      </div>
    </div>
  </nav>

  <section class="text-center bg-warning py-4">
    <div class="container bg-success">
      <h1 class="display-5">WELCOME TO THE SPORTS WORLD</h1>
      <p class="lead display-7">SPORTS TOOLS</p>
      <a href="#" class="btn btn-primary btn-lg ">PLAY GAME</a>
    </div>
  </section>

  <section class="py-4">
    <div class="container">
      <h2 class="mb-4 text-center text-brown"></h2>
      <div class="row g-3 justify-content-center">
        
        <div class="col-md-3 col-sm-6">
          <div class="card">
            <img src="bat.jpg" class="card-img-top" alt="Shot 1" style="height:180px; object-fit:cover;">
          </div>
        </div>

        <div class="col-md-3 col-sm-6">
          <div class="card">
            <img src="archery.jpg" class="card-img-top" alt="Shot 2" style="height:180px; object-fit:cover;">
          </div>
        </div>

        <div class="col-md-3 col-sm-6">
          <div class="card">
            <img src="shooting gun.webp" class="card-img-top" alt="Shot 3" style="height:180px; object-fit:cover;">
          </div>
        </div>

        <div class="col-md-3 col-sm-6">
          <div class="card">
            <img src="shoe.jpg" class="card-img-top" alt="Shot 4" style="height:180px; object-fit:cover;">
          </div>
        </div>

        <div class="col-md-3 col-sm-6">
          <div class="card">
            <img src="discuss throw.jpg" class="card-img-top" alt="Shot 5" style="height:180px; object-fit:cover;">
          </div>
        </div>

        <div class="col-md-3 col-sm-6">
          <div class="card">
            <img src="football.jpg" class="card-img-top" alt="Shot 6" style="height:180px; object-fit:cover;">
          </div>
        </div>

         <div class="col-md-3 col-sm-6">
          <div class="card">
            <img src="Shotput-Ball.jpg" class="card-img-top" alt="Shot 6" style="height:180px; object-fit:cover;">
          </div>
        </div>

        <div class="col-md-3 col-sm-6">
          <div class="card">
            <img src="javelin.jpg" class="card-img-top" alt="Shot 6" style="height:180px; object-fit:cover;">
          </div>
        </div>

      </div>
    </div>
  </section>


  <footer class="bg-dark text-white text-center py-4">
    <p> DESIGNED AND DEVELOPED BY KARTHI V (25017522)</p>
  </footer>

  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
```

## OUTPUT:
![alt text](<karthi/projectapp/static/Screenshot (122).png>)

## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
