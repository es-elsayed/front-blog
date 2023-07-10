<template>
    <router-link class="block p-2 text-white transition-colors duration-300 sm:inline-block sm:px-4 hover:text-primary" :to="to"> {{ label }}</router-link>
</template>
  
  
<script>

export default {
    name: 'NavLink',
    props: {
        to: {
            type: String,
            required: true
        },
        label: {
            type: String,
            required: true
        },
        
    },
    setup() { },
}
</script>