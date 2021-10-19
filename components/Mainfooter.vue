<template>
  <footer>
    <div id="fb-root"></div>
    <div class="bodyer">
      <v-container>
        <v-row>
          <v-col lg="3" md="6" cols="12">
            <div
              class="footer-link"
              v-for="(menu, index) in menus"
              @click="viewRoute(menu.link)"
              v-bind:key="index"
            >
              {{ menu.name }}
            </div>
          </v-col>
          <v-col lg="3" md="6" cols="12">
            <div
              class="footer-link"
              v-for="(menu, index) in menus"
              @click="viewRoute(menu.link)"
              v-bind:key="index"
            >
              {{ menu.name }}
            </div>
          </v-col>
          <v-col lg="4" md="6" cols="12">
            <div id="fb-root"></div>
            <script
              async
              defer
              crossorigin="anonymous"
              src="https://connect.facebook.net/en_US/sdk.js#xfbml=1&version=v12.0&appId=2745982388856199&autoLogAppEvents=1"
              nonce="sAjG04rh"
            ></script>
            <div
              class="fb-page"
              data-href="https://www.facebook.com/moommongpage"
              data-tabs="timeline"
              data-width=""
              data-height="300"
              data-small-header="false"
              data-adapt-container-width="true"
              data-hide-cover="false"
              data-show-facepile="true"
            >
              <blockquote
                cite="https://www.facebook.com/moommongpage"
                class="fb-xfbml-parse-ignore"
              >
                <a href="https://www.facebook.com/moommongpage"> Moommong</a>
              </blockquote>
            </div>
          </v-col>
        </v-row>
      </v-container>
    </div>
  </footer>
</template>

<script>
import { mapState, mapGetters } from "vuex";
export default {
  data() {
    return {
      menus: [
        { link: "/", name: "หน้าหลัก" },
        { link: "/", name: "โครงการ" },
        { link: "/", name: "ต้องการระบาย" },
        { link: "/", name: "นักรับฟัง" },
        { link: "/", name: "บทความ" }
      ]
    };
  },
  methods: {
    viewRoute(link) {
      this.$router.push({
        path: link
      });
    }
  },
  watch: {},
  mounted() {},
  components: {}
};
</script>

<style lang="scss" scoped>
footer {
  width: 100%;
  background-color: #363636;
  padding-top: 50px;
  padding-bottom: 50px;
  .footer-header {
    font-size: 1.4rem;
    color: #fff;
  }
  .footer-link {
    display: block;
    font-size: 1rem;
    font-weight: 300;
    color: #fff;
    margin-top: 20px;
    cursor: pointer;
    &:hover {
      opacity: 0.6;
    }
  }
}
</style>
