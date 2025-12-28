<template>
  <div class="min-h-screen bg-slate-950 text-slate-100 font-sans">
    <!-- Navigation -->
    <header class="sticky top-0 z-20 bg-slate-950/90 backdrop-blur border-b border-slate-800">
      <div class="max-w-5xl mx-auto flex items-center justify-between py-3 px-4">
        <div class="text-lg font-semibold tracking-tight">
          GO + VUE CV
        </div>
        <nav class="space-x-4 text-sm">
          <a href="#about" class="hover:text-cyan-300">About</a>
          <a href="#experience" class="hover:text-cyan-300">Experience</a>
          <a href="#projects" class="hover:text-cyan-300">Projects</a>
          <a href="#education" class="hover:text-cyan-300">Education</a>
          <a href="#contact" class="hover:text-cyan-300">Contact</a>
        </nav>
      </div>
    </header>

    <main class="max-w-5xl mx-auto px-4 pb-16">
      <!-- Hero -->
      <section id="home" class="py-12 border-b border-slate-800">
        <div class="grid gap-8 md:grid-cols-[2fr,1fr] items-center">
          <div>
            <p class="text-sm text-cyan-300 mb-2">Personal Portfolio</p>
            <h1 class="text-3xl md:text-4xl font-bold mb-3">
              Your Name Here
            </h1>
            <p class="text-lg text-slate-300 mb-4">
              Full‑stack Developer · Go + Vue · Automation & AI Enthusiast
            </p>
            <p class="text-sm text-slate-400 mb-6">
              Brief self‑intro here. For example: building modern web apps with Go backends,
              Vue frontends, and AI / automation tools like n8n and Ollama.
            </p>
            <div class="flex flex-wrap gap-3">
              <a href="#projects"
                 class="px-4 py-2 rounded bg-cyan-500 text-slate-950 text-sm font-medium hover:bg-cyan-400">
                View Projects
              </a>
              <a href="#contact"
                 class="px-4 py-2 rounded border border-slate-600 text-sm hover:border-cyan-400">
                Contact Me
              </a>
            </div>
          </div>
          <div class="space-y-3 text-sm text-slate-300">
            <div>
              <div class="text-slate-400">Location</div>
              <div>Hong Kong · Remote friendly</div>
            </div>
            <div>
              <div class="text-slate-400">Core Skills</div>
              <div>Go, Vue 3, TypeScript, REST API, n8n, Docker</div>
            </div>
            <div>
              <div class="text-slate-400">Languages</div>
              <div>Chinese · English</div>
            </div>
          </div>
        </div>
      </section>

      <!-- About / Skills -->
      <section id="about" class="py-10 border-b border-slate-800">
        <h2 class="text-xl font-semibold mb-4">About & Skills</h2>
        <p class="text-sm text-slate-300 mb-4">
          Replace this paragraph with your own background: years of experience, industries,
          and what type of roles or clients you are interested in.
        </p>
        <div class="grid gap-4 md:grid-cols-3 text-sm">
          <div class="border border-slate-800 rounded-lg p-4">
            <h3 class="font-semibold mb-2 text-cyan-300">Frontend</h3>
            <ul class="space-y-1 text-slate-300">
              <li>Vue 3 / Vite</li>
              <li>TypeScript / JavaScript</li>
              <li>Responsive design</li>
            </ul>
          </div>
          <div class="border border-slate-800 rounded-lg p-4">
            <h3 class="font-semibold mb-2 text-cyan-300">Backend</h3>
            <ul class="space-y-1 text-slate-300">
              <li>Go (Gin / Echo)</li>
              <li>RESTful APIs</li>
              <li>PostgreSQL / SQLite</li>
            </ul>
          </div>
          <div class="border border-slate-800 rounded-lg p-4">
            <h3 class="font-semibold mb-2 text-cyan-300">Automation & AI</h3>
            <ul class="space-y-1 text-slate-300">
              <li>n8n workflows</li>
              <li>Ollama local LLMs</li>
              <li>Prompt design</li>
            </ul>
          </div>
        </div>
      </section>

      <!-- Experience -->
      <section id="experience" class="py-10 border-b border-slate-800">
        <h2 class="text-xl font-semibold mb-4">Work Experience</h2>
        <div class="space-y-5 text-sm">
          <div>
            <div class="flex justify-between">
              <div class="font-semibold">Job Title – Company Name</div>
              <div class="text-slate-400">2022 – Present</div>
            </div>
            <div class="text-slate-400 mb-1">Location</div>
            <ul class="list-disc list-inside text-slate-300 space-y-1">
              <li>Bullet point describing your main responsibility.</li>
              <li>Bullet point describing a key achievement.</li>
              <li>Bullet point describing tools / tech stack used.</li>
            </ul>
          </div>

          <div>
            <div class="flex justify-between">
              <div class="font-semibold">Previous Role – Previous Company</div>
              <div class="text-slate-400">2019 – 2022</div>
            </div>
            <div class="text-slate-400 mb-1">Location</div>
            <ul class="list-disc list-inside text-slate-300 space-y-1">
              <li>Another responsibility or project you handled.</li>
              <li>Quantify impact where possible (%, time saved, etc.).</li>
            </ul>
          </div>
        </div>
      </section>

      <!-- Projects -->
      <section id="projects" class="py-10 border-b border-slate-800">
        <h2 class="text-xl font-semibold mb-4">Projects</h2>
        <div class="grid gap-4 md:grid-cols-2 text-sm">
          <article class="border border-slate-800 rounded-lg p-4">
            <h3 class="font-semibold mb-1">GO + VUE Portfolio Website</h3>
            <p class="text-slate-300 mb-2">
              Personal website built with Go backend and Vue frontend, deployed on free tiers.
            </p>
            <p class="text-slate-400 mb-2 text-xs">Tech: Go, Vue 3, Vite, Tailwind, Netlify</p>
            <a href="#" class="text-cyan-300 text-xs hover:underline">View code / demo</a>
          </article>

          <article class="border border-slate-800 rounded-lg p-4">
            <h3 class="font-semibold mb-1">AI Automation with n8n</h3>
            <p class="text-slate-300 mb-2">
              Automated contact‑form replies using n8n and LLMs, with summaries stored to a sheet.
            </p>
            <p class="text-slate-400 mb-2 text-xs">Tech: n8n, Gemini / OpenAI, Webhooks</p>
            <a href="#" class="text-cyan-300 text-xs hover:underline">View details</a>
          </article>
        </div>
      </section>

      <!-- Education -->
      <section id="education" class="py-10 border-b border-slate-800">
        <h2 class="text-xl font-semibold mb-4">Education</h2>
        <div class="space-y-3 text-sm">
          <div>
            <div class="font-semibold">Bachelor of Something – University Name</div>
            <div class="text-slate-400 text-xs">2015 – 2019</div>
            <p class="text-slate-300 text-sm">
              Short description of your studies, focus area, or relevant coursework.
            </p>
          </div>
        </div>
      </section>

      <!-- Contact -->
      <section id="contact" class="py-10">
        <h2 class="text-xl font-semibold mb-4">Contact</h2>
        <p class="text-sm text-slate-300 mb-3">
          Feel free to reach out for collaboration, freelance work, or just to say hi.
        </p>
        <ul class="text-sm text-slate-300 space-y-1">
          <li>Email: <a href="mailto:you@example.com" class="text-cyan-300">you@example.com</a></li>
          <li>GitHub: <a href="https://github.com/yourname" class="text-cyan-300" target="_blank">github.com/yourname</a></li>
          <li>LinkedIn: <a href="#" class="text-cyan-300" target="_blank">Your LinkedIn URL</a></li>
        </ul>
      </section>
    </main>
  </div>
</template>

<script setup>
// 暫時不需要腳本邏輯，之後要加動畫或 API 再擴充
</script>

<style scoped>
body {
  margin: 0;
}
</style>
