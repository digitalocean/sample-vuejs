<template>
  <div id="app" class="bg-green-600 py-56 min-h-screen">
    <div class="container mx-auto text-center px-8">
      <h2 class="text-3xl lg:text-6xl font-bold mb-2 text-white">Welcome to Your Vue App</h2>
      <h3 class="text-xl lg:text-4xl text-green-200">
        Deployed to
        <span
          class="font-bold bg-clip-text text-transparent bg-gradient-to-br from-blue-400 via-purple-400 to-blue-500"
        >DigitalOcean</span>
      </h3>

      <div class="flex justify-center space-x-2 mt-6 lg:mt-10">
       
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "App",
};
</script>

<style>
#app {
  background-color: #268351;
  background-image: url("data:image/svg+xml,%3Csvg width='60' height='60' viewBox='0 0 60 60' xmlns='http://www.w3.org/2000/svg'%3E%3Cg fill='none' fill-rule='evenodd'%3E%3Cg fill='%232c945c' fill-opacity='0.4'%3E%3Cpath d='M36 34v-4h-2v4h-4v2h4v4h2v-4h4v-2h-4zm0-30V0h-2v4h-4v2h4v4h2V6h4V4h-4zM6 34v-4H4v4H0v2h4v4h2v-4h4v-2H6zM6 4V0H4v4H0v2h4v4h2V6h4V4H6z'/%3E%3C/g%3E%3C/g%3E%3C/svg%3E");
}
</style>
