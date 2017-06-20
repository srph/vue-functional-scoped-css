<template>
  <div id="app">
    <my-button>Swag</my-button>
    <my-functional-button>No Swag</my-functional-button>
  </div>
</template>

<script>
import MyButton from './MyButton.vue';
import MyFunctionalButton from './MyFunctionalButton.vue';

export default {
  name: 'app',
  data() {
    return {
      swag: true
    };
  },
  components: {
    MyButton,
    MyFunctionalButton
  }
}
</script>