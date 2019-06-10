<template>
  <v-app light class="white" id="app">
    <v-flex class="pa-5" style="font-size: 2em; position: absolute; top: 0; left: 0; z-index: 999;">
      <h1>
      <v-avatar size="80" class="hidden-sm-and-down pink mb-3 mr-3">
        <img src="https://www.upwork.com/profile-portraits/c18GQ_SazI15TjBtgsPQevIocCzc7uI0SFZvk3saSug-1lVso7zW6rbpyCqWaV7uj0?1557003397602">
      </v-avatar>
      <v-avatar size="50" class="hidden-md-and-up pink mr-2 mb-2">
        <img src="https://www.upwork.com/profile-portraits/c18GQ_SazI15TjBtgsPQevIocCzc7uI0SFZvk3saSug-1lVso7zW6rbpyCqWaV7uj0?1557003397602">
      </v-avatar>
      <i>Nikita K.</i></h1>
      <p><v-icon large class="hidden-sm-and-down black--text mb-1 mr-2">location_on</v-icon><v-icon class="hidden-md-and-up mr-1">location_on</v-icon>Rockville, MD</p>
    </v-flex>

    <v-flex md4 lg3 class="pa-3 hidden-sm-and-down" style="font-size: 2em; position: fixed; bottom:0; right: 0; z-index: 1;">
      <v-layout column>
        <v-btn block round flat class="link link--kukuri" v-scroll-to="{el:'#info', offset: 0}"><v-spacer></v-spacer>Info</v-btn>
        <v-btn block round flat class="link link--kukuri" v-scroll-to="{el:'#work', offset: 0}"><v-spacer></v-spacer>Work</v-btn>
        <v-btn block round flat class="link link--kukuri" v-scroll-to="{el:'#contact', offset: 0}"><v-spacer></v-spacer>Contact</v-btn>
      </v-layout>
    </v-flex>

    <v-btn fixed bottom right class="hidden-md-and-up pink white--text" fab><v-icon>menu</v-icon></v-btn>

    <v-layout column id="info" class="height" style="background: -webkit-linear-gradient(to right, #232526, #414345); z-index: 0;">
      <span class="hidden-sm-and-down my-auto mx-auto" style="font-size: 3em; text-shadow: 0 0 1em white">Fullstack
        <h1 style="z-index: 1">Web Developer</h1>
      </span>
      <h1 style="z-index: 1; font-size: 2em;  text-shadow: 0 0 1em white; text-align: center;" class="hidden-md-and-up my-auto mx-auto">Fullstack Web Developer</h1>
    </v-layout>

    <v-flex class="height pa-5" id="work">
      <v-flex class="pa-5" style="font-size: 2em; position: absolute; top: 100vh; left: 0; z-index: 1;">
        <h1><span class="pink--text">1/4</span> Savvy Tech LLC</h1>
        <p>Company website, old version</p>
      </v-flex>

      <v-flex xs12 md10 offset-md1 lg6 offset-lg3 style="margin-top: 50vh; transform: translateY(-50%);">
        <v-img class="tilt hidden-sm-and-down round2 mx-auto" aspect-raito="1.7888" src="savvy-tech.png">
          <v-layout column class="hover fill-height" style="background: #2225;">
            <v-btn target="_blank" href="https://savvy-tech.firebaseapp.com" large class="my-auto mx-auto white white--text" flat fab><v-icon large>remove_red_eye</v-icon></v-btn>
          </v-layout>
        </v-img>
        <v-img v-ripple class="hidden-md-and-up round2 mx-auto" aspect-raito="1.7888" src="savvy-tech-mobile.png" style="max-height: 70vh;"></v-img>
      </v-flex>
    </v-flex>

    <v-flex class="height pa-5">
      <v-flex class="pa-5" style="font-size: 2em; position: absolute; top: 200vh; left: 0; z-index: 1;">
        <h1><span class="pink--text">2/4</span> Savvy Tech Enly</h1>
        <p>Company website, v2.0</p>
      </v-flex>

      <v-flex xs12 md10 offset-md1 lg6 offset-lg3 style="margin-top: 50vh; transform: translateY(-50%);">
        <v-img class="tilt hidden-sm-and-down round2 mx-auto" aspect-raito="1.7888" src="savvy-enly.png">
          <v-layout column class="hover fill-height" style="background: #2225;">
            <v-btn target="_blank" href="https://savvy-enly.firebaseapp.com" large class="my-auto mx-auto white white--text" flat fab><v-icon large>remove_red_eye</v-icon></v-btn>
          </v-layout>
        </v-img>
        <v-img v-ripple class="hidden-md-and-up round2 mx-auto" aspect-raito="1.7888" src="savvy-enly-mobile.png" style="max-height: 70vh;"></v-img>
      </v-flex>
    </v-flex>

    <v-flex class="height pa-5">
      <v-flex class="pa-5" style="font-size: 2em; position: absolute; top: 300vh; left: 0; z-index: 1;">
        <h1><span class="pink--text">3/4</span> Enly MVP</h1>
        <p>MVP for mobile fashion app.</p>
      </v-flex>

      <v-flex xs12 md10 offset-md1 lg6 offset-lg3 style="margin-top: 50vh; transform: translateY(-50%);">
        <v-img class="tilt hidden-sm-and-down round2 mx-auto" aspect-raito="1.7888" src="enly.png">
          <v-layout column class="hover fill-height" style="background: #2225;">
            <h1 class="hidden-sm-and-down mx-auto my-auto pink"> Mobile view only</h1>
            <v-btn target="_blank" href="https://enly-app.firebaseapp.com" large class="hidden-md-and-up my-auto mx-auto white white--text" flat fab><v-icon large>remove_red_eye</v-icon></v-btn>
          </v-layout>
        </v-img>
        <v-img v-ripple class="hidden-md-and-up round2 mx-auto" aspect-raito="1.7888" src="enly-mobile.png" style="max-height: 70vh;"></v-img>
      </v-flex>
    </v-flex>

    <v-flex class="height pa-5">
      <v-flex class="pa-5" style="font-size: 2em; position: absolute; top: 400vh; left: 0; z-index: 1;">
        <h1><span class="pink--text">4/4</span> Tuts Tree</h1>
        <p>Web-Dev teaching website</p>
      </v-flex>

      <v-flex xs12 md10 offset-md1 lg6 offset-lg3 style="margin-top: 50vh; transform: translateY(-50%);">
        <v-img class="tilt hidden-sm-and-down round2 mx-auto" aspect-raito="1.7888" src="tuts-tree.png">
          <v-layout column class="hover fill-height" style="background: #2225;">
            <v-btn target="_blank" href="https://tuts-tree.firebaseapp.com" large class="my-auto mx-auto white white--text" flat fab><v-icon large>remove_red_eye</v-icon></v-btn>
          </v-layout>
        </v-img>
        <v-img v-ripple class="hidden-md-and-up round2 mx-auto" aspect-raito="1.7888" src="tuts-tree-mobile.png" style="max-height: 70vh;"></v-img>
      </v-flex>
    </v-flex>

    <v-flex class="height" id="contact">
      <v-flex class="pa-5" style="font-size: 2em; position: absolute; top: 500vh; left: 0; z-index: 1;">
        <h1><v-icon size="60" left class="hidden-sm-and-down mb-2 pink--text">pets</v-icon><v-icon size="30" class="hidden-md-and-up mb-1 mr-1 pink--text">pets</v-icon>Contact</h1>
        <p>Open to offers</p>
      </v-flex>

      <v-layout row wrap class="hidden-sm-and-down" style="margin-top: 50vh; transform: translateY(-50%);">
        <a target="_blank" class="mx-auto" href="https://www.linkedin.com/in/picklenik/">
          <v-avatar v-ripple size="300" class="white scale">
            <img src="https://cdn.freebiesupply.com/logos/large/2x/linkedin-icon-logo-png-transparent.png">
          </v-avatar>
        </a>
        <a target="_blank" class="mx-auto" href="https://www.upwork.com/o/profiles/users/_~01d865e6d937b80c2c/">
          <v-avatar v-ripple size="300" class="white scale">
            <img src="https://i.pinimg.com/originals/77/df/31/77df312c0b02413a40106e6b06dffc17.png">
          </v-avatar>
        </a>
        <a target="_blank" class="mx-auto" href="https://github.com/PickleNik">
          <v-avatar v-ripple size="300" class="white scale">
            <img src="https://magentys.io/wp-content/uploads/2017/04/github-logo-1.png">
          </v-avatar>
        </a>
      </v-layout>
      <v-layout column class="hidden-md-and-up" style="margin-top: 50vh; transform: translateY(-50%);">
        <a target="_blank" class="mx-auto my-3" href="https://www.linkedin.com/in/picklenik/">
          <v-avatar v-ripple size="100" class="white">
            <img src="https://cdn.freebiesupply.com/logos/large/2x/linkedin-icon-logo-png-transparent.png">
          </v-avatar>
        </a>
        <a target="_blank" class="mx-auto my-3" href="https://www.upwork.com/o/profiles/users/_~01d865e6d937b80c2c/">
          <v-avatar v-ripple size="100" class="white">
            <img src="https://i.pinimg.com/originals/77/df/31/77df312c0b02413a40106e6b06dffc17.png">
          </v-avatar>
        </a>
        <a target="_blank" class="mx-auto my-3 black" href="https://github.com/PickleNik">
          <v-avatar v-ripple size="100" class="black">
            <img src="https://magentys.io/wp-content/uploads/2017/04/github-logo-1.png">
          </v-avatar>
        </a>
      </v-layout>
    </v-flex>

  </v-app>
</template>

<script>
import UniversalTilt from 'universal-tilt.js'

export default {
  name: 'App',
  data () {
    return {
      //
    }
  },
  mounted () {
    // eslint-disable-next-line
    VANTA.BIRDS({
      el: '#info',
      quantity: 5.00,
      backgroundColor: 0x0,
      backgroundAlpha: 0.00
    })
    const elems = document.querySelectorAll('.tilt')

    UniversalTilt.init({
      elements: elems,
      settings: {
        // options...
      },
      callbacks: {
        // callbacks...
      }
    })
  }
}
</script>

<style media="screen">
  @import url('https://fonts.googleapis.com/css?family=Montserrat:900');
  * {
    font-family: 'Montserrat'; color: #444;
  }
  @media only screen and (max-width: 960px) {
    h1 {
      font-size: 0.9em;
    }
    p {
      font-size: 0.6em;
    }
  }
  ::-webkit-scrollbar{
    width: 0;
  }
  .height {
    height: 100vh;
  }
  .round1 {
    border-radius: 1em;
  }
  .round2 {
    border-radius: 2em;
  }
  .hover{
    opacity: 0;
    transition-duration: 0.5s;
    transition-timing-function: ease;
    transition-property: all;
  }
  .hover:hover{
    opacity: 1;
  }
  .link {
    text-decoration: none;
    position: relative;
  }
  /* Kukuri */
  .link--kukuri {
    text-transform: uppercase;
    font-weight: 900;
    overflow: hidden;
    line-height: 0.75;
  }

  .link--kukuri:hover {
    color: #E91E63 !important;
  }

  .link--kukuri::after {
    content: '';
    position: absolute;
    height: 6px;
    width: 100%;
    top: 50%;
    margin-top: -4px;
    right: 0;
    background: #E91E63 !important;
    border-radius:1em;
    -webkit-transform: translate3d(-111%,0,0);
    transform: translate3d(-111%,0,0);
    -webkit-transition: -webkit-transform 0.4s;
    transition: transform .3s;
    -webkit-transition-timing-function: cubic-bezier(0.7,0,0.3,1);
    transition-timing-function: cubic-bezier(0.7,0,0.3,1);
  }

  .link--kukuri:hover::after {
    -webkit-transform: translate3d(100%,0,0);
    transform: translate3d(100%,0,0);
  }
  .link--kukuri:hover::before {
    width: 100%;
  }
  .scale {
    transition-duration: 0.5s;
    transition-timing-function: ease-in-out;
    transition-property: all;
  }
  .scale:hover {
    transform: scale(1.1);
  }
</style>
