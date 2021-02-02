<template>
  <div class="container">
    <br /><br /><br />
    <!-- heading text -->
    <h1 class="text-center display-4">Services Offered</h1>
    <br>
    <div class="container">
      <div class="row">
        <div class="col-md-4">
          <br /><br />
          <div class="card hover-shadow">
            <i class="fab icon fa-connectdevelop"></i>
            <h2>Web Design</h2>
            <hr class="length" />
            <ul>
              <li>Vue.js</li> <br />
              <li>React.js</li> <br />
              <li>MDB5</li> <br />
              <li>Material Design</li>
            </ul>
            <br /><br />
            <button type="button" class="btn btn-light">
              <h5>Learn More</h5>
            </button>
          </div>
        </div>
        <div class="col-md-4">
          <br /><br />
          <div class="card hover-shadow">
            <i class="fas icon fa-tools"></i>
            <h2>Maintenance</h2>
            <hr class="length" />
            <ul>
              <li>Fix Vulnerabilities</li>
              <li>Manage Hosting</li>
              <li>Secure Messaging</li>
              <li>Fix Broken Pages</li>
            </ul>
            <br /><br />
            <button type="button" class="btn btn-light">
              <h5>Learn More</h5>
            </button>
          </div>
        </div>
        <div class="col-md-4">
          <br /><br />
          <div class="card hover-shadow">
            <i class="far icon fa-calendar-alt"></i>
            <h2>Scheduling</h2>
            <hr class="length" />
            <ul>
              <li>Consumer Booking</li>
              <li>Support Booking</li>
              <li>Selectable Meetings</li>
              <li>Optional Personnel</li>
            </ul>
            <br /><br />
            <button type="button" class="btn btn-light">
              <h5>Learn More</h5>
            </button>
          </div>
        </div>
      </div>
    </div>
    <!-- end of heading-text -->
    <br /><br /><br />
    <!-- content -->
    <div class="container-fluid">
      <div class="row">
        <div class="col-md-6">
          <img
            src="https://images.unsplash.com/photo-1485827404703-89b55fcc595e?ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&ixlib=rb-1.2.1&auto=format&fit=crop&w=1050&q=80"
            class="img-fluid shadow-2-strong"
            alt=""
          />
        </div>
        <div class="col-md-6">
          <h1>Monster I.T.</h1>
          <p>
            Welcome to Monster I.T., where we make the biggest problems our solution.
            Setting us apart from the rest, we have developed our own way from fixing
            issues to building web sites.
            <br /> <br />
            Growing Since 2017, we marked our place in the Computer Science World. Let's
            chat today to see how we can help you or become your I.T. provider.
          </p>
        </div>
      </div>
      <br /><br />
      <div class="row">
        <div class="col-md-6">
          <h1>Development</h1>
          <p>
            Carefully constructed and with up-to-date technologies, we make your site
            personal. We design each font, background-color, embed JavaScript, and the
            effects to make your site consumer friendly.
            <br /> <br />
            We can utilize easy migrations for those needed to build and manage on their
            own, or we can manage it. Our customer service is superior and always eager
            to help with all of your questions.
          </p>
        </div>
        <div class="col-md-6">
          <img
            src="https://images.unsplash.com/photo-1580894742597-87bc8789db3d?ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&ixlib=rb-1.2.1&auto=format&fit=crop&w=1050&q=80"
            class="img-fluid shadow-2-strong"
            alt=""
          />
        </div>
      </div>
    </div>
    <!-- end of content -->
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
