<template>
  <div class="min-h-screen px-4 py-20 custom-bg">
    <div class="max-w-7xl mx-auto grid grid-cols-2 gap-4">
      <!-- Utilisation de grid pour créer deux colonnes -->
      <!-- Colonne de gauche pour le texte -->
      <div class="text-left">
        <!-- Texte aligné à droite -->
        <div
          class="inline-block bg-white/10 backdrop-blur-md p-6 rounded-lg animate-zoom text"
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
      <!-- Colonne de droite pour le bouton -->
      <div class="flex justify-end items-center">
        <!-- Bouton aligné à gauche, centré verticalement -->
        <a
          href="#download"
          class="px-8 py-4 text-lg font-semibold rounded-lg bg-gradient-to-r from-purple-600 to-pink-600 text-white hover:from-purple-700 hover:to-pink-700 transform hover:-translate-y-1 transition-all duration-300"
        >
          Rejoindre l'Aventure
        </a>
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
