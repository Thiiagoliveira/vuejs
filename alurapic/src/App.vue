<template>
  <div>
      <v-app light>
        <v-toolbar class="blue-grey lighten-3">
          <v-toolbar-title v-text="title"></v-toolbar-title>
        </v-toolbar>
        <main>
          <v-content>
            <section>
              <v-parallax style="background-color: #E6E6FA;" height="600">
                <v-layout column align-center justify-center class="black--text">
                   <img src="src/assets/logo_design-207x300.png" height="200">
                  <h1 class="black--text mb-2 display-2 text-xs-center">Seja bem-vindo ao banco de ideias</h1>
                  <div class="subheading mb-3 text-xs-center">Aplicação baseada em VueJS</div>
                  <v-btn class="dark lighten-2 mt-5" dark large>
                    Uma ideia aqui!
                  </v-btn>
                </v-layout>
              </v-parallax>
            </section>
          </v-content>
        </main>
    </v-app>
  </div>
</template>

<script>
export default {
  name: 'app',
  data (){
    return {
      title: 'Ideias de aplicativos'
    }
  }
}
</script>

<style>


</style>