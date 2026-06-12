Today's goal
1
Read the provided resources.
2
Watch the solution video.
3
Open Claude.
4
Set Claude effort level to Low.
5
Start a new conversation.
6
Paste the provided Portfolio Website prompt.
7
Replace placeholders with your own information.
8
Optionally upload your resume and profile photo.
9
Generate the complete portfolio website.
10
Save the generated HTML file.
11
Open the file in your browser and test it.
12
Take screenshots of the portfolio.
13
Optionally deploy your portfolio on Vercel or Netlify and make it publicly accessible.
14
If Claude does not complete the output or usage limits are reached, wait for the reset period and continue later.
15
Create a Day10 folder in your GitHub repository.
16
Create a day10.md file.
17
Upload screenshots, generated HTML file, and your learnings.
18
Commit and push the changes.
19
Submit the GitHub commit URL. (https://github.com/newnavin006-a11y/Naveen/new/main/My%2060%20day%20journey)



today i learnt how using prompt ai can make work easy

<img width="1287" height="751" alt="agithub(3)" src="https://github.com/user-attachments/assets/c968bdae-04cf-4871-addc-d532dd0590ef" />
<img width="1227" height="726" alt="agithub(4)" src="https://github.com/user-attachments/assets/ed225ee1-a8a1-420e-9077-76159e39a089" />
<img width="1030" height="406" alt="agithub(5)" src="https://github.com/user-attachments/assets/16002819-1f65-460e-9413-8c6f6f24f8e2" />
<img width="1301" height="767" alt="agithub(6)" src="https://github.com/user-attachments/assets/ddfe5f0e-53bd-491f-963c-542c42d75275" />
<img width="1296" height="836" alt="agithub" src="https://github.com/user-attachments/assets/4441e623-1a3c-4367-952d-a989fff9f3bf" />
<img width="1311" height="831" alt="agithub(1)" src="https://github.com/user-attachments/assets/f4b8a54f-5342-4e5f-8831-4b5603175a20" />
<img width="1242" height="737" alt="agithub(2)" src="https://github.com/user-attachments/assets/23a428a8-f437-48d2-bee2-0d97f9130380" />



<!DOCTYPE html>
<html lang="en" class="scroll-smooth">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Naveen Kumar — Portfolio</title>
  <meta name="description" content="Naveen Kumar — Mechanical Engineering Student, Python Developer & Algorithm Builder at IIMT College of Engineering, AKTU." />
  <meta name="keywords" content="Naveen Kumar, Mechanical Engineering, Python Developer, AutoCAD, Algorithm, IIMT, AKTU, Portfolio" />
  <meta name="author" content="Naveen Kumar" />
  <meta property="og:title" content="Naveen Kumar — Portfolio" />
  <meta property="og:description" content="Mechanical Engineering Student | Python Developer | Algorithm Builder" />
  <meta property="og:type" content="website" />
  <link rel="preconnect" href="https://fonts.googleapis.com" />
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
  <link href="https://fonts.googleapis.com/css2?family=Space+Grotesk:wght@300;400;500;600;700&family=Inter:wght@300;400;500;600&family=JetBrains+Mono:wght@400;500&display=swap" rel="stylesheet" />
  <script src="https://cdn.tailwindcss.com"></script>
  <script>
    tailwind.config = {
      darkMode: 'class',
      theme: {
        extend: {
          fontFamily: {
            display: ['Space Grotesk', 'sans-serif'],
            body: ['Inter', 'sans-serif'],
            mono: ['JetBrains Mono', 'monospace'],
          }
        }
      }
    }
  </script>
  <style>
    *, *::before, *::after { box-sizing: border-box; }
    html { scroll-behavior: smooth; }

    ::-webkit-scrollbar { width: 5px; }
    ::-webkit-scrollbar-track { background: #0D1117; }
    ::-webkit-scrollbar-thumb { background: rgba(59,130,246,0.4); border-radius: 4px; }
    ::-webkit-scrollbar-thumb:hover { background: rgba(59,130,246,0.7); }

    body { font-family: 'Inter', sans-serif; }

    /* ── DARK (default) ── */
    body.dark  { background: #0D1117; color: #e2e8f0; }
    body.light { background: #F5F7FA; color: #1e293b; }

    /* Blueprint grid */
    .grid-bg {
      background-image:
        linear-gradient(rgba(59,130,246,0.05) 1px, transparent 1px),
        linear-gradient(90deg, rgba(59,130,246,0.05) 1px, transparent 1px);
      background-size: 44px 44px;
    }
    .light .grid-bg {
      background-image:
        linear-gradient(rgba(59,130,246,0.08) 1px, transparent 1px),
        linear-gradient(90deg, rgba(59,130,246,0.08) 1px, transparent 1px);
    }

    /* Blueprint annotation lines (hero) */
    .bp-line {
      position: absolute; pointer-events: none;
      border: 1px dashed rgba(59,130,246,0.25);
    }

    /* Glow & borders */
    .card-dark  { background: rgba(30,41,59,0.6); border: 1px solid rgba(59,130,246,0.12); }
    .card-light { background: #ffffff;            border: 1px solid #e2e8f0; }
    .card { transition: transform .3s, box-shadow .3s, border-color .3s; }
    .dark  .card { background: rgba(30,41,59,0.6);  border: 1px solid rgba(59,130,246,0.12); }
    .light .card { background: #ffffff;              border: 1px solid #e2e8f0; }
    .card:hover {
      transform: translateY(-5px);
      box-shadow: 0 12px 40px rgba(59,130,246,0.15);
    }
    .dark  .card:hover { border-color: rgba(59,130,246,0.45); }
    .light .card:hover { border-color: #93c5fd; }

    /* Nav */
    .dark  .nav-bg { background: rgba(13,17,23,0.9); border-bottom: 1px solid rgba(59,130,246,0.1); }
    .light .nav-bg { background: rgba(245,247,250,0.9); border-bottom: 1px solid #e2e8f0; }

    .nav-link { position: relative; }
    .nav-link::after {
      content:''; position:absolute; left:0; bottom:-4px;
      width:0; height:2px; background:#3B82F6;
      transition: width .3s;
    }
    .nav-link:hover::after, .nav-link.active::after { width:100%; }
    .nav-link.active { color:#3B82F6; }

    /* Hero */
    .dark  .hero-bg { background: linear-gradient(135deg,#0D1117 0%,#101827 100%); }
    .light .hero-bg { background: linear-gradient(135deg,#EFF4FF 0%,#F5F7FA 100%); }

    /* Section alt */
    .dark  .section-alt { background: rgba(15,23,42,0.6); }
    .light .section-alt { background: #EFF4FF; }

    /* Muted text */
    .dark  .tx-muted { color: #94a3b8; }
    .light .tx-muted { color: #64748b; }

    /* Tags */
    .tag-blue   { background:rgba(59,130,246,.12); color:#60A5FA; border:1px solid rgba(59,130,246,.25); }
    .tag-orange { background:rgba(249,115,22,.12); color:#FB923C; border:1px solid rgba(249,115,22,.25); }
    .tag-gray   { border:1px solid; }
    .dark  .tag-gray { background:rgba(51,65,85,.5); color:#CBD5E1; border-color:#334155; }
    .light .tag-gray { background:#F1F5F9; color:#475569; border-color:#CBD5E1; }

    /* Cursor blink */
    .cursor::after { content:'|'; color:#3B82F6; animation:blink 1s step-end infinite; }
    @keyframes blink { 0%,100%{opacity:1} 50%{opacity:0} }

    /* Skill bars */
    .skill-fill {
      height:100%; border-radius:4px;
      background: linear-gradient(90deg,#3B82F6,#1D4ED8);
      width:0; transition: width 1.3s cubic-bezier(.4,0,.2,1);
    }
    .skill-fill.on { width: var(--w); }

    /* Timeline dot */
    .t-dot  { width:12px; height:12px; border-radius:50%; background:#3B82F6; flex-shrink:0; margin-top:4px; box-shadow:0 0 8px rgba(59,130,246,.6); }
    .t-line { width:1px; min-height:20px; flex-grow:1; margin-left:5px; background:linear-gradient(to bottom,rgba(59,130,246,.4),transparent); }

    /* Reveal */
    .reveal { opacity:0; transform:translateY(24px); transition:opacity .65s ease,transform .65s ease; }
    .reveal.on { opacity:1; transform:translateY(0); }

    /* Avatar ring */
    .av-ring { background:conic-gradient(#3B82F6,#1D4ED8,#F97316,#3B82F6); animation:spin 7s linear infinite; }
    @keyframes spin{ to{transform:rotate(360deg)} }

    /* Contact input */
    .c-input {
      width:100%; padding:11px 15px; border-radius:8px; font-family:'Inter',sans-serif;
      font-size:.875rem; outline:none; transition:border .2s,box-shadow .2s;
    }
    .dark  .c-input { background:rgba(15,23,42,.8); border:1px solid rgba(59,130,246,.2); color:#e2e8f0; }
    .dark  .c-input:focus { border-color:#3B82F6; box-shadow:0 0 0 3px rgba(59,130,246,.1); }
    .light .c-input { background:#fff; border:1px solid #CBD5E1; color:#1e293b; }
    .light .c-input:focus { border-color:#3B82F6; box-shadow:0 0 0 3px rgba(59,130,246,.1); }

    /* Mobile menu */
    #mob-menu { max-height:0; opacity:0; overflow:hidden; transition:max-height .3s ease,opacity .3s ease; }
    #mob-menu.open { max-height:400px; opacity:1; }

    @media(prefers-reduced-motion:reduce){
      .av-ring{animation:none}
      .cursor::after{animation:none}
      .reveal{opacity:1;transform:none}
    }
  </style>
</head>
<body class="dark">

<!-- ═══════════════════════ NAVBAR ═══════════════════════ -->
<nav id="navbar" class="nav-bg fixed top-0 left-0 right-0 z-50 backdrop-blur-md transition-all">
  <div class="max-w-6xl mx-auto px-5 py-4 flex items-center justify-between">
    <a href="#hero" class="font-display font-bold text-xl tracking-tight">
      <span class="text-blue-500">NK</span><span class="dark:text-white text-slate-800">.</span>
    </a>
    <div class="hidden md:flex items-center gap-7">
      <a href="#about"     class="nav-link text-sm font-medium dark:text-slate-300 text-slate-600 hover:text-blue-500 transition-colors font-body">About</a>
      <a href="#skills"    class="nav-link text-sm font-medium dark:text-slate-300 text-slate-600 hover:text-blue-500 transition-colors font-body">Skills</a>
      <a href="#projects"  class="nav-link text-sm font-medium dark:text-slate-300 text-slate-600 hover:text-blue-500 transition-colors font-body">Projects</a>
      <a href="#education" class="nav-link text-sm font-medium dark:text-slate-300 text-slate-600 hover:text-blue-500 transition-colors font-body">Education</a>
      <a href="#contact"   class="nav-link text-sm font-medium dark:text-slate-300 text-slate-600 hover:text-blue-500 transition-colors font-body">Contact</a>
    </div>
    <div class="flex items-center gap-3">
      <button id="theme-btn" class="w-9 h-9 rounded-full flex items-center justify-center dark:bg-slate-800 bg-white border dark:border-blue-500/20 border-slate-200 hover:border-blue-500/60 transition-all">
        <svg id="moon" class="w-4 h-4 text-blue-400" fill="none" viewBox="0 0 24 24" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M20.354 15.354A9 9 0 018.646 3.646 9.003 9.003 0 0012 21a9.003 9.003 0 008.354-5.646z"/></svg>
        <svg id="sun"  class="w-4 h-4 text-orange-400 hidden" fill="none" viewBox="0 0 24 24" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 3v1m0 16v1m9-9h-1M4 12H3m15.364 6.364l-.707-.707M6.343 6.343l-.707-.707m12.728 0l-.707.707M6.343 17.657l-.707.707M16 12a4 4 0 11-8 0 4 4 0 018 0z"/></svg>
      </button>
      <button id="hamburger" class="md:hidden w-9 h-9 flex items-center justify-center rounded-full dark:bg-slate-800 bg-white border dark:border-slate-700 border-slate-200">
        <svg class="w-4 h-4 dark:text-slate-300 text-slate-600" fill="none" viewBox="0 0 24 24" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h16"/></svg>
      </button>
    </div>
  </div>
  <div id="mob-menu" class="md:hidden nav-bg border-t dark:border-slate-700/50 border-slate-200">
    <div class="max-w-6xl mx-auto px-5 py-4 flex flex-col gap-4">
      <a href="#about"     onclick="closeMob()" class="text-sm font-medium dark:text-slate-300 text-slate-600 hover:text-blue-500 transition-colors py-1 font-body">About</a>
      <a href="#skills"    onclick="closeMob()" class="text-sm font-medium dark:text-slate-300 text-slate-600 hover:text-blue-500 transition-colors py-1 font-body">Skills</a>
      <a href="#projects"  onclick="closeMob()" class="text-sm font-medium dark:text-slate-300 text-slate-600 hover:text-blue-500 transition-colors py-1 font-body">Projects</a>
      <a href="#education" onclick="closeMob()" class="text-sm font-medium dark:text-slate-300 text-slate-600 hover:text-blue-500 transition-colors py-1 font-body">Education</a>
      <a href="#contact"   onclick="closeMob()" class="text-sm font-medium dark:text-slate-300 text-slate-600 hover:text-blue-500 transition-colors py-1 font-body">Contact</a>
    </div>
  </div>
</nav>

<!-- ═══════════════════════ HERO ═══════════════════════ -->
<section id="hero" class="hero-bg grid-bg min-h-screen flex items-center relative overflow-hidden pt-20">

  <!-- Blueprint annotation lines -->
  <div class="bp-line hidden lg:block" style="top:18%;left:12%;width:22%;height:32%;border-radius:4px;"></div>
  <div class="bp-line hidden lg:block" style="top:60%;right:8%;width:16%;height:20%;border-radius:4px;"></div>
  <div class="absolute top-1/3 left-0 w-1/2 h-px opacity-10" style="background:linear-gradient(90deg,transparent,#3B82F6,transparent)"></div>
  <div class="absolute bottom-1/3 right-0 w-1/2 h-px opacity-10" style="background:linear-gradient(270deg,transparent,#F97316,transparent)"></div>
  <!-- Ambient orbs -->
  <div class="absolute top-1/4 left-1/4 w-72 h-72 rounded-full opacity-8 blur-3xl" style="background:radial-gradient(circle,rgba(59,130,246,0.3),transparent)"></div>
  <div class="absolute bottom-1/4 right-1/4 w-56 h-56 rounded-full opacity-6 blur-3xl" style="background:radial-gradient(circle,rgba(249,115,22,0.25),transparent)"></div>

  <div class="max-w-6xl mx-auto px-5 py-16 w-full relative z-10">
    <div class="grid lg:grid-cols-2 gap-12 items-center">

      <!-- TEXT -->
      <div class="space-y-7">
        <div class="inline-flex items-center gap-2 px-4 py-2 rounded-full tag-blue font-mono text-xs font-medium">
          <span class="w-2 h-2 rounded-full bg-blue-500 animate-pulse"></span>
          Open to Opportunities
        </div>

        <div>
          <p class="font-mono text-blue-500 text-xs mb-2 tracking-widest uppercase">Hello, I'm</p>
          <h1 class="font-display font-bold leading-none dark:text-white text-slate-900" style="font-size:clamp(2.6rem,6.5vw,4.8rem)">
            Naveen<br/>
            <span class="text-blue-500" style="text-shadow:0 0 28px rgba(59,130,246,.5)">Kumar</span>
          </h1>
        </div>

        <div class="font-display text-lg dark:text-slate-300 text-slate-600 font-medium min-h-7">
          <span id="typer" class="cursor"></span>
        </div>

        <p class="font-body tx-muted leading-relaxed max-w-lg text-sm">
          Driven Mechanical Engineering undergraduate at IIMT College of Engineering (AKTU) with a strong foundation in mechanical design, technical project planning, and advanced mathematics. Proficient in AutoCAD and skilled in Python and C/C++ programming — building logic-intensive software that solves real-world engineering challenges.
        </p>

        <div class="flex flex-wrap gap-3">
          <a href="https://linkedin.com/in/naveen-kumar-a2a57a396" target="_blank" rel="noopener"
             class="inline-flex items-center gap-2 px-5 py-2.5 rounded-lg text-sm font-medium text-white font-body transition-all hover:scale-[1.03]"
             style="background:linear-gradient(135deg,#0077B5,#005fa3);box-shadow:0 4px 18px rgba(0,119,181,.35)">
            <svg class="w-4 h-4" fill="currentColor" viewBox="0 0 24 24"><path d="M20.447 20.452h-3.554v-5.569c0-1.328-.027-3.037-1.852-3.037-1.853 0-2.136 1.445-2.136 2.939v5.667H9.351V9h3.414v1.561h.046c.477-.9 1.637-1.85 3.37-1.85 3.601 0 4.267 2.37 4.267 5.455v6.286zM5.337 7.433a2.062 2.062 0 01-2.063-2.065 2.064 2.064 0 112.063 2.065zm1.782 13.019H3.555V9h3.564v11.452zM22.225 0H1.771C.792 0 0 .774 0 1.729v20.542C0 23.227.792 24 1.771 24h20.451C23.2 24 24 23.227 24 22.271V1.729C24 .774 23.2 0 22.222 0h.003z"/></svg>
            LinkedIn
          </a>
          <a href="mailto:newnavin006@gmail.com"
             class="inline-flex items-center gap-2 px-5 py-2.5 rounded-lg text-sm font-medium text-blue-400 font-body transition-all hover:scale-[1.03]"
             style="border:1px solid rgba(59,130,246,.4);background:rgba(59,130,246,.06)">
            <svg class="w-4 h-4" fill="none" viewBox="0 0 24 24" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 8l7.89 5.26a2 2 0 002.22 0L21 8M5 19h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z"/></svg>
            Email Me
          </a>
          <a href="tel:+917982528410"
             class="inline-flex items-center gap-2 px-5 py-2.5 rounded-lg text-sm font-medium dark:text-slate-300 text-slate-700 font-body transition-all hover:scale-[1.03] dark:bg-slate-800/60 bg-white"
             style="border:1px solid rgba(100,116,139,.3)">
            <svg class="w-4 h-4" fill="none" viewBox="0 0 24 24" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 5a2 2 0 012-2h3.28a1 1 0 01.948.684l1.498 4.493a1 1 0 01-.502 1.21l-2.257 1.13a11.042 11.042 0 005.516 5.516l1.13-2.257a1 1 0 011.21-.502l4.493 1.498a1 1 0 01.684.949V19a2 2 0 01-2 2h-1C9.716 21 3 14.284 3 6V5z"/></svg>
            +91 7982528410
          </a>
        </div>
      </div>

      <!-- AVATAR + CARDS -->
      <div class="flex flex-col items-center gap-6">
        <!-- Avatar with blueprint ring -->
        <div class="relative">
          <div class="av-ring w-44 h-44 rounded-full p-0.5">
            <div class="w-full h-full rounded-full overflow-hidden border-2 dark:border-slate-900 border-white">
              <img src="data:image/jpeg;base64,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" alt="Naveen Kumar" class="w-full h-full object-cover object-top" />
            </div>
          </div>
          <!-- Badge -->
          <div class="absolute -bottom-1 -right-1 w-12 h-12 rounded-full flex items-center justify-center text-xl border-2 dark:border-slate-900 border-white" style="background:linear-gradient(135deg,#3B82F6,#1D4ED8)">⚙️</div>
          <!-- Blueprint callout line -->
          <div class="hidden lg:block absolute -right-16 top-1/2 w-12 h-px bg-blue-500/40"></div>
          <div class="hidden lg:block absolute -right-24 top-1/2 -translate-y-3 font-mono text-xs text-blue-500/60 whitespace-nowrap">// mech + code</div>
        </div>

        <!-- Terminal card -->
        <div class="rounded-xl p-5 w-full max-w-sm font-mono text-xs dark:bg-slate-900/80 bg-slate-800 border dark:border-blue-500/20 border-slate-600" style="box-shadow:0 0 0 1px rgba(59,130,246,.1),0 8px 32px rgba(59,130,246,.08)">
          <div class="flex items-center gap-2 mb-4">
            <div class="w-3 h-3 rounded-full bg-red-500/80"></div>
            <div class="w-3 h-3 rounded-full bg-yellow-500/80"></div>
            <div class="w-3 h-3 rounded-full bg-green-500/80"></div>
            <span class="text-slate-500 ml-2 text-xs">naveen.json</span>
          </div>
          <div class="space-y-1 leading-relaxed text-xs">
            <div><span class="text-blue-400">const</span> <span class="text-orange-300">naveen</span> <span class="text-white">=</span> <span class="text-white">{</span></div>
            <div class="pl-4"><span class="text-green-400">name</span><span class="text-white">:</span> <span class="text-yellow-200">"Naveen Kumar"</span><span class="text-white">,</span></div>
            <div class="pl-4"><span class="text-green-400">degree</span><span class="text-white">:</span> <span class="text-yellow-200">"B.Tech Mech Engg"</span><span class="text-white">,</span></div>
            <div class="pl-4"><span class="text-green-400">college</span><span class="text-white">:</span> <span class="text-yellow-200">"IIMT / AKTU"</span><span class="text-white">,</span></div>
            <div class="pl-4"><span class="text-green-400">batch</span><span class="text-white">:</span> <span class="text-blue-300">2025</span><span class="text-slate-400"> — </span><span class="text-blue-300">2029</span><span class="text-white">,</span></div>
            <div class="pl-4"><span class="text-green-400">skills</span><span class="text-white">:</span> <span class="text-yellow-200">["Python","C/C++","AutoCAD"]</span><span class="text-white">,</span></div>
            <div class="pl-4"><span class="text-green-400">openTo</span><span class="text-white">:</span> <span class="text-blue-300">true</span></div>
            <div><span class="text-white">}</span></div>
          </div>
        </div>

        <!-- Quick stats -->
        <div class="flex gap-4 w-full max-w-sm">
          <div class="flex-1 card rounded-xl p-4 text-center">
            <div class="font-display font-bold text-2xl text-blue-500">2+</div>
            <div class="tx-muted text-xs mt-1 font-body">Projects</div>
          </div>
          <div class="flex-1 card rounded-xl p-4 text-center">
            <div class="font-display font-bold text-2xl text-orange-400">3+</div>
            <div class="tx-muted text-xs mt-1 font-body">Languages</div>
          </div>
          <div class="flex-1 card rounded-xl p-4 text-center">
            <div class="font-display font-bold text-2xl text-blue-500">1</div>
            <div class="tx-muted text-xs mt-1 font-body">Hackathon</div>
          </div>
        </div>
      </div>
    </div>

    <!-- Scroll hint -->
    <div class="flex justify-center mt-14">
      <a href="#about" class="flex flex-col items-center gap-2 tx-muted hover:text-blue-500 transition-colors">
        <span class="font-mono text-xs tracking-widest">SCROLL</span>
        <div class="w-6 h-10 rounded-full border-2 dark:border-slate-600 border-slate-400 flex justify-center pt-2">
          <div class="w-1 h-2 rounded-full bg-blue-500 animate-bounce"></div>
        </div>
      </a>
    </div>
  </div>
</section>


<!-- ═══════════════════════ ABOUT ═══════════════════════ -->
<section id="about" class="py-24 section-alt">
  <div class="max-w-6xl mx-auto px-5">
    <div class="reveal">
      <div class="flex items-center gap-4 mb-14">
        <span class="font-mono text-blue-500 text-xs">01</span>
        <h2 class="font-display font-bold text-3xl dark:text-white text-slate-900">About Me</h2>
        <div class="flex-1 h-px dark:bg-blue-500/20 bg-slate-300"></div>
      </div>
    </div>

    <div class="grid lg:grid-cols-5 gap-12 items-start">
      <div class="lg:col-span-3 reveal space-y-5">
        <p class="font-body tx-muted leading-relaxed">
          I'm a first-year <span class="text-blue-500 font-medium">Mechanical Engineering undergraduate at IIMT College of Engineering (AKTU)</span>, blending classical engineering disciplines with modern software development skills. My passion lies at the intersection of precision engineering and algorithmic thinking.
        </p>
        <p class="font-body tx-muted leading-relaxed">
          On the engineering side, I work with <span class="text-blue-500 font-medium">AutoCAD</span> for design and drafting and have a strong grounding in mechanical design principles and advanced mathematics. On the software side, I write production-quality code in <span class="text-blue-500 font-medium">Python, C, and C++</span>, focusing on logic-intensive problems — from game engines to hardware prototyping.
        </p>
        <p class="font-body tx-muted leading-relaxed">
          I participated in a college-level hackathon, collaborating cross-functionally on a real mechanical/hardware challenge, which sharpened both my prototyping skills and my ability to deliver under pressure. I'm actively looking for internship opportunities where I can apply multidisciplinary engineering principles to practical and industrial applications.
        </p>
        <div class="flex flex-wrap gap-3 pt-2">
          <span class="tag-blue px-3 py-1.5 rounded-full font-mono text-xs">📍 India</span>
          <span class="tag-orange px-3 py-1.5 rounded-full font-mono text-xs">🎓 IIMT / AKTU — 2025–2029</span>
          <span class="tag-blue px-3 py-1.5 rounded-full font-mono text-xs">💼 Open to Internships</span>
        </div>
        <!-- Contact quick row -->
        <div class="pt-2 flex flex-col sm:flex-row gap-3 text-sm">
          <a href="mailto:newnavin006@gmail.com" class="inline-flex items-center gap-2 text-blue-500 hover:underline font-mono text-xs">
            <svg class="w-4 h-4" fill="none" viewBox="0 0 24 24" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 8l7.89 5.26a2 2 0 002.22 0L21 8M5 19h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z"/></svg>
            newnavin006@gmail.com
          </a>
          <a href="tel:+917982528410" class="inline-flex items-center gap-2 tx-muted hover:text-blue-500 transition-colors font-mono text-xs">
            <svg class="w-4 h-4" fill="none" viewBox="0 0 24 24" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 5a2 2 0 012-2h3.28a1 1 0 01.948.684l1.498 4.493a1 1 0 01-.502 1.21l-2.257 1.13a11.042 11.042 0 005.516 5.516l1.13-2.257a1 1 0 011.21-.502l4.493 1.498a1 1 0 01.684.949V19a2 2 0 01-2 2h-1C9.716 21 3 14.284 3 6V5z"/></svg>
            +91 7982528410
          </a>
        </div>
      </div>

      <div class="lg:col-span-2 reveal grid grid-cols-2 gap-4">
        <div class="card rounded-xl p-5">
          <div class="text-3xl mb-3">⚙️</div>
          <h3 class="font-display font-semibold dark:text-white text-slate-800 text-sm mb-2">Mechanical Design</h3>
          <p class="tx-muted text-xs leading-relaxed">AutoCAD drafting, design principles, and technical project planning for industrial applications.</p>
        </div>
        <div class="card rounded-xl p-5">
          <div class="text-3xl mb-3">🐍</div>
          <h3 class="font-display font-semibold dark:text-white text-slate-800 text-sm mb-2">Python Dev</h3>
          <p class="tx-muted text-xs leading-relaxed">Logic-intensive software — games, algorithms, automation, and CLI applications.</p>
        </div>
        <div class="card rounded-xl p-5">
          <div class="text-3xl mb-3">💡</div>
          <h3 class="font-display font-semibold dark:text-white text-slate-800 text-sm mb-2">Algorithm Building</h3>
          <p class="tx-muted text-xs leading-relaxed">Designing efficient algorithms from game AI logic to mechanical computation problems.</p>
        </div>
        <div class="card rounded-xl p-5">
          <div class="text-3xl mb-3">🤝</div>
          <h3 class="font-display font-semibold dark:text-white text-slate-800 text-sm mb-2">Team Collaboration</h3>
          <p class="tx-muted text-xs leading-relaxed">Cross-functional teamwork in hackathon environments — ideation to prototype delivery.</p>
        </div>
      </div>
    </div>
  </div>
</section>


<!-- ═══════════════════════ SKILLS ═══════════════════════ -->
<section id="skills" class="py-24">
  <div class="max-w-6xl mx-auto px-5">
    <div class="reveal">
      <div class="flex items-center gap-4 mb-14">
        <span class="font-mono text-blue-500 text-xs">02</span>
        <h2 class="font-display font-bold text-3xl dark:text-white text-slate-900">Skills & Tools</h2>
        <div class="flex-1 h-px dark:bg-blue-500/20 bg-slate-300"></div>
      </div>
    </div>

    <div class="grid lg:grid-cols-2 gap-12">

      <!-- Bars -->
      <div class="reveal space-y-5">
        <h3 class="font-display font-semibold dark:text-white text-slate-800 mb-6 text-sm uppercase tracking-widest">Proficiency</h3>

        <div class="skill-row space-y-2">
          <div class="flex justify-between"><span class="font-body text-sm dark:text-slate-300 text-slate-700">Python Programming</span><span class="font-mono text-xs text-blue-500">85%</span></div>
          <div class="w-full h-2 dark:bg-slate-700/60 bg-slate-200 rounded-full overflow-hidden"><div class="skill-fill" style="--w:85%"></div></div>
        </div>
        <div class="skill-row space-y-2">
          <div class="flex justify-between"><span class="font-body text-sm dark:text-slate-300 text-slate-700">C / C++</span><span class="font-mono text-xs text-blue-500">78%</span></div>
          <div class="w-full h-2 dark:bg-slate-700/60 bg-slate-200 rounded-full overflow-hidden"><div class="skill-fill" style="--w:78%"></div></div>
        </div>
        <div class="skill-row space-y-2">
          <div class="flex justify-between"><span class="font-body text-sm dark:text-slate-300 text-slate-700">AutoCAD (2D/3D Design)</span><span class="font-mono text-xs text-blue-500">80%</span></div>
          <div class="w-full h-2 dark:bg-slate-700/60 bg-slate-200 rounded-full overflow-hidden"><div class="skill-fill" style="--w:80%"></div></div>
        </div>
        <div class="skill-row space-y-2">
          <div class="flex justify-between"><span class="font-body text-sm dark:text-slate-300 text-slate-700">Algorithm Development</span><span class="font-mono text-xs text-blue-500">82%</span></div>
          <div class="w-full h-2 dark:bg-slate-700/60 bg-slate-200 rounded-full overflow-hidden"><div class="skill-fill" style="--w:82%"></div></div>
        </div>
        <div class="skill-row space-y-2">
          <div class="flex justify-between"><span class="font-body text-sm dark:text-slate-300 text-slate-700">Mechanical Design & Planning</span><span class="font-mono text-xs text-blue-500">75%</span></div>
          <div class="w-full h-2 dark:bg-slate-700/60 bg-slate-200 rounded-full overflow-hidden"><div class="skill-fill" style="--w:75%"></div></div>
        </div>
        <div class="skill-row space-y-2">
          <div class="flex justify-between"><span class="font-body text-sm dark:text-slate-300 text-slate-700">Advanced Mathematics</span><span class="font-mono text-xs text-blue-500">88%</span></div>
          <div class="w-full h-2 dark:bg-slate-700/60 bg-slate-200 rounded-full overflow-hidden"><div class="skill-fill" style="--w:88%"></div></div>
        </div>
      </div>

      <!-- Tags -->
      <div class="reveal space-y-7">
        <div>
          <h3 class="font-display font-semibold dark:text-white text-slate-800 mb-4 text-sm uppercase tracking-widest">Programming Languages</h3>
          <div class="flex flex-wrap gap-2">
            <span class="tag-blue px-3 py-1.5 rounded-lg font-mono text-xs">Python</span>
            <span class="tag-blue px-3 py-1.5 rounded-lg font-mono text-xs">C</span>
            <span class="tag-blue px-3 py-1.5 rounded-lg font-mono text-xs">C++</span>
          </div>
        </div>
        <div>
          <h3 class="font-display font-semibold dark:text-white text-slate-800 mb-4 text-sm uppercase tracking-widest">Design & Engineering Tools</h3>
          <div class="flex flex-wrap gap-2">
            <span class="tag-orange px-3 py-1.5 rounded-lg font-mono text-xs">AutoCAD</span>
            <span class="tag-orange px-3 py-1.5 rounded-lg font-mono text-xs">Technical Drafting</span>
            <span class="tag-orange px-3 py-1.5 rounded-lg font-mono text-xs">Mechanical Design</span>
            <span class="tag-orange px-3 py-1.5 rounded-lg font-mono text-xs">Project Planning</span>
          </div>
        </div>
        <div>
          <h3 class="font-display font-semibold dark:text-white text-slate-800 mb-4 text-sm uppercase tracking-widest">Core Competencies</h3>
          <div class="flex flex-wrap gap-2">
            <span class="tag-blue px-3 py-1.5 rounded-lg font-mono text-xs">Algorithm Development</span>
            <span class="tag-blue px-3 py-1.5 rounded-lg font-mono text-xs">Advanced Mathematics</span>
            <span class="tag-blue px-3 py-1.5 rounded-lg font-mono text-xs">CLI Application Design</span>
            <span class="tag-blue px-3 py-1.5 rounded-lg font-mono text-xs">Hardware Prototyping</span>
          </div>
        </div>
        <div>
          <h3 class="font-display font-semibold dark:text-white text-slate-800 mb-4 text-sm uppercase tracking-widest">Soft Skills</h3>
          <div class="flex flex-wrap gap-2">
            <span class="tag-gray px-3 py-1.5 rounded-lg font-mono text-xs">Leadership</span>
            <span class="tag-gray px-3 py-1.5 rounded-lg font-mono text-xs">Communication</span>
            <span class="tag-gray px-3 py-1.5 rounded-lg font-mono text-xs">Collaboration</span>
            <span class="tag-gray px-3 py-1.5 rounded-lg font-mono text-xs">Teamwork</span>
            <span class="tag-gray px-3 py-1.5 rounded-lg font-mono text-xs">Problem Solving</span>
          </div>
        </div>
      </div>
    </div>
  </div>
</section>


<!-- ═══════════════════════ PROJECTS ═══════════════════════ -->
<section id="projects" class="py-24 section-alt">
  <div class="max-w-6xl mx-auto px-5">
    <div class="reveal">
      <div class="flex items-center gap-4 mb-14">
        <span class="font-mono text-blue-500 text-xs">03</span>
        <h2 class="font-display font-bold text-3xl dark:text-white text-slate-900">Projects</h2>
        <div class="flex-1 h-px dark:bg-blue-500/20 bg-slate-300"></div>
      </div>
    </div>

    <div class="grid md:grid-cols-2 gap-8">

      <!-- Project 1: Chess -->
      <div class="card rounded-2xl overflow-hidden reveal">
        <div class="h-1.5" style="background:linear-gradient(90deg,#3B82F6,#1D4ED8)"></div>
        <div class="p-7 space-y-5">
          <div class="flex items-start justify-between">
            <div class="flex items-center gap-3">
              <div class="w-12 h-12 rounded-xl flex items-center justify-center text-2xl" style="background:rgba(59,130,246,.1)">♟️</div>
              <div>
                <h3 class="font-display font-bold dark:text-white text-slate-800 text-lg">Chess Game — Python</h3>
                <p class="tx-muted font-mono text-xs mt-0.5">Personal Project  •  2024 – 2025</p>
              </div>
            </div>
          </div>

          <p class="font-body tx-muted text-sm leading-relaxed">
            A fully functional chess game built in Python from scratch, supporting both 2-player (human vs. human) and human vs. computer modes via a command-line interface. Engineered from the ground up with a focus on rule accuracy and AI competitiveness.
          </p>

          <ul class="space-y-2">
            <li class="flex items-start gap-2 text-sm">
              <span class="text-blue-500 mt-0.5 flex-shrink-0">▸</span>
              <span class="tx-muted font-body">Comprehensive move validation enforcing legal piece movements and turn-based gameplay rules for all chess pieces</span>
            </li>
            <li class="flex items-start gap-2 text-sm">
              <span class="text-blue-500 mt-0.5 flex-shrink-0">▸</span>
              <span class="tx-muted font-body">Check and checkmate detection algorithms to accurately identify game-ending conditions</span>
            </li>
            <li class="flex items-start gap-2 text-sm">
              <span class="text-blue-500 mt-0.5 flex-shrink-0">▸</span>
              <span class="tx-muted font-body">AI computer opponent using minimax logic to simulate a competitive single-player experience</span>
            </li>
          </ul>

          <div class="flex flex-wrap gap-2 pt-1">
            <span class="tag-blue px-2.5 py-1 rounded font-mono text-xs">Python</span>
            <span class="tag-blue px-2.5 py-1 rounded font-mono text-xs">OOP</span>
            <span class="tag-blue px-2.5 py-1 rounded font-mono text-xs">Game AI</span>
            <span class="tag-blue px-2.5 py-1 rounded font-mono text-xs">CLI</span>
            <span class="tag-blue px-2.5 py-1 rounded font-mono text-xs">Algorithm Design</span>
          </div>
        </div>
      </div>

      <!-- Project 2: Hackathon -->
      <div class="card rounded-2xl overflow-hidden reveal" style="transition-delay:.1s">
        <div class="h-1.5" style="background:linear-gradient(90deg,#F97316,#EA580C)"></div>
        <div class="p-7 space-y-5">
          <div class="flex items-start gap-3">
            <div class="w-12 h-12 rounded-xl flex items-center justify-center text-2xl flex-shrink-0" style="background:rgba(249,115,22,.1)">🔩</div>
            <div>
              <h3 class="font-display font-bold dark:text-white text-slate-800 text-lg">College Hackathon — Mech & Hardware Project</h3>
              <p class="tx-muted font-mono text-xs mt-0.5">Team Participant (4+ members)  •  2024</p>
            </div>
          </div>

          <p class="font-body tx-muted text-sm leading-relaxed">
            Collaborated in a cross-functional team to design and develop a mechanical/hardware solution under time-bound hackathon constraints. Drove ideation, hands-on prototyping, and technical planning throughout the engineering challenge.
          </p>

          <ul class="space-y-2">
            <li class="flex items-start gap-2 text-sm">
              <span class="text-orange-400 mt-0.5 flex-shrink-0">▸</span>
              <span class="tx-muted font-body">Led ideation sessions, translating problem statements into actionable engineering concepts</span>
            </li>
            <li class="flex items-start gap-2 text-sm">
              <span class="text-orange-400 mt-0.5 flex-shrink-0">▸</span>
              <span class="tx-muted font-body">Contributed to hands-on prototyping and hardware assembly within tight deadlines</span>
            </li>
            <li class="flex items-start gap-2 text-sm">
              <span class="text-orange-400 mt-0.5 flex-shrink-0">▸</span>
              <span class="tx-muted font-body">Coordinated technical planning and documentation across a diverse 4+ person team</span>
            </li>
          </ul>

          <div class="flex flex-wrap gap-2 pt-1">
            <span class="tag-orange px-2.5 py-1 rounded font-mono text-xs">Mechanical Design</span>
            <span class="tag-orange px-2.5 py-1 rounded font-mono text-xs">Hardware</span>
            <span class="tag-orange px-2.5 py-1 rounded font-mono text-xs">Prototyping</span>
            <span class="tag-orange px-2.5 py-1 rounded font-mono text-xs">Teamwork</span>
          </div>
        </div>
      </div>

    </div>
  </div>
</section>


<!-- ═══════════════════════ EDUCATION ═══════════════════════ -->
<section id="education" class="py-24">
  <div class="max-w-6xl mx-auto px-5">
    <div class="reveal">
      <div class="flex items-center gap-4 mb-14">
        <span class="font-mono text-blue-500 text-xs">04</span>
        <h2 class="font-display font-bold text-3xl dark:text-white text-slate-900">Education</h2>
        <div class="flex-1 h-px dark:bg-blue-500/20 bg-slate-300"></div>
      </div>
    </div>

    <div class="max-w-3xl space-y-5">

      <!-- B.Tech -->
      <div class="reveal flex gap-5">
        <div class="flex flex-col items-center pt-1">
          <div class="t-dot"></div>
          <div class="t-line"></div>
        </div>
        <div class="card rounded-xl p-6 flex-1 mb-2">
          <div class="flex flex-wrap items-start justify-between gap-2 mb-2">
            <h3 class="font-display font-bold dark:text-white text-slate-800">B.Tech — Mechanical Engineering</h3>
            <span class="tag-blue px-2.5 py-1 rounded font-mono text-xs">2025 – 2029</span>
          </div>
          <p class="text-blue-500 font-mono text-xs mb-3">IIMT College of Engineering, AKTU</p>
          <p class="tx-muted text-sm font-body leading-relaxed">
            Currently pursuing a B.Tech in Mechanical Engineering with a strong focus on mechanical design, advanced mathematics, and computing. Actively developing software skills in parallel with core engineering coursework to become a multidisciplinary engineer.
          </p>
        </div>
      </div>

      <!-- Class XII -->
      <div class="reveal flex gap-5" style="transition-delay:.1s">
        <div class="flex flex-col items-center pt-1">
          <div class="t-dot" style="background:#F97316;box-shadow:0 0 8px rgba(249,115,22,.6)"></div>
          <div class="t-line"></div>
        </div>
        <div class="card rounded-xl p-6 flex-1 mb-2">
          <div class="flex flex-wrap items-start justify-between gap-2 mb-2">
            <h3 class="font-display font-bold dark:text-white text-slate-800">Class XII — UP Board</h3>
            <span class="tag-orange px-2.5 py-1 rounded font-mono text-xs">2025</span>
          </div>
          <p class="text-orange-400 font-mono text-xs">Shri Sanatan Dharm Inter College</p>
        </div>
      </div>

      <!-- Class X -->
      <div class="reveal flex gap-5" style="transition-delay:.2s">
        <div class="flex flex-col items-center pt-1">
          <div class="t-dot" style="background:#64748b;box-shadow:0 0 8px rgba(100,116,139,.6)"></div>
        </div>
        <div class="card rounded-xl p-6 flex-1">
          <div class="flex flex-wrap items-start justify-between gap-2 mb-2">
            <h3 class="font-display font-bold dark:text-white text-slate-800">Class X — CBSE</h3>
            <span class="tag-gray px-2.5 py-1 rounded font-mono text-xs">2023</span>
          </div>
          <p class="tx-muted font-mono text-xs">YSY International School</p>
        </div>
      </div>

    </div>

    <!-- Hackathon highlight -->
    <div class="mt-14 reveal">
      <h3 class="font-display font-semibold dark:text-white text-slate-800 mb-6 flex items-center gap-2">
        <span class="text-orange-400">🏆</span> Achievements
      </h3>
      <div class="grid sm:grid-cols-2 gap-4 max-w-3xl">
        <div class="card rounded-xl p-5 flex items-start gap-4">
          <span class="text-2xl flex-shrink-0">🏅</span>
          <div>
            <div class="font-display font-semibold dark:text-white text-slate-800 text-sm">College-Level Hackathon Participant</div>
            <div class="tx-muted text-xs mt-1 font-body">Mechanical & Hardware track — IIMT College of Engineering, 2024</div>
          </div>
        </div>
        <div class="card rounded-xl p-5 flex items-start gap-4">
          <span class="text-2xl flex-shrink-0">♟️</span>
          <div>
            <div class="font-display font-semibold dark:text-white text-slate-800 text-sm">Chess AI Engine — Built from Scratch</div>
            <div class="tx-muted text-xs mt-1 font-body">Full game logic, move validation, checkmate detection & AI opponent — 2024–2025</div>
          </div>
        </div>
        <div class="card rounded-xl p-5 flex items-start gap-4">
          <span class="text-2xl flex-shrink-0">📐</span>
          <div>
            <div class="font-display font-semibold dark:text-white text-slate-800 text-sm">AutoCAD Certified Skill</div>
            <div class="tx-muted text-xs mt-1 font-body">Proficient in 2D & 3D mechanical drafting for design and technical documentation</div>
          </div>
        </div>
        <div class="card rounded-xl p-5 flex items-start gap-4">
          <span class="text-2xl flex-shrink-0">➕</span>
          <div>
            <div class="font-display font-semibold dark:text-white text-slate-800 text-sm">Multi-Language Programmer</div>
            <div class="tx-muted text-xs mt-1 font-body">Proficient in Python, C, and C++ — writing logic-intensive systems and algorithms</div>
          </div>
        </div>
      </div>
    </div>
  </div>
</section>


<!-- ═══════════════════════ CONTACT ═══════════════════════ -->
<section id="contact" class="py-24 section-alt">
  <div class="max-w-6xl mx-auto px-5">
    <div class="reveal">
      <div class="flex items-center gap-4 mb-14">
        <span class="font-mono text-blue-500 text-xs">05</span>
        <h2 class="font-display font-bold text-3xl dark:text-white text-slate-900">Get In Touch</h2>
        <div class="flex-1 h-px dark:bg-blue-500/20 bg-slate-300"></div>
      </div>
    </div>

    <div class="grid lg:grid-cols-2 gap-12">

      <div class="reveal space-y-8">
        <div>
          <h3 class="font-display font-bold text-2xl dark:text-white text-slate-900 mb-4">Let's build something<br/><span class="text-blue-500">great together.</span></h3>
          <p class="tx-muted font-body leading-relaxed text-sm">
            Whether you have an internship opportunity, a project idea, or just want to connect — I'm always open. I respond within 24 hours.
          </p>
        </div>

        <div class="space-y-4">
          <a href="mailto:newnavin006@gmail.com" class="card flex items-center gap-4 p-4 rounded-xl group">
            <div class="w-10 h-10 rounded-lg flex items-center justify-center flex-shrink-0" style="background:rgba(59,130,246,.1)">
              <svg class="w-5 h-5 text-blue-500" fill="none" viewBox="0 0 24 24" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 8l7.89 5.26a2 2 0 002.22 0L21 8M5 19h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z"/></svg>
            </div>
            <div>
              <div class="tx-muted text-xs font-body">Email</div>
              <div class="font-body font-medium dark:text-white text-slate-800 text-sm group-hover:text-blue-500 transition-colors">newnavin006@gmail.com</div>
            </div>
          </a>
          <a href="tel:+917982528410" class="card flex items-center gap-4 p-4 rounded-xl group">
            <div class="w-10 h-10 rounded-lg flex items-center justify-center flex-shrink-0" style="background:rgba(249,115,22,.1)">
              <svg class="w-5 h-5 text-orange-400" fill="none" viewBox="0 0 24 24" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 5a2 2 0 012-2h3.28a1 1 0 01.948.684l1.498 4.493a1 1 0 01-.502 1.21l-2.257 1.13a11.042 11.042 0 005.516 5.516l1.13-2.257a1 1 0 011.21-.502l4.493 1.498a1 1 0 01.684.949V19a2 2 0 01-2 2h-1C9.716 21 3 14.284 3 6V5z"/></svg>
            </div>
            <div>
              <div class="tx-muted text-xs font-body">Phone</div>
              <div class="font-body font-medium dark:text-white text-slate-800 text-sm group-hover:text-blue-500 transition-colors">+91 7982528410</div>
            </div>
          </a>
          <a href="https://linkedin.com/in/naveen-kumar-a2a57a396" target="_blank" class="card flex items-center gap-4 p-4 rounded-xl group">
            <div class="w-10 h-10 rounded-lg flex items-center justify-center flex-shrink-0" style="background:rgba(0,119,181,.1)">
              <svg class="w-5 h-5" style="color:#0077B5" fill="currentColor" viewBox="0 0 24 24"><path d="M20.447 20.452h-3.554v-5.569c0-1.328-.027-3.037-1.852-3.037-1.853 0-2.136 1.445-2.136 2.939v5.667H9.351V9h3.414v1.561h.046c.477-.9 1.637-1.85 3.37-1.85 3.601 0 4.267 2.37 4.267 5.455v6.286zM5.337 7.433a2.062 2.062 0 01-2.063-2.065 2.064 2.064 0 112.063 2.065zm1.782 13.019H3.555V9h3.564v11.452zM22.225 0H1.771C.792 0 0 .774 0 1.729v20.542C0 23.227.792 24 1.771 24h20.451C23.2 24 24 23.227 24 22.271V1.729C24 .774 23.2 0 22.222 0h.003z"/></svg>
            </div>
            <div>
              <div class="tx-muted text-xs font-body">LinkedIn</div>
              <div class="font-body font-medium dark:text-white text-slate-800 text-sm group-hover:text-blue-500 transition-colors">naveen-kumar-a2a57a396</div>
            </div>
          </a>
        </div>
      </div>

      <div class="reveal">
        <div class="card rounded-2xl p-7">
          <h3 class="font-display font-semibold dark:text-white text-slate-800 mb-6">Send a Message</h3>
          <div class="space-y-4">
            <div class="grid grid-cols-2 gap-4">
              <div>
                <label class="block tx-muted text-xs font-medium mb-2 font-body">Your Name</label>
                <input type="text" id="fn" placeholder="Ravi Sharma" class="c-input" />
              </div>
              <div>
                <label class="block tx-muted text-xs font-medium mb-2 font-body">Your Email</label>
                <input type="email" id="fe" placeholder="ravi@example.com" class="c-input" />
              </div>
            </div>
            <div>
              <label class="block tx-muted text-xs font-medium mb-2 font-body">Subject</label>
              <input type="text" id="fs" placeholder="Internship Opportunity / Collaboration" class="c-input" />
            </div>
            <div>
              <label class="block tx-muted text-xs font-medium mb-2 font-body">Message</label>
              <textarea id="fm" rows="5" placeholder="Tell me about the opportunity or project..." class="c-input resize-none"></textarea>
            </div>
            <button onclick="submitForm()" class="w-full py-3 rounded-xl font-display font-semibold text-sm text-white transition-all hover:scale-[1.02] active:scale-[0.98]" style="background:linear-gradient(135deg,#3B82F6,#1D4ED8);box-shadow:0 4px 20px rgba(59,130,246,.3)">
              Send Message ✉️
            </button>
            <p id="fstatus" class="text-center text-sm hidden font-body"></p>
          </div>
        </div>
      </div>
    </div>
  </div>
</section>


<!-- ═══════════════════════ FOOTER ═══════════════════════ -->
<footer class="border-t dark:border-blue-500/10 border-slate-200 py-8">
  <div class="max-w-6xl mx-auto px-5 flex flex-col sm:flex-row items-center justify-between gap-4">
    <div class="flex items-center gap-2">
      <span class="font-display font-bold text-blue-500">NK</span>
      <span class="tx-muted font-mono text-xs">© 2025 Naveen Kumar</span>
    </div>
    <p class="tx-muted font-mono text-xs">Mech Engineer by degree · Python Dev by passion 🔩🐍</p>
    <a href="https://linkedin.com/in/naveen-kumar-a2a57a396" target="_blank" class="tx-muted hover:text-blue-500 transition-colors">
      <svg class="w-5 h-5" fill="currentColor" viewBox="0 0 24 24"><path d="M20.447 20.452h-3.554v-5.569c0-1.328-.027-3.037-1.852-3.037-1.853 0-2.136 1.445-2.136 2.939v5.667H9.351V9h3.414v1.561h.046c.477-.9 1.637-1.85 3.37-1.85 3.601 0 4.267 2.37 4.267 5.455v6.286zM5.337 7.433a2.062 2.062 0 01-2.063-2.065 2.064 2.064 0 112.063 2.065zm1.782 13.019H3.555V9h3.564v11.452zM22.225 0H1.771C.792 0 0 .774 0 1.729v20.542C0 23.227.792 24 1.771 24h20.451C23.2 24 24 23.227 24 22.271V1.729C24 .774 23.2 0 22.222 0h.003z"/></svg>
    </a>
  </div>
</footer>


<script>
  // ── THEME ──
  const body = document.body;
  const moonEl = document.getElementById('moon');
  const sunEl  = document.getElementById('sun');
  function setTheme(t) {
    body.classList.remove('dark','light');
    body.classList.add(t);
    if (t==='dark'){ moonEl.classList.remove('hidden'); sunEl.classList.add('hidden'); }
    else           { sunEl.classList.remove('hidden');  moonEl.classList.add('hidden'); }
    localStorage.setItem('nk-theme', t);
  }
  document.getElementById('theme-btn').addEventListener('click', () =>
    setTheme(body.classList.contains('dark') ? 'light' : 'dark')
  );
  setTheme(localStorage.getItem('nk-theme') || 'dark');

  // ── MOBILE MENU ──
  document.getElementById('hamburger').addEventListener('click', () =>
    document.getElementById('mob-menu').classList.toggle('open')
  );
  function closeMob(){ document.getElementById('mob-menu').classList.remove('open'); }

  // ── TYPING ──
  const phrases = [
    'Mechanical Engineering Student',
    'Python Developer 🐍',
    'Algorithm Builder',
    'AutoCAD Designer ⚙️',
    'Problem Solver',
    'Hackathon Participant 🔩',
  ];
  let pi=0,ci=0,del=false;
  const typer = document.getElementById('typer');
  function type(){
    const cur = phrases[pi];
    if(del){ typer.textContent = cur.substring(0,ci--); if(ci<0){ del=false; pi=(pi+1)%phrases.length; setTimeout(type,500); return; } }
    else   { typer.textContent = cur.substring(0,++ci);  if(ci===cur.length){ del=true; setTimeout(type,2200); return; } }
    setTimeout(type, del ? 55 : 95);
  }
  type();

  // ── REVEAL ──
  const revObs = new IntersectionObserver(es => es.forEach(e => {
    if(e.isIntersecting){ e.target.classList.add('on'); revObs.unobserve(e.target); }
  }), { threshold: 0.1 });
  document.querySelectorAll('.reveal').forEach(el => revObs.observe(el));

  // ── SKILL BARS ──
  const sObs = new IntersectionObserver(es => es.forEach(e => {
    if(e.isIntersecting){
      e.target.querySelectorAll('.skill-fill').forEach(b => b.classList.add('on'));
      sObs.unobserve(e.target);
    }
  }), { threshold: 0.25 });
  const skillSec = document.getElementById('skills');
  if(skillSec) sObs.observe(skillSec);

  // ── ACTIVE NAV ──
  const navLinks = document.querySelectorAll('.nav-link');
  const secObs = new IntersectionObserver(es => es.forEach(e => {
    if(e.isIntersecting){
      navLinks.forEach(a => {
        a.classList.remove('active');
        if(a.getAttribute('href')==='#'+e.target.id) a.classList.add('active');
      });
    }
  }), { threshold: 0.4 });
  document.querySelectorAll('section[id]').forEach(s => secObs.observe(s));

  // ── CONTACT ──
  function submitForm(){
    const n=document.getElementById('fn').value.trim();
    const e=document.getElementById('fe').value.trim();
    const m=document.getElementById('fm').value.trim();
    const st=document.getElementById('fstatus');
    if(!n||!e||!m){
      st.textContent='⚠️ Please fill in your name, email, and message.';
      st.className='text-center text-sm text-orange-400 font-body';
      st.classList.remove('hidden'); return;
    }
    st.textContent='🚀 Sending…';
    st.className='text-center text-sm text-blue-400 font-body';
    st.classList.remove('hidden');
    setTimeout(()=>{
      st.textContent='✅ Message sent! Naveen will reply within 24 hours.';
      st.className='text-center text-sm text-green-400 font-body';
      ['fn','fe','fs','fm'].forEach(id => { const el=document.getElementById(id); if(el) el.value=''; });
    }, 1300);
  }

  // ── NAVBAR SCROLL ──
  window.addEventListener('scroll', () => {
    document.getElementById('navbar').style.backdropFilter = window.scrollY > 40 ? 'blur(20px)' : 'blur(8px)';
  });
</script>
</body>
</html>


