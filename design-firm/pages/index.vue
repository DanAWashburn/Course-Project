<template>
<section class="container">
  <div class="flex-item">
    <img src="../static/house-one.png" class="first">
    <img src="../static/house-two.png" class="second">
    <img src="../static/house-three.png" class="third">
  </div>
</section>
</template>

<script>

</script>

<style lang="scss">
.flex-item {
    display: flex;
    flex-direction: row;
    flex-wrap: wrap;
    justify-content: space-around;
}

.first {

    animation: fadeIn 0.75s ease-in;
}

.secon {

    animation: fadeIn 1.25s ease-in;
}

.third {

    animation: fadeIn 1.75s ease-in;
}
</style>
