<!DOCTYPE html><html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Barron Smart | Luxury Front-End Developer</title>
  <meta name="description" content="Luxury front-end developer building premium websites, landing pages, and graphics that convert." />  <!-- Google Fonts -->  <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@500;700&family=Inter:wght@300;400;500;600&display=swap" rel="stylesheet">  <style>
    :root {
      --bg: #0b0b0b;
      --card: #111;
      --gold: #c6a75e;
      --text: #f5f5f5;
      --muted: #b5b5b5;
    }

    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: 'Inter', sans-serif;
      background: var(--bg);
      color: var(--text);
      line-height: 1.7;
    }

    a {
      text-decoration: none;
      color: inherit;
    }

    section {
      padding: 80px 20px;
      max-width: 1100px;
      margin: auto;
    }

    h1, h2, h3 {
      font-family: 'Playfair Display', serif;
      font-weight: 700;
    }

    /* HERO */
    .hero {
      min-height: 100vh;
      display: flex;
      align-items: center;
      justify-content: center;
      text-align: center;
    }

    .hero h1 {
      font-size: clamp(2.2rem, 5vw, 3.5rem);
      margin-bottom: 20px;
    }

    .hero h1 span {
      color: var(--gold);
    }

    .hero p {
      color: var(--muted);
      max-width: 650px;
      margin: auto;
      font-size: 1.05rem;
    }

    .buttons {
      margin-top: 40px;
      display: flex;
      justify-content: center;
      gap: 20px;
      flex-wrap: wrap;
    }

    .btn {
      padding: 14px 34px;
      border-radius: 40px;
      font-size: 0.95rem;
      transition: all 0.3s ease;
    }

    .btn-primary {
      background: var(--gold);
      color: #000;
    }

    .btn-primary:hover {
      opacity: 0.85;
    }

    .btn-outline {
      border: 1px solid var(--gold);
      color: var(--gold);
    }

    .btn-outline:hover {
      background: var(--gold);
      color: #000;
    }

    /* ABOUT */
    .about {
      text-align: center;
    }

    .about p {
      max-width: 750px;
      margin: auto;
      color: var(--muted);
    }

    /* SERVICES */
    .services {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 25px;
      margin-top: 50px;
    }

    .service {
      background: var(--card);
      padding: 35px 25px;
      border-radius: 18px;
      transition: transform 0.3s ease;
    }

    .service:hover {
      transform: translateY(-8px);
    }

    .service h3 {
      color: var(--gold);
      margin-bottom: 10px;
    }

    .service p {
      color: var(--muted);
      font-size: 0.95rem;
    }

    /* PORTFOLIO */
    .portfolio {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
      gap: 25px;
      margin-top: 50px;
    }

    .work {
      position: relative;
      overflow: hidden;
      border-radius: 18px;
      height: 220px;
      background: #000;
    }

    .work img {
      width: 100%;
      height: 100%;
      object-fit: cover;
      transition: transform 0.6s ease;
      opacity: 0.85;
    }

    .work:hover img {
      transform: scale(1.08);
    }

    .overlay {
      position: absolute;
      inset: 0;
      background: rgba(0,0,0,0.65);
      display: flex;
      align-items: center;
      justify-content: center;
      text-align: center;
      opacity: 0;
      transition: opacity 0.4s ease;
      padding: 20px;
    }

    .work:hover .overlay {
      opacity: 1;
    }

    .overlay strong {
      display: block;
      color: var(--gold);
      font-family: 'Playfair Display', serif;
      font-size: 1.1rem;
      margin-bottom: 6px;
    }

    .overlay span {
      font-size: 0.85rem;
      color: var(--muted);
    }

    /* CONTACT */
    .contact {
      text-align: center;
    }

    .contact p {
      color: var(--muted);
      margin-bottom: 30px;
    }

    /* FOOTER */
    footer {
      text-align: center;
      padding: 30px 15px;
      color: var(--muted);
      font-size: 0.85rem;
      border-top: 1px solid #222;
    }

    /* WHATSAPP FLOAT */
    .whatsapp {
      position: fixed;
      bottom: 20px;
      right: 20px;
      background: var(--gold);
      color: #000;
      padding: 14px 20px;
      border-radius: 50px;
      font-size: 0.9rem;
      box-shadow: 0 10px 30px rgba(0,0,0,0.4);
    }
  </style></head>
<body>  <!-- HERO -->  <section class="hero">
    <div>
      <h1>Luxury Websites That <span>Convert</span></h1>
      <p>I design and build premium, fast, and responsive websites for brands and individuals who want to stand out online.</p>
      <div class="buttons">
        <a href="#contact" class="btn btn-primary">Hire Me</a>
        <a href="#portfolio" class="btn btn-outline">View Work</a>
      </div>
    </div>
  </section>  <!-- ABOUT -->  <section class="about">
    <h2>About Me</h2>
    <p>I’m Barron, a front-end developer and creative designer focused on building high-end websites, landing pages, and brand visuals that look professional and perform smoothly across all devices.</p>
  </section>  <!-- SERVICES -->  <section>
    <h2 style="text-align:center;">What I Do</h2>
    <div class="services">
      <div class="service">
        <h3>Front-End Development</h3>
        <p>Clean, responsive, and fast websites built with modern HTML, CSS, and JavaScript.</p>
      </div>
      <div class="service">
        <h3>Website & Landing Pages</h3>
        <p>High-converting landing pages designed to turn visitors into real clients.</p>
      </div>
      <div class="service">
        <h3>Graphic Design</h3>
        <p>Premium visuals, banners, ads, and brand designs that elevate your business image.</p>
      </div>
    </div>
  </section>  <!-- PORTFOLIO -->  <section id="portfolio">
    <h2 style="text-align:center;">Selected Works</h2>
    <div class="portfolio">
      <div class="work">
        <img src="https://via.placeholder.com/600x400" alt="Business Website" />
        <div class="overlay">
          <div>
            <strong>Business Website</strong>
            <span>Modern corporate website with clean UI and fast performance.</span>
          </div>
        </div>
      </div><div class="work">
    <img src="https://via.placeholder.com/600x400" alt="Landing Page" />
    <div class="overlay">
      <div>
        <strong>Landing Page</strong>
        <span>High‑converting landing page designed to capture leads.</span>
      </div>
    </div>
  </div>

  <div class="work">
    <img src="https://via.placeholder.com/600x400" alt="Brand Design" />
    <div class="overlay">
      <div>
        <strong>Brand & Graphics</strong>
        <span>Premium graphics, ads, and visuals for modern brands.</span>
      </div>
    </div>
  </div>
</div>

  </section>  <!-- CONTACT -->  <section id="contact" class="contact">
    <h2>Let’s Work Together</h2>
    <p>Have a project in mind? Let’s build something premium.</p>
    <div class="buttons">
      <a href="https://wa.me/2349136112942" class="btn btn-primary">WhatsApp Me</a>
      <a href="mailto:abasifrekesmart@gmail.com" class="btn btn-outline">Send Email</a>
    </div>
  </section>  <footer>
    © 2025 Barron Smart. All Rights Reserved.
  </footer><a href="https://wa.me/2349136112942" class="whatsapp">Chat on WhatsApp</a>

</body>
</html>

<!---
barron-smart001/barron-smart001 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
