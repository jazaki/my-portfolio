<template>
    <headroom>
        <header>
            HAHAHHAHA
        </header>
  </headroom>
</template>

<script>
import { headroom } from "vue-headroom";
export default {
    components: {
        headroom
    },
    name: 'Navbar',
    props: {
                // when element is initialised
        initial : "headroom",
        // when scrolling up
        pinned : "headroom--pinned",
        // when scrolling down
        unpinned : "headroom--unpinned",
        // when above offset
        top : "headroom--top",
        // when below offset
        notTop : "headroom--not-top",
        // when at bottom of scoll area
        bottom : "headroom--bottom",
        // when not at bottom of scroll area
        notBottom : "headroom--not-bottom"
    }
}
</script>

<style scoped>
.headroom {
    padding: 50px;
}
.headroom--not-top {
    background: #00a699;
}
</style>


