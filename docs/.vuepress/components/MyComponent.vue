<template>
  <div class="number">
      <h1>Hello this is a component</h1>
      <button @click="increment()">+</button>
      <strong>{{value}}</strong>
      <button @click="decrement()">-</button>
  </div>
</template>

<script>
export default {
  props: ['start'],
  data () {
    return {
      value: this.start
    }
  },
  methods: {
    increment() { this.value() },
    decrement() { this.value() }
  }
}
</script>

