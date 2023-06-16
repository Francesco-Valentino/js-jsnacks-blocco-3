<template lang="">
    <div>
        
    </div>
</template>

<script>
import NavLink from './NavLink.vue';

export default {
    components: {
        NavLink,
    },

    data(){
        links: [
            "Products",
            "Pippi",
            "Giustino",
            "San Pio da Pietralcina",
            "Er Pupone"
        ]
    },

    name: "AppHeader",    
}
</script>

<style lang="">
    
</style>