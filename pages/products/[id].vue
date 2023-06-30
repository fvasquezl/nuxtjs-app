<template>
    <div>
        <p>Products details for {{ id }}</p>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Illum voluptatem quis perferendis. Ea ipsa aperiam qui
            reiciendis inventore harum alias esse commodi voluptate quas at in, sequi eligendi numquam sint.</p>
    </div>
</template>

<script setup>
const { id } = useRoute().params
definePageMeta({
    layout: 'products'
})
</script>

<style lang="scss" scoped></style>