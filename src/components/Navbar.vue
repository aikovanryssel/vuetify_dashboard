<template >
    <nav>
       <v-toolbar flat app>
           <v-app-bar-nav-icon class="grey--text" @click="drawer=!drawer"></v-app-bar-nav-icon>
           <v-toolbar-title class="text-uppercase grey--text">
               <span class="font-weight-light">Todo</span> 
            </v-toolbar-title>
            <v-spacer></v-spacer>
            <v-btn outlined color="grey">
                <span>Sign Out</span>
                <v-icon right>logout</v-icon>
            </v-btn>
       </v-toolbar>
       <v-navigation-drawer v-model="drawer" app class="purple">
           <p>test</p>
       </v-navigation-drawer>
    </nav>
</template>

<script>
export default {
    data(){
        return{
            drawer:false
        }
    }
}
</script>