<script>
export default {
    name: 'AppTitle',
    data() {
        return {
            title: 'Sono la mia prima App con Vite!'
        }
    },
}
</script>

<template>
    <div>
        <h1>{{ title }}</h1>
    </div>

</template>

<style>
h1{
  color: blue;
  text-decoration:underline;
}
</style>