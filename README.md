<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Royal Fataka | Fireworks</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background-color: #0c0c0c;
      color: #fff;
      scroll-behavior: smooth;
    }

    header {
      background: linear-gradient(to right, #ff0080, #ff8c00);
      padding: 20px 40px;
      text-align: center;
    }

    header h1 {
      margin: 0;
      font-size: 2.5rem;
    }

    nav {
      background: #111;
      display: flex;
      justify-content: center;
      gap: 30px;
      padding: 10px 0;
    }

    nav a {
      color: #fff;
      text-decoration: none;
      font-weight: bold;
      transition: color 0.3s;
    }

    nav a:hover {
      color: #ff8c00;
    }

    section {
      padding: 60px 20px;
      max-width: 1000px;
      margin: auto;
    }

    .home {
      background: url('https://images.unsplash.com/photo-1507919982529-7fbc4a1abf15') center/cover no-repeat;
      color: white;
      text-shadow: 2px 2px 8px black;
      height: 80vh;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
    }

    .home h2 {
      font-size: 3rem;
      margin: 0;
    }

    .home p {
      font-size: 1.2rem;
      max-width: 600px;
      text-align: center;
    }

    .about, .contact {
      background-color: #1a1a1a;
    }

    footer {
      background: #111;
      text-align: center;
      padding: 20px;
      font-size: 0.9rem;
      color: #aaa;
    }

    form {
      display: flex;
      flex-direction: column;
      max-width: 400px;
      margin: auto;
    }

    input, textarea {
      padding: 10px;
      margin: 10px 0;
      border: none;
      border-radius: 4px;
    }

    button {
      background-color: #ff8c00;
      color: #000;
      padding: 10px;
      font-weight: bold;
      border: none;
      border-radius: 4px;
      cursor: pointer;
    }

    button:hover {
      background-color: #e67300;
    }
  </style>
</head>
<body>

  <header>
    <h1>Royal Fataka</h1>
    <p>Lighting Up the Sky Since [Year]</p>
  </header>

  <nav>
    <a href="#home">Home</a>
    <a href="#about">About Us</a>
    <a href="#contact">Contact</a>
  </nav>

  <section id="home" class="home">
    <h2>Welcome to Royal Fataka</h2>
    <p>Explore a dazzling range of fireworks that will turn your celebrations into a spectacle of light and sound!</p>
  </section>

  <section id="about" class="about">
    <h2>About Us</h2>
    <p>
      At Royal Fataka, we specialize in high-quality fireworks for all occasions—festivals, weddings, events, and more. 
      With years of experience, we are committed to safety, innovation, and unforgettable moments in the night sky.
    </p>
  </section>

  <section id="contact" class="contact">
    <h2>Contact Us</h2>
    <form>
      <input type="text" placeholder="Your Name" required />
      <input type="email" placeholder="Your Email" required />
      <textarea rows="5" placeholder="Your Message" required></textarea>
      <button type="submit">Send Message</button>
    </form>
  </section>

  <footer>
    &copy; 2025 Royal Fataka. All rights reserved.
  </footer>

</body>
</html>


