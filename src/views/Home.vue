<template>
<AppHeader/>
<div class="flex flex-row">
    <SideBar/>
    <app-bookmark-list/>
</div>
</template>

<script>
import SideBar from "@/components/Home/SideBar.vue";

export default {
    components: {
        SideBar
    }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
