<template>
    <v-app>
        <Menu />
        <Header />
        <Content />
        <Footer />
    </v-app>
</template>

<script>
//importando os componentes de forma local
import Menu from './components/Menu.vue'
import Header from './components/Header.vue'
import Content from './components/Content.vue'
import Footer from './components/Footer.vue'
export default {
    //Registrando o componente
    // componente: modulo importado ou só modulo importado
    components: {
        Menu,
        Header,
        Content,
        Footer
    }
}
</script>
