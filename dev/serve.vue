<script>
import Vue from 'vue';
import VueIconPicker from '@/vue-icon-picker.vue';

export default Vue.extend({
  name: 'ServeDev',
  components: {
    VueIconPicker
  }
});
</script>

<template>
  <div id="app">
    <vue-icon-picker />
  </div>
</template>
