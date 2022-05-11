<script>
import { defineComponent } from 'vue';
import Vue3BasicAutocomplete from '@/vue3-basic-autocomplete.vue';

export default defineComponent({
  name: 'ServeDev',
  components: {
    Vue3BasicAutocomplete
  }
});
</script>

<template>
  <div id="app">
    <vue3-basic-autocomplete />
  </div>
</template>
