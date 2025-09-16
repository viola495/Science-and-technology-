<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Faculty of Science and Technology - MRU</title>
  <style>
    /* Reset some defaults */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: Arial, sans-serif;
      line-height: 1.6;
      background: #f4f4f9;
      color: #333;
    }

    /* Navigation bar */
    .navbar {
      background: steelblue;
      padding: 15px;
    }
    .navbar ul {
      list-style: none;
      display: flex;
      justify-content: center;
    }
    .navbar ul li {
      margin: 0 15px;
    }
    .navbar ul li a {
      color: white;
      text-decoration: none;
      font-weight: bold;
    }
    .navbar ul li a:hover {
      text-decoration: underline;
    }

    /* Layout */
    .container {
      display: flex;
      margin: 20px;
    }

    /* Sidebar */
    .sidebar {
      width: 200px;
      background: #ddd;
      padding: 15px;
    }
    .sidebar ul {
      list-style: none;
    }
    .sidebar ul li {
      margin: 10px 0;
    }
    .sidebar ul li a {
      color: #000;
      text-decoration: none;
    }
    .sidebar ul li a:hover {
      color: steelblue;
    }

    /* Main content */
    .content {
      flex: 1;
      padding: 20px;
      background: #fff;
      margin-left: 20px;
      border-radius: 5px;
    }
    .content h1 {
      margin-bottom: 20px;
      color: steelblue;
    }

    /* Table styling */
    table {
      width: 100%;
      border-collapse: collapse;
      margin-top: 10px;
    }
    table, th, td {
      border: 1px solid #333;
    }
    th, td {
      padding: 10px;
      text-align: left;
    }
    th {
      background: #f0f0f0;
    }

    /* Footer */
    .footer {
      background: steelblue;
      color: white;
      text-align: center;
      padding: 15px;
      position: fixed;
      bottom: 0;
      left: 0;
      width: 100%;
    }
  </style>
</head>
<body>

  <!-- Navigation bar -->
  <nav class="navbar">
    <ul>
      <li><a href="#">Home</a></li>
      <li><a href="#">About</a></li>
      <li><a href="#">Contact</a></li>
    </ul>
  </nav>

  <div class="container">
    <!-- Sidebar -->
    <aside class="sidebar">
      <ul>
        <li><a href="#">Dashboard</a></li>
        <li><a href="#">Course Settings</a></li>
        <li><a href="#">Profile</a></li>
        <li><a href="#">Help</a></li>
      </ul>
    </aside>

    <!-- Main content -->
    <main class="content">
      <h1>Courses under Faculty of Science and Technology</h1>
      <table>
        <thead>
          <tr>
            <th>No.</th>
            <th>Course Code</th>
            <th>Course Name</th>
            <th>Credits</th>
          </tr>
        </thead>
        <tbody>
          <tr>
            <td>1</td>
            <td>CST101</td>
            <td>Introduction to Programming</td>
            <td>3</td>
          </tr>
          <tr>
            <td>2</td>
            <td>CST102</td>
            <td>Computer Networks</td>
            <td>4</td>
          </tr>
          <tr>
            <td>3</td>
            <td>CST103</td>
            <td>Database Systems</td>
            <td>3</td>
          </tr>
          <tr>
            <td>4</td>
            <td>CST104</td>
            <td>Web Development</td>
            <td>3</td>
          </tr>
        </tbody>
      </table>
    </main>
  </div>

  <!-- Footer -->
  <footer class="footer">
    <p>&copy; <span id="year"></span> Muteesa Royal University. All rights reserved.</p>
  </footer>

  <script>
    // Auto update year
    document.getElementById("year").textContent = new Date().getFullYear();
  </script>

</body>
</html>
