<template>
    <div class="home bg-gray-100 w-full h-screen p-12  flex flex-col justify-center items-center ">
        <img class="h-64 w-full object-cover" src="https://source.unsplash.com/random" alt="">
        <div class="flex flex-col items-center bg-gray-300 w-1/3 p-10 text-black rounded-xl shadow-xl -mt-24">
            <img class="h-64 w-64 rounded-full object-cover" src="https://source.unsplash.com/random" alt="">
            <h5 class="text-2xl font-semibold mt-4">Image information</h5>
            <p class="text-center mt-4"><span class="text-indigo-900 font-black">Lorem ipsum</span>, dolor sit amet consectetur adipisicing elit. Labore voluptate quos unde ad molestiae, eveniet consequuntur eligendi quae suscipit assumenda, ipsum asperiores iste aliquid magni repudiandae laborum perferendis omnis consequatur!</p>
        </div>
    </div>
</template>
<script>
// @ is an alias to /src

export default {
    name: 'Home',
    components: {}
}
</script>