<template>
    <div id="app">
        <header>
            <div class="wrapper">
                <!-- <HelloWorld msg="You did it!" /> -->

                <nav>
                    <router-link to="/">Home</router-link>
                    <router-link to="/about">About</router-link>
                </nav>
            </div>
        </header>

        <router-view />
    </div>
</template>

<script lang="ts">
import  {defineComponent   } from 'vue';

export default defineComponent({
        setup() {

},
    mounted() {   }
});
</script>

<style scoped>
header {
    line-height: 1.5;
    max-height: 100vh;
}

.logo {
    display: block;
    margin: 0 auto 2rem;
}

nav {
    width: 100%;
    font-size: 12px;
    text-align: center;
    margin-top: 2rem;
}

nav a.router-link-exact-active {
    color: var(--color-text);
}

nav a.router-link-exact-active:hover {
    background-color: transparent;
}

nav a {
    display: inline-block;
    padding: 0 1rem;
    border-left: 1px solid var(--color-border);
}

nav a:first-of-type {
    border: 0;
}
</style>
