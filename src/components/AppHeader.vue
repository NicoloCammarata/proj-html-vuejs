<script>
export default {
    data() {
        return {

        };
    },
    methods: {

    }
}
</script>

<template>
    <header>
        HEADER

        <ul>
            <li>
                <router-link :to="{ name: 'home' }">
                        Home
                    </router-link>
            </li>

            <li>
                <router-link :to="{ name: 'about' }">
                        About
                    </router-link>
            </li>

            <li>
                <router-link :to="{ name: 'contact' }">
                        Contact
                    </router-link>
            </li>
            <div >
                <img src="../assets/01-102x102.jpg" alt="">
            </div>
            
        </ul>
    </header>
</template>

<style lang="scss" scoped>
img{
    width: 100px;
    height: 100px;
}
</style>
