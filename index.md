<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Mostafa Abdelmotaleb - Academic Website</title>
  <style>
    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      line-height: 1.6;
      padding: 0;
      margin: 0;
      background: linear-gradient(to right, #e0f7fa, #f1f8e9);
      color: #1e293b;
    }

    header {
      text-align: center;
      padding: 50px 20px;
      background: #00796b;
      color: white;
    }

    header img {
      width: 180px;
      border-radius: 50%;
      border: 3px solid #fff;
      margin-bottom: 15px;
    }

    header h1 {
      font-size: 2.5em;
      margin: 0;
    }

    header p {
      font-size: 1.2em;
      margin-top: 10px;
    }

    section {
      background-color: white;
      padding: 25px;
      margin: 20px auto;
      max-width: 900px;
      border-radius: 12px;
      box-shadow: 0 8px 20px rgba(0,0,0,0.1);
    }

    h2 {
      color: #00796b;
      border-bottom: 2px solid #00796b;
      display: inline-block;
      padding-bottom: 5px;
      margin-bottom: 15px;
    }

    ul {
      list-style-type: square;
      padding-left: 20px;
    }

    a {
      color: #00796b;
      text-decoration: none;
    }

    a:hover {
      text-decoration: underline;
    }

    nav {
      background-color: #00796b;
      padding: 10px 0;
    }

    nav ul {
      list-style: none;
      margin: 0;
      padding: 0;
      display: flex;
      justify-content: center;
    }

    nav ul li {
      margin: 0 15px;
    }

    nav ul li a {
      color: white;
      text-decoration: none;
      font-weight: bold;
    }

    nav ul li a:hover {
      text-decoration: underline;
    }
  </style>
</head>

<body>{% include navbar.html %}
  <!-- Profile Photo -->
  <img src="profile.jpg" alt="Mostafa Abdelmotaleb" style="width:180px; border-radius:50%; margin-bottom:15px; display:block; margin-left:auto; margin-right:auto;">

  <!-- Main Heading -->
  <h1 style="text-align:center;">Mostafa Abdelmotaleb</h1>

  <!-- Introduction -->
  <p style="text-align:center;">Assistant Professor in Organizational and Social Psychology, HRM Department, Rabat Business School, Morocco. AACSB accredited.</p>

  <!-- Research Interests -->
  <section>
    <h2>Research Interests</h2>
    <ul>
      <li>Corporate Social Responsibility (CSR)</li>
      <li>Individual Attitudes and Behaviors</li>
      <li>Ethical Outcomes in Organizations</li>
    </ul>
  </section>

  <!-- Contact -->
  <section>
    <h2>Contact</h2>
    <p>Email: <a href="mailto:mostafa@univ.ma">mostafa@univ.ma</a></p>
    <p>CV: <a href="REPLACE_WITH_CV_URL" target="_blank">Download PDF</a></p>
    <p>LinkedIn: <a href="https://www.linkedin.com/in/YOUR-LINKEDIN" target="_blank">Profile</a></p>
    <p>Google Scholar: <a href="https://scholar.google.com/citations?user=YOURID" target="_blank">Profile</a></p>
  </section>
</body>
