<template>
<form >
    <div>
        <img src="/src/images/cu.png" alt="">
    </div>
<label for="">
    <input type="text" placeholder="What need to be done?">
</label>
</form>
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
form{
    background-color:white ;
    display: flex;
    margin: 2px;
    width: 690px;
    height: 60px;
    box-shadow: 0 0px 0px rgba(0,0,0,0.10),0 5px 5px rgba(0,0,0,0.10),0 5px 5px rgba(0,0,0,0.10),0 5px 5px rgba(0,0,0,0.10);
}
input::-webkit-input-placeholder{
    color:#5897be;
    font-style: italic;
    font-size: 20px;
}
div{
    display: flex;
    flex-direction: column;
    justify-content: center;
}
img{
    max-width:30px;
    margin:auto 10px;
}
</style>