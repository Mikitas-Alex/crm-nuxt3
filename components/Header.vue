<template>
  <header
    class="p-5 border-b border-gray-700 sticky w-full top-0 bg-zinc-900/90 z-10"
  >
    <nav class="flex items-center justify-between lg:max-w-screen-lg mx-auto">
      <NuxtLink to="/">
        <Icon name="uil:arrow-growth" size="2rem" class="text-emerald-500" />
        Nuxt - CRM</NuxtLink
      >
      <div class="flex items-center gap-4">
        <UserCreateModal />
        <NuxtLink to="https://github.com/Mikitas-Alex" target="_blank" class="group">
          <Icon name="uil:github" size="2rem" />
          <span class="group-hover:text-emerald-500 transition-all">
            Github
          </span>
        </NuxtLink>
      </div>
    </nav>
  </header>
</template>
