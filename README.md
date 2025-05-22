<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Dilla's Portfolio</title>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;700&display=swap" rel="stylesheet">
  <style>
    body {
      font-family: 'Inter', sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f2f4f7;
      color: #333;
    }
    header {
      background-color: #0077b6;
      color: white;
      padding: 40px 20px;
      text-align: center;
    }
    .container {
      max-width: 900px;
      margin: auto;
      padding: 30px 20px;
    }
    .profile {
      display: flex;
      flex-wrap: wrap;
      align-items: center;
      gap: 20px;
    }
    .profile img {
      width: 150px;
      height: 150px;
      border-radius: 50%;
      object-fit: cover;
      border: 3px solid #0077b6;
    }
    .card {
      background-color: white;
      padding: 20px;
      border-radius: 12px;
      box-shadow: 0 4px 12px rgba(0,0,0,0.1);
      margin-top: 20px;
    }
    .links a {
      display: inline-block;
      margin: 10px 10px 0 0;
      text-decoration: none;
      background-color: #0077b6;
      color: white;
      padding: 10px 16px;
      border-radius: 6px;
      transition: background-color 0.2s;
    }
    .links a:hover {
      background-color: #005f90;
    }
    footer {
      text-align: center;
      padding: 20px;
      font-size: 14px;
      color: #888;
    }
  </style>
</head>
<body>

  <header>
    <h1>👋 Hi, I'm Dilla</h1>
    <p>Marine Info Systems | Tech Enthusiast | Ocean Lover</p>
  </header>

  <div class="container">

    <div class="profile">
      <img src="dilla.jpg" alt="Dilla Photo" />
      <div>
        <p>
          I am a Marine Information System student at Universitas Pendidikan Indonesia with a great interest in technology, especially in project and product management, in addition to my interest in marine and fisheries.
        </p>
        <p>
          As a generalist, I enjoy learning new things, adapt quickly, and have good analytical skills in solving problems. I have experience in marine data analysis using various software, active in research activities, and contributing to organizations that focus on public relations.
        </p>
        <p>
          This involvement strengthens my communication and collaboration skills in various cross-disciplinary teams. I am always open to new opportunities, both for collaboration and professional development.
        </p>
        <p>Contact me via LinkedIn or email to collaborate!</p>
      </div>
    </div>

    <div class="card">
      <h2>🧠 Projects</h2>
      <ul>
        <li><strong>Mapping Seagrass Ecosystem:</strong> Using Landsat 8 & SVM</li>
        <li><strong>Coral Reef Fish Classification:</strong> MOGANET-T Model (90%+ accuracy)</li>
      </ul>
    </div>

    <div class="card links">
      <h2>🌐 Connect with Me</h2>
      <a href="https://instagram.com/dillamysr_" target="_blank">Instagram</a>
      <a href="https://linkedin.com/in/dillamayasari" target="_blank">LinkedIn</a>
      <a href="mailto:dillamaya2022@gmail.com">Email</a>
      <a href="https://www.academia.edu/yourusername" target="_blank">Academia.edu</a>
      <a href="https://kompas.id/yourakun" target="_blank">Kompas Profile</a>
    </div>

  </div>

  <footer>
    © 2025 Dilla Mayasari. Made with 💙 for tech & ocean.
  </footer>

</body>
</html>
