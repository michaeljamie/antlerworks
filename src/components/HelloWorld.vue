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
        <p>Our hand-carved whistles are the perfect gift for anyone.</p>
      </div>
      <div>
        <img src="./../assets/buckle.jpg" alt="Logo Text White">
        <h3>Buckles</h3>
        <p>Our big game buckles are meticulously carved and hand painted, and worthy of any collector's showcase, yet durable enough to be worn for generations.</p>
      </div>
      <div>
        <img src="./../assets/carvings.jpg" alt="Logo Text White">
        <h3>Carvings</h3>
        <p>Our unique collection of carvings is an ideal</p>
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
}

.intro h2 {
  margin: 8vh 6vw;
  font-size: 50px;
  color: #151b1f;
  font-family: "Cowboy", sans-serif;
  text-align: left;
  letter-spacing: 5px;
}

.products {
  width: 100%;
  display: flex;
  flex-direction: row;
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
}


.products h3 {
  font-size: 35px;
  margin: 5vh 0;
  color: #151b1f;
  font-family: 'Poppins', sans-serif;
  text-transform: uppercase;
  letter-spacing: 3px;
}

.products p {
  font-size: 18px;
  width: 70%;
}

</style>
