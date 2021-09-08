<template>
  <div class="wrapper">
    <parallax class="section page-header header-filter" :style="headerStyle">
      <div class="container">
        <div class="md-layout">

          <div class="md-layout-item" v-if="channel === 'discoveryTurbo'">
            <h1 class="title">Discovery Turbo</h1>
            <iframe style="height: 563px; width:1000px" allow="encrypted-media" width="100%" height="1000px !important;" src="https://tv7.mitele.uno/embed/mpd.php?canal=Discovery Turbo&amp;stream=/live/live/DiscoveryTurbo/SA_Live_dash_enc_2A/DiscoveryTurbo.mpd" id="iframe" name="iframe" frameborder="0" scrolling="yes" allowfullscreen=""></iframe>           
          </div>

          <div class="md-layout-item" v-if="channel === 'h&h'">
            <h1 class="title">Home & Health</h1>
            <iframe style="height: 563px; width:1000px" allow="encrypted-media" width="100%" height="100%" src="https://tv7.mitele.uno/embed/mpd.php?canal=Discovery home and health&amp;stream=/live/c3eds/DiscoveryHomeHealthHD/SA_Live_dash_enc_2A/DiscoveryHomeHealthHD.mpd" id="iframe" name="iframe" frameborder="0" scrolling="yes" allowfullscreen=""></iframe>
          </div>

          <div class="md-layout-item" v-if="channel === 'discoveryID'">
            <h1 class="title">Discovery ID</h1>
            <iframe style="height: 563px; width:1000px" allow="encrypted-media" width="100%" height="100%" src="https://tv7.mitele.uno/embed/mpd.php?canal=Discovery ID&amp;stream=/live/live/ID/SA_Live_dash_enc_2A/ID.mpd" id="iframe" name="iframe" frameborder="0" scrolling="yes" allowfullscreen=""></iframe>
          </div>

          <div class="md-layout-item" v-if="channel === 'discoveryChannel'">
            <h1 class="title">Discovery Channel</h1>
            <iframe style="height: 563px; width:1000px" allow="encrypted-media" width="100%" height="100%" src="https://tv7.mitele.uno/embed/mpd.php?canal=Discovery Channel&amp;stream=/live/c3eds/DiscoveryHD/SA_Live_dash_enc_2A/DiscoveryHD.mpd" id="iframe" name="iframe" frameborder="0" scrolling="yes" allowfullscreen=""></iframe>
          </div>

          <div class="md-layout-item" v-if="channel === 'discoveryTheater'">
            <h1 class="title">Discovery Theater</h1>
            <iframe style="height: 563px; width:1000px" allow="encrypted-media" width="100%" height="100%" src="https://tv7.mitele.uno/embed/mpd.php?canal=Discovery Theater&amp;stream=/live/c2live/Theater_HD/SA_Live_dash_enc_2A/Theater_HD.mpd" id="iframe" name="iframe" frameborder="0" scrolling="yes" allowfullscreen=""></iframe>
          </div>

          <div class="md-layout-item" v-if="channel === 'natgeo'">
            <h1 class="title">National Geographic</h1>
            <iframe style="height: 563px; width:1000px" allow="encrypted-media" width="100%" height="100%" src="https://tv7.mitele.uno/embed/mpd.php?canal=Natgeo&amp;stream=/live/c3eds/NatGeoHD/SA_Live_dash_enc_2A/NatGeoHD.mpd" id="iframe" name="iframe" frameborder="0" scrolling="yes" allowfullscreen=""></iframe>
          </div>

          <div class="md-layout-item" v-if="channel === 'axn'">
            <h1 class="title">AXN</h1>
            <iframe style="height: 563px; width:1000px" allow="encrypted-media" width="100%" height="100%" src="https://tv7.mitele.uno/embed/mpd.php?canal=AXN&amp;stream=/live/live/AXNHD/SA_Live_dash_enc_2A/AXNHD.mpd" id="iframe" name="iframe" frameborder="0" scrolling="yes" allowfullscreen=""></iframe>
          </div>

          <div class="md-layout-item" v-if="channel === 'vtv'">
            <h1 class="title">VTV</h1>
            <iframe style="height: 563px; width:1000px" class="embed-responsive-item" src="https://jquick-js.github.io/kid/?u=aHR0cHM6Ly9lcy1jZG4uY29tL3Z0di5qcz9hZGZmZ2Rk" scrolling="no" frameborder="0" allow="autoplay *; encrypted-media *;" allowfullscreen=""></iframe>
          </div>

          <div class="md-layout-item" v-if="channel === 'espn2'">
            <h1 class="title">ESPN 2</h1>
            <iframe style="height: 563px; width:1000px" allow="encrypted-media" width="100%" height="100%" src="https://tv7.mitele.uno/embed/mpd.php?canal=ESPN 2&amp;stream=live/c2live/ESPN_HD/SA_Live_dash_enc_2A/ESPN_HD.mpd" id="iframe" name="iframe" frameborder="0" scrolling="no" allowfullscreen=""></iframe>
          </div>

          <div class="md-layout-item" v-if="channel === 'espn3'">
            <h1 class="title">ESPN 3</h1>
            <iframe style="height: 563px; width:1000px" allow="encrypted-media" width="100%" height="100%" src="https://tv7.mitele.uno/embed/mpd.php?canal=ESPN 3&amp;stream=/live/c3eds/ESPN3/SA_Live_dash_enc_2A/ESPN3.mpd" id="iframe" name="iframe" frameborder="0" scrolling="no" allowfullscreen=""></iframe>
          </div>

          <div class="md-layout-item" v-if="channel === 'dtvSports'">
            <h1 class="title">Directv Sports</h1>
            <iframe style="height: 563px; width:1000px" allow="encrypted-media" width="100%" height="100%" src="https://www.mitele.uno/embed/dtv/dtv1.php" id="iframe" name="iframe" frameborder="0" scrolling="no" allowfullscreen=""></iframe>
          </div>

          <div class="md-layout-item" v-if="channel === 'foxSports'">
            <h1 class="title">Fox Sports</h1>
            <iframe style="height: 563px; width:1000px" allow="encrypted-media" width="100%" height="100%" src="https://tv7.mitele.uno/embed/mpd.php?canal=Fox Sports&amp;stream=/live/c3eds/FoxSports/SA_Live_dash_enc_2A/FoxSports.mpd" id="iframe" name="iframe" frameborder="0" scrolling="no" allowfullscreen=""></iframe>
          </div>

          <div class="md-layout-item" v-if="channel === 'tvperu'">
            <h1 class="title">TV Perú</h1>
            <iframe style="height: 563px; width:1000px" allow="encrypted-media" width="100%" height="100%" src="https://player.teleringa.com/embed/ext.php?url=cdnh8.iblups.com/hls/R9WtilpKKB.m3u8" id="iframe" name="iframe" frameborder="0" scrolling="no" allowfullscreen=""></iframe>
          </div>

           <div class="md-layout-item" v-if="channel === 'panamericana'">
            <h1 class="title">Panamericana Perú</h1>
            <iframe style="height: 563px; width:1000px" allow="encrypted-media" width="100%" height="100%" src="https://player.teleringa.com/embed/ext.php?url=cdnhd.iblups.com/hls/ptv2.m3u8" id="iframe" name="iframe" frameborder="0" scrolling="no" allowfullscreen=""></iframe>
          </div>

           <div class="md-layout-item" v-if="channel === 'history'">
            <h1 class="title">History Channel</h1>
            <iframe style="height: 563px; width:1000px" allow="encrypted-media" width="100%" height="100%" src="https://tv7.mitele.uno/embed/mpd.php?canal=History&amp;stream=/live/live/HistoryHD/SA_Live_dash_enc_2A/HistoryHD.mpd" id="iframe" name="iframe" frameborder="0" scrolling="yes" allowfullscreen=""></iframe>
          </div>

           <div class="md-layout-item" v-if="channel === 'history2'">
            <h1 class="title">History Channel 2</h1>
            <iframe style="height: 563px; width:1000px" allow="encrypted-media" width="100%" height="100%" src="https://tv7.mitele.uno/embed/mpd.php?canal=History 2&amp;stream=/live/c2live/History_2/SA_Live_dash_enc_2A/History_2.mpd" id="iframe" name="iframe" frameborder="0" scrolling="yes" allowfullscreen=""></iframe>
          </div>

           <div class="md-layout-item" v-if="channel === 'vtvplus'">
            <h1 class="title">VTV Plus</h1>
            <iframe style="height: 563px; width:1000px" src="http://tvporinternet.eshost.com.ar/canales/vtv.html" height="100%" width="100%" frameborder="0" allowfullscreen scrolling="no"></iframe>
          </div>

          <div class="md-layout-item" v-if="channel === 'telefe'">
            <h1 class="title">Telefe</h1>
            <iframe style="height: 563px; width:1000px" allow="encrypted-media" width="100%" height="100%" src="https://tv7.mitele.uno/embed/mpd-tlf.php?canal=Telefe&amp;stream=live/c3eds/TelefeHD/SA_Live_dash_enc_2A/TelefeHD.mpd" id="iframe" name="iframe" frameborder="0" scrolling="no" allowfullscreen=""></iframe>
          </div>

          <div class="md-layout-item" v-if="channel === 'wchannel'">
            <h1 class="title">Warner Channel</h1>
            <iframe style="height: 563px; width:1000px" allow="encrypted-media" width="100%" height="100%" src="https://tv7.mitele.uno/embed/mpd.php?canal=Warner Channel&amp;stream=/live/live/WarnerHD/SA_Live_dash_enc_2A/WarnerHD.mpd" id="iframe" name="iframe" frameborder="0" scrolling="yes" allowfullscreen=""></iframe>
          </div>

           <div class="md-layout-item" v-if="channel === 'nichelodeon'">
            <h1 class="title">Nichelodeon</h1>
            <iframe style="height: 563px; width:1000px" allow="encrypted-media" width="100%" height="100%" src="https://tv7.mitele.uno/embed/mpd.php?canal=Nick&amp;stream=/live/c3eds/Nickelodeon/SA_Live_dash_enc_2A/Nickelodeon.mpd" id="iframe" name="iframe" frameborder="0" scrolling="yes" allowfullscreen=""></iframe>
          </div>

           <div class="md-layout-item" v-if="channel === 'space'">
            <h1 class="title">Space</h1>
            <iframe style="height: 563px; width:1000px" allow="encrypted-media" width="100%" height="100%" src="https://tv7.mitele.uno/embed/mpd.php?canal=Space&amp;stream=/live/c3eds/Space/SA_Live_dash_enc_2A/Space.mpd" id="iframe" name="iframe" frameborder="0" scrolling="yes" allowfullscreen=""></iframe>
          </div>

          <div class="md-layout-item" v-if="channel === 'tntSeries'">
            <h1 class="title">TNT Series</h1>
            <iframe style="height: 563px; width:1000px" allow="encrypted-media" width="100%" height="100%" src="https://tv7.mitele.uno/embed/mpd.php?canal=TNT Series&amp;stream=/live/c3eds/TNTSeries/SA_Live_dash_enc_2A/TNTSeries.mpd" id="iframe" name="iframe" frameborder="0" scrolling="yes" allowfullscreen=""></iframe>
          </div>

          <div class="md-layout-item" v-if="channel === 'cinemax'">
            <h1 class="title">Cinemax</h1>
            <iframe style="height: 563px; width:1000px" allow="encrypted-media" width="100%" height="100%" src="https://tv7.mitele.uno/embed/mpd.php?canal=Cinemax&amp;stream=/live/c2live/Cinemax/SA_Live_dash_enc_2A/Cinemax.mpd" id="iframe" name="iframe" frameborder="0" scrolling="yes" allowfullscreen=""></iframe>
          </div>

           <div class="md-layout-item" v-if="channel === 'sony'">
            <h1 class="title">Sony</h1>
            <iframe style="height: 563px; width:1000px" allow="encrypted-media" width="100%" height="100%" src="https://tv7.mitele.uno/embed/mpd.php?canal=Sony&amp;stream=/live/live/SonyHD/SA_Live_dash_enc_2A/SonyHD.mpd" id="iframe" name="iframe" frameborder="0" scrolling="yes" allowfullscreen=""></iframe>
          </div>

           <div class="md-layout-item" v-if="channel === 'cinear'">
            <h1 class="title">Cine Argentino</h1>
            <iframe style="height: 563px; width:1000px" allow="encrypted-media" width="100%" height="100%" src="https://tv7.mitele.uno/embed/mpd.php?canal=CineAR&amp;stream=/live/c2live/INCAA_Tv/SA_Live_dash_enc_2A/INCAA_Tv.mpd" id="iframe" name="iframe" frameborder="0" scrolling="yes" allowfullscreen=""></iframe>
          </div>

          <div class="md-layout-item" v-if="channel === 'universal'">
            <h1 class="title">Universal Channel</h1>
            <iframe style="height: 563px; width:1000px" allow="encrypted-media" width="100%" height="100%" src="https://tv7.mitele.uno/embed/mpd.php?canal=Studio Universal&amp;stream=/live/c2live/Studio_Universal/SA_Live_dash_enc_2A/Studio_Universal.mpd" id="iframe" name="iframe" frameborder="0" scrolling="yes" allowfullscreen=""></iframe>
          </div>

          <div class="md-layout-item" v-if="channel === 'paramount'">
            <h1 class="title">Paramount Channel</h1>
            <iframe style="height: 563px; width:1000px" allow="encrypted-media" width="100%" height="100%" src="https://tv7.mitele.uno/embed/mpd.php?canal=Paramount&amp;stream=/live/live/Paramount/SA_Live_dash_enc_2A/Paramount.mpd" id="iframe" name="iframe" frameborder="0" scrolling="yes" allowfullscreen=""></iframe>
          </div>

          <div class="md-layout-item" v-if="channel === 'discoveryWorld'">
            <h1 class="title">Discovery World</h1>
            <iframe style="height: 563px; width:1000px" allow="encrypted-media" width="100%" height="100%" src="https://tv7.mitele.uno/embed/mpd.php?canal=Discovery World&amp;stream=live/c2live/Discovery_World_HD/SA_Live_dash_enc_2A/Discovery_World_HD.mpd" id="iframe" name="iframe" frameborder="0" scrolling="yes" allowfullscreen=""></iframe>
          </div>

          <div class="md-layout-item" v-if="channel === 'starChannel'">
            <h1 class="title">Star Channel Series</h1>
            <iframe style="height: 563px; width:1000px" allow="encrypted-media" width="100%" height="100%" src="https://tv7.mitele.uno/embed/mpd.php?canal=Star Series&amp;stream=/live/c3eds/FOX1HD/SA_Live_dash_enc_2A/FOX1HD.mpd" id="iframe" name="iframe" frameborder="1" scrolling="yes" allowfullscreen=""></iframe>
          </div>

          <div class="md-layout-item" v-if="channel === 'starChannelTv'">
            <h1 class="title">Star Channel</h1>
            <iframe style="height: 563px; width:1000px" allow="encrypted-media" width="100%" height="100%" src="https://tv7.mitele.uno/embed/mpd.php?canal=Star Channel&amp;stream=/live/c3eds/FOXHD/SA_Live_dash_enc_2A/FOXHD.mpd" id="iframe" name="iframe" frameborder="0" scrolling="yes" allowfullscreen=""></iframe>
          </div>
          

        </div>
      </div>
    </parallax>
   
  </div>
</template>

<script>
export default {
  bodyClass: "landing-page",
  props: {
    header: {
      type: String,
      default: require("@/assets/img/background_landing.jpg")
    },
    teamImg1: {
      type: String,
      default: require("@/assets/img/faces/avatar.jpg")
    },
    teamImg2: {
      type: String,
      default: require("@/assets/img/faces/christian.jpg")
    },
    teamImg3: {
      type: String,
      default: require("@/assets/img/faces/kendall.jpg")
    }
  },
  data() {
    return {
      name: null,
      email: null,
      message: null,
      channel: null,
    };
  },
  computed: {
    headerStyle() {
      return {
        backgroundImage: `url(${this.header})`
      };
    }
  },
  created: function() {
    this.channel = this.$route.params.channelId;
  },
};
</script>

<style lang="scss" scoped>
.md-card-actions.text-center {
  display: flex;
  justify-content: center !important;
}
.contact-form {
  margin-top: 30px;
}

.md-has-textarea + .md-layout {
  margin-top: 15px;
}


</style>
