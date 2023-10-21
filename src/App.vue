<template>
  <section class="main">
    <div class="submain">
      <video controls width="100%" height="100%">
        <source type="video/mp4" src="https://vimeo.com/876346618?share=copy" />
        <source type="video/webm" src="https://vimeo.com/876346618?share=copy" />
     </video>
    </div>
    <div class="submain2">
      <article>
        <h1>Our Ideology</h1>
        <h4>Working with the Best, for the Best.</h4>
        <p>Here at Zephurus, we've worked with the best in the industry, We collaborate closely with each of our clients, immersing ourselves
          in their businesses to comprehend their unique requirements thoroughly.
        </p>
        <i class="embrace">Your success is our success!</i>
        <h4>Embrace the Future Today</h4>
        <p>Don't be left behind; embrace the future of customer engagement with our AI-powered chatbots for businesses. Transform the way you interact with your customers, drive
          revenue growth, and outshine your competition with the power of artificial intelligence.
        </p>
      </article>
    </div>
  </section>
</template>

<script>
  
</script>

<style>
* {
  box-sizing: border-box;
}
body {
  margin: 0px !important;
  font-family: 'Kanit', sans-serif;
}

.main {
  width: 100%;
  height: 25rem;
  margin-top: 7rem;
  display: flex;
  flex-direction: row;
  flex-wrap: wrap;
  justify-content: space-between;
}
.submain {
  width: 45%;
  height: 100%;
}
.submain2 {
  width: 50%;
  height: auto;
}

.submain2 h1 {
  font-size: 30px;
  line-height: 10px;
}
.submain2 .embrace {
  color: dodgerblue;

}

@media screen and (max-width: 768px) {
  .main {
    flex-direction: column;
    justify-content: space-between;
    height: auto;
  }
  .submain {
    width: 100%;
    height: 400px;
  }
  .submain2 {
    width: 100%;
    margin-top: 20px;
    height: auto;
  }
}

</style>
