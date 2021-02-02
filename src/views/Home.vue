<template>
  <div class="home">
    <div class="bg-image">
      <img
        src="https://images.unsplash.com/photo-1485827404703-89b55fcc595e?ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80"
        class="img-fluid pic"
        alt="Sample"
        width="100%"
      />
      <div class="mask" style="background-color: rgba(0, 0, 0, 0.6)">
        <div class="d-flex justify-content-center align-items-center h-100">
          <h1 class="text-white display-4">Monster I.T.</h1>
        </div>
      </div>
    </div>
    <HelloWorld/>
    <h1 class="display-4">Customer Reviews</h1>
    <i class="fas icon-3 fa-star"></i>
    <i class="fas icon-3 fa-star"></i>
    <i class="fas icon-3 fa-star"></i>
    <i class="fas icon-3 fa-star"></i>
    <i class="fas icon-3 fa-star"></i>
    <br /><br />
    <div class="container">
      <div class="row">
        <div class="col-md-4">
          <div class="card">
            <div class="bg-image hover-overlay ripple" data-mdb-ripple-color="light">
              <img
                src="https://reiblaw.com/wp-content/uploads/2019/05/5-essential-tips-for-starting-your-own-business.jpg"
                class="img-fluid"
                width="330"
                height="300"
              />
              <a href="#!">
                <div class="mask" style="background-color: rgba(251, 251, 251, 0.15)"></div>
              </a>
            </div>
            <div class="card-body">
              <h5 class="card-title">Kee's Cleaning Service</h5>
              <p class="card-text">
                <em>"Monster I.T. provided affordable solutions for my business"</em>
              </p>
              <a href="https://kees-cleaning-service.netlify.app/" target="_blank">Website</a>
            </div>
          </div>
        </div>
        <div class="col-md-4">
          <div class="card">
            <div class="bg-image hover-overlay ripple" data-mdb-ripple-color="light">
              <img
                src="https://reiblaw.com/wp-content/uploads/2019/05/5-essential-tips-for-starting-your-own-business.jpg"
                class="img-fluid"
                width="330"
                height="300"
              />
              <a href="#!">
                <div class="mask" style="background-color: rgba(251, 251, 251, 0.15)"></div>
              </a>
            </div>
            <div class="card-body">
              <h5 class="card-title">Crystal's Decorating Service</h5>
              <p class="card-text">
                <em>"Monster I.T. provided affordable solutions for my business"</em>
              </p>
              <a href="https://www.touchbyme.net" target="_blank">Website</a>
            </div>
          </div>
        </div>
        <div class="col-md-4">
          <div class="card">
            <div class="bg-image hover-overlay ripple" data-mdb-ripple-color="light">
              <img
                src="https://reiblaw.com/wp-content/uploads/2019/05/5-essential-tips-for-starting-your-own-business.jpg"
                class="img-fluid"
                width="330"
                height="300"
              />
              <a href="#!">
                <div class="mask" style="background-color: rgba(251, 251, 251, 0.15)"></div>
              </a>
            </div>
            <div class="card-body">
              <h5 class="card-title">Brooks' Insurance Service</h5>
              <p class="card-text">
                <em>"Monster I.T. provided affordable solutions for my business"</em>
              </p>
              <a href="https://www.brookslifeagency.com" target="_blank">Website</a>
            </div>
          </div>
        </div>
      </div>
    </div>
    <br /><br /><br /><br />
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue';

export default {
  name: 'Home',
  components: {
    HelloWorld,
  },
};
</script>
