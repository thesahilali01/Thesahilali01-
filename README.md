
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <title>The Sahil Ali | Official Portfolio</title>

  <meta name="description" content="Official website of Sahil Ali. B.Com BFSI student, Veyro project builder and enthusiast in equity markets, crypto and technology.">

  <meta name="keywords" content="Sahil Ali, The Sahil Ali, Veyro, B.Com BFSI, Equity, Crypto, Technology">

  <meta name="author" content="Sahil Ali">
  <meta name="theme-color" content="#10131c">

  <meta property="og:title" content="The Sahil Ali | Official Website">
  <meta property="og:description" content="Explore the projects, interests and digital presence of Sahil Ali.">
  <meta property="og:type" content="website">

  <script type="application/ld+json">
  {
    "@context": "https://schema.org",
    "@type": "Person",
    "name": "Sahil Ali",
    "alternateName": "The Sahil Ali",
    "description": "B.Com BFSI student, builder of Veyro and enthusiast in equity markets, cryptocurrency and technology.",
    "sameAs": [
      "https://github.com/thesahilali01",
      "https://www.linkedin.com/in/thesahilali01/",
      "https://www.instagram.com/thesahilali01/",
      "https://x.com/thesahilali01"
    ]
  }
  </script>

  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    html {
      scroll-behavior: smooth;
    }

    body {
      background: #10131c;
      color: #f4f5f8;
      font-family: Arial, sans-serif;
      line-height: 1.7;
    }

    a {
      color: inherit;
      text-decoration: none;
    }

    .container {
      width: min(1100px, 90%);
      margin: auto;
    }

    header {
      padding: 24px 0;
      border-bottom: 1px solid #292d39;
    }

    nav {
      display: flex;
      justify-content: space-between;
      align-items: center;
      gap: 20px;
    }

    .logo {
      font-size: 21px;
      font-weight: 800;
      letter-spacing: 1px;
    }

    .logo span {
      color: #a5a8ff;
    }

    nav a {
      color: #c2c5d1;
      font-size: 14px;
      margin-left: 20px;
    }

    nav a:hover {
      color: #a5a8ff;
    }

    .hero {
      padding: 110px 0 90px;
      text-align: center;
    }

    .tag {
      display: inline-block;
      border: 1px solid #41465c;
      color: #b6b9ff;
      padding: 7px 17px;
      border-radius: 30px;
      font-size: 12px;
      letter-spacing: 2px;
      margin-bottom: 25px;
    }

    .hero h1 {
      font-size: clamp(42px, 8vw, 76px);
      line-height: 1.1;
      letter-spacing: -3px;
      margin-bottom: 22px;
    }

    .hero h1 span {
      color: #a5a8ff;
    }

    .hero p {
      color: #aeb2c1;
      max-width: 650px;
      margin: auto;
      font-size: 17px;
    }

    .buttons {
      display: flex;
      justify-content: center;
      gap: 14px;
      flex-wrap: wrap;
      margin-top: 32px;
    }

    .btn {
      padding: 12px 24px;
      border-radius: 9px;
      font-weight: 700;
      font-size: 14px;
      border: 1px solid #555a75;
      transition: .2s;
    }

    .primary {
      background: #a5a8ff;
      color: #10131c;
      border-color: #a5a8ff;
    }

    .btn:hover {
      transform: translateY(-3px);
    }

    section {
      padding: 70px 0;
    }

    .section-title {
      font-size: 30px;
      margin-bottom: 12px;
    }

    .section-subtitle {
      color: #969bad;
      margin-bottom: 30px;
    }

    .card {
      background: #191d29;
      border: 1px solid #2c3140;
      padding: 28px;
      border-radius: 16px;
    }

    .card h3 {
      margin-bottom: 12px;
      color: #c1c3ff;
    }

    .card p {
      color: #aeb2c1;
    }

    .grid {
      display: grid;
      grid-template-columns: repeat(2, 1fr);
      gap: 20px;
    }

    .social-grid {
      display: grid;
      grid-template-columns: repeat(4, 1fr);
      gap: 14px;
    }

    .social {
      display: block;
      text-align: center;
      background: #191d29;
      border: 1px solid #303548;
      padding: 20px 10px;
      border-radius: 12px;
      transition: .2s;
    }

    .social:hover {
      border-color: #a5a8ff;
      transform: translateY(-4px);
    }

    .social strong {
      display: block;
      margin-bottom: 5px;
    }

    .social small {
      color: #969bad;
    }

    .project {
      border: 1px solid #555a75;
      background: linear-gradient(135deg, #191d29, #252741);
    }

    .project-label {
      color: #a5a8ff;
      font-size: 12px;
      letter-spacing: 2px;
      margin-bottom: 12px;
    }

    .project h3 {
      font-size: 30px;
    }

    .project a {
      display: inline-block;
      margin-top: 20px;
      color: #b8baff;
      font-weight: bold;
    }

    footer {
      text-align: center;
      padding: 30px 0;
      border-top: 1px solid #292d39;
      color: #858a9c;
      font-size: 13px;
    }

    @media(max-width: 650px) {
      nav {
        flex-direction: column;
      }

      nav a {
        margin: 0 7px;
      }

      .hero {
        padding: 80px 0 65px;
      }

      .grid {
        grid-template-columns: 1fr;
      }

      .social-grid {
        grid-template-columns: repeat(2, 1fr);
      }

      .hero h1 {
        letter-spacing: -2px;
      }
    }
  </style>
</head>

<body>

<header>
  <div class="container">
    <nav>
      <a class="logo" href="#">THE <span>SAHIL ALI.</span></a>

      <div>
        <a href="#about">About</a>
        <a href="#projects">Projects</a>
        <a href="#social">Connect</a>
      </div>
    </nav>
  </div>
</header>

<main>

  <div class="hero">
    <div class="container">
      <div class="tag">OFFICIAL PERSONAL PORTFOLIO</div>

      <h1>I'm <span>Sahil Ali.</span></h1>

      <p>
        Exploring finance, equity markets, cryptocurrency
        and technology. Building ideas into meaningful projects.
      </p>

      <div class="buttons">
        <a href="#about" class="btn primary">Discover More</a>
        <a href="#social" class="btn">Connect With Me</a>
      </div>
    </div>
  </div>

  <section id="about">
    <div class="container">
      <h2 class="section-title">About Me</h2>
      <p class="section-subtitle">A little introduction.</p>

      <div class="card">
        <h3>Sahil Ali</h3>
        <p>
          I am currently pursuing B.Com BFSI and learning
          about financial markets, equity analysis,
          cryptocurrency and technology.

          I enjoy exploring new ideas, developing digital
          projects and continuously improving my skills.
        </p>
      </div>
    </div>
  </section>

  <section id="projects">
    <div class="container">
      <h2 class="section-title">My Projects</h2>
      <p class="section-subtitle">Ideas, learning and building.</p>

      <div class="card project">
        <div class="project-label">FEATURED PROJECT</div>
        <h3>VEYRO</h3>
        <p>Smart Trading Tools for Better Discipline.</p>
        <p>
          A project focused on trading tools and
          helping users develop better trading discipline.
        </p>

        <a href="https://thesahilali01.github.io/Veyro-/"
           target="_blank" rel="noopener noreferrer">
          Explore Veyro →
        </a>
      </div>
    </div>
  </section>

  <section>
    <div class="container">
      <h2 class="section-title">Education & Interests</h2>

      <div class="grid">
        <div class="card">
          <h3>Education</h3>
          <p>B.Com BFSI</p>
          <p>Currently learning</p>
        </div>

        <div class="card">
          <h3>Interests</h3>
          <p>Equity Markets</p>
          <p>Cryptocurrency</p>
          <p>Technology & Web Development</p>
        </div>
      </div>
    </div>
  </section>

  <section id="social">
    <div class="container">
      <h2 class="section-title">Find Me Online</h2>
      <p class="section-subtitle">
        Connect with my official profiles.
      </p>

      <div class="social-grid">

        <a class="social"
           href="https://github.com/thesahilali01"
           target="_blank" rel="noopener noreferrer">
          <strong>GitHub</strong>
          <small>Projects</small>
        </a>

        <a class="social"
           href="https://www.linkedin.com/in/thesahilali01/"
           target="_blank" rel="noopener noreferrer">
          <strong>LinkedIn</strong>
          <small>Professional</small>
        </a>

        <a class="social"
           href="https://www.instagram.com/thesahilali01/"
           target="_blank" rel="noopener noreferrer">
          <strong>Instagram</strong>
          <small>Social</small>
        </a>

        <a class="social"
           href="https://x.com/thesahilali01"
           target="_blank" rel="noopener noreferrer">
          <strong>X / Twitter</strong>
          <small>Updates</small>
        </a>

      </div>
    </div>
  </section>

</main>

<footer>
  <div class="container">
    © <span id="year"></span> Sahil Ali. All rights reserved.
    <br>
    Built with purpose.
  </div>
</footer>

<script>
  document.getElementById("year").textContent =
    new Date().getFullYear();
</script>

</body>
</html>

