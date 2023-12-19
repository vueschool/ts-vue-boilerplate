<script lang="ts">
// @ts-ignore this works fine
import { formatRelative } from "date-fns";
import { defineComponent } from "vue";
export default defineComponent({
  props: {
    date: { type: Date, required: true },
  },
  computed: {
    formatted() {
      // @ts-ignore this works fine
      return formatRelative(this.date, Date.now());
    },
  },
});
</script>
<template>
  <div>{{ formatted }}</div>
</template>
