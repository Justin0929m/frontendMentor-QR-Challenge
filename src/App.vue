<template>
  <div>
    <HelloWorldVue />
  </div>
</template>

<script>
import HelloWorldVue from '@/components/HelloWorld.vue'

export default {
  components: {
    HelloWorldVue
  }
}
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Outfit:wght@400;700&display=swap');

:root{
  --white: hsl(0, 0%, 100%);
  --lightGray: hsl(212, 45%, 89%);
  --grayishBlue: hsl(220, 15%, 55%);
  --darkBlue: hsl(218, 44%, 22%);
}

body{
  background-color: var(--grayishBlue);
  font-family: 'Outfit', sans-serif;
  overflow-y: hidden;
}

p{
  font-size: 15px;
  color: var(--grayishBlue);
}

</style>