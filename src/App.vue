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
        <!-- <div style="height: 100px"></div>  -->
        <!-- I added line 44  -->
        <header class="business bg-img parallax fixed-menu">
            <div class="container header-inner text-center">
                <h3 class="header-title">BA<span class="text-primary">SIX</span> - BUSINESS TEMPLATE</h3>
                <p class="lead header-text">Suspendisse in mi ut ante vulputate dapibus ac a velit. Fusce semper auctor dui in ultricies. Etiam nec nulla tortor. Donec a nibh facilisis, gravida justo nec, condimentum quam. Proin quis consequat dolor, non sollicitudin erat. Sed viverra et sapien vitae pharetra. Pellentesque venenatis placerat.</p>
                <a href="#services" class="btn btn-black smooth-scroll mr-2">SERVICES</a>
                <a href="#pricing" class="btn btn-primary smooth-scroll">PRICING</a>
            </div>
        </header>

        <div class="cta-big bg-secondary">
            <div class="container text-center">
                <h3 class="mb-0">The winner of  "Best Technology" at <span class="text-primary">Business Awards</span> in 2017!</h3>
            </div><!-- / container -->
        </div><!-- / cta -->

        <div class="container">
            <section id="services">
                <div class="row">
                    <div class="col-md-4">
                        <div class="promo-box text-center inner-space">
                            <i class="md-icon dp36 mb-1 box-icon bg-transparent text-primary">web</i>
                            <h6 class="box-title"><a href="#x" class="promo-link">UI DESIGN</a></h6>
                            <p class="box-description">Built on Bootstrap version 4, your website will look amazing on all screen sizes.</p>
                        </div><!-- / icon-block -->
                    </div><!-- / column -->

                    <div class="col-md-4">
                        <div class="promo-box text-center inner-space">
                            <i class="md-icon dp36 mb-1 box-icon bg-transparent text-primary">loyalty</i>
                            <h6 class="box-title"><a href="#x" class="promo-link">BRANDING</a></h6>
                            <p class="box-description">Built on Bootstrap version 4, your website will look amazing on all screen sizes.</p>
                        </div><!-- / icon-block -->
                    </div><!-- / column -->

                    <div class="col-md-4">
                        <div class="promo-box text-center inner-space">
                            <i class="md-icon dp36 mb-1 box-icon bg-transparent text-primary">trending_up</i>
                            <h6 class="box-title"><a href="#x" class="promo-link">STRATEGY</a></h6>
                            <p class="box-description">Built on Bootstrap version 4, your website will look amazing on all screen sizes.</p>
                        </div><!-- / icon-block -->
                    </div><!-- / column -->

                    <div class="col-md-4">
                        <div class="promo-box text-center inner-space">
                            <i class="md-icon dp36 mb-1 box-icon bg-transparent text-primary">send</i>
                            <h6 class="box-title"><a href="#x" class="promo-link">MARKETING</a></h6>
                            <p class="box-description">Built on Bootstrap version 4, your website will look amazing on all screen sizes.</p>
                        </div><!-- / icon-block -->
                    </div><!-- / column -->

                    <div class="col-md-4">
                        <div class="promo-box text-center inner-space">
                            <i class="md-icon dp36 mb-1 box-icon bg-transparent text-primary">dns</i>
                            <h6 class="box-title"><a href="#x" class="promo-link">DATA STORAGE</a></h6>
                            <p class="box-description">Built on Bootstrap version 4, your website will look amazing on all screen sizes.</p>
                        </div><!-- / icon-block -->
                    </div><!-- / column -->

                    <div class="col-md-4">
                        <div class="promo-box text-center inner-space">
                            <i class="md-icon dp36 mb-1 box-icon bg-transparent text-primary">public</i>
                            <h6 class="box-title"><a href="#x" class="promo-link">SEO</a></h6>
                            <p class="box-description">Built on Bootstrap version 4, your website will look amazing on all screen sizes.</p>
                        </div><!-- / icon-block -->
                    </div><!-- / column -->
                </div><!-- / row -->
            </section>
            <!-- / services -->
        </div><!-- / container -->

        <!-- projects -->
        <section id="projects" class="portfolio-type1 bg-deepgrey">
            <div class="container">
                <ul class="row portfolio list-unstyled" id="grid">
                    <!-- project -->
                    <li class="col-md-6 col-lg-4 project" data-groups='["branding"]'>
                        <figure class="portfolio-item">
                            <div class="hovereffect">
                                <img class="img-responsive" src="images/project1.jpg" alt="">
                                <a href="single-project-business.html">
                                     <div class="overlay">
                                        <div class="hovereffect-title">
                                            <h5>PROJECT 1</h5>
                                        </div><!-- / hovereffect-title -->
                                    </div><!-- / overlay -->
                                </a><!-- / project link -->
                            </div><!-- / hovereffect -->
                        </figure><!-- / portfolio-item -->
                    </li><!-- / project -->

                    <!-- project -->
                    <li class="col-md-6 col-lg-4 project" data-groups='["graphic-design"]'>
                        <figure class="portfolio-item">
                            <div class="hovereffect">
                                <img class="img-responsive" src="images/project2.jpg" alt="">
                                <a href="single-project-business.html">
                                     <div class="overlay">
                                        <div class="hovereffect-title">
                                            <h5>PROJECT 2</h5>
                                        </div><!-- / hovereffect-title -->
                                    </div><!-- / overlay -->
                                </a><!-- / project link -->
                            </div><!-- / hovereffect -->
                        </figure><!-- / portfolio-item -->
                    </li><!-- / project -->

                    <!-- project -->
                    <li class="col-md-6 col-lg-4 project" data-groups='["illustrations"]'>
                        <figure class="portfolio-item">
                            <div class="hovereffect">
                                <img class="img-responsive" src="images/project3.jpg" alt="">
                                <a href="single-project-business.html">
                                     <div class="overlay">
                                        <div class="hovereffect-title">
                                            <h5>PROJECT 3</h5>
                                        </div><!-- / hovereffect-title -->
                                    </div><!-- / overlay -->
                                </a><!-- / project link -->
                            </div><!-- / hovereffect -->
                        </figure><!-- / portfolio-item -->
                    </li><!-- / project -->

                    <!-- project -->
                    <li class="col-md-6 col-lg-4 project" data-groups='["graphic-design"]'>
                        <figure class="portfolio-item">
                            <div class="hovereffect">
                                <img class="img-responsive" src="images/project4.jpg" alt="">
                                <a href="single-project-business.html">
                                     <div class="overlay">
                                        <div class="hovereffect-title">
                                            <h5>PROJECT 4</h5>
                                        </div><!-- / hovereffect-title -->
                                    </div><!-- / overlay -->
                                </a><!-- / project link -->
                            </div><!-- / hovereffect -->
                        </figure><!-- / portfolio-item -->
                    </li><!-- / project -->

                    <!-- project -->
                    <li class="col-md-6 col-lg-4 project" data-groups='["branding"]'>
                        <figure class="portfolio-item">
                            <div class="hovereffect">
                                <img class="img-responsive" src="images/project5.jpg" alt="">
                                <a href="single-project-business.html">
                                     <div class="overlay">
                                        <div class="hovereffect-title">
                                            <h5>PROJECT 5</h5>
                                        </div><!-- / hovereffect-title -->
                                    </div><!-- / overlay -->
                                </a><!-- / project link -->
                            </div><!-- / hovereffect -->
                        </figure><!-- / portfolio-item -->
                    </li><!-- / project -->

                    <!-- project -->
                    <li class="col-md-6 col-lg-4 project" data-groups='["illustrations"]'>
                        <figure class="portfolio-item">
                            <div class="hovereffect">
                                <img class="img-responsive" src="images/project6.jpg" alt="">
                                <a href="single-project-business.html">
                                     <div class="overlay">
                                        <div class="hovereffect-title">
                                            <h5>PROJECT 6</h5>
                                        </div><!-- / hovereffect-title -->
                                    </div><!-- / overlay -->
                                </a><!-- / project link -->
                            </div><!-- / hovereffect -->
                        </figure><!-- / portfolio-item -->
                    </li><!-- / project -->
                </ul> <!-- / portfolio -->
            </div><!-- / container -->
        </section>
        <!-- / projects -->

        <section id="pricing">
            <div class="container">
                <div class="row">
                    <div class="col-md-4">
                        <div class="pricing-table">
                            <div class="pricing-table-title">
                                <h5 class="pricing-title">STARTER</h5>
                            </div>
                            <div class="pricing-table-price">
                                <p>
                                    <span class="pricing-price">FREE</span>
                                </p>
                            </div>
                            <div class="pricing-table-content">
                                <ul>
                                    <li><strong>1 Project</strong></li>
                                    <li>Free Lifetime Updates</li>
                                    <li>24/7 Support</li>
                                    <li>SASS Files Included</li>
                                    <li>Well Documented</li>
                                </ul>
                                <div class="pricing-table-button">
                                    <a href="#x" class="btn btn-primary">DOWNLOAD</a>
                                </div>
                            </div>
                        </div><!-- / pricing-table -->
                    </div><!-- / column -->

                    <div class="col-md-4">
                        <div class="featured pricing-table raised move">
                            <div class="pricing-table-title">
                                <h5 class="pricing-title">STANDARD</h5>
                            </div>
                            <div class="pricing-table-price">
                                <p>
                                    <span class="pricing-currency">$</span>
                                    <span class="pricing-price">4.99</span>
                                    <span class="pricing-period">/ Month</span>
                                </p>
                            </div>
                            <div class="pricing-table-content">
                                <ul>
                                    <li><strong>Up to 10 Projects</strong></li>
                                    <li>Free Lifetime Updates</li>
                                    <li>24/7 Support</li>
                                    <li>SASS Files Included</li>
                                    <li>Well Documented</li>
                                </ul>
                                <div class="pricing-table-button">
                                    <a href="#x" class="btn btn-secondary">BUY NOW</a>
                                </div>
                            </div>
                        </div><!-- / pricing-table -->
                    </div><!-- / column -->

                    <div class="col-md-4">
                        <div class="pricing-table">
                            <div class="pricing-table-title">
                                <h5 class="pricing-title">PREMIUM</h5>
                            </div>
                            <div class="pricing-table-price">
                                <p>
                                    <span class="pricing-currency">$</span>
                                    <span class="pricing-price">29.99</span>
                                    <span class="pricing-period">/ Month</span>
                                </p>
                            </div>
                            <div class="pricing-table-content">
                                <ul>
                                    <li><strong>Unlimited Projects</strong></li>
                                    <li>Free Lifetime Updates</li>
                                    <li>24/7 Support</li>
                                    <li>SASS Files Included</li>
                                    <li>Well Documented</li>
                                </ul>
                                <div class="pricing-table-button">
                                    <a href="#x" class="btn btn-primary">BUY NOW</a>
                                </div>
                            </div>
                        </div><!-- / pricing-table -->
                    </div><!-- / column -->
                </div><!-- / row -->
            </div><!-- / container -->
        </section>
        <!-- / pricing -->

        <section id="testimonials-slider" class="testimonials-bg-img bg-img dark">
            <h3 class="section-title text-center hidden">TESTIMONIALS</h3>
            <div class="container">
                <div id="testimonials-carousel-2" class="owl-carousel carousel-full-nav owl-theme">
                    <div class="block image-block text-center inner-space">
                        <img src="images/testimonial1.jpg" class="block-image circle" alt="">
                        <p class="box-description">Vivamus ornare est at enim placerat, sed rutrum risus consequat. Nam nec feugiat est. Aliquam imperdiet nulla a libero facilisis, vel sollicitudin urna egestas.</p>
                        <p class="cite text-sm text-secondary">- John Doe</p>
                    </div><!-- / image-block -->

                    <div class="block image-block text-center inner-space">
                        <img src="images/testimonial2.jpg" class="block-image circle" alt="">
                        <p class="box-description">Pellentesque ut hendrerit libero. Etiam interdum, velit eget euismod maximus, arcu magna vehicula ligula, at vulputate tortor ligula et nisi.</p>
                        <p class="cite text-sm text-secondary">- Jane Doe</p>
                    </div><!-- / image-block -->
                    
                    <div class="block image-block text-center inner-space">
                        <img src="images/testimonial3.jpg" class="block-image circle" alt="">
                        <p class="box-description">Vestibulum tincidunt orci arcu, non gravida arcu posuere non. Aliquam porta ut enim nec consequat. In tempor ultrices massa sit amet pretium.</p>
                        <p class="cite text-sm text-secondary">- James Doe</p>
                    </div><!-- / image-block -->
                </div><!-- / testimonials-carousel -->
            </div><!-- / container -->
        </section>
        <!-- / testimonials -->

        <div class="cta bg-primary dark">
            <div class="container">
                <div class="text-center">
                    <h3 class="mb-3">Trusted by the best Companies in the World!</h3>
                    <p class="lead">Thousands of customers can't be wrong!</p>
                </div><!-- / row -->
            </div><!-- / container -->
        </div><!-- / cta -->

        <section id="clients" class="w-border">
            <h3 class="section-title text-center hidden">CLIENTS</h3>
            <div class="container">
                <div id="clients-carousel" class="owl-carousel owl-theme">
                    <img src="images/client1.png" alt="">
                    <img src="images/client2.png" alt="">
                    <img src="images/client3.png" alt="">
                    <img src="images/client4.png" alt="">
                    <img src="images/client5.png" alt="">
                    <img src="images/client6.png" alt="">
                    <img src="images/client1.png" alt="">
                    <img src="images/client2.png" alt="">
                    <img src="images/client3.png" alt="">
                    <img src="images/client4.png" alt="">
                    <img src="images/client5.png" alt="">
                    <img src="images/client6.png" alt="">
                </div><!-- / owl-carousel -->
                <!-- / clients carousel -->
            </div><!-- / container -->
        </section>
        <!-- / clients -->

        <div class="cta-big bg-secondary">
            <div class="container">
                <div class="text-center">
                    <h3 class="mb-3">DO YOU WANT TO WORK WITH US?</h3>
                    <div class="spacer">&nbsp;</div>
                    <a href="contact-business.html" class="btn btn-primary"><i class="md-icon dp14 mr-1">phone</i><span>CONTACT US!</span></a>
                </div><!-- / row -->
            </div><!-- / container -->
        </div><!-- / cta -->

    <router-view/>

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
    </body>


  </div>
</template>
 <style>

</style>