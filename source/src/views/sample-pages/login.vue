<template lang="html">

  <!-- <section class="login">
    <div class="wrapper d-flex align-items-center auth login-full-bg">
      <div class="row w-100">
        <div class="col-lg-6 mx-auto">
          <div class="auth-form-dark text-left p-5">
            <h2>Login</h2>
            <h4 class="font-weight-light">Hello! let's get started</h4>
            <form class="pt-5">
              <form>
                <div class="form-group">
                  <label for="exampleInputEmail1">Username</label>
                  <input type="email" class="form-control" id="exampleInputEmail1" aria-describedby="emailHelp" placeholder="Username">
                  <i class="mdi mdi-account"></i>
                </div>
                <div class="form-group">
                  <label for="exampleInputPassword1">Password</label>
                  <input type="password" class="form-control" id="exampleInputPassword1" placeholder="Password">
                  <i class="mdi mdi-eye"></i>
                </div>
                <div class="mt-5">
                  <router-link class="btn btn-block btn-warning btn-lg font-weight-medium" to="/">Login</router-link>
                </div>
                <div class="mt-3 text-center">
                  <a href="#" class="auth-link text-white">Forgot password?</a>
                </div>
              </form>
            </form>
          </div>
        </div>
      </div>
    </div>
  </section> -->

  <div class="container-scroller">
    <div class="container-fluid page-body-wrapper full-page-wrapper auth-page">
      <div class="content-wrapper d-flex align-items-center auth auth-bg-1 theme-one">
        <div class="row w-100">
          <div class="col-lg-4 mx-auto">
            <div class="auto-form-wrapper">
              <form action="#">
                <div class="form-group">
                  <label class="label">Username</label>
                  <div class="input-group">
                    <input type="text" class="form-control" placeholder="Username">
                    <div class="input-group-append">
                      <span class="input-group-text">
                        <i class="mdi mdi-check-circle-outline"></i>
                      </span>
                    </div>
                  </div>
                </div>
                <div class="form-group">
                  <label class="label">Password</label>
                  <div class="input-group">
                    <input type="password" class="form-control" placeholder="*********">
                    <div class="input-group-append">
                      <span class="input-group-text">
                        <i class="mdi mdi-check-circle-outline"></i>
                      </span>
                    </div>
                  </div>
                </div>
                <div class="form-group">
                  <button class="btn btn-primary submit-btn btn-block">Login</button>
                </div>
                <div class="form-group d-flex justify-content-between">
                  <div class="form-check form-check-flat mt-0">
                    <label class="form-check-label">
                      <input type="checkbox" class="form-check-input" checked=""> Keep me signed in
                    <i class="input-helper"></i></label>
                  </div>
                  <a href="#" class="text-small forgot-password text-black">Forgot Password</a>
                </div>
                <div class="form-group">
                  <button class="btn btn-block g-login">
                    <!-- <img class="mr-3" src="../../images/file-icons/icon-google.svg" alt="">Log in with Google -->
                  </button>
                </div>
                <div class="text-block text-center my-3">
                  <span class="text-small font-weight-semibold">Not a member ?</span>
                  <a href="register.html" class="text-black text-small">Create new account</a>
                </div>
              </form>
            </div>
            <ul class="auth-footer">
              <li>
                <a href="#">Conditions</a>
              </li>
              <li>
                <a href="#">Help</a>
              </li>
              <li>
                <a href="#">Terms</a>
              </li>
            </ul>
            <p class="footer-text text-center">copyright © 2018 Bootstrapdash. All rights reserved.</p>
          </div>
        </div>
      </div>
      <!-- content-wrapper ends -->
    </div>
    <!-- page-body-wrapper ends -->
  </div>

</template>

<script lang="js">
export default {
  name: 'login'
}
</script>

<style scoped lang="scss">
.login {

}
</style>
