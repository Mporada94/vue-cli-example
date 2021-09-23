<template>
    <div>
        <label>Kolor tekstu został zmieniony</label>
    </div>
</template>

<script>
export default {
    props: {
       
    },
    beforeCreate() {
        console.log('beforeCreate');
    },
    created() {
        console.log('created');
    },
    beforeMount() {
        console.log('beforeMount');
    },
    mounted() {
        console.log("mounted");
    },
    // computed: {
    //     console.log("computed");
    // },
    beforeDestroy() {
        console.log('beforeDestroy');
    },
    destroyed() {
        console.log("destroyed");
    },
    methods: {
        
    }
}

</script>

<style scoped>

</style>