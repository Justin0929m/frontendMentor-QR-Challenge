<template>
  <div class="container">
    <div class="outerBox">
      <div class="innerBox">
        <img src="https://i.postimg.cc/bwb3m7fp/image-qr-code.png" class="qr-img" alt="">
      </div>
      <div class="para">
        <h3 class="title">Improve your front-end <br> skills by building projects</h3>
        <p class="text">Scan the QR code to visit Frontend Mentor and take your coding skills to the next level</p>
      </div>
    </div>
  </div>
</template>

<script setup>

</script>

<style scoped>

img{
  display: block;
  max-width: 100%;
  
}
.container {
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100vh;
}

.outerBox {
  background-color: var(--white);
  border-radius: 10px;
  width: 16rem;
  height: max-content;
  padding: 1rem;
}

.innerBox{
  width: 100%;
  height: 70%;
  border-radius: 10px;
  overflow: hidden;
}

.para{
  text-align: center;
}

.title{
  font-weight: 700;
}

.text{
  font-weight: 400;
}
</style>