<template>
  <div class="min-h-screen bg-slate-950 text-slate-50 flex flex-col">
    <main class="flex-1 flex items-center">
      <section
        class="w-full max-w-5xl mx-auto px-4 py-12 md:py-20 grid gap-10 md:grid-cols-2 items-center"
      >
        <!-- Left Column: Hero Content -->
        <div>
          <p class="text-sm font-medium text-indigo-300 mb-3 tracking-wide uppercase">
            Project Dronacharya
          </p>

          <h1 class="text-3xl md:text-5xl font-bold tracking-tight mb-4">
            Your personal AI guru for
            <span class="text-indigo-400">focused learning</span>.
          </h1>

          <p
            class="text-slate-300 mb-8 text-sm md:text-base leading-relaxed"
          >
            Turn scattered notes, PDFs, and lecture slides into a clear,
            structured, and distraction-free learning path. Let the AI do the
            heavy lifting while you focus on what matters.
          </p>

          <div class="flex flex-wrap gap-3">
            <RouterLink
              to="/upload"
              class="rounded-full bg-indigo-500 hover:bg-indigo-400 px-6 py-3 text-sm md:text-base font-medium transition"
            >
              Start by uploading notes
            </RouterLink>

            <RouterLink
              to="/curriculum"
              class="rounded-full border border-slate-600 text-slate-100 hover:bg-slate-800 px-6 py-3 text-sm md:text-base font-medium transition"
            >
              Build my curriculum
            </RouterLink>
          </div>

          <p class="mt-4 text-xs md:text-sm text-slate-400">
            No login, no noise — just you, your notes, and a focused path
            forward.
          </p>
        </div>

        <!-- Right Column: Feature Card -->
        <div class="space-y-4">
          <div
            class="rounded-2xl border border-slate-800 bg-slate-900/60 p-5 md:p-6 shadow-lg shadow-indigo-900/20"
          >
            <p class="text-xs font-semibold text-indigo-300 tracking-wide mb-3">
              HOW IT WORKS
            </p>

            <ul class="space-y-3 text-sm text-slate-200">
              <li class="flex gap-2">
                <span class="mt-0.5">📂</span>
                <span>
                  <strong>Upload your material</strong> — PDFs, notes, slides,
                  or textbooks.
                </span>
              </li>

              <li class="flex gap-2">
                <span class="mt-0.5">🧠</span>
                <span>
                  <strong>AI analyses everything</strong> — extracts topics,
                  difficulty, and key concepts.
                </span>
              </li>

              <li class="flex gap-2">
                <span class="mt-0.5">🎯</span>
                <span>
                  <strong>Get a guided path</strong> — structured curriculum,
                  summaries, and practice.
                </span>
              </li>
            </ul>
          </div>

          <!-- Mini Feature Cards -->
          <div class="grid gap-3 md:grid-cols-2 text-xs md:text-sm">
            <div
              class="rounded-xl border border-slate-800 bg-slate-900/60 p-3"
            >
              <p class="font-medium mb-1 text-slate-100">Curriculum Builder</p>
              <p class="text-slate-400">
                Auto-generate your day-wise study plan based on time and goals.
              </p>
            </div>

            <div
              class="rounded-xl border border-slate-800 bg-slate-900/60 p-3"
            >
              <p class="font-medium mb-1 text-slate-100">Practice & Revision</p>
              <p class="text-slate-400">
                Convert content into quizzes, flashcards, and targeted drills.
              </p>
            </div>
          </div>
        </div>
      </section>
    </main>
  </div>
</template>

<script setup lang="ts">
//
</script>
