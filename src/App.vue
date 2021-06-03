<template>
  <div id="app">
     <meta charset="UTF-8">
     <meta name="viewport" content="width=device-width, initial-scale=1.0">
   <link rel="preconnect" href="https://fonts.gstatic.com"> 
   <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300&display=swap" rel="stylesheet">

  
    <div class="title">
    <h1> The creative crew</h1>
    <h3>WHO WE ARE</h3>
    <h6>We are team of creatively diverse. <br> innovative individuals working in varius <br> locations from the world.</h6>
    </div>
    
     <section id="container">
       <div class="ph1">
      <article class="article">  <img   src="photo1.png" />   <h2 class="article__heading">PROJECT OWNER</h2>
      </article><p class="own">Bill Mahoney</p>
      </div>

      <div class="ph2">
      <article class="article">  <img  src="photo2.png" />   <p class="article__heading" >ART DIRECTOR</p>
      </article><p class="design">Saba Cabrera</p>
      </div>

    <div class="ph3">
      <article class="article">  <img  src="photo3.png" />   <h2 class="article__heading">TEACHLEAD</h2>
      </article><p class="design">Shae Le</p>
      </div>
<div class="ph4">
      <article class="article">  <img  src="photo4.png" />   <h2 class="article__heading">UX DESIGNER</h2>
      </article><p class="design">Skylah lu</p>
      </div>

     <div class="ph5">
      <article class="article">  <img  src="photo5.png" />   <h2 class="article__heading">DEVELOPER</h2>
      </article><p class="design">Griff Richards</p>
      </div>
       <div class="ph6">
      <article class="article">  <img  src="photo6.png" />   <h2 class="article__heading">DEVELOPER</h2>
      </article><p class="design">Stan John</p>
      </div>
 

      
 </section>
    
</div>
</template>

<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>
<script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/js/bootstrap.min.js"></script>
  
<script>
  export default {
    
  }
</script>

<style>
 
#app{
  position:relative;
 
 
}
 .title h1{
   padding-left: 20rem;
   font-family: 'PT Serif', serif;
   font-size:2.5rem;
   }
#container{
  margin:1rem;
}
.title h3{
  
  margin-top:2rem;
  font-size:14px;
  margin-left:10rem;
  font-weight:bold;
  font-family:'Poppins', sans-serif;
}
.title h6{
   margin-left:-5.5rem ;
   margin-top:4rem; 
   font-weight:400;
   font-size:14px;
   font-family:'Poppins', sans-serif;
}
  

img{
  width:150px;
  height:200px;
  box-shadow: 5px 10px #fffafa;
}

.title{
  display:flex;
  margin-top:-0.8rem;
  padding: 30px 20px 20px;
}
.article{
  display: flex;
 
}
.article__heading {
  font-family: var(--font-display);
  font-size:12px;
  white-space: nowrap;
  writing-mode: vertical-lr;
  line-height: 0ch;
 
 
}
h2{
  font-size:12px;
}

p{
  margin-top:-.5px;
  font-family:'Poppins', sans-serif;
  font-weight:bold;
  font-size:10px;
}
.ph1{ 
 
  margin-top:-1.5rem;
  margin-left:20rem;
}
.ph2{
   
    margin-left:39rem;
    margin-top:-11rem;
}
.ph3{
    
    margin-left:58rem;
    margin-top:-19rem;
}
.ph4{
  
  margin-top:6rem;
  margin-left:20rem;
}
.ph5{
  
  margin-left:39rem;
  margin-top:-11.5rem;

}
.ph6{
 
  margin-left:58rem;
  margin-top:-18.2rem;
}
    
@media only screen and (max-width:600px) {
  .title h1{
   padding-left: 0rem;
   font-family: 'PT Serif', serif;
   font-size:1rem;
   
   }
   #app{
     width:100%;
     height:100vh;

   }

.title h3{
  margin-top:2.5rem;
  margin-left:-120px;
  font-size:10px;
  font-weight:bold;
  font-family:'Poppins', sans-serif;
}
.title h6{
   
   margin-top:3.5rem; 
   margin-left:-4rem;
   font-weight:400;
   font-size:10px;
   font-family:'Poppins', sans-serif;
}
 h2{
  font-size:5px;
} 

img{
  width:80px;
  height:120px;
  box-shadow: 5px 10px #fffafa;
}

.title{
  display:flex;
  margin-top:-0.8rem;
  padding: 10px 10px 10px;
}
.article{
  display: flex;
 
}
.article__heading {
  font-family: var(--font-display);
  font-size:9px;
  white-space: nowrap;
  writing-mode: vertical-lr;
  line-height: 0ch;
 
 
}
p{
  margin-top:-.3px;
  font-family:'Poppins', sans-serif;
  font-weight:bold;
  font-size:9px;
}
.ph1{ 
 
  margin-top:-1.5rem;
  margin-left:0rem;
}
.ph2{
   
    margin-left:8rem;
    margin-top:-7rem;
}
.ph3{
    
    margin-left:0rem;
    margin-top:-1rem;
}
.ph4{
  
  margin-top:-6rem;
  margin-left:8rem;
}
.ph5{
  
  margin-left:0rem;
  margin-top:-1rem;

}
.ph6{
 
  margin-left:8rem;
  margin-top:-6rem;
}

}

</style>