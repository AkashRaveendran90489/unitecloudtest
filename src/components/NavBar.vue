<template>
  <div class="col-sm-12 col-md-12 col-xl-12">
    <b-navbar toggleable="md">
      <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

      <b-collapse id="nav-collapse" is-nav class="justify-content-end">
        <b-navbar-nav>
          <b-nav-item href="#">Our Products</b-nav-item
          ><b-nav-item href="#">For Engineers</b-nav-item
          ><b-nav-item href="#">Multi-Vitamins</b-nav-item
          ><b-nav-item href="#">Buy</b-nav-item
          ><b-nav-item href="#">Books</b-nav-item>
        </b-navbar-nav>
        <button class="mx-3 sign-button" type="submit">Sign in/Sign up</button>
      </b-collapse>
    </b-navbar>
  </div>
</template>

<script>
export default {
  name: "ButtonItems",
};
</script>
<style>
.navbar {
  box-shadow: 0px 4px 8px rgba(0, 0, 0, 0.15);
  width: 100%;
  font-size: 15px;
}
.nav-item {
  padding: 5px;
  color: #5a5a5a;
  padding-inline: 10px;
}
.navbar-nav .nav-item:hover {
  border-bottom: 2px solid #f28737;
  font-weight: bold;
}
.sign-button {
  margin: 6px;
  height: 40px;
  width: 150px;
  background-color: #dcdcdc;
  color: #5a5a5a;
  border: none;
  border-radius: 7px;
}
.sign-button:hover {
  background-color: #f28737;
}
</style>
