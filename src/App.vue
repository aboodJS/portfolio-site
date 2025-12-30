<script setup lang="ts"></script>

<template>
  <main class="bg-slate-900 grid justify-center">
    <section class="max-w-4xl grid h-screen content-center gap-8">
      <p class="text-cyan-400 font-medium">PORTFOLIO</p>
      <div class="md:text-7xl text-5xl font-bold">
        <h1 class="text-white">Abdullah</h1>
        <h1 class="text-cyan-400">Alsawafeen.</h1>
      </div>
      <p class="md:text-3xl bg-slate-900 text-slate-300">Frontend Developer</p>
      <p class="text-slate-400 text-lg">
        Crafting digital experiences with precision and purpose. Specializing in intuitive user
        interfaces that solve real-world problems.
      </p>
    </section>

    <section
      class="grid md:justify-between md:max-w-5xl md:gap-12 md:columns-2 md:grid-rows-3 max-md:text-center gap-3 h-[80vh]"
    >
      <h2
        class="text-3xl font-bold text-slate-100 flex items-center max-md:justify-center self-start gap-3 md:row-start-1"
      >
        <span class="w-8 h-1 bg-cyan-400 max-md:hidden"></span>About
      </h2>
      <div
        class="md:space-y-6 space-y-3 text-sm md:text-lg text-slate-300 leading-relaxed md:col-start-2"
      >
        <p>
          I am a developer who believes in the intersection of logic and creativity. My journey
          began with a curiosity for how things work on the web, which quickly evolved into a
          passion for building friendly, intuitive user interfaces.
        </p>
        <p>
          With a background in frontend development, I make pixel-perfect frontend implementations.
          I don't just write code; I build solutions that prioritize performance, accessibility, and
          user experience.
        </p>
        <p>
          When I'm not coding, I'm exploring new technologies, contributing to open source, or
          refining my craft through continuous learning.
        </p>
      </div>
    </section>
    <section>
      <h2
        class="text-3xl py-12 font-bold text-slate-100 flex items-center max-md:justify-center self-start gap-3 md:row-start-1"
      >
        <span class="w-8 h-1 bg-cyan-400 max-md:hidden"></span>Projects
      </h2>
      <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
        <a
          href="https://abstract-help-tailwind.netlify.app/"
          class="group block bg-slate-800/50 p-8 border border-slate-800 hover:border-cyan-400/50 transition-colors duration-300 max-md:w-[90vw] justify-self-center"
          ><div class="flex justify-between items-start mb-4">
            <h3
              class="text-xl font-bold text-slate-100 group-hover:text-cyan-400 transition-colors"
            >
              Abstarct Help page clone
            </h3>
          </div></a
        >
        <a
          href="https://startbucks-clone.netlify.app/"
          class="group block bg-slate-800/50 p-8 border border-slate-800 hover:border-cyan-400/50 transition-colors duration-300 max-md:w-[90vw] justify-self-center"
          ><div class="flex justify-between items-start mb-4">
            <h3
              class="text-xl font-bold text-slate-100 group-hover:text-cyan-400 transition-colors"
            >
              startbucks page clone
            </h3>
          </div></a
        >
        <a
          href="https://about-ableton.netlify.app/"
          class="group block bg-slate-800/50 p-8 border border-slate-800 hover:border-cyan-400/50 transition-colors duration-300 max-md:w-[90vw] justify-self-center"
          ><div class="flex justify-between items-start mb-4">
            <h3
              class="text-xl font-bold text-slate-100 group-hover:text-cyan-400 transition-colors"
            >
              startbucks page clone
            </h3>
          </div></a
        >
      </div>
    </section>
  </main>
</template>

<style scoped></style>
