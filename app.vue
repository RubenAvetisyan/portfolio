<template>
  <div class="min-h-screen bg-white">
    <!-- Header -->
    <header class="sticky top-0 z-50 w-full bg-white shadow-sm">
      <nav class="container mx-auto px-4 py-4">
        <div class="flex items-center justify-between">
          <h1 class="text-2xl font-bold text-blue-600">Ruben Avetisyan</h1>
          <a href="https://github.com/RubenAvetisyan" 
             class="flex items-center space-x-2 text-gray-600 hover:text-blue-600 transition-colors">
            <Icon icon="fa:github" class="h-6 w-6" />
            <span class="hidden md:inline">View on GitHub</span>
          </a>
        </div>
      </nav>
    </header>

    <!-- Hero Section -->
    <section class="py-16 bg-gradient-to-r from-blue-50 to-blue-100">
      <div class="container mx-auto px-4">
        <div class="flex flex-col md:flex-row items-center gap-8">
          <div class="w-48 h-48 rounded-full overflow-hidden shadow-lg">
            <img src="/DSC_7468.JPG" alt="Ruben Avetisyan" class="w-full h-full object-cover" />
          </div>
          <div class="max-w-2xl">
            <h2 class="text-4xl font-bold text-gray-800 mb-4">Senior Software Engineer</h2>
            <p class="text-xl text-gray-600 mb-6">
              Passionate about crafting exceptional web experiences with modern technologies. Specializing in JavaScript, TypeScript, and full-stack development.
            </p>
            <div class="flex gap-4">
              <a href="https://github.com/RubenAvetisyan" 
                 class="px-6 py-3 bg-blue-600 text-white rounded-full hover:bg-blue-700 transition-colors">
                View Portfolio
              </a>
              <a href="mailto:contact@example.com" 
                 class="px-6 py-3 border-2 border-blue-600 text-blue-600 rounded-full hover:bg-blue-50 transition-colors">
                Contact Me
              </a>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- About Section -->
    <section class="py-16">
      <div class="container mx-auto px-4">
        <h2 class="text-3xl font-bold text-gray-800 mb-8 text-center">About Me</h2>
        <div class="max-w-3xl mx-auto text-gray-600">
          <p class="mb-4">
            I'm a Senior Software Engineer with extensive experience in building modern web applications. 
            My focus is on creating efficient, scalable, and maintainable solutions using cutting-edge technologies.
          </p>
          <p>
            I believe in writing clean code, following best practices, and continuously learning new technologies 
            to stay at the forefront of web development.
          </p>
        </div>
      </div>
    </section>

    <!-- Skills Section -->
    <section class="py-16 bg-gray-50">
      <div class="container mx-auto px-4">
        <h2 class="text-3xl font-bold text-gray-800 mb-12 text-center">Technical Skills</h2>
        <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
          <div class="bg-white p-6 rounded-lg shadow-sm">
            <h3 class="text-xl font-semibold text-blue-600 mb-4">Frontend Development</h3>
            <ul class="space-y-2">
              <li class="flex items-center gap-2">
                <Icon icon="fa:check" class="text-green-500" />
                JavaScript (ES6+)
              </li>
              <li class="flex items-center gap-2">
                <Icon icon="fa:check" class="text-green-500" />
                TypeScript
              </li>
              <li class="flex items-center gap-2">
                <Icon icon="fa:check" class="text-green-500" />
                React.js
              </li>
              <li class="flex items-center gap-2">
                <Icon icon="fa:check" class="text-green-500" />
                Vue.js
              </li>
            </ul>
          </div>
          <div class="bg-white p-6 rounded-lg shadow-sm">
            <h3 class="text-xl font-semibold text-blue-600 mb-4">Backend Development</h3>
            <ul class="space-y-2">
              <li class="flex items-center gap-2">
                <Icon icon="fa:check" class="text-green-500" />
                Node.js
              </li>
              <li class="flex items-center gap-2">
                <Icon icon="fa:check" class="text-green-500" />
                Express.js
              </li>
              <li class="flex items-center gap-2">
                <Icon icon="fa:check" class="text-green-500" />
                RESTful APIs
              </li>
              <li class="flex items-center gap-2">
                <Icon icon="fa:check" class="text-green-500" />
                Database Design
              </li>
            </ul>
          </div>
          <div class="bg-white p-6 rounded-lg shadow-sm">
            <h3 class="text-xl font-semibold text-blue-600 mb-4">Tools & Practices</h3>
            <ul class="space-y-2">
              <li class="flex items-center gap-2">
                <Icon icon="fa:check" class="text-green-500" />
                Git & GitHub
              </li>
              <li class="flex items-center gap-2">
                <Icon icon="fa:check" class="text-green-500" />
                CI/CD
              </li>
              <li class="flex items-center gap-2">
                <Icon icon="fa:check" class="text-green-500" />
                Test-Driven Development
              </li>
              <li class="flex items-center gap-2">
                <Icon icon="fa:check" class="text-green-500" />
                Agile Methodologies
              </li>
            </ul>
          </div>
        </div>
      </div>
    </section>

    <!-- Contact Section -->
    <section class="py-16">
      <div class="container mx-auto px-4">
        <h2 class="text-3xl font-bold text-gray-800 mb-8 text-center">Get in Touch</h2>
        <div class="flex flex-col items-center space-y-4">
          <p class="text-gray-600 text-center max-w-2xl mb-8">
            I'm always interested in hearing about new projects and opportunities. 
            Feel free to reach out if you'd like to connect!
          </p>
          <div class="flex gap-4">
            <a href="https://github.com/RubenAvetisyan" 
               class="flex items-center gap-2 px-6 py-3 bg-gray-900 text-white rounded-full hover:bg-gray-800 transition-colors">
              <Icon icon="fa:github" class="h-5 w-5" />
              <span>GitHub</span>
            </a>
            <a href="mailto:contact@example.com" 
               class="flex items-center gap-2 px-6 py-3 bg-blue-600 text-white rounded-full hover:bg-blue-700 transition-colors">
              <Icon icon="fa:envelope" class="h-5 w-5" />
              <span>Email</span>
            </a>
          </div>
        </div>
      </div>
    </section>
  </div>
</template>

<script setup>
import { Icon } from '@iconify/vue';
</script>