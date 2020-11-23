<template>
  <div class="hello">
    <div class="menu">
        <h1 style="color:gold">Raiden</h1>
        <p style="color:yellow" >The Ordinary Random Guy</p>
      <div class="menu-item">
        <div class="menu-text">
        <ul>
         <li><a href="Home.html">Home</a></li>
         <li><a href="Register.html">Register</a></li>
         <li><a href="../components/Contact.html">Contact</a></li>
         </ul>
        </div>
      </div>
    </div>
  <body>
	<div class="aside">
	<h1 style="color:gold">My Profile</h1>
	<img class="foto" src="../assets/img/foto.jpg">
	<p style="color:white;">Name : Raja Darwin</p>
	<p style="color:white;">DOB : June, 12<sup>th</sup> 2001</p>
	<p style="color:white;">Age : 19</p>
	<p style="color:white;"> Currently studying Informatics</p>
	</div>
        <div class="article4" style="background-color:#251A4E">
        <h1 class="title" style="color:yellow; margin-top:75px; margin-bottom:50px;">You can contact me here!</h1>
        <h2 align="center" style="color: white" class="raja"> Raja Darwin a.k.a Raiden </h2>
        <p align="center" style="color: white">Be yourself, and never surrender
        <br>
        <a href="https://steamcommunity.com/id/rajadarwin" target="_blank"><img src="../assets/img/steamgan.png"  style="width:40px; height:40px;"  class="logo"/></a>
        <span class="tab"></span>
        <a href="https://www.facebook.com/raja.darwin/" target="_blank"><img src="../assets/img/fb1.png"  style="width:40px; height:40px;"  class="logo"/></a>
        <span class="tab"></span>
        <a href="https://www.youtube.com/channel/UCdQ5WmreOBQcT2pcc8h7-Qg" target="_blank"><img src="../assets/img/yt.png"  style="width:40px; height:40px;"  class="logo"/></a>
        <br>
        </p>
        </div>
        <div class="article2" style="background-color:#251A4E">
        <h2 style="color: gold">Introduction</h2>
        <p style="color: white">Darwin a.k.a Raiden </p>
        <p style="color:white;">Hi everyone! my name is Raja Darwin. I'm from Indonesia. I was born on June, 12<sup>th</sup> 2001. My favorite hobby is playing games. I love to play game so much. I can't do that anymore like before because of a lot of work in my college. It's really okay for me. I don't have many photos, But this is me with my sister, Ratu and the Beatles. If you wanna be my friend please click <cite><a href="Register.html" style="color:yellow">Register to be a friend</a></cite> here. </p>
        <img class="beatles" src="../assets/img/beatles.jpg">
        </div>
        <div class="article3" style="background-color:#251A4E">
        <h2 style="color: gold">My Favorite Food</h2>
        <p style="color: white">Spaghetti </p>
        <p style="color:white;">Spaghetti is one of the best dishes i've ever eat. It comes from Italy. It looks like a noodle but it has a bit bigger size. Bolognese sause is amazing. I really love it.</p>
        <img class="spaghetti" src="../assets/img/spaghetti.jpeg" >
        </div>
        <div class="article1" style="background-color:#251A4E">
        <h2 style="color: gold">My Favorite Kamen Rider</h2>
        <p style="color: white">Kamen Rider Gaim </p>
        <p style="color:white;">Kamen rider gaim is the fifteenth kamen rider in the heisei era. Its strength comes from lockseed. Kamen Rider in this series has the theme of fruit. As we can see, the gaim itself has an orange fruit theme. His special move is orange squash. I like this kamen rider because it has a very good design, and epic story.</p>
        <img class="gaim" src="../assets/img/krgaim.png" >
        </div>
        </body>
        </div>
</template>

<script>
export default {
  name: 'Home',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.name {
  display: flex;
  align-items: center;
  justify-content: center;
  vertical-align: middle;
  width: 100vw;
  height: calc(100vh - 60px);
}
.letter {
  margin: .8%;
  filter: drop-shadow(0px 0px 7px rgba(150, 150, 150, .7));
}
.letter-image {
  width: 100%;
}

.menu {
  font-family: Cambria, "Hoefler Text", "Liberation Serif", Times, "Times New Roman", "serif";
  padding-top:40px;
  padding-bottom:5%;
  text-align: center;
  background: #251A4E;
  color: white;
  font-size: 30px;
  margin-bottom:0%
}

.menu-item {
  flex: 1;
  text-align: center;
  display: flex;
  justify-content: center;
  align-items: center;
}

.menu-text{
  font-family: Impact, Haettenschweiler, 'Arial Narrow Bold', sans-serif;
  font-size: 20px;
  color: #818181;
  cursor: pointer;
  padding: 10px;
  width: fit-content;
}


.menu-center {
  font-family: Impact, Haettenschweiler, 'Arial Narrow Bold', sans-serif;
  font-size: 36px;
  color: #EAEAEA;
}

.aside {
  flex-grow: 2;
    flex-basis: 25%;
  padding-bottom:20px;
  margin-left:15%;
  margin-top:4%;
  font-family: Cambria, "Hoefler Text", "Liberation Serif", Times, "Times New Roman", "serif";
  text-align:center;
  border: thin solid white;
  position: absolute;
  right: 3%;
  width: 20%;
  background: #251A4E;
  border-radius: 12%;
}

ul {
  font-family: Cambria, "Hoefler Text", "Liberation Serif", Times, "Times New Roman", "serif";
  list-style-type: none;
  margin: 0;
  padding: 0;
  overflow: hidden;
  background-color: #1f4068 ;
  position: sticky;
  top: 0;
  left:0;
  bottom:0;
  width:100%;
  display:flex;
  align:center;
  font-size: 15px;
  margin-top:30px;
  
}

li {
  float: left;
  margin-left: auto;
  margin-right: auto;
}

li a {
  display: block;
  color: white;
  padding-left: 70px;
  padding-top: 16px;
  padding-bottom: 16px;
  padding-right: 70px;
  text-decoration: none;
}

li a:hover {
  background-color: gold;
  color:black;
}

.foto{
	height:50%;
	width:50%;
	border-radius: 50%;
  align:center;
  border-style: solid;
  border-color: gold;
}

.foto:hover {
  background-color: orangered;
  box-shadow:
        0 0 40px 1px 	#FFA500,  
        0 0 40px 1px 	#FFA500; 
}

.article2 {
	font-family: Cambria, "Hoefler Text", "Liberation Serif", Times, "Times New Roman", "serif";
	padding-top:20px;
	padding-left:40px;
	padding-right:20px;
	padding-bottom:70px;
	margin-left: 50px;
	border: thin solid white;
	width:65%;
	border-radius: 5%;
	margin-top:50px;
	margin-bottom:50px;
	
}

.article4 {
	font-family: Cambria, "Hoefler Text", "Liberation Serif", Times, "Times New Roman", "serif";
	padding-top:20px;
	padding-left:40px;
	padding-right:20px;
	padding-bottom:70px;
	margin-left: 50px;
	border: thin solid white;
	width:65%;
	border-radius: 5%;
	margin-top:4%;
	margin-bottom:50px;
	
}

.beatles {
  height:60%;
	width:80%;
	display: block;
  margin-left: auto;
  margin-right: auto;
}

.article1 {
	font-family: Cambria, "Hoefler Text", "Liberation Serif", Times, "Times New Roman", "serif";
	padding-top:20px;
	padding-left:40px;
	padding-right:20px;
	padding-bottom:20px;
	margin-left: 50px;
	border: thin solid white;
	width:65%;
	border-radius: 5%;
	margin-top:100px;
	margin-bottom:100px;
	
}

.article3 {
	font-family: Cambria, "Hoefler Text", "Liberation Serif", Times, "Times New Roman", "serif";
	padding-top:20px;
	padding-left:40px;
	padding-right:20px;
	padding-bottom:40px;
	margin-left: 50px;
	border: thin solid white;
	width:65%;
	border-radius: 5%;
	margin-top:100px;
	margin-bot:100px;
	
}

.spaghetti {
  height:40%;
	width:60%;
	display: block;
  margin-left: auto;
  margin-right: auto;
}

.gaim {
	height:80%;
	width:40%;
	display: block;
  margin-left: auto;
  margin-right: auto;
}

h1.title{
  text-align: center;
  color: red;
  padding: 0;
  margin: 0;
  font-style: solid;

}

.logo{
  align-content: center;
	border: 1px solid;
  border-color: red;
	margin-top:40px;
	border-radius: 50%;
	background-color: #FFFF00;
  box-shadow:
        0 0 5px 1px blue,  
        0 0 5px 1px 	blue; 
}
.logo:hover {
  background-color: orangered;
  box-shadow:
        0 0 15px 1px 	blue,  
        0 0 15px 1px 	blue; 
  color: white;
}

 .tab { 
  display: inline-block; 
  margin-left: 5px; 
} 

body {
  padding-top:0.001%;
	margin:0;
	font-family: Arial, Helvetica, sans-serif;
	background-color: #1b1b2f;
	opacity:inherit;
}
</style>
