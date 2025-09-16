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
    <h1>Muteesa 1 Royal University</h1>
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
