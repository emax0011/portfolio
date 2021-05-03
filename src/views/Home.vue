<template>
  <!--<Front page page/>-->
  <div class="home">
    
   <div class="about">
   
    <h4 class='fade-in'> {{welcome}}</h4> 
    <h1 class='fade-in'> {{name}} </h1>
    <h3 class='fade-in'> {{skills}} </h3>

    <div class="linething">
       <img class ='fade-in' src="../assets/img/linething1.png" alt="arrow">
    </div>
   
  </div>

<!--<Round corner box 1/>-->
   <div class="roundcorner1">
        <p id="rcorners1"> More about me </p>
        </div>


<!--<About me Page/>-->
  <div class="page">
    <div class="page-container">
    <div class="page-left">
       
        <img class ="selfie1" src="../assets/img/emsiself.jpeg" alt="my selfie">
    </div>    
    <div class="page-right">
        <div class="infosection">
        <h5> ABOUT ME</h5>
        <p> Hi i’m Ema Catovic.
            I’m a danish based 
            Multimedia Designer
            <br> 
            I’m in love with designing,
            and would describe myself
            very detail oriented and hard 
            working. I love challenges and 
            want to achieve a high quality 
            with a holistic and creative 
            approach for my projects.
             </p>
             </div>
         
      </div>
    </div>

<!--<Video page/>-->
    <div class="video-page">
    <h6> Cv Video</h6>

<div class="videoshare1"> 
    <iframe width="560" height="315" src="https://www.youtube.com/embed/rCmK5Po2j7M" 
    title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; 
    clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>
    </div>

    <br> <br>
     <br> <br>

<!--<Round corner box 2/>-->
<div class="round-corner">
<p id="rcorners2"> Some of my selcted work </p>
</div>

<!--<Photography Page/>-->
     <div class="page2">

     <br><br><br>
     <h2> Photography </h2>
     <br> <br>
     <h6> Aesthetically pleasing </h6>
      <div class="photo-container">
        <img class ="photography1" src="../assets/img/angelsky.jpeg" alt="beach and sky">
        <img class ="photography1" src="../assets/img/picnicbillede.jpeg" alt="picnic sunset">
        <img class ="photography1" src="../assets/img/sloveniapic.jpeg" alt="slovenia">
      </div>
     </div> 

      <br> <br>

<!--<Illustration Page/>-->
  <div class="page3">
    <h2> Illustrations </h2>
     <br> <br>
     <h6> Commercial and Personal </h6>
     <div class="photo-container">
        <img class ="photography1" src="../assets/img/plakatcovid.jpg" alt="plakat 1">
        <img class ="photography1" src="../assets/img/coralreliefposter.jpg" alt="coral poster">
      </div>
     
    </div>

    <br> <br>

<!--<Coral Relief page/>-->
     <div class="page4">
    <h2> Coral Relief Project </h2>
     <br> <br>
     <h6> Adopt a coral project </h6>
      <div class="photo-container">
        <img class ="photography2" src="../assets/img/corally1.png" alt="coral first">
        </div>
         <div class="photo-container">
        <img class ="photography3" src="../assets/img/secondcoral1.png" alt="coral second">
      </div>
    </div>

    <br> <br>

<!--<Design Layout Page/>-->
     <div class="page5">
    <h2> Design Layouts </h2>
     <br> <br>
     <h6> School assignment </h6>
     <div class="photo-container">
        <img class ="photography4" src="../assets/img/coralrapport.png" alt="coral rapport">
      </div>
      <br> <br>
     <h6> Guide to Strandvejen </h6>
     <div class="photo-container">
        <img class ="photography4" src="../assets/img/strandvejenting.png" alt="strandvejen">
      </div>
     <br> <br><br> <br><br> <br>
    </div>
    <div class="round-corner3">
<p id="rcorners3"> Contact me </p>
</div>


<!--<Contact information page/>-->
<div class="page6">
<h6> Contact information </h6>
<br><br

<div class="infotext1">
<p id="info1">Ema Catovic</p>
<p id="info1-num">Number: +45 22 43 44 56</p>
<p id="info1-mai">Mail: emax0011@easv365.dk </p>
</div>

<!--<Download my cv button/>-->
<v-btn
  id="button"
  elevation="2"
  color="#DDD5CA">
  <a href="https://www.dropbox.com/s/fp8y424i9wzfv5l/CVDESIGNpdff.pdf?dl=0" target="_blank">
    Download my CV
  </a>
</v-btn>
</div>

<!--<Socials/>-->
<div class="socials">
  <li><a href="https://www.linkedin.com/in/ema-catovic-033aa9205/"><i class="fa fa-linkedin"></i></a></li>
  <li><a href="https://www.linkedin.com/in/ema-catovic-033aa9205/"><i class="fa fa-youtube"></i></a></li>
  <li><a href="https://www.instagram.com/90scelebvibes/"><i class="fa fa-instagram"></i></a></li>
  </div>
</div>

</div>

</template>

<script>
export default {
  data: () => ({
     name: 'EMA CATOVIC',
      skills: 'A Multimedia Designer',
      welcome: 'Welcome to my portfolio'
  }),
};
</script>


<style>
/* Download CV button*/
#button {
  display: block;
  margin-left: 52%;
  margin-right: 20%;
  margin-bottom: 40px;
  margin-top: -65px;
}

#button a {
  text-decoration: none;
  color: black;

}

/* first page */
.about {
  background-color: #E8E2DB;
   padding: 11%;
   height:100vh;
    }  

.linething {
  display: flex;
  justify-content:flex-end;
  height: 120px;

}

/* video cv */
.videoshare1{
  display: flex;
  justify-content: center;
  padding: 18px;
}


/* page backgrounds*/
.page2 {
  background-color: #DDD5CA;
}

.page3 {
  background-color: #DDD5CA;
}

.page4 {
  background-color: #DDD5CA;
}

.page5 {
  background-color: #DDD5CA;
}

.page6 {
  background-color: white;
}


/* socials*/
.socials {
  list-style-type: none;
  display: flex;
  justify-content: center; 
}
.socials a i {
  color:#983B5C;
  font-size: 30px;
  display: inline-block;
  padding: 8px;
}

/* First page 'welcome' */
h4 {
  font-size: 30px;
  display: flex;
    justify-content: center;
    margin-right: 550px; 
    margin-bottom: 35px;
    font-family: 'Nothing You Could Do', cursive;
    transition-property: width;
}

/* First page 'multimedia designer'*/
h3 {
    font-size: 50px;
    display: flex;
    justify-content: center;
    color: #983B5C;
    margin-left: 350px;
    margin-top: 30px;
    font-family: 'Nothing You Could Do', cursive;
}

/* First page 'my name'*/
h1 {
    font-size: 130px;
    display: flex;
    justify-content: center;
    font-family: 'Playfair Display', serif;
    margin-bottom: -30px;
    margin-top: -50px;
}

/* photography, coral relief project, design layout text*/
h2 {
   font-size: 50px;
   display: flex;
    justify-content: center;
    font-family: 'Playfair Display', serif;
    margin-bottom: -30px;
    margin-top: -50px;
    margin-left: 30px;
}

/* page background and containers */
.page {
  background-color:white;
}

.page-container {
  display:flex;
  width:70%;
  margin:0 auto 30px auto;
}

.page-left {
  display: flex;
  width:40%;
  justify-content: flex-end;
  margin-right:13px;
}

.page-right {
 width:45%;
 padding: 5px;
 margin-left: 15px;
}

/* round corner*/
#rcorners1 {
  border-radius: 25px;
  background: white;
  padding: 10px;
  width: 330px;
  height: 50px;
  font-size: 18px;
  font-family: 'raleway', serif;
  font-weight:bold;
  margin-left: 37%;
}

/* second page 'about me' title*/
  h5 {
  font-size: 30px;
  display: flex;
  justify-content: flex-start;
  font-family: 'Playfair Display', serif;
  color:#983B5C;
}

/* second titles under photography, design layout etc*/
h6 {
  font-size: 20px;
  display: flex;
  justify-content: center;
  font-family: 'Nothing You Could Do', cursive;
  color:#983B5C;
  margin-right: -20px;

}

/* text on page 2*/
 p {
    font-size: 16px;
    font-family: 'Raleway', serif;
    display: flex;
  justify-content: space-around;
  }


/* contact me text*/
.infotext1 {
  margin-right: 25%;
}

#info1 {
  font-size: 15px;
  font-family: 'Raleway', serif;
  justify-content: center;
  align-items: left;
  padding-right: 8.5%;

}

#info1-num {
  font-size: 15px;
  font-family: 'Raleway', serif;
  justify-content: center;
  align-items: left;
  padding: -8px;
  margin-top: -18px;
  

}

#info1-mai {
  font-size: 15px;
  font-family: 'Raleway', serif;
  justify-content: center;
  align-items: left;
  padding-left: 3%;
  margin-top: -17.5px;
  
}

/* Individual photos*/
.selfie1 {
    padding: 10px;
    height: 200px;
    width: 200px;
  }

.photography1 {
  height: 400px;
  width: 280px;
  display: flex;
  justify-content: center;
  padding: 20px;

}

.photography2 {
  height: 300px;
  width: 590px;
  display: flex;
  justify-content: center;
  padding: 15px;
  
}
.photography3 {
  height: 350px;
  width: 420px;
  display: flex;
  justify-content: center;
  padding: 15px;
}

.photography4 {
  display: flex;
  justify-content: center;
  height: 410px;
  width: 530px;
  padding: 10px;
}

/* photo container for the photos*/
.photo-container {
  display: flex;
  justify-content: center;
  width:90%;
  margin:0 auto
}


/* Fade in on front page*/  
.fade-in {
    animation: fadeIn 6s;
}

/* round corners*/
#rcorners2 {
  border-radius: 25px;
  background: #DDD5CA;
  padding: 10px;
  width: 330px;
  height: 50px;
  font-size: 18px;
  font-family: 'raleway', serif;
  font-weight:bold;
  margin-left: 37%;
}

#rcorners3 {
  border-radius: 25px;
  background: white;
  padding: 10px;
  width: 330px;
  height: 50px;
  font-size: 18px;
  font-family: 'raleway', serif;
  font-weight:bold;
  margin-left: 37%;
}

.roundcorner1 {
  margin-top: -2%;
}
.round-corner {
  margin-bottom: -3%;
}

.round-corner3 {
   margin-top: -2%;
}

/* Fade in*/
@keyframes fadeIn {
    from {
        opacity: 0;
    }

    to {
        opacity: 1;
    }
}

/* extra responsive 1 */
@media screen and (max-width: 1160px) {
  h1 {
    font-size: 100px
  }
  
  h4 {
    font-size: 24px;
    width: 50%;
  }
  h3 {
    font-size: 24px;
  }

  .round-corner {
  margin-bottom: -4%;
}
}

/* extra responsive 2 */
@media screen and (max-width: 890px) {
  h1 {
    font-size: 86px;
  }

  .round-corner {
  margin-bottom: -4%;
}
}

/* Tablet */
@media screen and (max-width: 768px) {
  
  /* front page */
  .about {
    padding: 10%;
   height:50vh;
  }
  .linething {
    height: 80px;
    padding: 10px;
    margin-right: 120px;
    margin-top: 10px;
    }
  h4 {
    font-size: 20px;
    width: 50%;
    margin-left: 84px;
  }
  h1 {
    font-size: 50px;
  }
  h3 {
    font-size: 20px;
    margin-right:100px;
    margin-left: 40%;
  }

/* About me page */

p {
  font-size: 13px;
}

#rcorners1 {
  margin-left: 30%;
}

/* Photo page */
#rcorners2 {
  margin-left: 30%;
}

.round-corner {
  margin-bottom: -5%;
}

.photography1 {
  height: 300px;
  width: 210px;
  padding: 20px;

}

h2 {
  font-size: 30px;
}

h6 {
  font-size: 18px;
}

.photography2 {
  height: 230px;
  width: 450px;
  padding: 20px;
}

.photography3 {
  height: 260px;
  width: 300px;
  padding: 20px;
}

.photography4 {
  height: 330px;
  width: 430px;
  padding: 15px;
}


/* contact me section*/
#rcorners3 {
  margin-left: 30%;
}

#button {
  margin-left: 56%;
}

#button a {
  font-size:10px;

}

#info1 {
  font-size: 12px;
  padding-right: 11.5%;

}

#info1-num {
  font-size: 12px;
}

#info1-mai {
  font-size: 12px;
  padding-left: 4%;
  
}

}

/* Mobile */
@media screen and (max-width: 500px) {

/* front page */
  .about {
    padding: 25%;
   height:95vh;
   padding-top: 45%;
  }
  .linething {
    height: 50px;
    padding: 8px;
    margin-right: 98px;
    margin-top: 8px;
    }
  h4 {
    font-size: 15px;
    width: 80%;
    margin-left: 10px;
    padding:5px;
  }
  h1 {
    font-size: 30px;
  }
  h3 {
    font-size: 15px;
    margin-right:5px;
    margin-left: 5%;
  }

/* About me page */
p {
  font-size: 10px;
}
h5 {
  font-size: 20px;
}

.selfie1 {
  height: 180px;
  width: 180px;
}
#rcorners1 {
  margin-left: 18%;
}

/* Photo page */
#rcorners2 {
  margin-left: 20%;
}

.round-corner {
  margin-bottom: -8%;
}

.photography1 {
  height: 220px;
  width: 150px;
  padding: 15px;
}

h2 {
  font-size: 30px;
}

h6 {
  font-size: 15px;
}

.photography2 {
  height: 200px;
  width: 400px;
  padding: 20px;
}

.photography4 {
  height: 260px;
  width: 350px;
  padding: 15px;
}

/* contact me section*/
#rcorners3 {
  margin-left: 20%;
}

#button {
  margin-left: 58%;
}
#info1 {
  padding-right: 17%;
}

#info1-mai {
  padding-left: 6.4%;
  
}


}
</style>
