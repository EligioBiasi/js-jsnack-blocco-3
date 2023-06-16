<template>
    <div>
        <ul>
            <li v-for="link in LinksContainer">

            </li>
        </ul>
    </div>
</template>
<script>
import NavLink from './NavLink.vue'

export default {
    components:{
        NavLink,
    },
    data(){
        return{
            LinksContainer:[
                {
                    link:1,
                },
                {
                    link:2,
                },
                {
                    link:3,
                },
                {
                    link:4,
                },
                {
                    link:5,
                },
            ]
        }
    }
}
</script>
<style lang="scss" scoped>
    
</style>