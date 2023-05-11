<template>
    <header class="header">
      <link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Codystar&family=Knewave&display=swap" rel="stylesheet">
        <h1 class="header__title ">PowerUp</h1>
        <h2 class="header__subTitle">Le fan site pas officiel du tout de Chainsaw man</h2>
    <nav class="header__container">
        <ul class="header__container__nav__list">
                <li class="header__container__nav__list list">
                    <a class="header__container__nav__list__item item" href="#">Acceuil</a>
                </li>
                <li class="header__container__nav__list list">
                    <a class="header__container__nav__list__item item" href="#">A-propos</a>
                </li>
                <li class="header__container__nav__list list">
                    <a class="header__container__nav__list__item item" href="#">Contact</a>
                </li>
                <li class="header__container__nav__list list">
                    <a class="header__container__nav__list__item item" href="#">Liste-des-épisodes-personnages</a>
                </li>
         </ul>

     
    </nav>
    
    </header>
    
</template>
<script setup>

</script>
<style>

.header{
    background-color:goldenrod;
    
  }
  .header__title{
    text-align: center;
    font-family: 'Knewave', cursive;
    color:darkred;
    text-shadow: 2px 4px 10px red;
  }
  .header__container__nav__list__item{
    color:darkred;
    vertical-align:text-top;
  }
  h1{
    margin: 0;
    color:darkred;
    text-shadow: 2px 4px 10px red;
    }

  .header__subTitle{
    text-align: center;
    font-family: 'Knewave', cursive;
    color:darkred;
    text-shadow: 2px 4px 10px red;
    position:relative;
    top: -10px;
  }

  .header__container__nav__list{
    display: flex;
    justify-content: space-around;
    font-family: 'Knewave', cursive;
    color:darkred;
    text-shadow: 2px 4px 10px red;
    position:relative;
    top: -10px;
  }
</style>
