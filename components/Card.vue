<template>
  <div class="drop-shadow mt-6 flex items-center justify-center">
    <div class="max-w-sm rounded overflow-hidden shadow-lg">
      <img
        class="w-full"
        src="https://i0.wp.com/resepkoki.id/wp-content/uploads/2017/01/Sunny-side-up.jpg?fit=500%2C333&ssl=1"
        alt="Sunset in the mountains"
      />
      <div class="px-6 py-4">
        <div class="font-bold text-xl mb-2">{{ nama }}</div>
        <p class="text-gray-700 text-base">{{ deskripsi }}</p>
      </div>
      <div class="px-6 pt-4 pb-2">
        <span
          class="inline-block bg-gray-200 rounded-full px-3 py-1 text-sm font-semibold text-gray-700 mr-2 mb-2"
          >#masakanrumahan</span
        >
        <span
          class="inline-block bg-gray-200 rounded-full px-3 py-1 text-sm font-semibold text-gray-700 mr-2 mb-2"
          >#simple</span
        >
        <span
          class="inline-block bg-gray-200 rounded-full px-3 py-1 text-sm font-semibold text-gray-700 mr-2 mb-2"
          >#semuabisa</span
        >
      </div>
    </div>
    <slot />
  </div>
</template>

<script setup>
export default {
  props: {
    nama: {
      type: String,
      default: "Nama masakan",
    },
    deskripsi: {
      type: String,
      default: "Deskripsi Makanan",
    },
  },
};
</script>