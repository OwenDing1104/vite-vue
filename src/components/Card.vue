<script setup>
import { ref } from 'vue'

</script>

<template>
  <div class="card">
    <h1>NBA Superstar</h1>
    <img src="https://thumbs.dreamstime.com/b/michael-jordan-chicago-bulls-superstar-image-taken-color-slide-73861883.jpg" alt="Jordan">
    <div class="content">
      <h2><b>Michael Jordan</b></h2>
      <p>Michael Jeffrey Jordan (born February 17, 1963), also known by his initials MJ, is an American former professional basketball player and businessman. Widely considered the greatest basketball player of all time, the official National Basketball Association (NBA) website states that "by acclamation, Michael Jordan is the greatest basketball player of all time." He played fifteen seasons in the NBA, winning six NBA championships with the Chicago Bulls. He was integral in popularizing the sport of basketball and the NBA around the world in the 1980s and 1990s, becoming a global cultural icon.</p>
      <div class="button1">
        <button id="detail1">Details</button>
        <button id="cloneButton1">CloneCard</button>
        <button id="color1">ColorCard</button>
        <button id="heading1">ChangeHeading</button>
        <button id="delete1">Delete</button>  
      </div> 
    </div>
  </div>
</template>

<style scoped>
  .card {
    max-width: 400px;
    margin: 12px;
    background-color: pink;
    text-align: center;
    padding:6px ;
    border-radius: 6px;
  }
  /*The heading setting in the card*/
  .card h1{
    font-size: 36px ;
    color: #CE1141;
  }
  /*The second heading setting in the card*/
  .card h2{
    font-size: 30px ;
    color: #CE1141;
  }
  /*The content setting in the card*/
  .card p{
    font-size: 16px ;
    color: black;
    margin-left: 8px ;
    margin-right: 8px ;
  }
  /*The image setting in the card*/
  .card img {
    width: 85%;
    height:auto;
  }
  /*The button setting in the card*/
  .button1 {
    margin: 24px auto;
  }
  .button1 button {
    font-size: 24px;
    color: #CE1141;
    background-color: white;
    padding: 6px;
  }
  .button1 button:hover, .button1 button:focus {
    color: white;
    background-color: #CE1141;
  }

  @media screen and (max-width: 800px){
    .detailsButton{
      display: none;
    }
  }

</style>

