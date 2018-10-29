<template>
  <div id="app">
   
   
   <header>
     <nav class="navbar navbar-expand-lg navbar-light fixed-top bg-white custom-menu menu-pills">
         <div class="container">
             <a class="navbar-brand" href="index2.html"><img src="images/logo-blue.png" alt=""></a>
             
             <button class="navbar-toggler navbar-toggler-right" type="button" data-toggle="collapse" data-target="#navbar-toggle" aria-controls="navbar-toggle" aria-expanded="false" aria-label="Toggle navigation">
                 <span class="navbar-toggler-icon"></span>
             </button><!-- / navbar-toggler -->

             <div class="collapse navbar-collapse" id="navbar-toggle">
                 <ul class="navbar-nav ml-auto">
                     <li class="nav-item">
                         <a class="nav-link active" href="index2.html">HOME</a>
                     </li>
                     <li class="nav-item">
                         <a class="nav-link" href="about-business.html">ABOUT</a>
                     </li>
                     <li class="nav-item">
                         <a class="nav-link" href="services-business.html">SERVICES</a>
                     </li>
                     <li class="nav-item">
                         <a class="nav-link" href="portfolio-business.html">PROJECTS</a>
                     </li>
                     <li class="nav-item">
                         <a class="nav-link mr-0" href="contact-business.html">CONTACT</a>
                     </li>
                 </ul><!-- / navbar-nav -->
             </div><!-- / navbar-collapse -->
         </div><!-- / container -->
     </nav><!-- / custom-menu -->
     <div style="height: 100px"></div>
   </header>

     
  <router-view/>
  
  <div style="height: 50px"></div>

  <div class="footer-widgets bg-primary-hover dark">
      <div class="container">
          <div class="row">
              <div class="col-lg-4 widget">
                  <img src="images/logo-blue-light.png" alt="logo" class="footer-logo">
                  <p>Pellentesque at neque enim. In sodales mattis augue quis commodo. Donec sed purus aliquam, dapibus erat id, fringilla magna. Class aptent taciti sociosqu ad litora torquent per conubia nostra, per inceptos himenaeos. Nunc mollis ligula a lacus egestas.</p>
                  <a href="about-business.html" class="btn btn-primary mt-2"><b>READ MORE</b></a>
              </div><!-- / column-->

              <div class="col-lg-4 widget">
                  <h3 class="widget-title">RECENT PROJECTS</h3>
                  <div class="project-widget">
                      <div class="project-small">
                          <a href="#x"><img src="images/project-small1.jpg" alt=""></a>
                          <a href="#x"><img src="images/project-small2.jpg" alt=""></a>
                          <a href="#x"><img src="images/project-small3.jpg" alt=""></a>
                          <a href="#x"><img src="images/project-small4.jpg" alt=""></a>
                          <a href="#x"><img src="images/project-small5.jpg" alt=""></a>
                          <a href="#x"><img src="images/project-small6.jpg" alt=""></a>
                          <a href="#x"><img src="images/project-small7.jpg" alt=""></a>
                          <a href="#x"><img src="images/project-small8.jpg" alt=""></a>
                      </div><!-- / project-small -->
                  </div><!-- / project-widget -->
              </div><!-- / column-->

              <div class="col-lg-4 widget">
                  <h3 class="widget-title">USEFUL LINKS</h3>
                  <ul class="useful-links">
                      <li class="mb-3 border-primary"><a href="#x">Privacy Policy</a></li>
                      <li class="mb-3 border-primary"><a href="#x">Terms & Conditions</a></li>
                      <li class="mb-3 border-primary"><a href="#x">Support Center</a></li>
                      <li class="mb-3 border-primary"><a href="#x">Contact Us</a></li>
                  </ul>
              </div><!-- / column-->
          </div><!-- / row -->
      </div><!-- / container -->
  </div><!-- / footer-widgets -->

  <a href="#top" class="scroll-to-top is-hidden smooth-scroll" data-nav-status="toggle"><i class="md-icon dp18">expand_less</i></a>

  <footer class="dark bg-primary">
      <div class="container-fluid text-center">
          <p>Copyright © 2017. BASIX by <a href="http://kingstudio.ro" target="_blank">KingStudio</a>. All Rights Reserved.</p>
      </div><!-- / container-fluid -->
  </footer>

  </div>
</template>

<style>

</style>