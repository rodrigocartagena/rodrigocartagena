<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Rodrigo Cartagena</title>
  <style>
    * { box-sizing: border-box; }
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background-color: white;
      color: black;
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
      flex-wrap: wrap;
    }
    nav a {
      color: #f1f5f9;
      padding: 1rem 2rem;
      display: block;
      text-decoration: none;
    }
    nav a:hover { background-color: #334155; }
    .tab-content {
      display: none;
      padding: 2rem;
      max-width: 900px;
      margin: auto;
    }
    .active { display: block; }
    .link-section { margin-top: 1rem; }
    .link-section a {
      display: block;
      margin-bottom: 0.5rem;
      color: #2563eb;
      text-decoration: underline;
      word-break: break-word;
    }

    /* --- BLOGS styles --- */
    .blog-list {
      list-style: none;
      padding: 0;
      margin: 1rem 0 2rem 0;
      display: grid;
      gap: 1rem;
    }
    .blog-card {
      border: 1px solid #e2e8f0;
      border-radius: 12px;
      padding: 1rem 1.25rem;
      background: #f8fafc;
      transition: transform .12s ease, box-shadow .12s ease;
      cursor: pointer;
    }
    .blog-card:hover {
      transform: translateY(-2px);
      box-shadow: 0 6px 18px rgba(15, 23, 42, 0.12);
      background: #eef2ff;
    }
    .blog-card h4 {
      margin: 0 0 .25rem 0;
      color: #0f172a;
    }
    .blog-card p {
      margin: 0;
      color: #334155;
      font-size: .95rem;
    }
    .blog-article { display: none; }
    .blog-article.active { display: block; }
    .blog-toolbar {
      display: flex;
      align-items: center;
      gap: .75rem;
      margin-bottom: 1rem;
    }
    .btn {
      border: 1px solid #1e293b;
      background: #0f172a;
      color: #fff;
      padding: .5rem .9rem;
      border-radius: 10px;
      cursor: pointer;
    }
    .btn:hover { background: #1e293b; }
    .hint {
      font-size: .9rem;
      color: #475569;
    }
    .info-panel {
      max-width: 900px;
      margin: 12px 0 0 0;
      background: #f8fafc;
      border: 1px solid #e2e8f0;
      border-radius: 12px;
      padding: 1rem;
      display:none;
    }
    .chart-wrap {
      margin: 20px auto;
      background: #f8fafc;
      border: 1px solid #e2e8f0;
      border-radius: 12px;
      padding: 1rem;
    }
    .subtle-hr {
      border: none;
      border-top: 1px solid #e2e8f0;
      margin: 1.5rem 0;
    }

    /* Photo gallery from Experiences kept unchanged */
    .photo-gallery {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 1rem;
      margin-top: 2rem;
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

  <!-- HOME -->
  <div id="home" class="tab-content active">
    <h2>Welcome</h2>
    <p>Hello! I'm Rodrigo Cartagena,</p>
    <p>I grew up in Bolivia, a country with huge mountains, dense jungles, and wide, open spaces that can feel like a different world. Since getting from one place to another wasn't always easy or cheap, airplanes were like magic. They could fly over the Andes, cut through the Amazon, and connect people in just a few hours. That wonder from childhood soon became a genuine passion.</p>
    <p>Because of my passion for flying, I immediately became interested in STEM fields, particularly math, physics, and astronomy. I even had the privilege of competing internationally on behalf of Bolivia! The most important thing I've learned from every obstacle is that you can't merely admire airplanes; you must know about them, find ways to improve them, and ensure that flying is affordable and accessible for everyone.</p>
    <p>But science isn't everything! I also love music—learning to play the violin and piano has taught me that often the greatest way to grasp the world is via a melody—astronomy, which reminds me how small and magnificent we are in the universe, and chess, which taught me to think a few steps ahead constantly.</p>
    <p>I enjoy seeing amazing places, learning about different cultures, and traveling. Every journey motivates me to set higher goals and put in more effort to create a future where flying is accessible, easier, and cleaner.</p>
    <p>I appreciate you joining me on this journey to build a world where technology preserves the environment, fosters human connection, and makes advancement accessible to everyone!</p>
    <p>Additionally, never forget that the sky is only the beginning!</p>
    <hr />
    <h3>Recommended pages:</h3>
    <div class="link-section">
      <a href="https://github.com/yourusername" target="_blank">Not avalible yet!</a>
      <a href="https://www.youtube.com/" target="_blank">Not avalible yet!</a>
      <a href="https://drive.google.com/" target="_blank">Not avalible yet!</a>
    </div>
  </div>

  <!-- CV -->
  <div id="cv" class="tab-content">
    <h1>My CV</h1>
    <h3>My contact information:</h3>
    <ul>
      <li>Email: rodrigocartagenav10@gmail.com </li>
      <li>Let's connect on <a href="https://www.linkedin.com/in/rodrigo-cartagena-81494a1b5/?msgControlName=view_message_button&msgConversationId=2-MjQxMmRlZjItZTE5OC00ZTQxLTlhMWItMjRlNjczNThhZmY0XzAxMg%3D%3D&msgOverlay=true" target="_blank" rel="noopener">LinkedIn</a></li>
    </ul>
    <hr/>
    <h3>Education</h3>
    <ul>
      <li>Jordan High School, Katy TX, USA – Student 10th Grade</li>
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
      <li><a href="https://katytimes.com/stories/local-students-attend-award-winning-tapia-camps-at-rice-university,86490" target="_blank" rel="noopener">TAPIA STEM CAMP</a>, Rice University, 2024</li>
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

  <!-- COMMUNITIES -->
  <div id="communities" class="tab-content">
    <h2>Communities</h2>
    <h3><strong>Canguro Matematico - Bolivia</strong></h3>
    <p>It is the Bolivian branch of Kangourou sans Frontières, the world's most significant international mathematics competition. The Sociedad Boliviana de Educación Matemática and the Olimpiada Matemática Boliviana organize it to encourage mathematical thinking and problem-solving skills in students from third grade in elementary school to sixth grade in secondary school.</p>

    <h3><strong>Team Infinitum</strong></h3>
    <p>A reputable organization for its excellence in preparing young people for national and worldwide arithmetic competitions. Their programs focus on advanced mathematical theories, logical thinking, and problem-solving techniques to give participants excellent comprehension and appreciation of mathematics.</p>

    <h3><strong>AstroCBA</strong></h3>
    <img src="https://github.com/rodrigocartagena/rodrigocartagena/blob/main/Jaha.png?raw=true" alt="AstroCBA Logo" style="width: 200px; vertical-align: middle; margin-left: 10px;">
    <p>The Bolivian American Center (CBA) in Santa Cruz, Bolivia, is home to this young astronomy group. They aim to pique children's and teenagers' interest in and enthusiasm for the stars! They host astronomy workshops, telescope evenings, and even departmental astronomy Olympiads for younger students, among other entertaining and instructive events. Additionally, AstroCBA is pleased to send students to compete internationally, such as the Latin American Astronomy Olympiads, on behalf of Bolivia.</p>
    <p>Fundamentally, AstroCBA's goal is to introduce young people to the cosmos one starry night at a time.</p>

    <h3><strong>Virtual Flight School Bolivia (EVV)</strong></h3>
    <p>A pioneer organization in Bolivia for online aviation education was established in 2022 and uses cutting-edge flying simulators, such as Virtual Reality (VR) technology, to provide theoretical and hands-on training programs. Through its courses, students can obtain experience in a highly realistic setting before flying real aircraft, ranging from introductory levels for kids to programs for private and commercial pilots. </p>
  </div>

  <!-- WEBINARS -->
  <div id="webinars" class="tab-content">
    <h2>Webinars</h2>
    <h3>Black Holes</h3>
    <p>In my webinar about black holes, I explained how these mysterious giants can absorb and change the energy and matter of nearby stars to grow even bigger. I used simple examples and cool pictures to make it easy for everybody to understand. I loved talking about one of the most incredible things about the world, and I hope it makes more people want to stay interested and keep exploring space.</p>
    <hr>
    <a href="https://www.facebook.com/watch/?v=1062135828030609" target="_blank" rel="noopener">
      <img src="https://github.com/rodrigocartagena/rodrigocartagena/blob/main/Screenshot%202025-04-27%20235230.png?raw=true" alt="Black Hole Webinar" style="max-width: 100%; height: auto; display: block; margin: 20px auto;">
    </a>
  </div>

  <!-- PROJECTS -->
  <div id="projects" class="tab-content">
    <h2>Projects</h2>
    <h3>Sky Match: Fighter Jets</h3>
    <p>It is a matching pairs game, which requires players to find and identify concealed cards, recognizing the name, model, and key features of the aircraft. This improves working memory and focus, which decline with age but can be maintained with mental training. It also boosts visual and spatial memory, which helps the brain establish new neural connections and build cognitive resilience. Moreover, improving or winning boosts self-esteem and delight, making it more than a mental workout.</p>
    <hr>
    <h3>Blue Sky Builders</h3>
    <p>Reimagining aviation's future is the goal of this game, not merely building airports or flying planes! Players learn sustainability tactics and enjoy competition and collaboration by making wise choices to cut CO₂ emissions. It's a fun, hands-on method to promote greener skies and demonstrate that innovation and sustainability coexist. Every move contributes to a better tomorrow.</p>
    <hr>
    <h3>3D Printer</h3>
    <p>My favorite tool is my 3D printer! I use it to build scale aviation models and custom parts to realize my ideas. Designing something on a computer and seeing it evolve is fascinating. My 3D printing projects teach me about aerodynamics, engineering, and problem-solving.</p>
    <img src="https://github.com/rodrigocartagena/rodrigocartagena/blob/main/Pronectss%203d%20print.%20eh.png?raw=true"  style="width: 300px; vertical-align: middle; margin-bottom: 10px;">
    <hr>
  </div>

  <!-- BLOGS (improved) -->
  <div id="blogs" class="tab-content">
    <h2>Blogs</h2>

    <!-- List view -->
    <ul id="blogList" class="blog-list">
      <li class="blog-card" onclick="openBlogArticle('woh')">
        <h4>Wings Over Houston Air Show</h4>
        <p>Photos, highlights, and notes from the show.</p>
      </li>
      <li class="blog-card" onclick="openBlogArticle('skyward')">
        <h4>Skyward Emissions: How Aviation Fuel Use Has Changed — and What It Means for Climate Change</h4>
        <p>Data, context, and what to watch in decarbonizing flight.</p>
      </li>
    </ul>

    <!-- Article: Wings Over Houston -->
    <div id="blog-woh" class="blog-article">
      <div class="blog-toolbar">
        <button class="btn" onclick="returnToBlogList()">← Back to Blogs</button>
        <span class="hint">Event recap and resources</span>
      </div>

      <h3>Wings Over Houston Air Show</h3>
      <p>
        Highlights from the show, favorite aircraft, and learning takeaways. (Add your write-up and photos here.)
      </p>

      <!-- Keep your existing example link (replace with your real URL/image when ready) -->
      <a href="https://your-link-here.com" target="_blank" rel="noopener">
        <img src="https://your-image-link-here.com/image.jpg" alt="Wings Over Houston Airshow" style="max-width: 100%; height: auto; display: block; margin: 20px auto;">
      </a>
    </div>

    <!-- Article: Skyward Emissions -->
    <div id="blog-skyward" class="blog-article">
      <div class="blog-toolbar">
        <button class="btn" onclick="returnToBlogList()">← Back to Blogs</button>
        <span class="hint">Long read · with interactive chart</span>
      </div>

      <h3>Skyward Emissions: How Aviation Fuel Use Has Changed — and What It Means for Climate Change</h3>

      <p><em>Aviation is a small share of global energy use but punches above its weight in climate impact.</em> Over the last decades, new aircraft and operations have made flying far more fuel-efficient. Still, global jet fuel consumption and the climate footprint of the sector remain large — and the industry faces a steep challenge to decarbonize at the scale and speed climate science demands.</p>

      <h4>What the data show</h4>
      <p>Global jet fuel demand fell during the COVID shock but rebounded quickly as travel recovered. The <a href="https://www.iea.org/data-and-statistics/charts/global-aviation-fuel-consumption-2013-2021" target="_blank" rel="noopener">IEA’s historical charts</a> show year-by-year jet-fuel consumption trends (2013–2021) and are a good starting point for plotting recent recovery and pre-pandemic growth.</p>

      <p>Longer-term efficiency gains are real: analyses by the <a href="https://theicct.org/publication/aviation-global-jet-aircraft-fuel-burn-jan25/" target="_blank" rel="noopener">ICCT</a> find the average fuel burn of newly delivered jets decreased by roughly <strong>43%</strong> from 1970 to 2024, averaging about a 1% per-year reduction in block fuel intensity. Those gains come from better engines, lighter airframes, and improved operations — but improvements have slowed recently.</p>

      <p>Yet despite efficiency gains, sustainable fuels and zero-carbon propulsion are still tiny in the overall fuel mix. The <a href="https://www.iea.org/reports/aviation" target="_blank" rel="noopener">IEA</a> notes SAFs account for well under 1% of aviation fuel consumed today — meaning nearly all jet fuel burned is fossil kerosene.</p>

      <p>Finally, the policy and industrial picture is mixed: <a href="https://www.icao.int/environmental-protection/CORSIA/Pages/default.aspx" target="_blank" rel="noopener">ICAO’s CORSIA mechanism</a> and airline pledges aim for net-zero by 2050, but reporting and offset integrity remain contested; recent <a href="https://www.reuters.com/business/sustainable-business/exclusive-airlines-sustainable-fuel-plans-face-delays-cancellations-data-shows-2023-09-14/" target="_blank" rel="noopener">reporting</a> has shown many announced SAF projects have stalled or failed, limiting near-term supply growth.</p>

      <h4>Why aviation matters for climate</h4>
      <p><strong>Aviation emissions are unique:</strong> aircraft emit CO₂ at altitude, and contrails and other non-CO₂ effects (NOₓ, contrail cirrus) multiply their warming impact. Even if aviation stays a single-digit percentage of global CO₂ today, rapid post-pandemic traffic growth without meaningful fuel replacement would push cumulative warming higher — a problem climate models flag as significant for reaching Paris targets.</p>

      <!-- INTERACTIVE CHART (between Why... and Solutions...) -->
      <div class="chart-wrap">
        <canvas id="fuelChart" style="max-width: 860px; margin: 0 auto; display: block;"></canvas>
        <div id="eventInfo" class="info-panel"></div>
      </div>

      <h4>Solutions & what big companies are doing</h4>

      <h5>Sustainable Aviation Fuels (SAF)</h5>
      <p><strong>SAF</strong> (HEFA, waste-to-jet, power-to-liquid) can cut lifecycle CO₂ vs fossil jet fuel, but supply is tiny and production is expensive. Airlines and oil/energy firms have launched SAF partnerships and offtake agreements (for example <a href="https://www.united.com/en/us/fly/about/sustainability" target="_blank" rel="noopener">United’s SAF program</a>), but many announced projects have been delayed or canceled, and <a href="https://www.reuters.com/business/sustainable-business/exclusive-airlines-sustainable-fuel-plans-face-delays-cancellations-data-shows-2023-09-14/" target="_blank" rel="noopener">independent reporting</a> shows only a small fraction of announced SAF plants are operational.</p>

      <h5>Hydrogen and fuel cells / combustion</h5>
      <p>Aircraft makers are exploring hydrogen long-term. <a href="https://www.airbus.com/en/innovation/zero-emission/hydrogen/zeroe" target="_blank" rel="noopener">Airbus</a> has public ZEROe hydrogen concept work and continues R&D into hydrogen fuel-cell and turbine concepts; startups like <a href="https://www.zeroavia.com/" target="_blank" rel="noopener">ZeroAvia</a> are developing hydrogen powertrains, though the commercial path to scale is uncertain.</p>

      <h4>Future work</h4>
      <ul>
        <li><a href="https://www.iea.org/reports/aviation" target="_blank" rel="noopener">SAF scale-up</a> &amp; feedstock availability tracking</li>
        <li><a href="https://theicct.org/publication/aviation-global-jet-aircraft-fuel-burn-jan25/" target="_blank" rel="noopener">Aircraft efficiency standards</a> (ICCT, ICAO)</li>
        <li>Hydrogen feasibility trials &amp; infrastructure buildout</li>
        <li>Policy &amp; mandates (EU SAF mandate, US incentives)</li>
      </ul>

      <h5>References</h5>
      <ul>
        <li><a href="https://www.iea.org/data-and-statistics/charts/global-aviation-fuel-consumption-2013-2021" target="_blank" rel="noopener">IEA Global Aviation Fuel Consumption</a></li>
        <li><a href="https://theicct.org/publication/aviation-global-jet-aircraft-fuel-burn-jan25/" target="_blank" rel="noopener">ICCT Aircraft Fuel Burn Trends</a></li>
        <li><a href="https://www.icao.int/environmental-protection/CORSIA/Pages/default.aspx" target="_blank" rel="noopener">ICAO CORSIA</a></li>
        <li><a href="https://www.reuters.com/business/sustainable-business/exclusive-airlines-sustainable-fuel-plans-face-delays-cancellations-data-shows-2023-09-14/" target="_blank" rel="noopener">Reuters SAF Project Delays</a></li>
        <li><a href="https://www.united.com/en/us/fly/about/sustainability" target="_blank" rel="noopener">United Airlines SAF Program</a></li>
        <li><a href="https://www.airbus.com/en/innovation/zero-emission/hydrogen/zeroe" target="_blank" rel="noopener">Airbus ZEROe Project</a></li>
        <li><a href="https://www.zeroavia.com/" target="_blank" rel="noopener">ZeroAvia Hydrogen Aircraft</a></li>
      </ul>
    </div>
  </div>

  <!-- EXPERIENCES -->
  <div id="experiences" class="tab-content">
    <h2>Experiences</h2>
    <div class="photo-gallery">
      <img src="https://github.com/rodrigocartagena/rodrigocartagena/blob/main/00ec715d-4d23-4aa8-a9fe-e08e7309d04c.jpg?raw=true" alt="Experience 1">
      <img src="https://github.com/rodrigocartagena/rodrigocartagena/blob/main/Tu1.jpg?raw=true" alt="Experience 2">
      <img src="https://github.com/rodrigocartagena/rodrigocartagena/blob/main/Tu2.jpg?raw=true" alt="Experience 3">
      <img src="https://github.com/rodrigocartagena/rodrigocartagena/blob/main/Tu8.jpg?raw=true" alt="Experience 4">
      <img src="https://github.com/rodrigocartagena/rodrigocartagena/blob/main/Tu4.jpg?raw=true" alt="Experience 5">
      <img src="https://github.com/rodrigocartagena/rodrigocartagena/blob/main/Tu6.jpg?raw=true" alt="Experience 6">
      <img src="https://github.com/rodrigocartagena/rodrigocartagena/blob/main/Tu7.jpg?raw=true" alt="Experience 7">
      <img src="https://github.com/rodrigocartagena/rodrigocartagena/blob/main/Tu9.jpg?raw=true" alt="Experience 8">
    </div>
  </div>

  <!-- Scripts -->
  <script>
    function showTab(tabId) {
      const tabs = document.querySelectorAll('.tab-content');
      tabs.forEach(tab => tab.classList.remove('active'));
      document.getElementById(tabId).classList.add('active');

      // When returning to Blogs list, ensure list view shows and articles hide
      if (tabId === 'blogs') {
        returnToBlogList();
      }
    }

    // BLOG view controls
    function openBlogArticle(which) {
      document.getElementById('blogList').style.display = 'none';
      document.querySelectorAll('.blog-article').forEach(el => el.classList.remove('active'));
      const target = document.getElementById(which === 'skyward' ? 'blog-skyward' : 'blog-woh');
      target.classList.add('active');

      // Lazy-init chart when Skyward opens
      if (which === 'skyward') {
        initFuelChart();
      }
    }

    function returnToBlogList() {
      document.getElementById('blogList').style.display = 'grid';
      document.querySelectorAll('.blog-article').forEach(el => el.classList.remove('active'));
      // Clean up any info panel state
      const info = document.getElementById('eventInfo');
      if (info) { info.style.display = 'none'; info.innerHTML = ''; }
    }
  </script>

  <!-- Chart.js (needed for the interactive line chart in Skyward article) -->
  <script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
  <script>
    let skyChart;

    function initFuelChart() {
      const canvas = document.getElementById('fuelChart');
      if (!canvas) return;

      const ctx = canvas.getContext('2d');

      // Destroy if re-entering the article to avoid duplicate charts
      if (skyChart) {
        skyChart.destroy();
        skyChart = null;
      }

      // Decadal + key-event granularity (illustrative values)
      const labels = [1970, 1980, 1990, 2001, 2008, 2013, 2019, 2020, 2024];
      const values = [150, 180, 200, 195, 185, 220, 245, 160, 240]; // Mt (example series)

      const eventDetails = {
        1970: "First-gen wide-bodies expand capacity; higher fuel burn per passenger than today.",
        1980: "Twin-engine ETOPS and efficiency gains begin to spread.",
        1990: "Operational improvements & higher load factors reduce per-seat intensity.",
        2001: "9/11 demand shock; security changes; gradual recovery afterward.",
        2008: "Oil price spike + Great Financial Crisis depress traffic temporarily.",
        2013: "Recovery continues; LCC growth & hub-and-spoke efficiency raise total demand.",
        2019: "Pre-COVID peak traffic; efficiency improves but total fuel still high.",
        2020: "COVID shock collapses demand; historic one-year drop in fuel burn.",
        2024: "Rebound near/above prior highs; SAF still <1% of fuel; contrails/non-CO₂ remain concerns."
      };

      skyChart = new Chart(ctx, {
        type: 'line',
        data: {
          labels,
          datasets: [{
            label: 'Global Aviation Fuel Consumption (Mt)',
            data: values,
            fill: false,
            borderColor: '#2563eb',
            backgroundColor: '#1e40af',
            tension: 0.2,
            pointRadius: 5,
            pointHoverRadius: 7
          }]
        },
        options: {
          responsive: true,
          maintainAspectRatio: true,
          plugins: {
            tooltip: {
              callbacks: {
                afterLabel: function(context) {
                  const year = context.label;
                  return eventDetails[year] ? "Event: " + eventDetails[year] : "";
                }
              }
            },
            legend: { display: true }
          },
          scales: {
            x: { ticks: { color: '#0f172a' }, grid: { color: '#e2e8f0' } },
            y: {
              beginAtZero: false,
              title: { display: true, text: 'Million tonnes (Mt)' },
              ticks: { color: '#0f172a' },
              grid: { color: '#e2e8f0' }
            }
          },
          onClick: (evt, elements) => {
            const info = document.getElementById('eventInfo');
            const points = skyChart.getElementsAtEventForMode(evt, 'nearest', { intersect: true }, true);
            if (points.length) {
              const idx = points[0].index;
              const year = labels[idx];
              const value = values[idx];
              const detail = eventDetails[year] || 'No event data available.';
              info.innerHTML = `
                <strong>${year}</strong> — ~${value} Mt estimated fuel consumption.<br/>
                <em>Context:</em> ${detail}<br/>
                <span style="color:#334155">Higher total fuel burn contributes to CO₂ and non-CO₂ effects (e.g., contrails), amplifying climate impact.</span>
              `;
              info.style.display = 'block';
            }
          }
        }
      });
    }
  </script>
</body>
</html>
