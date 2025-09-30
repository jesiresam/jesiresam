<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>[Your Name] — Front-End Developer</title>

  <!-- Simple, self-contained styling for a clean, professional look -->
  <style>
    :root{
      --bg:#0f1724; --card:#0b1220; --muted:#9aa4b2; --accent:#7c5cff; --glass: rgba(255,255,255,0.04);
      --radius:14px; font-family:Inter, "Segoe UI", Roboto, Arial, sans-serif;
    }
    html,body{height:100%; margin:0; background: linear-gradient(180deg, #071026 0%, #07152a 100%); color:#e6eef6;}
    .container{max-width:980px; margin:36px auto; padding:28px; border-radius:18px; background: linear-gradient(180deg, rgba(255,255,255,0.02), rgba(255,255,255,0.01)); box-shadow: 0 10px 30px rgba(2,6,23,0.6);}
    .header{display:flex; gap:20px; align-items:center;}
    .avatar{width:110px; height:110px; border-radius:20px; background:linear-gradient(135deg, var(--accent), #4bc0c8); display:flex; align-items:center; justify-content:center; font-weight:700; font-size:36px; color:white; flex-shrink:0;}
    h1{margin:0; font-size:26px;}
    .subtitle{color:var(--muted); margin-top:6px; font-size:14px;}
    .bio{margin-top:18px; line-height:1.6; color:#d8e6f2;}
    .grid{display:grid; grid-template-columns:1fr 340px; gap:20px; margin-top:22px;}
    .card{background:var(--card); padding:18px; border-radius:12px; box-shadow: 0 6px 18px rgba(2,6,23,0.5);}
    .skills{display:flex; flex-wrap:wrap; gap:8px; margin-top:12px;}
    .chip{background:var(--glass); color:var(--muted); padding:8px 10px; border-radius:999px; font-size:13px;}
    .projects-list{display:flex; flex-direction:column; gap:12px;}
    .project{background:linear-gradient(180deg, rgba(255,255,255,0.02), rgba(0,0,0,0.04)); padding:12px; border-radius:10px; display:flex; justify-content:space-between; align-items:center;}
    .project-left{max-width:68%;}
    .project-title{font-weight:600; margin:0;}
    .project-desc{color:var(--muted); margin-top:6px; font-size:13px;}
    .cta{margin-top:18px; display:flex; gap:12px; flex-wrap:wrap;}
    .btn{background:linear-gradient(90deg,var(--accent),#4bc0c8); color:#071026; padding:10px 14px; border-radius:10px; font-weight:700; text-decoration:none;}
    footer{margin-top:22px; color:var(--muted); font-size:13px; text-align:center;}
    .meta-row{display:flex; gap:10px; flex-wrap:wrap; align-items:center; margin-top:8px;}
    .stat{background:#071326; padding:8px 10px; border-radius:8px; font-weight:700; color:#bcd5ff; font-size:13px;}
    pre {background:#041226; padding:12px; border-radius:8px; overflow:auto; color:#cfe9ff;}
    @media(max-width:900px){ .grid{grid-template-columns:1fr; } .avatar{width:86px;height:86px;font-size:28px;} }
  </style>
</head>
<body>
  <main class="container" role="main" aria-labelledby="main-title">
    <header class="header">
      <div class="avatar" aria-hidden="true">YS</div>
      <div>
        <h1 id="main-title"> Samantha Jesire — Front-End Developer (ALX ProDev)</h1>
        <div class="subtitle">I build beautiful, accessible web apps. Interested in UI, performance, and real user impact.</div>
        <div class="meta-row">
          <span class="stat">🌍 Nairobi, Kenya</span>
          <span class="stat">📧 <a href="mailto:[you@example.com]" style="color:inherit; text-decoration:none;">[you@example.com]</a></span>
          <span class="stat">💼 Open to opportunities</span>
        </div>
      </div>
    </header>

    <section class="bio card" aria-label="About">
      <h2 style="margin-top:0;">About</h2>
      <p>
        I started software engineering because <strong> I have always had a strong interest in tech. </strong>.
        I am passionate about <strong>creative tech and using tech to make technology more accesible and enjoyable to use.</strong>.
      </p>
      <p>
        My aim is <strong>to build aesthetically pleasing and easy to use software especially marketing software for small businesses.</strong>.
        That’s why I focus on working on <strong>accessible web apps, UI and UX and front end projects.</strong>.
      </p>

      <div class="cta">
        <a class="btn" href="" target="_blank" rel="noopener">Portfolio</a>
        <a class="btn" href="https://github.com/jesiresam" target="_blank" rel="noopener">GitHub</a>
        <a class="btn" href="" target="_blank" rel="noopener">Resume (PDF)</a>
      </div>
    </section>

    <div class="grid">
      <!-- Left column: Projects & Skills -->
      <div>
        <section class="card" aria-label="What I do">
          <h3 style="margin-top:0;">What I do</h3>
          <ul style="margin:10px 0 0 18px; color:var(--muted);">
            <li>Design and develop pixel-perfect UIs using modern HTML, CSS, and JavaScript.</li>
            <li>Build modular, maintainable React apps and reusable component libraries.</li>
            <li>Optimize performance and accessibility to deliver delightful user experiences.</li>
          </ul>
        </section>

        <section class="card" aria-label="Selected projects" style="margin-top:12px;">
          <h3 style="margin-top:0;">Selected Projects</h3>
          <div class="projects-list">
            <!-- Project 1 -->
            <article class="project">
              <div class="project-left">
                <div class="project-title">Project One — [Project Name]</div>
                <div class="project-desc">A short 1-line summary: what it is, tech used, and the problem it solves. <em>Example: A responsive expense tracker built with React, Tailwind, and localStorage for offline-first budgets.</em></div>
              </div>
              <div style="text-align:right;">
                <a class="btn" href="https://github.com/[your-github]/[project-1]" target="_blank">Repo</a>
              </div>
            </article>

            <!-- Project 2 -->
            <article class="project">
              <div class="project-left">
                <div class="project-title">Project Two — [Project Name]</div>
                <div class="project-desc">Short summary + highlight (e.g., "Accessibility-first landing page with Lighthouse score: 98").</div>
              </div>
              <div style="text-align:right;">
                <a class="btn" href="https://github.com/[your-github]/[project-2]" target="_blank">Repo</a>
              </div>
            </article>
            <!-- Add more project cards as needed -->
          </div>
        </section>

        <section class="card" aria-label="Skills" style="margin-top:12px;">
          <h3 style="margin-top:0;">Tech & Skills</h3>
          <div class="skills">
            <span class="chip">HTML5</span>
            <span class="chip">CSS3</span>
            <span class="chip">JavaScript (ES6+)</span>
            <span class="chip">React</span>
            <span class="chip">Tailwind CSS</span>
            <span class="chip">Responsive Design</span>
            <span class="chip">Accessibility (a11y)</span>
            <span class="chip">Git & GitHub</span>
            <span class="chip">Performance Optimization</span>
            <span class="chip">Testing (Jest | RTL)</span>
          </div>
        </section>

        <section class="card" style="margin-top:12px;" aria-label="Learning & Certifications">
          <h3 style="margin-top:0;">Courses & Certifications</h3>
          <ul style="color:var(--muted); margin:8px 0 0 18px;">
            <li>ALX ProDev — Front-End Track (in progress)</li>
            <li>[Any other certificate, e.g., "FreeCodeCamp — Responsive Web Design"]</li>
          </ul>
        </section>
      </div>

      <!-- Right column: Stats, Contact, Quick Links -->
      <aside>
        <section class="card" aria-label="GitHub Stats">
          <h3 style="margin-top:0;">GitHub at-a-glance</h3>
          <p style="color:var(--muted); margin-top:6px;">Add these images in your README for live stats (replace username):</p>
          <pre>
<!-- Example Badges (place these as images in your README.md) -->
&lt;img src="https://github-readme-stats.vercel.app/api?username=[your-github]&amp;show_icons=true" /&gt;
&lt;img src="https://github-readme-streak-stats.herokuapp.com/?user=[your-github]" /&gt;
          </pre>
          <p style="color:var(--muted); margin-top:8px;">Tip: add language and top project cards to highlight strengths.</p>
        </section>

        <section class="card" aria-label="Contact" style="margin-top:12px;">
          <h3 style="margin-top:0;">Contact</h3>
          <p style="color:var(--muted); margin-top:6px;">
            <strong>Email:</strong> <a href="mailto:jesiresam@gmail.com" style="color:inherit;">jesiresam@gmail.com</a><br/>
            <strong>LinkedIn:</strong> <a href=https://www.linkedin.com/in/samantha-jesire/overlay/about-this-profile/?lipi=urn%3Ali%3Apage%3Ad_flagship3_profile_view_base%3B8ujXUjVxTcq9RncGYEnWEA%3D%3D"" target="_blank" rel="noopener" style="color:inherit;">Jesiresam</a><br/>
            <strong>Portfolio:</strong> <a href="[portfolio-url]" target="_blank" rel="noopener" style="color:inherit;">[portfolio]</a>
          </p>
        </section>

        <section class="card" aria-label="How I like to work" style="margin-top:12px;">
          <h3 style="margin-top:0;">How I like to work</h3>
          <p style="color:var(--muted); margin-top:6px;">I value clear specs, iterative feedback, and testing. I enjoy collaborating on product-focused teams and learning new tools quickly.</p>
        </section>

        <section class="card" aria-label="Call to action" style="margin-top:12px;">
          <h3 style="margin-top:0;">Let's collaborate</h3>
          <p style="color:var(--muted); margin-top:6px;">If you have an idea or role that fits my skill set, I'd love to talk. Open to internships, junior front-end roles, and freelance UX-focused builds.</p>
          <div style="margin-top:10px;">
            <a class="btn" href="mailto:[you@example.com]">Reach out →</a>
          </div>
        </section>
      </aside>
    </div>

    <footer>
      Built with ❤️ • ALX ProDev Front-End • <a href="https://github.com/[your-github]" target="_blank" style="color:inherit;">@your-github</a>
    </footer>
  </main>
</body>
</html>

