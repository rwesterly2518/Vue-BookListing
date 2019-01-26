<template>
    <li>{{book.title}}:{{book.author}}</li> 
</template>

<script>
export default {
    name: 'BookItem',
    props: ['book']
  }
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
li{
    display: block;
    margin: 0 10px;
    font-family: Arial;
    font-style: italic;
}

</style>
