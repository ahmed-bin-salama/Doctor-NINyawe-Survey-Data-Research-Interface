<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Doctor NINyawe eBook</title>
  <script src="https://cdn.tailwindcss.com"></script>
</head>
<body class="bg-gray-50 text-gray-900">
  <!-- Header -->
  <header class="bg-white shadow sticky top-0 z-50">
    <div class="max-w-7xl mx-auto px-6 py-4 flex justify-between items-center">
      <h1 class="text-2xl font-bold text-blue-600">Doctor-NINyawe</h1>
      <nav class="space-x-6">
        <a href="#anatomy" class="text-gray-600 hover:text-blue-600">Anatomy</a>
        <a href="#physiology" class="text-gray-600 hover:text-blue-600">Physiology</a>
        <a href="#pathology" class="text-gray-600 hover:text-blue-600">Pathology</a>
      </nav>
    </div>
  </header>

  <!-- Hero Section -->
  <section class="text-center py-16 bg-gradient-to-br from-blue-100 to-indigo-200">
    <h2 class="text-4xl font-extrabold mb-4">Interactive Medical eBook</h2>
    <p class="max-w-2xl mx-auto text-lg text-gray-700">
      Built from real medical lectures using AI structuring, TailwindCSS, and Obsidian-ready organization.
    </p>
    <img src="images/cover.png" alt="Book Cover" class="mx-auto mt-8 rounded-xl shadow-lg w-64">
  </section>

  <!-- Content Sections -->
  <main class="max-w-5xl mx-auto px-6 py-12 space-y-24">
    
    <!-- Anatomy Section -->
    <section id="anatomy">
      <h3 class="text-3xl font-bold text-blue-700 mb-4">Anatomy</h3>
      <p class="mb-4">Explore the detailed structure of the human body — from bones and muscles to nerves and vessels.</p>
      <img src="images/anatomy.png" alt="Anatomy" class="rounded-lg shadow mb-6 w-full">
      <a href="lectures/anatomy.html" class="bg-blue-600 text-white px-4 py-2 rounded hover:bg-blue-700">Read Lecture</a>
    </section>

    <!-- Physiology Section -->
    <section id="physiology">
      <h3 class="text-3xl font-bold text-green-700 mb-4">Physiology</h3>
      <p class="mb-4">Understand the functions of each body system through AI-organized flowcharts and interactive explanations.</p>
      <img src="images/histology.png" alt="Physiology" class="rounded-lg shadow mb-6 w-full">
      <a href="lectures/physiology.html" class="bg-green-600 text-white px-4 py-2 rounded hover:bg-green-700">Read Lecture</a>
    </section>

    <!-- Pathology Section -->
    <section id="pathology">
      <h3 class="text-3xl font-bold text-red-700 mb-4">Pathology</h3>
      <p class="mb-4">Dive into disease mechanisms with histopathological visuals, explanations, and AI-clarified notes.</p>
      <a href="lectures/pathology.html" class="bg-red-600 text-white px-4 py-2 rounded hover:bg-red-700">Read Lecture</a>
    </section>
  </main>

  <!-- Footer -->
  <footer class="bg-gray-900 text-gray-300 text-center py-8 mt-16">
    <p>© 2025 Doctor NINyawe — AI-Powered Medical Learning</p>
    <p class="text-sm text-gray-500 mt-2">Built with TailwindCSS · Hosted on GitHub Pages</p>
  </footer>
</body>
</html>
