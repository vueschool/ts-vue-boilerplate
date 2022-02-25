<script lang="ts">
import formatRelative from "date-fns/formatRelative";
import { defineComponent } from "vue";
export default defineComponent({
  props: {
    date: { type: Date, required: true },
  },
  computed: {
    formatted() {
      return formatRelative(this.date, Date.now());
    },
  },
});
</script>
<template>
  <div>{{ formatted }}</div>
</template>
