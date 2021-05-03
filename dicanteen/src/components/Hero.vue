<template>
  <div class="hero">
    <!-- desktop -->
    <div class="d-none d-md-block">
      <div class="row mt-5">
        <div class="col-md-6">
          <div class="d-flex h-100">
            <div class="justify-content-center align-self-center">
              <h1>di<strong>Canteen</strong></h1>
              <h4>
                Future Canteen on your hand
              </h4>
              <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Laborum earum nobis iste cumque magnam modi nostrum dolore dolorem architecto quia.</p>
              <router-link class="btn btn-lg btn-danger" to="/foods">Pesan</router-link>
            </div>
          </div>
        </div>
        <div class="col-md-6 bg-warning">
          <img src="../assets/images/hero.png" width="100%" alt />
        </div>
      </div>
    </div>
    <!-- mobile -->
    <div class="d-sm-block d-md-none">
      <div class="row mt-5">
        <div class="col-md-6 mb-3">
          <img src="../assets/images/hero.png" width="100%" alt />
        </div>
        <div class="col-md-6">   
          <div class="d-flex h-100">
            <div class="justify-content-center align-self-center">
              <h1>di<strong>Canteen</strong></h1>
              <h4>
                Future Canteen on your hand
              </h4>
              <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Laborum earum nobis iste cumque magnam modi nostrum dolore dolorem architecto quia.</p>
              <router-link class="btn btn-lg btn-danger" to="/foods">Pesan</router-link>
            </div>
          </div>
        </div>
      </div>
    </div>
     <br><br><br><br><br>
  </div>
 
</template>

<script>
export default {
  name: "Hero",
};
</script>

<style>
</style>