<template>
  <div class="about">
    <h1>Conecte-se comigo!</h1>
    <a href="https://github.com/MarcosT-800">
      <i class="fab fa-github"></i> Github
    </a>
    <a href="https://www.linkedin.com/in/marcos-alves-b2934a203/">
      <i class="fab fa-linkedin"></i> Linkedin
    </a>
    <a href="https://www.youtube.com/channel/UCDSYFgjuwGaazkscfxlg6bA/featured">
      <i class="fab fa-youtube"></i> YouTube
    </a>
  </div>
</template>

<style>
@media (min-width: 1024px) {
  .about {
    display: flex;
    flex-direction: column;
    justify-content: center;
    min-height: 100vh;
    display: flex;
    align-items: center;
  }

  /* Estilos adicionais para os ícones, se necessário */
  .about a i {
    margin-right: 5px; /* Ajuste o espaçamento conforme necessário */
  }
}
</style>
