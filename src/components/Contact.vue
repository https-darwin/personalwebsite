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
         <li><a href="Contact.html">Contact</a></li>
         </ul>
        </div>
      </div>
    </div>
	<div class="aside">
	<h1 style="color:gold">My Profile</h1>
	<img class="foto" src="../assets/img/foto.jpg">
	<p style="color:white;">Name : Raja Darwin</p>
	<p style="color:white;">DOB : June, 12<sup>th</sup> 2001</p>
	<p style="color:white;">Age : 19</p>
	<p style="color:white;"> Currently studying Informatics</p>
	</div>

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
  text-align: center;
  background: #251A4E;
  color: white;
  font-size: 30px;
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
	margin-bot:100px;
	
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
</style>
