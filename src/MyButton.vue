<script>
export default {
  name: 'my-button',
  render(h) {
    return h('button', this.$vnode.data.attrs, this.$slots.default);
  }
}
</script>

<style scoped>
button {
  color: red;
  border: 1px solid blue;
}
</style>