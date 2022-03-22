<script>
import SciHub from "./components/SciHub.vue";

export default {
    data() {
        return {
            query: ""
        };
    },
    methods: {
        onSearch() {
            console.log(this.query);
        }
    },
    computed: {
    },
    watch: {
    },
    components: { SciHub }
}


</script>

<template>
<SciHub />
</template>