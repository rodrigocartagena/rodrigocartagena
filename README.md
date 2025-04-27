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
    <h2>Rodrigo Cartagena </h2>
    <h3>My CV</h3>
    <h3>My contact information:</h3>
    <ul>
      <li>Email: rodrigocartagenav10@gmail.com </li>
    </ul>
    <h3>Education</h3>
    <ul>
      <li>Jordan High School, Katy TX, USA – Student 9th Grade</li>
      <li>Seven Lakes Junior High, Katy TX, USA</li>
      <li>Alemán-Deutsche Schule Santa Cruz, Bolivia</li>
    </ul>
  <hr/>
    <h3>Awards and Honors</h3>
    <h3>International Awards</h3>
    <ul>
      <li>Bronze Medal, Copernicus Olympiad Mathematics – New York, 2024</li>
       <li>Honorable Mention, AMC 8 – USA, 2024</li>
      <li>Silver Medal, Copernicus Olympiad Astronomy and Physics – Houston, Texas, 2024</li>
      <li>Gold Medal, International Mathematics Olympiad Challenge (IMOC)</li>
      <li>Bronze Medal, International Geometry Olympiad Challenge (IGOC)</li>
      <li>Bronze Medal, Galileo International Astronomy Olympiad (GIAO)</li>
      <li>Honorable Mention, International Trigonometry Olympiad (ITO) – Indonesia, 2023</li>
      <li>Honorable Mention, Young Mathematicians Tournament</li>
      <li>Silver Medal, TalentGO – Peru, 2021</li>
      <li>Gold Medal, Mateam – Mexico, 2021</li>
    </ul>
  <h3>Bolivian Awards</h3>
  <ul>
    <li>Senate Chamber Tribute, Bolivia, 2024</li>
    <li>Silver Medal, Mathematical Kangaroo – Santa Cruz, Bolivia, 2023</li>
    <li>Honorable Mention, AMC 8 – Bolivia-USA, 2023</li>
    <li>Honorable Mention, EULER</li>
    <li>Silver Medal, Physics, Plurinational Student Scientific Olympiad of Bolivia (OCEPB) – Cochabamba, Bolivia, 2022</li>
    <li>Silver Medal, Physics, Plurinational Student Scientific Olympiad of Bolivia (OCEPB) – Santa Cruz, Bolivia, 2023</li>
  </ul>
  <h3>Regional Awards</h3>
  <ul>
    <li>Silver Medal, UPSA-MAT – Santa Cruz, Bolivia, 2022</li>
  </ul>
  <hr/>
  <h3>Languages</h3>
  <ul>
    <li>English (Advanced) | Spanish (Native) | Guaraní-Indigenous (Basic) | German (Intermediate) | Portuguese (Basic)</li>
  </ul>
  <hr>
  <h3>Extracurricular Activities</h3>
  <ul>
    <li>TAPIA STEAM CAMP, Rice University, 2024</li>
    <li>AE360 – Principles of Aerodynamics, Washington Youth Rocketry, 2024</li>
    <li>Engineering: Solving Real-World Problems, Rice University, 2025</li>
  </ul>
  <hr>
  <h3>Hobbies and Interests</h3>
  <ul>
    <li>Violin | Piano | Astronomy Club | Swimming | Tennis | Basketball</li>
  </ul>
  <hr>
</div>
<div id="communities" class="tab-content">
  <h2>Communities</h2>

  <h3><strong>Canguro Matematico - Bolivia</strong></h3>
  <p>It is the Bolivian branch of Kangourou sans Frontières, the world's most significant international mathematics competition. The Sociedad Boliviana de Educación Matemática and the Olimpiada Matemática Boliviana organize it to encourage mathematical thinking and problem-solving skills in students from third grade in elementary school to sixth grade in secondary school.</p>

  <h3><strong>Team Infinitum</strong></h3>
  <p>A reputable organization for its excellence in preparing young people for national and worldwide arithmetic competitions. Their programs focus on advanced mathematical theories, logical thinking, and problem-solving techniques to give participants excellent comprehension and appreciation of mathematics.</p>

  <h3>
  <strong>
    AstroCBA
  </strong>
</h3>  <img src="https://github.com/rodrigocartagena/rodrigocartagena/blob/main/Jaha.png?raw=true" alt="AstroCBA Logo" style="width: 200px; horizontal-align: middle; margin-left: 10px;">
  <p>The Bolivian American Center (CBA) in Santa Cruz, Bolivia, is home to this young astronomy group. They aim to pique children's and teenagers' interest in and enthusiasm for the stars! They host astronomy workshops, telescope evenings, and even departmental astronomy Olympiads for younger students, among other entertaining and instructive events. Additionally, AstroCBA is pleased to send students to compete internationally, such as the Latin American Astronomy Olympiads, on behalf of Bolivia.</p>

  <p>Fundamentally, AstroCBA's goal is to introduce young people to the cosmos one starry night at a time.</p>
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
