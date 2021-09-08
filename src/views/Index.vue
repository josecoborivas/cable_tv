<template>
  <div class="wrapper">
    <parallax class="page-header header-filter" :style="headerStyle">
      <div class="md-layout">
        <div class="md-layout-item">
          <div class="image-wrapper">
            
            <div class="brand">
              <h1>Home Tv</h1>
              <h3>Tv Cable gratis sin anuncios.</h3>
            </div>
          </div>
        </div>
      </div>
    </parallax>
    <div class="main main-raised">
      <div class="section section-basic">
        <div class="container">
          <div class="title">
            <h2 class="mb-4">Canales</h2>
            <v-row class="d-flex justify-start mb-6 mt-4" justify="center" align="center">
              
              <v-col cols="3" md="3" class="ml-4 mr-4" style="display: flex; align-items: center;">
                <img style="width: 200px; heigth:200px; cursor: pointer;" link @click="ver('discoveryTurbo')" src="@/assets/img/logos/discoveryTurbo.png" alt="">  
              </v-col>

              <v-col cols="3" md="3" style="display: flex; align-items: center;">
                <img style="width: 200px; heigth:200px; cursor: pointer;" link @click="ver('h&h')" src="@/assets/img/logos/h&h.png" alt="">
              </v-col>

              <v-col cols="3" md="3" style="display: flex; align-items: center;">
                <img style="width: 200px; heigth:200px; cursor: pointer;" link @click="ver('discoveryID')" src="@/assets/img/logos/discoveryID.png" alt="">
              </v-col>

              <v-col cols="3" md="3" style="display: flex; align-items: center;">
                <img style="width: 200px; heigth:200px; cursor: pointer;" link @click="ver('discoveryChannel')" src="@/assets/img/logos/discoveryChannel.png" alt="">
              </v-col>

              <v-col cols="3" md="3" align="center" style="display: flex; align-items: center;">
                <img style="width: 200px; heigth:200px; cursor: pointer;" link @click="ver('discoveryWorld')" src="@/assets/img/logos/discoveryWorld.png" alt="">
              </v-col>

              <v-col cols="3" md="3" style="display: flex; align-items: center;">
                <img style="width: 200px; heigth:200px; cursor: pointer;" link @click="ver('discoveryTheater')" src="@/assets/img/logos/discoveryTheater.png" alt="">
              </v-col>

              <v-col cols="3" md="3" style="display: flex; align-items: center;">
                <img style="width: 200px; heigth:200px; cursor: pointer;" link @click="ver('natgeo')" src="@/assets/img/logos/natgeo.png" alt="">
              </v-col>

              <v-col cols="3" md="3" style="display: flex; align-items: center;">
                <img style="width: 200px; heigth:200px; cursor: pointer;" link @click="ver('axn')" src="@/assets/img/logos/axn.png" alt="">
              </v-col>

              <v-col cols="3" md="3" style="display: flex; align-items: center;">
                <img style="width: 200px; heigth:200px; cursor: pointer;" link @click="ver('vtv')" src="@/assets/img/logos/vtv.png" alt="">
              </v-col>

              <v-col cols="3" md="3" align="center" style="display: flex; align-items: center;">
                <img style="width: 200px; heigth:200px; cursor: pointer;" link @click="ver('espn2')" src="@/assets/img/logos/espn2.png" alt="">
              </v-col>

              <v-col cols="3" md="3" align="center" style="display: flex; align-items: center;">
                <img style="width: 200px; heigth:200px; cursor: pointer;" link @click="ver('espn3')" src="@/assets/img/logos/espn3.png" alt="">
              </v-col>

              <v-col cols="3" md="3" align="center" style="display: flex; align-items: center;">
                <img style="width: 200px; heigth:200px; cursor: pointer;" link @click="ver('dtvSports')" src="@/assets/img/logos/dtvSports.png" alt="">
              </v-col>

              <v-col cols="3" md="3" align="center" style="display: flex; align-items: center;">
                <img style="width: 200px; heigth:200px; cursor: pointer;" link @click="ver('foxSports')" src="@/assets/img/logos/foxSports.png" alt="">
              </v-col>

              <v-col cols="3" md="3" align="center" style="display: flex; align-items: center;">
                <img style="width: 200px; heigth:200px; cursor: pointer;" link @click="ver('tvperu')" src="@/assets/img/logos/tvperu.png" alt="">
              </v-col>

              <v-col cols="3" md="3" align="center" style="display: flex; align-items: center;">
                <img style="width: 200px; heigth:200px; cursor: pointer;" link @click="ver('panamericana')" src="@/assets/img/logos/panamericana.png" alt="">
              </v-col>

              <v-col cols="3" md="3" align="center" style="display: flex; align-items: center;">
                <img style="width: 200px; heigth:200px; cursor: pointer;" link @click="ver('telefe')" src="@/assets/img/logos/telefe.png" alt="">
              </v-col>

               <v-col cols="3" md="3" align="center" style="display: flex; align-items: center;">
                <img style="width: 200px; heigth:200px; cursor: pointer;" link @click="ver('history')" src="@/assets/img/logos/history.png" alt="">
              </v-col>

              <v-col cols="3" md="3" align="center" style="display: flex; align-items: center;">
                <img style="width: 200px; heigth:200px; cursor: pointer;" link @click="ver('history2')" src="@/assets/img/logos/history2.png" alt="">
              </v-col>

              <v-col cols="3" md="3" align="center" style="display: flex; align-items: center;">
                <img style="width: 200px; heigth:200px; cursor: pointer;" link @click="ver('wchannel')" src="@/assets/img/logos/wchannel.png" alt="">
              </v-col>

               <v-col cols="3" md="3" align="center" style="display: flex; align-items: center;">
                <img style="width: 200px; heigth:200px; cursor: pointer;" link @click="ver('nichelodeon')" src="@/assets/img/logos/nichelodeon.png" alt="">
              </v-col>

               <v-col cols="3" md="3" align="center" style="display: flex; align-items: center;">
                <img style="width: 200px; heigth:200px; cursor: pointer;" link @click="ver('space')" src="@/assets/img/logos/space.png" alt="">
              </v-col>

              <v-col cols="3" md="3" align="center" style="display: flex; align-items: center;">
                <img style="width: 200px; heigth:200px; cursor: pointer;" link @click="ver('tntSeries')" src="@/assets/img/logos/tntSeries.png" alt="">
              </v-col>

              <v-col cols="3" md="3" align="center" style="display: flex; align-items: center;">
                <img style="width: 200px; heigth:200px; cursor: pointer;" link @click="ver('cinemax')" src="@/assets/img/logos/cinemax.png" alt="">
              </v-col>

               <v-col cols="3" md="3" align="center" style="display: flex; align-items: center;">
                <img style="width: 200px; heigth:200px; cursor: pointer;" link @click="ver('sony')" src="@/assets/img/logos/sony.png" alt="">
              </v-col>

               <v-col cols="3" md="3" align="center" style="display: flex; align-items: center;">
                <img style="width: 200px; heigth:200px; cursor: pointer;" link @click="ver('cinear')" src="@/assets/img/logos/cinear.png" alt="">
              </v-col>

              <v-col cols="3" md="3" align="center" style="display: flex; align-items: center;">
                <img style="width: 200px; heigth:200px; cursor: pointer;" link @click="ver('universal')" src="@/assets/img/logos/universal.png" alt="">
              </v-col>

              <v-col cols="3" md="3" align="center" style="display: flex; align-items: center;">
                <img style="width: 200px; heigth:200px; cursor: pointer;" link @click="ver('paramount')" src="@/assets/img/logos/paramount.png" alt="">
              </v-col>

              <v-col cols="3" md="3" align="center" style="display: flex; align-items: center;">
                <img style="width: 200px; heigth:200px; cursor: pointer;" link @click="ver('starChannel')" src="@/assets/img/logos/starChannel.png" alt="">
              </v-col>

              <v-col cols="3" md="3" align="center" style="display: flex; align-items: center;">
                <img style="width: 200px; heigth:200px; cursor: pointer;" link @click="ver('starChannelTv')" src="@/assets/img/logos/starChannelTv.png" alt="">
              </v-col>

              

              

             

            </v-row>
            
          </div>
          
        </div>
      </div>
     
    </div>
  </div>
</template>

<script>

export default {
  components: {

  },
  name: "index",
  bodyClass: "index-page",
  props: {
    image: {
      type: String,
      default: require("@/assets/img/background_tv_cable.jpg")
    },
    leaf4: {
      type: String,
      default: require("@/assets/img/leaf4.png")
    },
    leaf3: {
      type: String,
      default: require("@/assets/img/leaf3.png")
    },
    leaf2: {
      type: String,
      default: require("@/assets/img/leaf2.png")
    },
    leaf1: {
      type: String,
      default: require("@/assets/img/leaf1.png")
    },
    signup: {
      type: String,
      default: require("@/assets/img/city.jpg")
    },
    landing: {
      type: String,
      default: require("@/assets/img/landing.jpg")
    },
    profile: {
      type: String,
      default: require("@/assets/img/profile.jpg")
    }
  },
  data() {
    return {
      firstname: null,
      email: null,
      password: null,
      leafShow: false
    };
  },
  methods: {
    leafActive() {
      if (window.innerWidth < 768) {
        this.leafShow = false;
      } else {
        this.leafShow = true;
      }
    },
    ver(canal){
      this.$router.push(
        {
          name: "channel",
          params: { channelId: canal },
        },
        () => {}
      );
    }

  },
  computed: {
    headerStyle() {
      return {
        backgroundImage: `url(${this.image})`
      };
    },
    signupImage() {
      return {
        backgroundImage: `url(${this.signup})`
      };
    }
  },
  mounted() {
    this.leafActive();
    window.addEventListener("resize", this.leafActive);
  },
  beforeDestroy() {
    window.removeEventListener("resize", this.leafActive);
  }
};
</script>
<style lang="scss">
.section-download {
  .md-button + .md-button {
    margin-left: 5px;
  }
}

@media all and (min-width: 991px) {
  .btn-container {
    display: flex;
  }
}
</style>
