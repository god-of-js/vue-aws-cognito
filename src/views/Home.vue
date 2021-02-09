<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png" />
    <form>
      <input placeholder="Email" />
      <input placeholder="Name" />
      <input placeholder="Password" />
      <button>Register</button>
    </form>
  </div>
</template>

<script>
// @ is an alias to /src

export default {
  name: "Home",
  components: {},
  methods: {
  }
};
</script>
<style lang="scss" scoped>
@import "../assets/styles/style.scss";
form {
  width: 30%;
  margin: auto;
  margin-top: 20px;
  input {
    width: 95%;
    outline: none;
    background-color: white;
    border: transparent;
    @include box-shadow();
    padding: 10px;
    height: 28px;
    border-radius: 5px;
    margin-top: 20px;
  }
  button {
    width: 100%;
    padding: 10px;
    height: 45px;
    border-radius: 5px;
    margin-top: 20px;
    outline: none;
    border: transparent;
    cursor: pointer;
  }
}
</style>
