<script>
import { defineComponent } from "vue";
import TestPackage2 from "@/test-package-2.vue";

export default defineComponent({
    name: "ServeDev",
    components: {
        TestPackage2,
    },
});
</script>

<template>
    <div id="app">
        <test-package-2 />
    </div>
</template>
