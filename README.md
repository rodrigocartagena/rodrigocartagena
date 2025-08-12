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
    <p>I grew up in Bolivia, a country with huge mountains, dense jungles...</p>
    <!-- trimmed for brevity, keep your original text here -->
  </div>

  <!-- CV -->
  <div id="cv" class="tab-content">
    <!-- Your full CV section content -->
  </div>

  <!-- COMMUNITIES -->
  <div id="communities" class="tab-content">
    <!-- Your full communities content -->
  </div>

  <!-- WEBINARS -->
  <div id="webinars" class="tab-content">
    <!-- Your webinars section -->
  </div>

  <!-- PROJECTS -->
  <div id="projects" class="tab-content">
    <!-- Your projects section -->
  </div>

  <!-- BLOGS -->
  <div id="blogs" class="tab-content">
    <h2>Blogs</h2>
    <ul>
      <li><a href="#" onclick="showTab('skywardArticle')">Skyward Emissions: How Aviation Fuel Use Has Changed — and What It Means for Climate Change</a></li>
      <li><a href="#" onclick="showTab('houstonAirshow')">Wings Over Houston Airshow - Blue Angels</a></li>
    </ul>
  </div>

  <!-- SKYWARD ARTICLE -->
  <div id="skywardArticle" class="tab-content">
    <a href="#" onclick="showTab('blogs')">← Back to Blogs</a>
    <h2>Skyward Emissions: How Aviation Fuel Use Has Changed — and What It Means for Climate Change</h2>
    <p>Aviation is a small share of global energy use but punches above its weight...</p>
    <h3>What the data show</h3>
    <p>Global jet fuel demand fell during the COVID shock... <a href="https://www.iea.org/data-and-statistics/charts/global-aviation-fuel-consumption-2013-2021" target="_blank">IEA Data</a></p>
    <p>Longer-term efficiency gains are real... <a href="https://theicct.org/publication/aviation-global-jet-aircraft-fuel-burn-jan25/" target="_blank">ICCT Report</a></p>
    <p>Yet despite efficiency gains... <a href="https://www.iea.org/reports/aviation" target="_blank">IEA SAF Data</a></p>
    <p>Finally, the policy and industrial picture... <a href="https://www.icao.int/environmental-protection/CORSIA/Pages/default.aspx" target="_blank">ICAO CORSIA</a></p>

    <h3>Why aviation matters for climate</h3>
    <p>Aviation emissions are unique...</p>

    <canvas id="fuelChart" style="max-width:800px; margin: 20px auto; display:block;"></canvas>
    <div id="eventInfo" style="max-width:800px; margin:auto; background:#f8f9fa; padding:1rem; border-radius:8px; display:none;"></div>

    <h3>Solutions & what big companies are doing</h3>
    <p>SAF can cut lifecycle CO₂... <a href="https://www.united.com/en/us/fly/about/sustainability" target="_blank">United SAF Program</a></p>
    <p>Hydrogen aircraft research... <a href="https://www.airbus.com/en/innovation/zero-emission/hydrogen/zeroe" target="_blank">Airbus ZEROe</a></p>

    <h3>References</h3>
    <ul>
      <li><a href="https://www.iea.org/data-and-statistics/charts/global-aviation-fuel-consumption-2013-2021" target="_blank">IEA Global Aviation Fuel Consumption</a></li>
      <li><a href="https://theicct.org/publication/aviation-global-jet-aircraft-fuel-burn-jan25/" target="_blank">ICCT Aircraft Fuel Burn Trends</a></li>
      <li><a href="https://www.icao.int/environmental-protection/CORSIA/Pages/default.aspx" target="_blank">ICAO CORSIA</a></li>
      <li><a href="https://www.united.com/en/us/fly/about/sustainability" target="_blank">United Airlines SAF Program</a></li>
      <li><a href="https://www.airbus.com/en/innovation/zero-emission/hydrogen/zeroe" target="_blank">Airbus ZEROe Project</a></li>
    </ul>
  </div>

  <!-- HOUSTON AIRSHOW ARTICLE -->
  <div id="houstonAirshow" class="tab-content">
    <a href="#" onclick="showTab('blogs')">← Back to Blogs</a>
    <h2>Wings Over Houston Airshow - Blue Angels</h2>
    <p>Jet engines roar at Ellington Airport's Wings Over Houston Airshow every fall when the U.S. Navy Blue Angels perform...</p>
    <p>The Blue Angels' performance is the airshow's highlight...</p>
  </div>

  <!-- EXPERIENCES -->
  <div id="experiences" class="tab-content">
    <!-- Your experiences section -->
  </div>

  <script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
  <script>
    function showTab(tabId) {
      const tabs = document.querySelectorAll('.tab-content');
      tabs.forEach(tab => tab.classList.remove('active'));
      document.getElementById(tabId).classList.add('active');
    }

    document.addEventListener("DOMContentLoaded", function() {
      const ctx = document.getElementById('fuelChart').getContext('2d');
      const eventDetails = {
        1970: "First generation wide-body jets introduced.",
        1980: "Fuel efficiency gains from twin-engine designs.",
        1990: "Operational improvements reduce per-seat emissions.",
        2000: "Low-cost carriers expand flight volume.",
        2010: "Composite airframes like Boeing 787 enter service.",
        2020: "COVID-19 pandemic causes demand drop."
      };
      const fuelData = {
        labels: [1970, 1980, 1990, 2000, 2010, 2020],
        datasets: [{
          label: 'Global Aviation Fuel Consumption (Mt)',
          data: [150, 180, 200, 250, 300, 220],
          fill: false,
          borderColor: '#2563eb',
          tension: 0.1,
          pointBackgroundColor: '#1e40af'
        }]
      };
      const chart = new Chart(ctx, {
        type: 'line',
        data: fuelData,
        options: {
          responsive: true,
          plugins: {
            tooltip: {
              callbacks: {
                afterLabel: function(context) {
                  const year = context.label;
                  return eventDetails[year] ? "Event: " + eventDetails[year] : "";
                }
              }
            }
          },
          onClick: (evt) => {
            const points = chart.getElementsAtEventForMode(evt, 'nearest', { intersect: true }, true);
            if (points.length) {
              const year = fuelData.labels[points[0].index];
              document.getElementById('eventInfo').innerHTML = `<strong>${year}:</strong> ${eventDetails[year] || 'No event data available.'}`;
              document.getElementById('eventInfo').style.display = 'block';
            }
          }
        }
      });
    });
  </script>
</body>
</html>
