<template>
  <div>
    <div class="flex items-center justify-between px-4 md:px-16 h-16 w-full">
      <!-- Logo -->
      <div>
        <img class="h-16" src="../assets/images/Logo 1.png" alt="" />
      </div>

      <!-- Menu burger -->
      <div class="md:hidden w-20 flex justify-between">
        <!-- <div class="w-16 flex items-center justify-center">
          <button @click="openModal">
            <Modal v-if="showModal" @close="closeModal" />
            <svg
              width="20"
              height="20"
              viewBox="0 0 20 20"
              fill="black"
              xmlns="http://www.w3.org/2000/svg"
            >
              <path
                d="M10 0C8.68678 0 7.38642 0.258658 6.17317 0.761205C4.95991 1.26375 3.85752 2.00035 2.92893 2.92893C1.05357 4.8043 0 7.34784 0 10C0 12.6522 1.05357 15.1957 2.92893 17.0711C3.85752 17.9997 4.95991 18.7362 6.17317 19.2388C7.38642 19.7413 8.68678 20 10 20C12.6522 20 15.1957 18.9464 17.0711 17.0711C18.9464 15.1957 20 12.6522 20 10C20 8.68678 19.7413 7.38642 19.2388 6.17317C18.7362 4.95991 17.9997 3.85752 17.0711 2.92893C16.1425 2.00035 15.0401 1.26375 13.8268 0.761205C12.6136 0.258658 11.3132 0 10 0ZM5.07 16.28C5.5 15.38 8.12 14.5 10 14.5C11.88 14.5 14.5 15.38 14.93 16.28C13.5294 17.396 11.7909 18.0026 10 18C8.14 18 6.43 17.36 5.07 16.28ZM16.36 14.83C14.93 13.09 11.46 12.5 10 12.5C8.54 12.5 5.07 13.09 3.64 14.83C2.57618 13.4446 1.99967 11.7467 2 10C2 5.59 5.59 2 10 2C14.41 2 18 5.59 18 10C18 11.82 17.38 13.5 16.36 14.83ZM10 4C8.06 4 6.5 5.56 6.5 7.5C6.5 9.44 8.06 11 10 11C11.94 11 13.5 9.44 13.5 7.5C13.5 5.56 11.94 4 10 4ZM10 9C9.60218 9 9.22064 8.84196 8.93934 8.56066C8.65804 8.27936 8.5 7.89782 8.5 7.5C8.5 7.10218 8.65804 6.72064 8.93934 6.43934C9.22064 6.15804 9.60218 6 10 6C10.3978 6 10.7794 6.15804 11.0607 6.43934C11.342 6.72064 11.5 7.10218 11.5 7.5C11.5 7.89782 11.342 8.27936 11.0607 8.56066C10.7794 8.84196 10.3978 9 10 9Z"
                fill="black"
              />
            </svg>
          </button>
        </div> -->
        <button
          @click="showModal = true"
          class=""
        >
        <svg
              width="20"
              height="20"
              viewBox="0 0 20 20"
              fill="black"
              xmlns="http://www.w3.org/2000/svg"
            >
              <path
                d="M10 0C8.68678 0 7.38642 0.258658 6.17317 0.761205C4.95991 1.26375 3.85752 2.00035 2.92893 2.92893C1.05357 4.8043 0 7.34784 0 10C0 12.6522 1.05357 15.1957 2.92893 17.0711C3.85752 17.9997 4.95991 18.7362 6.17317 19.2388C7.38642 19.7413 8.68678 20 10 20C12.6522 20 15.1957 18.9464 17.0711 17.0711C18.9464 15.1957 20 12.6522 20 10C20 8.68678 19.7413 7.38642 19.2388 6.17317C18.7362 4.95991 17.9997 3.85752 17.0711 2.92893C16.1425 2.00035 15.0401 1.26375 13.8268 0.761205C12.6136 0.258658 11.3132 0 10 0ZM5.07 16.28C5.5 15.38 8.12 14.5 10 14.5C11.88 14.5 14.5 15.38 14.93 16.28C13.5294 17.396 11.7909 18.0026 10 18C8.14 18 6.43 17.36 5.07 16.28ZM16.36 14.83C14.93 13.09 11.46 12.5 10 12.5C8.54 12.5 5.07 13.09 3.64 14.83C2.57618 13.4446 1.99967 11.7467 2 10C2 5.59 5.59 2 10 2C14.41 2 18 5.59 18 10C18 11.82 17.38 13.5 16.36 14.83ZM10 4C8.06 4 6.5 5.56 6.5 7.5C6.5 9.44 8.06 11 10 11C11.94 11 13.5 9.44 13.5 7.5C13.5 5.56 11.94 4 10 4ZM10 9C9.60218 9 9.22064 8.84196 8.93934 8.56066C8.65804 8.27936 8.5 7.89782 8.5 7.5C8.5 7.10218 8.65804 6.72064 8.93934 6.43934C9.22064 6.15804 9.60218 6 10 6C10.3978 6 10.7794 6.15804 11.0607 6.43934C11.342 6.72064 11.5 7.10218 11.5 7.5C11.5 7.89782 11.342 8.27936 11.0607 8.56066C10.7794 8.84196 10.3978 9 10 9Z"
                fill="black"
              />
            </svg>
        </button>

        <!-- Le popup pour le formulaire d'inscription -->
        <SignupForm v-if="showModal" @close="showModal = false" />
        

        <button @click="toggleMenu" class="text-black">
          <svg
            class="w-6 h-6"
            fill="none"
            stroke="currentColor"
            viewBox="0 0 24 24"
            xmlns="http://www.w3.org/2000/svg"
          >
            <path
              stroke-linecap="round"
              stroke-linejoin="round"
              stroke-width="2"
              d="M4 6h16M4 12h16M4 18h16"
            ></path>
          </svg>
        </button>
      </div>

      <!-- Menu principal -->
      <div class="hidden md:flex md:items-center md:justify-between w-2/3">
        <ul class="flex space-x-8 font-light">
          <!-- Liens du menu -->
          <li
            :class="{ active: currentPath === '/' }"
            class="flex space-x-2 items-center"
          >
            <svg
              width="20"
              height="18"
              viewBox="0 0 20 18"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
            >
              <path
                d="M10 3.19L15 7.69V15.5H13V9.5H7V15.5H5V7.69L10 3.19ZM10 0.5L0 9.5H3V17.5H9V11.5H11V17.5H17V9.5H20L10 0.5Z"
                fill="black"
              />
            </svg>
            <NuxtLink to="/" class="cursor-pointer hover:text-red-600"
              >Accueil</NuxtLink
            >
          </li>
          <li
            :class="{ active: currentPath === '/Services' }"
            class="flex space-x-2 items-center"
          >
            <svg
              width="20"
              height="18"
              viewBox="0 0 20 21"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
            >
              <path
                d="M9 16.5H11V13.5H14V11.5H11V8.5H9V11.5H6V13.5H9V16.5ZM2 20.5C1.45 20.5 0.979002 20.304 0.587002 19.912C0.195002 19.52 -0.000664969 19.0493 1.69779e-06 18.5V6.5C1.69779e-06 5.95 0.196002 5.479 0.588002 5.087C0.980002 4.695 1.45067 4.49934 2 4.5H6V2.5C6 1.95 6.196 1.479 6.588 1.087C6.98 0.695002 7.45067 0.499335 8 0.500002H12C12.55 0.500002 13.021 0.696002 13.413 1.088C13.805 1.48 14.0007 1.95067 14 2.5V4.5H18C18.55 4.5 19.021 4.696 19.413 5.088C19.805 5.48 20.0007 5.95067 20 6.5V18.5C20 19.05 19.804 19.521 19.412 19.913C19.02 20.305 18.5493 20.5007 18 20.5H2ZM2 18.5H18V6.5H2V18.5ZM8 4.5H12V2.5H8V4.5Z"
                fill="black"
              />
            </svg>
            <NuxtLink to="/Services" class="cursor-pointer hover:text-red-600"
              >Services</NuxtLink
            >
          </li>
          <li
            :class="{ active: currentPath === '/APropos' }"
            class="flex space-x-2 items-center"
          >
            <svg
              width="7"
              height="17"
              viewBox="0 0 7 17"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
            >
              <path
                d="M5.49988 0.5C5.10206 0.5 4.72053 0.658035 4.43922 0.93934C4.15792 1.22064 3.99988 1.60218 3.99988 2C3.99988 2.39782 4.15792 2.77936 4.43922 3.06066C4.72053 3.34196 5.10206 3.5 5.49988 3.5C5.89771 3.5 6.27924 3.34196 6.56054 3.06066C6.84185 2.77936 6.99988 2.39782 6.99988 2C6.99988 1.60218 6.84185 1.22064 6.56054 0.93934C6.27924 0.658035 5.89771 0.5 5.49988 0.5ZM5.13988 5.27C3.94988 5.37 0.699882 7.96 0.699882 7.96C0.499882 8.11 0.559883 8.1 0.719883 8.38C0.879883 8.65 0.859883 8.67 1.04988 8.54C1.24988 8.41 1.57988 8.2 2.12988 7.86C4.24988 6.5 2.46988 9.64 1.55988 14.93C1.19988 17.55 3.55988 16.2 4.16988 15.8C4.76988 15.41 6.37988 14.3 6.53988 14.19C6.75988 14.04 6.59988 13.92 6.42988 13.67C6.30988 13.5 6.18988 13.62 6.18988 13.62C5.53988 14.05 4.34988 14.95 4.18988 14.38C3.99988 13.81 5.21988 9.9 5.88988 7.21C5.99988 6.57 6.29988 5.17 5.13988 5.27Z"
                fill="black"
              />
            </svg>
            <NuxtLink to="/APropos" class="cursor-pointer hover:text-red-600"
              >À propos</NuxtLink
            >
          </li>
        </ul>
        <div class="">
          <LanguageSelector />
        </div>

        <button
          @click="showModal = true"
          class=""
        >
        <svg
              width="20"
              height="20"
              viewBox="0 0 20 20"
              fill="black"
              xmlns="http://www.w3.org/2000/svg"
            >
              <path
                d="M10 0C8.68678 0 7.38642 0.258658 6.17317 0.761205C4.95991 1.26375 3.85752 2.00035 2.92893 2.92893C1.05357 4.8043 0 7.34784 0 10C0 12.6522 1.05357 15.1957 2.92893 17.0711C3.85752 17.9997 4.95991 18.7362 6.17317 19.2388C7.38642 19.7413 8.68678 20 10 20C12.6522 20 15.1957 18.9464 17.0711 17.0711C18.9464 15.1957 20 12.6522 20 10C20 8.68678 19.7413 7.38642 19.2388 6.17317C18.7362 4.95991 17.9997 3.85752 17.0711 2.92893C16.1425 2.00035 15.0401 1.26375 13.8268 0.761205C12.6136 0.258658 11.3132 0 10 0ZM5.07 16.28C5.5 15.38 8.12 14.5 10 14.5C11.88 14.5 14.5 15.38 14.93 16.28C13.5294 17.396 11.7909 18.0026 10 18C8.14 18 6.43 17.36 5.07 16.28ZM16.36 14.83C14.93 13.09 11.46 12.5 10 12.5C8.54 12.5 5.07 13.09 3.64 14.83C2.57618 13.4446 1.99967 11.7467 2 10C2 5.59 5.59 2 10 2C14.41 2 18 5.59 18 10C18 11.82 17.38 13.5 16.36 14.83ZM10 4C8.06 4 6.5 5.56 6.5 7.5C6.5 9.44 8.06 11 10 11C11.94 11 13.5 9.44 13.5 7.5C13.5 5.56 11.94 4 10 4ZM10 9C9.60218 9 9.22064 8.84196 8.93934 8.56066C8.65804 8.27936 8.5 7.89782 8.5 7.5C8.5 7.10218 8.65804 6.72064 8.93934 6.43934C9.22064 6.15804 9.60218 6 10 6C10.3978 6 10.7794 6.15804 11.0607 6.43934C11.342 6.72064 11.5 7.10218 11.5 7.5C11.5 7.89782 11.342 8.27936 11.0607 8.56066C10.7794 8.84196 10.3978 9 10 9Z"
                fill="black"
              />
            </svg>
        </button>

        <!-- Le popup pour le formulaire d'inscription -->
        <SignupForm v-if="showModal" @close="showModal = false" />
        

        <!-- <div class="w-16 flex items-center justify-center">
          <button @click="openModal">
            <Modal v-if="showModal" @close="closeModal" />
            <svg
              width="20"
              height="20"
              viewBox="0 0 20 20"
              fill="black"
              xmlns="http://www.w3.org/2000/svg"
            >
              <path
                d="M10 0C8.68678 0 7.38642 0.258658 6.17317 0.761205C4.95991 1.26375 3.85752 2.00035 2.92893 2.92893C1.05357 4.8043 0 7.34784 0 10C0 12.6522 1.05357 15.1957 2.92893 17.0711C3.85752 17.9997 4.95991 18.7362 6.17317 19.2388C7.38642 19.7413 8.68678 20 10 20C12.6522 20 15.1957 18.9464 17.0711 17.0711C18.9464 15.1957 20 12.6522 20 10C20 8.68678 19.7413 7.38642 19.2388 6.17317C18.7362 4.95991 17.9997 3.85752 17.0711 2.92893C16.1425 2.00035 15.0401 1.26375 13.8268 0.761205C12.6136 0.258658 11.3132 0 10 0ZM5.07 16.28C5.5 15.38 8.12 14.5 10 14.5C11.88 14.5 14.5 15.38 14.93 16.28C13.5294 17.396 11.7909 18.0026 10 18C8.14 18 6.43 17.36 5.07 16.28ZM16.36 14.83C14.93 13.09 11.46 12.5 10 12.5C8.54 12.5 5.07 13.09 3.64 14.83C2.57618 13.4446 1.99967 11.7467 2 10C2 5.59 5.59 2 10 2C14.41 2 18 5.59 18 10C18 11.82 17.38 13.5 16.36 14.83ZM10 4C8.06 4 6.5 5.56 6.5 7.5C6.5 9.44 8.06 11 10 11C11.94 11 13.5 9.44 13.5 7.5C13.5 5.56 11.94 4 10 4ZM10 9C9.60218 9 9.22064 8.84196 8.93934 8.56066C8.65804 8.27936 8.5 7.89782 8.5 7.5C8.5 7.10218 8.65804 6.72064 8.93934 6.43934C9.22064 6.15804 9.60218 6 10 6C10.3978 6 10.7794 6.15804 11.0607 6.43934C11.342 6.72064 11.5 7.10218 11.5 7.5C11.5 7.89782 11.342 8.27936 11.0607 8.56066C10.7794 8.84196 10.3978 9 10 9Z"
                fill="black"
              />
            </svg>
          </button>
        </div> -->
      </div>
    </div>

    <!-- Menu burger (affichage mobile) -->

    <ul
      v-if="showMenu"
      class="md:hidden flex flex-col justify-center place-content-center items-center space-y-2 absolute top-16 right-4 z-20 bg-white p-4 shadow-md rounded-md"
    >
      <!-- Liens du menu -->
      <li :class="{ active: currentPath === '/' }">
        <NuxtLink to="/" class="cursor-pointer">Accueil</NuxtLink>
      </li>
      <li :class="{ active: currentPath === '/Services' }">
        <NuxtLink to="/Services" class="cursor-pointer">Services</NuxtLink>
      </li>
      <li :class="{ active: currentPath === '/APropos' }">
        <NuxtLink to="/APropos" class="cursor-pointer">À propos</NuxtLink>
      </li>
      <LanguageSelector />
    </ul>
  </div>
</template>

<!--    
<script>

export default {
    name: 'IndexPage',
}
</script> -->

<script>
import SignupForm from "../components/SignupForm.vue";

import LanguageSelector from "../components/LanguageSelector.vue";
import Modal from "./Modal.vue";
export default {
  name: "Header",
  data() {
    return {
      showModal: false, // État de la fenêtre modale (pop-up)
      currentPath: "", // Stocke l'URL de la page actuelle
      showMenu: false,
    };
  },
  components: {
    LanguageSelector,
    Modal,
    SignupForm,
  },
  mounted() {
    this.currentPath = this.$route.path; // Récupère l'URL de la page actuelle
  },
  methods: {
    // openModal() {
    //   this.showModal = true; // Afficher la fenêtre modale (pop-up)
    // },
    // closeModal() {
    //   this.showModal = false; // Fermer la fenêtre modale (pop-up)
    // },
    toggleMenu() {
      this.showMenu = !this.showMenu;
    },
    // openLoginModal() {
    //   this.showLoginModal = true; // Afficher la fenêtre modale de connexion
    // },
    // closeLoginModal() {
    //   this.showLoginModal = false; // Fermer la fenêtre modale de connexion
    // },

    //   openModalLogin() {
    //   this.showModal = true; // Ouvrir le Modal
    // },
    // handleScroll() {
    //   this.scrollPosition = window.scrollY;
    // },
  },
};
</script>
<style>
.active {
  /* Styles pour le bouton actif */
  color: red;
}
</style>
