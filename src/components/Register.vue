<template>
  <div class="row">
    <div class="col-12">
      <form>
      <div class="form-group">
          <label for="exampleInputName">Name</label>
          <input
            type="text"
            class="form-control"
            id="exampleInputName"
            aria-describedby="nameHelp"
            placeholder="Enter name"
          />
        </div>
        <div class="form-group">
          <label for="exampleInputEmail1">Email address</label>
          <input
            type="email"
            class="form-control"
            id="exampleInputEmail1"
            aria-describedby="emailHelp"
            placeholder="Enter email"
          />
        </div>
        <div class="form-group">
          <label for="exampleInputPassword1">Password</label>
          <input
            type="password"
            class="form-control"
            id="exampleInputPassword1"
            placeholder="Password"
          />
        </div>
        <button type="submit" class="btn btn-primary">Register</button>
      </form>
    </div>
  </div>
</template>
<script>
export default {
  name: "Register",
};
</script>