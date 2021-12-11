<template>
  <router-link to="/"> <h4>go back</h4></router-link>
  <h2>Thanks for visiting!</h2>
  <form>
    <div class="container">
      <h1>CONTACT</h1>
      <label>rajuprasadp1@gmail.com</label>
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
  background: rgb(49, 190, 68);
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
  text-align: center;
  overflow: auto;
  min-height: 300px;
  border: 1px solid steelblue;
  padding: 30px;
  border-radius: 5px;
}
router-link {
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
</style>
