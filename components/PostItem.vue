<template>
    <div class="post-container py-8">
        <h3 class="text-3xl font-bold">
            <nuxt-link :to="`posts/1`">Post Title</nuxt-link> 
        </h3>
        <div class="post-meta text-gray-700  items-center space-x-2">
            <div>Feb 2, 2022</div>
            <div>&middot;</div>
            <div>Ronaldo</div>
            <div class="post-review leading-relaxed mt-5">
                Lorem ipsum dolor sit amet consectetur adipisicing elit. Laudantium explicabo vitae deserunt? Quae odit ad maxime veniam accusantium dignissimos ratione fugit saepe,
                 voluptates eveniet reprehenderit. Voluptatem, dolorum? Ipsa, harum consequuntur
            </div>
            <div class="mt-5">
                <nuxt-link :to="`posts/1`" class="bg-blue-700 hover:bg-blue-800 text-white rounded inline-block px-4 py-2">
                    Read More
                </nuxt-link>
            </div>
        </div>
    </div>
</template>

<script setup>

</script>

<style lang="scss" scoped>

</style>