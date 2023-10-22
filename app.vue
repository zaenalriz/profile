<template>
  <div>
    <div class="flex items-center h-screen w-full justify-center">
      <div class="max-w-xs">
        <div class="bg-white  rounded-lg py-3">
          <div class="photo-wrapper p-2">
            <img class="w-32 h-32 rounded-full mx-auto" src="/profile.jpeg" alt="zaenal">
          </div>
          <div class="p-2">
            <h3 class="text-center text-xl text-gray-900 font-medium leading-8">Muhamad Zaenal Rizki</h3>
            <div class="text-center text-gray-400 text-xs font-semibold">
              <p>Web Developer</p>
            </div>
            <div class="text-center my-3">
              <a target="_blank" href="https://github.com/zaenalriz"
                class="text-xs mx-2 text-indigo-500 italic hover:underline hover:text-indigo-600 font-medium">
                Github</a>
              <a target="_blank" href="https://www.linkedin.com/in/muhamad-zaenal-rizki-952430215/"
                class="text-xs mx-2 text-indigo-500 italic hover:underline hover:text-indigo-600 font-medium">
                Linkedin</a>
            </div>

          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<script setup lang="ts">
useSeoMeta({
  title: 'zaenalriz',
  ogTitle: 'zaenalriz',
  description: 'zaenalriz',
  ogDescription: 'zaenalriz',
})
</script>