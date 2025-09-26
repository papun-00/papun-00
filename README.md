<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Nihar Ranjan Mohapatra — DevOps & Infrastructure</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css">
  <meta name="description" content="Portfolio of Nihar Ranjan Mohapatra — Infrastructure & DevOps engineer. Kubernetes, Istio, Docker, GitHub Actions, Observability." />
  <style>
    .badge { display:inline-flex; align-items:center; gap:.5rem; padding:.35rem .6rem; border-radius:999px; background:#eef2ff; color:#312e81; font-weight:600; transition: all 0.3s; }
    .badge:hover { transform: scale(1.05); }
    .glass { background: rgba(255,255,255,0.06); backdrop-filter: blur(6px); }
  </style>
</head>
<body class="bg-gradient-to-b from-slate-900 to-slate-800 text-slate-100 leading-relaxed">
  <div class="min-h-screen max-w-6xl mx-auto px-4 sm:px-6 lg:px-8 py-6">

    <!-- Header -->
    <header class="flex flex-col sm:flex-row items-center justify-between py-4 sm:py-6">
      <div class="flex items-center gap-4 mb-3 sm:mb-0">
        <img src="https://uploads.onecompiler.io/43wm8t7fw/43xvn2pfn/WhatsApp%20Image%202025-09-26%20at%2022.43.31.jpeg" 
             alt="Nihar Photo" class="w-12 h-12 sm:w-14 sm:h-14 rounded-full object-cover border-2 border-indigo-500" />
        <div>
          <h1 class="text-xl sm:text-2xl font-extrabold">Nihar Ranjan Mohapatra</h1>
          <p class="text-xs sm:text-sm text-slate-300">Infrastructure & DevOps — 4 years • Kubernetes • CI/CD • Observability</p>
        </div>
      </div>
      <nav class="flex flex-wrap gap-2 sm:gap-3">
        <a class="text-sm py-2 px-4 rounded-lg hover:bg-white/5" href="#projects">Projects</a>
        <a class="text-sm py-2 px-4 rounded-lg hover:bg-white/5" href="#tech">Tech</a>
        <a class="text-sm py-2 px-4 rounded-lg bg-indigo-600 hover:brightness-95" href="#contact">Contact</a>
      </nav>
    </header>

    <!-- Hero -->
    <section class="grid grid-cols-1 md:grid-cols-2 gap-6 md:gap-8 items-start md:items-center py-8">
      <div>
        <h2 class="text-3xl sm:text-4xl lg:text-5xl font-extrabold leading-tight">Hello 👋 I'm <span class="text-indigo-400">Nihar</span></h2>
        <p class="mt-4 text-slate-300 text-sm sm:text-base">An infrastructure enthusiast with 4 years building highly available microservice systems, secure cluster networking, and automated self-service CI/CD platforms. I love solving real-world problems with automation and reliable design.</p>

        <div class="mt-5 flex flex-wrap gap-3">
          <a class="badge" href="https://github.com/papun-00/papun-00" target="_blank"><i class="fa-brands fa-github"></i> GitHub</a>
          <a class="badge" href="https://www.linkedin.com/in/nihar-ranjan-mohapatra-4942a4345" target="_blank"><i class="fa-brands fa-linkedin"></i> LinkedIn</a>
          <a class="badge" href="mailto:nmohapatra079@gmail.com"><i class="fa-solid fa-envelope"></i> Mail</a>
        </div>

        <div class="mt-6 flex flex-wrap gap-3">
          <a href="#projects" class="inline-block rounded-md px-5 py-3 bg-indigo-600 text-white font-semibold shadow">See my work</a>
          <a href="#contact" class="inline-block rounded-md px-5 py-3 border border-indigo-600 text-indigo-200">Hire / Collaborate</a>
        </div>
      </div>

      <div class="glass rounded-2xl p-6 shadow-xl mt-6 md:mt-0">
        <h3 class="font-semibold text-lg">Quick stats</h3>
        <ul class="mt-4 space-y-2 text-slate-200 text-sm sm:text-base">
          <li>🛠️ 4 years building infra & CI/CD</li>
          <li>☁️ Kubernetes, Istio, Docker, Meshery</li>
          <li>🔁 GitHub Actions, Ansible, Terraform (examples in projects)</li>
          <li>📈 Observability: Prometheus, Grafana</li>
        </ul>
        <div class="mt-4 grid grid-cols-1 sm:grid-cols-2 gap-3">
          <img src="https://github-readme-stats.vercel.app/api?username=papun-00&show_icons=true&theme=blueberry&count_private=true" alt="GitHub stats" class="rounded w-full" />
          <img src="https://github-readme-streak-stats.herokuapp.com/?user=papun-00&theme=blueberry&hide_border=true" alt="Streak" class="rounded w-full" />
        </div>
      </div>
    </section>

    <!-- Tech stack -->
    <section id="tech" class="mt-10">
      <h3 class="text-2xl font-bold">Tech Stack</h3>
      <p class="text-slate-300 mt-2 text-sm sm:text-base">Tools I use regularly for designing resilient platforms and developer workflows.</p>

      <div class="mt-4 grid grid-cols-1 sm:grid-cols-2 md:grid-cols-4 gap-3">
        <div class="p-4 rounded-lg glass flex flex-col items-start">
          <img src="https://img.shields.io/badge/-Kubernetes-pale?style=flat-square&logo=kubernetes" alt="k8s" />
          <img class="mt-2" src="https://img.shields.io/badge/-Istio-yellow?style=flat-square&logo=istio" alt="istio" />
        </div>
        <div class="p-4 rounded-lg glass flex flex-col items-start">
          <img src="https://img.shields.io/badge/-Go-cyan?style=flat-square&logo=go" alt="go" />
          <img class="mt-2" src="https://img.shields.io/badge/-Docker-grey?style=flat-square&logo=docker" alt="docker" />
        </div>
        <div class="p-4 rounded-lg glass flex flex-col items-start">
          <img src="https://img.shields.io/badge/-Git-blueviolet?style=flat-square&logo=git" alt="git" />
          <img class="mt-2" src="https://img.shields.io/badge/-GitHub-181717?style=flat-square&logo=github" alt="github" />
        </div>
        <div class="p-4 rounded-lg glass flex flex-col items-start">
          <img src="https://img.shields.io/badge/-Prometheus-blueviolet?style=flat-square&logo=prometheus" alt="prom" />
          <img class="mt-2" src="https://img.shields.io/badge/-Grafana-green?style=flat-square&logo=grafana" alt="grafana" />
        </div>
      </div>
    </section>

    <!-- Skills -->
    <section id="skills" class="mt-10">
      <h3 class="text-2xl font-bold">Skills</h3>
      <p class="text-slate-300 mt-2 text-sm sm:text-base">Key abilities I bring to frontend development and web design.</p>

      <div class="mt-4 flex flex-wrap gap-3">
        <span class="badge" style="background:#f06529; color:white;">HTML5</span>
        <span class="badge" style="background:#2965f1; color:white;">CSS3</span>
        <span class="badge" style="background:#38bdf8; color:#000;">Frontend Web Design</span>
        <span class="badge" style="background:#a78bfa; color:white;">Responsive Layouts</span>
        <span class="badge" style="background:#f472b6; color:white;">Creative UI/UX Design</span>
      </div>
    </section>

    <!-- Projects -->
    <section id="projects" class="mt-10">
      <h3 class="text-2xl font-bold">Selected Projects</h3>
      <p class="text-slate-300 mt-2 text-sm sm:text-base">Short summaries and links to code or demos.</p>

      <div class="mt-6 grid grid-cols-1 sm:grid-cols-2 md:grid-cols-3 gap-4">
        <article class="p-5 rounded-xl glass">
          <h4 class="font-semibold">Self-Service CI/CD Platform</h4>
          <p class="text-sm sm:text-base text-slate-300 mt-2">Design and delivery of a multi-team self-service pipeline using GitHub Actions, templated workflows, and policy checks.</p>
          <div class="mt-3 flex flex-wrap items-center gap-2 text-xs sm:text-sm">
            <span class="badge">GitHub Actions</span>
            <span class="badge">Terraform</span>
          </div>
          <div class="mt-4">
            <a class="text-indigo-300 underline" href="#">View repo</a>
          </div>
        </article>
        <article class="p-5 rounded-xl glass">
          <h4 class="font-semibold">Cluster Mesh & Istio</h4>
          <p class="text-sm sm:text-base text-slate-300 mt-2">Setup of Istio across multi-cluster environments and traffic management + service mesh observability with Meshery.</p>
          <div class="mt-3 flex flex-wrap items-center gap-2 text-xs sm:text-sm">
            <span class="badge">Istio</span>
            <span class="badge">Meshery</span>
          </div>
          <div class="mt-4">
            <a class="text-indigo-300 underline" href="#">Read writeup</a>
          </div>
        </article>
        <article class="p-5 rounded-xl glass">
          <h4 class="font-semibold">Observability Platform</h4>
          <p class="text-sm sm:text-base text-slate-300 mt-2">Consolidated telemetry with Prometheus, Grafana dashboards, alerting rules and runbooks for incident response.</p>
          <div class="mt-3 flex flex-wrap items-center gap-2 text-xs sm:text-sm">
            <span class="badge">Prometheus</span>
            <span class="badge">Grafana</span>
          </div>
          <div class="mt-4">
            <a class="text-indigo-300 underline" href="#">See dashboards</a>
          </div>
        </article>
      </div>
    </section>

    <!-- Contact -->
    <section id="contact" class="mt-10 mb-12 grid grid-cols-1 md:grid-cols-2 gap-6">
      <div class="glass rounded-lg p-6">
        <h3 class="text-xl font-semibold">Let's collaborate</h3>
        <p class="text-slate-300 mt-2 text-sm sm:text-base">Prefer email? <a class="underline text-indigo-300" href="mailto:nmohapatra079@gmail.com">nmohapatra079@gmail.com</a>.</p>
        <div class="mt-5 flex flex-col gap-3">
          <a href="https://twitter.com/@niharranjan00" class="inline-flex items-center gap-3 badge" target="_blank"><i class="fa-brands fa-twitter"></i> @niharranjan00</a>
          <a href="https://www.linkedin.com/in/nihar-ranjan-mohapatra-4942a4345" class="inline-flex items-center gap-3 badge" target="_blank"><i class="fa-brands fa-linkedin"></i> LinkedIn</a>
        </div>
      </div>

      <form class="glass rounded-lg p-6" action="mailto:nmohapatra079@gmail.com" method="get" encType="text/plain">
        <h3 class="text-xl font-semibold">Quick message</h3>
        <label class="block mt-3 text-sm sm:text-base text-slate-300">Your name</label>
        <input class="mt-1 w-full rounded bg-transparent border border-white/5 p-2" name="name" />
        <label class="block mt-3 text-sm sm:text-base text-slate-300">Message</label>
        <textarea class="mt-1 w-full rounded bg-transparent border border-white/5 p-2" name="message" rows="4"></textarea>
        <div class="mt-4">
          <button type="submit" class="w-full sm:w-auto px-4 py-2 rounded bg-indigo-600 hover:brightness-95">Send email</button>
        </div>
      </form>
    </section>

    <footer class="text-center text-slate-400 py-6 border-t border-white/5 text-sm sm:text-base">© <span id="year"></span> Nihar Ranjan Mohapatra — 🚀 • Reach me: nmohapatra079@gmail.com</footer>
  </div>

  <script>
    document.getElementById('year').textContent = new Date().getFullYear();
  </script>
</body>
</html>
