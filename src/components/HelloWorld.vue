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
    <h2>Family Owned and Operated since 1992</h2>
    <div class='products'>
      <div>
        <img src="./../assets/whistles.jpg" alt="Logo Text White">
        <h3>Whistles</h3>
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.</p>
      </div>
      <div>
        <img src="./../assets/buckle.jpg" alt="Logo Text White">
        <h3>Buckles</h3>
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.</p>
      </div>
      <div>
        <img src="./../assets/carvings.jpg" alt="Logo Text White">
        <h3>Carvings</h3>
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.</p>
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
        Card 1
      </div>
      <div class='aboutUsCard'>
        Card 2
      </div>
      <div class='aboutUsCard'>
        Card 3
      </div>

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
  background-color: linear-gradient(rgba(255, 255, 255, 0.8));
  margin: 0 auto;
  height: auto;
}

.intro h2 {
  margin: 8vh 6vw;
  font-size: 50px;
  color: #34421E;
  font-family: "Cowboy", sans-serif;
  text-align: left;
  letter-spacing: 5px;
}

.products {
  width: 100%;
  display: flex;
  flex-direction: row;
  margin-bottom: 10vh;
}

.products>div {
  width: 33%;
  display: flex;
  flex-direction: column;
  align-items: center;
}

.products img {
  width: 400px;
  height: 400px;
  border-radius: 100%;
  margin-top: 5vh;
  border: 3px solid #34421E;
}


.products h3 {
  font-size: 50px;
  margin: 5vh 0;
  color: #34421E;
  font-family: "Cowboy", sans-serif;
  text-transform: uppercase;
  letter-spacing: 3px;
}

.products p {
  font-size: 23px;
  width: 70%;
  color: #151516;
  font-family: 'Roboto', sans-serif;
}

.aboutUs {
  min-height: 80vh;
  position: relative;
  padding: 15rem 0; 
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
  background-color: rgba(10, 49, 37, 0.4);
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
  height: 500px;
  min-width: 350px;
  border-radius: 3px;
  display: flex;
  align-items: flex-start;
  justify-content: center;
  padding: 5vw;
  box-shadow: 0 10px 20px rgba(0,0,0,0.19), 0 6px 6px rgba(0,0,0,0.23);
}

</style>
