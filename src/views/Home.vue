<template>
  <div>
    <h1 class="text-center font-bold text-blue-150">
      <i class="fas fa-rss-square"></i> Recent News
      <i class="fas fa-angle-double-down"></i>
    </h1>
    <h2 class="text-center text-red-100 font-bold mb-4">
      <i class="fab fa-youtube"></i> Most Recent News From Youtube
    </h2>
    <div class="align-center">
      <iframe
        width="560"
        height="315"
        src="https://www.youtube.com/embed/qJ3jnGCtPUs?controls=0"
        title="YouTube video player"
        frameborder="0"
        allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
        allowfullscreen
      ></iframe>
    </div>
  </div>
</template>

<script>
export default {
  name: "Home",
  components: {},
};
</script>