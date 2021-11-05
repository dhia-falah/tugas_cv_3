<template>
  <body>
    <div id="app" v-for="user in users" :key="user.id">
      <nav>
        <h1>DHIA FALAH RAHMA <span id="e">WARDANI</span></h1>
        <center><img src="AKU.jpg" width="215px" height="320px" /></center>
        <h2>contact</h2>
        <hr style="border: 1px solid gray" />
        <p><b>Address:</b> <br />{{ user.alamat }}</p>
        <p><b>phone:</b> <br />{{ user.phone }}</p>
        <p><b>Email:</b> <br />{{ user.email }}</p>
        <p><b>Linkedin:</b> <br />-</p>
        <h2>languages</h2>
        <hr style="border: 1px solid gray" />
        <ul>
          <li>{{ user.bahasa1 }}</li>
          <li>{{ user.bahasa2 }}</li>
          <li>{{ user.bahasa3 }}</li>
          <li>{{ user.bahasa4 }}</li>
        </ul>

        <h2>Hobbies</h2>
        <hr style="border: 1px solid gray" />
        <ul>
          <li>{{ user.hobi1 }}</li>
          <li>{{ user.hobi2 }}</li>
          <li>{{ user.hobi3 }}</li>
          <li>{{ user.hobi4 }}</li>
        </ul>
      </nav>
      <article>
        <h2>summary</h2>
        <hr style="border: 1px solid gray" />
        <p>{{ user.sumary }}</p>
        <h2>Skill Highlights</h2>
        <hr style="border: 1px solid gray" />
        <ul id="ul">
          <li>{{ user.skill }}</li>
          <li>{{ user.skill1 }}</li>
          <li>{{ user.skill2 }}</li>
          <li>{{ user.skill3 }}</li>
          <li>{{ user.skill4 }}</li>
          <li>{{ user.skill5 }}</li>
        </ul>
        <h2>Experience</h2>
        <hr style="border: 1px solid gray" />
        <p><b>Web Developer </b>- 09/2015 to 05/2019</p>
        <p><b>Luna Web Design, </b>New York</p>
        <ul>
          <li>{{ user.epe }}</li>
          <li>{{ user.epe1 }}</li>
          <li>{{ user.epe2 }}</li>
          <li>{{ user.epe3 }}</li>
          <li>{{ user.epe4 }}</li>
        </ul>
        <h2>Education</h2>
        <hr style="border: 1px solid gray" />
        <P
          >Bacherlor of science: <b>Computer Information Systems </b>- 2014<br /><b
            >Columbia University, </b
          >NY</P
        >
        <h2>Certifications</h2>
        <hr style="border: 1px solid gray" />
        <p>
          PHP Framework (certificate):<b>Zend, Codeigniter, Symfony.</b
          ><br />programming languages:<b
            >JavaScript,HTML5,PHP OOP,CSS,<br />SQL,MySQL.</b
          >
        </p>
      </article>
      <br /><br /><br /><br />
      <div id="pisah"></div>
      <div id="kabeh">
        <div id="iy">
          <div id="jk"><h2>RESUME</h2></div>
          <h1 id="img">
            <div id="v"></div>
            <div id="foto">
              <img src="AKU.jpg" id="foto"/>
            </div>
            <center>DHIA FALAH RAHMA WARDANI</center>
          </h1>
        </div>
        <div id="bar">
          <h2>profile</h2>
          <hr style="border: 1px dotted black" />
          <p><b>NAME</b><br />Dhia Falah Rahma Wardani</p>
          <p><b>DATE OF BIRTH</b><br />06 September 2005</p>
          <p>
            <b>ADDRESS</b><br />Kelurahan Patemon RT02 RW01 GunungPati Kota
            Semarang
          </p>
          <p><b>WEBSITE</b><br />-</p>
          <h2>AWARDS</h2>
          <hr style="border: 1px dotted black" />
          <p><b>CREATIVE AWARDS</b><br />-</p>
          <p><b>INTERFACE DESIGN</b><br />-</p>
          <h2>CONTACT</h2>
          <hr style="border: 1px dotted black" />
          <p><b>HOME NUMBER</b><br />-&#9742;</p>
          <p><b>PHONE NUMBER</b><br />+62 858-0330-3044</p>
          <p><b>EMAIL</b><br />dhiafala@gmail.com</p>
          <h2>SOCIAL</h2>
          <hr style="border: 1px dotted black" />
          <p><b>TWITTER</b><br />-</p>
          <p><b>INSTAGRAM</b><br />d-fala06</p>
          <p><b>FACEBOOK</b><br />Dhia Falah</p>
        </div>
        <div id="all">
          <h3>GRAPHIC ARTIST</h3>
          <hr style="border: 1px solid black" />
          <div id="r">
            <h3>WORK EXPERIENCE</h3>
            <hr style="border: 1px dotted black" />
            <div id="em">
              <p><b>CREATIVE ROOMS</b><br />Feb 2013 - Jun 2014</p>
              <br />
              <p><b>CREATIVE ROOMS</b><br />Feb 2013 - Jun 2014</p>
              <br />
              <p><b>CREATIVE ROOMS</b><br />Feb 2013 - Jun 2014</p>
              <br />
              <p>
                <b>SENIOR ART DIRECTOR</b><br />Lorem ipsum dolor sit amet
                <br />consectetur adipisicing elit.
              </p>
              <p>
                <b>SENIOR ART DIRECTOR</b><br />Lorem ipsum dolor sit amet
                <br />consectetur adipisicing elit.
              </p>
              <p>
                <b>SENIOR ART DIRECTOR</b><br />Lorem ipsum dolor sit amet
                <br />consectetur adipisicing elit.
              </p>
            </div>
          </div>
          <br /><br /><br />

          <div id="t">
            <h3>EDUCATION</h3>
            <hr style="border-style: dotted; color: black" />
            <div id="as">
              <p><b>MASTER DEGREE</b><br />Feb 2011 - Jun 2014</p>
              <p><b>MASTER DEGREE</b><br />Feb 2011 - Jun 2014</p>
              <p><b>MASTER DEGREE</b><br />Feb 2011 - Jun 2014</p>
              <p><b>UNIVERSITY ART DIRECTOR</b><br />Jakarta, Indonesia</p>
              <p><b>UNIVERSITY ART DIRECTOR</b><br />Jakarta, Indonesia</p>
              <p><b>UNIVERSITY ART DIRECTOR</b><br />Jakarta, Indonesia</p>
            </div>
          </div>
          <br />
          <div id="q">
            <h3>SKILLS</h3>
            <hr style="border-style: dotted; color: black" />
            <div id="pop">
              <h4>PROFESSIONAL SKILLS</h4>
              <p>Microsoft Windows</p>
              <p>Windows</p>
              <p>Mac OSX</p>
              <p>Data Hinding</p>
              <p>Record Keeping</p>
              <p>Web Skills</p>
              <h4>PERSONAL SKILLS</h4>
              <p>Organisation</p>
              <p>Communication</p>
              <p>Time Keeping</p>
              <p>Team Player</p>
              <p>Commitment</p>
              <p>Multitasking</p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </body>
</template>
<script>
/* eslint-disable */
import axios from "axios";
export default {
  data() {
    return {
      users: [],
    };
  },
  mounted() {
    this.load();
  },
  methods: {
    load() {
      axios
        .get("http://localhost:3000/users")
        .then((res) => {
          this.users = res.data;
        })
        .catch((err) => {
          console.log(err);
        });
    },
  },
};
</script> 
<style>
* {
  box-sizing: border-box;
}
body {
  font-family: Arial, Helvetica, sans-serif;
  background-color: grey;
}

/*style the header */
header {
  background-color: #666;
  padding: 30px;
  text-align: center;
  font-size: 35px;
  color: white;
}

nav {
  float: left;
  width: 30%;
  height: 100%px;
  background: #ccc;
  padding: 20px;
}

article {
  float: left;
  padding: 20px;
  background-color: white;
  width: 70%;
  height: 1084px;
}

#ul {
  -webkit-column-count: 2;
  -moz-column-count: 2;
  column-count: 2;
}
#e {
  color: red;
}

#bar {
  float: left;
  border: 25px solid white;
  width: 45%;
  text-align: right;
  background-color: white;
}
h1 {
  color: white;
}

#all {
  float: left;
  border: 25px solid white;
  width: 55%;
  height: 15500%;
  background-color: white;
}
#em {
  -webkit-column-count: 2;
  -moz-column-count: 2;
  column-count: 2;
}
#as {
  -webkit-column-count: 2;
  -moz-column-count: 2;
  column-count: 2;
}
#r {
  border: 25px solid rgb(228, 218, 218);
  height: 400px;
  background-color: rgb(228, 218, 218);
}
#t {
  border: 25px solid rgb(228, 218, 218);
  height: 345px;
  background-color: rgb(228, 218, 218);
}
h2 {
  font-family: "Times New Roman", Times, serif;
}
h3 {
  font-family: "Times New Roman", Times, serif;
}

#iy {
  border: 1px solid rgb(1, 1, 24);
  background-color: rgb(1, 1, 24);
}
#q {
  border: 25px solid rgb(228, 218, 218);
  background-color: rgb(228, 218, 218);
}
#pop {
  -webkit-column-count: 2;
  -moz-column-count: 2;
  column-count: 2;
}
#pisah {
  background-color: grey;
  height: 1230px;
}
#foto {
  border-radius: 100px;
  width: 200px;
  height: 200px;
  padding-left: 110px;
  padding-top: 70px;
}
#v {
  background-color: white;
  width: 1314px;
  height: 15px;
}
#jk {
    padding-left: 110px;
  padding-top: 10px;
  background-color: rgb(1, 1, 24);
  color: palevioletred;
}
</style>
