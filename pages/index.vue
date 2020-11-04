<template>
  <v-row justify="center" align="center">
    <v-col cols="12" sm="8" md="10">
      <div class="text-center">
        <vuetify-logo />
      </div>
      <v-card>
        <v-card-title class="headline">
          Welcome to iTunes MUSIC.
        </v-card-title>
        <v-card-text>
          <p />
          <p>
            You can click for view itunes page.
            <a
              href="https://www.apple.com/th/itunes/"
              target="_blank"
              rel="noopener noreferrer"
              title="chat"
            >
              iTunes MUSIC page </a>.
          </p>
          <p>IF YOU WANT TO VIEW PROFILE CLICK CONTiUNUE</p>
        </v-card-text>
        <v-card-actions>
          <v-spacer />
          <v-btn color="warning" nuxt to="/inspire">
            Continue
            <v-icon>mdi-cursor-default-click</v-icon>
          </v-btn>
        </v-card-actions>
      </v-card>
    </v-col>
  </v-row>
</template>
<script>
import VuetifyLogo from '~/components/VuetifyLogo.vue'
export default {
  components: {
    VuetifyLogo
  }
}
</script>
