<template>
  <div id="app">
    <!--Navbar-->
    <nav class="navbar navbar-expand-lg navbar-light bg-info">
        <a class="navbar-brand text-white" href="#">Hacktiv Inventory</a>
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarSupportedContent">
          <ul class="navbar-nav mr-auto">
            <li class="nav-item">
                <a class="nav-link text-white" href="#" tabindex="-1" aria-disabled="true">Login</a>
              </li>
            <li class="nav-item">
              <a class="nav-link text-white" href="#" tabindex="-1" aria-disabled="true">Logout</a>
            </li>
          </ul>
        </div>
      </nav>
    <!--Form Login-->
    <div class="card col-4 mx-auto my-2">
        <img src="./assets/login.jpg" class="card-img-top img-thumbnail " alt="...">
        <div class="card-body d-flex flex-row">
          <form class="col-12" @submit.prevent="login">
            <div class="form-group">
              <label for="email">Email</label>
              <input id="email" type="email" class="form-control" required />
            </div>
            <div class="form-group">
              <label for="caption">Password</label>
              <input id="caption" type="password" class="form-control" required />
            </div>
            <div class="text-center">
              <button type="submit" class="btn btn-info">Submit</button>
            </div>
          </form>
        </div>
      </div>

      <!--Content-->
      <div class=" container">
          <h1>Content</h1>
        <!-- <img alt="Vue logo" src="./assets/logo.png"> -->
        <div class="row justify-content-start">
            <div class="col-4">
                <div class="card mx-auto my-2" style="width: 12rem;">
                <img src="https://ecs7.tokopedia.net/img/cache/700/product-1/2019/9/27/64681733/64681733_2ff55480-4c52-4d1c-9989-59884d391b14_450_450" class="card-img-top" alt="...">
                <div class="card-body card-body ">
                    <h5 class="card-title">Apple Mac Mini 2018 Core i3 SSD 128 GB</h5>
                    <p class="card-text">Quantity: 20</p>
                    <!-- <a href="#" class="btn btn-primary">Go somewhere</a> -->
                </div>
                </div>
            </div>
            <div class="col-4">
                <div class="card mx-auto my-2" style="width: 12rem;">
                <img src="https://ecs7.tokopedia.net/img/cache/700/product-1/2019/9/27/64681733/64681733_2ff55480-4c52-4d1c-9989-59884d391b14_450_450" class="card-img-top" alt="...">
                <div class="card-body card-body ">
                    <h5 class="card-title">Apple Mac Mini 2018 Core i3 SSD 128 GB</h5>
                    <p class="card-text">Quantity: 20</p>
                    <!-- <a href="#" class="btn btn-primary">Go somewhere</a> -->
                </div>
                </div>
            </div>
            <div class="col-4">
                <div class="card mx-auto my-2" style="width: 12rem;">
                <img src="https://ecs7.tokopedia.net/img/cache/700/product-1/2019/9/27/64681733/64681733_2ff55480-4c52-4d1c-9989-59884d391b14_450_450" class="card-img-top" alt="...">
                <div class="card-body card-body ">
                    <h5 class="card-title">Apple Mac Mini 2018 Core i3 SSD 128 GB</h5>
                    <p class="card-text">Quantity: 20</p>
                    <!-- <a href="#" class="btn btn-primary">Go somewhere</a> -->
                </div>
                </div>
            </div>
        </div>
      </div>
    <!-- <router-view/> -->
  </div>
</template>
<script>
export default {

}
</script>

<style>
</style>
