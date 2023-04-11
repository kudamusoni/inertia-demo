<template>
    <div>
        <h1 class="text-4xl">Users</h1>
        <!-- <Nav /> -->

        <div style="margin-top: 400px;">
            <p>Current time is {{ time }}</p>

            <Link href="/users" class="text-blue-500" preserve-scroll>Refresh</Link>
        </div>
    </div>
</template>

<script>
// import Nav from "../Shared/Nav.vue";
import { Link } from "@inertiajs/inertia-vue3";

export default {
    components: {
        // Nav,
        Link
    },
    props: ['time']
}
</script>
