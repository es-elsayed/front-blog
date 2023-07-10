<template>
    <nav id="navbar" class="z-10 w-full px-4 py-4 bg-white shadow sm:bg-gray-900 sm:shadow-none sm:py-6 sm:fixed">
        <div class="container flex flex-col items-center justify-between mx-auto sm:flex-row ">
            <div class="text-3xl font-bold">
                <span class="sm:text-white">Islam </span>
                <span class="text-primary">Abdu</span>
            </div>
            <div class="w-full mt-4 text-white sm:mt-8 sm:space-x-4 sm:text-right sm:block">
                <nav-link to="/articles"> Articles</nav-link>
                <nav-link to="/about"> about</nav-link>
                <nav-link to="/conatct"> conatct</nav-link>
            </div>
        </div>
    </nav>
</template>
  
  
<script>
 import NavLink from "./NavLink.vue";
export default {
    name: 'NavComponent',
    components:{NavLink},
    props: {},
    setup() { },
}
</script>