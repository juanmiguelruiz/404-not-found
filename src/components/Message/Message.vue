<template>
  <div class="row">
    <div class="col s12">
      <img src="../../assets/Scarecrow.png" alt="image" class="message__img" />
    </div>
    <div class="col s12">
      <p class="message__title">
        I have bad news for you
      </p>
      <p class="message__text">
        The page you are looking for might be removed or is temporarily
        unavailable
      </p>
    </div>
  </div>
</template>

<script>
export default {
  name: "Message",
};
</script>

<style>
.message__img {
  margin: 5% auto;
  width: 100%;
  display: flex;
}

.message__title {
  font-family: Space Mono;
  font-style: normal;
  font-weight: bold;
  font-size: 2.7em;
  line-height: 1.5em;
  letter-spacing: -0.035em;
}

.message__text {
  font-family: Space Mono;
  font-size: 1em;
  font-weight: 200;
  line-height: 1.5em;
  letter-spacing: -0.035em;
}
</style>
