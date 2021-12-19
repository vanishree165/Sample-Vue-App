<template>
  <div class="container-fluid p-0">
    <div class="row">
      <div class="col-md-6">
        <img src="../assets/banner-img.jpg" class="banner-img" />
      </div>
      <div class="col-md-6 p-3 p-md-5">
        <div class="container-fluid">
          <h1 class="mb-4">Restaurant App</h1>
          <ul class="nav nav-tabs" id="myTab" role="tablist">
            <li class="nav-item" role="presentation">
              <button
                class="nav-link active"
                id="home-tab"
                data-bs-toggle="tab"
                data-bs-target="#home"
                type="button"
                role="tab"
                aria-controls="home"
                aria-selected="true"
              >
                LOGIN
              </button>
            </li>
            <li class="nav-item" role="presentation">
              <button
                class="nav-link"
                id="profile-tab"
                data-bs-toggle="tab"
                data-bs-target="#profile"
                type="button"
                role="tab"
                aria-controls="profile"
                aria-selected="false"
              >
                REGISTER
              </button>
            </li>
          </ul>
          <div class="tab-content mt-4" id="myTabContent">
            <div
              class="tab-pane fade show active"
              id="home"
              role="tabpanel"
              aria-labelledby="home-tab"
            >
             <Login />
            </div>
            <div
              class="tab-pane fade"
              id="profile"
              role="tabpanel"
              aria-labelledby="profile-tab"
            >
              <Register />
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
import Login from"./Login.vue";
import Register from "./Register.vue";
export default {
  name: "LandingPage",
  components: {
    Login,
    Register
  }
};
</script>
