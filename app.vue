<template>
  <div class="min-h-screen bg-gray-900 text-white flex flex-col justify-center items-center">
    <!-- Background section -->
    <div class="relative overflow-hidden bg-cover bg-center w-full" :style="{ backgroundImage: 'url(https://unsplash.com/photos/WLUHO9A_xik/download?force=true&w=1920)' }">
      <div class="absolute inset-0 bg-black bg-opacity-70 backdrop-blur-md"></div>

      <!-- Profile Section -->
      <div class="relative z-10 max-w-4xl mx-auto text-center py-24">
        <img src="public/profile-idan.jpg" alt="Wildan's Profile Photo" class="w-32 h-32 mx-auto rounded-full border-4 border-gray-700 shadow-lg object-cover transform transition duration-300 hover:scale-110">
        <h1 class="text-4xl font-bold mt-4">Wildan Ahmad Zackiy Mustaghfirin</h1>
        <p class="text-lg mt-2">Information Technology Student | Web Developer | Tech Enthusiast</p>
      </div>
    </div>

    <!-- About Me Section -->
    <section class="max-w-4xl mx-auto py-12 px-6 text-center">
      <h2 class="text-3xl font-semibold mb-6">About Me</h2>
      <p class="leading-relaxed">
        Hello! I’m Wildan, a passionate Information Technology student at Universitas Brawijaya. I specialize in web development and graphic design, with an eagerness to constantly improve my skills. I am actively involved in various organizations, contributing to both technical and entrepreneurial activities.
      </p>
    </section>

    <!-- Skills Section -->
    <section class="max-w-4xl mx-auto py-12 px-6 text-center">
      <h2 class="text-3xl font-semibold mb-6">Skills</h2>
      <div class="space-y-6">
        <div>
          <div class="flex justify-between">
            <p class="font-semibold">PHP & MySQL Development</p>
            <span class="text-gray-500 hidden group-hover:inline">85%</span>
          </div>
          <div class="w-full bg-gray-700 rounded-full h-4 relative group">
            <div class="bg-blue-600 h-4 rounded-full" style="width: 85%;"></div>
          </div>
        </div>
        <div>
          <div class="flex justify-between">
            <p class="font-semibold">JavaScript & Nuxt.js</p>
            <span class="text-gray-500 hidden group-hover:inline">80%</span>
          </div>
          <div class="w-full bg-gray-700 rounded-full h-4 relative group">
            <div class="bg-blue-600 h-4 rounded-full" style="width: 80%;"></div>
          </div>
        </div>
        <!-- Add more skills as needed -->
      </div>
    </section>

    <!-- Education Section -->
    <section class="max-w-4xl mx-auto py-12 px-6 text-center">
      <h2 class="text-3xl font-semibold mb-6">Education</h2>
      <div class="bg-gray-800 p-6 rounded-lg shadow-md text-center">
        <p><strong>Institution:</strong> Universitas Brawijaya</p>
        <p><strong>Major:</strong> Information Technology</p>
        <p><strong>IPK:</strong> 3.78</p>
      </div>
    </section>

    <!-- Experience Section -->
    <section class="max-w-4xl mx-auto py-12 px-6 text-center">
      <h2 class="text-3xl font-semibold mb-6">Experience</h2>
      <div class="bg-gray-800 p-6 rounded-lg shadow-md text-left space-y-4">
        <div>
          <h3 class="text-xl font-semibold">Staff at Mahasiswa Wirausaha</h3>
          <p>Maret 2024 – Sekarang</p>
          <ul class="list-disc list-inside">
            <li>Participated in entrepreneurship seminars and public speaking training.</li>
            <li>Acted as CTO, managing the technological aspects of the organization.</li>
          </ul>
        </div>
        <div>
          <h3 class="text-xl font-semibold">Staff Ahli at PUSKOMINFO BEM Vokasi</h3>
          <p>Maret 2024 – Sekarang</p>
          <ul class="list-disc list-inside">
            <li>Designed content for BEM Vokasi's Instagram feeds.</li>
            <li>Produced a company profile video involving camera and editing teams.</li>
            <li>Organized a workshop on graphic design.</li>
          </ul>
        </div>
      </div>
    </section>

    <!-- Portfolio Section -->
    <section class="max-w-4xl mx-auto py-12 px-6 text-center">
      <h2 class="text-3xl font-semibold mb-6">Portfolio</h2>
      <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
        <!-- Project 1 -->
        <div class="bg-gray-800 p-6 rounded-lg shadow-md text-left">
          <h3 class="text-xl font-semibold">PHP & MySQL Web Application</h3>
          <p class="mt-2">Developed a web application using PHP and MySQL with a focus on data management and user authentication.</p>
        </div>

        <!-- Project 2 -->
        <div class="bg-gray-800 p-6 rounded-lg shadow-md text-left">
          <h3 class="text-xl font-semibold">Mobile App using Flutter</h3>
          <p class="mt-2">Created a cross-platform mobile application using Flutter, showcasing efficient UI design and backend integration.</p>
        </div>

        <!-- Project 3 -->
        <div class="bg-gray-800 p-6 rounded-lg shadow-md text-left">
          <h3 class="text-xl font-semibold">Personal Portfolio Website</h3>
          <p class="mt-2">Designed and developed a personal portfolio website to showcase projects and skills, built using HTML, CSS, and JavaScript.</p>
        </div>

        <!-- Project 4 -->
        <div class="bg-gray-800 p-6 rounded-lg shadow-md text-left">
          <h3 class="text-xl font-semibold">E-commerce Platform</h3>
          <p class="mt-2">Built an e-commerce platform with features like product listings, shopping cart, and payment integration using PHP and MySQL.</p>
        </div>
      </div>
    </section>

    <!-- Contact Section -->
    <section class="max-w-4xl mx-auto py-12 px-6 text-center">
      <h2 class="text-3xl font-semibold mb-6">Contact</h2>
      <div class="grid grid-cols-1 md:grid-cols-3 gap-6 text-center">
        <div class="flex flex-col items-center">
          <p class="text-lg">Email</p>
          <a href="mailto:wildanazmus@gmail.com" class="underline hover:text-blue-400">wildanazmus@gmail.com</a>
        </div>
        <div class="flex flex-col items-center">
          <p class="text-lg">LinkedIn</p>
          <a href="https://linkedin.com/in/wildan-ahmad-zackiy-mustaghfirin" class="underline hover:text-blue-400">linkedin.com/in/wildan-ahmad-zackiy-mustaghfirin</a>
        </div>
        <div class="flex flex-col items-center">
          <p class="text-lg">GitHub</p>
          <a href="https://github.com/wildanazmus" class="underline hover:text-blue-400">github.com/wildanazmus</a>
        </div>
      </div>
    </section>
  </div>
</template>

<script>
export default {
  name: 'Portfolio',
};
</script>

<style scoped>
/* Custom styles can be added here */
</style>
