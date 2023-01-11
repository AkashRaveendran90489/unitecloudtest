<template>
  <!-- <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
    <div class="container-fluid">
      <a class="navbar-brand" href="#"></a>
      <button
        class="navbar-toggler"
        type="button"
        data-bs-toggle="collapse"
        data-bs-target="#navbarNav"
        aria-controls="navbarNav"
        aria-expanded="false"
        aria-label="Toggle navigation"
      >
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ms-md-auto gap-2">
          <li class="nav-item rounded">
            <a class="nav-link active" aria-current="page" href="#"
              ><i class="bi bi-house-fill me-2"></i>Home</a
            >
          </li>
          <li class="nav-item rounded">
            <a class="nav-link" href="#"
              ><i class="bi bi-people-fill me-2"></i>About</a
            >
          </li>
          <li class="nav-item rounded">
            <a class="nav-link" href="#"
              ><i class="bi bi-telephone-fill me-2"></i>Contact</a
            >
          </li>
          <li class="nav-item dropdown rounded">
            <a
              class="nav-link dropdown-toggle"
              href="#"
              id="navbarDropdown"
              role="button"
              data-bs-toggle="dropdown"
              aria-expanded="false"
              ><i class="bi bi-person-fill me-2"></i>Profile</a
            >
            <ul
              class="dropdown-menu dropdown-menu-end"
              aria-labelledby="navbarDropdown"
            >
              <li><a class="dropdown-item" href="#">Account</a></li>
              <li><a class="dropdown-item" href="#">Another action</a></li>
              <li>
                <hr class="dropdown-divider" />
              </li>
              <li><a class="dropdown-item" href="#">Logout</a></li>
            </ul>
          </li>
        </ul>
      </div>
    </div>
  </nav> -->
  <!-- <nav class="navbar navbar-expand-lg px-3">
    <button
      class="navbar-toggler"
      type="button"
      data-toggle="collapse"
      data-target="#navbarNav"
      aria-controls="navbarNav"
      aria-expanded="false"
      aria-label="Toggle navigation"
    >
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarNav">
      <ul class="navbar-nav mr-auto w-100 justify-content-end">
        <li class="nav-item active">
          <a class="nav-link" href="#">Home</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">About</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Contact</a>
        </li>
      </ul>
    </div>
    <button class="btn btn-outline-success my-2 my-sm-0" type="submit">
      Sign Up
    </button>
  </nav> -->
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
          <!-- <button class="mx-3 sign-button" type="submit">
            Sign in/Sign up
          </button> -->
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
  /* margin-right: 10px; */
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
