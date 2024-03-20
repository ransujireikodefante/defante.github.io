# defante.github.io
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Toyota</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
    }
    header {
      background-color: #1c1c1c;
      color: #fff;
      padding: 10px;
      text-align: center;
    }
    nav {
      background-color: #333;
      text-align: center;
      padding: 10px;
    }
    nav a {
      color: #fff;
      text-decoration: none;
      margin: 0 10px;
    }
    section {
      padding: 20px;
    }
    footer {
      background-color: #1c1c1c;
      color: #fff;
      text-align: center;
      padding: 10px;
      position: fixed;
      bottom: 0;
      width: 100%;
    }
    .container {
      max-width: 1200px;
      margin: 0 auto;
      padding: 0 20px;
    }
    .image-gallery {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      margin-top: 20px;
    }
    .image-gallery img {
      width: 300px;
      margin: 10px;
    }
  </style>
</head>
<body>
  <header>
    <h1>Welcome to Toyota</h1>
  </header>
  <nav>
    <a href="#home">Home</a>
    <a href="#about">About</a>
    <a href="#products">Products/Services</a>
  </nav>
  <section id="home">
    <div class="container">
      <h2>Homepage</h2>
      <div class="image-gallery">
        <img src="toyota1.png" alt="Toyota Car 1">
        <img src="toyota2.png" alt="Toyota Car 2">
        <img src="toyota3.png" alt="Toyota Car 3">
      </div>
    </div>
  </section>
  <section id="about">
    <div class="container">
      <h2>About Toyota</h2>
      <p>Toyota is a Japanese multinational automotive manufacturer headquartered in Toyota City, Japan. It was founded by Kiichiro Toyoda in 1937.</p>
      <img src="factory.jpg" alt="Toyota Factory">
    </div>
  </section>
  <section id="products">
    <div class="container">
      <h2>Products/Services</h2>
      <h3>Vehicles</h3>
      <div class="image-gallery">
        <img src="toyota camry.png" alt="Toyota Camry">
        <img src="toyota corolla.jpg" alt="Toyota Corolla">
        <img src="toyota rav4.jpg" alt="Toyota RAV4">
      </div>
      <div>
      <h3>Services</h3>
      <p>We offer maintenance and repair services for Toyota vehicles.</p>
    </div>
  </section>
  <footer>
    <p>&copy; 2024 Toyota. Defante.</p>
  </footer>
</body>
</html>


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Toyota Products & Services</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <nav>
            <ul>
                <li><a href="services.html">Services</a></li>
                <li><a href="products.html">Products</a></li>
            </ul>
        </nav>
    </header>

    <section class="products">
        <h2>Toyota Products & Services</h2>
        <div class="product">
            <img src="toyota camry.png" alt="Camry">
            <h3>Camry</h3>
            <p>The Camry has a stellar reputation for reliability. It's known to run for hundreds of thousands of miles with proper maintenance. This makes it a go-to choice for folks looking for a worry-free car ownership experience. Safety: Toyota doesn't skimp on safety, and the Camry is a testament to that.</p>
        </div>
        <div class="product">
            <img src="toyota corolla.jpg" alt="Corolla">
            <h3>Corolla</h3>
            <p>Along with a fuel-efficient four-cylinder, the Corolla sedan offers an immensely thrifty hybrid model. The EPA estimates the front-drive hybrid will earn 50 mpg city and 43 mpg highway while the all-wheel drive one is rated for 47 mpg city and 41 mpg highway.</p>
        </div>
        <div class="product">
            <img src="toyota rav4.jpg" alt="RAV4">
            <h3>RAV4</h3>
            <p>The 2024 Toyota RAV4 is a well-rounded compact SUV that boasts good fuel economy, a spacious cabin and a long list of standard features. It's a reliable option and a good value in the class, but its noisy engine disappoints.</p>
        </div>
        <div class="product">
            <img src="pickup.png" alt="Pickup Truck">
            <h3>Pickup Truck</h3>
            <p>What's so special about a Toyota Hilux?
The Toyota Hilux is known for its durability and reliability. It is designed to withstand tough conditions and extreme environments. The Hilux is built with a tough frame and body that can handle heavy loads and harsh terrains. It has a reputation for being one of the most reliable vehicles in the market.</p>
        </div>
    </section>

    <footer>
        <p>&copy; 2024 Toyota. Defante.</p>
    </footer>
</body>
</html>
