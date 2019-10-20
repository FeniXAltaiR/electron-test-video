<template>
  <div>
    <video controls src="@/assets/XcQ.mp4" poster="@/assets/logo.png">
       Элемент video не поддерживается вашим браузером.
    </video>
  </div>
</template>

<script>
  export default {
    name: 'landing-page',
  };
</script>

<style>
  @import url('https://fonts.googleapis.com/css?family=Source+Sans+Pro');

  * {
    box-sizing: border-box;
    margin: 0;
    padding: 0;
  }

  video {
    width: 100vw;
    height: 100vh;
  }
</style>
