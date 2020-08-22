# Website-design

<!DOCTYPE html>
<html lang="en" dir="ltr">
  <head>
    <meta charset="utf-8">
    <title></title>
    <link rel="stylesheet" href="Project_01_Final.css">
    <style>
      *{
  margin:0;
  padding:0;
  font-family: Century Gothic;
}
body {
  background-image:linear-gradient(rgba(0,0,0,0.5),rgba(0,0,0,0.5)), url(back.jpg);
  background-size: cover;
}
ul {
  float:right;
  list-style-type: none;
  padding: 5px;
  margin: 5px;
}

ul li {
  display: inline;

}
 ul li a{
   text-decoration: none;
   color: white;
   padding: 7px 10px;
   border: 1px solid transparent;
 }
 ul li a:hover{
   color:#000;
   background-color: #fff;
   transition: 0.6s ease;
 }
ul li.active a{
  color:#000;
  background-color: #fff;
}
 .logo {
    float: left;
    width: 150px;
    height: auto;
    margin-left: 20px;
    margin-top: 8px;
    transition: 0.6s ease;
    border: 1px solid black;
    padding: 5px;
 }
 img:active{
   color:#000;
   background-color: #fff;
 }
 .logo:hover{
   background-color: #fff;
   cursor: pointer;
 }

 #tit {
   position: absolute;
   top: 250px;
   left: 100px;
   right: 50px;
 }
 #title{
   color: #fff;
   font-size: 4em;
   font-family: Century Gothic;
   text-align: center;
}
.btn{
  position: absolute;
  top: 350px;
  left: 550px;
  right: 50px;
}
#btns{
  border: 1px solid #fff;
  padding: 10px;
  text-decoration: none;
  color: #fff;
}
#btns:hover{
  background-color: #fff;
  color: #000;
}
    </style>
  </head>
  <body>
    <nav>
      <div class="main">
        <ul>
          <li class="active"><a href="#">Home</a></li>
          <li><a href="#">Services</a></li>
          <li><a href="#">Gallery</a></li>
          <li><a href="#">About</a></li>
          <li><a href="#">Contact</a></li>
        </ul>
      </div>
      <div id="active">
        <img src="logo.jpg" class="logo" alt="">
      </div>
    </nav>
    <div id="tit">
      <h1 id="title">WEBDEV CREATIONS</h1>
    </div>
    <div class="btn">
      <a href="#" id="btns">WATCH VIDEO</a>
      <a href="#" id="btns">EXPLORE MORE</a>
    </div>
  </body>
</html>
