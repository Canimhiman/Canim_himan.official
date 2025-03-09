<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Canim Himan Official</title>
  <link href="https://fonts.googleapis.com/css?family=Roboto:400,700&display=swap" rel="stylesheet">
  <style>
    /* Global Styles */
    body {
      margin: 0;
      font-family: 'Roboto', sans-serif;
      background-color: #111;
      color: #fff;
      line-height: 1.6;
    }
    a {
      color: #e91e63;
      text-decoration: none;
    }
    a:hover {
      text-decoration: underline;
    }
    header, section, footer {
      padding: 20px;
      text-align: center;
    }
    h1, h2 {
      margin: 0 0 20px 0;
    }
    
    /* Header Styles */
    header {
      background: url('https://via.placeholder.com/1920x1080?text=Hero+Image') no-repeat center center/cover;
      height: 100vh;
      position: relative;
    }
    header::after {
      content: "";
      position: absolute;
      top: 0; left: 0;
      right: 0; bottom: 0;
      background: rgba(0, 0, 0, 0.6);
    }
    header nav {
      position: absolute;
      top: 20px;
      right: 20px;
      z-index: 2;
    }
    header nav a {
      margin-left: 20px;
      font-weight: 700;
    }
    header h1 {
      position: relative;
      top: 40vh;
      font-size: 4em;
      color: #e91e63; /* neon pink */
      text-shadow: 2px 2px 10px #000;
      z-index: 2;
    }
    
    /* Section Styles */
    section {
      padding: 60px 20px;
    }
    .music, .videos, .gallery {
      background-color: #222;
      margin: 20px 0;
      padding: 40px 20px;
    }
    
    /* Social Icons */
    .social-icons a {
      margin: 0 10px;
      display: inline-block;
    }
    .social-icons img {
      width: 32px;
      height: 32px;
    }
    
    /* Footer */
    footer {
      background-color: #000;
      padding: 20px;
      color: #888;
      font-size: 0.9em;
    }
    
    /* Responsive adjustments */
    @media (max-width: 768px) {
      header h1 {
        font-size: 3em;
      }
      header nav a {
        margin-left: 10px;
        font-size: 0.9em;
      }
    }
  </style>
</head>
<body>
  <!-- Header / Hero Section -->
  <header>
    <nav>
      <a href="#about">About</a>
      <a href="#music">Music</a>
      <a href="#videos">Videos</a>
      <a href="#gallery">Gallery</a>
      <a href="#contact">Contact</a>
    </nav>
    <h1>CANIM HIMAN</h1>
  </header>
  
  <!-- About Section -->
  <section id="about">
    <h2>About</h2>
    <p>Canim Himan is an emerging Indian rapper and singer breaking boundaries with his unique blend of English rap and soulful melodies. Combining modern energy with global appeal, his music resonates with fans everywhere.</p>
  </section>
  
  <!-- Music Section -->
  <section id="music" class="music">
    <h2>Music</h2>
    <p>Listen to my tracks on SoundCloud and YouTube.</p>
    <p>
      <a href="https://on.soundcloud.com/SWYXUy7peTeAQNHPA" target="_blank">SoundCloud</a> | 
      <a href="https://youtube.com/@himan18?si=J07TM8GFucHKZB0S" target="_blank">YouTube</a>
    </p>
  </section>
  
  <!-- Videos Section -->
  <section id="videos" class="videos">
    <h2>Videos</h2>
    <p>Watch my music videos and live performances.</p>
    <!-- Example Embedded Video (Replace with your own video links) -->
    <iframe width="560" height="315" src="https://www.youtube.com/embed/dQw4w9WgXcQ" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
  </section>
  
  <!-- Gallery Section -->
  <section id="gallery" class="gallery">
    <h2>Gallery</h2>
    <p>A selection of photos curated from my Instagram.</p>
    <!-- Replace these with images from your Instagram that have a Western appeal -->
    <img src="https://via.placeholder.com/300x200?text=Image+1" alt="Gallery Image">
    <img src="https://via.placeholder.com/300x200?text=Image+2" alt="Gallery Image">
    <img src="https://via.placeholder.com/300x200?text=Image+3" alt="Gallery Image">
  </section>
  
  <!-- Contact Section -->
  <section id="contact">
    <h2>Contact</h2>
    <p>For bookings and inquiries, email me at <a href="mailto:contact@canimhimanofficial.com">contact@canimhimanofficial.com</a></p>
  </section>
  
  <!-- Social Icons -->
  <section class="social-icons">
    <a href="https://youtube.com/@himan18?si=J07TM8GFucHKZB0S" target="_blank">
      <img src="https://via.placeholder.com/32?text=YT" alt="YouTube">
    </a>
    <a href="https://www.instagram.com/canim_himan" target="_blank">
      <img src="https://via.placeholder.com/32?text=IG" alt="Instagram">
    </a>
    <a href="https://on.soundcloud.com/SWYXUy7peTeAQNHPA" target="_blank">
      <img src="https://via.placeholder.com/32?text=SC" alt="SoundCloud">
    </a>
  </section>
  
  <!-- Footer -->
  <footer>
    <p>&copy; 2025 Canim Himan Official. All Rights Reserved.</p>
  </footer>
</body>
</html>
