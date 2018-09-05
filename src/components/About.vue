<template>
    <div class="about">
        <h1>hello {{their_name}}, This is an about page </h1>
        <p>Lorem ipsum dolor sit amet, consectetur adipisicing edit, seddo eiusmod tempor i</p>
    </div>
</template>

<script>
    export default {
        name: 'Skills',
        data(){
            return {
                their_name: this.$route.params.name
            }
        }
    }
</script>