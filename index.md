---
layout: default
---

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
      background: #f0f4f8; 
      color: #1e293b; 
    }

    header {
      background: linear-gradient(135deg, #0d9488, #2563eb);
      color: white;
      padding: 40px 20px;
      text-align: center;
    }

    header img {
      width: 180px;
      border-radius: 50%;
      margin-bottom: 15px;
      box-shadow: 0 4px 15px rgba(0,0,0,0.3);
    }

    h1 { font-size: 2.5em; margin: 10px 0; }
    h2 { color: #2563eb; margin-top: 30px; border-bottom: 2px solid #2563eb; display: inline-block; padding-bottom: 5px; }
    p { font-size: 1.1em; margin: 10px 0 20px; }
    ul { list-style-type: square; padding-left: 20px; }

    nav {
      background: white;
      padding: 10px 0;
      box-shadow: 0 4px 6px rgba(0,0,0,0.1);
      text-align: center;
      position: sticky;
      top: 0;
      z-index: 1000;
    }

    nav ul {
      list-style: none;
      margin: 0;
      padding: 0;
      display: inline-flex;
    }

    nav ul li {
      margin: 0 15px;
    }

    nav ul li a {
      color: #2563eb;
      text-decoration: none;
      font-weight: bold;
      font-size: 1.1em;
    }

    nav ul li a.active {
      text-decoration: underline;
    }

    nav ul li a:hover {
      color: #0d9488;
    }

    section { 
      margin: 30px auto; 
      max-width: 800px; 
      background: #fff; 
      padding: 20px; 
      border-radius: 12px; 
      box-shadow: 0 8px 20px rgba(0,0,0,0.08); 
      transition: transform 0.3s ease, box-shadow 0.3s ease;
    }

    section:hover {
      transform: translateY(-4px);
      box-shadow: 0 12px 24px rgba(0,0,0,0.15);
    }
  </style>
</head>

<body>
  <nav>
    <ul>
      <li><a href="#home" class="active">Home</a></li>
      <li><a href="#research">Research</a></li>
      <li><a href="#contact">Contact</a></li>
    </ul>
  </nav>

  <header id="home">
    <img src="profile.jpg" alt="Mostafa Abdelmotaleb">
    <h1>Mostafa Abdelmotaleb</h1>
    <p>Assistant Professor in Organizational and Social Psychology, HRM Department, Rabat Business School, Morocco. AACSB accredited.</p>
  </header>

  <section id="research">
    <h2>Research Interests</h2>
    <ul>
      <li>Corporate Social Responsibility (CSR)</li>
      <li>Individual Attitudes and Behaviors</li>
      <li>Ethical Outcomes in Organizations</li>
    </ul>
  </section>

  <section id="contact">
    <h2>Contact</h2>
    <p>Email: <a href="mailto:mostafa@univ.ma">mostafa@univ.ma</a></p>
    <p>CV: <a href="REPLACE_WITH_CV_URL" target="_blank">Download PDF</a></p>
    <p>LinkedIn: <a href="https://www.linkedin.com/in/YOUR-LINKEDIN" target="_blank">Profile</a></p>
    <p>Google Scholar: <a href="https://scholar.google.com/citations?user=YOURID" target="_blank">Profile</a></p>
  </section>
</body>
