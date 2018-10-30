<template>
  <div id="app">
    <body class="has-fixed-menu">

    <div id="preloader">
        <div class="preloader">
            <span></span>
            <span></span>
        </div>
    </div>

    <div id="top"></div>

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
    <!-- I added line 44  -->

    <router-view/>
       
    <div style="height: 50px"></div> 

    <a href="#top" class="scroll-to-top is-hidden smooth-scroll" data-nav-status="toggle"><i class="md-icon dp18">expand_less</i></a>

    <footer class="dark bg-primary">
        <div class="container-fluid text-center">
            <p>Copyright © 2017. BASIX by <a href="http://kingstudio.ro" target="_blank">KingStudio</a>. All Rights Reserved.</p>
        </div><!-- / container-fluid -->
    </footer>
    </body>
  </div>
</template>
 <style>

</style>