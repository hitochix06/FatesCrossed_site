<template>
  <div class="min-h-screen px-4 py-10 custom-bg">
    <div class="max-w-7xl mx-auto grid grid-cols-1 md:grid-cols-2 gap-4">
      <!-- Modification ici pour une seule colonne sur petits écrans et deux colonnes à partir de medium -->
      <div
        class="flex justify-center md:justify-between-end items-center mt-40 mb-8 md:mb-0"
      >
        <!-- Centrage du bouton sur petits écrans -->
        <a
          href="#download"
          class="px-6 py-3 md:px-8 md:py-4 text-base md:text-lg font-semibold rounded-lg bg-gradient-to-r from-purple-600 to-pink-600 text-white hover:from-purple-700 hover:to-pink-700 transform hover:-translate-y-1 transition-all duration-300"
        >
          Rejoindre l'Aventure
        </a>
      </div>
      <div class="text-left">
        <!-- Texte aligné à droite -->
        <div
          class="inline-block bg-white/10 backdrop-blur-md p-6 rounded-lg text"
        >
          <p class="mt-4 text-xl leading-relaxed text-white">
            Dans ce jeu d'aventure captivant, incarnez un héros aux prises avec
            un passé sombre et des secrets insondables. Sauvé des rues par la
            mystérieuse Lilly, vous vous lancez dans une quête pour découvrir la
            vérité. Explorez des environnements riches, résolvez des énigmes
            complexes et affrontez des dangers pour démêler les mystères qui
            entourent la disparition de votre mère et un événement étrange qui a
            changé votre destin. Vos choix façonneront l'histoire et
            détermineront le destin des êtres qui vous entourent. Êtes-vous prêt
            à percer les mystères qui vous entourent ?
          </p>
        </div>
      </div>
    </div>
  </div>
</template>

<style>
@keyframes zoom {
  from {
    transform: scale(1);
  }
  to {
    transform: scale(1.05);
  }
}
.animate-zoom {
  animation: zoom 10s infinite alternate;
}
.custom-bg {
  background-image: url("src/assets/web-presplash.jpg");
  background-size: cover; /* Couvre toute la zone disponible */
  background-position: center; /* Centre l'image */
}
</style>
