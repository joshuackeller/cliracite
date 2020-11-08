<template>
<div class="FAQ">
<div class="about_wrap">
    <div class="about_con">
      <h1 class="about_header">FAQs</h1>
    </div>
  </div>

  <div class="about_p_wrap">
  <div class="about_p">
    <h2>As a race director, how do I use Racite?</h2>
    <p width="500px">We work with each race director individually to set up
      their page. If you would like to use Racite for your race, please contact
      us at newrace@racite.com. One of our race specialists will help you get
      things started.
    </p>
    <h2>How can I sign up for a race?</h2>
    <p width="500px">To sign up for a race, you will first need to set up and
      account with Racite. You will then be able to go to our Races page and
      find what race you want to sign up for. If you have any problems, please
      email us ad service@racite.com.
    </p>
    <h2>How much does it cost to sign up for a race?</h2>
    <p>Each race decides individually on the entry fee. Prices can be found on
      each individual race page.
    </p>
    <h2>How much does Racite cost as a race director?</h2>
    <p>Fees are decided based on the size of the race and the price of the entry
      fee. If you would like to get a quote for your race, please email
      newrace@racite.com
     </p>
  </div>
  </div>
</div>
</template>

<style scoped>

@font-face {
    font-family: "ChunkFive-Regular";
    src: url("/assets/ChunkFive-Regular.otf");
}
.about_con {
  display: flex;
  justify-content: center;
}
.about_header {
  font-family: "ChunkFive-Regular";
  width: 100px;
}
.about_p_wrap {
  display: flex;
  justify-content: center;
}
.about_p {
  margin: 20px;
  margin-left: 50px;
  margin-bottom: 30px;
  width: 800px;
}
@media only screen and (max-width: 400px) {
  .about_p {
    margin: 20px;
    width: 300px;
  }
}
</style>
