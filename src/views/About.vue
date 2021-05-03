<template>
  
  <div class="about">
   
    <h4 class='fade-in'> {{welcome}}</h4> 
    <h1 class='fade-in'> {{name}} </h1>
    <h3 class='fade-in'> {{skills}} </h3>
  
  </div>

    
</template>


<script>
//import HelloWorld from './components/HelloWorld';

export default {
  data: () => ({
     name: 'EMA CATOVIC',
      skills: 'A Multimedia Designer',
      welcome: 'Welcome to my portfolio'
  }),

};

</script>

<style>
.about {
  background-color: #E8E2DB;
   padding: 0px;
    margin-top: 200px;
    margin-bottom: 90px;
    }  


h4 {
  font-size: 30px;
  display: flex;
    justify-content: center;
    margin-right: 550px; 
    margin-bottom: 35px;
    font-family: 'Nothing You Could Do', cursive;
    transition-property: width;
}

h3 {
    font-size: 50px;
    display: flex;
    justify-content: center;
    color: #983B5C;
    margin-left: 350px;
    margin-top: 30px;
    font-family: 'Nothing You Could Do', cursive;
}

h1 {
    font-size: 130px;
    display: flex;
    justify-content: center;
    font-family: 'Playfair Display', serif;
    margin-bottom: -30px;
    margin-top: -50px;
}


  
.fade-in {
    animation: fadeIn 6s;
}

@keyframes fadeIn {
    from {
        opacity: 0;
    }

    to {
        opacity: 1;
    }
}


</style>

