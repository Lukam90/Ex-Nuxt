<script setup></script>

<template>
    <section>
        <h1 class="text-5xl font-bold mt-20">Hello, I'm John Doe!</h1>

        <p class="text-base text-gray-900 p-2 italic">Nuxt Developer</p>
    </section>

    <section class="flex flex-col md:flex-row">
        <div class="md:w-3/4">
            <h2 class="text-3xl font-bold mt-8">My Story</h2>

            <p class="text-lg py-2">Lorem ipsum dolor sit amet consectetur adipisicing elit. A nulla minima cupiditate vitae debitis id, blanditiis velit aperiam illo suscipit.</p>
        
            <p class="text-lg py-2">Lorem ipsum dolor sit amet consectetur adipisicing elit. Recusandae, mollitia, nesciunt laborum neque minima sit quasi facilis consequuntur inventore asperiores adipisci! Alias placeat soluta quibusdam?</p>
        </div>

        <img src="~/assets/images/danvega-avatar.png" alt="" class="w-1/2 md:max-w-sm p-8 mx-auto" />
    </section>

    <section>
        <h2 class="text-3xl font-bold mt-8">Latest Blog Posts</h2>
    </section>
</template>