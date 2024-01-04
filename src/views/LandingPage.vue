<template>
    <nav>
        <router-link>logo</router-link>
        <div class="navbar-links">
            <router-link tag="li">Jogos</router-link>
            <router-link tag="li">Notícias</router-link>
            <router-link tag="li">Regras</router-link>
        </div>
            <div class="auth-buttons">
                <button class="signin-button" @click="router.push({})">Sign In</button>
                <button class="signup-button" onclick="location.href='/html/register.html'">Sign Up</button>
            </div>
    </nav>
</template>

<script>
    export default {
        data() {
            return {
                key: value
            }
        },
    }
</script>

<style>

</style>