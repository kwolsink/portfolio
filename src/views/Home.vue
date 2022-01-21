<template>
  <div class="home">
    <div class="introduction section">
      <p>
        Welcome to my online portfolio! My name is Kasper Wolsink and here I try to show off the progress I book during
        my time as a software developer!
      </p>
    </div>
    <div class="spacer layer1"></div>

    <div class="section">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Ab accusamus amet autem, cum
      doloribus ea earum eos explicabo fugiat fugit id laboriosam libero nemo nihil quia repellendus sapiente sequi
      soluta.
    </div>
    <div class="section">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Ab accusamus amet autem, cum
      doloribus ea earum eos explicabo fugiat fugit id laboriosam libero nemo nihil quia repellendus sapiente sequi
      soluta.
    </div>
  </div>
</template>

<script>


export default {
  name: 'Home',
  components: {}
}
</script>

<style lang="scss">

.introduction {
  color: white;
  background: #ca69fa;
  font-weight: 900;
}

.section {
  position: relative;
  display: flex;
  flex-direction: column;
  align-items: center;
  padding: 100px 20vw
}

.spacer {
  aspect-ratio: 900/150;
  width: 100%;
  background-repeat: no-repeat;
  background-position: center;
  background-size: cover;
}

.layer1 {
  background-image: url("../assets/layer1.svg");
}


</style>
