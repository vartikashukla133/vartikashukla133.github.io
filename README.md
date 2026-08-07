# vartikashukla133.github.io
Personal Branding Strategist | LinkedIn Ghostwriter | Helping founders build authority through positioning and content.
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <title>Vartika Shukla | Personal Branding Strategist</title>

  <meta
    name="description"
    content="Portfolio of Vartika Shukla, Personal Branding Strategist and LinkedIn Ghostwriter helping founders and professionals build authority through positioning, content and clear communication."
  >

  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    html {
      scroll-behavior: smooth;
    }

    body {
      font-family: Arial, Helvetica, sans-serif;
      background: #f8f7f4;
      color: #1f1f1f;
      line-height: 1.7;
    }

    a {
      text-decoration: none;
      color: inherit;
    }

    .container {
      width: min(1100px, 90%);
      margin: auto;
    }

    /* NAVBAR */

    nav {
      background: rgba(248, 247, 244, 0.95);
      border-bottom: 1px solid #dedbd4;
      position: sticky;
      top: 0;
      z-index: 100;
    }

    .nav-container {
      min-height: 72px;
      display: flex;
      align-items: center;
      justify-content: space-between;
    }

    .logo {
      font-size: 20px;
      font-weight: 700;
    }

    .nav-links {
      display: flex;
      gap: 28px;
      font-size: 14px;
    }

    .nav-links a:hover {
      color: #6c5ce7;
    }

    /* HERO */

    .hero {
      min-height: 88vh;
      display: flex;
      align-items: center;
      padding: 80px 0;
    }

    .hero-content {
      max-width: 850px;
    }

    .eyebrow {
      color: #6c5ce7;
      font-weight: 700;
      margin-bottom: 18px;
      text-transform: uppercase;
      letter-spacing: 1.5px;
      font-size: 13px;
    }

    h1 {
      font-size: clamp(46px, 8vw, 88px);
      line-height: 1.02;
      margin-bottom: 28px;
      letter-spacing: -3px;
    }

    .hero-description {
      font-size: 21px;
      max-width: 720px;
      color: #555;
      margin-bottom: 35px;
    }

    .hero-buttons {
      display: flex;
      gap: 14px;
      flex-wrap: wrap;
    }

    .btn {
      display: inline-block;
      padding: 14px 24px;
      border-radius: 8px;
      font-weight: 600;
      transition: 0.2s ease;
    }

    .btn-primary {
      background: #1f1f1f;
      color: white;
    }

    .btn-primary:hover {
      background: #6c5ce7;
      transform: translateY(-2px);
    }

    .btn-secondary {
      border: 1px solid #1f1f1f;
    }

    .btn-secondary:hover {
      background: white;
    }

    /* SECTIONS */

    section {
      padding: 100px 0;
    }

    .section-label {
      color: #6c5ce7;
      font-weight: 700;
      text-transform: uppercase;
      letter-spacing: 1.5px;
      font-size: 13px;
      margin-bottom: 14px;
    }

    h2 {
      font-size: clamp(34px, 5vw, 54px);
      line-height: 1.1;
      margin-bottom: 30px;
      letter-spacing: -1.5px;
    }

    .section-intro {
      max-width: 720px;
      font-size: 18px;
      color: #555;
      margin-bottom: 50px;
    }

    /* ABOUT */

    .about-grid {
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 70px;
      align-items: start;
    }

    .about-text p {
      margin-bottom: 20px;
      color: #444;
    }

    .belief-box {
      background: #1f1f1f;
      color: white;
      padding: 40px;
      border-radius: 14px;
    }

    .belief-box p {
      font-size: 24px;
      line-height: 1.4;
    }

    /* SERVICES */

    .services {
      background: white;
    }

    .cards {
      display: grid;
      grid-template-columns: repeat(3, 1fr);
      gap: 20px;
    }

    .card {
      border: 1px solid #dedbd4;
      border-radius: 14px;
      padding: 32px;
      transition: 0.2s ease;
      background: #fff;
    }

    .card:hover {
      transform: translateY(-5px);
      border-color: #6c5ce7;
    }

    .card h3 {
      margin-bottom: 15px;
      font-size: 22px;
    }

    .card p {
      color: #666;
      margin-bottom: 18px;
    }

    .card ul {
      padding-left: 18px;
      color: #444;
    }

    .card li {
      margin-bottom: 9px;
    }

    /* PROOF */

    .proof-grid {
      display: grid;
      grid-template-columns: repeat(3, 1fr);
      gap: 20px;
    }

    .proof-card {
      background: #eeeae3;
      border-radius: 14px;
      padding: 35px;
    }

    .proof-number {
      font-size: 38px;
      font-weight: 700;
      color: #6c5ce7;
      margin-bottom: 8px;
    }

    .proof-card p {
      color: #555;
    }

    /* WORK */

    .work {
      background: white;
    }

    .work-grid {
      display: grid;
      grid-template-columns: repeat(2, 1fr);
      gap: 24px;
    }

    .work-card {
      padding: 35px;
      border: 1px solid #dedbd4;
      border-radius: 14px;
    }

    .work-card span {
      font-size: 12px;
      text-transform: uppercase;
      color: #6c5ce7;
      font-weight: 700;
      letter-spacing: 1px;
    }

    .work-card h3 {
      font-size: 24px;
      margin: 12px 0;
    }

    .work-card p {
      color: #666;
      margin-bottom: 18px;
    }

    .work-card a {
      font-weight: 700;
      color: #6c5ce7;
    }

    /* PROCESS */

    .process-grid {
      display: grid;
      grid-template-columns: repeat(5, 1fr);
      gap: 15px;
    }

    .process-step {
      background: #1f1f1f;
      color: white;
      padding: 28px 20px;
      border-radius: 12px;
    }

    .process-number {
      color: #a99df3;
      font-size: 13px;
      font-weight: 700;
      margin-bottom: 15px;
    }

    .process-step h3 {
      font-size: 18px;
    }

    /* CTA */

    .cta {
      background: #6c5ce7;
      color: white;
      text-align: center;
    }

    .cta h2 {
      max-width: 800px;
      margin: 0 auto 20px;
    }

    .cta p {
      max-width: 620px;
      margin: 0 auto 30px;
      color: #ebe8ff;
    }

    .cta .btn {
      background: white;
      color: #1f1f1f;
    }

    /* FOOTER */

    footer {
      padding: 35px 0;
      border-top: 1px solid #dedbd4;
    }

    .footer-content {
      display: flex;
      justify-content: space-between;
      gap: 20px;
      font-size: 14px;
      color: #666;
    }

    /* MOBILE */

    @media (max-width: 800px) {
      .nav-links {
        display: none;
      }

      .about-grid,
      .cards,
      .proof-grid,
      .work-grid {
        grid-template-columns: 1fr;
      }

      .process-grid {
        grid-template-columns: 1fr 1fr;
      }

      h1 {
        letter-spacing: -2px;
      }

      .footer-content {
        flex-direction: column;
      }
    }

    @media (max-width: 500px) {
      .process-grid {
        grid-template-columns: 1fr;
      }

      section {
        padding: 75px 0;
      }
    }
  </style>
</head>

<body>

  <!-- NAVIGATION -->

  <nav>
    <div class="container nav-container">
      <div class="logo">Vartika Shukla.</div>

      <div class="nav-links">
        <a href="#about">About</a>
        <a href="#services">Services</a>
        <a href="#proof">Proof</a>
        <a href="#work">Work</a>
        <a href="#contact">Contact</a>
      </div>
    </div>
  </nav>


  <!-- HERO -->

  <header class="hero">
    <div class="container hero-content">

      <div class="eyebrow">
        Personal Branding Strategist + LinkedIn Ghostwriter
      </div>

      <h1>
        I turn expertise into a Personal Brand people remember.
      </h1>

      <p class="hero-description">
        I help founders, consultants and professionals turn what they know
        into clear positioning, strategic content and a reputation that starts
        selling before the first call.
      </p>

      <div class="hero-buttons">
        <a href="#work" class="btn btn-primary">
          See My Work
        </a>

        <a
          href="https://www.linkedin.com/in/YOUR-LINKEDIN-USERNAME/"
          target="_blank"
          class="btn btn-secondary"
        >
          Connect on LinkedIn
        </a>
      </div>

    </div>
  </header>


  <!-- ABOUT -->

  <section id="about">
    <div class="container">

      <div class="section-label">About</div>

      <h2>
        Writing is the medium.<br>
        Reputation is the goal.
      </h2>

      <div class="about-grid">

        <div class="about-text">

          <p>
            I'm Vartika, a Personal Branding Strategist and LinkedIn Ghostwriter.
          </p>

          <p>
            I work at the intersection of positioning, content and reputation.
            Because publishing more content isn't the same as building a brand.
          </p>

          <p>
            My job is to understand what makes someone's expertise valuable,
            find the ideas worth owning and turn them into communication people
            can recognise and trust.
          </p>

          <p>
            The goal isn't internet fame.
          </p>

          <p>
            It's becoming known for something valuable enough that the right
            opportunities start finding you.
          </p>

        </div>

        <div class="belief-box">
          <p>
            Your niche might help people find you.
            <br><br>
            Your perspective gives them a reason to remember you.
          </p>
        </div>

      </div>

    </div>
  </section>


  <!-- SERVICES -->

  <section id="services" class="services">
    <div class="container">

      <div class="section-label">Services</div>

      <h2>How I can help you.</h2>

      <p class="section-intro">
        Different problems need different levels of support.
        Here's where I work.
      </p>

      <div class="cards">

        <div class="card">
          <h3>Done For You</h3>

          <p>
            For professionals who want their Personal Brand strategically
            built and managed.
          </p>

          <ul>
            <li>Positioning</li>
            <li>LinkedIn Profile Optimisation</li>
            <li>Content Strategy</li>
            <li>LinkedIn Ghostwriting</li>
            <li>Personal Brand Strategy</li>
          </ul>
        </div>

        <div class="card">
          <h3>Coaching</h3>

          <p>
            For people who want to build their own brand but need strategy,
            structure and feedback.
          </p>

          <ul>
            <li>Personal Branding Strategy</li>
            <li>Positioning</li>
            <li>LinkedIn Strategy</li>
            <li>Content Direction</li>
            <li>Monetisation Strategy</li>
          </ul>
        </div>

        <div class="card">
          <h3>Consultation</h3>

          <p>
            For people who need clarity before investing in ongoing support.
          </p>

          <ul>
            <li>LinkedIn Audit</li>
            <li>Profile Review</li>
            <li>Positioning Review</li>
            <li>Content Strategy Review</li>
          </ul>
        </div>

      </div>

    </div>
  </section>


  <!-- PROOF -->

  <section id="proof">
    <div class="container">

      <div class="section-label">Proof</div>

      <h2>
        I prefer receipts over claims.
      </h2>

      <p class="section-intro">
        Some evidence from building, writing and experimenting with Personal
        Branding and LinkedIn.
      </p>

      <div class="proof-grid">

        <div class="proof-card">
          <div class="proof-number">64K+</div>
          <p>
            Impressions generated by a single strategic LinkedIn comment.
          </p>
        </div>

        <div class="proof-card">
          <div class="proof-number">300+</div>
          <p>
            Students reached through a LinkedIn and Personal Branding session.
          </p>
        </div>

        <div class="proof-card">
          <div class="proof-number">90 Days</div>
          <p>
            Used as an intensive period to study, test and build on LinkedIn.
          </p>
        </div>

      </div>

    </div>
  </section>


  <!-- WORK -->

  <section id="work" class="work">
    <div class="container">

      <div class="section-label">Selected Work</div>

      <h2>
        A few examples of how I think and write.
      </h2>

      <div class="work-grid">

        <div class="work-card">
          <span>Personal Branding</span>

          <h3>
            Your niche isn't your differentiation. Your perspective is.
          </h3>

          <p>
            A piece exploring why people become memorable because of how
            they interpret their niche, not simply because of the niche itself.
          </p>

          <a href="#" target="_blank">
            Read Sample →
          </a>
        </div>


        <div class="work-card">
          <span>Founder Branding</span>

          <h3>
            Reputation should work when you're not in the room.
          </h3>

          <p>
            A strategic piece connecting Personal Branding with leverage,
            trust and business scalability.
          </p>

          <a href="#" target="_blank">
            Read Sample →
          </a>
        </div>


        <div class="work-card">
          <span>Ghostwriting</span>

          <h3>
            Expertise → Words → Authority → Reputation
          </h3>

          <p>
            My approach to ghostwriting starts with extracting expertise,
            not manufacturing opinions.
          </p>

          <a href="#" target="_blank">
            Read Sample →
          </a>
        </div>


        <div class="work-card">
          <span>Strategy</span>

          <h3>
            Not every post is supposed to perform the same job.
          </h3>

          <p>
            A breakdown of discovery content, connection content and why
            impressions alone don't tell the full story.
          </p>

          <a href="#" target="_blank">
            Read Sample →
          </a>
        </div>

      </div>

    </div>
  </section>


  <!-- PROCESS -->

  <section>
    <div class="container">

      <div class="section-label">Process</div>

      <h2>
        How expertise becomes reputation.
      </h2>

      <div class="process-grid">

        <div class="process-step">
          <div class="process-number">01</div>
          <h3>Expertise</h3>
        </div>

        <div class="process-step">
          <div class="process-number">02</div>
          <h3>Positioning</h3>
        </div>

        <div class="process-step">
          <div class="process-number">03</div>
          <h3>Words</h3>
        </div>

        <div class="process-step">
          <div class="process-number">04</div>
          <h3>Authority</h3>
        </div>

        <div class="process-step">
          <div class="process-number">05</div>
          <h3>Reputation</h3>
        </div>

      </div>

    </div>
  </section>


  <!-- CONTACT -->

  <section id="contact" class="cta">
    <div class="container">

      <h2>
        Your expertise shouldn't need explaining from scratch on every call.
      </h2>

      <p>
        If you're building a Personal Brand and need clearer positioning,
        better content or someone to turn your expertise into words,
        let's talk.
      </p>

      <a
        href="https://www.linkedin.com/in/YOUR-LINKEDIN-USERNAME/"
        target="_blank"
        class="btn"
      >
        Message Me on LinkedIn
      </a>

    </div>
  </section>


  <!-- FOOTER -->

  <footer>
    <div class="container footer-content">

      <p>
        © 2026 Vartika Shukla
      </p>

      <p>
        Personal Branding Strategist + LinkedIn Ghostwriter
      </p>

    </div>
  </footer>

</body>
</html>
