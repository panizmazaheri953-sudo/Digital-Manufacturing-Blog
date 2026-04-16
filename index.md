<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Paniz Manufacturing | Precision Additive Manufacturing</title>
<style>
  * {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
  }

  body {
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
    min-height: 100vh;
  }

  /* Navigation Bar */
  .navbar {
    background: white;
    box-shadow: 0 2px 20px rgba(0,0,0,0.1);
    padding: 1rem 2rem;
    position: sticky;
    top: 0;
    z-index: 100;
  }

  .nav-container {
    max-width: 1200px;
    margin: 0 auto;
    display: flex;
    justify-content: space-between;
    align-items: center;
    flex-wrap: wrap;
  }

  .logo {
    font-size: 1.5rem;
    font-weight: bold;
    background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
    -webkit-background-clip: text;
    background-clip: text;
    color: transparent;
  }

  .nav-links {
    display: flex;
    gap: 1.5rem;
    flex-wrap: wrap;
  }

  .nav-links a {
    text-decoration: none;
    color: #333;
    font-weight: 500;
    transition: color 0.3s;
  }

  .nav-links a:hover {
    color: #667eea;
  }

  /* Hero Section */
  .hero {
    background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
    color: white;
    text-align: center;
    padding: 4rem 2rem;
  }

  .hero h1 {
    font-size: 3rem;
    margin-bottom: 1rem;
  }

  .hero p {
    font-size: 1.2rem;
    opacity: 0.9;
  }

  /* Container */
  .container {
    max-width: 1200px;
    margin: 0 auto;
    padding: 2rem;
  }

  /* Cards */
  .cards {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: 2rem;
    margin: 3rem 0;
  }

  .card {
    background: white;
    border-radius: 15px;
    padding: 2rem;
    box-shadow: 0 10px 30px rgba(0,0,0,0.1);
    transition: transform 0.3s;
  }

  .card:hover {
    transform: translateY(-5px);
  }

  .card h3 {
    color: #667eea;
    margin-bottom: 1rem;
    font-size: 1.5rem;
  }

  .card p {
    color: #555;
    line-height: 1.6;
  }

  /* Process Table */
  .process-table {
    background: white;
    border-radius: 15px;
    padding: 2rem;
    margin: 2rem 0;
    box-shadow: 0 10px 30px rgba(0,0,0,0.1);
  }

  .process-table h2 {
    color: #333;
    margin-bottom: 1.5rem;
  }

  table {
    width: 100%;
    border-collapse: collapse;
  }

  th {
    background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
    color: white;
    padding: 1rem;
    text-align: left;
  }

  td {
    padding: 1rem;
    border-bottom: 1px solid #eee;
    color: #555;
  }

  tr:hover {
    background: #f8f9ff;
  }

  /* Footer */
  .footer {
    background: #1a1a2e;
    color: white;
    text-align: center;
    padding: 2rem;
    margin-top: 3rem;
  }

  /* Buttons */
  .btn {
    display: inline-block;
    background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
    color: white;
    padding: 12px 30px;
    border-radius: 30px;
    text-decoration: none;
    margin-top: 1rem;
    transition: transform 0.3s;
  }

  .btn:hover {
    transform: scale(1.05);
  }

  @media (max-width: 768px) {
    .nav-container {
      flex-direction: column;
      gap: 1rem;
    }
    .hero h1 {
      font-size: 2rem;
    }
  }
</style>
</head>
<body>

<!-- Navigation -->
<nav class="navbar">
  <div class="nav-container">
    <div class="logo">Paniz Manufacturing</div>
    <div class="nav-links">
      <a href="/Digital-Manufacturing-Blog/">Home</a>
      <a href="/Digital-Manufacturing-Blog/project">Project</a>
      <a href="/Digital-Manufacturing-Blog/printing">3D Printing</a>
      <a href="/Digital-Manufacturing-Blog/quality">Quality</a>
      <a href="/Digital-Manufacturing-Blog/simulation">Simulation</a>
    </div>
  </div>
</nav>

<!-- Hero Section -->
<section class="hero">
  <h1>Precision Additive Manufacturing</h1>
  <p>Specialist manufacturer of interchangeable plastic casings for modular electronics</p>
</section>

<!-- Main Content -->
<div class="container">
  <!-- Cards -->
  <div class="cards">
    <div class="card">
      <h3>🎯 Current Project</h3>
      <p><strong>Phones-R-Us</strong> - Producing top and bottom casings for modular mobile devices.</p>
      <p><strong>Target:</strong> 50,000 units/year</p>
      <a href="/Digital-Manufacturing-Blog/project" class="btn">Learn More →</a>
    </div>
    <div class="card">
      <h3>🖨️ Additive Manufacturing</h3>
      <p>FDM and SLA 3D printing optimized for precision tolerances and repeatability.</p>
      <a href="/Digital-Manufacturing-Blog/printing" class="btn">View Process →</a>
    </div>
    <div class="card">
      <h3>📊 Quality Control</h3>
      <p>Statistical process control ensuring interchangeability across multiple suppliers.</p>
      <a href="/Digital-Manufacturing-Blog/quality" class="btn">View Metrics →</a>
    </div>
  </div>

  <!-- Process Table -->
  <div class="process-table">
    <h2>Our Manufacturing Process</h2>
    <table>
      <thead>
        <tr><th>Stage</th><th>Description</th><th>Technology</th></tr>
      </thead>
      <tbody>
        <tr><td>1. Design</td><td>CAD modelling from client drawings</td><td>SolidWorks / Reverse Engineering</td></tr>
        <tr><td>2. Additive Manufacturing</td><td>3D printing with controlled parameters</td><td>FDM / SLA</td></tr>
        <tr><td>3. Metrology</td><td>Precision measurement of all dimensions</td><td>CMM / Laser Scanning</td></tr>
        <tr><td>4. Quality Control</td><td>Statistical process capability analysis</td><td>Cp, Cpk</td></tr>
        <tr><td>5. Assembly Validation</td><td>FESTO CP Lab automated testing</td><td>Industry 4.0 Workflow</td></tr>
        <tr><td>6. Capacity Planning</td><td>Production scaling simulation</td><td>Tecnomatix Plant Simulation</td></tr>
      </tbody>
    </table>
  </div>
</div>

<!-- Footer -->
<footer class="footer">
  <p>Paniz Manufacturing Company | Digital Manufacturing Portfolio</p>
  <p style="margin-top: 0.5rem; font-size: 0.8rem; opacity: 0.7;">Industry 4.0 | Additive Manufacturing | Quality Assurance</p>
</footer>

</body>
</html>
