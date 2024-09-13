<script>
export default {
  data() {
    return {
      count: 0
    }
  }
}
</script>

<template>
    <div class="jumbotron">
        <div class="jumbotron-text">
            <h1>Dovrei essere un jumbotron</h1>
            <p>non sono capace a immaginarmi un jumbotron perciò ho messo una immagine a caso</p>
        </div>
    </div>
</template>

<style scoped>
.jumbotron{
    border: 2px solid lightgrey;
    height: 500px;
    width: 900px;
    margin: 0 auto;
    background-image: url(../assets/image.jpg);
}
.jumbotron-text{
    text-align: center;
    padding: 20px;
}
</style>