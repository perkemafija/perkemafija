/*Colours and fonts*/

body{
	background-color: rgb(250,250,250);
	text-align: center;

	}

.img-circle{
	border-radius: 0%;
	border-spacing: 5px;
	border-width: 5px;
}
.img-profile{
    border-radius: 50%;
	border-width: 150px;
	border-spacing: 10px
}
h1{
	font-style:italic;
	font-size: 50px;
	font-weight: bold;
	font-family: 'Times New Roman', monospace;
	color: rgb(240, 240, 240);
}

h2{display: inline-block;
    font-size: 35px;
    font-weight: bolder;
    font-family: 'Oswald', sans-serif;
    color: rgb(240, 240, 240);
}

p{font-weight: bold;
	font-size: 20px;
	font-style:italic;
	font-family: 'garamond', cursive;
	font-synthesis: inherit;
	color: rgb(240, 240, 240);
}
.btn-brown{ padding: 10px 10px 10px 10px;
	text-decoration: none;
	background-color: rgb(230,230,230);
	color:rgb(30,30,30);
	font-weight: bold;
	font: 'Helvetica', cursive;
	border: 5px;
	border-radius: 10px
}
.btn-brown:hover{
	color:rgb(255, 210, 63);
	cursor: pointer;
	background-color: rgb(130, 51, 41);
}

.container{ 
	padding: 30px
	border-radius:4px;
}

.Card {
  background-color: rgb(30, 30, 30);
  padding: 20px 20px 20px 40px;
  border: 5px;
  border-radius: 30px;
  margin: 50px 50px 50px 50px;
  box-shadow: 10px 10px 30px rgba(0,0,0);
  overflow: hidden;
}
.list-inline {
  list-style: none;
  padding-left: 0px 20px;
}
.list-inline > li {
  display: inline;
  padding: 0px 20px;
}
.sidebar {
  position: top-left;
  width: 200px;
  left: 20px;
  top: 20PX;
  bottom: 20px;
}
.page-content {
  margin-left: 200px;
}
.sidebar ul { 
  list-style: none;
  padding-left: 0px;
  font-family: 'Helvetica' , cursive;
  font-size: 17px;
  font-weight: lighter;
}
a{
	padding: 10px 10px 10px 10px;
	border: 5px;
	border-radius: 10px;#
	text-decoration: none;
}

@media (max-width: 960px) {
  /* For a screen < 960px, this CSS will be read */
  .container {
    width: 860px;
  }
}
@media (max-width: 870px) {
  /* For a screen < 720px, this CSS will be read */
  .container {
    width: 770px;
  }
}
@media (max-width: 780px) {
  /* For a screen < 540px, this CSS will be read */
  .container {
    width: 540px;
  }
 @media (max-width: 550px) {
  /* For a screen < 960px, this CSS will be read */
  .container {
    width: 460px;
  }
}
@media (max-width: 480px) {
  /* For a screen < 720px, this CSS will be read */
  .container {
    width: 330px;
  }
}
@media (max-width: 340px) {
  /* For a screen < 540px, this CSS will be read */
  .container {
    width: 200px;
  }
}
