<template>
    <div>
        <h2>{{msg}}</h2>
    </div>
</template>

<script>
export default {
    name: "ComeOn",
    props: {
        msg: String
    }
}
</script>

<style scoped>
h2{
    margin: 40px 0 0;
}
</style>


