<template>
  <footer class="footer">
    <Container>
      <router-link to="/apartments-vue">
        <Logo />
      </router-link>
    </Container>
  </footer>
</template>

<script>
import Container from "./shared/Container.vue";
import Logo from "./Logo.vue";
export default {
  name: "Footer",
  components: {
    Container,
    Logo,
  },
};
</script>

<style lang="scss" scoped>
@import "../assets/scss/variables.scss";

.footer {
  background: $secondary-color;
  height: 30px;
}
</style>
