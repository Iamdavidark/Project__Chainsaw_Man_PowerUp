<template>
    
    <main class="main">
        <div class="parallax-effect"></div>

        <div class="main__container__image-section image-section">
            <img class="img__band" src="../images/Power bandw.jpg">
        </div>
        <div class="main__wrapper wrapper">
            <div class="main__container">
                <h3 class="main__container__text-section__title title">Dernier épisode :</h3> 
                <h4 class="main__container__text-section__title__subTitle">KATANA VS TRONÇONEUSE</h4>
                <h5 class="main__container__text-section__title__subSubTitle">Chapitres 35-36-37-38-40</h5>
            
            </div>
        </div> 
        <div class="main__container__image-section__subImage-section">
            <img class="img__ep12" src="../images/Chainsaw-Man-episode-12-1600x900.jpg">
        </div>
        
    </main>
  </template>
  
  <script setup>
  const { data } = await useFetch('/api/confidential', {
    headers: useRequestHeaders(['authorization'])
  })
  </script>
  <style>
  
  .img__band{
    width : 100%;
    height:auto;
    position:relative;
    top:-17px;
      }
  .img__ep12{
    width : 100%;
    height:auto;
    position:relative;
    left:-200px;
    top:-40px;
    
      }

      .main__wrapper{
        background-color:goldenrod;
        /* background-size: contain; */
      }
      /* .main__container__subContainer{
        
      } */
      .main__container__text-section__title{
        font-family: 'Knewave', cursive;
        color: azure;

      }
      .main__container__text-section__title__subTitle{
        font-family: 'Knewave', cursive;
        
      }
      .main__container__text-section__title__subSubTitle{
        font-family: 'Knewave', cursive;
        text-align: right;
      }
      /* ..main__container__image-section__subImage-section{
          
      } */
    
</style>
        