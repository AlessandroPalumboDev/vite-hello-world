<script>
export default{
    name: 'AppHero',
    data(){
        return{
            sottotitolo:'JUMBOTRON',
        };
    },
}
</script>

<template>
<div>
    <h2>{{ sottotitolo }}</h2>
</div>

</template>

<style>
h2{
    color: green;
    text-decoration: overline;
}
</style>