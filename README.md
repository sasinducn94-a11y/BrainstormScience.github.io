# BrainstormScience.github.io
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Brainstorm Science</title>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700&display=swap" rel="stylesheet">
  <style>
    :root {
      --bg: #0b1020;
      --card: #121836;
      --accent: #4de3c1;
      --text: #e9ecf1;
      --muted: #aab0d6;
    }

    * { box-sizing: border-box; margin: 0; padding: 0; }

    body {
      font-family: 'Inter', sans-serif;
      background: var(--bg);
      color: var(--text);
      line-height: 1.6;
    }

    header {
      padding: 3rem 1.5rem;
      text-align: center;
      background: radial-gradient(circle at top, #1a2160, var(--bg));
    }

    header h1 {
      font-size: 3rem;
      font-weight: 700;
      letter-spacing: -1px;
    }

    header p {
      margin-top: 1rem;
      color: var(--muted);
      font-size: 1.2rem;
    }

    nav {
      margin-top: 2rem;
    }

    nav a {
      color: var(--text);
      text-decoration: none;
      margin: 0 1rem;
      font-weight: 500;
      opacity: 0.85;
    }

    nav a:hover { color: var(--accent); }

    main {
      max-width: 1100px;
      margin: 3rem auto;
      padding: 0 1.5rem;
    }

    .section-title {
      font-size: 2rem;
      margin-bottom: 1.5rem;
    }

    .grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
      gap: 1.5rem;
    }

    .card {
      background: var(--card);
      padding: 1.5rem;
      border-radius: 14px;
      transition: transform 0.2s ease, box-shadow 0.2s ease;
    }

    .card:hover {
      transform: translateY(-6px);
      box-shadow: 0 10px 30px rgba(0,0,0,0.4);
    }

    .card h3 {
      margin-bottom: 0.5rem;
    }

    .card p {
      color: var(--muted);
      font-size: 0.95rem;
    }

    .cta {
      margin: 4rem 0;
      text-align: center;
    }

    .cta button {
      background: var(--accent);
      color: #04110d;
      border: none;
      padding: 0.9rem 1.6rem;
      font-size: 1rem;
      border-radius: 30px;
      cursor: pointer;
      font-weight: 600;
    }

    .cta button:hover {
      opacity: 0.9;
    }

    footer {
      text-align: center;
      padding: 2rem 1rem;
      color: var(--muted);
      border-top: 1px solid #1f2550;
    }
  </style>
</head>
<body>

<header>
  <h1>Brainstorm</h1>
  <p>Where curiosity meets science.</p>
  <nav>
    <a href="#topics">Topics</a>
    <a href="#articles">Articles</a>
    <a href="#experiments">Experiments</a>
    <a href="#about">About</a>
  </nav>
</header>

<main>

  <section id="topics">
    <h2 class="section-title">Explore Topics</h2>
    <div class="grid">
      <div class="card">
        <h3>🧠 Brain & Mind</h3>
        <p>Neuroscience, psychology, memory, creativity, and how we think.</p>
      </div>
      <div class="card">
        <h3>🚀 Space</h3>
        <p>Black holes, galaxies, time, and the future of space exploration.</p>
      </div>
      <div class="card">
        <h3>⚛️ Physics</h3>
        <p>The rules of reality—from particles to the universe itself.</p>
      </div>
      <div class="card">
        <h3>🤖 AI & Tech</h3>
        <p>Artificial intelligence, future technology, and ethics.</p>
      </div>
    </div>
  </section>

  <section id="articles" style="margin-top:4rem;">
    <h2 class="section-title">Featured Articles</h2>
    <div class="grid">
      <div class="card">
        <h3>How the Brain Creates Ideas</h3>
        <p>What happens inside your brain when a new idea suddenly appears?</p>
      </div>
      <div class="card">
        <h3>Can Time Actually Slow Down?</h3>
        <p>Einstein’s relativity explained without the headache.</p>
      </div>
      <div class="card">
        <h3>Is AI Conscious?</h3>
        <p>The science and philosophy behind machine intelligence.</p>
      </div>
    </div>
  </section>

  <section id="experiments" class="cta">
    <h2 class="section-title">Interactive Science</h2>
    <p style="margin-bottom:1.5rem; color:var(--muted);">Test your brain with quizzes, illusions, and simulations.</p>
    <button>Try a Brain Quiz</button>
  </section>

  <section id="about">
    <h2 class="section-title">About Brainstorm</h2>
    <p style="color:var(--muted); max-width:700px;">
      Brainstorm is a science platform built to make complex ideas clear, visual, and exciting. 
      Our goal is simple: spark curiosity and help you understand the world—one idea at a time.
    </p>
  </section>

</main>

<footer>
  © 2025 Brainstorm Science · Think Deeper
</footer>

</body>
</html>
