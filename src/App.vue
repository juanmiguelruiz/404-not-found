<template>
  <div id="app" class="container">
    <Header />
    <Message/>
    <Button/>
    <Footer/>
  </div>
</template>

<script>
import Header from "./components/Header";
import Message from "./components/Message";
import Button from "./components/Button";
import Footer from "./components/Footer";


export default {
  name: "App",
  components: {
    Header,
    Message,
    Button,
    Footer,
  },
};
</script>

<style src="./styles.css"></style>
