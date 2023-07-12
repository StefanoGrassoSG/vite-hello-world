<script>
export default {
  data() {
    return { 

     }
  },
}
</script>

<template>
    <div class="jumbo">
        <img src="../assets/bat.jpg" alt="">
    </div>
</template>

<style scoped>
.jumbo {
    width: 700px;
    height: 600px;
    margin: auto;
}

.jumbo > * {
    object-fit: cover;
    width: 100%;
    height: 100%;
    border-radius: 50%;
}
</style>