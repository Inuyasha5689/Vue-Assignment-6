<template>
    <div class="container">
        <my-header></my-header>
        <hr>
        <div class="row">
            <my-servers></my-servers>
            <my-server-description></my-server-description>
        </div>
        <hr>
        <my-footer></my-footer>
    </div>
</template>

<script>
    import Servers from './Servers/Servers.vue';
    import ServerDescription from './Servers/ServerDescription.vue';
    import Header from './Shared/Header.vue';
    import Footer from './Shared/Footer.vue';
    export default {
        components: {
            'my-header': Header,
            'my-servers': Servers,
            'my-server-description': ServerDescription,
            'my-footer': Footer
        }
    }
</script>