<template>
<li>
    <div>
        <img src="/src/images/cu.png" alt="">
    </div>
<label for="">
    <input type="text" placeholder="What need to be done?">
</label>
</li>
</template>

<script lang="ts" setup >

</script>

<style scoped>
input{
    font-size: 20px;
    outline: none;
    width:640px;
    height:60px;
    border: 0px;
}
input::-webkit-input-placeholder{
    color:#5897be;
    font-style: italic;
    font-size: 20px;
}
li{
    background-color:white ;
    display: flex;
    width: 690px;
    height: 60px;
    box-shadow: 0 0px 0px rgba(0,0,0,0.10),0 5px 5px rgba(0,0,0,0.10),0 5px 5px rgba(0,0,0,0.10),0 5px 5px rgba(0,0,0,0.10);
}
img{
    max-width:30px;
    margin:auto 10px;
}
div{
    display: flex;
    flex-direction: column;
    justify-content: center;
}
</style>