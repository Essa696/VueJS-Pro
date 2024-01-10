
<template>

        <div class="container">

            <Header title="Vue Application" />
            
            <button @click="handleClick" >Get started</button>
        </div>

        <div class="container">

            <Header title="To do list" />

            <button>Add Tasks</button>
        </div>

</template>

<script>

 import Header from "./Header.vue"      

 export default {

    name: "App",
    components: {
        Header
    },
    
 methods: {

    handleClick() {

        console.log("button clicked")

        }

    }
 }    

</script>


<style>
    #app {

        text-align: center;
        color: coral;
        margin-top: 60px;

    }

    .container {

        border: 1px solid;
        padding: 30px;
        max-width: 500px;
        margin: auto;
        margin-top: 20px;
}

    button {

        padding: 10px 20px;
        font-size: 15px;
        background: aquamarine;
        border: none;
        cursor: pointer;
        border-radius: 5px;
}


    

    

</style>