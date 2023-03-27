<template>
    <div>
        <h1>Yello {{ name }}</h1>

        <h1 v-for="item of frameworks">{{ item }}</h1>
    </div>
</template>

<script>
export default {
    props: ['name','frameworks']
}
</script>
