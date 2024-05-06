<template>
  <div class="">
    <!-- <img alt="Vue logo" src="../assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/> -->
    <div class="p-6 max-w-sm mx-auto bg-gray-500 rounded-xl shadow-lg  items-center ">
      <div>
        <div class="text-xl font-medium text-black">ChitCha</div>
        <p class="text-myclolor">You have a new message!</p>
      </div>
    </div>

    <div class="lg:text-myclolor md:bg-gray-500">
      <button class="btn-blue">hello hello</button>
    </div>

    <!-- aspect-{ratio} -->
    <div class="flex">
      <div class="w-60 h-96 border">
        <div class="aspect-square bg-red-500"></div>
      </div>
      <div class="w-60 h-96 border">
        <div class="aspect-[2/1] bg-red-500"></div>
      </div>
      <div class="w-60 h-96 border">
        <div class="aspect-[2/3] bg-red-500"></div>
      </div>
    </div>
    
    
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'HomeView',
  components: {
    // HelloWorld
  },
  data() {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  },
  created() {
    console.log('created')
  },
  mounted() {
    console.log(process.env.NODE_ENV)
  },
  methods: {
    methods() {
      console.log('methods')
    }
  }
}
</script>