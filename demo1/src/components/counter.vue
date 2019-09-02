<template>
<div>
<button type="submit" @click="add">+</button>
<p> {{message}}</p > 
<button type="submit" @click="minus">-</button>
</div>
<script>


export default {
created:function(){
this.message = 0;
},

methods:{
add:function () {
this.message++;
<!-- document.getElementById("message").value=this.message -->
},
minus:function () {
this.message--;
<!-- document.getElementById("message").value=this.message -->
}
}
}
</script>
<style>

</style>