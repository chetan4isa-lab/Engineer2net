<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title> Electrical Engineering Menu </title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      background-color: #f9f8ff; /* light purple-white */
      color: #2c003e;
    }
    header {
      background-color: #665679; /* deep purple */
      padding: 15px 20px;
      color: white;
      text-align: center;
    }
    nav {
      display: flex;
      justify-content: center;
      background: #a64dff; /* lighter purple */
    }
    nav a {
      color: white;
      padding: 14px 20px;
      text-decoration: none;
      font-weight: bold;
      transition: background 0.3s;
    }
    nav a:hover {
      background: #6a0dad;
      border-radius: 5px;
    }
    section {
      padding: 30px;
      text-align: center;
    }
    section h2 {
      color: #6a0dad;
    }
    .card-container {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
      gap: 20px;
      margin-top: 20px;
    }
    .card {
      background: white;
      padding: 20px;
      border-radius: 12px;
      box-shadow: 0px 4px 8px rgba(106, 13, 173, 0.2); /* purple glow */
      border: 2px solid #a64dff;
      transition: transform 0.2s, background 0.3s;
    }
    .card:hover {
      transform: scale(1.05);
      background: #f2e6ff; /* light purple hover */
    }
    footer {
      text-align: center;
      background: #6a0dad;
      color: white;
      padding: 15px;
      margin-top: 30px;
    }
  </style>
</head>
<body>
  <header>
    <h1>Electrical Engineering Menu</h1>
  </header>

  <nav>
    <a href="#network theory ">Network Theory</a>
    <a herf="#electromagnetic field theory">Electromagnetic Field Theory </a>
    <a href="#electric machines">Electric Machines</a>
    <a href="#power system">Power System</a>
    <a href="#control system">Control System</a>
    <a href="#signal and systems">Signal And Systems</a>
    <a href="#analog electronics">Analog Electronics</a>
    <a href="#digital electronics">Digital Electronics</a>
    <a href="#measurements">Measurements</a>
  </nav>

  <section id="network theory">
    <h2>Network Theory</h2>
    <div class="card-container">
      <div class="card">Basic Concepts</div>
      <div class="card">Network Theorems</div>
      <div class="card">Transients</div>
      <div class="card">AC Analysis</div>
      <div class="card">Resonance</div>
      <div class="card">Coupled Circuits</div>
      <div class="card">Two Port Networks</div>
    </div>
  </section>
  
  <section id="electromagnetic field theory">
    <h2>Electromagnetic Field Theory</h2>
    <div class="card-container">
      <div class="card">Vector Analysis</div>
      <div class="card">Electrostatics</div>
      <div class="card">Magnetostatics</div>
      <div class="card">Uniform Plane Wave</div>
    </div>
  </section>

  <section id="electric machines">
    <h2>Electric Machines</h2>
    <div class="card-container">
      <div class="card">Transformers</div>
      <div class="card">DC Machines</div>
      <div class="card">Induction Motors</div>
    </div>
  </section>

  <section id="power systems">
    <h2>Power Systems</h2>
    <div class="card-container">
      <div class="card">Generation</div>
      <div class="card">Line Parameters</div>
      <div class="card">Load Flow and Fault Analysis</div>
      <div class="card">Power System Stability</div>
      <div class="card">Power System Protection and Switchgear</div>
    </div>
  </section>

  <section id="electronics">
    <h2>Electronics</h2>
    <div class="card-container">
      <div class="card">Semiconductors</div>
      <div class="card">Diodes & Transistors</div>
      <div class="card">Op-Amps</div>
    </div>
  </section>

  <section id="measurements">
    <h2>Measurements</h2>
    <div class="card-container">
      <div class="card">Multimeters</div>
      <div class="card">Oscilloscopes</div>
      <div class="card">Wattmeters</div>
    </div>
  </section>

  <footer>
    <p>© 2025 Electrical Engineering Menu | Designed for Students</p>
  </footer>
</body>
</html>
