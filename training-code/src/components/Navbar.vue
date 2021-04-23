<template>
    <nav>
        <v-toolbar flat app>
            <v-app-bar-nav-icon class="grey--text" @click="drawer = !drawer">
            </v-app-bar-nav-icon>
            <v-toolbar-title class="text-uppercase grey--text">
                <span class="font-weight-light">Todo</span>
                <span>App</span>
            </v-toolbar-title>
            <v-spacer></v-spacer>
            <v-btn flat color="grey">
                <span> Sign Out </span>
                <v-icon right class="mdi mdi-logout-variant"> </v-icon>
            </v-btn>
        </v-toolbar>

        <v-navigation-drawer app v-model="drawer">
            <v-list-item>
                <v-list-item-content >
                    <v-list-item-title class="title">
                        Application
                    </v-list-item-title>
                    <v-list-item-subtitle>
                        TodoApp
                    </v-list-item-subtitle>
                </v-list-item-content>
            </v-list-item>

            <v-divider></v-divider>

        </v-navigation-drawer>
        <p> Hello </p>
    </nav>
</template>

<script>
export default {
    data(){
        return{
            drawer: false
        }
    }
}
</script>

<style scoped>

</style>
