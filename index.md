<!DOCTYPE html>
<html>
<head>
<style>
body {
  background-color: #1e3a5f;
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
}
.header {
  background-color: #0d2b44;
  padding: 20px;
  text-align: center;
}
.header h1 {
  color: white;
  margin: 0;
}
.nav {
  background-color: #0a1f33;
  padding: 15px;
  text-align: center;
}
.nav button {
  background-color: #2a6f9c;
  color: white;
  border: none;
  padding: 10px 20px;
  margin: 5px;
  font-size: 16px;
  cursor: pointer;
  border-radius: 5px;
}
.nav button:hover {
  background-color: #3a8fbc;
}
.content {
  background-color: #e6f0fa;
  padding: 40px;
  min-height: 400px;
}
.container {
  max-width: 1000px;
  margin: auto;
  background-color: white;
  padding: 30px;
  border-radius: 10px;
  box-shadow: 0 4px 8px rgba(0,0,0,0.1);
}
h2 {
  color: #1e3a5f;
}
table {
  width: 100%;
  border-collapse: collapse;
  margin: 20px 0;
}
th, td {
  border: 1px solid #ddd;
  padding: 12px;
  text-align: left;
}
th {
  background-color: #1e3a5f;
  color: white;
}
.footer {
  background-color: #0d2b44;
  color: white;
  text-align: center;
  padding: 15px;
  font-size: 14px;
}
</style>
</head>
<body>

<div class="header">
  <h1>Paniz Manufacturing Company</h1>
  <p style="color: #b8d4e8;">Precision Additive Manufacturing Specialist</p>
</div>

<div class="nav">
  <button onclick="location.href='/'">Home</button>
  <button onclick="location.href='/project'">Phones-R-Us Project</button>
  <button onclick="location.href='/printing'">3D Printing</button>
  <button onclick="location.href='/quality'">Quality Control</button>
  <button onclick="location.href='/simulation'">Plant Simulation</button>
</div>

<div class="content">
  <div class="container">
    <h2>Welcome to Paniz Manufacturing</h2>
    <p>We specialise in producing high-precision plastic casings for modular electronic devices using additive manufacturing and Industry 4.0 workflows.</p>
    
    <h3>Our Manufacturing Process</h3>
    <table>
      <tr><th>Stage</th><th>Description</th></tr>
      <tr><td>1. Design</td><td>CAD modelling from client drawings</td></tr>
      <tr><td>2. Additive Manufacturing</td><td>3D printing with controlled parameters</td></tr>
      <tr><td>3. Metrology</td><td>Precision measurement of all dimensions</td></tr>
      <tr><td>4. Quality Control</td><td>Statistical process capability analysis</td></tr>
      <tr><td>5. Assembly Validation</td><td>FESTO CP Lab automated testing</td></tr>
      <tr><td>6. Capacity Planning</td><td>Tecnomatix Plant Simulation</td></tr>
    </table>
    
    <h3>Current Client: Phones-R-Us</h3>
    <p><strong>Target:</strong> 50,000 interchangeable phone casings per year</p>
    <p><strong>Timeline:</strong> 9-week prototype delivery</p>
  </div>
</div>

<div class="footer">
  <p>Paniz Manufacturing Company | Digital Manufacturing Portfolio</p>
</div>

</body>
</html>
