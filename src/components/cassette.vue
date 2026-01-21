<script setup>
import {ref} from 'vue'

</script>

<template>
    <div id="reproductor">
            <div id="cassetr">
                <div id="medio">
                <div id="circulo1"></div>
                <div id="cuadrado"></div>
                <div id="circulo2"></div>
                </div>
            </div>
        </div>
    <div class="botones">
        <div id="replay">⏮</div>
        <div id="pause">⏸</div>
        <div id="rewind">⏭</div>
        <div id="stop">⏹</div>
        <div id="play">▶</div>
          
    </div>
</template>

<style scoped>
    #reproductor {
            width: 300px;
            height: 180px;
            background-color: rgb(255, 211, 251);
            border-radius: 15px;
            display: flex;
            justify-content: center;
            align-items: center;
        }
        #cassetr {
            width: 250px;
            height: 130px;
            background-color: rgb(255, 164, 225);
            border-radius: 10px;
            position: relative;
            display: flex;
            justify-content: space-around;
            align-items: center;
        }
        #circulo1, #circulo2 {
            width: 40px;
            height: 40px;
            background-color: rgba(250, 250, 250, 0.667);
            border-radius: 50%;
            box-shadow: inset 2px 2px 5px rgba(0, 0, 0, 0.2);
            
        }
        #cuadrado {
            width: 60px;
            height: 20px;
            background-color: rgba(250, 250, 250, 0.667);
            box-shadow: inset 2px 2px 5px rgba(0, 0, 0, 0.2);
        }

        #medio {
            display: flex;
            justify-content: space-between;
            align-items: center;
            width: 160px;
            background-color: rgb(255, 211, 251);
            border-radius: 30px;
            padding: 5px;
        }

        .botones {
            display: flex;
            justify-content: space-around;
            align-items: center;
            margin-top: 15px;
        }

        #pause, #stop, #play, #rewind, #replay {
            width: 50px;
            height: 50px;
            background-color: rgb(255, 164, 225);
            border-radius: 20px;
            display: flex;
            padding-bottom: 3px;
            justify-content: center;
            align-items: center;
            font-size: 30px;
            color: white;
            box-shadow: 2px 2px 5px rgba(0, 0, 0, 0.2);
            cursor: pointer;
        }

        
</style>