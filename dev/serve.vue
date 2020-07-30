<script>
import Vue from 'vue';
import { BaseLoader } from '@/entry';

export default Vue.extend({
  name: 'ServeDev',
  components: {
    BaseLoader,
  }
});
</script>

<template>
  <div id="app">
    <BaseLoader />
  </div>
</template>
