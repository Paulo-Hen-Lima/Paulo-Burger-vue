<template>
  <picture>
     <source media="(max-width: 2000px)" srcset="/img/burger.jpg">
  <div id="main-banner" >
    <h1>Paulo Burger</h1>
  </div>
</picture>
</template>

<script>
  export default {
    name: "Banner"
  }
</script>
<style scoped>
  #main-banner {
    position: relative;
    height: 50vh; 
    min-width: 320px;
    max-width: 100%;
    display: flex;
    align-items: center;
    justify-content: flex-start; 
    padding: 20px;
    box-sizing: border-box; 
    background-image: url('/img/burger.jpg'); 
    background-position: center;
    background-size: cover; 
    background-repeat: no-repeat; 
  }

  #main-banner h1 {
    color: #FFF;
    font-size: 2rem; 
    background-color: rgba(34, 34, 34, 0.8); 
    padding: 20px 40px;
    text-align: left; 
  }

  @media (max-width: 600px) {
    #main-banner {
      height: 30vh; 
      padding: 10px;
    }

    #main-banner h1 {
      font-size: 1.5rem; 
      padding: 10px 20px;
    }
  }

  @media (min-width: 1200px) {
    #main-banner {
      height: 90vh; 
    }

    #main-banner h1 {
      font-size: 2.5rem; 
      padding: 30px 50px;
    }
  }

  @media (min-width: 3000px) {
    #main-banner {
      height: 70vh; 
    }

    #main-banner h1 {
      font-size: 3rem; 
      padding: 40px 60px;
    }
  }
</style>
