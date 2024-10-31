Nama   : Anita (312310244)
# LatihanWeb5
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mengenal JavaScript</title>
    <script type="text/javascript" src="assets/js/app.js"></script>
</head>
<body>
    <h1>Pengenalan JavaScript</h1>
    <h3>Contoh document.write dan console.log</h3>
    <script>
        document.write("Hello World");
        console.log("Hello World");
    </script>

    <!-- Form dengan Validasi JavaScript -->
    <h3>Form Validasi</h3>
    <form onsubmit="return validateForm()">
        Nama: <input type="text" id="name" name="name"><br><br>
        Email: <input type="text" id="email" name="email"><br><br>
        <input type="submit" value="Submit">
    </form>
</body>
</html>

# Hasil : 
![Screenshot (238)](https://github.com/user-attachments/assets/26b4581b-d623-4618-98af-edc3307a1a72)

Nama : Anita (312310244)


# latihanWeb6
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Simple Bootstrap Layout</title>
  <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
  <style>
    .featurette-image {
      width: 150px;
      height: 150px;
      background-color: #6c757d;
    }
    .widget-box {
      background-color: #f8f9fa;
      padding: 20px;
      margin-top: 20px;
    }
    .widget-header {
      background-color: #007bff;
      color: white;
      padding: 10px;
      margin-bottom: 10px;
    }
    .circle-icon {
      width: 120px;
      height: 120px;
      border-radius: 50%;
      display: inline-block;
      margin: auto;
    }
  </style>
</head>
<body>

<div class="container">
  <!-- Header Section -->
  <div class="jumbotron text-center">
    <h1 class="display-4">Hello World!</h1>
    <p class="lead">Lorem ipsum dolor sit amet, consectetur adipiscing elit...</p>
    <a href="#" class="btn btn-primary btn-lg">Learn more »</a>
  </div>

  <!-- Circle Icons Section -->
  <div class="row text-center mb-4">
    <div class="col-md-4">
      <div class="circle-icon bg-warning mb-2"></div>
      <h3>Heading</h3>
      <p>Donec sed odio dui...</p>
      <button class="btn btn-secondary">View detail</button>
    </div>
    <div class="col-md-4">
      <div class="circle-icon bg-primary mb-2"></div>
      <h3>Heading</h3>
      <p>Donec sed odio dui...</p>
      <button class="btn btn-secondary">View detail</button>
    </div>
    <div class="col-md-4">
      <div class="circle-icon bg-info mb-2"></div>
      <h3>Heading</h3>
      <p>Donec sed odio dui...</p>
      <button class="btn btn-secondary">View detail</button>
    </div>
  </div>

  <!-- Main Content with Widget -->
  <div class="row">
    <!-- Main Content -->
    <div class="col-md-8">
      <div class="featurette mb-4">
        <div class="row">
          <div class="col-md-7">
            <h2 class="featurette-heading">First featurette heading.</h2>
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit...</p>
          </div>
          <div class="col-md-5">
            <div class="featurette-image"></div>
          </div>
        </div>
      </div>
      <div class="featurette mb-4">
        <div class="row">
          <div class="col-md-7 order-md-2">
            <h2 class="featurette-heading">First featurette heading.</h2>
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit...</p>
          </div>
          <div class="col-md-5 order-md-1">
            <div class="featurette-image"></div>
          </div>
        </div>
      </div>
    </div>

    <!-- Widget Section -->
    <div class="col-md-4">
      <div class="widget-box">
        <div class="widget-header">Widget Header</div>
        <ul class="list-unstyled">
          <li><a href="#">Widget Link</a></li>
          <li><a href="#">Widget Link</a></li>
          <li><a href="#">Widget Link</a></li>
          <li><a href="#">Widget Link</a></li>
          <li><a href="#">Widget Link</a></li>
        </ul>
      </div>
      <div class="widget-box">
        <div class="widget-header">Widget Text</div>
        <p>Vestibulum lorem elit, iaculis in nisl...</p>
      </div>
    </div>
  </div>

  <!-- Footer -->
  <footer class="text-center mt-4">
    <p>&copy; 2021 - Universitas Pelita Bangsa</p>
  </footer>
</div>

<script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
<script src="https://cdn.jsdelivr.net/npm/bootstrap@4.5.2/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>

# Hasil : 
![Screenshot 2024-10-31 133635](https://github.com/user-attachments/assets/0d7448cd-10f7-4b56-acea-2ea5a18a19e2)

