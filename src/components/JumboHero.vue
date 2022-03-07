<template>
  <div class="jumbo">
    <h2>Questo è il jumbo</h2>
  </div>
</template>

<script>
export default {
  name: "JumboHero"
}
</script>


<style scoped>



.jumbo{
  background-image: url("https://picsum.photos/2000/400");
  height: 500px;
  background-size: cover;
  position: relative;
}

h2{
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  color: white;
  text-transform: uppercase;
}
</style>