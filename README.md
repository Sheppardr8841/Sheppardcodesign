<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Sheppard & C. Design + Build</title>
  <link href="https://fonts.googleapis.com/css2?family=Lato&family=Playfair+Display&display=swap" rel="stylesheet">
  <style>
    :root {
      --green: #2D3E34;
      --brown: #7A5E45;
      --cream: #F2EEE3;
      --gray: #4C4C4C;
    }
    * { margin: 0; padding: 0; box-sizing: border-box; }
    body {
      font-family: 'Lato', sans-serif;
      color: var(--gray);
      background-color: var(--cream);
    }
    header {
      background: var(--green);
      color: var(--cream);
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 1rem 2rem;
      position: sticky;
      top: 0;
      z-index: 1000;
    }
    header h1 { font-family: 'Playfair Display', serif; font-size: 1.5rem; }
    nav a {
      color: var(--cream);
      margin-left: 1rem;
      text-decoration: none;
      font-weight: bold;
    }
    .hero {
      background: url('https://images.unsplash.com/photo-1600585154340-be6161a56a0c') center/cover no-repeat;
      color: var(--cream);
      text-align: center;
      padding: 8rem 2rem;
    }
    .hero h2 {
      font-family: 'Playfair Display', serif;
      font-size: 3rem;
    }
    .hero p {
      font-size: 1.25rem;
      margin: 1rem 0 2rem;
    }
    .btn {
      background: var(--brown);
      color: var(--cream);
      padding: 0.75rem 1.5rem;
      border: none;
      font-weight: bold;
      cursor: pointer;
    }
    section {
      padding: 4rem 2rem;
      max-width: 1200px;
      margin: auto;
    }
    .services, .portfolio {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 2rem;
    }
    .service, .portfolio-item {
      background: white;
      padding: 1rem;
      border: 1px solid #ddd;
    }
    .service img {
      width: 40px;
      margin-bottom: 1rem;
    }
    .testimonials, .contact {
      background: var(--brown);
      color: var(--cream);
      padding: 4rem 2rem;
    }
    footer {
      background: var(--green);
      color: var(--cream);
      text-align: center;
      padding: 2rem;
    }
  </style>
</head>
<body>
  <header>
    <h1>Sheppard & C.</h1>
    <nav>
      <a href="#services">Services</a>
      <a href="#portfolio">Portfolio</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <section class="hero">
    <h2>Your Vision. Our Craft.</h2>
    <p>High-quality custom builds & interiors, done right.</p>
    <button class="btn">Get a Quote</button>
  </section>

  <section id="about">
    <h2>About Us</h2>
    <p>With over 20 years in the trades, we bring experience, reliability, and passion to every project. We specialize in trim, interiors, decks, and complete custom work.</p>
  </section>

  <section id="services">
    <h2>Services</h2>
    <div class="services">
      <div class="service">
        <img src="https://img.icons8.com/ios-filled/50/hammer.png" alt="Trim Work" />
        <h3>Interior Trim & Finish</h3>
        <p>Detail-rich interior trim that elevates your space.</p>
      </div>
      <div class="service">
        <img src="https://img.icons8.com/ios-filled/50/saw.png" alt="Custom Carpentry" />
        <h3>Custom Carpentry</h3>
        <p>Tailor-made features for function and beauty.</p>
      </div>
      <div class="service">
        <img src="https://img.icons8.com/ios-filled/50/deck.png" alt="Decks" />
        <h3>Decks & Porches</h3>
        <p>Built for relaxation and long-lasting value.</p>
      </div>
      <div class="service">
        <img src="https://img.icons8.com/ios-filled/50/renovation.png" alt="Renovations" />
        <h3>Full-Service Renovations</h3>
        <p>Complete updates done with care and expertise.</p>
      </div>
    </div>
  </section>

  <section id="portfolio">
    <h2>Portfolio</h2>
    <div class="portfolio">
      <div class="portfolio-item"><img src="https://images.unsplash.com/photo-1560185008-5c9d47b9fc86" alt="Project 1" width="100%"></div>
      <div class="portfolio-item"><img src="https://images.unsplash.com/photo-1599423300746-b62533397364" alt="Project 2" width="100%"></div>
      <div class="portfolio-item"><img src="https://images.unsplash.com/photo-1630510863203-7fc2a29c2c89" alt="Project 3" width="100%"></div>
    </div>
  </section>

  <section class="testimonials">
    <h2>What Our Clients Say</h2>
    <p>"The Sheppard team turned our ideas into a beautiful finished space. Highly recommend!"</p>
    <p>"Professional, on-time, and meticulous craftsmanship."</p>
  </section>

  <section id="contact" class="contact">
    <h2>Contact Us</h2>
    <form>
      <input type="text" placeholder="Name" required /><br/><br/>
      <input type="email" placeholder="Email" required /><br/><br/>
      <input type="tel" placeholder="Phone" /><br/><br/>
      <textarea placeholder="Message" rows="5" required></textarea><br/><br/>
      <button class="btn" type="submit">Send Message</button>
    </form>
  </section>

  <footer>
    <p>&copy; 2025 Sheppard & C. Design + Build | Lic. #123456</p>
  </footer>
</body>
</html>



