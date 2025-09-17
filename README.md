<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Youth Voices — Home</title>

  <style>
    /* Basic reset */
    * { box-sizing: border-box; margin: 0; padding: 0; }
    html { scroll-behavior: smooth; } /* smooth scrolling for anchor links */
    body { font-family: system-ui, -apple-system, "Segoe UI", Roboto, "Helvetica Neue", Arial; line-height: 1.5; color: #222; }

    /* Fixed top navbar (black bar) */
    nav {
      position: fixed;
      top: 0;
      left: 0;
      right: 0;
      background: #000;
      color: #fff;
      display: flex;
      gap: 10px;
      align-items: center;
      padding: 12px 16px;
      z-index: 1000;
      overflow-x: auto; /* good for small screens */
      -webkit-overflow-scrolling: touch;
    }
    nav a {
      color: #fff;
      text-decoration: none;
      padding: 8px 10px;
      border-radius: 6px;
      white-space: nowrap;
      font-weight: 600;
      font-size: 15px;
    }
    nav a:hover { background: rgba(255,255,255,0.06); text-decoration: underline; }

    /* Make room under the fixed nav */
    .page-content { padding-top: 68px; } /* equal roughly to nav height + space */

    /* Layout */
    .container { max-width: 900px; margin: 0 auto; padding: 20px; }

    /* Section styling */
    section {
      padding: 48px 0;
      border-bottom: 1px solid #ececec;
    }
    section h2 { margin-bottom: 12px; font-size: 24px; }
    section p { color: #333; margin-bottom: 12px; }

    /* Small helper: back-to-top */
    .top-link {
      display: inline-block;
      margin-top: 8px;
      text-decoration: none;
      font-size: 14px;
    }

    /* Responsive tweaks */
    @media (max-width: 520px) {
      nav { padding: 10px; gap: 8px; }
      nav a { font-size: 14px; padding: 7px 9px; }
      .container { padding: 12px; }
    }
  </style>
</head>

<body>
  <!-- NAVBAR: edit links here if you want to add more -->
  <nav>
    <a href="#home">Home</a>
    <a href="#art">Art Lovers</a>
    <a href="#careers">Dream Careers</a>
    <a href="#fun">For Fun</a>
    <a href="#law">Law & Debates</a>
    <a href="#skills">Skills & Growth</a>
  </nav>

  <div class="page-content">
    <main class="container">
      <!-- HOME / top -->
      <section id="home">
        <h2>Welcome to Youth Voices</h2>
        <p>Hi! This is your homepage. Use the black menu above to jump to each section. No extra files needed — everything is in one page.</p>
        <a class="top-link" href="#home">You are at top</a>
      </section>

      <!-- ART section -->
      <section id="art">
        <h2>🎨 Art Lovers</h2>
        <p>Share drawings, poems, comics, weekly challenges, and gallery posts. Paste your images or links here and add small captions.</p>
        <p>Ideas: monthly theme, art contest, tutorial video links.</p>
        <a class="top-link" href="#home">⬆ Back to top</a>
      </section>

      <!-- CAREERS section -->
      <section id="careers">
        <h2>🚀 Dream Careers</h2>
        <p>Give career advice, interviews with mentors, short quizzes about jobs, and how to start working toward your dream career.</p>
        <p>Ideas: "Career of the month", study tips, guest mentor Q&amp;A.</p>
        <a class="top-link" href="#home">⬆ Back to top</a>
      </section>

      <!-- FUN section -->
      <section id="fun">
        <h2>🎉 For Fun</h2>
        <p>Puzzles, memes, quick quizzes, and game nights. Keep this section light and playful so everyone enjoys visiting.</p>
        <a class="top-link" href="#home">⬆ Back to top</a>
      </section>

      <!-- LAW & DEBATES -->
      <section id="law">
        <h2>⚖️ Law & Debates</h2>
        <p>Mini-debates, simple law facts, mock trial scripts, "Law in 60 seconds" posts. Great place to practice speaking and thinking fast.</p>
        <a class="top-link" href="#home">⬆ Back to top</a>
      </section>

      <!-- SKILLS & GROWTH -->
      <section id="skills">
        <h2>📚 Skills & Growth</h2>
        <p>Workshops, study tips, time-management ideas, language practice, presentations, and challenge checklists.</p>
        <p>Ideas: "This week practice", watchlist, reading goals.</p>
        <a class="top-link" href="#home">⬆ Back to top</a>
      </section>

      <!-- Footer or extra info -->
      <section id="contact">
        <h2>Contact / Notes</h2>
        <p>If you want to add content, edit this file and paste images or text under the right section. If the menu still does not move, make sure you're editing the same `index.html` file that your site uses (the one published by GitHub Pages).</p>
        <p>Tip: <strong>nav links like <code>href="#art"</code></strong> must match the section id <strong><code>id="art"</code></strong>.</p>
      </section>
    </main>
  </div>

</body>
</html>
# YouthVoicesproject
It will be a platform on which students share their paintings, poetry, photography, or short videos.  Others give feedback, clap, and encourage. And other sections of differents purposes 
