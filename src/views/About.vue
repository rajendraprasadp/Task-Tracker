<template>
  <router-link to="/"> go back</router-link>
  <h2>Thanks for visiting!</h2>
  <form>
    <div class="container">
      <label>Suggestions</label>
      <input type="text" placeholder="any suggestions" />
    </div>
  </form>
</template>

<script>
export default {
  name: "About",
  props: {
    text: String,
  },
};
</script>
<style scoped>
h2 {
  text-align: center;
}

label {
  display: inline-block;
  background: rgb(180, 34, 34);
  color: #fff;
  border: none;
  padding: 10px 20px;
  margin: 5px;
  border-radius: 5px;
  cursor: pointer;
  text-decoration: none;
  font-size: 15px;
  font-family: inherit;
  text-align: center;
}

.container {
  max-width: 500px;
  margin: 30px auto;
  overflow: auto;
  min-height: 300px;
  border: 1px solid steelblue;
  padding: 30px;
  border-radius: 5px;
}
</style>
