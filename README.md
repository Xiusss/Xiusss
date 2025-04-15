<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>My Personal Website</title>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;700&display=swap" rel="stylesheet">
  <style>
    body {
      margin: 0;
      font-family: 'Inter', sans-serif;
      background-color: #f8f9fa;
      color: #212529;
    }
    header {
      background-color: #343a40;
      color: white;
      padding: 1rem 2rem;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }
    nav a {
      color: white;
      margin-left: 1.5rem;
      text-decoration: none;
      font-weight: bold;
    }
    nav a:hover {
      text-decoration: underline;
    }
    main {
      padding: 2rem;
    }
    section {
      margin-bottom: 3rem;
    }
    .card {
      background: white;
      padding: 1.5rem;
      margin-top: 1rem;
      border-radius: 12px;
      box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
    }
    footer {
      background-color: #343a40;
      color: white;
      text-align: center;
      padding: 1rem;
      margin-top: 3rem;
    }
  </style>
</head>
<body>
  <header>
    <h1>My Website</h1>
    <nav>
      <a href="index.html">Home</a>
      <a href="whoami.html">Who Am I</a>
      <a href="projects.html">Projects</a>
    </nav>
  </header>

  <main>
    <section>
      <h2>Welcome!</h2>
      <div class="card">
        <p>Hi! I'm glad you're here. Explore more about who I am and what I work on by using the links above.</p>
      </div>
    </section>
  </main>

  <footer>
    <p>&copy; 2025 My Name. All rights reserved.</p>
  </footer>
</body>
</html>

<!-- whoami.html -->
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Who Am I</title>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;700&display=swap" rel="stylesheet">
  <style>
    body { font-family: 'Inter', sans-serif; margin: 0; background-color: #f8f9fa; color: #212529; }
    header, footer { background-color: #343a40; color: white; padding: 1rem 2rem; }
    nav a { color: white; margin-left: 1.5rem; text-decoration: none; font-weight: bold; }
    nav a:hover { text-decoration: underline; }
    main { padding: 2rem; }
    .card { background: white; padding: 1.5rem; border-radius: 12px; box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1); }
  </style>
</head>
<body>
  <header>
    <h1>Who Am I</h1>
    <nav>
      <a href="index.html">Home</a>
      <a href="whoami.html">Who Am I</a>
      <a href="projects.html">Projects</a>
    </nav>
  </header>
  <main>
    <div class="card">
      <h2>About Me</h2>
      <p>I am a passionate researcher and developer focused on innovative human-computer interaction technologies. My interests include virtual reality, neurological interfaces, and immersive systems that aim to create impactful experiences for real-world challenges.</p>
    </div>
  </main>
  <footer>
    <p>&copy; 2025 My Name. All rights reserved.</p>
  </footer>
</body>
</html>

<!-- projects.html -->
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Projects</title>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;700&display=swap" rel="stylesheet">
  <style>
    body { font-family: 'Inter', sans-serif; margin: 0; background-color: #f8f9fa; color: #212529; }
    header, footer { background-color: #343a40; color: white; padding: 1rem 2rem; }
    nav a { color: white; margin-left: 1.5rem; text-decoration: none; font-weight: bold; }
    nav a:hover { text-decoration: underline; }
    main { padding: 2rem; }
    .project-card {
      background: white;
      padding: 1.5rem;
      border-radius: 12px;
      box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
      margin-bottom: 2rem;
    }
  </style>
</head>
<body>
  <header>
    <h1>Projects</h1>
    <nav>
      <a href="index.html">Home</a>
      <a href="whoami.html">Who Am I</a>
      <a href="projects.html">Projects</a>
    </nav>
  </header>
  <main>
    <div class="project-card">
      <h2>VR for Mental Health</h2>
      <p>A virtual reality experience designed to support individuals dealing with eating disorders by creating a safe, immersive environment for cognitive and emotional exploration.</p>
    </div>
    <div class="project-card">
      <h2>Neurological Interfaces</h2>
      <p>Exploring brain-computer interfaces for more intuitive interaction with digital environments, especially for accessibility and adaptive systems.</p>
    </div>
    <div class="project-card">
      <h2>Immersive Research in HCI</h2>
      <p>My ongoing PhD proposal on redefining human-computer interaction using multimodal, immersive technologies for societal benefit.</p>
    </div>
  </main>
  <footer>
    <p>&copy; 2025 My Name. All rights reserved.</p>
  </footer>
</body>
</html>
