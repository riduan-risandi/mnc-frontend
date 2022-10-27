<template>
  <div>
<body data-spy="scroll" data-target=".site-navbar-target" data-offset="300">

  <nav class="navbar navbar-expand-lg navbar-dark ftco_navbar bg-dark ftco-navbar-light site-navbar-target" id="ftco-navbar">
      <div class="container">
          <a href="#" class="navbar-brand">
              <router-link to="/"><img src="images/aven.png" alt="" /></router-link>
          </a>
      <a class="navbar-brand" href="index.html">Aven <span class="gradient4">Residence</span></a>
      <button class="navbar-toggler js-fh5co-nav-toggle fh5co-nav-toggle" type="button" data-toggle="collapse" data-target="#ftco-nav" aria-controls="ftco-nav" aria-expanded="false" aria-label="Toggle navigation">
        <span class="oi oi-menu"></span> Menu
      </button>

          <div class="collapse navbar-collapse" id="ftco-nav">
              <ul class="navbar-nav nav ml-auto">
                  <li class="nav-item"><a href="#home-section" class="nav-link"><span>Unit Types</span></a></li>
                  <li class="nav-item"><a href="#services-section" class="nav-link"><span>Facilities</span></a></li>
                  <li class="nav-item"><a href="#projects-section" class="nav-link"><span>Location</span></a></li>
                  <li class="nav-item"><a href="#about-section" class="nav-link"><span>Developer</span></a></li>
                  <li class="nav-item"><a href="#" class="btn btn-primary2">Contact Us &nbsp;</a></li>
              </ul>
          </div>
      </div>
  </nav>

  <div class="ftco-section-2 img" style="background-image: url('/images/bg_fix.png')"  >  
    <br><br>
      <!-- <div class="home-slider js-fullheight owl-carousel"> -->
          <div class="slider-item js-fullheight"> 
                <div class="container-fluid p-0"> 
                        <div class="text col-md-12">
                              <h1 class="mb-4 mt-3">Find your <br><span class="gradient4" >dream</span> house</h1>
                              <p class="pdesc">Aven Residence provides several houses with <br>strategic locations and affordable prices.</p> 
                            <div class="input-group-prepend">
                                <a class="btn btn-primary4 ">Download Brochure</a> 
                                <a class="btn btn-primary3 ">View Unit</a>  
                            </div> 
 
                        </div>
                </div>
          </div>
      <!-- </div> -->
    </div>  
 
</body></div>
</template>

<script>
export default {
  name: 'HelloWorld' ,
  mounted() {
    let Script = document.createElement("script");
    Script.setAttribute("src", "https://cdnjs.cloudflare.com/ajax/libs/OwlCarousel2/2.3.4/owl.carousel.min.js");
    Script.setAttribute("src", "https://www.jsdelivr.com/package/npm/main-js");
    Script.setAttribute("src", "https://cdnjs.cloudflare.com/ajax/libs/jquery/3.6.1/jquery.min.js");
    Script.setAttribute("src", "https://maps.googleapis.com/maps/api/js?key=AIzaSyBVWaKrjvy3MaE7SQ74_uJiULgl1JY0H2s&sensor=false");
    
    document.head.appendChild(Script);
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
} 
    .img{
        height: 600px; 
    }
    .btn-primary2 {
        /* Auto layout */
        display: flex;
        flex-direction: row;
        /* align-items: center; */
        color: white;
        /* font-color: #FFFFFF; */
        padding: 16px 32px;
        gap: 10px;
        width: 151px;
        height: 56px;
        background: #6F4A9E;
        border-radius: 10px;
    }
    
    .btn-primary3 {
        /* Auto layout */
        display: flex;
        flex-direction: row;
        /* align-items: center; */
        color: black;
        border-color: #dee2e6;
        padding: 16px 32px;
        gap: 10px;
        width: 151px;
        height: 56px;
        background: #FFFFFF;
        border-radius: 10px;
    }
    .btn-primary4 {
        /* Auto layout */
        display: flex;
        flex-direction: row;
        align-items: center; 
        /* font-color: #FFFFFF; */
        padding: 16px 32px;
        gap: 10px;
        width: 151px;
        height: 56px;
        background: #6F4A9E;
        color: white;
        border-radius: 10px;
        margin-right: 10px;
        
    }
    
    /*  .btn-primary3 { 
        position: absolute;
        width: 1440px;
        height: 872px;
        left: 0px;
        top: 152px;
        background: url(house-isolated-field.png);
    } */
    
    .h1 {
        /* Find your dream house */
        width: 517px;
        height: 168px;
        font-family: 'Inter';
        font-style: normal;
        font-weight: 800;
        font-size: 72px;
        line-height: 84px;
        /* or 117% */
        color: #161932;
        /* Inside auto layout */
        flex: none;
        order: 0;
        flex-grow: 0;
    }
    
    .pdesc {
        /* Aven Residence provides several houses with strategic locations and affordable prices. */
        width: 517px;
        height: 68px;
        font-family: 'Inter';
        font-style: normal;
        font-weight: 400;
        font-size: 20px;
        line-height: 34px;
        /* or 170% */
        color: rgba(22, 25, 50, 0.6);
        /* Inside auto layout */
        flex: none;
        order: 1;
        flex-grow: 0;
    }
    
    .pdownload {
        /* Button Primary */
        /* Auto layout */
        display: flex;
        flex-direction: row;
        align-items: center;
        padding: 16px 32px;
        gap: 10px;
        width: 216px;
        height: 56px;
        background: #6F4A9E;
        border-radius: 10px;
        /* Inside auto layout */
        flex: none;
        order: 0;
        flex-grow: 0;
        /* Download Brochure */
        width: 152px;
        height: 24px;
        font-family: 'Inter';
        font-style: normal;
        font-weight: 600;
        font-size: 16px;
        line-height: 24px;
        /* identical to box height, or 150% */
        color: #FFFFFF;
        /* Inside auto layout */
        flex: none;
        order: 0;
        flex-grow: 0;
    }
    
    #gradient4 {
        background-image: linear-gradient(-90deg, 161932, yellow);
    }
</style>
