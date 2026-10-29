<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Reindel Andrada</title>
  <style>
    :root {
      --bg: #0d1117;
      --surface: #161b22;
      --border: #30363d;
      --text-main: #c9d1d9;
      --text-muted: #8b949e;
      --accent: #58a6ff;
    }

    body {
      font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
      background-color: var(--bg);
      color: var(--text-main);
      line-height: 1.5;
      margin: 0;
      padding: 40px 20px;
      display: flex;
      justify-content: center;
    }

    .container {
      max-width: 600px;
      width: 100%;
    }

    h2 { margin-bottom: 8px; font-size: 24px; color: #ffffff; }
    h3 { margin: 32px 0 16px 0; font-size: 16px; text-transform: uppercase; letter-spacing: 0.5px; color: var(--text-muted); }
    p { margin-top: 0; color: var(--text-muted); }

    /* Project Card */
    .project-card {
      display: flex;
      align-items: center;
      gap: 16px;
      background: var(--surface);
      border: 1px solid var(--border);
      border-radius: 12px;
      padding: 16px;
      text-decoration: none;
      color: inherit;
      transition: all 0.2s ease;
    }

    .project-card:hover {
      border-color: var(--text-muted);
      transform: translateY(-2px);
      box-shadow: 0 4px 12px rgba(0,0,0,0.2);
    }

    .project-card img {
      width: 64px;
      height: 64px;
      border-radius: 12px;
      object-fit: cover;
    }

    .project-info strong {
      display: block;
      color: var(--accent);
      font-size: 16px;
      margin-bottom: 4px;
    }

    .project-info span {
      display: inline-block;
      margin-top: 8px;
      font-size: 12px;
      padding: 4px 8px;
      background: rgba(88, 166, 255, 0.1);
      color: var(--accent);
      border-radius: 99px;
    }

    /* Social Links */
    .social-links {
      display: flex;
      flex-wrap: wrap;
      gap: 12px;
    }

    .social-btn {
      display: flex;
      align-items: center;
      gap: 8px;
      background: var(--surface);
      border: 1px solid var(--border);
      padding: 8px 16px;
      border-radius: 99px;
      text-decoration: none;
      color: var(--text-main);
      font-size: 14px;
      transition: background 0.2s;
    }

    .social-btn:hover {
      background: var(--border);
    }
  </style>
</head>
<body>

  <div class="container">
    <header>
      <h2>Reindel Andrada</h2>
      <p>Computer Science student at the Technological University of the Philippines – Manila.<br>
      Building software projects and working through programming problems.</p>
    </header>

    <section>
      <h3>Featured project</h3>
      <a href="https://github.com/Cyborg1644W/Pawi---Study-Timer-Stats" class="project-card">
        <img src="https://github.com/user-attachments/assets/f8b0cb0d-8d3f-4ebb-80e4-c0ae99e7c797" alt="Pawi Icon" />
        <div class="project-info">
          <strong>Pawi — Study Timer & Stats ↗</strong>
          <div>An Android app for focused study and tracking sessions.</div>
          <span>Google Play release pending</span>
        </div>
      </a>
    </section>

    <section>
      <h3>Elsewhere</h3>
      <div class="social-links">
        <a href="https://reindelandrada.vercel.app/" class="social-btn">
          <img src="https://cdn.simpleicons.org/vercel/white" width="16" alt="" />
          Portfolio
        </a>
        <a href="https://leetcode.com/u/Reindel/" class="social-btn">
          <img src="https://cdn.simpleicons.org/leetcode/white" width="16" alt="" />
          LeetCode
        </a>
        <a href="https://www.linkedin.com/in/reindelandrada/" class="social-btn">
          <img src="https://cdn.simpleicons.org/linkedin/white" width="16" alt="" />
          LinkedIn
        </a>
      </div>
    </section>
  </div>

</body>
</html>
