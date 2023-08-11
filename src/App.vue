<template>
  <ul>
    <li></li>
  </ul>
</template>

<script>
import { VueElement } from "vue";

export default {
  data() {
    return {
      storedResourses: [
        {
          id: "official-guide",
          title: "Official Guide",
          description: "The official VueElement.js documentation.",
          link: 'https://vuejs.org'
        },
        {
          id: "google",
          title: "Google",
          description: "Learn to google",
          link: 'https://google.org'
        },
      ],
    };
  },
};
</script>
