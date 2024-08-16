<template>
  <div id="footer">
    <p>Paulo Burger &copy; 2024</p>
  </div>
</template>

<script>
export default {
  name: "Footer"
}
</script> 

<style scoped>
#footer {
    height: 200px;
    background-color: #222;
    border-top: 4px solid #111;
    color: #fcba03;
    display: flex;
    align-items: center;
    justify-content: center;
    font-size: 16px;
    padding: 10px;
    width: 100%;
    box-sizing: border-box;
    position: relative;
    margin: 0 auto; 
}

@media (max-width: 768px) {
    #footer {
        height: 150px; 
        font-size: 14px; 
    }
}

@media (max-width: 480px) {
    #footer {
        height: 120px; 
        font-size: 12px; 
    }
}
</style>
