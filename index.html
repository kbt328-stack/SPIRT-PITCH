<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
<title>The site is the easy part. — A free ops package for Spirit 2.0</title>
<meta name="description" content="A free, full-stack operations proposal for Hunter Peterson and the Let's Buy Spirit movement. From Kyle at Insightful Eye." />
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Playfair+Display:ital,wght@0,400;0,700;0,900;1,400;1,700;1,900&family=Newsreader:ital,opsz,wght@0,6..72,300;0,6..72,400;0,6..72,500;1,6..72,300;1,6..72,400&family=JetBrains+Mono:wght@300;400;500&display=swap" rel="stylesheet">
<style>
  :root {
    --ink: #0B0E14;
    --ink-2: #0F1320;
    --ink-3: #161B2C;
    --gold: #C9A961;
    --gold-bright: #E5C079;
    --gold-deep: #8C7338;
    --cream: #F2EBDA;
    --cream-2: #C9C0AC;
    --rule: rgba(201, 169, 97, 0.18);
    --rule-strong: rgba(201, 169, 97, 0.4);
  }

  * { box-sizing: border-box; margin: 0; padding: 0; }

  html { scroll-behavior: smooth; }

  body {
    background: var(--ink);
    color: var(--cream);
    font-family: 'Newsreader', Georgia, serif;
    font-weight: 300;
    font-size: 18px;
    line-height: 1.6;
    -webkit-font-smoothing: antialiased;
    overflow-x: hidden;
    background-image:
      radial-gradient(ellipse at 20% 0%, rgba(201, 169, 97, 0.08), transparent 50%),
      radial-gradient(ellipse at 80% 100%, rgba(201, 169, 97, 0.05), transparent 50%);
  }

  /* Subtle grain overlay */
  body::before {
    content: '';
    position: fixed;
    inset: 0;
    pointer-events: none;
    z-index: 100;
    opacity: 0.4;
    background-image: url("data:image/svg+xml,%3Csvg viewBox='0 0 400 400' xmlns='http://www.w3.org/2000/svg'%3E%3Cfilter id='n'%3E%3CfeTurbulence type='fractalNoise' baseFrequency='0.9' numOctaves='3' stitchTiles='stitch'/%3E%3C/filter%3E%3Crect width='100%25' height='100%25' filter='url(%23n)' opacity='0.5'/%3E%3C/svg%3E");
    mix-blend-mode: overlay;
  }

  .container {
    max-width: 1080px;
    margin: 0 auto;
    padding: 0 32px;
  }

  .narrow {
    max-width: 720px;
    margin: 0 auto;
    padding: 0 32px;
  }

  /* ==================== TOP BAR ==================== */
  .topbar {
    position: relative;
    border-bottom: 1px solid var(--rule);
    padding: 20px 0;
    z-index: 10;
  }
  .topbar-inner {
    display: flex;
    justify-content: space-between;
    align-items: baseline;
    font-family: 'JetBrains Mono', monospace;
    font-size: 11px;
    letter-spacing: 0.18em;
    text-transform: uppercase;
    color: var(--cream-2);
  }
  .topbar .brand {
    color: var(--gold);
    font-weight: 500;
  }
  .topbar .meta { display: flex; gap: 32px; }
  .topbar .meta span { opacity: 0.7; }

  /* ==================== HERO ==================== */
  .hero {
    padding: 100px 0 80px;
    position: relative;
  }

  .eyebrow {
    font-family: 'JetBrains Mono', monospace;
    font-size: 11px;
    letter-spacing: 0.3em;
    text-transform: uppercase;
    color: var(--gold);
    margin-bottom: 40px;
    display: flex;
    align-items: center;
    gap: 16px;
  }
  .eyebrow::before {
    content: '';
    width: 36px;
    height: 1px;
    background: var(--gold);
  }

  h1.headline {
    font-family: 'Playfair Display', serif;
    font-weight: 900;
    font-size: clamp(56px, 9vw, 120px);
    line-height: 0.92;
    letter-spacing: -0.025em;
    margin-bottom: 32px;
    color: var(--cream);
  }
  h1.headline em {
    font-style: italic;
    font-weight: 400;
    color: var(--gold);
  }

  .hero-sub {
    font-family: 'Newsreader', serif;
    font-style: italic;
    font-weight: 300;
    font-size: clamp(20px, 2.4vw, 28px);
    line-height: 1.4;
    color: var(--cream-2);
    max-width: 640px;
    margin-bottom: 48px;
  }

  .hero-meta {
    display: flex;
    flex-wrap: wrap;
    gap: 0;
    border-top: 1px solid var(--rule);
    border-bottom: 1px solid var(--rule);
    padding: 20px 0;
  }
  .hero-meta-item {
    flex: 1;
    min-width: 200px;
    padding: 8px 24px 8px 0;
    border-right: 1px solid var(--rule);
  }
  .hero-meta-item:last-child { border-right: none; }
  .hero-meta-label {
    font-family: 'JetBrains Mono', monospace;
    font-size: 10px;
    letter-spacing: 0.2em;
    text-transform: uppercase;
    color: var(--cream-2);
    opacity: 0.6;
    margin-bottom: 6px;
  }
  .hero-meta-value {
    font-family: 'Playfair Display', serif;
    font-size: 22px;
    font-weight: 700;
    color: var(--gold);
  }

  /* ==================== SECTION SHARED ==================== */
  section {
    padding: 100px 0;
    position: relative;
  }

  .section-num {
    font-family: 'JetBrains Mono', monospace;
    font-size: 11px;
    letter-spacing: 0.3em;
    color: var(--gold);
    margin-bottom: 24px;
    display: flex;
    align-items: center;
    gap: 12px;
  }
  .section-num span { opacity: 0.5; }

  h2 {
    font-family: 'Playfair Display', serif;
    font-weight: 700;
    font-size: clamp(40px, 5.5vw, 68px);
    line-height: 1;
    letter-spacing: -0.02em;
    margin-bottom: 48px;
    color: var(--cream);
  }
  h2 em {
    font-style: italic;
    font-weight: 400;
    color: var(--gold);
  }

  /* ==================== DIAGNOSIS ==================== */
  .diagnosis {
    border-top: 1px solid var(--rule);
  }
  .diagnosis p {
    font-family: 'Newsreader', serif;
    font-size: 22px;
    line-height: 1.55;
    color: var(--cream);
    margin-bottom: 24px;
  }
  .diagnosis p.lead::first-line {
    font-variant: small-caps;
    letter-spacing: 0.05em;
    color: var(--gold-bright);
  }
  .diagnosis .pull {
    font-family: 'Playfair Display', serif;
    font-style: italic;
    font-weight: 400;
    font-size: clamp(28px, 4vw, 44px);
    line-height: 1.2;
    color: var(--gold);
    margin: 56px 0;
    padding: 0 0 0 32px;
    border-left: 2px solid var(--gold);
  }

  /* ==================== THE BUILD ==================== */
  .build {
    background: var(--ink-2);
    border-top: 1px solid var(--rule);
    border-bottom: 1px solid var(--rule);
  }

  .layer {
    display: grid;
    grid-template-columns: 200px 1fr;
    gap: 48px;
    padding: 56px 0;
    border-bottom: 1px solid var(--rule);
    align-items: start;
  }
  .layer:last-child { border-bottom: none; }

  .layer-marker {
    font-family: 'JetBrains Mono', monospace;
    font-size: 11px;
    letter-spacing: 0.2em;
    color: var(--gold);
  }
  .layer-marker .num {
    font-family: 'Playfair Display', serif;
    font-size: 64px;
    font-weight: 900;
    line-height: 1;
    display: block;
    margin-bottom: 8px;
    color: var(--gold);
  }
  .layer-marker .when {
    color: var(--cream-2);
    opacity: 0.7;
    text-transform: uppercase;
    margin-top: 12px;
    display: block;
  }

  .layer h3 {
    font-family: 'Playfair Display', serif;
    font-weight: 700;
    font-size: clamp(28px, 3.5vw, 40px);
    line-height: 1.1;
    margin-bottom: 16px;
    color: var(--cream);
  }
  .layer h3 em {
    font-style: italic;
    font-weight: 400;
    color: var(--gold);
  }
  .layer p {
    font-size: 18px;
    line-height: 1.65;
    color: var(--cream-2);
  }
  .layer p + p { margin-top: 12px; }

  .stack {
    margin-top: 18px;
    display: flex;
    flex-wrap: wrap;
    gap: 8px;
  }
  .stack span {
    font-family: 'JetBrains Mono', monospace;
    font-size: 10px;
    letter-spacing: 0.15em;
    text-transform: uppercase;
    color: var(--gold);
    border: 1px solid var(--rule-strong);
    padding: 6px 12px;
    border-radius: 2px;
  }

  /* ==================== ARCHITECTURE ==================== */
  .arch {
    background: var(--ink);
    border-bottom: 1px solid var(--rule);
  }
  .arch-frame {
    margin-top: 32px;
    padding: 48px 24px;
    background: var(--ink-3);
    border: 1px solid var(--rule);
    border-radius: 4px;
  }
  .arch-frame svg { display: block; width: 100%; height: auto; }

  .arch-caption {
    font-family: 'JetBrains Mono', monospace;
    font-size: 11px;
    letter-spacing: 0.15em;
    text-transform: uppercase;
    color: var(--cream-2);
    opacity: 0.7;
    margin-top: 24px;
    text-align: center;
  }

  /* ==================== TIMELINE ==================== */
  .timeline ol {
    list-style: none;
    border-top: 1px solid var(--rule);
  }
  .timeline li {
    display: grid;
    grid-template-columns: 180px 1fr;
    gap: 32px;
    padding: 24px 0;
    border-bottom: 1px solid var(--rule);
    align-items: baseline;
  }
  .timeline .when {
    font-family: 'JetBrains Mono', monospace;
    font-size: 12px;
    letter-spacing: 0.18em;
    text-transform: uppercase;
    color: var(--gold);
  }
  .timeline .what {
    font-family: 'Newsreader', serif;
    font-size: 22px;
    line-height: 1.4;
    color: var(--cream);
  }
  .timeline .what em {
    font-style: italic;
    color: var(--gold-bright);
  }

  /* ==================== WHY ME ==================== */
  .why {
    background: var(--ink-2);
    border-top: 1px solid var(--rule);
    border-bottom: 1px solid var(--rule);
  }
  .why-grid {
    display: grid;
    grid-template-columns: repeat(2, 1fr);
    gap: 0;
    border-top: 1px solid var(--rule);
    border-left: 1px solid var(--rule);
  }
  .why-item {
    padding: 40px 32px;
    border-right: 1px solid var(--rule);
    border-bottom: 1px solid var(--rule);
  }
  .why-item .num {
    font-family: 'JetBrains Mono', monospace;
    font-size: 11px;
    letter-spacing: 0.2em;
    color: var(--gold);
    margin-bottom: 12px;
  }
  .why-item h4 {
    font-family: 'Playfair Display', serif;
    font-weight: 700;
    font-size: 24px;
    line-height: 1.2;
    margin-bottom: 12px;
    color: var(--cream);
  }
  .why-item h4 em {
    font-style: italic;
    color: var(--gold);
  }
  .why-item p {
    font-size: 16px;
    line-height: 1.6;
    color: var(--cream-2);
  }

  /* ==================== PERSONAL NOTE ==================== */
  .personal {
    background: var(--ink);
    border-top: 1px solid var(--rule);
    border-bottom: 1px solid var(--rule);
  }
  .letter {
    margin-top: 32px;
    padding: 56px 64px;
    background: var(--ink-2);
    border: 1px solid var(--rule-strong);
    position: relative;
  }
  .letter::before {
    content: '';
    position: absolute;
    inset: 8px;
    border: 1px solid var(--rule);
    pointer-events: none;
  }
  .letter-header {
    font-family: 'JetBrains Mono', monospace;
    font-size: 10px;
    letter-spacing: 0.25em;
    text-transform: uppercase;
    color: var(--cream-2);
    opacity: 0.6;
    margin-bottom: 32px;
    padding-bottom: 20px;
    border-bottom: 1px solid var(--rule);
    display: flex;
    justify-content: space-between;
  }
  .letter-salutation {
    font-family: 'Playfair Display', serif;
    font-style: italic;
    font-weight: 400;
    font-size: 28px;
    color: var(--gold);
    margin-bottom: 28px;
  }
  .letter p {
    font-family: 'Newsreader', serif;
    font-style: italic;
    font-weight: 300;
    font-size: 21px;
    line-height: 1.65;
    color: var(--cream);
    margin-bottom: 24px;
  }
  .letter p em {
    font-style: normal;
    color: var(--gold-bright);
  }
  .letter .sign {
    font-family: 'Playfair Display', serif;
    font-style: italic;
    font-weight: 700;
    font-size: 36px;
    color: var(--gold);
    margin-top: 40px;
    padding-top: 32px;
    border-top: 1px solid var(--rule);
  }
  .letter .sign-meta {
    font-family: 'JetBrains Mono', monospace;
    font-size: 11px;
    letter-spacing: 0.2em;
    text-transform: uppercase;
    color: var(--cream-2);
    opacity: 0.7;
    margin-top: 8px;
  }
  @media (max-width: 768px) {
    .letter { padding: 32px 24px; }
    .letter::before { inset: 6px; }
    .letter p { font-size: 17px; }
    .letter .sign { font-size: 28px; }
    .letter-salutation { font-size: 22px; }
    .letter-header { flex-direction: column; gap: 4px; }
  }

  /* ==================== TERMS ==================== */
  .terms {
    text-align: center;
    padding: 140px 0;
  }
  .terms-list {
    list-style: none;
    margin: 48px auto 0;
    max-width: 640px;
  }
  .terms-list li {
    font-family: 'Playfair Display', serif;
    font-style: italic;
    font-weight: 400;
    font-size: clamp(28px, 4vw, 42px);
    line-height: 1.4;
    color: var(--cream);
    padding: 16px 0;
    border-bottom: 1px solid var(--rule);
  }
  .terms-list li:last-child { border-bottom: none; }
  .terms-list li strong {
    font-family: 'Playfair Display', serif;
    font-style: normal;
    font-weight: 900;
    color: var(--gold);
  }

  .terms-coda {
    margin-top: 64px;
    font-family: 'Newsreader', serif;
    font-style: italic;
    font-size: 22px;
    line-height: 1.5;
    color: var(--cream-2);
    max-width: 560px;
    margin-left: auto;
    margin-right: auto;
  }

  /* ==================== CTA ==================== */
  .cta {
    background: linear-gradient(180deg, var(--ink) 0%, var(--ink-3) 100%);
    border-top: 1px solid var(--gold);
    text-align: center;
    padding: 120px 0;
  }
  .cta h2 {
    margin-bottom: 24px;
  }
  .cta p.sub {
    font-family: 'Newsreader', serif;
    font-style: italic;
    font-size: 24px;
    color: var(--cream-2);
    margin-bottom: 56px;
  }
  .cta-channels {
    display: flex;
    justify-content: center;
    gap: 24px;
    flex-wrap: wrap;
  }
  .cta-channel {
    border: 1px solid var(--gold);
    padding: 20px 32px;
    text-decoration: none;
    color: var(--gold);
    font-family: 'JetBrains Mono', monospace;
    font-size: 14px;
    letter-spacing: 0.12em;
    text-transform: uppercase;
    transition: all 0.3s ease;
    position: relative;
    overflow: hidden;
  }
  .cta-channel::before {
    content: '';
    position: absolute;
    inset: 0;
    background: var(--gold);
    transform: translateY(100%);
    transition: transform 0.3s ease;
    z-index: -1;
  }
  .cta-channel:hover {
    color: var(--ink);
  }
  .cta-channel:hover::before {
    transform: translateY(0);
  }
  .cta-channel { z-index: 1; isolation: isolate; }
  .cta-channel span { display: block; font-size: 11px; opacity: 0.6; margin-bottom: 4px; }

  /* ==================== FOOTER ==================== */
  footer {
    border-top: 1px solid var(--rule);
    padding: 40px 0;
    background: var(--ink);
  }
  .footer-inner {
    display: flex;
    justify-content: space-between;
    align-items: center;
    flex-wrap: wrap;
    gap: 24px;
    font-family: 'JetBrains Mono', monospace;
    font-size: 11px;
    letter-spacing: 0.18em;
    text-transform: uppercase;
    color: var(--cream-2);
    opacity: 0.7;
  }
  .footer-inner .tagline {
    font-family: 'Playfair Display', serif;
    font-style: italic;
    font-size: 16px;
    color: var(--gold);
    text-transform: none;
    letter-spacing: 0;
  }

  /* ==================== ANIMATIONS ==================== */
  @keyframes fadeUp {
    from { opacity: 0; transform: translateY(30px); }
    to { opacity: 1; transform: translateY(0); }
  }
  .hero h1.headline { animation: fadeUp 1.2s ease both; }
  .hero .hero-sub { animation: fadeUp 1.2s ease 0.2s both; }
  .hero .hero-meta { animation: fadeUp 1.2s ease 0.4s both; }
  .hero .eyebrow { animation: fadeUp 1.2s ease both; }

  /* ==================== RESPONSIVE ==================== */
  @media (max-width: 768px) {
    body { font-size: 16px; }
    .container, .narrow { padding: 0 24px; }
    .hero { padding: 64px 0 56px; }
    section { padding: 64px 0; }

    .layer { grid-template-columns: 1fr; gap: 16px; padding: 40px 0; }
    .layer-marker .num { font-size: 48px; }

    .timeline li { grid-template-columns: 1fr; gap: 8px; }

    .why-grid { grid-template-columns: 1fr; }

    .topbar-inner { flex-direction: column; gap: 8px; align-items: flex-start; }
    .topbar .meta { gap: 16px; }

    .hero-meta { flex-direction: column; }
    .hero-meta-item { border-right: none; border-bottom: 1px solid var(--rule); padding: 12px 0; }
    .hero-meta-item:last-child { border-bottom: none; }
  }
</style>
</head>
<body>

<!-- =============== TOP BAR =============== -->
<div class="topbar">
  <div class="container topbar-inner">
    <div class="brand">Insightful Eye</div>
    <div class="meta">
      <span>Confidential proposal</span>
      <span>For: Hunter Peterson</span>
      <span>Re: Spirit 2.0</span>
    </div>
  </div>
</div>

<!-- =============== HERO =============== -->
<header class="hero">
  <div class="container">
    <div class="eyebrow">A free, full-stack ops package for Spirit 2.0</div>
    <h1 class="headline">The site is <em>the easy part.</em></h1>
    <p class="hero-sub">Thirty-seven thousand people just pledged to a movement built on a website you put together in an hour. The site can be rebuilt in an afternoon. The system around it is what determines whether this becomes an airline or a footnote.</p>
    <div class="hero-meta">
      <div class="hero-meta-item">
        <div class="hero-meta-label">Cost to you</div>
        <div class="hero-meta-value">$0</div>
      </div>
      <div class="hero-meta-item">
        <div class="hero-meta-label">Time to live</div>
        <div class="hero-meta-value">48 hours</div>
      </div>
      <div class="hero-meta-item">
        <div class="hero-meta-label">Decision needed</div>
        <div class="hero-meta-value">A reply</div>
      </div>
    </div>
  </div>
</header>

<!-- =============== DIAGNOSIS =============== -->
<section class="diagnosis">
  <div class="narrow">
    <div class="section-num"><span>01 —</span> Diagnosis</div>
    <h2>What I see right <em>now.</em></h2>
    <p class="lead">You have thirty-seven thousand founding patrons who pledged in roughly thirty-six hours. Their data is sitting in a Manus-generated database that was not designed to hold a movement. Your inbox is being shared by developers, journalists, aviation lawyers, venture capitalists, employees of a now-defunct airline, and the patrons themselves — all funneled through one human being who has not slept.</p>
    <p>The website is the visible part. It is also the simplest part. What is about to bury you is the operational layer underneath it — pledger relationship management, automated communications, inbound triage, financial transparency tooling, and the digital scaffolding that the FAA conversation will eventually demand.</p>
    <div class="pull">"If you're a developer, please reach out." — That is what you said. This is more than that.</div>
    <p>I run a GoHighLevel and AI-automation studio out of Rhode Island. The stack you need does not need to be invented. It already exists, and I already build it for paying clients. I am offering to build it for you for free, because the model — community ownership, one member one vote, transparent books — deserves competent infrastructure, not another janky weekend project.</p>
  </div>
</section>

<!-- =============== THE BUILD =============== -->
<section class="build">
  <div class="container">
    <div class="section-num"><span>02 —</span> The build</div>
    <h2>Four layers. <em>One operator.</em></h2>

    <div class="layer">
      <div class="layer-marker">
        <span class="num">I</span>
        Public surface
        <span class="when">Live in 48 hours</span>
      </div>
      <div>
        <h3>A site that <em>does not crash.</em></h3>
        <p>Next.js on Vercel, edge-cached across eighteen global regions, fronted by Cloudflare with full DDoS mitigation and per-IP rate limiting. hCaptcha on the pledge form. Sentry on every error path. Stale-while-revalidate caching keeps the homepage up even if the database briefly hiccups. Load-tested against simulated viral spikes before DNS cuts over. Survives a million visitors per hour — and stays up if you go viral on TikTok again at two in the morning.</p>
        <p>Pledge flow rebuilt for capture: multi-step progressive profiling so a hesitant visitor commits to email before they decide on amount; UTM tagging on every inbound source so you actually know what is converting; a founding-patron number assigned at submission with a shareable receipt graphic; built-in referral codes so every patron can recruit two more with one tap.</p>
        <div class="stack">
          <span>Next.js 15</span><span>Vercel Edge</span><span>Cloudflare</span><span>hCaptcha</span><span>Sentry</span><span>Postgres</span>
        </div>
      </div>
    </div>

    <div class="layer">
      <div class="layer-marker">
        <span class="num">II</span>
        Pledger CRM
        <span class="when">Operational by day 7</span>
      </div>
      <div>
        <h3>A real database for <em>thirty-seven thousand humans.</em></h3>
        <p>Every founding patron tracked in GoHighLevel: pledge amount, timestamp, contact preference, geographic origin, governance vote eligibility, inbound traffic source, referral chain. Day-zero welcome sequence with proof of non-binding intent. Milestone updates triggered automatically. FAQ deflection so the same five questions stop hitting your DMs four thousand times each.</p>
        <p>Every patron gets a shareable status page. Every patron has a referral code. Every patron is identifiable as a real human via lightweight verification — so the governance conversation later is not undermined by bot-pledger doubts. Trust scales when communication scales. Capture compounds when patrons can pull other patrons in.</p>
        <div class="stack">
          <span>GoHighLevel</span><span>Twilio Verify</span><span>SendGrid</span><span>Referral chains</span><span>Status pages</span>
        </div>
      </div>
    </div>

    <div class="layer">
      <div class="layer-marker">
        <span class="num">III</span>
        Inbound triage
        <span class="when">Live by day 14</span>
      </div>
      <div>
        <h3>An AI agent at the front of <em>every inbox.</em></h3>
        <p>Claude API plus an ElevenLabs voice persona — internally we call her Iris — sitting in front of email, DMs, and the contact form. Categorizes inbound on arrival: developer offer, press inquiry, aviation legal, patron question, VC outreach, employment inquiry, vendor pitch, other. Routes each into its own queue. Auto-responds to the trivial. Surfaces the urgent. You stop drowning. You start replying only to the messages that actually require you.</p>
        <div class="stack">
          <span>Claude API</span><span>ElevenLabs</span><span>n8n</span><span>OpenRouter</span>
        </div>
      </div>
    </div>

    <div class="layer">
      <div class="layer-marker">
        <span class="num">IV</span>
        Governance scaffold
        <span class="when">Drafted by day 21</span>
      </div>
      <div>
        <h3>The Packers comparison made <em>operational.</em></h3>
        <p>One-member-one-vote infrastructure: voter registry, pledge-weighted dividend ledger schema, transparent financial dashboard, ESOP-ready employee equity scaffolding. I will not draft your corporate vehicle — that is your aviation counsel's job — but I will hand them a digital system that makes the model executable from day one of operations rather than year three.</p>
        <div class="stack">
          <span>Postgres</span><span>Public dashboard</span><span>Audit log</span><span>Open books</span>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- =============== ARCHITECTURE DIAGRAM =============== -->
<section class="arch">
  <div class="container">
    <div class="section-num"><span>03 —</span> Architecture</div>
    <h2>How the <em>pieces fit.</em></h2>
    <div class="arch-frame">
      <svg viewBox="0 0 1000 540" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Spirit 2.0 architecture diagram">
        <defs>
          <marker id="arrow" viewBox="0 0 10 10" refX="9" refY="5" markerWidth="8" markerHeight="8" orient="auto-start-reverse">
            <path d="M0,0 L10,5 L0,10 z" fill="#C9A961" />
          </marker>
          <linearGradient id="goldFade" x1="0" x2="1">
            <stop offset="0" stop-color="#C9A961" stop-opacity="0.0"/>
            <stop offset="0.5" stop-color="#C9A961" stop-opacity="0.6"/>
            <stop offset="1" stop-color="#C9A961" stop-opacity="0.0"/>
          </linearGradient>
        </defs>

        <!-- background grid -->
        <g opacity="0.06" stroke="#C9A961">
          <path d="M0 90 H1000" /><path d="M0 180 H1000" /><path d="M0 270 H1000" /><path d="M0 360 H1000" /><path d="M0 450 H1000" />
        </g>

        <!-- LEFT: Inbound sources -->
        <g font-family="'JetBrains Mono', monospace" font-size="11" letter-spacing="1.5">
          <text x="60" y="40" fill="#C9A961" font-weight="500">INBOUND</text>
          <line x1="60" y1="50" x2="200" y2="50" stroke="url(#goldFade)" />
        </g>

        <g>
          <rect x="40" y="80" width="180" height="50" rx="2" fill="none" stroke="#C9A961" stroke-opacity="0.5"/>
          <text x="55" y="105" fill="#F2EBDA" font-family="'Newsreader', serif" font-size="14">Pledger traffic</text>
          <text x="55" y="120" fill="#C9C0AC" font-family="'JetBrains Mono', monospace" font-size="9" letter-spacing="1">37K+ AND CLIMBING</text>

          <rect x="40" y="160" width="180" height="50" rx="2" fill="none" stroke="#C9A961" stroke-opacity="0.5"/>
          <text x="55" y="185" fill="#F2EBDA" font-family="'Newsreader', serif" font-size="14">Press inquiries</text>
          <text x="55" y="200" fill="#C9C0AC" font-family="'JetBrains Mono', monospace" font-size="9" letter-spacing="1">CBS · WSJ · TC</text>

          <rect x="40" y="240" width="180" height="50" rx="2" fill="none" stroke="#C9A961" stroke-opacity="0.5"/>
          <text x="55" y="265" fill="#F2EBDA" font-family="'Newsreader', serif" font-size="14">Developer offers</text>
          <text x="55" y="280" fill="#C9C0AC" font-family="'JetBrains Mono', monospace" font-size="9" letter-spacing="1">DMs &amp; emails</text>

          <rect x="40" y="320" width="180" height="50" rx="2" fill="none" stroke="#C9A961" stroke-opacity="0.5"/>
          <text x="55" y="345" fill="#F2EBDA" font-family="'Newsreader', serif" font-size="14">Aviation legal</text>
          <text x="55" y="360" fill="#C9C0AC" font-family="'JetBrains Mono', monospace" font-size="9" letter-spacing="1">FAA · counsel</text>

          <rect x="40" y="400" width="180" height="50" rx="2" fill="none" stroke="#C9A961" stroke-opacity="0.5"/>
          <text x="55" y="425" fill="#F2EBDA" font-family="'Newsreader', serif" font-size="14">VC / capital</text>
          <text x="55" y="440" fill="#C9C0AC" font-family="'JetBrains Mono', monospace" font-size="9" letter-spacing="1">NON-VOTING ONLY</text>
        </g>

        <!-- arrows from inbound to triage -->
        <g stroke="#C9A961" stroke-opacity="0.55" fill="none" marker-end="url(#arrow)">
          <path d="M225 105 C 300 105, 320 250, 395 260" />
          <path d="M225 185 C 300 185, 320 255, 395 265" />
          <path d="M225 265 H 395" />
          <path d="M225 345 C 300 345, 320 280, 395 275" />
          <path d="M225 425 C 300 425, 320 290, 395 280" />
        </g>

        <!-- CENTER: Iris triage -->
        <g>
          <rect x="395" y="220" width="210" height="100" rx="3" fill="#0F1320" stroke="#E5C079" stroke-width="1.5"/>
          <text x="500" y="245" text-anchor="middle" fill="#E5C079" font-family="'JetBrains Mono', monospace" font-size="10" letter-spacing="2">AI TRIAGE LAYER</text>
          <text x="500" y="278" text-anchor="middle" fill="#F2EBDA" font-family="'Playfair Display', serif" font-style="italic" font-size="26" font-weight="400">Iris</text>
          <text x="500" y="302" text-anchor="middle" fill="#C9C0AC" font-family="'JetBrains Mono', monospace" font-size="9" letter-spacing="1.5">CLAUDE · ELEVENLABS</text>
        </g>

        <!-- arrow from triage to systems -->
        <g stroke="#C9A961" stroke-opacity="0.55" fill="none" marker-end="url(#arrow)">
          <path d="M605 245 C 680 245, 700 110, 770 110" />
          <path d="M605 270 H 770" />
          <path d="M605 295 C 680 295, 700 430, 770 430" />
        </g>

        <!-- RIGHT: Systems of record -->
        <g font-family="'JetBrains Mono', monospace" font-size="11" letter-spacing="1.5">
          <text x="770" y="40" fill="#C9A961" font-weight="500">SYSTEMS</text>
          <line x1="770" y1="50" x2="940" y2="50" stroke="url(#goldFade)" />
        </g>

        <g>
          <rect x="770" y="85" width="190" height="50" rx="2" fill="none" stroke="#C9A961" stroke-opacity="0.5"/>
          <text x="785" y="110" fill="#F2EBDA" font-family="'Newsreader', serif" font-size="14">Public site</text>
          <text x="785" y="125" fill="#C9C0AC" font-family="'JetBrains Mono', monospace" font-size="9" letter-spacing="1">VERCEL · CLOUDFLARE</text>

          <rect x="770" y="245" width="190" height="50" rx="2" fill="none" stroke="#C9A961" stroke-opacity="0.5"/>
          <text x="785" y="270" fill="#F2EBDA" font-family="'Newsreader', serif" font-size="14">Pledger CRM</text>
          <text x="785" y="285" fill="#C9C0AC" font-family="'JetBrains Mono', monospace" font-size="9" letter-spacing="1">GOHIGHLEVEL</text>

          <rect x="770" y="405" width="190" height="50" rx="2" fill="none" stroke="#C9A961" stroke-opacity="0.5"/>
          <text x="785" y="430" fill="#F2EBDA" font-family="'Newsreader', serif" font-size="14">Governance ledger</text>
          <text x="785" y="445" fill="#C9C0AC" font-family="'JetBrains Mono', monospace" font-size="9" letter-spacing="1">POSTGRES · OPEN BOOKS</text>
        </g>

        <!-- bottom outflow -->
        <g stroke="#C9A961" stroke-opacity="0.4" fill="none" stroke-dasharray="3,4">
          <path d="M865 135 V 245" />
          <path d="M865 295 V 405" />
        </g>

        <!-- HUNTER node bottom center -->
        <g>
          <circle cx="500" cy="490" r="32" fill="none" stroke="#E5C079" stroke-width="1.5"/>
          <text x="500" y="496" text-anchor="middle" fill="#E5C079" font-family="'Playfair Display', serif" font-size="14" font-style="italic">Hunter</text>
        </g>
        <g stroke="#E5C079" stroke-opacity="0.6" fill="none" marker-end="url(#arrow)" stroke-dasharray="2,3">
          <path d="M500 458 V 325" />
        </g>
        <text x="510" y="400" fill="#C9C0AC" font-family="'JetBrains Mono', monospace" font-size="9" letter-spacing="1.5">ESCALATION ONLY</text>
      </svg>
    </div>
    <div class="arch-caption">Iris fields inbound. Hunter sees only what requires Hunter.</div>
  </div>
</section>

<!-- =============== TIMELINE =============== -->
<section class="timeline">
  <div class="narrow">
    <div class="section-num"><span>04 —</span> Timeline</div>
    <h2>From reply <em>to running.</em></h2>
    <ol>
      <li>
        <span class="when">Hour 0</span>
        <span class="what">You reply to my DM. I send a one-page scope and a Loom of the staging environment already half-built.</span>
      </li>
      <li>
        <span class="when">Hour 6</span>
        <span class="what">Site rebuilt on production-grade infrastructure. Staging URL in your hands for sign-off.</span>
      </li>
      <li>
        <span class="when">Hour 24</span>
        <span class="what">DNS cut. <em>letsbuyspirit.com</em> live on the new stack. Pledge form re-enabled with proper validation.</span>
      </li>
      <li>
        <span class="when">Day 7</span>
        <span class="what">All 37K+ existing pledgers imported into GoHighLevel. Day-zero welcome sequence triggered. Status pages live.</span>
      </li>
      <li>
        <span class="when">Day 14</span>
        <span class="what">Iris is live across DM and email. Inbound categorized and routed. Your effective inbox shrinks by ninety percent.</span>
      </li>
      <li>
        <span class="when">Day 21</span>
        <span class="what">Governance scaffold drafted, handed to your aviation counsel for review. Public financial dashboard online.</span>
      </li>
    </ol>
  </div>
</section>

<!-- =============== WHY ME =============== -->
<section class="why">
  <div class="container">
    <div class="section-num"><span>05 —</span> Why me</div>
    <h2>Operator, <em>not pitchman.</em></h2>
    <div class="why-grid">
      <div class="why-item">
        <div class="num">/ 01</div>
        <h4>The stack is <em>already mine.</em></h4>
        <p>Insightful Eye runs on exactly this architecture for paying clients. GoHighLevel, Vercel, Claude API, ElevenLabs, n8n. Nothing here is theoretical or freshly Googled.</p>
      </div>
      <div class="why-item">
        <div class="num">/ 02</div>
        <h4>I solo-ship <em>real businesses.</em></h4>
        <p>Renaissance Auto Recovery, TT Pro Scapes, Dog Gone Spoiled, Insightful Eye itself. Every site, every automation, every voice agent — built and operated by one person. I move fast because I have to.</p>
      </div>
      <div class="why-item">
        <div class="num">/ 03</div>
        <h4>Voice agents <em>in production.</em></h4>
        <p>Iris is not a concept. She is the front-of-house for our $499 AI Audit offer. The triage layer described above is a known quantity I have already shipped.</p>
      </div>
      <div class="why-item">
        <div class="num">/ 04</div>
        <h4>Rhode Island, <em>not Sand Hill.</em></h4>
        <p>I am not a fund. I am not an incubator. I am not building a personal brand off your movement. I am betting my time on a thing I believe in. The rest figures itself out later.</p>
      </div>
    </div>
  </div>
</section>

<!-- =============== PERSONAL NOTE =============== -->
<section class="personal">
  <div class="narrow">
    <div class="section-num"><span>06 —</span> A note from the operator</div>
    <h2>Why this <em>isn't abstract.</em></h2>
    <div class="letter">
      <div class="letter-header">
        <span>Providence, Rhode Island</span>
        <span>May 2026</span>
      </div>
      <div class="letter-salutation">Dear Hunter,</div>
      <p>I am a Rhode Island native, running a small shop out of Providence. Spirit operated out of PVD and Boston — both within thirty minutes of my front door. The 3 a.m. shutdown text reached people I know. This is not abstract to me.</p>
      <p>I am not a fund. I am not an agency. I am one operator running a six-business stack solo, from a state most venture money flies over. If a thing called <em>owned by the people</em> is going to mean anything, the scaffolding under it has to be built by operators whose incentives do not pull against the patrons. Mine do not.</p>
      <p>For what it is worth — I came forward as a whistleblower in a case handled by the Massachusetts Attorney General's office. I would rather not foreground it. But the kind of governance system you are trying to build requires operators who choose transparency when it is costly, not when it is convenient. So you should know.</p>
      <p>Small. Local. For the people. Same side as you. My name attached to this is enough for now.</p>
      <div class="sign">— Kyle</div>
      <div class="sign-meta">Insightful Eye · Providence, RI</div>
    </div>
  </div>
</section>

<!-- =============== TERMS =============== -->
<section class="terms">
  <div class="narrow">
    <div class="section-num" style="justify-content: center;"><span>07 —</span> The terms</div>
    <h2>Plain <em>English.</em></h2>
    <ul class="terms-list">
      <li>Zero <strong>fee.</strong></li>
      <li>Zero <strong>strings.</strong></li>
      <li>No NDA. No <strong>preferred shares.</strong></li>
      <li>Source code is <strong>yours</strong> from day one.</li>
      <li>Fire me <strong>any time.</strong></li>
    </ul>
    <p class="terms-coda">Right now I am not asking for anything. Let's get something real built. The rest is the easy part once there is a "rest."</p>
  </div>
</section>

<!-- =============== CTA =============== -->
<section class="cta">
  <div class="narrow">
    <h2>Reply <em>and I start tonight.</em></h2>
    <p class="sub">Three channels. Whichever you check first.</p>
    <div class="cta-channels">
      <a class="cta-channel" href="https://instagram.com/spiritair2.0" target="_blank" rel="noopener">
        <span>Campaign account</span>
        @spiritair2.0
      </a>
      <a class="cta-channel" href="https://instagram.com/hitherehunter" target="_blank" rel="noopener">
        <span>Personal account</span>
        @hitherehunter
      </a>
      <a class="cta-channel" href="mailto:Kbt328@gmail.com">
        <span>Direct</span>
        Kbt328@gmail.com
      </a>
    </div>
  </div>
</section>

<!-- =============== FOOTER =============== -->
<footer>
  <div class="container footer-inner">
    <div>Insightful Eye · Rhode Island · 2026</div>
    <div class="tagline">Grow Smarter, Not Harder.</div>
    <div>Page built in &lt; 2 hrs. So can yours.</div>
  </div>
</footer>

</body>
</html>
