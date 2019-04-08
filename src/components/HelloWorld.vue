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
      <img src="assets/textlogowhite.png" alt="Logo Text White">
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
            <h5>We have proudly owned and operated The Antler Works since 1992</h5>
            <div class='prodline'></div>
          </div>
        </div>
        <div class="prodrow">
          <div class='prodcard3'>
            <h4>100% Handcrafted Products</h4>
            <h5>All of our products are completely handmade in beautiful Star Valley, Wyoming</h5>
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
        <source src="assets/Forest_15_3b_Videvo.mp4">
        Your browser is not supported!
      </video>
    </div>
    <div class='aboutUsContent'>
      <div>
        <div class='aboutUsCard aboutUsCardWhistles'>
          <div>
            <div class='cardTop'>
              <img src="assets/whistles.jpg" alt="Logo Text White" class='productsImg'>
            </div>
            <div class='cardBottom'>
              <h3>Whistles</h3>
              <div class='prodCardLine'></div>
              <p>ed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.</p>
            </div>
          </div>
        </div>
      </div>
      <div>
        <div class='aboutUsCard'>
          <div>
            <div class='cardTop'>
              <img src="assets/buckle.jpg" alt="Logo Text White" class='productsImg'>
            </div>
            <div class='cardBottom'>
              <h3>Buckles</h3>
              <div class='prodCardLine'></div>
              <p>ed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.</p>
            </div>
          </div>
        </div>
        <div class='aboutUsCard'>
          <div>
            <div class='cardTop'>
              <img src="assets/carvings.jpg" alt="Logo Text White" class='productsImg'>
            </div>
            <div class='cardBottom'>
              <h3>Carvings</h3>
              <div class='prodCardLine'></div>
              <p>ed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.</p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
  <div class='about'>
    <div>
      <h2>About Us</h2>
      <div class='aboutLine'></div>
      <h5>The Hyde Family began The Antler Works in 1992 and three generations now proudly continue to carry it on.  We stand by the quality of our products and guarantee your complete satisfaction.</h5>
      <button>Contact Us</button>
    </div>
    <img src="assets/family.png.jpeg" alt="" class='familypic'>
  </div>
    <div class='clients'>
      <h4>Some of our clients include:</h4>
      <div>
        <img src="assets/logoalamo.png" alt="">
        <img src="assets/logocabelas.png" alt="">
        <img src="assets/logodisney.png" alt="">
        <img src="assets/logocowboys.png" alt="">
        <img src="assets/logosmithsonian.png" alt="">
        <img src="assets/logograndcanyon.png" alt="">
      </div>
    </div>
    <div class='contact'>
      <div class='contact-tabs'>
        <a>
          <img src="assets/phone.png" alt="">
          <h3>Phone</h3>
          <p>(307) 886-3236</p>
        </a>
        <div class='contact-divider'></div>
        <a>
          <img src="assets/address.png" alt="">
          <h3>Address</h3>
          <p>4645 Bittercreek Rd</p>
          <p>Afton, WY 83110</p>
        </a>
        <div class='contact-divider'></div>
        <a>
          <img src="assets/email.png" alt="">
          <h3>Email</h3>
          <p>antlerworks@silverstar.com</p>
        </a>
      </div>
      <!-- <div class='contact-bottom'>
        <a href=""><img src="assets/social-fb.png" alt=""></a>
        <a href=""><img src="assets/social-li.png" alt=""></a>
        <a href=""><img src="assets/social-tw.png" alt=""></a>
      </div> -->
      <p>Copyright © 2019</p>
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
  width: 240px;
  height: 240px;
  border-radius: 100%;
  border: 6px solid #191919;
  box-shadow: 0 0 0 5pt #fff;
  opacity: .85;
}

.products h4 {
  color: white;
  font-size: 55px;
  font-family: 'Western';
  margin-bottom: 5px;
}

.products h5 {
  margin-top: 8px;
  color: #a0a1a0;
  font-size: 25px;
  text-align: left;
  width: 80%;
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
  background: linear-gradient(to bottom, #0f0f0f, #191919 );
  display: flex;
  flex-direction: column;
  align-items: flex-start;
  justify-content: center;
  padding: 60px;
}

.prodcard3 {
  width: 50%;
  height: 100%;
  background: linear-gradient(to bottom, #0f0f0f, #191919 );
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
  height: auto;
  min-height: 175vh;
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
  background-color: rgba(0, 0, 0, 0.40);
  /* opacity: .4; */
  height: 100%;
  width: 100%;
  position: absolute;
  top:0;right:0;bottom:0;left:0;
  z-index: 3;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: space-around;
}

.aboutUsContent>div {
  height: 100%;
  width: 100%;
  display: flex;
  flex-direction: row;
  align-items: center;
  justify-content: space-around;
  margin: 15px 0;
}

.aboutUsContent h2 {
  font-size: 75px;
  margin: 6vh 0 2vh 0;
  color: white;
  font-family: 'Western';
  letter-spacing: 5px;
}

.aboutUsCard {
  background: white;
  height: 700px;
  width: 25vw;
  display: flex;
  align-items: center;
  justify-content: center;
  text-align: center;
  box-shadow: 0 10px 20px rgba(0,0,0,0.19), 0 6px 6px rgba(0,0,0,0.23);
  border-radius: 3px;
}

.aboutUsCardWhistles {
  width: 75vw;
  height: 850px;
}

.aboutUsCard>div {
  height: 100%;
}

.aboutUsCard h3 {
  font-size: 55px;
  margin: 3vh 0 0 0;
  color: white;
  font-family: 'Western';
  /* font-family: 'Roboto', sans-serif; */
  letter-spacing: 3px;
}

.aboutUsCard p {
  font-size: 20px;
  width: 80%;
  color: #a0a1a0;
  font-family: 'Roboto', sans-serif;
}

.aboutUsCardWhistles p {
  width: 50%;
}

.prodCardLine {
  margin: 1vh 0;
  height: 5px;
  width: 60%;
  background: #3f5125;
  border-radius: 1px;
}

.aboutUsCardWhistles .prodCardLine {
  width: 30%;
}

.cardTop {
  width: 100%;
  height: 50%;
  display: flex;
  align-items: center;
  justify-content: center;
}

.cardBottom {
  width: 100%;
  height: 50%;
  background: linear-gradient(to bottom, #0f0f0f, #191919 );
  margin-bottom: 0;
  display: flex;
  flex-direction: column;
  align-items: center;
  padding-top: 5px;
}

.aboutUsCardWhistles .cardTop {
  height: 60%;
}

.aboutUsCardWhistles .cardBottom {
  height: 40%;
  justify-content: center;
}

.aboutUsCardWhistles h3 {
  margin: 0;
}

.about {
  height: auto;
  padding: 12vh 8vh;
  display: flex;
  flex-direction: row;
  align-items: center;
  justify-content: flex-start;
  /* background: #191919; */
  background: linear-gradient(to right bottom, rgba(0, 0, 0, 0.75), rgba(0, 0, 0, 0.9) ), url('./../assets/treeabout.jpg');
  background-position: center;
  background-size: cover;
  background-repeat: none;
  background-attachment: fixed;
  /* border-bottom: 7px white solid;
  border-top: 7px white solid; */
}

.about>div {
  display: flex;
  flex-direction: column;
  align-items: center;
  background: rgba(255, 255, 255, 0.6);
  border-radius: 3px;
  padding: 5vh 1vh;
  min-width: 30vw;
  box-shadow: 0 10px 20px rgba(0,0,0,0.19), 0 6px 6px rgba(0,0,0,0.23);
}

.about h2 {
  font-size: 55px;
  color: #fff;
  font-family: 'Western';
  /* font-family: 'Poppins', sans-serif; */
}

.about h5 {
  font-size: 23px;
  color: #191919;
  width: 80%;
}

.about button {
  color: white;
  border: none;
  border-radius: 3px;
  background: #3f5125;
  padding: 40px 60px;
  font-size: 25px;
  transform: translateY(10vh);
    transition: all .25s ease-in-out;
}

.about button:hover {
  filter: brightness(120%);
    transform: translateY(9vh);
}

.aboutLine {
  margin: 1vh 0 5vh 0;
  height: 5px;
  width: 25%;
  background: #3f5125;
  border-radius: 1px;
  margin: 30px 0 40px 0;
}

.familypic {
  max-width: 50vw;
  margin-left: 8vw;
  border-bottom: 5px solid rgba(63, 81, 37, 0.9);
  border-right: 5px solid rgba(63, 81, 37, 0.6);
  border-left: 5px solid rgba(63, 81, 37, 0.7);
  border-top: 5px solid rgba(63, 81, 37, 0.5);
}

.clients {
  background: linear-gradient(to bottom, rgba(255, 255, 255, 0.1), rgba(255, 255, 255, 0.3) ), url('./../assets/clientsbkgd.jpg');
  background-position: center;
  background-size: cover;
  background-repeat: none;
  background-repeat: no-repeat;
  display: flex;
  flex-direction: column;
  justify-content: center;
  min-height: 50vh;
  padding: 8vh 0;
  overflow: hidden;
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
  margin: 9vh 0;

}

.clients img {
  max-height: 12vh;
  margin: 0 18px;
}

.contact {
  min-height: 35vh;
  background: linear-gradient(to bottom, #0f0f0f, #191919 );
  color: white;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
}

.contact-tabs {
  display: flex;
  flex-direction: row;
  justify-content: center;
  width: 100%;
  margin: 8vh 0 5vh 0;
}

.contact-tabs>a {
  height: 20vh;
  width: 20vw;
  border-top: 3px solid #3f5125;
  cursor: pointer;
}

.contact-tabs>a:hover img {
  transform: translateY(-3px);
  filter: brightness(120%);
}

.contact-divider {
  width: 1px;
  height: 20vh;
  background: #f1f2f3;
  margin: 0 3vw 1vw 3vw;
  border-radius: 1px;
}

.contact img {
  max-height: 7vh;
  margin: 35px 20px;
  transition: all .25s ease-in-out;
}
.contact p {
  font-size: 18px;
  margin-bottom: 3vh;
}

.contact-tabs h3 {
  font-size: 25px;
  margin-bottom: 15px;
  font-family: 'Poppins', sans-serif;
}

.contact-tabs p {
  font-size: 20px;
  margin: 0;
  color: #f1f2f3;
}

.contact-bottom a img {
  max-height: 6vh;
}

.contact-bottom a:hover img {
  transform: translateY(-3px);
  filter: brightness(120%);
}

</style>
