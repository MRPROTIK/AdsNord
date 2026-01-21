 <!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover" />
  <meta http-equiv="X-UA-Compatible" content="IE=edge" />
  <title>geminidigitalai — AI Tools, Education, Services & Business Solutions</title>
  <meta name="description" content="geminidigitalai is a modern AI-powered digital platform offering AI tools, AI education, AI services, and AI-driven solutions for businesses and individuals." />
  <meta name="keywords" content="AI tools, AI services, AI education, AI automation, AI marketing, AI chatbot, AI consulting, geminidigitalai" />
  <meta name="robots" content="index,follow" />
  <link rel="canonical" href="https://example.com/" />
  <meta property="og:title" content="geminidigitalai — AI Tools, Education, Services & Solutions" />
  <meta property="og:description" content="AI tools, AI education, and AI services to help you build, market, automate, and scale." />
  <meta property="og:type" content="website" />
  <meta name="theme-color" content="#0B1020" />
  <link rel="preconnect" href="https://cdn.tailwindcss.com" crossorigin>
  <link rel="preconnect" href="https://unpkg.com" crossorigin>
  <script src="https://cdn.tailwindcss.com"></script>
  <script>
    tailwind.config = {
      darkMode: 'class',
      theme: {
        extend: {
          fontFamily: {
            sans: ['ui-sans-serif', 'system-ui', 'Inter', 'Segoe UI', 'Roboto', 'Helvetica Neue', 'Arial', 'Noto Sans', 'Apple Color Emoji', 'Segoe UI Emoji'],
            mono: ['ui-monospace','SFMono-Regular','Menlo','Monaco','Consolas','Liberation Mono','Courier New','monospace'],
          },
          colors: {
            ink: { 900: '#070A12', 800: '#0B1020', 700: '#0E1630' },
            neon: { blue: '#5CE1FF', purple: '#A78BFA', pink: '#FB7185' },
          },
          boxShadow: {
            glow: '0 0 0 1px rgba(92,225,255,.15), 0 8px 40px rgba(167,139,250,.20)',
            soft: '0 10px 40px rgba(0,0,0,.18)',
          },
          keyframes: {
            floaty: { '0%,100%': { transform: 'translateY(0px)' }, '50%': { transform: 'translateY(-8px)' } },
            shimmer: { '0%': { backgroundPosition: '0% 50%' }, '100%': { backgroundPosition: '100% 50%' } },
            pulseRing: { '0%': { transform: 'scale(0.92)', opacity: '0.65' }, '100%': { transform: 'scale(1.18)', opacity: '0' } },
            slideUp: { '0%': { opacity: 0, transform: 'translateY(14px)' }, '100%': { opacity: 1, transform: 'translateY(0)' } },
          },
          animation: {
            floaty: 'floaty 5s ease-in-out infinite',
            shimmer: 'shimmer 8s ease infinite',
            pulseRing: 'pulseRing 1.6s ease-out infinite',
            slideUp: 'slideUp .6s ease-out both',
          }
        }
      }
    }
  </script>

  <style>
    :root{
      --bg0: #0B1020;
      --bg1: #070A12;
      --card: rgba(255,255,255,.06);
      --card2: rgba(255,255,255,.09);
      --stroke: rgba(255,255,255,.12);
      --text: rgba(255,255,255,.88);
      --muted: rgba(255,255,255,.68);
      --shadow: 0 10px 40px rgba(0,0,0,.25);
      --gradA: radial-gradient(900px 450px at 10% 10%, rgba(92,225,255,.18), transparent 60%),
               radial-gradient(700px 420px at 90% 10%, rgba(167,139,250,.22), transparent 60%),
               radial-gradient(900px 520px at 40% 100%, rgba(251,113,133,.12), transparent 60%);
      --gradB: linear-gradient(120deg, rgba(92,225,255,.18), rgba(167,139,250,.18), rgba(251,113,133,.16));
      --focus: rgba(92,225,255,.35);
    }
    .light{
      --bg0: #F7F8FC;
      --bg1: #FFFFFF;
      --card: rgba(10,16,32,.06);
      --card2: rgba(10,16,32,.08);
      --stroke: rgba(10,16,32,.12);
      --text: rgba(10,16,32,.90);
      --muted: rgba(10,16,32,.68);
      --shadow: 0 12px 40px rgba(10,16,32,.12);
      --gradA: radial-gradient(900px 450px at 10% 10%, rgba(92,225,255,.24), transparent 60%),
               radial-gradient(700px 420px at 90% 10%, rgba(167,139,250,.22), transparent 60%),
               radial-gradient(900px 520px at 40% 100%, rgba(251,113,133,.14), transparent 60%);
      --gradB: linear-gradient(120deg, rgba(92,225,255,.20), rgba(167,139,250,.18), rgba(251,113,133,.16));
      --focus: rgba(92,225,255,.40);
    }

    html { scroll-behavior: smooth; }
    body{
      background: var(--bg1);
      color: var(--text);
      text-rendering: optimizeLegibility;
      -webkit-font-smoothing: antialiased;
      -moz-osx-font-smoothing: grayscale;
      position: relative;
      overflow-x: hidden;
    }
    /* Aurora background as a separate fixed layer (keeps sections readable) */
    body::before{
      content:"";
      position: fixed;
      inset: 0;
      z-index: -2;
      background-image: var(--gradA);
      background-attachment: fixed;
      background-size: cover;
      pointer-events: none;
    }
    body::after{
      content:"";
      position: fixed;
      inset: 0;
      z-index: -1;
      background: linear-gradient(180deg, rgba(7,10,18,.35), rgba(7,10,18,.92));
      pointer-events: none;
    }

    ::selection{ background: rgba(167,139,250,.35); color: var(--text); }

    .bg-aurora{
      background-image: var(--gradA);
      background-attachment: fixed;
    }

    .glass{
      background: color-mix(in srgb, var(--card) 85%, transparent);
      border: 1px solid var(--stroke);
      box-shadow: var(--shadow);
      backdrop-filter: blur(14px);
      -webkit-backdrop-filter: blur(14px);
    }
    .glass-soft{
      background: color-mix(in srgb, var(--card2) 80%, transparent);
      border: 1px solid var(--stroke);
      backdrop-filter: blur(12px);
      -webkit-backdrop-filter: blur(12px);
    }

    .chip{
      border: 1px solid var(--stroke);
      background: color-mix(in srgb, var(--card2) 70%, transparent);
    }

    .grad-text{
      background: linear-gradient(90deg, #5CE1FF, #A78BFA, #FB7185);
      -webkit-background-clip: text;
      background-clip: text;
      color: transparent;
    }

    .btn{
      display: inline-flex;
      align-items: center;
      justify-content: center;
      gap: .5rem;
      padding: .75rem 1rem;
      border-radius: .9rem;
      font-weight: 600;
      transition: transform .15s ease, box-shadow .15s ease, background .15s ease, border-color .15s ease;
      will-change: transform;
      user-select: none;
    }
    .btn:active{ transform: translateY(1px); }
    .btn-primary{
      background: linear-gradient(120deg, rgba(92,225,255,.95), rgba(167,139,250,.95), rgba(251,113,133,.90));
      color: #07101f;
      box-shadow: 0 14px 40px rgba(167,139,250,.25);
    }
    .btn-primary:hover{ box-shadow: 0 18px 55px rgba(167,139,250,.35); transform: translateY(-1px); }
    .btn-ghost{
      border: 1px solid var(--stroke);
      background: color-mix(in srgb, var(--card) 65%, transparent);
      color: var(--text);
    }
    .btn-ghost:hover{ background: color-mix(in srgb, var(--card2) 75%, transparent); transform: translateY(-1px); }

    .focus-ring:focus{
      outline: none;
      box-shadow: 0 0 0 4px var(--focus);
      border-color: rgba(92,225,255,.45);
    }

    .nav-link{
      color: var(--muted);
      transition: color .15s ease, background .15s ease;
      border-radius: .75rem;
      padding: .5rem .75rem;
    }
    .nav-link:hover{ color: var(--text); background: color-mix(in srgb, var(--card2) 70%, transparent); }
    .nav-link[aria-current="page"]{ color: var(--text); background: color-mix(in srgb, var(--card2) 85%, transparent); border: 1px solid var(--stroke); }

    .section{
      display: none;
    }
    .section.active{
      display: block;
      animation: slideUp .6s ease-out both;
    }

    .divider{
      height: 1px;
      background: linear-gradient(90deg, transparent, color-mix(in srgb, var(--stroke) 90%, transparent), transparent);
    }

    .grid-fade:before{
      content:"";
      position:absolute;
      inset:-2px;
      background:
        radial-gradient(circle at 25% 20%, rgba(92,225,255,.12), transparent 55%),
        radial-gradient(circle at 75% 30%, rgba(167,139,250,.14), transparent 60%),
        linear-gradient(to bottom, rgba(255,255,255,.05), transparent 40%),
        linear-gradient(90deg, rgba(255,255,255,.05) 1px, transparent 1px),
        linear-gradient(0deg, rgba(255,255,255,.05) 1px, transparent 1px);
      background-size: auto, auto, auto, 48px 48px, 48px 48px;
      mask-image: radial-gradient(closest-side, rgba(0,0,0,1), rgba(0,0,0,.1) 55%, transparent 70%);
      opacity: .8;
      pointer-events:none;
      border-radius: 1.5rem;
    }

    .skeleton{
      background: linear-gradient(90deg, color-mix(in srgb, var(--card2) 85%, transparent), color-mix(in srgb, var(--card) 80%, transparent), color-mix(in srgb, var(--card2) 85%, transparent));
      background-size: 200% 100%;
      animation: shimmer 1.4s linear infinite;
      border: 1px solid var(--stroke);
    }

    /* Chat widget */
    .chat-fab{
      position: fixed;
      right: 16px;
      bottom: 16px;
      z-index: 60;
    }
    .chat-panel{
      position: fixed;
      right: 16px;
      bottom: 86px;
      width: min(420px, calc(100vw - 32px));
      max-height: min(640px, calc(100vh - 120px));
      z-index: 60;
      display: none;
    }
    .chat-panel.open{ display: block; animation: slideUp .3s ease-out both; }
    .chat-scroll{ scrollbar-width: thin; scrollbar-color: rgba(167,139,250,.45) transparent; }
    .chat-scroll::-webkit-scrollbar{ width: 10px; }
    .chat-scroll::-webkit-scrollbar-thumb{ background: rgba(167,139,250,.35); border-radius: 999px; border: 2px solid transparent; background-clip: padding-box; }
    .chat-bubble{
      border: 1px solid var(--stroke);
      background: color-mix(in srgb, var(--card2) 80%, transparent);
    }
    .chat-bubble.ai{
      background: linear-gradient(135deg, color-mix(in srgb, rgba(92,225,255,.22) 80%, transparent), color-mix(in srgb, rgba(167,139,250,.18) 80%, transparent));
    }


    /* Header: constant deep + sticky */
    .site-header{
      background: rgba(11,16,32,.78);
      backdrop-filter: blur(12px);
      -webkit-backdrop-filter: blur(12px);
      border-bottom: 1px solid var(--stroke);
    }
    .site-header .glass{
      background: color-mix(in srgb, rgba(255,255,255,.06) 90%, transparent);
    }
        /* Reduce motion */
    @media (prefers-reduced-motion: reduce){
      html{ scroll-behavior: auto; }
      .section.active{ animation: none; }
      .animation, .animate-floaty{ animation: none !important; }
      .btn{ transition: none; }
    }
  </style>

  <script type="application/ld+json">
  {
    "@context": "https://schema.org",
    "@type": "Organization",
    "name": "geminidigitalai",
    "url": "https://example.com/",
    "logo": "https://example.com/logo.png",
    "description": "AI-powered digital platform providing AI tools, AI education, AI services, and AI-based business solutions.",
    "sameAs": [
      "https://www.linkedin.com/",
      "https://www.facebook.com/",
      "https://www.youtube.com/",
      "https://twitter.com/"
    ],
    "contactPoint": [{
      "@type": "ContactPoint",
      "contactType": "customer support",
      "email": "hello@geminidigitalai.com"
    }]
  }
  </script>

  <script type="application/ld+json">
  {
    "@context": "https://schema.org",
    "@type": "WebSite",
    "name": "geminidigitalai",
    "url": "https://example.com/",
    "potentialAction": {
      "@type": "SearchAction",
      "target": "https://example.com/?q={search_term_string}",
      "query-input": "required name=search_term_string"
    }
  }
  </script>
</head>

<body class="min-h-screen">
  <a href="#main" class="sr-only focus:not-sr-only focus:fixed focus:left-4 focus:top-4 focus:z-[80] focus:rounded-xl focus:bg-white/90 focus:px-4 focus:py-2 focus:text-black">Skip to content</a>

  <!-- Top bar -->
  <header class="sticky top-0 z-50 site-header">
    <div class="mx-auto max-w-7xl px-4 sm:px-6 lg:px-8 pt-4">
      <div class="glass rounded-2xl">
        <div class="flex items-center justify-between gap-3 px-4 py-3 sm:px-5">
          <div class="flex items-center gap-3 min-w-0">
            <div class="relative h-10 w-10 rounded-2xl overflow-hidden border border-white/10 dark:border-white/10" aria-hidden="true">
              <div class="absolute inset-0" style="background: linear-gradient(140deg, rgba(92,225,255,.9), rgba(167,139,250,.85), rgba(251,113,133,.75));"></div>
              <div class="absolute inset-[2px] rounded-2xl bg-black/30 dark:bg-black/25"></div>
              <div class="absolute inset-0 grid place-items-center text-[11px] font-mono font-bold tracking-wider text-white">GDAI</div>
            </div>
            <div class="min-w-0">
              <div class="flex items-center gap-2">
                <span class="font-semibold tracking-tight text-base sm:text-lg">geminidigitalai</span>
                <span class="hidden sm:inline-flex chip rounded-full px-2 py-0.5 text-xs text-[color:var(--muted)]">AI Platform</span>
              </div>
              <p class="hidden sm:block text-xs text-[color:var(--muted)]">Tools • Education • Services • Solutions</p>
            </div>
          </div>

          <nav class="hidden lg:flex items-center gap-1" aria-label="Primary">
            <a class="nav-link" href="#home" data-route="home">Home</a>
            <a class="nav-link" href="#about" data-route="about">About</a>
            <a class="nav-link" href="#services" data-route="services">AI Services</a>
            <a class="nav-link" href="#tools" data-route="tools">AI Tools</a>
            <a class="nav-link" href="#blog" data-route="blog">Blog</a>
            <a class="nav-link" href="#contact" data-route="contact">Contact</a>
          </nav>

          <div class="flex items-center gap-2">
            <button id="themeToggle" class="btn btn-ghost focus-ring h-10 px-3" type="button" aria-label="Toggle dark/light mode">
              <svg id="iconSun" class="hidden h-5 w-5" viewBox="0 0 24 24" fill="none" aria-hidden="true">
                <path d="M12 18a6 6 0 1 0 0-12 6 6 0 0 0 0 12Z" stroke="currentColor" stroke-width="1.6"/>
                <path d="M12 2v2M12 20v2M4 12H2M22 12h-2M5 5l1.5 1.5M17.5 17.5 19 19M19 5l-1.5 1.5M5 19l1.5-1.5" stroke="currentColor" stroke-width="1.6" stroke-linecap="round"/>
              </svg>
              <svg id="iconMoon" class="h-5 w-5" viewBox="0 0 24 24" fill="none" aria-hidden="true">
                <path d="M21 13.2A7.6 7.6 0 0 1 10.8 3a6.8 6.8 0 1 0 10.2 10.2Z" stroke="currentColor" stroke-width="1.6" stroke-linejoin="round"/>
              </svg>
              <span class="hidden sm:inline text-sm text-[color:var(--muted)]" id="themeLabel">Dark</span>
            </button>

            <button id="mobileMenuBtn" class="lg:hidden btn btn-ghost focus-ring h-10 px-3" type="button" aria-controls="mobileMenu" aria-expanded="false" aria-label="Open menu">
              <svg class="h-5 w-5" viewBox="0 0 24 24" fill="none" aria-hidden="true">
                <path d="M4 7h16M4 12h16M4 17h16" stroke="currentColor" stroke-width="1.6" stroke-linecap="round"/>
              </svg>
            </button>

            <a class="hidden sm:inline-flex btn btn-primary focus-ring h-10 px-4" href="#contact" data-route="contact">
              <span>Get Started</span>
              <svg class="h-4 w-4" viewBox="0 0 24 24" fill="none" aria-hidden="true">
                <path d="M7 17 17 7M17 7H9M17 7v8" stroke="currentColor" stroke-width="1.8" stroke-linecap="round" stroke-linejoin="round"/>
              </svg>
            </a>
          </div>
        </div>

        <!-- Mobile menu -->
        <div id="mobileMenu" class="hidden border-t" style="border-color: var(--stroke);">
          <div class="px-4 py-3 sm:px-5">
            <div class="grid gap-1">
              <a class="nav-link" href="#home" data-route="home">Home</a>
              <a class="nav-link" href="#about" data-route="about">About</a>
              <a class="nav-link" href="#services" data-route="services">AI Services</a>
              <a class="nav-link" href="#tools" data-route="tools">AI Tools</a>
              <a class="nav-link" href="#blog" data-route="blog">Blog</a>
              <a class="nav-link" href="#contact" data-route="contact">Contact</a>
            </div>
            <div class="mt-3 flex gap-2">
              <a class="btn btn-primary focus-ring w-full" href="#contact" data-route="contact">Get Started</a>
              <a class="btn btn-ghost focus-ring w-full" href="#tools" data-route="tools">Explore AI</a>
            </div>
          </div>
        </div>

      </div>
    </div>
  </header>

  <main id="main" class="mx-auto max-w-7xl px-4 sm:px-6 lg:px-8 pb-20 pt-6 sm:pt-10">
    <!-- HOME -->
    <section id="home" class="section active" data-page="home" aria-label="Home page">
      <div class="grid gap-6 lg:grid-cols-12 items-stretch">
        <div class="lg:col-span-7">
          <div class="glass rounded-3xl p-5 sm:p-7 lg:p-8 relative overflow-hidden">
            <div class="absolute inset-0 opacity-70 pointer-events-none" aria-hidden="true" style="background: radial-gradient(700px 300px at 20% 10%, rgba(92,225,255,.18), transparent 60%), radial-gradient(650px 360px at 90% 0%, rgba(167,139,250,.22), transparent 60%);"></div>

            <div class="relative">
              <div class="flex flex-wrap items-center gap-2">
                <span class="chip rounded-full px-3 py-1 text-xs sm:text-sm text-[color:var(--muted)]">Futuristic AI platform</span>
                <span class="chip rounded-full px-3 py-1 text-xs sm:text-sm text-[color:var(--muted)]">Built for marketers & founders</span>
                <span class="chip rounded-full px-3 py-1 text-xs sm:text-sm text-[color:var(--muted)]">Tools • Education • Services</span>
              </div>

              <h1 class="mt-4 text-3xl sm:text-5xl font-semibold tracking-tight leading-[1.05]">
                Build, market, and automate with <span class="grad-text">AI-first</span> digital experiences.
              </h1>
              <p class="mt-4 text-base sm:text-lg text-[color:var(--muted)] max-w-2xl">
                geminidigitalai helps businesses and individuals ship smarter websites, generate high-quality content, deploy AI chatbots, and automate workflows—fast, secure, and scalable.
              </p>

              <div class="mt-6 flex flex-col sm:flex-row gap-3">
                <a class="btn btn-primary focus-ring w-full sm:w-auto" href="#contact" data-route="contact">
                  Get Started
                  <svg class="h-4 w-4" viewBox="0 0 24 24" fill="none" aria-hidden="true">
                    <path d="M7 17 17 7M17 7H9M17 7v8" stroke="currentColor" stroke-width="1.8" stroke-linecap="round" stroke-linejoin="round"/>
                  </svg>
                </a>
                <a class="btn btn-ghost focus-ring w-full sm:w-auto" href="#tools" data-route="tools">
                  Explore AI Tools
                  <svg class="h-4 w-4" viewBox="0 0 24 24" fill="none" aria-hidden="true">
                    <path d="M12 5v14M5 12h14" stroke="currentColor" stroke-width="1.8" stroke-linecap="round"/>
                  </svg>
                </a>
              </div>

              <div class="mt-7 grid grid-cols-2 sm:grid-cols-4 gap-3">
                <div class="glass-soft rounded-2xl p-3">
                  <div class="text-xs text-[color:var(--muted)]">Avg. delivery</div>
                  <div class="mt-1 text-lg font-semibold">7–14 days</div>
                </div>
                <div class="glass-soft rounded-2xl p-3">
                  <div class="text-xs text-[color:var(--muted)]">Automation impact</div>
                  <div class="mt-1 text-lg font-semibold">Up to 40%</div>
                </div>
                <div class="glass-soft rounded-2xl p-3">
                  <div class="text-xs text-[color:var(--muted)]">Core focus</div>
                  <div class="mt-1 text-lg font-semibold">Growth + UX</div>
                </div>
                <div class="glass-soft rounded-2xl p-3">
                  <div class="text-xs text-[color:var(--muted)]">Support</div>
                  <div class="mt-1 text-lg font-semibold">Human + AI</div>
                </div>
              </div>
            </div>
          </div>
        </div>

        <div class="lg:col-span-5">
          <div class="glass rounded-3xl p-5 sm:p-7 h-full relative overflow-hidden">
            <div class="absolute -right-10 -top-10 h-56 w-56 rounded-full opacity-30" aria-hidden="true" style="background: radial-gradient(circle at 30% 30%, rgba(92,225,255,.8), transparent 60%); filter: blur(2px);"></div>
            <div class="absolute -left-12 -bottom-12 h-64 w-64 rounded-full opacity-30" aria-hidden="true" style="background: radial-gradient(circle at 30% 30%, rgba(167,139,250,.8), transparent 60%);"></div>

            <div class="relative">
              <div class="flex items-center justify-between gap-2">
                <div>
                  <h2 class="text-lg font-semibold">AI Command Center</h2>
                  <p class="text-sm text-[color:var(--muted)]">A clear path from idea → implementation.</p>
                </div>
                <span class="chip rounded-full px-3 py-1 text-xs text-[color:var(--muted)] font-mono">v1.0</span>
              </div>

              <div class="mt-5 rounded-3xl border p-4 sm:p-5 relative overflow-hidden grid-fade" style="border-color: var(--stroke);">
                <div class="relative">
                  <div class="flex items-center gap-2">
                    <div class="h-2.5 w-2.5 rounded-full bg-red-400/70"></div>
                    <div class="h-2.5 w-2.5 rounded-full bg-yellow-400/70"></div>
                    <div class="h-2.5 w-2.5 rounded-full bg-green-400/70"></div>
                    <div class="ml-2 text-xs text-[color:var(--muted)] font-mono">/workspace/ai-growth</div>
                  </div>

                  <div class="mt-4 grid gap-3">
                    <div class="glass-soft rounded-2xl p-4">
                      <div class="flex items-center justify-between">
                        <div class="font-semibold">Strategy</div>
                        <div class="text-xs text-[color:var(--muted)]">Discovery</div>
                      </div>
                      <div class="mt-2 h-2 rounded-full" style="background: color-mix(in srgb, var(--stroke) 70%, transparent);">
                        <div class="h-2 rounded-full" style="width: 85%; background: linear-gradient(90deg, rgba(92,225,255,.9), rgba(167,139,250,.85));"></div>
                      </div>
                      <p class="mt-2 text-sm text-[color:var(--muted)]">Positioning, ICP, funnel mapping, and KPI plan.</p>
                    </div>

                    <div class="glass-soft rounded-2xl p-4 animate-floaty" style="animation: floaty 6s ease-in-out infinite;">
                      <div class="flex items-center justify-between">
                        <div class="font-semibold">Build</div>
                        <div class="text-xs text-[color:var(--muted)]">In progress</div>
                      </div>
                      <div class="mt-2 grid grid-cols-3 gap-2">
                        <div class="skeleton h-8 rounded-xl"></div>
                        <div class="skeleton h-8 rounded-xl"></div>
                        <div class="skeleton h-8 rounded-xl"></div>
                      </div>
                      <p class="mt-2 text-sm text-[color:var(--muted)]">Fast AI web builds with performance-first UX.</p>
                    </div>

                    <div class="glass-soft rounded-2xl p-4">
                      <div class="flex items-center justify-between">
                        <div class="font-semibold">Automate</div>
                        <div class="text-xs text-[color:var(--muted)]">Ready</div>
                      </div>
                      <div class="mt-2 flex flex-wrap gap-2">
                        <span class="chip rounded-full px-3 py-1 text-xs text-[color:var(--muted)]">Lead routing</span>
                        <span class="chip rounded-full px-3 py-1 text-xs text-[color:var(--muted)]">Email sequences</span>
                        <span class="chip rounded-full px-3 py-1 text-xs text-[color:var(--muted)]">CRM sync</span>
                        <span class="chip rounded-full px-3 py-1 text-xs text-[color:var(--muted)]">AI chatbot</span>
                      </div>
                      <p class="mt-2 text-sm text-[color:var(--muted)]">Reduce manual work; improve conversion speed.</p>
                    </div>
                  </div>
                </div>
              </div>

              <div class="mt-5 flex flex-col sm:flex-row gap-3">
                <a class="btn btn-ghost focus-ring w-full" href="#services" data-route="services">View AI Services</a>
                <button class="btn btn-primary focus-ring w-full" type="button" id="openChatFromHome">Ask the AI Assistant</button>
              </div>

            </div>
          </div>
        </div>
      </div>

      <div class="mt-8 glass rounded-3xl p-5 sm:p-7">
        <div class="flex flex-col lg:flex-row lg:items-end lg:justify-between gap-4">
          <div>
            <h2 class="text-2xl sm:text-3xl font-semibold tracking-tight">AI services overview</h2>
            <p class="mt-2 text-[color:var(--muted)] max-w-2xl">Everything you need to launch, grow, and optimize—with AI embedded into the workflow.</p>
          </div>
          <div class="flex gap-2">
            <button class="btn btn-ghost focus-ring px-3 h-10" type="button" id="servicesPrev" aria-label="Previous service">Prev</button>
            <button class="btn btn-ghost focus-ring px-3 h-10" type="button" id="servicesNext" aria-label="Next service">Next</button>
          </div>
        </div>

        <div class="mt-5 overflow-hidden">
          <div id="servicesCarousel" class="flex gap-3 transition-transform duration-500 will-change-transform">
            <!-- Cards inserted by JS -->
          </div>
        </div>

        <div class="mt-6 divider"></div>

        <div class="mt-6 grid gap-4 lg:grid-cols-3">
          <div class="glass-soft rounded-2xl p-5">
            <div class="flex items-center gap-3">
              <div class="h-10 w-10 rounded-2xl grid place-items-center border" style="border-color: var(--stroke); background: linear-gradient(135deg, rgba(92,225,255,.15), rgba(167,139,250,.12));">
                <svg class="h-5 w-5" viewBox="0 0 24 24" fill="none" aria-hidden="true"><path d="M12 2l9 5v10l-9 5-9-5V7l9-5Z" stroke="currentColor" stroke-width="1.6" stroke-linejoin="round"/><path d="M12 7v10" stroke="currentColor" stroke-width="1.6" stroke-linecap="round"/></svg>
              </div>
              <div>
                <div class="font-semibold">Why choose geminidigitalai</div>
                <div class="text-sm text-[color:var(--muted)]">Outcome-driven, not tool-driven.</div>
              </div>
            </div>
            <ul class="mt-4 space-y-2 text-sm text-[color:var(--muted)]">
              <li class="flex gap-2"><span class="text-[color:var(--text)]">•</span>AI + human review for reliable quality.</li>
              <li class="flex gap-2"><span class="text-[color:var(--text)]">•</span>Fast iterations, clear deliverables, transparent scope.</li>
              <li class="flex gap-2"><span class="text-[color:var(--text)]">•</span>Performance-first UX, SEO, and conversion design.</li>
            </ul>
          </div>

          <div class="glass-soft rounded-2xl p-5">
            <div class="flex items-center gap-3">
              <div class="h-10 w-10 rounded-2xl grid place-items-center border" style="border-color: var(--stroke); background: linear-gradient(135deg, rgba(167,139,250,.16), rgba(251,113,133,.10));">
                <svg class="h-5 w-5" viewBox="0 0 24 24" fill="none" aria-hidden="true"><path d="M20 7 10 17l-5-5" stroke="currentColor" stroke-width="1.8" stroke-linecap="round" stroke-linejoin="round"/></svg>
              </div>
              <div>
                <div class="font-semibold">Secure by design</div>
                <div class="text-sm text-[color:var(--muted)]">Best-practice workflows.</div>
              </div>
            </div>
            <ul class="mt-4 space-y-2 text-sm text-[color:var(--muted)]">
              <li class="flex gap-2"><span class="text-[color:var(--text)]">•</span>Input validation & spam protection patterns.</li>
              <li class="flex gap-2"><span class="text-[color:var(--text)]">•</span>Privacy-aware chatbot and data handling.</li>
              <li class="flex gap-2"><span class="text-[color:var(--text)]">•</span>Speed optimizations for mobile-first performance.</li>
            </ul>
          </div>

          <div class="glass-soft rounded-2xl p-5">
            <div class="flex items-center gap-3">
              <div class="h-10 w-10 rounded-2xl grid place-items-center border" style="border-color: var(--stroke); background: linear-gradient(135deg, rgba(92,225,255,.12), rgba(251,113,133,.10));">
                <svg class="h-5 w-5" viewBox="0 0 24 24" fill="none" aria-hidden="true"><path d="M12 20a8 8 0 1 0 0-16 8 8 0 0 0 0 16Z" stroke="currentColor" stroke-width="1.6"/><path d="M12 6v6l4 2" stroke="currentColor" stroke-width="1.6" stroke-linecap="round" stroke-linejoin="round"/></svg>
              </div>
              <div>
                <div class="font-semibold">Faster learning curve</div>
                <div class="text-sm text-[color:var(--muted)]">Education + templates.</div>
              </div>
            </div>
            <p class="mt-4 text-sm text-[color:var(--muted)]">
              Get simple guides, checklists, and real-world examples to apply AI in marketing, operations, and product—without the jargon.
            </p>
            <div class="mt-4">
              <a class="btn btn-ghost focus-ring w-full" href="#blog" data-route="blog">Visit Knowledge Hub</a>
            </div>
          </div>
        </div>
      </div>

      <div class="mt-8 grid gap-6 lg:grid-cols-12">
        <div class="lg:col-span-7">
          <div class="glass rounded-3xl p-5 sm:p-7">
            <div class="flex items-center justify-between gap-4">
              <div>
                <h2 class="text-2xl sm:text-3xl font-semibold tracking-tight">Testimonials</h2>
                <p class="mt-2 text-[color:var(--muted)]">What clients and learners say about our AI-first approach.</p>
              </div>
              <div class="flex gap-2">
                <button class="btn btn-ghost focus-ring px-3 h-10" type="button" id="testPrev">Prev</button>
                <button class="btn btn-ghost focus-ring px-3 h-10" type="button" id="testNext">Next</button>
              </div>
            </div>

            <div class="mt-5 relative overflow-hidden">
              <div id="testTrack" class="flex gap-3 transition-transform duration-500 will-change-transform">
                <!-- inserted by JS -->
              </div>
            </div>
          </div>
        </div>

        <div class="lg:col-span-5">
          <div class="glass rounded-3xl p-5 sm:p-7">
            <h2 class="text-2xl sm:text-3xl font-semibold tracking-tight">Newsletter</h2>
            <p class="mt-2 text-[color:var(--muted)]">AI tips, new tools, and practical guides—sent weekly. No spam.</p>
            <form id="newsletterForm" class="mt-5 grid gap-3" autocomplete="on">
              <label class="grid gap-1">
                <span class="text-sm text-[color:var(--muted)]">Email</span>
                <input class="focus-ring w-full rounded-2xl border bg-transparent px-4 py-3 text-sm" style="border-color: var(--stroke);" type="email" name="email" placeholder="you@company.com" required />
              </label>
              <div class="flex flex-col sm:flex-row gap-3">
                <button class="btn btn-primary focus-ring w-full sm:w-auto" type="submit">Subscribe</button>
                <button class="btn btn-ghost focus-ring w-full sm:w-auto" type="button" id="newsletterDemoFill">Use demo email</button>
              </div>
              <p class="text-xs text-[color:var(--muted)]">By subscribing, you agree to receive emails from geminidigitalai. Unsubscribe anytime.</p>
              <div id="newsletterToast" class="hidden rounded-2xl border p-4 text-sm" style="border-color: var(--stroke); background: color-mix(in srgb, var(--card2) 80%, transparent);"></div>
            </form>
          </div>
        </div>
      </div>
    </section>

    <!-- ABOUT -->
    <section id="about" class="section" data-page="about" aria-label="About page">
      <div class="glass rounded-3xl p-5 sm:p-7 lg:p-8 relative overflow-hidden">
        <div class="absolute inset-0 opacity-70 pointer-events-none" aria-hidden="true" style="background: radial-gradient(900px 400px at 15% 10%, rgba(167,139,250,.22), transparent 60%), radial-gradient(800px 380px at 90% 30%, rgba(92,225,255,.18), transparent 60%);"></div>
        <div class="relative grid gap-6 lg:grid-cols-12">
          <div class="lg:col-span-7">
            <span class="chip rounded-full px-3 py-1 text-xs text-[color:var(--muted)]">About geminidigitalai</span>
            <h1 class="mt-4 text-3xl sm:text-5xl font-semibold tracking-tight leading-[1.05]">
              Our mission: make AI <span class="grad-text">usable</span>, <span class="grad-text">safe</span>, and <span class="grad-text">profitable</span>.
            </h1>
            <p class="mt-4 text-[color:var(--muted)] text-base sm:text-lg max-w-2xl">
              We’re building a complete AI-powered digital platform where anyone—from freelancers to enterprises—can learn AI, deploy tools, and implement solutions that drive measurable outcomes.
            </p>

            <div class="mt-6 grid gap-3 sm:grid-cols-2">
              <div class="glass-soft rounded-2xl p-5">
                <div class="text-sm text-[color:var(--muted)]">Vision</div>
                <div class="mt-1 font-semibold text-lg">An AI-driven future with human clarity</div>
                <p class="mt-2 text-sm text-[color:var(--muted)]">Technology should amplify creativity, not add complexity. We simplify AI into repeatable systems.</p>
              </div>
              <div class="glass-soft rounded-2xl p-5">
                <div class="text-sm text-[color:var(--muted)]">Mission</div>
                <div class="mt-1 font-semibold text-lg">Practical AI adoption for everyone</div>
                <p class="mt-2 text-sm text-[color:var(--muted)]">Tools, education, and services designed to help you launch faster and operate smarter.</p>
              </div>
            </div>
          </div>

          <div class="lg:col-span-5">
            <div class="glass-soft rounded-3xl p-5 sm:p-6 relative overflow-hidden">
              <div class="absolute -right-24 -top-24 h-64 w-64 rounded-full opacity-25" aria-hidden="true" style="background: radial-gradient(circle at 30% 30%, rgba(251,113,133,.85), transparent 60%);"></div>
              <div class="relative">
                <h2 class="text-xl font-semibold">Brand story</h2>
                <p class="mt-3 text-sm text-[color:var(--muted)]">
                  geminidigitalai started with a simple idea: people don’t need more AI hype—they need a clear system.
                  We combine modern UX, SEO, and automation with AI workflows that are auditable, maintainable, and designed for real users.
                </p>

                <div class="mt-5 grid gap-3">
                  <div class="rounded-2xl border p-4" style="border-color: var(--stroke); background: color-mix(in srgb, var(--card2) 72%, transparent);">
                    <div class="flex items-center justify-between gap-2">
                      <div class="font-semibold">Trust & credibility</div>
                      <div class="text-xs text-[color:var(--muted)]">What we optimize</div>
                    </div>
                    <ul class="mt-3 grid gap-2 text-sm text-[color:var(--muted)]">
                      <li class="flex gap-2"><span class="text-[color:var(--text)]">•</span>SEO-ready content architecture & metadata</li>
                      <li class="flex gap-2"><span class="text-[color:var(--text)]">•</span>Conversion-focused UI micro-interactions</li>
                      <li class="flex gap-2"><span class="text-[color:var(--text)]">•</span>Performance budgets for mobile</li>
                      <li class="flex gap-2"><span class="text-[color:var(--text)]">•</span>Security patterns and privacy-first data handling</li>
                    </ul>
                  </div>

                  <div class="flex flex-col sm:flex-row gap-3">
                    <a class="btn btn-primary focus-ring w-full sm:w-auto" href="#services" data-route="services">See AI Services</a>
                    <a class="btn btn-ghost focus-ring w-full sm:w-auto" href="#contact" data-route="contact">Work with us</a>
                  </div>
                </div>

              </div>
            </div>
          </div>

        </div>
      </div>
    </section>

    <!-- SERVICES -->
    <section id="services" class="section" data-page="services" aria-label="AI Services page">
      <div class="glass rounded-3xl p-5 sm:p-7 lg:p-8">
        <div class="flex flex-col lg:flex-row lg:items-end lg:justify-between gap-4">
          <div>
            <span class="chip rounded-full px-3 py-1 text-xs text-[color:var(--muted)]">AI Services</span>
            <h1 class="mt-4 text-3xl sm:text-5xl font-semibold tracking-tight">Production-ready AI services for real-world growth</h1>
            <p class="mt-3 text-[color:var(--muted)] max-w-2xl">Choose a service or combine them into a full AI growth system—strategy, build, content, automation, and optimization.</p>
          </div>
          <div class="flex flex-col sm:flex-row gap-3">
            <button class="btn btn-ghost focus-ring" type="button" id="serviceEstimatorBtn">Open Quick Estimator</button>
            <a class="btn btn-primary focus-ring" href="#contact" data-route="contact">Request a proposal</a>
          </div>
        </div>

        <div class="mt-6 grid gap-4 md:grid-cols-2 lg:grid-cols-3" id="servicesGrid">
          <!-- inserted by JS -->
        </div>

        <div class="mt-6 divider"></div>

        <div class="mt-6 grid gap-4 lg:grid-cols-12">
          <div class="lg:col-span-7">
            <div class="glass-soft rounded-3xl p-5 sm:p-6">
              <h2 class="text-xl font-semibold">How we deliver</h2>
              <div class="mt-4 grid gap-3">
                <div class="rounded-2xl border p-4" style="border-color: var(--stroke); background: color-mix(in srgb, var(--card2) 70%, transparent);">
                  <div class="flex items-center justify-between">
                    <div class="font-semibold">1) Discovery</div>
                    <div class="text-xs text-[color:var(--muted)]">Goals • Constraints • KPIs</div>
                  </div>
                  <p class="mt-2 text-sm text-[color:var(--muted)]">We map your use case, audience, and success metrics—then choose the simplest AI workflow that works.</p>
                </div>
                <div class="rounded-2xl border p-4" style="border-color: var(--stroke); background: color-mix(in srgb, var(--card2) 70%, transparent);">
                  <div class="flex items-center justify-between">
                    <div class="font-semibold">2) Build + integrate</div>
                    <div class="text-xs text-[color:var(--muted)]">UX • SEO • Automation</div>
                  </div>
                  <p class="mt-2 text-sm text-[color:var(--muted)]">We design for conversion, ship fast, and integrate AI tools safely—human review included.</p>
                </div>
                <div class="rounded-2xl border p-4" style="border-color: var(--stroke); background: color-mix(in srgb, var(--card2) 70%, transparent);">
                  <div class="flex items-center justify-between">
                    <div class="font-semibold">3) Optimize</div>
                    <div class="text-xs text-[color:var(--muted)]">Analytics • Iteration</div>
                  </div>
                  <p class="mt-2 text-sm text-[color:var(--muted)]">We track performance, improve content and funnels, and keep your system stable as you scale.</p>
                </div>
              </div>
            </div>
          </div>

          <div class="lg:col-span-5">
            <div class="glass-soft rounded-3xl p-5 sm:p-6">
              <h2 class="text-xl font-semibold">Quick Estimator</h2>
              <p class="mt-2 text-sm text-[color:var(--muted)]">A lightweight estimate to help you plan. Final pricing depends on scope and integrations.</p>

              <form id="estimatorForm" class="mt-4 grid gap-3">
                <label class="grid gap-1">
                  <span class="text-sm text-[color:var(--muted)]">Primary goal</span>
                  <select class="focus-ring w-full rounded-2xl border bg-transparent px-4 py-3 text-sm" style="border-color: var(--stroke);" name="goal" required>
                    <option value="leadgen">Generate leads</option>
                    <option value="content">Scale content</option>
                    <option value="automation">Automate operations</option>
                    <option value="chatbot">Deploy a chatbot</option>
                    <option value="full">Full AI growth system</option>
                  </select>
                </label>
                <label class="grid gap-1">
                  <span class="text-sm text-[color:var(--muted)]">Business size</span>
                  <select class="focus-ring w-full rounded-2xl border bg-transparent px-4 py-3 text-sm" style="border-color: var(--stroke);" name="size" required>
                    <option value="solo">Solo / Freelancer</option>
                    <option value="smb">SMB (2–20)</option>
                    <option value="mid">Mid (20–200)</option>
                    <option value="ent">Enterprise</option>
                  </select>
                </label>
                <label class="grid gap-1">
                  <span class="text-sm text-[color:var(--muted)]">Speed</span>
                  <select class="focus-ring w-full rounded-2xl border bg-transparent px-4 py-3 text-sm" style="border-color: var(--stroke);" name="speed" required>
                    <option value="standard">Standard</option>
                    <option value="fast">Fast track</option>
                  </select>
                </label>

                <div class="grid gap-2 sm:grid-cols-2">
                  <label class="flex items-center gap-2 rounded-2xl border px-4 py-3 text-sm" style="border-color: var(--stroke); background: color-mix(in srgb, var(--card2) 70%, transparent);">
                    <input type="checkbox" name="integrations" value="crm" />
                    <span>CRM integration</span>
                  </label>
                  <label class="flex items-center gap-2 rounded-2xl border px-4 py-3 text-sm" style="border-color: var(--stroke); background: color-mix(in srgb, var(--card2) 70%, transparent);">
                    <input type="checkbox" name="integrations" value="analytics" />
                    <span>Analytics setup</span>
                  </label>
                </div>

                <button class="btn btn-primary focus-ring" type="submit">Calculate estimate</button>
                <div id="estimateOutput" class="hidden rounded-2xl border p-4 text-sm" style="border-color: var(--stroke); background: color-mix(in srgb, var(--card2) 80%, transparent);"></div>
              </form>

              <div class="mt-4">
                <a class="btn btn-ghost focus-ring w-full" href="#contact" data-route="contact">Send this to our team</a>
              </div>
            </div>
          </div>

        </div>
      </div>
    </section>

    <!-- TOOLS -->
    <section id="tools" class="section" data-page="tools" aria-label="AI Tools page">
      <div class="glass rounded-3xl p-5 sm:p-7 lg:p-8">
        <div class="flex flex-col lg:flex-row lg:items-end lg:justify-between gap-4">
          <div>
            <span class="chip rounded-full px-3 py-1 text-xs text-[color:var(--muted)]">AI Tools</span>
            <h1 class="mt-4 text-3xl sm:text-5xl font-semibold tracking-tight">Practical AI tools with clear use cases</h1>
            <p class="mt-3 text-[color:var(--muted)] max-w-2xl">Pick a category to see recommended tools and how to use them in your workflow.</p>
          </div>
          <div class="flex flex-col sm:flex-row gap-3">
            <button class="btn btn-ghost focus-ring" type="button" id="toolsCopyPrompt">Copy a prompt template</button>
            <button class="btn btn-primary focus-ring" type="button" id="openChatFromTools">Ask for tool recommendations</button>
          </div>
        </div>

        <div class="mt-6 flex flex-wrap gap-2" role="tablist" aria-label="Tool categories">
          <button class="btn btn-ghost focus-ring px-4 h-10" type="button" data-tool-tab="writing" aria-selected="true">AI Writing</button>
          <button class="btn btn-ghost focus-ring px-4 h-10" type="button" data-tool-tab="image" aria-selected="false">Image Generation</button>
          <button class="btn btn-ghost focus-ring px-4 h-10" type="button" data-tool-tab="productivity" aria-selected="false">Productivity</button>
        </div>

        <div class="mt-5 grid gap-4 md:grid-cols-2 lg:grid-cols-3" id="toolsGrid">
          <!-- inserted by JS -->
        </div>

        <div class="mt-7 glass-soft rounded-3xl p-5 sm:p-6">
          <div class="flex flex-col lg:flex-row lg:items-center lg:justify-between gap-3">
            <div>
              <h2 class="text-xl font-semibold">Prompt starter kit</h2>
              <p class="mt-1 text-sm text-[color:var(--muted)]">A simple structure for consistent, high-quality outputs.</p>
            </div>
            <div class="flex gap-2">
              <button class="btn btn-ghost focus-ring px-3 h-10" type="button" id="promptShort">Short</button>
              <button class="btn btn-ghost focus-ring px-3 h-10" type="button" id="promptFull">Full</button>
            </div>
          </div>
          <pre id="promptBox" class="mt-4 rounded-2xl border p-4 overflow-auto text-xs sm:text-sm font-mono leading-relaxed chat-scroll" style="border-color: var(--stroke); background: color-mix(in srgb, var(--card2) 75%, transparent); white-space: pre-wrap;"></pre>
          <div class="mt-3 flex flex-col sm:flex-row gap-3">
            <button class="btn btn-primary focus-ring w-full sm:w-auto" type="button" id="copyPromptBtn">Copy prompt</button>
            <a class="btn btn-ghost focus-ring w-full sm:w-auto" href="#blog" data-route="blog">Learn prompt engineering</a>
          </div>
        </div>
      </div>
    </section>

    <!-- BLOG -->
    <section id="blog" class="section" data-page="blog" aria-label="Blog page">
      <div class="glass rounded-3xl p-5 sm:p-7 lg:p-8">
        <div class="flex flex-col lg:flex-row lg:items-end lg:justify-between gap-4">
          <div>
            <span class="chip rounded-full px-3 py-1 text-xs text-[color:var(--muted)]">Blog / Knowledge Hub</span>
            <h1 class="mt-4 text-3xl sm:text-5xl font-semibold tracking-tight">Learn AI with clear, SEO-friendly guides</h1>
            <p class="mt-3 text-[color:var(--muted)] max-w-2xl">Tutorials, trends, and practical playbooks for marketers, founders, freelancers, and tech learners.</p>
          </div>
          <div class="flex flex-col sm:flex-row gap-3">
            <button class="btn btn-ghost focus-ring" type="button" id="openCmsBtn">Open Mini CMS</button>
            <div class="flex gap-2">
              <input id="blogSearch" class="focus-ring w-full sm:w-64 rounded-2xl border bg-transparent px-4 py-3 text-sm" style="border-color: var(--stroke);" type="search" placeholder="Search articles..." aria-label="Search articles" />
              <button class="btn btn-primary focus-ring px-4" type="button" id="blogSearchBtn">Search</button>
            </div>
          </div>
        </div>

        <div class="mt-6 grid gap-4 lg:grid-cols-12">
          <div class="lg:col-span-8">
            <div id="blogList" class="grid gap-4">
              <!-- inserted by JS -->
            </div>
          </div>

          <aside class="lg:col-span-4">
            <div class="glass-soft rounded-3xl p-5 sm:p-6">
              <h2 class="text-xl font-semibold">Popular topics</h2>
              <div class="mt-4 flex flex-wrap gap-2" id="topicChips">
                <!-- inserted by JS -->
              </div>

              <div class="mt-6 divider"></div>

              <h2 class="mt-6 text-xl font-semibold">Get a curated learning path</h2>
              <p class="mt-2 text-sm text-[color:var(--muted)]">Tell the assistant your role and goal. It will suggest what to read and what to build next.</p>
              <button class="mt-4 btn btn-primary focus-ring w-full" type="button" id="openChatFromBlog">Ask the AI Assistant</button>

              <div class="mt-6 rounded-3xl border p-4" style="border-color: var(--stroke); background: color-mix(in srgb, var(--card2) 70%, transparent);">
                <div class="text-sm font-semibold">Blog CMS support</div>
                <p class="mt-2 text-sm text-[color:var(--muted)]">
                  This demo includes a mini CMS (localStorage) so you can add/edit posts in-browser. For production, connect to a headless CMS (e.g., Sanity, Strapi, Contentful).
                </p>
              </div>
            </div>
          </aside>
        </div>

      </div>
    </section>

    <!-- CONTACT -->
    <section id="contact" class="section" data-page="contact" aria-label="Contact page">
      <div class="glass rounded-3xl p-5 sm:p-7 lg:p-8">
        <div class="flex flex-col lg:flex-row lg:items-end lg:justify-between gap-4">
          <div>
            <span class="chip rounded-full px-3 py-1 text-xs text-[color:var(--muted)]">Contact</span>
            <h1 class="mt-4 text-3xl sm:text-5xl font-semibold tracking-tight">Let’s build your AI advantage</h1>
            <p class="mt-3 text-[color:var(--muted)] max-w-2xl">Tell us what you’re building. We’ll recommend the simplest AI solution that gets results—fast and safely.</p>
          </div>
          <div class="flex flex-col sm:flex-row gap-3">
            <a class="btn btn-ghost focus-ring" href="mailto:hello@geminidigitalai.com">Email: hello@geminidigitalai.com</a>
            <a class="btn btn-primary focus-ring" target="_blank" rel="noopener" href="https://wa.me/15551234567?text=Hi%20geminidigitalai%2C%20I%27d%20like%20help%20with%20AI%20services." aria-label="Chat on WhatsApp">WhatsApp / Live Chat</a>
          </div>
        </div>

        <div class="mt-6 grid gap-4 lg:grid-cols-12">
          <div class="lg:col-span-7">
            <div class="glass-soft rounded-3xl p-5 sm:p-6">
              <h2 class="text-xl font-semibold">Contact form</h2>
              <p class="mt-2 text-sm text-[color:var(--muted)]">We typically reply within 1–2 business days.</p>

              <form id="contactForm" class="mt-5 grid gap-3" novalidate>
                <div class="grid gap-3 sm:grid-cols-2">
                  <label class="grid gap-1">
                    <span class="text-sm text-[color:var(--muted)]">Full name</span>
                    <input class="focus-ring w-full rounded-2xl border bg-transparent px-4 py-3 text-sm" style="border-color: var(--stroke);" name="name" autocomplete="name" required placeholder="Your name" />
                  </label>
                  <label class="grid gap-1">
                    <span class="text-sm text-[color:var(--muted)]">Work email</span>
                    <input class="focus-ring w-full rounded-2xl border bg-transparent px-4 py-3 text-sm" style="border-color: var(--stroke);" name="email" autocomplete="email" required type="email" placeholder="you@company.com" />
                  </label>
                </div>

                <label class="grid gap-1">
                  <span class="text-sm text-[color:var(--muted)]">What do you need help with?</span>
                  <select class="focus-ring w-full rounded-2xl border bg-transparent px-4 py-3 text-sm" style="border-color: var(--stroke);" name="need" required>
                    <option value="">Select a topic</option>
                    <option>AI Website Development</option>
                    <option>AI Content Generation</option>
                    <option>AI Digital Marketing</option>
                    <option>AI Automation Solutions</option>
                    <option>AI Chatbot Development</option>
                    <option>AI Consulting</option>
                  </select>
                </label>

                <label class="grid gap-1">
                  <span class="text-sm text-[color:var(--muted)]">Project details</span>
                  <textarea class="focus-ring w-full rounded-2xl border bg-transparent px-4 py-3 text-sm min-h-[130px]" style="border-color: var(--stroke);" name="message" required placeholder="Goals, timeline, links, and any constraints..."></textarea>
                </label>

                <div class="flex flex-col sm:flex-row gap-3">
                  <button class="btn btn-primary focus-ring w-full sm:w-auto" type="submit">Send message</button>
                  <button class="btn btn-ghost focus-ring w-full sm:w-auto" type="button" id="contactDemoFill">Fill sample</button>
                  <button class="btn btn-ghost focus-ring w-full sm:w-auto" type="button" id="openChatFromContact">Chat with assistant</button>
                </div>

                <div id="contactToast" class="hidden rounded-2xl border p-4 text-sm" style="border-color: var(--stroke); background: color-mix(in srgb, var(--card2) 80%, transparent);"></div>
                <p class="text-xs text-[color:var(--muted)]">This demo does not submit to a server. In production, connect this to your backend (or a form provider) with spam protection and rate limiting.</p>
              </form>
            </div>
          </div>

          <div class="lg:col-span-5">
            <div class="glass-soft rounded-3xl p-5 sm:p-6">
              <h2 class="text-xl font-semibold">Social & quick links</h2>
              <div class="mt-4 grid gap-3">
                <a class="btn btn-ghost focus-ring w-full justify-between" href="#services" data-route="services">
                  <span>AI Services</span>
                  <span class="text-xs text-[color:var(--muted)]">See offerings</span>
                </a>
                <a class="btn btn-ghost focus-ring w-full justify-between" href="#tools" data-route="tools">
                  <span>AI Tools</span>
                  <span class="text-xs text-[color:var(--muted)]">Explore stack</span>
                </a>
                <a class="btn btn-ghost focus-ring w-full justify-between" href="#blog" data-route="blog">
                  <span>Knowledge Hub</span>
                  <span class="text-xs text-[color:var(--muted)]">Tutorials & guides</span>
                </a>
              </div>

              <div class="mt-6 divider"></div>

              <div class="mt-6 grid gap-3">
                <div class="rounded-3xl border p-5" style="border-color: var(--stroke); background: linear-gradient(135deg, rgba(92,225,255,.10), rgba(167,139,250,.10), rgba(251,113,133,.08));">
                  <div class="flex items-center justify-between gap-2">
                    <div class="font-semibold">Live chat</div>
                    <span class="chip rounded-full px-2 py-0.5 text-xs text-[color:var(--muted)]">AI Assistant</span>
                  </div>
                  <p class="mt-2 text-sm text-[color:var(--muted)]">Use the chatbot to get instant recommendations, tool suggestions, and next steps.</p>
                  <button class="mt-4 btn btn-primary focus-ring w-full" type="button" id="openChatFromCard">Open assistant</button>
                </div>

                <div class="rounded-3xl border p-5" style="border-color: var(--stroke); background: color-mix(in srgb, var(--card2) 70%, transparent);">
                  <div class="font-semibold">Security & performance</div>
                  <p class="mt-2 text-sm text-[color:var(--muted)]">
                    We prioritize: fast loading, accessible components, clean SEO, and privacy-aware data handling.
                  </p>
                  <div class="mt-3 flex flex-wrap gap-2">
                    <span class="chip rounded-full px-3 py-1 text-xs text-[color:var(--muted)]">Mobile-first</span>
                    <span class="chip rounded-full px-3 py-1 text-xs text-[color:var(--muted)]">Schema</span>
                    <span class="chip rounded-full px-3 py-1 text-xs text-[color:var(--muted)]">Metadata</span>
                    <span class="chip rounded-full px-3 py-1 text-xs text-[color:var(--muted)]">Best practices</span>
                  </div>
                </div>
              </div>

            </div>
          </div>
        </div>
      </div>
    </section>

    
    <footer class="mt-12">
      <div class="glass rounded-3xl p-5 sm:p-7">
        <div class="grid gap-8 lg:grid-cols-12">
          <!-- Brand -->
          <div class="lg:col-span-4">
            <div class="flex items-center gap-3">
              <div class="relative h-10 w-10 rounded-2xl overflow-hidden border" style="border-color: var(--stroke);" aria-hidden="true">
                <div class="absolute inset-0" style="background: linear-gradient(140deg, rgba(92,225,255,.9), rgba(167,139,250,.85), rgba(251,113,133,.75));"></div>
                <div class="absolute inset-[2px] rounded-2xl bg-black/30"></div>
                <div class="absolute inset-0 grid place-items-center text-[11px] font-mono font-bold tracking-wider text-white">GDAI</div>
              </div>
              <div>
                <div class="font-semibold">geminidigitalai</div>
                <p class="text-sm text-[color:var(--muted)]">AI tools, education, and services to build the future—today.</p>
              </div>
            </div>
            <p class="mt-4 text-sm text-[color:var(--muted)]">
              Fast, secure, and scalable AI-first builds: content, automation, chatbots, and growth systems.
            </p>
          </div>

          <!-- Quick links -->
          <div class="lg:col-span-4">
            <div class="text-sm font-semibold">Quick Links</div>
            <div class="mt-3 grid grid-cols-2 gap-2">
              <a class="nav-link inline-flex items-center justify-between" href="#home" data-route="home"><span>Home</span><span aria-hidden="true">→</span></a>
              <a class="nav-link inline-flex items-center justify-between" href="#about" data-route="about"><span>About</span><span aria-hidden="true">→</span></a>
              <a class="nav-link inline-flex items-center justify-between" href="#services" data-route="services"><span>AI Services</span><span aria-hidden="true">→</span></a>
              <a class="nav-link inline-flex items-center justify-between" href="#tools" data-route="tools"><span>AI Tools</span><span aria-hidden="true">→</span></a>
              <a class="nav-link inline-flex items-center justify-between" href="#blog" data-route="blog"><span>Blog</span><span aria-hidden="true">→</span></a>
              <a class="nav-link inline-flex items-center justify-between" href="#contact" data-route="contact"><span>Contact</span><span aria-hidden="true">→</span></a>
            </div>
          </div>

          <!-- Social -->
          <div class="lg:col-span-4">
            <div class="text-sm font-semibold">Social</div>
            <div class="mt-3 grid gap-2">
              <a class="glass-soft rounded-2xl px-4 py-3 flex items-center justify-between hover:translate-y-[-1px] transition" href="https://www.linkedin.com/" target="_blank" rel="noopener">
                <span class="flex items-center gap-3">
                  <span class="h-9 w-9 rounded-2xl grid place-items-center border" style="border-color: var(--stroke);">
                    <svg class="h-4 w-4" viewBox="0 0 24 24" fill="none" aria-hidden="true">
                      <path d="M6.5 9.5V18M6.5 6.5v.2M10 18v-5.2c0-1.6 1-2.8 2.6-2.8 1.4 0 2.4.9 2.6 2.2.02.2.02.4.02.6V18M10 12.3c.3-1.3 1.4-2.3 2.9-2.3" stroke="currentColor" stroke-width="1.6" stroke-linecap="round"/>
                    </svg>
                  </span>
                  <span class="text-sm font-medium">LinkedIn</span>
                </span>
                <span class="text-xs text-[color:var(--muted)]">Follow →</span>
              </a>

              <a class="glass-soft rounded-2xl px-4 py-3 flex items-center justify-between hover:translate-y-[-1px] transition" href="https://www.facebook.com/" target="_blank" rel="noopener">
                <span class="flex items-center gap-3">
                  <span class="h-9 w-9 rounded-2xl grid place-items-center border" style="border-color: var(--stroke);">
                    <svg class="h-4 w-4" viewBox="0 0 24 24" fill="none" aria-hidden="true">
                      <path d="M14 8h2V5h-2c-2 0-4 1.6-4 4v2H8v3h2v7h3v-7h2l1-3h-3V9c0-.6.4-1 1-1Z" stroke="currentColor" stroke-width="1.6" stroke-linejoin="round"/>
                    </svg>
                  </span>
                  <span class="text-sm font-medium">Facebook</span>
                </span>
                <span class="text-xs text-[color:var(--muted)]">Like →</span>
              </a>

              <a class="glass-soft rounded-2xl px-4 py-3 flex items-center justify-between hover:translate-y-[-1px] transition" href="https://www.youtube.com/" target="_blank" rel="noopener">
                <span class="flex items-center gap-3">
                  <span class="h-9 w-9 rounded-2xl grid place-items-center border" style="border-color: var(--stroke);">
                    <svg class="h-4 w-4" viewBox="0 0 24 24" fill="none" aria-hidden="true">
                      <path d="M10 15.5V8.5l6 3.5-6 3.5Z" stroke="currentColor" stroke-width="1.6" stroke-linejoin="round"/>
                      <path d="M21 7.5a3 3 0 0 0-2.2-2.2C17 5 12 5 12 5s-5 0-6.8.3A3 3 0 0 0 3 7.5 31 31 0 0 0 3 12s0 3.5.2 4.5a3 3 0 0 0 2.2 2.2C7 19 12 19 12 19s5 0 6.8-.3A3 3 0 0 0 21 16.5 31 31 0 0 0 21 12s0-3.5-.0-4.5Z" stroke="currentColor" stroke-width="1.6" stroke-linejoin="round"/>
                    </svg>
                  </span>
                  <span class="text-sm font-medium">YouTube</span>
                </span>
                <span class="text-xs text-[color:var(--muted)]">Watch →</span>
              </a>

              <a class="glass-soft rounded-2xl px-4 py-3 flex items-center justify-between hover:translate-y-[-1px] transition" href="https://twitter.com/" target="_blank" rel="noopener">
                <span class="flex items-center gap-3">
                  <span class="h-9 w-9 rounded-2xl grid place-items-center border" style="border-color: var(--stroke);">
                    <svg class="h-4 w-4" viewBox="0 0 24 24" fill="none" aria-hidden="true">
                      <path d="M18 6 6 18M7 6h4l6 12h-4L7 6Z" stroke="currentColor" stroke-width="1.6" stroke-linecap="round" stroke-linejoin="round"/>
                    </svg>
                  </span>
                  <span class="text-sm font-medium">X (Twitter)</span>
                </span>
                <span class="text-xs text-[color:var(--muted)]">Post →</span>
              </a>
            </div>
          </div>
        </div>

        <div class="mt-7 divider"></div>

        <div class="mt-5 flex flex-col md:flex-row md:items-center md:justify-between gap-3">
          <p class="text-xs text-[color:var(--muted)]">
            © <span id="year"></span> geminidigitalai. All rights reserved.
          </p>
          <div class="flex flex-wrap items-center gap-x-4 gap-y-2 text-xs">
            <a class="text-[color:var(--muted)] hover:text-[color:var(--text)]" href="#terms">Terms &amp; Conditions</a>
            <a class="text-[color:var(--muted)] hover:text-[color:var(--text)]" href="#privacy">Privacy Policy</a>
            <span class="text-[color:var(--muted)] hidden sm:inline">•</span>
            <span class="text-[color:var(--muted)]">Built with modern UX + SEO-ready structure.</span>
          </div>
        </div>
      </div>
    </footer>

  </main>

  <!-- Chatbot floating button -->
  <div class="chat-fab">
    <button id="chatToggle" class="btn btn-primary focus-ring rounded-2xl h-12 px-4 shadow-glow" type="button" aria-haspopup="dialog" aria-expanded="false" aria-controls="chatPanel">
      <span class="relative">
        <span class="absolute -inset-2 rounded-2xl opacity-40" style="background: radial-gradient(circle at 30% 30%, rgba(92,225,255,.55), transparent 60%);"></span>
        <span class="absolute -inset-2 rounded-2xl opacity-30 animate-pulseRing" style="background: radial-gradient(circle at 30% 30%, rgba(167,139,250,.55), transparent 60%);"></span>
      </span>
      <svg class="h-5 w-5" viewBox="0 0 24 24" fill="none" aria-hidden="true">
        <path d="M20 12a7 7 0 0 1-7 7H7l-3 3v-6a7 7 0 1 1 16-4Z" stroke="currentColor" stroke-width="1.7" stroke-linejoin="round"/>
        <path d="M8 11h8M8 15h5" stroke="currentColor" stroke-width="1.7" stroke-linecap="round"/>
      </svg>
      <span class="text-sm font-semibold">AI Assistant</span>
    </button>
  </div>

  <!-- Chatbot panel -->
  <div id="chatPanel" class="chat-panel" role="dialog" aria-modal="true" aria-label="AI Assistant chat">
    <div class="glass rounded-3xl overflow-hidden">
      <div class="flex items-center justify-between gap-3 px-4 py-3 border-b" style="border-color: var(--stroke);">
        <div class="min-w-0">
          <div class="flex items-center gap-2">
            <div class="h-2.5 w-2.5 rounded-full bg-green-400/70"></div>
            <div class="font-semibold truncate">geminidigitalai Assistant</div>
            <span class="chip rounded-full px-2 py-0.5 text-xs text-[color:var(--muted)]">demo</span>
          </div>
          <div class="text-xs text-[color:var(--muted)]">Ask about services, tools, learning paths, or next steps.</div>
        </div>
        <button id="chatClose" class="btn btn-ghost focus-ring h-10 px-3" type="button" aria-label="Close chat">
          <svg class="h-5 w-5" viewBox="0 0 24 24" fill="none" aria-hidden="true">
            <path d="M6 6l12 12M18 6 6 18" stroke="currentColor" stroke-width="1.8" stroke-linecap="round"/>
          </svg>
        </button>
      </div>

      <div id="chatMessages" class="chat-scroll px-4 py-4 space-y-3 overflow-auto" style="height: min(430px, calc(100vh - 280px));">
        <!-- inserted by JS -->
      </div>

      <div class="border-t px-4 py-3" style="border-color: var(--stroke);">
        <div class="flex flex-wrap gap-2 mb-2">
          <button class="chip rounded-full px-3 py-1 text-xs focus-ring" type="button" data-quick="Recommend AI tools for social media content">Tools for social</button>
          <button class="chip rounded-full px-3 py-1 text-xs focus-ring" type="button" data-quick="What AI service should I choose for lead generation?">Lead gen</button>
          <button class="chip rounded-full px-3 py-1 text-xs focus-ring" type="button" data-quick="Create a 7-day learning plan for AI marketing">Learning plan</button>
          <button class="chip rounded-full px-3 py-1 text-xs focus-ring" type="button" data-quick="How can I automate client onboarding?">Automate ops</button>
        </div>
        <form id="chatForm" class="flex gap-2" autocomplete="off">
          <input id="chatInput" class="focus-ring flex-1 rounded-2xl border bg-transparent px-4 py-3 text-sm" style="border-color: var(--stroke);" placeholder="Type your message..." required />
          <button class="btn btn-primary focus-ring px-4" type="submit">Send</button>
        </form>
        <div class="mt-2 text-[11px] text-[color:var(--muted)]">
          Demo assistant: no external API calls. Don’t share sensitive information.
        </div>
      </div>
    </div>
  </div>

  <!-- Mini CMS Modal -->
  <div id="cmsModal" class="fixed inset-0 z-[70] hidden" aria-hidden="true">
    <div class="absolute inset-0" style="background: rgba(0,0,0,.55);"></div>
    <div class="relative mx-auto max-w-3xl px-4 sm:px-6 lg:px-8 py-10">
      <div class="glass rounded-3xl overflow-hidden">
        <div class="flex items-center justify-between gap-3 px-4 py-3 border-b" style="border-color: var(--stroke);">
          <div>
            <div class="font-semibold">Mini Blog CMS (localStorage)</div>
            <div class="text-xs text-[color:var(--muted)]">Add/edit posts for this demo. Not for production use.</div>
          </div>
          <button id="cmsClose" class="btn btn-ghost focus-ring h-10 px-3" type="button" aria-label="Close CMS">
            <svg class="h-5 w-5" viewBox="0 0 24 24" fill="none" aria-hidden="true">
              <path d="M6 6l12 12M18 6 6 18" stroke="currentColor" stroke-width="1.8" stroke-linecap="round"/>
            </svg>
          </button>
        </div>

        <div class="p-4 sm:p-6 grid gap-4">
          <form id="cmsForm" class="grid gap-3">
            <input type="hidden" name="id" />
            <div class="grid gap-3 sm:grid-cols-2">
              <label class="grid gap-1">
                <span class="text-sm text-[color:var(--muted)]">Title</span>
                <input class="focus-ring w-full rounded-2xl border bg-transparent px-4 py-3 text-sm" style="border-color: var(--stroke);" name="title" required placeholder="e.g., AI Marketing: A Practical Starter Guide" />
              </label>
              <label class="grid gap-1">
                <span class="text-sm text-[color:var(--muted)]">Category</span>
                <input class="focus-ring w-full rounded-2xl border bg-transparent px-4 py-3 text-sm" style="border-color: var(--stroke);" name="category" required placeholder="Tutorial / News / How-to" />
              </label>
            </div>
            <div class="grid gap-3 sm:grid-cols-3">
              <label class="grid gap-1">
                <span class="text-sm text-[color:var(--muted)]">Read time</span>
                <input class="focus-ring w-full rounded-2xl border bg-transparent px-4 py-3 text-sm" style="border-color: var(--stroke);" name="readTime" required placeholder="6 min" />
              </label>
              <label class="grid gap-1">
                <span class="text-sm text-[color:var(--muted)]">Tags (comma-separated)</span>
                <input class="focus-ring w-full rounded-2xl border bg-transparent px-4 py-3 text-sm" style="border-color: var(--stroke);" name="tags" required placeholder="SEO, Prompts, Automation" />
              </label>
              <label class="grid gap-1">
                <span class="text-sm text-[color:var(--muted)]">Author</span>
                <input class="focus-ring w-full rounded-2xl border bg-transparent px-4 py-3 text-sm" style="border-color: var(--stroke);" name="author" required placeholder="geminidigitalai" />
              </label>
            </div>
            <label class="grid gap-1">
              <span class="text-sm text-[color:var(--muted)]">Excerpt</span>
              <textarea class="focus-ring w-full rounded-2xl border bg-transparent px-4 py-3 text-sm min-h-[88px]" style="border-color: var(--stroke);" name="excerpt" required placeholder="A one-paragraph summary for SEO and previews."></textarea>
            </label>
            <label class="grid gap-1">
              <span class="text-sm text-[color:var(--muted)]">Content (markdown-ish)</span>
              <textarea class="focus-ring w-full rounded-2xl border bg-transparent px-4 py-3 text-sm min-h-[170px]" style="border-color: var(--stroke);" name="content" required placeholder="Use headings, bullet points, and short paragraphs."></textarea>
            </label>
            <div class="flex flex-col sm:flex-row gap-3">
              <button class="btn btn-primary focus-ring w-full sm:w-auto" type="submit">Save post</button>
              <button class="btn btn-ghost focus-ring w-full sm:w-auto" type="button" id="cmsReset">New post</button>
              <button class="btn btn-ghost focus-ring w-full sm:w-auto" type="button" id="cmsSeed">Reset demo posts</button>
            </div>
          </form>

          <div class="divider"></div>

          <div>
            <div class="flex items-center justify-between gap-2">
              <div class="font-semibold">All posts</div>
              <button class="btn btn-ghost focus-ring h-10 px-3" type="button" id="cmsExport">Export JSON</button>
            </div>
            <div id="cmsList" class="mt-3 grid gap-3">
              <!-- inserted by JS -->
            </div>
          </div>

        </div>
      </div>
    </div>
  </div>

  <!-- Post Reader Modal -->
  <div id="postModal" class="fixed inset-0 z-[75] hidden" aria-hidden="true">
    <div class="absolute inset-0" style="background: rgba(0,0,0,.55);"></div>
    <div class="relative mx-auto max-w-4xl px-4 sm:px-6 lg:px-8 py-10">
      <article class="glass rounded-3xl overflow-hidden">
        <div class="flex items-center justify-between gap-3 px-4 py-3 border-b" style="border-color: var(--stroke);">
          <div class="min-w-0">
            <div id="postMeta" class="text-xs text-[color:var(--muted)]"></div>
            <h2 id="postTitle" class="mt-1 font-semibold text-lg sm:text-xl truncate"></h2>
          </div>
          <button id="postClose" class="btn btn-ghost focus-ring h-10 px-3" type="button" aria-label="Close article">
            <svg class="h-5 w-5" viewBox="0 0 24 24" fill="none" aria-hidden="true">
              <path d="M6 6l12 12M18 6 6 18" stroke="currentColor" stroke-width="1.8" stroke-linecap="round"/>
            </svg>
          </button>
        </div>
        <div class="p-4 sm:p-6">
          <div id="postTags" class="flex flex-wrap gap-2"></div>
          <div id="postContent" class="mt-4 text-sm sm:text-base leading-relaxed text-[color:var(--muted)] whitespace-pre-wrap"></div>
          <div class="mt-6 divider"></div>
          <div class="mt-5 flex flex-col sm:flex-row gap-3">
            <button class="btn btn-primary focus-ring w-full sm:w-auto" type="button" id="postAskAssistant">Ask assistant about this</button>
            <button class="btn btn-ghost focus-ring w-full sm:w-auto" type="button" id="postCopyLink">Copy link</button>
          </div>
        </div>
      </article>
    </div>
  </div>

  <script>
    // ---------- Utilities ----------
    const $ = (sel, el=document) => el.querySelector(sel);
    const $$ = (sel, el=document) => Array.from(el.querySelectorAll(sel));
    const clamp = (n,min,max)=>Math.max(min,Math.min(max,n));
    const escapeHtml = (s='') => s.replace(/[&<>"']/g, m => ({'&':'&amp;','<':'&lt;','>':'&gt;','"':'&quot;',"'":'&#039;'}[m]));
    const uid = () => Math.random().toString(16).slice(2) + Date.now().toString(16);

    // ---------- Theme ----------
    const root = document.documentElement;
    const themeToggle = $('#themeToggle');
    const themeLabel = $('#themeLabel');
    const iconSun = $('#iconSun');
    const iconMoon = $('#iconMoon');

    function applyTheme(mode){
      // mode: 'dark' or 'light'
      if(mode === 'light'){
        root.classList.add('light');
        root.classList.remove('dark');
        iconSun.classList.remove('hidden');
        iconMoon.classList.add('hidden');
        themeLabel.textContent = 'Light';
        document.querySelector('meta[name="theme-color"]').setAttribute('content', '#F7F8FC');
      } else {
        root.classList.remove('light');
        root.classList.add('dark');
        iconSun.classList.add('hidden');
        iconMoon.classList.remove('hidden');
        themeLabel.textContent = 'Dark';
        document.querySelector('meta[name="theme-color"]').setAttribute('content', '#0B1020');
      }
      localStorage.setItem('gdai_theme', mode);
    }

    function initTheme(){
      const saved = localStorage.getItem('gdai_theme');
      if(saved){
        applyTheme(saved);
        return;
      }
      const prefersDark = window.matchMedia && window.matchMedia('(prefers-color-scheme: dark)').matches;
      applyTheme(prefersDark ? 'dark' : 'light');
    }

    themeToggle.addEventListener('click', () => {
      const isLight = root.classList.contains('light');
      applyTheme(isLight ? 'dark' : 'light');
    });

    initTheme();

    // ---------- Routing (SPA-like) ----------
    const sections = $$('.section');
    const navLinks = $$('a[data-route], nav a[data-route]');
    const mobileMenu = $('#mobileMenu');
    const mobileBtn = $('#mobileMenuBtn');

    function setActiveRoute(route){
      sections.forEach(s => s.classList.toggle('active', s.dataset.page === route));
      $$('a[data-route]').forEach(a => a.setAttribute('aria-current', a.dataset.route === route ? 'page' : 'false'));
      if(mobileMenu && !mobileMenu.classList.contains('hidden')) toggleMobileMenu(false);
      window.scrollTo({ top: 0, behavior: 'smooth' });
      document.title = pageTitles[route] || pageTitles.home;
    }

    const pageTitles = {
      home: 'geminidigitalai — AI Tools, Education, Services & Business Solutions',
      about: 'About — geminidigitalai',
      services: 'AI Services — geminidigitalai',
      tools: 'AI Tools — geminidigitalai',
      blog: 'Blog / Knowledge Hub — geminidigitalai',
      contact: 'Contact — geminidigitalai'
    };

    function routeFromHash(){
      const h = (location.hash || '#home').replace('#','').trim();
      const route = ['home','about','services','tools','blog','contact'].includes(h) ? h : 'home';
      setActiveRoute(route);
    }

    window.addEventListener('hashchange', routeFromHash);

    // Intercept internal navigation for smoothness
    document.addEventListener('click', (e) => {
      const a = e.target.closest('a[data-route]');
      if(!a) return;
      const route = a.dataset.route;
      if(!route) return;
      e.preventDefault();
      history.pushState(null, '', `#${route}`);
      routeFromHash();
    });

    window.addEventListener('popstate', routeFromHash);

    function toggleMobileMenu(force){
      const open = typeof force === 'boolean' ? force : mobileMenu.classList.contains('hidden');
      mobileMenu.classList.toggle('hidden', !open);
      mobileBtn.setAttribute('aria-expanded', open ? 'true' : 'false');
    }

    mobileBtn.addEventListener('click', () => toggleMobileMenu());

    // ---------- Data (Services, Tools, Testimonials, Blog) ----------
    const services = [
      {
        title: 'AI Website Development',
        desc: 'Modern, conversion-focused websites with SEO architecture, fast performance, and AI-ready components.',
        bullets: ['UX + UI system', 'SEO + schema', 'Speed & accessibility'],
        accent: 'rgba(92,225,255,.22)'
      },
      {
        title: 'AI Content Generation',
        desc: 'Human-reviewed AI content for landing pages, blogs, ads, email sequences, and product messaging.',
        bullets: ['Tone alignment', 'Originality checks', 'SEO optimization'],
        accent: 'rgba(167,139,250,.22)'
      },
      {
        title: 'AI Digital Marketing',
        desc: 'AI-powered strategy for social, search, and email with testing loops and measurable growth.',
        bullets: ['Offer + funnel', 'Ad/SEO research', 'Creative iterations'],
        accent: 'rgba(251,113,133,.20)'
      },
      {
        title: 'AI Automation Solutions',
        desc: 'Automate repetitive operations: lead routing, reporting, onboarding, and internal workflows.',
        bullets: ['Workflow mapping', 'Tool integration', 'Monitoring + QA'],
        accent: 'rgba(167,139,250,.18)'
      },
      {
        title: 'AI Chatbot Development',
        desc: 'Site and support chatbots with guardrails, knowledge sources, and lead capture.',
        bullets: ['FAQs + knowledge', 'Lead qualification', 'Handoff to humans'],
        accent: 'rgba(92,225,255,.18)'
      },
      {
        title: 'AI Consulting',
        desc: 'Clarity-first AI adoption: roadmap, vendor/tool selection, governance, and training.',
        bullets: ['Use-case selection', 'Risk controls', 'Team enablement'],
        accent: 'rgba(251,113,133,.16)'
      }
    ];

    const toolsByTab = {
      writing: [
        { name: 'AI Writing Assistant', use: 'Blogs, landing pages, emails', how: 'Draft fast, then refine with a brand voice checklist and human editing.', tags: ['SEO', 'Brand voice', 'Outlines'] },
        { name: 'Ad Copy Generator', use: 'Paid ads & social hooks', how: 'Generate 20 variations, test 3–5, iterate based on CTR and conversion.', tags: ['Testing', 'Hooks', 'Performance'] },
        { name: 'Content Brief Builder', use: 'SEO article planning', how: 'Create keyword clusters, headings, and intent mapping before writing.', tags: ['Keywords', 'Structure', 'Intent'] }
      ],
      image: [
        { name: 'AI Image Generator', use: 'Creative assets & concepts', how: 'Use consistent styles (lighting, lens, palette) to create brand-safe visuals.', tags: ['Brand style', 'Consistency', 'Concepts'] },
        { name: 'Product Mockup Tool', use: 'Launch pages & ads', how: 'Turn screenshots into mockups to improve perceived product value.', tags: ['Mockups', 'Ads', 'Landing pages'] },
        { name: 'Background Remover', use: 'E-commerce & thumbnails', how: 'Batch process images, then compress for speed and SEO.', tags: ['Ecom', 'Speed', 'Cleanup'] }
      ],
      productivity: [
        { name: 'Meeting Summarizer', use: 'Notes & action items', how: 'Summarize decisions, owners, deadlines; push to your task tracker.', tags: ['Ops', 'Teams', 'Execution'] },
        { name: 'Workflow Automator', use: 'Integrations across tools', how: 'Trigger actions from form submissions to CRM + email + Slack updates.', tags: ['Automation', 'Integrations', 'Scaling'] },
        { name: 'AI Research Copilot', use: 'Competitor and market research', how: 'Generate a research matrix and validate with sources before decisions.', tags: ['Research', 'Strategy', 'Validation'] }
      ]
    };

    const testimonials = [
      {
        quote: 'We launched a clean, fast website with AI-assisted content in under two weeks. The funnel is clearer and conversions improved.',
        name: 'Amina R.',
        role: 'Founder, eCommerce brand'
      },
      {
        quote: 'The AI automation setup removed hours of manual follow-ups each week. Our onboarding is now consistent and trackable.',
        name: 'Daniel K.',
        role: 'Agency Owner'
      },
      {
        quote: 'The knowledge hub broke down AI into steps I could actually apply. No fluff—just practical frameworks.',
        name: 'Sofia M.',
        role: 'Freelance Marketer'
      }
    ];

    const seedPosts = [
      {
        id: 'p1',
        title: 'AI Marketing: A Practical Starter Guide (No Hype)',
        category: 'Tutorial',
        readTime: '7 min',
        tags: ['AI Marketing', 'Funnels', 'Testing'],
        author: 'geminidigitalai',
        dateISO: new Date(Date.now() - 1000*60*60*24*10).toISOString(),
        excerpt: 'A clear system to apply AI in marketing: define the offer, map the funnel, generate variations, and run a feedback loop with metrics.',
        content:
`## What AI is best at (in marketing)
- Generating variations quickly (hooks, angles, CTAs)
- Summarizing research (positioning, competitor matrices)
- Drafting content outlines and briefs

## A simple workflow
1) Define your goal: leads, sales, retention
2) Map your funnel stages and key metrics
3) Generate 10–20 variations
4) Test 3–5 and iterate based on results

## Guardrails (important)
- Keep a brand voice checklist
- Validate facts and claims
- Use analytics to decide what "good" means

## Next step
Ask the assistant: "Build me a 14-day plan for AI marketing for my niche."`
      },
      {
        id: 'p2',
        title: 'How to Build an AI Chatbot That Captures Leads (Safely)',
        category: 'How-to',
        readTime: '6 min',
        tags: ['Chatbots', 'Lead Gen', 'Privacy'],
        author: 'geminidigitalai',
        dateISO: new Date(Date.now() - 1000*60*60*24*6).toISOString(),
        excerpt: 'A lead-focused chatbot needs: clear intent, strong UX, guardrails, and a handoff to humans. Here’s the checklist.',
        content:
`## The lead-capture chatbot checklist
- Define user intents (pricing, booking, support)
- Keep responses short; offer next actions
- Capture details with consent (name, email, need)
- Handoff to a human for edge cases

## Safety guardrails
- Don’t request sensitive data
- Confirm before submitting a lead
- Add a "sources / limitations" message when needed

## Integration ideas
- Send qualified leads to CRM
- Trigger email sequences
- Notify sales/support in Slack

## Next step
Ask the assistant: "Write my chatbot’s first 10 conversation flows."`
      },
      {
        id: 'p3',
        title: 'AI SEO: How to Create Content That Actually Ranks',
        category: 'Guide',
        readTime: '8 min',
        tags: ['SEO', 'Content', 'Structure'],
        author: 'geminidigitalai',
        dateISO: new Date(Date.now() - 1000*60*60*24*2).toISOString(),
        excerpt: 'Ranking content is about intent, structure, and credibility. AI helps you produce faster—but you still need a strategy.',
        content:
`## What matters in AI-assisted SEO
- Search intent mapping (informational vs commercial)
- Clear structure (H2/H3, scannable sections)
- Unique insights (examples, data, checklists)
- Internal links (topic clusters)

## Recommended workflow
1) Build a content brief (keywords + intent)
2) Outline with AI, then add real examples
3) Add FAQs and schema where relevant
4) Optimize for readability and speed

## Next step
Ask the assistant: "Create a content cluster for my business."`
      }
    ];

    // ---------- Renderers ----------
    function serviceCardHTML(s){
      return `
        <div class="glass-soft rounded-3xl p-5 min-w-[280px] sm:min-w-[340px] border" style="border-color: var(--stroke); background: linear-gradient(135deg, ${s.accent}, color-mix(in srgb, var(--card2) 70%, transparent));">
          <div class="flex items-start justify-between gap-3">
            <div>
              <div class="text-xs text-[color:var(--muted)]">Service</div>
              <div class="mt-1 text-lg font-semibold">${escapeHtml(s.title)}</div>
            </div>
            <div class="h-10 w-10 rounded-2xl border grid place-items-center" style="border-color: var(--stroke); background: color-mix(in srgb, var(--card2) 70%, transparent);">
              <svg class="h-5 w-5" viewBox="0 0 24 24" fill="none" aria-hidden="true">
                <path d="M12 2l9 5v10l-9 5-9-5V7l9-5Z" stroke="currentColor" stroke-width="1.6" stroke-linejoin="round"/>
                <path d="M7.5 10.5 12 13l4.5-2.5" stroke="currentColor" stroke-width="1.6" stroke-linecap="round" stroke-linejoin="round"/>
              </svg>
            </div>
          </div>
          <p class="mt-3 text-sm text-[color:var(--muted)]">${escapeHtml(s.desc)}</p>
          <div class="mt-4 flex flex-wrap gap-2">
            ${s.bullets.map(b => `<span class="chip rounded-full px-3 py-1 text-xs text-[color:var(--muted)]">${escapeHtml(b)}</span>`).join('')}
          </div>
          <div class="mt-5 flex gap-2">
            <a class="btn btn-ghost focus-ring w-full" href="#contact" data-route="contact" data-prefill="${encodeURIComponent(s.title)}">Talk to us</a>
            <button class="btn btn-primary focus-ring px-4" type="button" data-ask="${encodeURIComponent('Tell me how ' + s.title + ' works and what I need to get started.')}">Ask</button>
          </div>
        </div>
      `;
    }

    function testimonialHTML(t){
      return `
        <div class="glass-soft rounded-3xl p-5 sm:p-6 min-w-[280px] sm:min-w-[360px] border" style="border-color: var(--stroke);">
          <div class="flex items-start gap-3">
            <div class="h-10 w-10 rounded-2xl border grid place-items-center" style="border-color: var(--stroke); background: linear-gradient(135deg, rgba(92,225,255,.10), rgba(167,139,250,.10));">
              <svg class="h-5 w-5" viewBox="0 0 24 24" fill="none" aria-hidden="true">
                <path d="M7.5 10.5c0-2.2 1.8-4 4-4h1V4.5c-4.1 0-7 2.7-7 6.6V18h6v-7.5h-4Z" stroke="currentColor" stroke-width="1.6" stroke-linejoin="round"/>
                <path d="M15.5 10.5c0-2.2 1.8-4 4-4h1V4.5c-4.1 0-7 2.7-7 6.6V18h6v-7.5h-4Z" stroke="currentColor" stroke-width="1.6" stroke-linejoin="round"/>
              </svg>
            </div>
            <div>
              <p class="text-sm sm:text-base text-[color:var(--text)] leading-relaxed">“${escapeHtml(t.quote)}”</p>
              <div class="mt-3 text-sm">
                <span class="font-semibold">${escapeHtml(t.name)}</span>
                <span class="text-[color:var(--muted)]"> — ${escapeHtml(t.role)}</span>
              </div>
            </div>
          </div>
        </div>
      `;
    }

    function toolCardHTML(t){
      return `
        <div class="glass-soft rounded-3xl p-5 border" style="border-color: var(--stroke);">
          <div class="flex items-start justify-between gap-3">
            <div>
              <div class="font-semibold text-lg">${escapeHtml(t.name)}</div>
              <div class="mt-1 text-sm text-[color:var(--muted)]">Use case: ${escapeHtml(t.use)}</div>
            </div>
            <div class="h-10 w-10 rounded-2xl border grid place-items-center" style="border-color: var(--stroke); background: linear-gradient(135deg, rgba(92,225,255,.10), rgba(251,113,133,.08));">
              <svg class="h-5 w-5" viewBox="0 0 24 24" fill="none" aria-hidden="true">
                <path d="M12 3l8 4v10l-8 4-8-4V7l8-4Z" stroke="currentColor" stroke-width="1.6" stroke-linejoin="round"/>
                <path d="M8 12h8" stroke="currentColor" stroke-width="1.6" stroke-linecap="round"/>
                <path d="M12 8v8" stroke="currentColor" stroke-width="1.6" stroke-linecap="round"/>
              </svg>
            </div>
          </div>
          <p class="mt-3 text-sm text-[color:var(--muted)]">${escapeHtml(t.how)}</p>
          <div class="mt-4 flex flex-wrap gap-2">
            ${t.tags.map(tag => `<span class="chip rounded-full px-3 py-1 text-xs text-[color:var(--muted)]">${escapeHtml(tag)}</span>`).join('')}
          </div>
          <div class="mt-5 flex flex-col sm:flex-row gap-2">
            <button class="btn btn-primary focus-ring w-full sm:w-auto" type="button" data-ask="${encodeURIComponent(`Give me a step-by-step workflow to use ${t.name} for ${t.use}.`)}">Get workflow</button>
            <button class="btn btn-ghost focus-ring w-full sm:w-auto" type="button" data-ask="${encodeURIComponent(`Write 5 prompt examples for ${t.name} related to: ${t.use}.`)}">Prompt examples</button>
          </div>
        </div>
      `;
    }

    function formatDate(iso){
      const d = new Date(iso);
      return d.toLocaleDateString(undefined, { year: 'numeric', month: 'short', day: 'numeric' });
    }

    function postCardHTML(p){
      const tags = (p.tags || []).slice(0,3);
      return `
        <article class="glass-soft rounded-3xl p-5 border" style="border-color: var(--stroke);">
          <div class="flex items-start justify-between gap-3">
            <div class="min-w-0">
              <div class="text-xs text-[color:var(--muted)]">${escapeHtml(p.category)} • ${escapeHtml(p.readTime)} • ${formatDate(p.dateISO)}</div>
              <h3 class="mt-2 text-lg sm:text-xl font-semibold tracking-tight">${escapeHtml(p.title)}</h3>
              <p class="mt-2 text-sm text-[color:var(--muted)]">${escapeHtml(p.excerpt)}</p>
              <div class="mt-3 flex flex-wrap gap-2">
                ${tags.map(t => `<span class="chip rounded-full px-3 py-1 text-xs text-[color:var(--muted)]">${escapeHtml(t)}</span>`).join('')}
              </div>
            </div>
            <div class="hidden sm:grid place-items-center h-12 w-12 rounded-2xl border" style="border-color: var(--stroke); background: linear-gradient(135deg, rgba(167,139,250,.10), rgba(92,225,255,.10));">
              <svg class="h-5 w-5" viewBox="0 0 24 24" fill="none" aria-hidden="true">
                <path d="M7 4h10a2 2 0 0 1 2 2v14l-7-3-7 3V6a2 2 0 0 1 2-2Z" stroke="currentColor" stroke-width="1.6" stroke-linejoin="round"/>
                <path d="M9 8h6M9 12h6" stroke="currentColor" stroke-width="1.6" stroke-linecap="round"/>
              </svg>
            </div>
          </div>
          <div class="mt-5 flex flex-col sm:flex-row gap-2">
            <button class="btn btn-primary focus-ring w-full sm:w-auto" type="button" data-open-post="${escapeHtml(p.id)}">Read</button>
            <button class="btn btn-ghost focus-ring w-full sm:w-auto" type="button" data-ask="${encodeURIComponent(`Summarize this topic and give me next steps: ${p.title}`)}">Ask assistant</button>
          </div>
        </article>
      `;
    }

    // ---------- Blog Store (localStorage) ----------
    const BLOG_KEY = 'gdai_blog_posts_v1';

    function loadPosts(){
      try{
        const raw = localStorage.getItem(BLOG_KEY);
        if(!raw) return null;
        const parsed = JSON.parse(raw);
        if(!Array.isArray(parsed)) return null;
        return parsed;
      }catch(_){ return null; }
    }
    function savePosts(posts){
      localStorage.setItem(BLOG_KEY, JSON.stringify(posts));
    }
    function ensureSeed(){
      const existing = loadPosts();
      if(existing && existing.length) return existing;
      savePosts(seedPosts);
      return seedPosts;
    }

    let posts = ensureSeed();

    // ---------- Home: Services carousel ----------
    const servicesCarousel = $('#servicesCarousel');
    let servicesIndex = 0;

    function renderServicesCarousel(){
      servicesCarousel.innerHTML = services.map(serviceCardHTML).join('');
      // For smooth carousel, set width via cards. We'll translate by card width + gap.
      servicesIndex = 0;
      updateServicesCarousel();
    }

    function updateServicesCarousel(){
      const cards = $$('#servicesCarousel > div');
      if(!cards.length) return;
      const card = cards[0];
      const styles = getComputedStyle(servicesCarousel);
      const gap = parseFloat(styles.columnGap || styles.gap || 12) || 12;
      const cardW = card.getBoundingClientRect().width;
      const maxIndex = Math.max(0, cards.length - Math.floor((servicesCarousel.parentElement.getBoundingClientRect().width + gap) / (cardW + gap)));
      servicesIndex = clamp(servicesIndex, 0, maxIndex);
      const x = (cardW + gap) * servicesIndex;
      servicesCarousel.style.transform = `translateX(${-x}px)`;
    }

    $('#servicesPrev').addEventListener('click', () => { servicesIndex--; updateServicesCarousel(); });
    $('#servicesNext').addEventListener('click', () => { servicesIndex++; updateServicesCarousel(); });
    window.addEventListener('resize', () => updateServicesCarousel());

    // ---------- Home: Testimonials slider ----------
    const testTrack = $('#testTrack');
    let testIndex = 0;
    function renderTestimonials(){
      testTrack.innerHTML = testimonials.map(testimonialHTML).join('');
      testIndex = 0;
      updateTestimonials();
    }
    function updateTestimonials(){
      const cards = $$('#testTrack > div');
      if(!cards.length) return;
      const card = cards[0];
      const styles = getComputedStyle(testTrack);
      const gap = parseFloat(styles.columnGap || styles.gap || 12) || 12;
      const cardW = card.getBoundingClientRect().width;
      const maxIndex = Math.max(0, cards.length - Math.floor((testTrack.parentElement.getBoundingClientRect().width + gap) / (cardW + gap)));
      testIndex = clamp(testIndex, 0, maxIndex);
      const x = (cardW + gap) * testIndex;
      testTrack.style.transform = `translateX(${-x}px)`;
    }
    $('#testPrev').addEventListener('click', () => { testIndex--; updateTestimonials(); });
    $('#testNext').addEventListener('click', () => { testIndex++; updateTestimonials(); });
    window.addEventListener('resize', () => updateTestimonials());

    // ---------- Services page grid ----------
    function renderServicesGrid(){
      $('#servicesGrid').innerHTML = services.map(s => `
        <div class="glass-soft rounded-3xl p-5 border relative overflow-hidden" style="border-color: var(--stroke);">
          <div class="absolute -right-14 -top-14 h-44 w-44 rounded-full opacity-30" aria-hidden="true" style="background: radial-gradient(circle at 30% 30%, ${s.accent}, transparent 60%);"></div>
          <div class="relative">
            <div class="flex items-start justify-between gap-3">
              <div>
                <div class="text-xs text-[color:var(--muted)]">AI Service</div>
                <h3 class="mt-1 text-lg font-semibold">${escapeHtml(s.title)}</h3>
              </div>
              <span class="chip rounded-full px-3 py-1 text-xs text-[color:var(--muted)]">Production-ready</span>
            </div>
            <p class="mt-3 text-sm text-[color:var(--muted)]">${escapeHtml(s.desc)}</p>
            <ul class="mt-4 grid gap-2 text-sm text-[color:var(--muted)]">
              ${s.bullets.map(b=>`<li class="flex gap-2"><span class="text-[color:var(--text)]">•</span>${escapeHtml(b)}</li>`).join('')}
            </ul>
            <div class="mt-5 flex flex-col sm:flex-row gap-2">
              <a class="btn btn-primary focus-ring w-full sm:w-auto" href="#contact" data-route="contact" data-prefill="${encodeURIComponent(s.title)}">Get started</a>
              <button class="btn btn-ghost focus-ring w-full sm:w-auto" type="button" data-ask="${encodeURIComponent(`What deliverables are included in ${s.title}? Provide a simple scope and timeline.`)}">Ask assistant</button>
            </div>
          </div>
        </div>
      `).join('');
    }

    // ---------- Tools page ----------
    let activeToolTab = 'writing';
    const toolsGrid = $('#toolsGrid');

    function setToolTab(tab){
      activeToolTab = tab;
      $$('button[data-tool-tab]').forEach(b => {
        const on = b.dataset.toolTab === tab;
        b.setAttribute('aria-selected', on ? 'true' : 'false');
        b.classList.toggle('btn-primary', on);
        b.classList.toggle('btn-ghost', !on);
      });
      renderTools();
    }

    function renderTools(){
      const list = toolsByTab[activeToolTab] || [];
      toolsGrid.innerHTML = list.map(toolCardHTML).join('');
    }

    document.addEventListener('click', (e) => {
      const btn = e.target.closest('button[data-tool-tab]');
      if(!btn) return;
      setToolTab(btn.dataset.toolTab);
    });

    // Prompt kit
    const promptBox = $('#promptBox');
    const promptShortText =
`ROLE: You are an expert assistant.
GOAL: [what you want]
CONTEXT: [audience + constraints]
OUTPUT: [format + length]
CHECK: list assumptions + next steps.`;

    const promptFullText =
`ROLE
You are an expert AI assistant for geminidigitalai. Be clear, practical, and concise.

GOAL
Help me achieve: [describe outcome]

CONTEXT
- Audience: [who it's for]
- Industry/niche: [optional]
- Constraints: [budget/timeline/tools/legal]
- Tone: professional but friendly

INPUTS (optional)
- Existing assets/links: [...]
- Examples I like: [...]
- Offer/product details: [...]

TASK
1) Ask any missing questions (max 5).
2) Produce the deliverable in a structured format.
3) Provide a "Next Steps" checklist.
4) Include a simple measurement plan (KPIs).

OUTPUT FORMAT
- Summary
- Step-by-step plan
- Draft/content/template
- Risks & guardrails
- Next steps + KPIs`;

    function setPrompt(mode){
      promptBox.textContent = mode === 'full' ? promptFullText : promptShortText;
    }

    $('#promptShort').addEventListener('click', () => setPrompt('short'));
    $('#promptFull').addEventListener('click', () => setPrompt('full'));

    function copyToClipboard(text){
      return navigator.clipboard?.writeText(text).catch(() => {
        const ta = document.createElement('textarea');
        ta.value = text;
        document.body.appendChild(ta);
        ta.select();
        document.execCommand('copy');
        ta.remove();
      });
    }

    $('#copyPromptBtn').addEventListener('click', async () => {
      await copyToClipboard(promptBox.textContent);
      toast('Prompt copied to clipboard.');
    });

    $('#toolsCopyPrompt').addEventListener('click', async () => {
      await copyToClipboard(promptFullText);
      toast('Full prompt template copied.');
    });

    // ---------- Blog ----------
    const blogList = $('#blogList');
    const blogSearch = $('#blogSearch');

    function computeTopics(allPosts){
      const counts = new Map();
      allPosts.forEach(p => (p.tags || []).forEach(t => counts.set(t, (counts.get(t) || 0) + 1)));
      return Array.from(counts.entries()).sort((a,b)=>b[1]-a[1]).slice(0, 12).map(([tag, count]) => ({ tag, count }));
    }

    function renderTopics(){
      const topics = computeTopics(posts);
      const wrap = $('#topicChips');
      wrap.innerHTML = topics.map(t => `
        <button class="chip rounded-full px-3 py-1 text-xs focus-ring" type="button" data-topic="${escapeHtml(t.tag)}">
          ${escapeHtml(t.tag)} <span class="opacity-70">(${t.count})</span>
        </button>
      `).join('') || `<span class="text-sm text-[color:var(--muted)]">No topics yet.</span>`;
    }

    function renderBlogList(filter=''){
      const q = (filter || '').trim().toLowerCase();
      let list = [...posts].sort((a,b)=> new Date(b.dateISO) - new Date(a.dateISO));
      if(q){
        list = list.filter(p => {
          const hay = [
            p.title, p.category, p.excerpt, p.author,
            ...(p.tags || []), p.content
          ].join(' ').toLowerCase();
          return hay.includes(q);
        });
      }

      if(!list.length){
        blogList.innerHTML = `
          <div class="glass-soft rounded-3xl p-6 border" style="border-color: var(--stroke);">
            <div class="font-semibold">No articles found</div>
            <p class="mt-2 text-sm text-[color:var(--muted)]">Try a different search term, or open the mini CMS to add a post.</p>
            <div class="mt-4 flex flex-col sm:flex-row gap-2">
              <button class="btn btn-primary focus-ring w-full sm:w-auto" type="button" id="openCmsInline">Open Mini CMS</button>
              <button class="btn btn-ghost focus-ring w-full sm:w-auto" type="button" id="clearSearch">Clear search</button>
            </div>
          </div>
        `;
        $('#openCmsInline')?.addEventListener('click', openCMS);
        $('#clearSearch')?.addEventListener('click', () => { blogSearch.value=''; renderBlogList(''); });
        return;
      }

      blogList.innerHTML = list.map(postCardHTML).join('');
    }

    $('#blogSearchBtn').addEventListener('click', () => renderBlogList(blogSearch.value));
    blogSearch.addEventListener('keydown', (e) => { if(e.key === 'Enter'){ e.preventDefault(); renderBlogList(blogSearch.value); } });

    document.addEventListener('click', (e) => {
      const t = e.target.closest('button[data-topic]');
      if(!t) return;
      blogSearch.value = t.dataset.topic;
      renderBlogList(t.dataset.topic);
    });

    // Post reader modal
    const postModal = $('#postModal');
    const postClose = $('#postClose');
    const postTitle = $('#postTitle');
    const postMeta = $('#postMeta');
    const postTags = $('#postTags');
    const postContent = $('#postContent');
    let openPostId = null;

    function openPost(id){
      const p = posts.find(x => x.id === id);
      if(!p) return;
      openPostId = id;
      postTitle.textContent = p.title;
      postMeta.textContent = `${p.category} • ${p.readTime} • ${formatDate(p.dateISO)} • by ${p.author}`;
      postTags.innerHTML = (p.tags||[]).map(t => `<span class="chip rounded-full px-3 py-1 text-xs text-[color:var(--muted)]">${escapeHtml(t)}</span>`).join('');
      postContent.textContent = p.content || '';
      postModal.classList.remove('hidden');
      postModal.setAttribute('aria-hidden', 'false');
      document.body.style.overflow = 'hidden';
    }

    function closePost(){
      postModal.classList.add('hidden');
      postModal.setAttribute('aria-hidden', 'true');
      document.body.style.overflow = '';
      openPostId = null;
    }

    postClose.addEventListener('click', closePost);
    postModal.addEventListener('click', (e) => { if(e.target === postModal.firstElementChild) closePost(); });
    window.addEventListener('keydown', (e) => { if(e.key === 'Escape'){ if(!postModal.classList.contains('hidden')) closePost(); if($('#cmsModal') && !$('#cmsModal').classList.contains('hidden')) closeCMS(); if($('#chatPanel').classList.contains('open')) closeChat(); } });

    document.addEventListener('click', (e) => {
      const btn = e.target.closest('button[data-open-post]');
      if(!btn) return;
      openPost(btn.getAttribute('data-open-post'));
    });

    $('#postAskAssistant').addEventListener('click', () => {
      const p = posts.find(x => x.id === openPostId);
      if(!p) return;
      openChat();
      enqueueUserMessage(`Help me understand and apply this article: "${p.title}". Give me a checklist and a 7-day plan.`);
      closePost();
    });

    $('#postCopyLink').addEventListener('click', async () => {
      const url = `${location.origin}${location.pathname}#blog`;
      await copyToClipboard(url);
      toast('Blog link copied.');
    });

    // ---------- CMS ----------
    const cmsModal = $('#cmsModal');
    const cmsForm = $('#cmsForm');
    const cmsList = $('#cmsList');

    function openCMS(){
      cmsModal.classList.remove('hidden');
      cmsModal.setAttribute('aria-hidden','false');
      document.body.style.overflow = 'hidden';
      renderCMSList();
    }
    function closeCMS(){
      cmsModal.classList.add('hidden');
      cmsModal.setAttribute('aria-hidden','true');
      document.body.style.overflow = '';
    }
    $('#openCmsBtn').addEventListener('click', openCMS);
    $('#cmsClose').addEventListener('click', closeCMS);
    cmsModal.addEventListener('click', (e)=>{ if(e.target === cmsModal.firstElementChild) closeCMS(); });

    function setCmsForm(p){
      cmsForm.id.value = p?.id || '';
      cmsForm.title.value = p?.title || '';
      cmsForm.category.value = p?.category || '';
      cmsForm.readTime.value = p?.readTime || '6 min';
      cmsForm.tags.value = (p?.tags || []).join(', ');
      cmsForm.author.value = p?.author || 'geminidigitalai';
      cmsForm.excerpt.value = p?.excerpt || '';
      cmsForm.content.value = p?.content || '';
    }

    function renderCMSList(){
      const sorted = [...posts].sort((a,b)=> new Date(b.dateISO) - new Date(a.dateISO));
      cmsList.innerHTML = sorted.map(p => `
        <div class="rounded-3xl border p-4" style="border-color: var(--stroke); background: color-mix(in srgb, var(--card2) 70%, transparent);">
          <div class="flex items-start justify-between gap-3">
            <div class="min-w-0">
              <div class="text-xs text-[color:var(--muted)]">${escapeHtml(p.category)} • ${escapeHtml(p.readTime)} • ${formatDate(p.dateISO)}</div>
              <div class="mt-1 font-semibold truncate">${escapeHtml(p.title)}</div>
              <div class="mt-2 flex flex-wrap gap-2">
                ${(p.tags||[]).slice(0,4).map(t => `<span class="chip rounded-full px-3 py-1 text-xs text-[color:var(--muted)]">${escapeHtml(t)}</span>`).join('')}
              </div>
            </div>
            <div class="flex flex-col gap-2">
              <button class="btn btn-ghost focus-ring h-10 px-3" type="button" data-cms-edit="${escapeHtml(p.id)}">Edit</button>
              <button class="btn btn-ghost focus-ring h-10 px-3" type="button" data-cms-del="${escapeHtml(p.id)}">Delete</button>
            </div>
          </div>
        </div>
      `).join('') || `<div class="text-sm text-[color:var(--muted)]">No posts yet.</div>`;
    }

    cmsForm.addEventListener('submit', (e) => {
      e.preventDefault();
      const data = Object.fromEntries(new FormData(cmsForm).entries());
      const nowISO = new Date().toISOString();
      const p = {
        id: data.id || uid(),
        title: (data.title || '').trim(),
        category: (data.category || '').trim(),
        readTime: (data.readTime || '').trim(),
        tags: (data.tags || '').split(',').map(x=>x.trim()).filter(Boolean),
        author: (data.author || '').trim(),
        excerpt: (data.excerpt || '').trim(),
        content: (data.content || '').trim(),
        dateISO: data.id ? (posts.find(x=>x.id===data.id)?.dateISO || nowISO) : nowISO
      };

      const idx = posts.findIndex(x=>x.id===p.id);
      if(idx >= 0) posts[idx] = p;
      else posts.unshift(p);

      savePosts(posts);
      renderBlogList(blogSearch.value);
      renderTopics();
      renderCMSList();
      setCmsForm(null);
      toast('Post saved.');
    });

    $('#cmsReset').addEventListener('click', () => setCmsForm(null));
    $('#cmsSeed').addEventListener('click', () => {
      posts = [...seedPosts];
      savePosts(posts);
      renderBlogList(blogSearch.value);
      renderTopics();
      renderCMSList();
      setCmsForm(null);
      toast('Demo posts restored.');
    });

    $('#cmsExport').addEventListener('click', async () => {
      await copyToClipboard(JSON.stringify(posts, null, 2));
      toast('Posts JSON copied to clipboard.');
    });

    document.addEventListener('click', (e) => {
      const edit = e.target.closest('button[data-cms-edit]');
      const del = e.target.closest('button[data-cms-del]');
      if(edit){
        const id = edit.getAttribute('data-cms-edit');
        const p = posts.find(x=>x.id===id);
        if(p) setCmsForm(p);
      }
      if(del){
        const id = del.getAttribute('data-cms-del');
        const p = posts.find(x=>x.id===id);
        if(!p) return;
        if(confirm(`Delete "${p.title}"?`)){
          posts = posts.filter(x=>x.id!==id);
          savePosts(posts);
          renderBlogList(blogSearch.value);
          renderTopics();
          renderCMSList();
          toast('Post deleted.');
        }
      }
    });

    // ---------- Newsletter / Contact (demo integration) ----------
    function showInlineToast(el, msg){
      el.textContent = msg;
      el.classList.remove('hidden');
      setTimeout(() => el.classList.add('hidden'), 4200);
    }

    $('#newsletterDemoFill').addEventListener('click', () => {
      $('#newsletterForm input[name="email"]').value = 'demo@geminidigitalai.com';
    });

    $('#newsletterForm').addEventListener('submit', (e) => {
      e.preventDefault();
      const email = $('#newsletterForm input[name="email"]').value.trim();
      const toastEl = $('#newsletterToast');
      if(!email || !email.includes('@')){
        showInlineToast(toastEl, 'Please enter a valid email address.');
        return;
      }
      // Demo "integration"
      const list = JSON.parse(localStorage.getItem('gdai_newsletter') || '[]');
      if(!list.includes(email)) list.push(email);
      localStorage.setItem('gdai_newsletter', JSON.stringify(list));
      showInlineToast(toastEl, `Subscribed: ${email} (demo saved locally).`);
      $('#newsletterForm').reset();
    });

    $('#contactDemoFill').addEventListener('click', () => {
      $('#contactForm [name="name"]').value = 'Jordan Lee';
      $('#contactForm [name="email"]').value = 'jordan@company.com';
      $('#contactForm [name="need"]').value = 'AI Automation Solutions';
      $('#contactForm [name="message"]').value = 'Hi geminidigitalai — I want to automate lead routing, onboarding, and reporting. We use Google Sheets + Slack + a CRM. Timeline: 2–4 weeks.';
    });

    $('#contactForm').addEventListener('submit', (e) => {
      e.preventDefault();
      const form = $('#contactForm');
      const name = form.name.value.trim();
      const email = form.email.value.trim();
      const need = form.need.value.trim();
      const message = form.message.value.trim();
      const toastEl = $('#contactToast');

      const errors = [];
      if(!name) errors.push('Name is required.');
      if(!email || !email.includes('@')) errors.push('Valid email is required.');
      if(!need) errors.push('Please select a topic.');
      if(!message || message.length < 20) errors.push('Please add a bit more detail (20+ chars).');

      if(errors.length){
        showInlineToast(toastEl, errors.join(' '));
        return;
      }

      // Demo: store lead locally
      const leads = JSON.parse(localStorage.getItem('gdai_leads') || '[]');
      leads.push({ id: uid(), name, email, need, message, createdAt: new Date().toISOString() });
      localStorage.setItem('gdai_leads', JSON.stringify(leads));

      showInlineToast(toastEl, 'Message sent (demo saved locally). In production, connect this form to your backend or form provider.');
      form.reset();
    });

    // Prefill contact "need"
    document.addEventListener('click', (e) => {
      const a = e.target.closest('a[data-prefill]');
      if(!a) return;
      const v = decodeURIComponent(a.dataset.prefill || '');
      // Delay until route switches
      setTimeout(() => {
        const sel = $('#contactForm [name="need"]');
        if(sel){
          sel.value = v;
        }
      }, 250);
    });

    // ---------- Estimator ----------
    $('#serviceEstimatorBtn').addEventListener('click', () => {
      const el = $('#estimatorForm');
      el?.scrollIntoView({ behavior: 'smooth', block: 'start' });
      el?.querySelector('select')?.focus();
    });

    $('#estimatorForm').addEventListener('submit', (e) => {
      e.preventDefault();
      const form = e.currentTarget;
      const goal = form.goal.value;
      const size = form.size.value;
      const speed = form.speed.value;
      const integrations = Array.from(form.querySelectorAll('input[name="integrations"]:checked')).map(x=>x.value);

      const base = {
        leadgen: 1800, content: 1200, automation: 2400, chatbot: 2200, full: 4200
      }[goal] || 1800;

      const sizeMult = { solo: 1.0, smb: 1.25, mid: 1.7, ent: 2.4 }[size] || 1.0;
      const speedMult = speed === 'fast' ? 1.25 : 1.0;
      const integAdd = integrations.length * 350;

      const est = Math.round((base * sizeMult * speedMult) + integAdd);
      const rangeLow = Math.round(est * 0.85);
      const rangeHigh = Math.round(est * 1.25);

      const out = $('#estimateOutput');
      out.classList.remove('hidden');
      out.innerHTML = `
        <div class="font-semibold">Estimated range: $${rangeLow.toLocaleString()} — $${rangeHigh.toLocaleString()}</div>
        <div class="mt-2 text-[color:var(--muted)] text-sm">Includes: discovery, implementation, and QA. Excludes: paid media spend, premium tool subscriptions, and enterprise compliance add-ons.</div>
        <div class="mt-3 flex flex-col sm:flex-row gap-2">
          <button class="btn btn-primary focus-ring w-full sm:w-auto" type="button" id="estimateAsk">Ask assistant for a plan</button>
          <button class="btn btn-ghost focus-ring w-full sm:w-auto" type="button" id="estimateCopy">Copy estimate</button>
        </div>
      `;

      $('#estimateAsk').addEventListener('click', () => {
        openChat();
        enqueueUserMessage(`My goal is "${goal}", business size "${size}", speed "${speed}", integrations "${integrations.join(', ') || 'none'}". Propose a simple scope, timeline, and deliverables. Budget range: $${rangeLow}–$${rangeHigh}.`);
      });

      $('#estimateCopy').addEventListener('click', async () => {
        await copyToClipboard(`Estimate (demo): $${rangeLow}–$${rangeHigh} | goal=${goal} size=${size} speed=${speed} integrations=${integrations.join(',') || 'none'}`);
        toast('Estimate copied.');
      });
    });

    // ---------- Global toast (lightweight) ----------
    let toastTimer = null;
    function toast(message){
      let el = $('#globalToast');
      if(!el){
        el = document.createElement('div');
        el.id = 'globalToast';
        el.className = 'fixed left-1/2 -translate-x-1/2 bottom-24 z-[90] hidden';
        el.innerHTML = `<div class="glass rounded-2xl px-4 py-3 text-sm border" style="border-color: var(--stroke);"></div>`;
        document.body.appendChild(el);
      }
      el.firstElementChild.textContent = message;
      el.classList.remove('hidden');
      clearTimeout(toastTimer);
      toastTimer = setTimeout(() => el.classList.add('hidden'), 2500);
    }

    // ---------- Chatbot (demo assistant) ----------
    const chatPanel = $('#chatPanel');
    const chatToggle = $('#chatToggle');
    const chatClose = $('#chatClose');
    const chatMessages = $('#chatMessages');
    const chatForm = $('#chatForm');
    const chatInput = $('#chatInput');

    function openChat(){
      chatPanel.classList.add('open');
      chatToggle.setAttribute('aria-expanded','true');
      setTimeout(() => chatInput.focus(), 100);
      if(!chatMessages.dataset.seeded){
        seedChat();
        chatMessages.dataset.seeded = '1';
      }
    }
    function closeChat(){
      chatPanel.classList.remove('open');
      chatToggle.setAttribute('aria-expanded','false');
    }
    chatToggle.addEventListener('click', () => {
      chatPanel.classList.contains('open') ? closeChat() : openChat();
    });
    chatClose.addEventListener('click', closeChat);

    function bubble(role, text){
      const wrap = document.createElement('div');
      wrap.className = `flex ${role === 'user' ? 'justify-end' : 'justify-start'}`;
      const b = document.createElement('div');
      b.className = `chat-bubble ${role !== 'user' ? 'ai' : ''} rounded-3xl px-4 py-3 max-w-[88%]`;
      b.innerHTML = `<div class="text-xs mb-1 ${role === 'user' ? 'opacity-70' : 'opacity-80'}">${role === 'user' ? 'You' : 'AI Assistant'}</div><div class="text-sm leading-relaxed whitespace-pre-wrap">${escapeHtml(text)}</div>`;
      wrap.appendChild(b);
      return wrap;
    }

    function scrollChatBottom(){
      chatMessages.scrollTop = chatMessages.scrollHeight;
    }

    function seedChat(){
      chatMessages.innerHTML = '';
      chatMessages.appendChild(bubble('ai', `Hi — I’m the geminidigitalai assistant.\nWhat are you trying to achieve: more leads, better content, automation, a chatbot, or a full AI growth system?`));
      scrollChatBottom();
    }

    function aiRespond(userText){
      const t = userText.toLowerCase();

      const recommendations = [];
      if(/lead|leads|sales|funnel|conversion/.test(t)){
        recommendations.push(
`For lead generation, here’s a simple AI-first plan:
1) Clarify offer + ideal customer (ICP)
2) Build a fast landing page with a single CTA
3) Add an AI chatbot for qualification + booking
4) Create 10–20 ad/email/message variations
5) Track: conversion rate, CPL, booked calls

If you share your niche and offer, I can draft your landing structure and a chatbot flow.`
        );
      }
      if(/content|blog|seo|copy|email|newsletter/.test(t)){
        recommendations.push(
`For content scaling:
- Start with a content brief (keywords + intent + outline)
- Generate a draft with a consistent brand voice
- Add unique examples, FAQs, and internal links
- Ship weekly and iterate via Search Console + analytics

Tell me your industry and primary audience. I’ll propose a content cluster + 10 article ideas.`
        );
      }
      if(/automate|automation|workflow|zapier|make|crm|onboarding|ops/.test(t)){
        recommendations.push(
`For automation:
1) Map your workflow (trigger → steps → owner → tools)
2) Standardize inputs (forms, fields, naming)
3) Integrate CRM + email + notifications
4) Add monitoring + fallbacks

Which tools are you using today (CRM, email, spreadsheets, Slack)?`
        );
      }
      if(/chatbot|support|faq|whatsapp|live chat/.test(t)){
        recommendations.push(
`For a chatbot:
- Define top 5 intents (pricing, booking, product, support, demo)
- Use short answers + quick buttons
- Capture leads with consent (name, email, need)
- Add a human handoff path

Want me to write your first 10 conversation flows?`
        );
      }
      if(/learn|learning|course|tutorial|plan|roadmap/.test(t)){
        recommendations.push(
`Learning path (7 days):
Day 1: AI basics + prompting structure
Day 2: AI for research + positioning
Day 3: AI for copy (landing + ads)
Day 4: AI for SEO briefs + clusters
Day 5: Automations (forms → CRM → email)
Day 6: Chatbots + guardrails
Day 7: Measurement + iteration loop

Tell me your role (marketer, founder, freelancer, learner) and your goal.`
        );
      }

      if(!recommendations.length){
        return `I can help with:
- AI services (websites, content, marketing, automation, chatbots, consulting)
- Tool recommendations and workflows
- Learning plans and templates

What’s your role and your goal for the next 30 days?`;
      }

      // Combine up to 2 responses
      return recommendations.slice(0,2).join('\n\n');
    }

    function enqueueUserMessage(text){
      chatMessages.appendChild(bubble('user', text));
      scrollChatBottom();

      const typing = document.createElement('div');
      typing.className = 'flex justify-start';
      typing.innerHTML = `
        <div class="chat-bubble ai rounded-3xl px-4 py-3 max-w-[88%]">
          <div class="text-xs mb-1 opacity-80">AI Assistant</div>
          <div class="text-sm text-[color:var(--muted)]">Thinking…</div>
        </div>
      `;
      chatMessages.appendChild(typing);
      scrollChatBottom();

      setTimeout(() => {
        typing.remove();
        chatMessages.appendChild(bubble('ai', aiRespond(text)));
        scrollChatBottom();
      }, 520);
    }

    chatForm.addEventListener('submit', (e) => {
      e.preventDefault();
      const v = chatInput.value.trim();
      if(!v) return;
      chatInput.value = '';
      enqueueUserMessage(v);
    });

    document.addEventListener('click', (e) => {
      const q = e.target.closest('button[data-quick]');
      if(!q) return;
      openChat();
      enqueueUserMessage(q.dataset.quick);
    });

    // Buttons to open chat from pages
    $('#openChatFromHome').addEventListener('click', openChat);
    $('#openChatFromTools').addEventListener('click', openChat);
    $('#openChatFromBlog').addEventListener('click', openChat);
    $('#openChatFromContact').addEventListener('click', openChat);
    $('#openChatFromCard').addEventListener('click', openChat);

    // Buttons with "Ask" prompt from cards
    document.addEventListener('click', (e) => {
      const ask = e.target.closest('button[data-ask]');
      if(!ask) return;
      openChat();
      enqueueUserMessage(decodeURIComponent(ask.dataset.ask || ''));
    });

    // ---------- Init + small UX ----------
    document.getElementById('year').textContent = new Date().getFullYear();

    // Initial renders
    renderServicesCarousel();
    renderTestimonials();
    renderServicesGrid();
    setToolTab('writing');
    setPrompt('full');
    renderBlogList('');
    renderTopics();

    // Ensure route on load
    routeFromHash();

    // Improve hash links by default
    if(!location.hash) history.replaceState(null, '', '#home');

    // Close chat when clicking outside (optional)
    document.addEventListener('click', (e) => {
      const isOpen = chatPanel.classList.contains('open');
      if(!isOpen) return;
      const clickedInside = e.target.closest('#chatPanel') || e.target.closest('#chatToggle');
      if(!clickedInside) closeChat();
    }, { capture: true });

    // Ask assistant from tool "Copy prompt template" already handled.

    // Contact prefill from hash query-like
    document.addEventListener('click', (e) => {
      const a = e.target.closest('a[href="#contact"][data-route="contact"]');
      if(!a) return;
      // After navigation, focus the form
      setTimeout(() => $('#contactForm [name="name"]')?.focus(), 350);
    });
  </script>
</body>
</html>Hey GPT, use this code and only try to separate the background. Can you do that?
