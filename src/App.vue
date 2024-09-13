<script>
import AppTitle from "./components/AppTitle.vue";
import AppHero from "./components/AppHero.vue";
 
export default {
    components:{
        AppTitle,
        AppHero
    },
    data() {
        return {
        }
    }
}
</script>

<template>
    <div>
        <AppTitle/>
        <AppHero/>
    </div>
</template>

<style scoped>

</style>
