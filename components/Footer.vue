<template>
    <footer class="Footer">
        <h1 class="Footer__title ">PowerUp</h1>
        <nav class="Footer__container">
            <ul class="Footer__container__nav__list">
                    <li class="Footer__container__nav__list list">
                        <a class="Footer__container__nav__list__item item" href="#">Acceuil</a>
                    </li>
                    <li class="Footer__container__nav__list list">
                        <a class="Footer__container__nav__list__item item" href="#">A-propos</a>
                    </li>
                    <li class="Footer__container__nav__list list">
                        <a class="Footer__container__nav__list__item item" href="#">Contact</a>
                    </li>
                    <li class="Footer__container__nav__list list">
                        <a class="Footer__container__nav__list__item item" href="#">Liste-des-épisodes-personnages</a>
                    </li>
                    <div class="Footer__container__image-section__subImage-section">
            <img class="img__wp" src="../images/wp9532701.jpeg">
        </div>
            </ul>
        </nav>
    </footer>
</template>
<style>
 .Footer{
    background-color:goldenrod;
    bottom: 0;
    width : 100%;
    height:200px;
     position:relative;
     top:auto;

  }
.Footer__title{
    font-family: fantasy;
    font-family: 'Knewave', cursive;
    color:darkred;
    text-shadow: 2px 4px 10px red;
    position:relative;
    right: -2%;
    top: -10px;
  }
  .Footer__container__nav__list{ 
    display:grid;
    font-family: 'Knewave', cursive;
    color:darkred;
    text-shadow: 2px 4px 10px red;
    
   }
   .Footer__container__nav__list__item{
    color:darkred;

   }
   .img__wp{
    width :15%;
    height:auto;
    position:relative;
    right:-1100px;
    top:-150px;
   }
</style>