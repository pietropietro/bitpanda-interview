<template lang="pug">
  #app.todo-app
    div {{ message }}
</template>

<script lang="ts">
import { defineComponent } from '@vue/composition-api';

export default defineComponent({
  name: 'App',
  setup() {
    // utilise todo-bitpanda-server to get data

    return {
      message: 'Todo list should be here',
    };
  },
});
</script>

<style lang="scss">
.todo-app {
  text-align: center;
}
</style>
