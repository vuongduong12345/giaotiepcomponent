<template>
    <div>
        <h1>{{test}}</h1>
        <h1>{{title}}</h1>
        
    </div>
</template>
<script>
export default {
    props: {
        title: String
    },
    data(){
        return {
            test:'toi là thăng con'
        }
    }
    
}
</script>
<style>

</style>