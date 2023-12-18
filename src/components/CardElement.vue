<template>
  <article>
    <img :src="imageSrc" alt="">
    <p>
        {{ serie }}
    </p>
  </article>
</template>

<script>
export default {
    name: 'PastaElement',
    // props: [
    //     'imageSrc',
    //     'title',
    //     'type',
    //     'cookingTime'
    // ]
    props: {
        imageSrc : {
            type: String,
            required: true
        },
        serie : String,
    }
}
</script>

<style>

</style>