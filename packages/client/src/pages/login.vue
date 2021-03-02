<template>
  <form>
    <img class="logo" src="@/assets/logo.jpg" alt="Open Message" />

    <h3><strong>Sign in to Open Message</strong></h3>

    <p style="margin-bottom:50px">
      <em>Welcome back! Login to access the open message.</em>
    </p>

    <div class="form-group">
      <label>Email address</label>
      <input type="email" class="form-control form-control-lg" />
    </div>

    <div class="form-group">
      <label>Password</label>
      <input type="password" class="form-control form-control-lg" />
    </div>

    <button type="submit" class="btn btn-dark btn-lg btn-block">Sign In</button>

    <p class="forgot-password text-right mt-2 mb-4">
      <router-link to="/forgot-password">Forgot password ?</router-link>
    </p>
  </form>
</template>

<script>
    export default {};
</script>

<style>
body {
  justify-content: center;
  background-image: url("~@/assets/Background-Image.jpg");
  background-repeat: no-repeat;
  background-size: cover;
  background-attachment: fixed;
}

h3 {
  text-align: center;
  color: purple;
  margin-top: 100px;
}
</style>
