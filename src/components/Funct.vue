<template>
<ul>
    <li id="shallow">
        <div></div>
    </li>
    <li id="shallow1"></li>
    <li id="shallow2"></li>
</ul>
</template>

<script lang="ts" setup scoped>

</script>

<style scoped>
ul{
    margin-top: 2px;
   
    display: flex;
    flex-direction: column;
    align-items: center;
}
li{
    list-style-type: none;
}
#shallow1{
    margin-top: 1px;
    width:670px;
    height:6px;
    background-color: white;
    box-shadow: 0 5px 5px rgba(0,0,0,0.10),0 5px 5px rgba(0,0,0,0.10),0 5px 5px rgba(0,0,0,0.10),0 5px 5px rgba(0,0,0,0.10);
}
#shallow2{
    margin-top: 1px;
    width:650px;
    height:6px;
    background-color: white;
    box-shadow: 0 5px 5px rgba(0,0,0,0.10),0 5px 5px rgba(0,0,0,0.10),0 5px 5px rgba(0,0,0,0.10),0 5px 5px rgba(0,0,0,0.10);
}
div{
    background-color: white;
    width: 690px;
    height: 40px;
    display:flex;
    justify-content: space-between;
    align-items: center;
    box-shadow: 0 5px 5px rgba(0,0,0,0.10),0 0px 0px rgba(0,0,0,0.10),0 5px 5px rgba(0,0,0,0.10),0 5px 5px rgba(0,0,0,0.10);
}

</style>