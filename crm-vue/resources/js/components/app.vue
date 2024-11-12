<template>
    <!-- <p>
        <strong>Current router path: {{ $route.path }}</strong>
    </p> -->

    <nav>
        <router-link class="link" to="/">Home</router-link>
        <router-link class="link" to="/about">About</router-link>
    </nav>

    <main>
        <router-view></router-view>
    </main>
</template>
