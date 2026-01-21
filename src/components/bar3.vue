<script setup>
import {ref} from 'vue'

</script>

<template>
<div class="bar">
<button id="black-buttom">.</button>
<div class="bar-comp"> 
    <div id="circle"> .</div>
</div>
<button id="white-buttom">.</button>
<p class="number">125</p>
</div>
</template>

<style scoped>

.bar{
    display: flex;
    flex-direction: column;
    margin: 30px;
    margin: 30px;
}
.bar-comp{
    width: 35%;
    padding: 250px 2px;
    margin: 10px 10px;
    background-color: black;
    border-radius: 20px;
}

#black-buttom{
    border-radius: 60%;
    margin: 10px;
    background-color: rgb(49, 49, 49);
    color: rgb(49, 49, 49);
}

#white-buttom{
    border-radius: 60%;
    margin: 10px;
    background-color: rgb(223, 223, 223);
    color: rgb(223, 223, 223);
}

#circle{
    margin: -7px;
    padding: 3px 3px 2px 2px;
    border-radius: 50%;
    color: rgb(126, 126, 126);
    background: linear-gradient(to bottom, #fdfdfd 0%, #d9d9d9 40%, #555555 100%);
    box-shadow:
    inset 0 2px 4px rgba(255, 255, 255, 0.8), /* reflejo interno arriba */
    inset 0 -2px 4px rgba(0, 0, 0, 0.4),      /* sombra interna abajo */
    0 2px 6px rgba(0, 0, 0, 0.6);             /* sombra externa */
    border: 1px;

}

.number{
    color:grey;
    margin: 0px 0px 12px 12px;
    font-family: 'Courier New', Courier, monospace;
}
</style>