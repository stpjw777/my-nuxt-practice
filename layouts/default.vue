><template>
  <v-app>
    <header-component />
    <nuxt />
    <footer-component />
  </v-app>
</template>

<script>
import HeaderComponent from "@/components/HeaderComponent";
import FooterComponent from "@/components/FooterComponent";
export default {
  components: {
    HeaderComponent,
    FooterComponent
  }
};
</script>