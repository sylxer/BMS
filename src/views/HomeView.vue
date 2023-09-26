<template>
  <v-app id="home">
    <NavBar />
    <v-container fluid>
      <div class="head">
        <v-row>
          <v-col cols="5">
            <div style="position: relative" class="mt-16">
              <h1 class="text-grey">Hello,</h1>
              <h1 class="text-white">We're From Group 3</h1>
              <span class="text-grey">Basic Media Schooling</span><br />

              <v-btn tile dark class="text-yellow mt-8" variant="outlined">
                Contact
              </v-btn>
            </div>
          </v-col>
          <v-col cols="2">
            <div
              style="
                position: absolute;
                z-index: 9999;
                bottom: 0;
                margin-left: auto;
                margin-right: auto;
                left: 0;
                right: 0;
                text-align: center;
              "
              class="mt-16"
            >
              <v-icon>fas fa-angle-double-down</v-icon>
            </div>
          </v-col>
          <v-col cols="5">
            <div style="position: relative; z-index: 9999" class="mt-16">
              <v-img src="../assets/Team.png" contain max-height="280"></v-img>
            </div>
          </v-col>
        </v-row>
      </div>
      <v-col cols="12" class="mt-16" id="about">
        <div>
          <v-row>
            <v-col cols="12" sm="6">
              <div class="egg">
                <v-img src="../assets/camera.png" max-height="250" class=""></v-img>
              </div>
            </v-col>
            <v-col cols="12" sm="6">
              <h5 class="mt-16">About</h5>
              <div style="width: 120px">
                <v-slider
                  v-model="slider2"
                  color="yellow"
                  label="track-color"
                ></v-slider>
              </div>
              <h4 class="mt-n4">BMS 2023</h4>
              <h4 class="">Basic Media Schooling HMIT 2023</h4>
              <p class="text-grey">
                Basic Media Schooling (BMS) HMIT 2023 adalah program pelatihan yang dirancang khusus
                untuk membantu peserta mengembangkan keterampilan mereka dalam bermedia informasi.
                Tujuan utama dari BMS adalah untuk memberikan pemahaman yang mendalam tentang media
                informasi dan memberikan peserta pelatihan praktis untuk menguasai berbagai aspek dalam bermedia.
              </p>
              <br />
              <p class="text-grey">
                Materi pelatihan media yang mencakup fotografi, videografi, jurnalistik, pers, penulisan,
                desain, dan dasar-dasar website menawarkan wawasan yang komprehensif dalam dunia media modern.
                Semua ini merupakan landasan penting untuk berkarir di dunia media yang terus berkembang dan berubah
                dengan cepat.
              </p>
            </v-col>
          </v-row>
        </div>
      </v-col>
      <div class="text-center mt-4">
        <h2>What we Do</h2>
        <div style="width: 120px; margin: 0 auto">
          <v-slider
            v-model="slider2"
            color="yellow"
            label="track-color"
          ></v-slider>
        </div>
      </div>
      <v-col cols="12" class="padd">
        <div class="first" id="project">
          <v-row>
            <v-col cols="12">
              <div class="child">
                <v-btn
                  icon="fas fa-laptop"
                  color="#FBDF7E"
                  class="text-white"
                ></v-btn>
                <h3 class="ml-3 mt-4">Design</h3>
                <p class="text-grey ml-3 mt-4 text-caption">
                  Kami merancang dengan menggunakan Figma <br />Figma memudahkan kami
                  <br />membuat desain yang berkualitas.
                </p>
              </div>
              <div class="child">
                <v-btn
                  icon="fas fa-laptop"
                  color="#FBDF7E"
                  class="text-white"
                ></v-btn>
                <h3 class="ml-3 mt-4">Coding</h3>
                <p class="text-grey ml-3 mt-4 text-caption">
                  Mengembangkan Website dengan menggunakan Vue.js <br />Dengan Vue.js, kami dapat mengembangkan 
                  <br />fitur-fitur dinamis dengan mudah
                </p>
              </div>
              <div class="child">
                <v-btn
                  icon="fas fa-laptop"
                  color="#FBDF7E"
                  class="text-white"
                ></v-btn>
                <h3 class="ml-3 mt-4">Deployment</h3>
                <p class="text-grey ml-3 mt-4 text-caption">
                  Mendeploy Website menggunakan layanan<br /> Vercel adalah platform hosting
                  <br />yang kuat dan user-friendly
                </p>
              </div>
            </v-col>
          </v-row>
          <v-divider></v-divider>
        </div>
      </v-col>

      <v-col cols="12" id="team">
        <div class="pre">
          <h1 class="mb-4">Team</h1>
          <v-row>
            <v-col cols="12" sm="3">
              <v-card class="mx-auto" max-width="300" height="">
                <v-img src="../assets/Fazrul.jpg" height="200px" cover></v-img>

                <v-card-title> Fazrul Ahmad Fadhilah </v-card-title>

                <v-card-subtitle>
                  5027221025 | 8/4/2005
                </v-card-subtitle>
                <v-card-text>
                  Saya berasal dari Bandung, Jawa Barat. 
                  Kepribadian saya adalah ESFP-T. Salah satu hobi saya adalah mendengarkan music.
                </v-card-text>
              </v-card>
            </v-col>
            <v-col cols="12" sm="3">
              <v-card class="mx-auto" max-width="300" height="">
                <v-img src="../assets/Steven.jpeg" height="200px" cover></v-img>

                <v-card-title> Steven Figo </v-card-title>

                <v-card-subtitle>
                  5027221021 | 11/30/2004
                </v-card-subtitle>
                <v-card-text>
                  Saya berasal dari Sibolga, Sumatera Utara.
                  Salah satu kegemaran saya yang saya nikmati adalah bernyanyi.
                </v-card-text>
              </v-card>
            </v-col>
            <v-col cols="12" sm="3">
              <v-card class="mx-auto" max-width="300" height="">
                <v-img src="../assets/Zaki.jpg" height="200px" cover></v-img>

                <v-card-title> Naufan Zaki Luqmanulhakim </v-card-title>

                <v-card-subtitle>
                  5027221065 | 2/5/2004
                </v-card-subtitle>
                <v-card-text>
                  Saya adalah Naufan Zakii, berasal dari Tangerang Selatan, Banten.
                  Follow akun Instagram pribadi saya, @naufanzakii.
                </v-card-text>
              </v-card>
            </v-col>
            <v-col cols="12" sm="3">
              <v-card class="mx-auto" max-width="300" height="">
                <v-img src="../assets/Syl.jpg" height="200px" cover></v-img>

                <v-card-title> Sylvia Febrianti </v-card-title>

                <v-card-subtitle>
                  5027221019 | 2/14/2004
                </v-card-subtitle>
                <v-card-text>
                  Hallo semua! Saya berasal dari Bangka Belitung. Jangan lupa kunjungi akun Instagram saya di @sylviafebriantii.
                </v-card-text>
              </v-card>
            </v-col>
          </v-row>
        </div>
      </v-col>

      <v-col cols="12" id="karya">
        <div class="pre">
          <h1 class="mb-4">Karya</h1>
          <v-row>
            <v-col cols="12" sm="3">
              <v-card class="mx-auto" max-width="300" height="">
                <v-img src="../assets/kalku.jpg" height="200px" cover></v-img>

                <v-card-title> kalkulator </v-card-title>

                <v-card-subtitle>
                  Fazrul Ahmad Fadhilah
                </v-card-subtitle>
                <v-card-text>
                  Pembuatan kalkulator menggunakan HTML dan JavaScript, yang berfungsi selayaknya kalkulator.
                </v-card-text>
              </v-card>
            </v-col>
            <v-col cols="12" sm="3">
              <v-card class="mx-auto" max-width="300" height="">
                <v-img src="../assets/iot.png" height="200px" cover></v-img>

                <v-card-title> Project IOT Club </v-card-title>

                <v-card-subtitle>
                  Steven Figo
                </v-card-subtitle>
                <v-card-text>
                  Mengoperasikan Kamera ESP dan mengidentifikasi objek menggunakan bahasa pemrograman python.
                </v-card-text>
              </v-card>
            </v-col>
            <v-col cols="12" sm="3">
              <v-card class="mx-auto" max-width="300" height="">
                <v-img src="../assets/petani.jpg" height="200px" cover></v-img>

                <v-card-title> Petani Kerja </v-card-title>

                <v-card-subtitle>
                  Naufan Zaki Luqmanulhakim
                </v-card-subtitle>
                <v-card-text>
                  Website untuk mencari kerja yang dapat menampilkan beberapa informasi dari perusahaan perusahaan.
                </v-card-text>
              </v-card>
            </v-col>
            <v-col cols="12" sm="3">
              <v-card class="mx-auto" max-width="300" height="">
                <v-img src="../assets/movie.png" height="200px" cover></v-img>

                <v-card-title> EventSphere </v-card-title>

                <v-card-subtitle>
                  Sylvia Febrianti
                </v-card-subtitle>
                <v-card-text>
                  Website yang berfungsi seperti TIX ID yang dapat memesan tiket bioskop secara online, disini kita dapat memilih kursi, tanggal, dll.
                </v-card-text>
              </v-card>
            </v-col>
          </v-row>
        </div>
      </v-col>

      <v-col cols="12" sm="12" class="px-16" id="contact">
        <v-row>
          <v-col cols="12" sm="4">
            <div class="child">
              <h1>Contact info.</h1>
              <v-btn
                icon="fas fa-map-marker-alt"
                color=""
                class="mt-10"
                variant="outlined"
              ></v-btn
              ><br />
              <span class="text-caption">Your Street SYO,yourArea Dream </span
              ><br />
              <v-btn
                icon="fas fa-phone-alt"
                color=""
                class="mt-10"
                variant="outlined"
              ></v-btn
              ><br />
              <span class="text-caption">00235 - 6521 </span> <br />
              <span class="text-caption">00235 - 6521 </span> <br />
              <v-btn
                icon="fas fa-envelope"
                color=""
                class="mt-10"
                variant="outlined"
              ></v-btn
              ><br />
              <span class="text-caption">aaeideapro@gmail.com </span> <br />
              <span class="text-caption">aaeideapro@gmail.com </span> <br />
            </div>
          </v-col>
          <v-col cols="12" sm="8">
            <h1 class="mt-8">Send your message</h1>
            <v-divider></v-divider>
            <span class="text-caption"
            >Jika ada pertanyaan, saran, maupun kritik, silahkan kirimkan pesan kepada kami di bawah ini!</span
            >
            <v-row class="mt-10">
              <v-col cols="12" sm="6">
                <v-text-field
                  label="Name"
                  persistent-hint
                  variant="outlined"
                ></v-text-field>
              </v-col>
              <v-col cols="12" sm="6">
                <v-text-field
                  label="Phone No"
                  persistent-hint
                  variant="outlined"
                ></v-text-field>
              </v-col>
            </v-row>
            <v-textarea
              label="Message"
              persistent-hint
              variant="outlined"
            ></v-textarea>
            <v-btn color="#FBDF7E" class="mt-2">Submit Now</v-btn>
          </v-col>
        </v-row>
      </v-col>
    </v-container>
    <FooterView />
  </v-app>
</template>

<script>
import { defineComponent } from "vue";
import NavBar from "../components/NavBar.vue";
import FooterView from "../components/FooterView.vue";

// Components
//import HelloWorld from '../components/HelloWorld.vue';

export default defineComponent({
  name: "HomeView",
  setup() {
    return {
      slider2: 50,

      items: [
        {
          img: "i3.jpg",
        },
        {
          img: "i4.jpg",
        },
        {
          img: "i5.jpg",
        },
        {
          img: "i6.jpeg",
        },
        {
          img: "i9.jpg",
        },
        {
          img: "i8.jpg",
        },
      ],
    };
  },
  components: {
    NavBar,
    FooterView,
  },
});
</script>
<style scoped>
.v-container {
  padding: 16px 0 16px 0;
}

.head {
  position: relative;
  text-align: center;
  padding: 12px;
  margin-bottom: 6px;
  height: 400px;
  width: 100%;
  color: white;
}
.head:before {
  content: "";
  position: absolute;
  top: 0;
  left: 0;
  height: 100%;
  width: 50%;
  background: black;
  transform: skew(0deg, 6deg);
}
.head:after {
  content: "";
  position: absolute;
  top: 0;
  right: 0;
  height: 100%;
  width: 50%;
  background: black;
  transform: skew(0deg, -6deg);
}
.egg {
  display: block;
  margin-left: 100px;
  margin-top: 50px;
  width: 356px;
  height: 300px;
  background-color: #fbdf7e;
  border-radius: 50% 50% 50% 50% / 60% 60% 40% 40%;
}
.first {
  width: 100%;
  height: 280px;
  text-align: center;
  padding: 2rem 2rem;
}
.child {
  display: inline-block;
  padding: 2rem 1rem;
  vertical-align: middle;
  text-align: center;
  margin-right: 8px;
}
.imgHover {
  padding: 0 200px;
}
.pre {
  width: 100%;
  height: 470px;
  text-align: center;
  padding: 0 200px;
  background-color: #f5f5f5;
}
.hire {
  width: 100%;
  height: 200px;
  padding: 0 200px;
  background-color: #e9e9e9;
  margin-top: -24px;
}
</style>