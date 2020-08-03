<template>
    <h1>{{title}}</h1>
</template>

<script>
export default ({
    data() {
        return {
            title: 'All Books',
        };
    },
    name: 'BookList',
});
</script>


<style scoped>
h1, h2 {
    font-weight: normal;
}
</style>