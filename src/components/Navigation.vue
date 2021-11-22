<template>
    <nav class="c-nav" v-if="showNavigation">
        <ul class="c-nav-list">
        <li class="c-nav-list-item" v-for="(link, index) in links" v-bind:key="index">
             {{link}} 
        </li>
        </ul>
    </nav>
</template>

<script>
export default{
    name: 'Navigation',
    data(){
        return{
            showNavigation: true,
            links:[
                "home",
                "shop",
                "contact"
            ]
        }
    }
}
</script>