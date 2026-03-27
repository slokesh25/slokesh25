<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Python Full Stack Developer</title>

  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background: linear-gradient(135deg, #0f172a, #1e293b);
      color: white;
      display: flex;
      justify-content: center;
      align-items: center;
      padding: 30px;
    }

    .container {
      max-width: 800px;
      width: 100%;
    }

    .card {
      background: #1e293b;
      padding: 30px;
      border-radius: 15px;
      box-shadow: 0 0 25px rgba(0,0,0,0.6);
      transition: transform 0.2s;
    }

    /* 🔥 Shake effect */
    .card:hover {
      animation: shake 0.3s;
    }

    @keyframes shake {
      0% { transform: translateX(0); }
      25% { transform: translateX(-6px); }
      50% { transform: translateX(6px); }
      75% { transform: translateX(-6px); }
      100% { transform: translateX(0); }
    }

    h1 {
      text-align: center;
      color: #38bdf8;
      margin-bottom: 5px;
    }

    h2 {
      text-align: center;
      font-size: 18px;
      color: #cbd5f5;
      margin-bottom: 20px;
    }

    h3 {
      margin-top: 25px;
      color: #facc15;
      border-bottom: 1px solid #334155;
      padding-bottom: 5px;
    }

    p {
      line-height: 1.6;
      font-size: 15px;
    }

    ul {
      padding-left: 20px;
    }

    li {
      margin-bottom: 8px;
    }

    .skill-box {
      background: #0f172a;
      padding: 10px;
      border-radius: 8px;
      margin-bottom: 10px;
      border-left: 4px solid #38bdf8;
    }

  </style>
</head>

<body>

<div class="container">
  <div class="card">

    <h1>👨‍💻 Python Full Stack Developer</h1>
    <h2>Aspiring Developer</h2>

    <h3>🎯 Objective</h3>
    <p>
      Aspiring Python Full Stack Developer with hands-on experience in building scalable web applications 
      using Python, Django, Django REST Framework, SQL, and modern frontend technologies. 
      Seeking an entry-level opportunity to contribute to innovative software solutions while continuously 
      enhancing my technical and problem-solving skills.
    </p>

    <h3>💡 Technical Skills</h3>

    <div class="skill-box">
      <strong>Python:</strong> Object Oriented Programming (OOP), Exception Handling, File Handling, 
      Data Structures (List, Tuple, Set, Dictionary)
    </div>

    <div class="skill-box">
      <strong>Web Technologies:</strong> HTML, CSS (Flexbox, Grid, Responsive Design)
    </div>

    <div class="skill-box">
      <strong>Database:</strong> SQL (Oracle) – Joins, Subqueries, DDL, DML
    </div>

    <div class="skill-box">
      <strong>Backend Development:</strong> Python, Django, Django REST Framework
    </div>

    <div class="skill-box">
      <strong>Tools:</strong> Git, GitHub, VS Code
    </div>

  </div>
</div>

</body>
</html>
