<template>
    <header class="header">
        <h1>Todo List</h1>
        <div id="nav">
            <router-link to="/">Home</router-link> |
            <router-link to="/about">About</router-link>
        </div>
    </header>
</template>

<script>
    export default {
        name: "Header"
    }
</script>

<style scoped>
    .header {
        background: #42b983;
        color: #fff;
        text-align: center;
        padding: 10px;
    }

    .header a {
        color: #fff;
        padding-right: 5px;
    }

    #nav {
        padding: 10px;
    }

    #nav a {
        color: #2c3e50;
        font-weight: lighter;
        text-decoration: none;
    }

    #nav a.router-link-exact-active {
        font-weight: bold;
    }
</style>