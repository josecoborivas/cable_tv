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
            <h1 style="margin-bottom: 1em;">Canales</h1>
            <v-row class="d-flex justify-start mb-6 mt-4" justify="center" align="center">
              
              <v-col cols="2" md="2" class="ml-4 mr-4" style="display: flex; align-items: center; margin-bottom: 7px;">
                <img style="width: 150px; heigth:150px; cursor: pointer;" link @click="ver('discoveryTurbo')" src="@/assets/img/logos/discoveryTurbo.png" alt="">  
              </v-col>

              <v-col cols="2" md="2" class="ml-4 mr-4" style="display: flex; align-items: center; margin-bottom: 7px;">
                <img style="width: 150px; heigth:150px; cursor: pointer;" link @click="ver('garageTv')" src="@/assets/img/logos/garagetv.png" alt="">  
              </v-col>

              <v-col cols="2" md="2" style="display: flex; align-items: center; margin-bottom: 7px;">
                <img style="width: 150px; heigth:150px; cursor: pointer;" link @click="ver('h&h')" src="@/assets/img/logos/h&h.png" alt="">
              </v-col>

              <v-col cols="2" md="2" style="display: flex; align-items: center; margin-bottom: 7px;">
                <img style="width: 150px; heigth:150px; cursor: pointer;" link @click="ver('gourmet')" src="@/assets/img/logos/gourmet.png" alt="">
              </v-col>

              <v-col cols="2" md="2" style="display: flex; align-items: center; margin-bottom: 7px;">
                <img style="width: 150px; heigth:150px; cursor: pointer;" link @click="ver('A&E')" src="@/assets/img/logos/A&E.png" alt="">
              </v-col>

              <v-col cols="2" md="2" style="display: flex; align-items: center; margin-bottom: 7px;">
                <img style="width: 150px; heigth:150px; cursor: pointer;" link @click="ver('discoveryID')" src="@/assets/img/logos/discoveryID.png" alt="">
              </v-col>

              <v-col cols="2" md="2" style="display: flex; align-items: center; margin-bottom: 7px;">
                <img style="width: 150px; heigth:150px; cursor: pointer;" link @click="ver('discoveryChannel')" src="@/assets/img/logos/discoveryChannel.png" alt="">
              </v-col>

              <v-col cols="2" md="2" align="center" style="display: flex; align-items: center; margin-bottom: 7px;">
                <img style="width: 150px; heigth:150px; cursor: pointer;" link @click="ver('discoveryWorld')" src="@/assets/img/logos/discoveryWorld.png" alt="">
              </v-col>

              <v-col cols="2" md="2" style="display: flex; align-items: center; margin-bottom: 7px;">
                <img style="width: 150px; heigth:150px; cursor: pointer;" link @click="ver('discoveryTheater')" src="@/assets/img/logos/discoveryTheater.png" alt="">
              </v-col>

              <v-col cols="2" md="2" style="display: flex; align-items: center; margin-bottom: 7px;">
                <img style="width: 150px; heigth:150px; cursor: pointer;" link @click="ver('tlc')" src="@/assets/img/logos/tlc.png" alt="">
              </v-col>

              <v-col cols="2" md="2" style="display: flex; align-items: center; margin-bottom: 7px;">
                <img style="width: 150px; heigth:150px; cursor: pointer;" link @click="ver('natgeo')" src="@/assets/img/logos/natgeo.png" alt="">
              </v-col>

              <v-col cols="2" md="2" style="display: flex; align-items: center; margin-bottom: 7px;">
                <img style="width: 150px; heigth:150px; cursor: pointer;" link @click="ver('animalplanet')" src="@/assets/img/logos/animalplanet.png" alt="">
              </v-col>

              <v-col cols="2" md="2" style="display: flex; align-items: center; margin-bottom: 7px;">
                <img style="width: 150px; heigth:150px; cursor: pointer;" link @click="ver('foodnetwork')" src="@/assets/img/logos/foodnetwork.png" alt="">
              </v-col>

              <v-col cols="2" md="2" style="display: flex; align-items: center; margin-bottom: 7px;">
                <img style="width: 150px; heigth:150px; cursor: pointer;" link @click="ver('axn')" src="@/assets/img/logos/axn.png" alt="">
              </v-col>

              <v-col cols="2" md="2" style="display: flex; align-items: center; margin-bottom: 7px;">
                <img style="width: 150px; heigth:150px; cursor: pointer;" link @click="ver('vtv')" src="@/assets/img/logos/vtv.png" alt="">
              </v-col>

              <!--v-col cols="2" md="2" style="display: flex; align-items: center; margin-bottom: 7px;">
                <img style="width: 150px; heigth:150px; cursor: pointer;" link @click="ver('vtvplus')" src="@/assets/img/logos/vtvplus.png" alt="">
              </v-col-->

              <v-col cols="2" md="2" align="center" style="display: flex; align-items: center; margin-bottom: 7px;">
                <img style="width: 150px; heigth:150px; cursor: pointer;" link @click="ver('espn')" src="@/assets/img/logos/espn.png" alt="">
              </v-col>

              <v-col cols="2" md="2" align="center" style="display: flex; align-items: center; margin-bottom: 7px;">
                <img style="width: 150px; heigth:150px; cursor: pointer;" link @click="ver('espn2')" src="@/assets/img/logos/espn2.png" alt="">
              </v-col>

              <v-col cols="2" md="2" align="center" style="display: flex; align-items: center; margin-bottom: 7px;">
                <img style="width: 150px; heigth:150px; cursor: pointer;" link @click="ver('espn3')" src="@/assets/img/logos/espn3.png" alt="">
              </v-col>

              <v-col cols="2" md="2" align="center" style="display: flex; align-items: center; margin-bottom: 7px;">
                <img style="width: 150px; heigth:150px; cursor: pointer;" link @click="ver('dtvSports')" src="@/assets/img/logos/dtvSports.png" alt="">
              </v-col>

              <v-col cols="2" md="2" align="center" style="display: flex; align-items: center; margin-bottom: 7px;">
                <img style="width: 150px; heigth:150px; cursor: pointer;" link @click="ver('foxSports')" src="@/assets/img/logos/foxSports.png" alt="">
              </v-col>

              <v-col cols="2" md="2" align="center" style="display: flex; align-items: center; margin-bottom: 7px;">
                <img style="width: 150px; heigth:150px; cursor: pointer;" link @click="ver('pxsports')" src="@/assets/img/logos/pxsports.png" alt="">
              </v-col>

              <v-col cols="2" md="2" align="center" style="display: flex; align-items: center; margin-bottom: 7px;">
                <img style="width: 150px; heigth:150px; cursor: pointer;" link @click="ver('tvperu')" src="@/assets/img/logos/tvperu.png" alt="">
              </v-col>

              <v-col cols="2" md="2" align="center" style="display: flex; align-items: center; margin-bottom: 7px;">
                <img style="width: 150px; heigth:150px; cursor: pointer;" link @click="ver('panamericana')" src="@/assets/img/logos/panamericana.png" alt="">
              </v-col>

              <v-col cols="2" md="2" align="center" style="display: flex; align-items: center; margin-bottom: 7px;">
                <img style="width: 150px; heigth:150px; cursor: pointer;" link @click="ver('telefe')" src="@/assets/img/logos/telefe.png" alt="">
              </v-col>

              <v-col cols="2" md="2" align="center" style="display: flex; align-items: center; margin-bottom: 7px;">
                <img style="width: 150px; heigth:150px; cursor: pointer;" link @click="ver('canal9ar')" src="@/assets/img/logos/canal9ar.png" alt="">
              </v-col>

              <v-col cols="2" md="2" align="center" style="display: flex; align-items: center; margin-bottom: 7px;">
                <img style="width: 150px; heigth:150px; cursor: pointer;" link @click="ver('cnnEs')" src="@/assets/img/logos/cnnEs.png" alt="">
              </v-col>

               <v-col cols="2" md="2" align="center" style="display: flex; align-items: center; margin-bottom: 7px;">
                <img style="width: 150px; heigth:150px; cursor: pointer;" link @click="ver('history')" src="@/assets/img/logos/history.png" alt="">
              </v-col>

              <v-col cols="2" md="2" align="center" style="display: flex; align-items: center; margin-bottom: 7px;">
                <img style="width: 150px; heigth:150px; cursor: pointer;" link @click="ver('history2')" src="@/assets/img/logos/history2.png" alt="">
              </v-col>

              <v-col cols="2" md="2" align="center" style="display: flex; align-items: center; margin-bottom: 7px;">
                <img style="width: 150px; heigth:150px; cursor: pointer;" link @click="ver('wchannel')" src="@/assets/img/logos/wchannel.png" alt="">
              </v-col>

              <v-col cols="2" md="2" align="center" style="display: flex; align-items: center; margin-bottom: 7px;">
                <img style="width: 150px; heigth:150px; cursor: pointer;" link @click="ver('cartoon')" src="@/assets/img/logos/cartoon.png" alt="">
              </v-col>

              <v-col cols="2" md="2" align="center" style="display: flex; align-items: center; margin-bottom: 7px;">
                <img style="width: 150px; heigth:150px; cursor: pointer;" link @click="ver('nichelodeon')" src="@/assets/img/logos/nichelodeon.png" alt="">
              </v-col>

              <v-col cols="2" md="2" align="center" style="display: flex; align-items: center; margin-bottom: 7px;">
                <img style="width: 150px; heigth:150px; cursor: pointer;" link @click="ver('kpop')" src="@/assets/img/logos/kpop.png" alt="">
              </v-col>

              <v-col cols="2" md="2" align="center" style="display: flex; align-items: center; margin-bottom: 7px;">
                <img style="width: 150px; heigth:150px; cursor: pointer;" link @click="ver('space')" src="@/assets/img/logos/space.png" alt="">
              </v-col>

              <v-col cols="2" md="2" align="center" style="display: flex; align-items: center; margin-bottom: 7px;">
                <img style="width: 150px; heigth:150px; cursor: pointer;" link @click="ver('cinecanal')" src="@/assets/img/logos/cinecanal.png" alt="">
              </v-col>

              <v-col cols="2" md="2" align="center" style="display: flex; align-items: center; margin-bottom: 7px;">
                <img style="width: 150px; heigth:150px; cursor: pointer;" link @click="ver('tntSeries')" src="@/assets/img/logos/tntSeries.png" alt="">
              </v-col>

              <v-col cols="2" md="2" align="center" style="display: flex; align-items: center; margin-bottom: 7px;">
                <img style="width: 150px; heigth:150px; cursor: pointer;" link @click="ver('a3cine')" src="@/assets/img/logos/a3cine.png" alt="">
              </v-col>

              <v-col cols="2" md="2" align="center" style="display: flex; align-items: center; margin-bottom: 7px;">
                <img style="width: 150px; heigth:150px; cursor: pointer;" link @click="ver('a3series')" src="@/assets/img/logos/a3series.png" alt="">
              </v-col>

              <v-col cols="2" md="2" align="center" style="display: flex; align-items: center; margin-bottom: 7px;">
                <img style="width: 150px; heigth:150px; cursor: pointer;" link @click="ver('comedyCentral')" src="@/assets/img/logos/comedyCentral.png" alt="">
              </v-col>

              <v-col cols="2" md="2" align="center" style="display: flex; align-items: center; margin-bottom: 7px;">
                <img style="width: 150px; heigth:150px; cursor: pointer;" link @click="ver('cinemax')" src="@/assets/img/logos/cinemax.png" alt="">
              </v-col>
              
              <v-col cols="2" md="2" align="center" style="display: flex; align-items: center; margin-bottom: 7px;">
                <img style="width: 150px; heigth:150px; cursor: pointer;" link @click="ver('amc')" src="@/assets/img/logos/amc.png" alt="">
              </v-col>

              <v-col cols="2" md="2" align="center" style="display: flex; align-items: center; margin-bottom: 7px;">
                <img style="width: 150px; heigth:150px; cursor: pointer;" link @click="ver('fxm')" src="@/assets/img/logos/fxm.png" alt="">
              </v-col>

              <v-col cols="2" md="2" align="center" style="display: flex; align-items: center; margin-bottom: 7px;">
                <img style="width: 150px; heigth:150px; cursor: pointer;" link @click="ver('tnt')" src="@/assets/img/logos/tnt.png" alt="">
              </v-col>

               <v-col cols="2" md="2" align="center" style="display: flex; align-items: center; margin-bottom: 7px;">
                <img style="width: 150px; heigth:150px; cursor: pointer;" link @click="ver('sony')" src="@/assets/img/logos/sony.png" alt="">
              </v-col>

               <v-col cols="2" md="2" align="center" style="display: flex; align-items: center; margin-bottom: 7px;">
                <img style="width: 150px; heigth:150px; cursor: pointer;" link @click="ver('cinear')" src="@/assets/img/logos/cinear.png" alt="">
              </v-col>

              <v-col cols="2" md="2" align="center" style="display: flex; align-items: center; margin-bottom: 7px;">
                <img style="width: 150px; heigth:150px; cursor: pointer;" link @click="ver('universal')" src="@/assets/img/logos/universal.png" alt="">
              </v-col>

              <v-col cols="2" md="2" align="center" style="display: flex; align-items: center; margin-bottom: 7px;">
                <img style="width: 150px; heigth:150px; cursor: pointer;" link @click="ver('paramount')" src="@/assets/img/logos/paramount.png" alt="">
              </v-col>

              <v-col cols="2" md="2" align="center" style="display: flex; align-items: center; margin-bottom: 7px;">
                <img style="width: 150px; heigth:150px; cursor: pointer;" link @click="ver('starChannel')" src="@/assets/img/logos/starChannel.png" alt="">
              </v-col>

              <v-col cols="2" md="2" align="center" style="display: flex; align-items: center; margin-bottom: 7px;">
                <img style="width: 150px; heigth:150px; cursor: pointer;" link @click="ver('starChannelTv')" src="@/assets/img/logos/starChannelTv.png" alt="">
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
img:hover{
  -webkit-box-shadow: -1px 13px 29px 3px rgba(0,0,0,0.75);
  -moz-box-shadow: -1px 13px 29px 3px rgba(0,0,0,0.75);
  box-shadow: -1px 13px 29px 3px rgba(0,0,0,0.75);
}


</style>
