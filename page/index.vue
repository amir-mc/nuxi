<script>
export default {
  computed: {
    counter() {
      return this.$store.state.counter
    }
  },
  methods: {
    increment() {
      this.$store.commit('increment')
    }
  }
}
</script>