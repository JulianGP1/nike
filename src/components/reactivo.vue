<script setup>

    import {ref} from 'vue'
    //console.log('Holaaa')
    //let number = 5  //interpolaciòn de variables 
    let number = ref(5) //hago reactiva la variable 

    //creo la funcion que estoy llamando con el @click:
    function add(){
        number.value++  //usar el value para terminar la reactividad 
        console.log(number)
    }

    function rest(){
        number.value--
        console.log(number)
    }


</script>

<template>
    <div class="max-w-96 bg-purple-300 rounded py-3 px-5 mx-auto">
        <div class="bg-red-400 size-8 flex justify-center items-center rounded-full" v-if="number > 0">
            {{ number }}
        </div>
        <div v-else>
            nadie te escribe 
        </div>
        <div class="flex justify-start items-center">
            <div class="bg-blue-400 size-8 flex justify-center items-center rounded-full" @click="add()">
                +
            </div>
            <div class="bg-blue-400 size-8 flex justify-center items-center rounded-full" @click="rest()">
                -
            </div>

        </div>

        
    </div>

</template>




