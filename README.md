<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Rodrigo Cartagena</title>
  <style>
    * {
      box-sizing: border-box;
    }
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background-color: white; /* Changed to white */
      color: black; /* Changed to black */
    }
    header {
      background-color: #0f172a;
      color: white;
      padding: 2rem;
      text-align: center;
    }
    nav {
      background-color: #1e293b;
      display: flex;
      justify-content: center;
    }
    nav a {
      color: #f1f5f9;
      padding: 1rem 2rem;
      display: block;
      text-decoration: none;
    }
    nav a:hover {
      background-color: #334155;
    }
    .tab-content {
      display: none;
      padding: 2rem;
      max-width: 900px;
      margin: auto;
    }
    .photo-gallery {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 1rem;
  margin-top: 2rem;
}
    .active {
      display: block;
    }
    .link-section {
      margin-top: 1rem;
    }
    .link-section a {
      display: block;
      margin-bottom: 0.5rem;
      color: #2563eb;
      text-decoration: underline;
    }
    .photo-gallery {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 1rem;
  margin-top: 2rem;
}
.photo-gallery img {
  width: 250px; /* You can change to 200px or 300px if needed */
  height: auto;
  border: none;
  box-shadow: none;
  object-fit: cover;
}
  </style>
</head>
<body>
  <header>
    <h1 style="font-size: 3rem;">Rodrigo Cartagena</h1>
    <p style="font-size: 1.2rem;">Aspiring Engineer | Aviation Enthusiast | Science & Math Explorer</p>
  </header>

  <nav>
    <a href="#" onclick="showTab('home')">Home</a>
    <a href="#" onclick="showTab('cv')">CV</a>
    <a href="#" onclick="showTab('communities')">Communities</a>
    <a href="#" onclick="showTab('webinars')">Webinars</a>
    <a href="#" onclick="showTab('projects')">Projects</a>
    <a href="#" onclick="showTab('blogs')">Blogs</a>
    <a href="#" onclick="showTab('experiences')">Experiences</a>
  </nav>

  <div id="home" class="tab-content active">
    <h2>Welcome</h2>
    <p>Hello! I'm Rodrigo Cartagena, and I always have my head in the clouds...literally! 😊</p>

<p>I grew up in Bolivia, a country with huge mountains, dense jungles, and wide, open spaces that can feel like a different world. Since getting from one place to another wasn't always easy or cheap, airplanes were like magic. They could fly over the Andes, cut through the Amazon, and connect people in just a few hours. That wonder from childhood soon became a genuine passion.</p>

<p>Because of my passion for flying, I immediately became interested in STEM fields, particularly math, physics, and astronomy. I even had the privilege of competing internationally on behalf of Bolivia! The most important thing I've learned from every obstacle is that you can't merely admire airplanes; you must know about them, find ways to improve them, and ensure that flying is affordable and accessible for everyone.</p>

<p>But science isn't everything! I also love music—learning to play the violin and piano has taught me that often the greatest way to grasp the world is via a melody—astronomy, which reminds me how small and magnificent we are in the universe, and chess, which taught me to think a few steps ahead constantly.</p>

<p>I enjoy seeing amazing places, learning about different cultures, and traveling. Every journey motivates me to set higher goals and put in more effort to create a future where flying is accessible, easier, and cleaner.</p>

<p>I appreciate you joining me on this journey to build a world where technology preserves the environment, fosters human connection, and makes advancement accessible to everyone!</p>

<p>Additionally, never forget that the sky is only the beginning!</p>
    <hr />
    <h3>Projects & Links</h3>
    <div class="link-section">
      <!-- Replace with your own links -->
      <a href="https://github.com/yourusername" target="_blank">My GitHub Projects</a>
      <a href="https://www.youtube.com/" target="_blank">YouTube Video – Flight Science Presentation</a>
      <a href="https://drive.google.com/" target="_blank">My Drone Design PDF</a>
    </div>
  </div>

  <div id="cv" class="tab-content">
    <h2>My CV</h2>
    <p> Rodrigo Cartagena</p>

    <h3>Education</h3>
    <ul>
      <li>[School Name] – Grade 9-10</li>
      <li>Math Olympiad Participant</li>
      <li>STEM Camp at Rice University – Summer 2024</li>
    </ul>

    <h3>Skills & Interests</h3>
    <ul>
      <li>Aviation Engineering Basics</li>
      <li>3D Printing & Design</li>
      <li>Algebra, Geometry, Physics</li>
      <li>Science Fairs</li>
    </ul>

    <h3>Languages</h3>
    <ul>
      <li>English – Fluent</li>
      <li>Spanish – Fluent</li>
    </ul>
  </div>

<div id="experiences" class="tab-content">
  <h2>Experiences</h2>

  <div class="photo-gallery">
    <img src="https://github.com/rodrigocartagena/rodrigocartagena/blob/main/00ec715d-4d23-4aa8-a9fe-e08e7309d04c.jpg?raw=true">
    <img src="https://via.placeholder.com/300" alt="Experience 2">
    <img src="https://via.placeholder.com/300" alt="Experience 3">
    <!-- Add more pictures by copying another <img> line -->
  </div>
</div>

  <script>
    function showTab(tabId) {
      const tabs = document.querySelectorAll('.tab-content');
      tabs.forEach(tab => tab.classList.remove('active'));
      document.getElementById(tabId).classList.add('active');
    }
  </script>
</body>
</html>
