<template>
<div id="app">
  <div class="container">
    <div class="flex-item-standard">
      <h1>design firm</h1>
    </div>
  </div>
  <div class="container">
    <nav class="flex-item2">

        <h5 class="list-inline-item">
          <n-link to="/">Home</n-link>
        </h5>
        <h5 class="list-inline-item">
          <n-link to="/drinks">Drinks</n-link>
        </h5>
        <h5 class="list-inline-item">
          <n-link to="/press">Press</n-link>
        </h5>
        <h5 class="list-inline-item">
          <n-link to="/team">Team</n-link>
        </h5>

    </nav>
  </div>
  <nuxt />
</div>
</template>

<style lang="scss">
//Some of this should be in a master scss file. I put it in the assets folder but it's not importing. Does it need to say @import or something?//
@import url('https://fonts.googleapis.com/css?family=Electrolize|Farro&display=swap');

$darkgrey: #555555;
$title: 'Electrolize', sans-serif;
$standard: 'Farro', sans-serif;

h1 {
    font-size: 500%;
    font-family: $title;
    color: $darkgrey;
}

h5 {
    font-family: $standard;
    color: $darkgrey;
    font-size: 150%;
}
p {
    font-family: $standard;

    color: $darkgrey;
}
//Why isn't the below working?//
n-link:link {
  text-decoration: none;
}

n-link:visited {
  text-decoration: none;
}

n-link{
  color: $darkgrey;
}
.flex-item-standard {
    display: flex;
    flex-direction: column;
    height: 150px;
    justify-content: center;
    align-items: center;
}
.flex-item2 {
    display: flex;
    flex-wrap: wrap;
    min-height: 100px;
    justify-content: space-around;
}

</style>
