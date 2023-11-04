<template>
    <div class="container mx-auto w-1/2 py-8">
        <Title>{{ $route.params.id }} | {{ title }}</Title>
        <h3 class="text-3xl font-bold">
            <nuxt-link :to="`posts/1`">Post Title</nuxt-link> 
        </h3>
        <div class="post-meta text-gray-700 flex items-center space-x-2">
            <div>Feb 2, 2022</div>
            <div>&middot;</div>
            <div>Ronaldo</div>
        </div>
    
        <div class="post-content mt-5">
            <p class="text-center">{{ $route.params.id }} Lorem ipsum dolor sit amet consectetur adipisicing elit. Laudantium explicabo vitae deserunt? Quae odit ad maxime veniam accusantium dignissimos ratione fugit saepe,
            voluptates eveniet reprehenderit. Voluptatem, dolorum? Ipsa, harum consequuntur?</p>
        </div>
    </div>
</template>

<script setup>

</script>

<style lang="scss" scoped>

</style>