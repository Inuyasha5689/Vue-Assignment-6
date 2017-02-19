<template>
    <div class="container">
        <my-header></my-header>
        <hr>
        <my-content></my-content>
        <hr>
        <my-footer></my-footer>
    </div>
</template>

<script>
    import Content from './Content.vue';
    import Header from './Shared/Header.vue';
    import Footer from './Shared/Footer.vue';
    export default {
        components: {
            'my-header': Header,
            'my-content': Content,
            'my-footer': Footer
        }
    }
</script>