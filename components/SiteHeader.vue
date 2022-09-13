<template>
  <div>
    <nav>
      <a href="#">Home</a>
      <a href="#">About</a>
      <a href="#">Training Programs</a>
      <a href="#">Nutrition Blog</a>
    </nav>

    <div class="hero">
      <div>
        <h1>Trained by Kim.</h1>
        <h3>Get trained and reach your fitness goal faster than ever with our QikFit program.</h3>
      </div>
    </div>
  </div>
</template>

<style scoped>
nav {
  @apply flex flex-wrap gap-16 justify-center py-4 bg-indigo-700;
}

nav a {
  @apply text-lg font-semibold text-gray-100 hover:bg-indigo-800 px-4 py-2 rounded-lg;
}

.hero {
  @apply h-64 bg-gray-900 flex flex-col;
}

.hero > div {
  @apply m-auto;
}

.hero > div h1 {
  @apply text-5xl font-extrabold text-gray-300;
}

.hero > div h3 {
  @apply mt-3 text-gray-300 text-xl font-semibold;
}

</style>

