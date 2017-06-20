<script>
export default {
  name: 'my-functional-button',
  functional: true,
  render(h, context) {
    return h('button', context.data, context.children);
  }
}
</script>

<style scoped>
button {
  color: red;
  border: 1px solid blue;
}
</style>