@import url('https://fonts.googleapis.com/css2?family=Roboto+Slab:wght@700&display=swap');

@import url('https://fonts.googleapis.com/css2?family=Alex+Brush&display=swap');

* {text-align: left;
margin: 0 auto;
font-family: Verdana, Tahoma, Trebuchet;}

main {background-color: white ;
margin-left:  auto;
margin-right:  auto;
width: 100%;
color:  #333;
animation: fadeInAnimation ease 3s;
animation-iteration-count: 1;
animation-fill-mode: forwards;
}

a {text-decoration: none;}

/*animation when page opens*/
@keyframes fadeInAnimation {
    0% {
        opacity: 0;
    }
    100% {
        opacity: 1;
     }
} 

/*scroll with static image in the bg*/
.parallax {
  /* The image used */
  background-image: url("korosh-field.jpg");

  /* Set a specific height */
  min-height: 600px; 

  /* Create the parallax scrolling effect */
  background-attachment: fixed;
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
}

/*Title Personlig tränare Korosh Moradi*/
#namn {text-align: center;
min-height: 50px;
max-width: 100%;
min-width: 250px;
font-family: 'Roboto Slab', serif;
font-size: 70px;
color: white;
padding-top: 200px;
}

/*Vad kan hjälpa dig med? menu*/
.menu {max-width: 100%;
margin-top: 0px;
background-color: #333;
text-align: center;
padding-bottom: 50px;
justify-content: space-around;
}

/*Vad jag kan hjälpa med?*/
#hjälpa-med {text-align: center;
color: white;
font-family: 'Roboto Slab', serif;
padding-top: 50px;
margin-bottom: 20px;
letter-spacing: 1px;}

/*Vad jag kan hjälpa mig? val*/
.menu-länk {text-align: center;
background-color: white;
border:  2px solid rgb(221, 222, 223);
margin-left: 50px;
margin-right: 50px;
margin-top: 20px;
min-height: 40px;
display: flex;
flex: 1 1 0%;
font-size: 18px;
text-align: center;
align-content: center;
align-items: center;
justify-content: center;
letter-spacing: 1px;
font-family: Open Sans, Verdana, Arial, sans-serif;
color: #333;}

.menu-länk a {color:  #333;}

.menu-länk:hover {border-color:  #FFA700;
cursor: pointer;}

/*Text + round image*/
.flex-box {width: 80%;
margin-top: 60px;
}

.flex-box::after {
  content: "";
  clear: both;
  display: table;
}

#kom-igång, #presentation {margin-bottom: 20px;
margin-top: 20px;}

/*Round image 1*/
#gym {float: left;
  border-radius:50%;
  margin-right: 50px;
}

/*Round image 2 near presentation*/
#pt-korosh {float: right;
  border-radius:50%;
  margin-left: 50px;}

/*SMALL SCREEN*/
@media only screen and (max-width: 680px){

  .flex-box {
  display: flex;
  flex-direction: column;
   margin: 30px;
}

#gym, #pt-korosh {
  margin-right: auto;
  margin-left: auto;

}

.article {text-align: left;
}

}

/*END SMALL SCREENS*/

/*Button kontakta mig*/
.button {
  background-color: #FFA700;
  border: none;
  color: black;
  padding: 15px 32px;
  text-align: center;
  text-decoration: none;
  display: inline-block;
  font-size: 20px;
  margin: 10px;
  cursor: pointer;
}

.button a {color:  black;}
.button:hover {background-color: #DB8F00;}

/*div for Program*/
#prislista {
margin: 30px;
text-align: left; }

h2 {font-family: 'Roboto Slab', sans-serif;
font-style: italic;
text-transform: uppercase;
font-size: 32px;
letter-spacing: 1px;
}

h3 {font-family: 'Roboto Slab', sans-serif;
font-size: 22px;
color: #333;
margin-bottom: 10px;}

.italic {font-style: italic;
font-weight: lighter;}

/*gallery of pictures*/
#gallery {display: inline-block;
text-align: center;
margin-top: 30px;
margin-bottom: 30px;
}

/*every picture in the gallery*/
.bild {width: 20%;
height: 20%;}


/*FOOTER*/
footer {background-color: #333;
margin-top: 30px;
padding: 30px;
color:  white;
display: flex;
flex-direction: row;
flex-wrap: wrap;}

.h2-footer {color:  white;
margin-bottom: 20px;
font-family: 'Roboto Slab', serif !important;}

#kontakt a {color: #FFA700;
text-decoration: none; 
margin-left:  7px;}

#kontakt a:hover {color: #DB8F00; }

#citat {font-family: 'Roboto Slab', serif;
font-style: italic ;
width: 200px;
margin: 20px; }

#insta {max-width: 200px;
margin-left: 45px;}

.button-insta {
  background-color: #205383;
  border: none;
  color: white;
  padding: 7px 16px;
  text-align: center;
  text-decoration: none;
  display: inline-block;
  font-size: 16px;
  margin-left:  25px;
  cursor: pointer;
  border-radius:  5px;
  font-weight: bold;
}

.button-insta a {color: white;}

.button-youtube {
  background-color:red;
  border: none;
  color: white;
  padding: 7px 16px;
  text-align: center;
  text-decoration: none;
  display: inline-block;
  font-size: 16px;
  margin-left:  50px;
  margin-top:  10px;
  cursor: pointer;
  border-radius:  5px;
  font-weight: bold;
}

.button-insta:hover {background-color: #DB8F00;}
.button-youtube:hover {background-color: #DB8F00;}

#copyright {text-align: right;
font-size: 12px;
margin-top:  50px;}

/*Button Upp^ */
#myBtn {
  display: none;
  position: fixed;
  bottom: 20px;
  right: 30px;
  z-index: 99;
  font-size: 16px;
  border: none;
  outline: none;
  background-color: #FFA700;
  color: black;
  cursor: pointer;
  padding: 10px;
  border-radius: 4px;
}

#myBtn:hover {
  background-color: #DB8F00;
}

/*menu that open down when clicked*/
#panel, #panel2, #panel3 {background-color: white;
border:  2px solid rgb(221, 222, 223);
margin-left: 50px;
margin-right: 50px;
margin-top: 20px;
min-height: 40px;
display: flex;
flex: 1 1 0%;
font-family: Open Sans, Verdana, Arial, sans-serif;
color: #333;
padding: 50px;
display: none;
}
