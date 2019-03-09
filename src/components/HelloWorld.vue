<template>
<div>
  <div class="header">
    <nav>
      <a href="">Home</a>
      <a href="">Products</a>
      <a href="">About Us</a>
      <a href="">Contact Us</a>
    </nav>
    <div class='headerText'>
      <img src="./../assets/textlogowhite.png" alt="Logo Text White">
    </div>

  </div>
  <div class='intro'>
    <div class='products'>
      <div>
        <div class="prodrow">
          <div class='prodcard1'>

          </div>
          <div class='prodcard2'>
            <h4>Family Owned and Operated</h4>
            <h5>We have proudly owned and operated The Antler Works since 1994</h5>
            <div class='prodline'></div>
          </div>
        </div>
        <div class="prodrow">
          <div class='prodcard3'>
            <h4>100% Handcrafted Products</h4>
            <h5>All of our products are completely handmade in our shop in beautiful Star Valley</h5>
            <div class='prodline'></div>
          </div>
          <div class='prodcard4'>

          </div>
        </div>
      </div>
    </div>
  </div>
  <div class='aboutUs'>
    <div class='bg-video'>
      <video class='bg-videoContent' autoplay muted loop>
        <source src="../assets/Forest-Lullaby.mp4">
        Your browser is not supported!
      </video>
    </div>
    <div class='aboutUsContent'>
      <div class='aboutUsCard'>
        <div>
          <img src="./../assets/whistles.jpg" alt="Logo Text White" class='productsImg'>
          <h3>Whistles</h3>
          <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.</p>
        </div>
      </div>
      <div class='aboutUsCard'>
        <div>
          <img src="./../assets/buckle.jpg" alt="Logo Text White" class='productsImg'>
          <h3>Buckles</h3>
          <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.</p>
        </div>
      </div>
      <div class='aboutUsCard'>
        <div>
          <img src="./../assets/carvings.jpg" alt="Logo Text White" class='productsImg'>
          <h3>Carvings</h3>
          <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.</p>
        </div>
      </div>

    </div>
  </div>
  <div class='about'>
  </div>
    <div class='clients'>
      <h4>Some of our clients include:</h4>
      <div>
        <img src="./../assets/logoalamo.png" alt="">
        <img src="./../assets/logocabelas.png" alt="">
        <img src="./../assets/logodisney.png" alt="">
        <img src="./../assets/logocowboys.png" alt="">
        <img src="./../assets/logosmithsonian.png" alt="">
        <img src="./../assets/logograndcanyon.png" alt="">
      </div>
    </div>
</div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

@font-face {
  font-family: "Western";
  src: url('./../assets/fonts/WEST____.TTF');
}

@font-face {
  font-family: "Cowboy";
  src: url('./../assets/fonts/Young Heart.ttf');
}


.header {
  height: 99vh;
  width: 100%;
  background: linear-gradient(to bottom, rgba(0, 0, 0, 0.8), rgba(0, 0, 0, 0.5) ), url('./../assets/treesbkgd.jpg');
  background-position: center;
  background-size: cover;
  background-repeat: none;
  background-repeat: no-repeat;
  background-attachment: fixed;
  display: flex;
	flex-direction: column;
	flex-wrap: nowrap;
	justify-content: flex-start;
	align-items: stretch;
	align-content: stretch;
  margin: 0;
  position: initial;
  text-align: center;
}

nav {
  width: 100%;
  display: flex;
  flex-direction: row;
  justify-content: center;
  margin: 4vh 0;
}

nav a {
  width: 15%;
  text-decoration: none;
    color: white;
    font-size: 30px;
    margin: 0 4vw;
    font-family: 'Poppins', sans-serif;
    text-transform: uppercase;
}

.headerText {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
}

.headerText>img {
  max-width: 60%;
}

.intro {
  background: linear-gradient(to bottom, rgba(214, 212, 212, 0.6), rgba(236, 230, 230, 0.3) );
  height: 100%;
  width: 100%;
  padding: 5vw;
}

.intro h2 {
  font-size: 50px;
  color: #3f5125;
  font-family: "Cowboy", sans-serif;
  text-align: left;
  letter-spacing: 5px;
}

.products {
  width: 100%;
  display: flex;
  flex-direction: column;
  margin-bottom: 10vh;
  align-items: center;
}

.productsImg {
  width: 280px;
  height: 280px;
  border-radius: 100%;
  margin-top: 0;
  border: 6px solid #3f5125;
  box-shadow: 0 0 0 5pt #fff;
  opacity: .85;
}

.products h4 {
  color: white;
  font-size: 40px;
}

.products h5 {
  color: #a0a1a0;
  font-size: 25px;
  text-align: left;
  width: 75%;
}

.prodline {
  height: 5px;
  width: 30%;
  margin-top: 25px;
  background: #3f5125;
  border-radius: 1px;
}

.products p {
  font-size: 23px;
  width: 70%;
  color: #151516;
  font-family: 'Roboto', sans-serif;
}

.products>div {
  width: 75vw;
  min-height: 90vh;
  margin-top: 10vh;
  display: flex;
  flex-direction: column;
}

.prodrow {
  display: flex;
  flex-direction: row;
  height: 45vh;
  width: 100%;
}

.prodcard1 {
  width: 50%;
  height: 100%;
  background: linear-gradient(to bottom, rgba(0, 0, 0, 0.2), rgba(0, 0, 0, 0.3) ), url('./../assets/fieldbkgd.jpg');
  background-position: center;
  background-size: cover;
  background-repeat: none;
  background-repeat: no-repeat;
}

.prodcard2 {
  width: 50%;
  height: 100%;
  background: black;
  display: flex;
  flex-direction: column;
  align-items: flex-start;
  justify-content: center;
  padding: 60px;
}

.prodcard3 {
  width: 50%;
  height: 100%;
  background: black;
  display: flex;
  flex-direction: column;
  align-items: flex-start;
  justify-content: center;
  padding: 60px;
}

.prodcard4 {
  width: 50%;
  height: 100%;
  background: linear-gradient(to bottom, rgba(0, 0, 0, 0.2), rgba(0, 0, 0, 0.4) ), url('./../assets/mtnbkgd.jpg');
  background-position: center;
  background-size: cover;
  background-repeat: none;
  background-repeat: no-repeat;
}

.aboutUs {
  min-height: 90vh;
  position: relative;
  padding: 20rem 0; 
}

.bg-video {
  position: absolute;
  top: 0;
  left: 0;
  height: 100%;
  width: 100%;
  z-index: -999;
  opacity: .25;
  overflow: hidden;
}

.bg-videoContent {
  height: 100%;
  width: 100%;
  object-fit: cover;
}

.aboutUsContent {
  color: black;
  background: #0a3125;
  background-color: rgba(4, 59, 16, 0.5);
  /* opacity: .4; */
  height: 100%;
  width: 100%;
  position: absolute;
  top:0;right:0;bottom:0;left:0;
  z-index: 3;
  display: flex;
  flex-direction: row;
  align-items: center;
  justify-content: space-around;
}

.aboutUsCard {
  background: white;
  height: 750px;
  width: 25vw;
  display: flex;
  align-items: flex-start;
  justify-content: center;
  padding: 2vw;
  box-shadow: 0 10px 20px rgba(0,0,0,0.19), 0 6px 6px rgba(0,0,0,0.23);
}

.aboutUsCard h3 {
  font-size: 50px;
  margin: 3vh 0;
  color: #34421E;
  font-family: 'Roboto', sans-serif;
  letter-spacing: 3px;
}

.aboutUsCard p {
  font-size: 22px;
  width: 100%;
  color: #151516;
  font-family: 'Roboto', sans-serif;
}

.about {
  min-height: 80vh;
}

.clients {
  background: linear-gradient(to bottom, rgba(0, 0, 0, 0.2), rgba(0, 0, 0, 0.4) ), url('./../assets/clientsbkgd.jpg');
  background-position: center;
  background-size: cover;
  background-repeat: none;
  background-repeat: no-repeat;
  min-height: 50vh;
  padding: 8vh 0;
}

.clients h4 {
  color: white;
  font-size: 30px;
}

.clients div {
  display: flex;
  flex-direction: row;
  width: 100%;
  justify-content: center;
  margin: 7vh 0;

}

.clients img {
  max-height: 12vh;
  margin: 0 18px;
}

</style>
