<template>
    <div>
        <h2>Witaj {{ username }}</h2>
        <a @click="logOut()">Wyloguj</a>
    </div>
</template>

<script>
    export default {
        props: ['username'],
        methods: {
            logOut() {
                this.$emit('logOut', this.email);
            }
        },
    }
</script>
