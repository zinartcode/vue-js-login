<template>
  <div class="hero">
    <div>
      <img id="instaLogo" src="../assets/instagram-icon.png" />
      <h1 class="display-3">Welcome to club</h1>
      <p class="lead">Enter your login</p>
      <button type="button" class="btn btn-secondary">Give it a try</button>
    </div>
  </div>
</template>

<style>
  .hero {
    height: 90vh;
    display: flex;
    align-items: center;
    justify-content: center;
    text-align: center;
  }
  .hero .lead {
    font-weight: 200;
    font-size: 1.5rem;
  }
  #instaLogo {
    height: 13em;
    weight: auto;
  }
</style>