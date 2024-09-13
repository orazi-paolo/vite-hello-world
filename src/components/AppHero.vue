<script>
export default {
  data() {
    return {
        message: "Questo è un jumbotron",
      
    }
  }
}
</script>

<template>
    <div class="jumbotron">{{ message }}</div>
</template>

<style scoped>
.jumbotron{
    font-size: 40px;
    background-color: red;
}
</style>