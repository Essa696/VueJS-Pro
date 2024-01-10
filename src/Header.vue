<template>

    <header>

        <h1>{{ title }}</h1>
        
        
    </header>

</template>

<script>

export default {

    name : "Header",
    props : {

        title : String
    }

}

</script>

<style>


button {

    padding: 10px 20px;
    font-size: 15px;
    background: aquamarine;
    border: none;
    cursor: pointer;
    border-radius: 5px;
}

</style>