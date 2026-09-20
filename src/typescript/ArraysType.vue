
<script setup lang="ts">

const numeriArray: number[] = [0, 1, 2, 3, 4, 5]

//console.log(numeriArray.length);

const cadena: string = numeriArray.join("---")

//console.log(cadena);

numeriArray.push(6)
//console.log(numeriArray);
// const numeriArray2 = [... numeriArray ]

const numeriArray2: (number | string)[] = [... numeriArray ]

numeriArray2.push(7)
numeriArray2.push('888')


</script>


<template>
    <div>
        <h2>Listas - Arrays</h2>
        <p>{{ numeriArray.join(", ") }}</p>
        <p>{{ numeriArray2.join(", ") }}</p>
    </div>
</template>


<style scoped>

</style>