<template>
  <div class="a">
    <div v-for="cd in listCv" :key="cd.id">
      <div class="bg"></div>
      <div class="res">{{ cd.cv1 }}</div>
      <div class="jud" style="font-family: 'Courier New', Courier, monospace">
        <div class="gb" style="margin-left: 10px">
          <div style="text-align: right">
            <img
              class="gm"
              src="https://e7.pngegg.com/pngimages/821/205/png-clipart-sinon-anime-sketch-mangaka-anime-black-hair-manga.png"
              width="200"
              height="200"
              style="border-radius: 100px"
            />
            <h3 style="color: black; text-align: right">
              <font id="bc">{{ cd.cv2 }}</font>
            </h3>
            <hr
              style="
                border: 1px dashed black;
                padding-left: 10px;
                padding-right: 10px;
                margin-left: 20px;
              "
            />
            <p style="color: black">
              <b
                ><font id="db">{{ cd.cv4 }}</font></b
              ><br /><font id="db">{{ cd.cv5 }}</font>
            </p>
            <p style="color: black">
              <b
                ><font id="db">{{ cd.cv6 }}</font></b
              ><br /><font id="db">{{ cd.cv7 }}</font>
            </p>
            <p style="color: black">
              <b
                ><font id="db">{{ cd.cv8 }}</font></b
              ><br /><font id="db">{{ cd.cv9 }}</font>
            </p>
            <p style="color: black">
              <b
                ><font id="db">{{ cd.cv10 }}</font></b
              ><br /><font id="db">{{ cd.cv11 }}</font>
            </p>
            <h3 style="color: black; text-align: right">
              <font id="bc">{{ cd.cv12 }}</font>
            </h3>
            <hr
              style="
                border: 1px dashed black;
                padding-left: 10px;
                padding-right: 10px;
                margin-left: 20px;
              "
            />
            <p style="color: black">
              <b
                ><font id="db">{{ cd.cv13 }}</font></b
              ><br /><font id="db">{{ cd.cv14 }}</font>
            </p>
            <p style="color: black">
              <b
                ><font id="db">{{ cd.cv15 }}</font></b
              ><br /><font id="db">{{ cd.cv16 }}</font>
            </p>
            <h3 style="color: black; text-align: right">
              <font id="bc">{{ cd.cv17 }}</font>
            </h3>
            <hr
              style="
                border: 1px dashed black;
                padding-left: 10px;
                margin-left: 20px;
                padding-right: 10px;
              "
            />
            <p style="color: black">
              <b
                ><font id="db">{{ cd.cv18 }} <span>&#9742;</span></font></b
              ><br /><font id="db">{{ cd.cv19 }}</font>
            </p>
            <p style="color: black">
              <b
                ><font id="db"
                  >{{ cd.cv20 }} <i class="fas fa-phone"></i></font></b
              ><br /><font id="db">{{ cd.cv19 }}</font>
            </p>
            <p style="color: black">
              <b
                ><font id="db">{{ cd.cv21 }} &#9993;</font></b
              ><br /><font id="db">{{ cd.cv22 }}</font>
            </p>
            <h3 style="color: black; text-align: right">
              <font id="bc">{{ cd.cv23 }}</font>
            </h3>
            <hr
              style="
                border: 1px dashed black;
                padding-left: 10px;
                margin-left: 20px;
                padding-right: 10px;
              "
            />
            <p style="color: black">
              <b
                ><font id="db"
                  >{{ cd.cv24 }} <i class="fab fa-facebook-f"></i></font></b
              ><br /><font id="db">{{ cd.cv25 }}</font>
            </p>
            <p style="color: black">
              <b
                ><font id="db"
                  >{{ cd.cv26 }} <i class="fab fa-instagram"></i></font></b
              ><br /><font id="db">{{ cd.cv27 }}</font>
            </p>
          </div>
        </div>
        <div
          class="cb"
          style="
            font-family: 'Courier New', Courier, monospace;
            font-size: 20px;
          "
        >
          <h2>{{ cd.cv28 }}<br />{{ cd.cv29 }} SAPUTRA</h2>
        </div>
      </div>
      <br /><br />
      <div style="margin-left: 270px; margin-top: 5px; margin-right: auto">
        <h2>
          <font id="bc">{{ cd.cv30 }}</font>
          <hr style="border: 1px solid black; margin-right: 20px" />
        </h2>
        <div
          style="
            margin-left: 20px;
            margin-right: 20px;
            background-color: silver;
          "
        >
          <br />
          <h2 style="margin-left: 20px">
            <font id="bc"><i class="fas fa-suitcase"></i> {{ cd.cv31 }}</font>
          </h2>
          <hr
            style="
              border: 1px dashed black;
              padding-left: 10px;
              padding-right: 10px;
              margin-left: 20px;
              margin-right: 20px;
            "
          />
          <div style="display: flex; margin-left: 20px; margin-right: 20px">
            <p>
              <b>{{ cd.cv32 }}</b
              ><br />{{ cd.cv33 }}
            </p>
            <div style="margin-left: 50px">
              <p>
                <b>{{ cd.cv34 }}</b
                ><br />{{ cd.cv35 }}
              </p>
            </div>
          </div>
          <div style="display: flex; margin-left: 20px; margin-right: 20px">
            <p>
              <b>{{ cd.cv37 }}</b
              ><br />{{ cd.cv38 }}
            </p>
            <div style="margin-left: 50px">
              <p>
                <b>{{ cd.cv39 }}</b
                ><br />{{ cd.cv40 }}
              </p>
            </div>
          </div>
          <div style="display: flex; margin-left: 20px; margin-right: 20px">
            <p>
              <b>{{ cd.cv37 }}</b
              ><br />{{ cd.cv38 }}
            </p>
            <div style="margin-left: 50px">
              <p>
                <b>{{ cd.cv39 }}</b
                ><br />{{ cd.cv40 }}
              </p>
            </div>
          </div>
        </div>
        <br />
        <div
          style="
            margin-left: 20px;
            margin-right: 20px;
            background-color: silver;
          "
        >
          <br />
          <h2 style="margin-left: 20px">
            <font id="bc"><i class="fas fa-book"></i> {{ cd.cv41 }}</font>
          </h2>
          <hr
            style="
              border: 1px dashed black;
              padding-left: 10px;
              padding-right: 10px;
              margin-left: 20px;
              margin-right: 20px;
            "
          />
          <br />
          <div style="display: flex; margin-left: 20px; margin-right: 20px">
            <p>
              <b>{{ cd.cv42 }}</b
              ><br />{{ cd.cv43 }}
            </p>
            <div style="margin-left: 50px">
              <p>
                <b>{{ cd.cv44 }}</b
                ><br />{{ cd.cv55 }}
              </p>
            </div>
          </div>
          <div style="display: flex; margin-left: 20px; margin-right: 20px">
            <p>
              <b>{{ cd.cv42 }}</b
              ><br />{{ cd.cv43 }}
            </p>
            <div style="margin-left: 50px">
              <p>
                <b>{{ cd.cv44 }}</b
                ><br />{{ cd.cv55 }}
              </p>
            </div>
          </div>
          <div style="display: flex; margin-left: 20px; margin-right: 20px">
            <p>
              <b>{{ cd.cv42 }}</b
              ><br />{{ cd.cv43 }}
            </p>
            <div style="margin-left: 50px">
              <p>
                <b>{{ cd.cv44 }}</b
                ><br />{{ cd.cv55 }}
              </p>
            </div>
          </div>
        </div>
        <br />
        <div
          style="
            margin-left: 20px;
            margin-right: 20px;
            background-color: silver;
            padding: auto;
          "
        >
          <br />
          <h2 style="margin-left: 20px">
            <font id="bc">SKILLS</font>
          </h2>
          <hr
            style="
              border: 1px dashed black;
              padding-left: 10px;
              padding-right: 10px;
              margin-left: 20px;
              margin-right: 20px;
            "
          />
          <div style="display: flex; margin-left: 20px; margin-right: 20px">
            <p>
              <b>PROFESIONAL SKILLS</b><br /><br />Microsoft Windows
              <i class="fas fa-circle"></i><i class="fas fa-circle"></i
              ><i class="fas fa-circle"></i><i class="fas fa-circle"></i
              ><i class="fas fa-circle"></i><span class="g">&#9899;&#9899;</span
              ><br />Windows<font style="margin-left: 74px">
                <i class="fas fa-circle"></i><i class="fas fa-circle"></i
                ><i class="fas fa-circle"></i><i class="fas fa-circle"></i
                ><i class="fas fa-circle"></i></font
              ><span class="g">&#9899;&#9899;</span><br />Mac OSX
              <font style="margin-left: 67px"
                ><i class="fas fa-circle"></i><i class="fas fa-circle"></i
                ><i class="fas fa-circle"></i><i class="fas fa-circle"></i
                ><i class="fas fa-circle"></i></font
              ><span class="g">&#9899;&#9899;</span><br />Data Handling
              <font style="margin-left: 34px"
                ><i class="fas fa-circle"></i><i class="fas fa-circle"></i
                ><i class="fas fa-circle"></i><i class="fas fa-circle"></i
                ><i class="fas fa-circle"></i></font
              ><span class="g">&#9899;&#9899;</span><br />Record Keeping
              <font style="margin-left: 20px"
                ><i class="fas fa-circle"></i><i class="fas fa-circle"></i
                ><i class="fas fa-circle"></i><i class="fas fa-circle"></i
                ><i class="fas fa-circle"></i></font
              ><span class="g">&#9899;&#9899;</span><br />Web Skills
              <font style="margin-left: 60px"
                ><i class="fas fa-circle"></i><i class="fas fa-circle"></i
                ><i class="fas fa-circle"></i><i class="fas fa-circle"></i
                ><i class="fas fa-circle"></i
                ><span class="g">&#9899;&#9899;</span></font
              >
            </p>
            <div style="margin-left: 50px">
              <p>
                <b>PERSONAL SKILLS</b><br /><br />Organisatoin
                <i style="margin-left: 20px" class="fas fa-circle"></i
                ><i class="fas fa-circle"></i><i class="fas fa-circle"></i
                ><i class="fas fa-circle"></i><i class="fas fa-circle"></i
                ><span class="g">&#9899;&#9899;</span><br />Communication
                <i class="fas fa-circle"></i><i class="fas fa-circle"></i
                ><i class="fas fa-circle"></i><i class="fas fa-circle"></i
                ><i class="fas fa-circle"></i
                ><span class="g">&#9899;&#9899;</span><br />Time Keeping
                <i style="margin-left: 13px" class="fas fa-circle"></i
                ><i class="fas fa-circle"></i><i class="fas fa-circle"></i
                ><i class="fas fa-circle"></i><i class="fas fa-circle"></i
                ><span class="g">&#9899;&#9899;</span><br />Team Player
                <i style="margin-left: 22px" class="fas fa-circle"></i
                ><i class="fas fa-circle"></i><i class="fas fa-circle"></i
                ><i class="fas fa-circle"></i><i class="fas fa-circle"></i
                ><span class="g">&#9899;&#9899;</span><br />Commitment
                <i style="margin-left: 21px" class="fas fa-circle"></i
                ><i class="fas fa-circle"></i><i class="fas fa-circle"></i
                ><i class="fas fa-circle"></i><i class="fas fa-circle"></i
                ><span class="g">&#9899;&#9899;</span><br />Multitasking
                <i style="margin-left: 27px" class="fas fa-circle"></i
                ><i class="fas fa-circle"></i><i class="fas fa-circle"></i
                ><i class="fas fa-circle"></i><i class="fas fa-circle"></i
                ><span class="g">&#9899;&#9899;</span>
              </p>
            </div>
          </div>
        </div>
      </div>
    </div>
    <br /><br />
    <div class="ah"></div>
  </div>
</template>


<script>
/* eslint-disable */
import axios from "axios";
export default {
  data() {
    return {
      listCv: [],
    };
  },
  mounted() {
    this.load();
  },
  methods: {
    load() {
      axios
        .get("http://localhost:3000/listCv")
        .then((res) => {
          this.listCv = res.data;
        })
        .catch((err) => {
          console.log(err);
        });
    },
  },
  name: "Project2",
  computed: {
    Project2() {
      return this.$store.state.Project2;
    },
  },
};
</script>

<style>
#bc {
  font-family: Courier;
  font-size: 30px;
}
#db {
  font-family: Arial;
}
span {
  content: "\260E";
}
.a {
  height: 1125px;
  background-color: white;
  margin-right: 20px;
  margin-left: 20px;
  padding-bottom: 220px;
  font-family: Arial;
}
.bg {
  background-color: darkslateblue;
  height: 40px;
}
.res {
  background-color: darkslateblue;
  height: 1px;
  margin-left: 70px;
  width: 130px;
  font-family: Arial;
  color: white;
  font-size: 20px;
  text-align: center;
  padding-bottom: 25px;
}
.jud {
  background-color: darkslateblue;
  height: 100px;
  font-family: Arial;
  color: white;
  display: flex;
}
.gb {
  padding-top: 30px;
}
.gm {
  width: 200px;
  height: 200px;
  display: flex;
  border-radius: 50%;
  margin-left: 20px;
}
.cb {
  margin-left: 10px;
  font-family: Arial;
}
body {
  margin-left: 200px;
  margin-right: 200px;
  margin-bottom: 50px;
}
.g {
  opacity: 0.5;
}
.ah {
  background-color: darkslateblue;
  height: 40px;
}
</style>