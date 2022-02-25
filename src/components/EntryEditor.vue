<script lang="ts" setup>
import EmojiField from "@/components/EmojiField.vue";
import ArrowCircleRight from "@/assets/icons/arrow-circle-right.svg";
</script>
<template>
  <form class="entry-form" @submit.prevent>
    <textarea placeholder="New Journal Entry for danielkelly_io"></textarea>
    <EmojiField />
    <div class="entry-form-footer">
      <span>0 / 280</span>
      <button>Remember <ArrowCircleRight width="20" /></button>
    </div>
  </form>
</template>
