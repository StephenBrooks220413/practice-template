<template>
  <div class="home">
    <div class="bg-image">
      <img
        src="https://th.bing.com/th/id/R84ce1e1e3ce799aec8a44f5985967848?rik=3w6ugCC1ImILHA&riu=http%3a%2f%2fi1.wp.com%2fstatic.vectorcharacters.net%2fuploads%2f2016%2f12%2fFunny_Monsters_5.png&ehk=oTvdJ%2bcoMHq7h%2bNwoPX4yx4P6DPKEnT4SlC7jDfYKMY%3d&risl=&pid=ImgRaw"
        class="img-fluid pic"
        alt="Sample"
      />
      <div class="mask" style="background-color: rgba(0, 0, 0, 0.6)">
        <div class="d-flex justify-content-center align-items-center h-100">
          <h1 class="text-white display-4">Monster I.T.</h1>
        </div>
      </div>
    </div>
    <HelloWorld/>
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
