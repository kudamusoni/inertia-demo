<template>
    <nav class="mt-6">
        <ul class="list-disc">
            <li>
                <NavLink href="/" :active="$page.component === 'Home'">Home</NavLink>
            </li>
            <li>
                <NavLink href="/users" :active="$page.component === 'Users'">Users</NavLink>
            </li>
            <li>
                <NavLink href="/settings" :active="$page.component === 'settings'">Setting</NavLink>
            </li>
            <li>
                <NavLink class="text-blue-500 hover:underline" href="/logout" method="post" as="button" :active="$page.component === 'logout'">Log Out</NavLink>
            </li>
        </ul>
    </nav>
</template>
<script>
import { NavLink } from "./NavLink.vue";
export default {
    components: { NavLink }
};
</script>
