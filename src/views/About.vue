<template>
 <div>
     <h1>About {{id}}</h1>
 </div>
</template>
<script>
export default {
    props: {
        id:{
            type: Number,
            default: 0,
        }
    }
}</script>