<template>
    <nav class="bg-dark">
        <a href="../views/HomeView.vue">
          <img class="logo" src="https://i.postimg.cc/JnpQqnfb/retro-sword-badges-shields-logo-260nw-450358219.webp" alt="Logo">
        </a>
        <router-link to="/">Home</router-link> |
        <router-link to="/about">About</router-link> |
        <router-link to="/resume">Resume</router-link> |
        <router-link to="/project">Project</router-link> |
        <router-link to="/testimonial">Testimonial</router-link> |
        <router-link to="/contact">Contact</router-link> |
      </nav>
      <!-- <nav class="navbar navbar-expand-lg bg-dark navbar-dark">
        <div class="container-fluid">
            <a href="../views/HomeView.vue">
                <img class="logo" src="https://i.postimg.cc/JnpQqnfb/retro-sword-badges-shields-logo-260nw-450358219.webp" alt="Logo">
            </a>
          <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
          </button>
          <div class="collapse navbar-collapse" id="navbarSupportedContent">
            <ul class="navbar-nav ms-auto mb-2 mb-lg-0">
              <li class="nav-item">
                <a class="nav-link active" aria-current="page" href="../views/HomeView.vue">
                    <i class="bi bi-house"></i>
                  Home</a>
              </li>
              <li class="nav-item">
                <a class="nav-link active" aria-current="page" href="../views/AboutView.vue">
                    <i class="bi bi-file-person-fill"></i>
                  About</a>
              </li>
              <li class="nav-item">
                <a class="nav-link active" aria-current="page" href="../views/ResumeView.vue">
                    <i class="bi bi-file-earmark-person-fill"></i>
                  Resume</a>
              </li>
              <li class="nav-item">
                <a class="nav-link active" aria-current="page" href="../views/ProjectView.vue">
                    <i class="bi bi-folder-fill"></i>
                  Projects</a>
              </li>
              <li class="nav-item">
                <a class="nav-link active" aria-current="page" href="../views/TestimonialView.vue">
                    <i class="bi bi-journal-richtext"></i>
                  Testimonials</a>
              </li>
              <li class="nav-item">
                <a class="nav-link active" aria-current="page" href="../views/ContactView.vue">
                    <i class="bi bi-person-lines-fill"></i>
                  Contact</a>
              </li>
            </ul>
          </div>
        </div>
      </nav> -->
</template>
<script>
export default {
    
}
</script>
<style>
  nav{
    box-shadow: .3vw .5vw .45vw .1vw ;
    display: flex;
    justify-content: space-between;
    align-items: center;
  }
@media screen and (max-width: 545px){
  nav{
    flex-flow: column nowrap;
  }
}

</style>