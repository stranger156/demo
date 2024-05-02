<template>
<div class="father">
<Header />
<Body />
<Footer />
</div> 
</template>

<script lang="ts" setup scoped>
import Header from "./components/Header.vue"
import Footer from "./components/Footer.vue"
import Body from "/src/Body.vue"

</script>

<style>
.father{
    display:flex;
    flex-direction:column;
    justify-items: flex-start;
    align-items: center;
/*     min-width:900px; */
}
*{
  margin: 0;
  padding: 0;
}
body {
  background:#f5f5f5;
}
</style>
