<template>
<nav class="navbar navbar-expand-lg">
  <div class="container">
    <a class="navbar-brand" href="#">
        <img src="https://i.postimg.cc/zv6MjJZb/Cassidy-Lawrence-1.gif" alt="my-logo" style="width: 4rem;">
    </a>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav ms-auto mb-2 mb-lg-0">
        <li class="nav-item">
          <a class="nav-link" href="#">About</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Resume</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Projects</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Testimonials</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Contact</a>
        </li>
      </ul>
    </div>
  </div>
</nav>
</template>

<script>
    export default {
        
    }
</script>

<style scoped>
.navbar{
    background-color: rgba(0, 0, 0, 0.3);
}

.navbar-nav a{
    color: rgb(251, 96, 84);
    text-shadow:3px 3px 3px black;
}
</style>