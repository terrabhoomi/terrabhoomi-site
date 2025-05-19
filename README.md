# terrabhoomi-site
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Terra Bhoomi</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    }

    body {
      background-color: #f5f5f5;
      color: #333;
    }

    header {
      background: #000;
      color: #fff;
      padding: 15px 30px;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }

    header img {
      height: 50px;
    }

    nav a {
      color: #fff;
      margin-left: 20px;
      text-decoration: none;
      font-weight: 500;
    }

    .hero {
      background-image: url("CD5F58CC-79CB-464A-A549-9B7BD361D17D.jpeg");
      background-size: cover;
      background-position: center;
      height: 90vh;
      display: flex;
      align-items: center;
      justify-content: center;
      color: white;
      text-shadow: 2px 2px 5px rgba(0,0,0,0.7);
      text-align: center;
    }

    .hero h1 {
      font-size: 3em;
      max-width: 90%;
    }

    .about, .gallery, .contact {
      padding: 60px 30px;
      text-align: center;
    }

    .about h2, .gallery h2, .contact h2 {
      font-size: 2em;
      margin-bottom: 20px;
    }

    .gallery-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
      margin-top: 30px;
    }

    .gallery-grid img {
      width: 100%;
      border-radius: 10px;
      box-shadow: 0 5px 15px rgba(0,0,0,0.2);
    }

    .contact p {
      font-size: 1.1em;
      margin-top: 10px;
    }

    footer {
      background: #222;
      color: #aaa;
      text-align: center;
      padding: 20px;
    }
  </style>
</head>
<body>

  <header>
    <img src="2C920330-4477-4264-A124-A23BB292E8DF.jpeg" alt="Terra Bhoomi Logo" />
    <nav>
      <a href="#">Home</a>
      <a href="#about">About</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <section class="hero">
    <h1>Discover Nature. Live Premium. Terra Bhoomi.</h1>
  </section>

  <section id="about" class="about">
    <h2>About Terra Bhoomi</h2>
    <p>
      Terra Bhoomi is your ultimate nature and adventure destination in Kerala. Spanning 10 acres of stunning landscapes,
      we blend luxury with sustainability – from private villas and eco-rooms to treks, treehouses, ziplining and more.
    </p>
  </section>

  <section class="gallery">
    <h2>Gallery</h2>
    <div class="gallery-grid">
      <img src="07C18821-871E-4176-9678-80DAAC5E789D.jpeg" alt="Gallery Image 1" />
      <img src="31AAB8F2-B7B3-4D90-8D5C-D3C77C852784.jpeg" alt="Gallery Image 2" />
      <img src="J8tHYGcVwtBHMzVRRdSz13.jpeg" alt="Gallery Image 3" />
    </div>
  </section>

  <section id="contact" class="contact">
    <h2>Contact Us</h2>
    <p>Email: connect.terrabhoomi@gmail.com</p>
    <p>Instagram: @terrabhoomi</p>
    <p>Phone: +91 97453 99831</p>
  </section>

  <footer>
    © 2025 Terra Bhoomi. All rights reserved.
  </footer>

</body>
</html>
