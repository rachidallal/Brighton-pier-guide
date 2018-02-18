
body{
font-size: 100%;
background-color:#D5EEFF;
font-family: 'Lato', sans-serif;

}


.heroHead{

font-size: 400%; 
color: white;
background-color: #50595C;

}

.heroSub{
color:white;
font-size: 200%;
background-color:#50595C;

}


header {
  height: 100vh;
  background-image: url(https://images.unsplash.com/photo-1475328592440-9b941a6fb7aa?auto=format&fit=crop&w=1267&q=80);
  background-size: cover;
  background-position: center;
  margin-bottom: 50px;
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-orient: vertical;
  -webkit-box-direction: normal;
      -ms-flex-direction: column;
          flex-direction: column;
  -webkit-box-pack: center;
      -ms-flex-pack: center;
          justify-content: center;
  -webkit-box-align: center;
      -ms-flex-align: center;
          align-items: center;
  text-align: center;
  /* open source @devtips on codepen */ 
}

p {
  
  margin: 0 auto 20px;

}

.icon {

  color: #FF6C00;
}

/* navigaton */ 
/* Add a black background color to the top navigation */
.topnav {
    background-color: #50595C;
    overflow: hidden;
}

/* Style the links inside the navigation bar */
.topnav a {
    float: left;
    color: #f2f2f2;
    text-align: center;
    padding: 14px 16px;
    text-decoration: none;
    font-size: 17px;
}

/* Change the color of links on hover */
.topnav a:hover {
    background-color: #ddd;
    color: black;
}

/* Add a color to the active/current link */
.topnav a.active {
    background-color: #4CAF50;
    color: white;
}



.firstHead {

  font-size: 200%;
  margin-top: 5%;
}

.secondHead {

   width: 31.250em;
   margin-top:10%
 /* margin: 0 auto 20px; */ 
  font-size: 400%;

}

 /*.pic1 img {
  display: inline block;
  width: 29.500em;
  height: 19.625em;
  margin-left: 20%;
}
*/ 

.centered {

  text-align: center;
}




.first {

  font-size: 150%;
  width: 90%;
  text-decoration: underline;

}

.second {

  font-size: 110%;
  width: 90%;
  padding-top:1.8em;

}

.third{

   font-size: 110%;
  max-width: 90%;
  padding-top:1.6em;
 margin-left: 2em;
}

.fourth {
font-size: 110%;
  width: 90%;
  padding-top:2em;
 margin-left: 2em;

}

.last {
font-size: 110%;
  width: 90%;
  padding-top:4em;
 margin-left: 2em;

}

iframe {

  max-width: 100%;
  max-height: 200px; 
}

.video-container {
   position: relative;
   padding-bottom: 44%; /*16:9 */
   margin-top: 4%; 
  height: 0; 
}


.video-container iframe {
   position: absolute;
   top: 0; left: 0; right: 0; bottom: 0;
 
}


.float-left {

float:left;
margin-right: 10px; 

}

.float-right {

  float:right;
  margin-left: 10px;
  margin-top: 10px;
}


.banner img {

max-width: 100%;
padding-left: 2em;


}

.clear {

  clear:both;
}
table {  
    color: #333; /* Lighten up font color */
    font-family: Helvetica, Arial, sans-serif; /* Nicer font */
    width: 640px; 
    border-collapse: collapse; 
    border-spacing: 0; 

}

td, th { border: 1px solid #CCC; height: 30px; } /* Make cells a bit taller */

th {  
    background: #F3F3F3; /* Light grey background */
    font-weight: bold; /* Make sure they're bold */
}

td {  
    background: #FAFAFA; /* Lighter grey background */
    text-align: center; /* Center our text */
}
/* http://cssmenumaker.com/blog/stylish-css-tables-tutorial/ */


.thirdHeader {


  font-size: 150%;
  width: 90%;
  text-decoration: underline;
}


.fourthHeader {

  font-size: 150%;
  width: 90%;
  text-decoration: underline;
}

.fifthHeader {

   font-size: 150%;
  width: 90%;
  text-decoration: underline;
}


.block{
  display: inline; 
}


.container {
  display: flex;
  flex-wrap: wrap;
  align-items: flex-start;
}

.item {
  background: #ddd;
  height: 190px;
  width: 190px;
  margin: 5px;
}

/*.container {

  background-color: red;
} */ 


/* collumns( @https://www.w3schools.com/howto/howto_css_four_columns.asp )*/

* {

  box-sizing: border-box;
}



/* each collumn */
.column1 {
    float: left;
    width: 25%;
    padding: 10px;
    background-color: white;
    height: 300px;
 
}

.fa-sun { /* icon */ 

  color:yellow;
}

.column2 {
    float: left;
    width: 25%;
    padding: 10px;
    height: 300px;
    background-color: white;
    }

.column3 {
    float: left;
    width: 25%;
    padding: 10px;
    height: 300px; 
    background-color: white;
}

.column4 {
    float: left;
    width: 25%;
    padding: 10px;
    height: 300px;
    background-color: white;
}

.column5 {
    float: left;
    width: 50%;
    padding: 10px;
    background-color: #D5EEFF;
    height: 300px;

  }
  .column6 {
    float: left;
    width: 50%;
    padding: 10px;
    background-color: #D5EEFF;;
    height: 300px;
}


/* Clear floats after the columns */
.row:after {
    content: "";
    display: table;
    clear: both;
}

.row {

  padding-left: 
}


footer {

  background-color: gray; 
 
}



.bigText {

  font-size: 150%;
}


footer {
color: #fff;
  background: #555;
  padding: 1em 1.25em 1em 1.25em;

}


/* media queries */
@media (max-width:1025px)  { /* desktop */ 

body {
background-color: #D5EEFF;
color: black;
}

}

@media (max-width: 480px){ /* phones */ 


  body {

  background-color: #BDE4F4; 
  color: black;
  }

  
}


@media ( min-width: 481px) and (max-width: 700px){ /* evrything between phone and tablet */
  p {

  color: black;
  }

  body {

   background-color: seagreen;    
  }


}

@media screen and (max-width: 959px) { /* hero img */

#container {

  width: 100%;
}

img{

  width: 100%;
}


}


@media (max-width: 600px) { /* make the bottom collumns cover the viewport */
    .column1 {
        width: 100%;

        
    }
}
@media (max-width: 600px) { /* make the bottom collumns cover the viewport */
    .column2 {
        width: 100%;
    }
}
@media (max-width: 600px) { /* make the bottom collumns cover the viewport */
    .column3 {
        width: 100%;
    }
}
@media (max-width: 600px) {/* make the bottom collumns cover the viewport */
    .column4 {
        width: 100%;
    }

    @media (max-width: 600px) {/* make the bottom collumns cover the viewport */
    .column5 {
        width: 100%;
    }

    @media (max-width: 600px) {/* make the bottom collumns cover the viewport */
    .column6 {
        width: 100%;
    }



    @media (min-width:1281px) { /* hi-res laptops and desktops */ }
}

