<script lang="ts" setup>
  import nitroguy from "@/data/nitroguy.json";
</script>

<template>
  <div id="index">
    <div id="about-me" class="bg-zinc-700 p-5 relative">
      <div class="absolute bottom-5 -top-5 -left-5 right-5 bg-zinc-500 -z-10" />
      <div class="absolute -bottom-5 top-5 left-5 -right-5 bg-zinc-300 -z-10" />
      <p>Hi there!</p>
      <p>I'm <NuxtLink to="/links">NitroGuy</NuxtLink>. Currently, I am a human who lives on Earth. My hobbies include programming, producing music, editing videos, playing video games, and sleeping.</p>
      <p>I am highly interested in computer science and software development. I would call myself a "full-stack web developer" as of now but I am very eager to explore other facets of computer science. I've been coding since 2015 and I am proficient in Java, Python, HTML, CSS, JavaScript, TypeScript, C++, and C#. If you want to read more about my work, check out my <NuxtLink :to="nitroguy.socials.github.link">GitHub</NuxtLink> or read my personal commentary on the <NuxtLink to="/projects">projects</NuxtLink> I've made.</p>
      <p>I am chronically addicted to music. I love playing, producing, and listening to music. I've loved a variety of genres over the years but right now I am most fixated on <NuxtLink to="/tangents/dubstep-subgenres">dubstep</NuxtLink> and EDM. Check out my <NuxtLink to="/music">discography</NuxtLink> or visit my <NuxtLink :to="nitroguy.socials.soundcloud.link">SoundCloud</NuxtLink> if you're into that kind of stuff.</p>
      <p>I love and am endlessly inspired by the worlds that video games create. They have been a massive part of my life but I hardly ever play them anymore and I want to get back into them! Some of my all-time favorites include Minecraft, Factorio, Team Fortress 2, the Ace Attorney series, Stardew Valley, and <NuxtLink to="/tangents/favorite-games">more</NuxtLink>.</p>
      <p><NuxtLink to="https://en.pronouns.page/he">he/him</NuxtLink></p>
    </div>
  </div>
</template>
