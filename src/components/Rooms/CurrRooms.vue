<template>
  <div class="flex flex-row mt-5 justify-between items-baseline">
    <div class="flex flex-row items-baseline">
      <SymbolIcon class="mr-1" />
      <span class="text-lg font-bold text-black">진행중인 추억들이에요</span>
    </div>
    <span class="text-sm">더보기</span>
  </div>
  <!-- <div class="overflow-x-auto flex flex-row h-56 ml-1">
    <Room v-on:click="goto('Board')"></Room>
    <Room v-on:click="goto('Board')"></Room>
    <AddRoom></AddRoom>
  </div> -->

  <div class="flex flex-row h-48 ml-1 mb-5 mt-3">
    <swiper
      :slidesPerView="2"
      :freeMode="false"
      :spaceBetween="3"
      :scrollbar="{
        hide: true,
      }"
      class="mySwiper"
    >
      <swiper-slide><Room v-on:click="goto('Board')" /></swiper-slide>
      <swiper-slide><Room v-on:click="goto('Board')" /></swiper-slide>
      <swiper-slide><AddRoom /></swiper-slide>
    </swiper>
  </div>
</template>

<script>
import { Swiper, SwiperSlide } from "swiper/vue";
import SwiperCore, { Scrollbar } from "swiper/core";
import "swiper/swiper.scss";

import "swiper/components/pagination/pagination.min.css";
import "swiper/components/scrollbar/scrollbar.min.css";

import SymbolIcon from "../../assets/title_symbol_1.svg";
import Room from "./Room.vue";
import AddRoom from "./AddRoom.vue";

SwiperCore.use([Scrollbar]);

export default {
  name: "CurrRooms",
  components: {
    Swiper,
    SwiperSlide,
    Room,
    AddRoom,
    SymbolIcon,
  },
  props: {},
  methods: {
    goto(page) {
      this.$router.push(page);
    },
  },
};
</script>
