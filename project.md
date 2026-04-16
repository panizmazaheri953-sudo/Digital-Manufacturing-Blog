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
  <p style="color: #b8d4e8;">Phones-R-Us Project</p>
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
    <h2>Phones-R-Us: Modular Phone Casings</h2>
    
    <h3>The Challenge</h3>
    <p>We have been approached by Phones-R-Us to produce top and bottom casings for their existing modular mobile device.</p>
    
    <h3>Key Requirements</h3>
    <table>
      <tr><th>Requirement</th><th>Specification</th></tr>
      <tr><td>Bottom casing</td><td>Drawing provided, must match exactly</td></tr>
      <tr><td>Top casing</td><td>Reverse engineer from existing part</td></tr>
      <tr><td>Interchangeability</td><td>Must fit with "master" casings from other supplier</td></tr>
      <tr><td>Assembly line</td><td>Must flow through FESTO CP Lab without jamming</td></tr>
      <tr><td>Production target</td><td>50,000 units per annum</td></tr>
      <tr><td>Timeline</td><td>9 weeks to present sample for testing</td></tr>
    </table>
    
    <h3>Project Timeline</h3>
    <table>
      <tr><th>Week</th><th>Activity</th></tr>
      <tr><td>1-2</td><td>3D printing trials, material selection</td></tr>
      <tr><td>3-4</td><td>Metrology and tolerance optimization</td></tr>
      <tr><td>5-6</td><td>FESTO CP Lab assembly validation</td></tr>
      <tr><td>7-8</td><td>Plant simulation and capacity planning</td></tr>
      <tr><td>9</td><td>Final sample delivery</td></tr>
    </table>
  </div>
</div>

<div class="footer">
  <p>Paniz Manufacturing Company | Digital Manufacturing Portfolio</p>
</div>

</body>
</html>
