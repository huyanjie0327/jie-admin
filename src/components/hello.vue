<template>
    <div>hello, {{count}}</div>
</template>

<script>
export default { 
    computed: {
        count() {
            return this.$store.state.count;
        }
    }
}
</script>
