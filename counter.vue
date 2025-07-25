<script>
  export default {
    data() {
        return {count: 0}
    },
    methods: {
        inc() {this.count++}
    }
  }
</script>

<template>

    <h1>{{ count }}</h1>
    <button @click="inc">+1</button>
</template>

