<template>
  <div class="flex items-center">
    <div class="flex w-36 h-44 justify-center items-center">
      <!-- <div><bookCover /></div> -->
      <div><bookImg /></div>
    </div>
  </div>
  <!-- <div class="p-3 my-3 mx-2 bg-white rounded-xl shadow-md">
    <div class="flex w-36 h-44 justify-center items-center">
      <svg xmlns="http://www.w3.org/2000/svg" class="h-14 w-14" fill="none" viewBox="0 0 24 24" stroke="currentColor">
        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 4v16m8-8H4" />
      </svg>
    </div>
  </div> -->
</template>

<script>
import bookImg from "../../assets/book_background.svg";

export default {
  name: "Room",
  props: {},
  components: {
    bookImg,
    // bookCover,
  },
};
</script>
