# Project Responsive Web Design using Bootstrap
## Date:09/05/2024

## AIM:
To design a responsive website for a Pharmaceutical Company using Bootstrap.


## DESIGN STEPS:

### Step 1:
Clone the repository from GitHub.

### Step 2:
Create Django Admin project.

### Step 3:
Create a New App under the Django Admin project.

### Step 4:
Insert the necessary CSS and JavaScript files as external in order to use Bootstrap.

### Step 5:
Create a HTML file and include the needed Bootstrap components.

### Step 6:
Publish the website in the LocalHost.

## PROGRAM :
about.html
```
<!doctype html>
<html class="no-js" lang="zxx">

<head>
    <meta charset="utf-8">
    <meta http-equiv="x-ua-compatible" content="ie=edge">
    <title>Medi</title>
    <meta name="description" content="">
    <meta name="viewport" content="width=device-width, initial-scale=1">

    <!-- <link rel="manifest" href="site.webmanifest"> -->
    <link rel="shortcut icon" type="image/x-icon" href="img/favicon.png">
    <!-- Place favicon.ico in the root directory -->

    <!-- CSS here -->
    <link rel="stylesheet" href="css/bootstrap.min.css">
    <link rel="stylesheet" href="css/owl.carousel.min.css">
    <link rel="stylesheet" href="css/magnific-popup.css">
    <link rel="stylesheet" href="css/font-awesome.min.css">
    <link rel="stylesheet" href="css/themify-icons.css">
    <link rel="stylesheet" href="css/nice-select.css">
    <link rel="stylesheet" href="css/flaticon.css">
    <link rel="stylesheet" href="css/gijgo.css">
    <link rel="stylesheet" href="css/animate.css">
    <link rel="stylesheet" href="css/slicknav.css">
    <link rel="stylesheet" href="css/style.css">
    <!-- <link rel="stylesheet" href="css/responsive.css"> -->
</head>

<body>
    <!--[if lte IE 9]>
            <p class="browserupgrade">You are using an <strong>outdated</strong> browser. Please <a href="https://browsehappy.com/">upgrade your browser</a> to improve your experience and security.</p>
        <![endif]-->


    <!-- header-start -->
    <header>
        <div class="header-area ">
            <div id="sticky-header" class="main-header-area">
                <div class="container">
                    <div class="row align-items-center">
                        <div class="col-xl-3 col-lg-3">
                            <div class="logo-img">
                                <a href="index.html">
                                    <img src="img/logo.png" alt="">
                                </a>
                            </div>
                        </div>
                        <div class="col-xl-9 col-lg-9">
                            <div class="menu_wrap d-none d-lg-block">
                                <div class="menu_wrap_inner d-flex align-items-center justify-content-end">
                                    <div class="main-menu">
                                        <nav>
                                            <ul id="navigation">
                                                <li><a href="index.html">home</a></li>
                                                <li><a href="about.html">About</a></li>
                                                <li><a href="#">blog <i class="ti-angle-down"></i></a>
                                                    <ul class="submenu">
                                                        <li><a href="blog.html">blog</a></li>
                                                        <li><a href="single-blog.html">single-blog</a></li>
                                                    </ul>
                                                </li>
                                                <li><a href="#">pages <i class="ti-angle-down"></i></a>
                                                    <ul class="submenu">
                                                        <li><a href="department.html">Deportment</a></li>
                                                        <li><a href="elements.html">elements</a></li>
                                                    </ul>
                                                </li>
                                                <li><a href="contact.html">Contact</a></li>
                                            </ul>
                                        </nav>
                                    </div>
                                    <div class="book_room">
                                        <div class="book_btn">
                                            <a class="popup-with-form" href="#test-form">Book  Appointment</a>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>
                        <div class="col-12">
                            <div class="mobile_menu d-block d-lg-none"></div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </header>
    <!-- header-end -->

    <!-- bradcam_area_start  -->
    <div class="bradcam_area breadcam_bg">
        <div class="container">
            <div class="row">
                <div class="col-xl-12">
                    <div class="bradcam_text">
                        <h3>About Us</h3>
                    </div>
                </div>
            </div>
        </div>
    </div>
    <!-- bradcam_area_end  -->

    <!-- welcome_clicnic_area_start -->
    <div class="welcome_clicnic_area">
        <div class="container">
            <div class="row align-items-center">
                <div class="col-xl-6 col-lg-6">
                    <div class="welcome_thumb">
                        <div class="thumb_1">
                            <img src="img/about/1.jpg" alt="">
                        </div>
                    </div>
                </div>
                <div class="col-xl-6 col-lg-6">
                    <div class="welcome_docmed_info">
                        <h3>Welcome To
                            <span>Modern Clinic.</span></h3>
                        <p>Lorem ipsum dolor sit amet, consectetur Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veni.</p>
                        <ul>
                            <li> <i class="flaticon-verified"></i> Lorem ipsum dolor sit amet </li>
                            <li> <i class="flaticon-verified"></i> Consectetur adipisicing elit, sed do</li>
                            <li> <i class="flaticon-verified"></i> Eiusmod tempor incididunt ut labore </li>
                        </ul>
                        <a href="about.html" class="boxed-btn6">About us</a>
                    </div>
                </div>
            </div>
        </div>
    </div>
    <!-- welcome_clicnic_area_end -->


    <!-- expert_doctors_area_start -->
    <div class="expert_doctors_area p-0">
        <div class="container">
            <div class="row justify-content-center ">
                <div class="col-lg-6">
                    <div class="section_title mb-55 text-center">
                        <h3>Our Doctors</h3>
                        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore.</p>
                    </div>
                </div>
            </div>
            <div class="row justify-content-center">
                <div class="col-lg-4 col-md-6">
                    <div class="single_expert">
                        <div class="expert_thumb">
                            <img src="img/experts/1.png" alt="">
                        </div>
                        <div class="experts_name text-center">
                            <h3>Jhon Smith</h3>
                            <span>Dentist</span>
                            <div class="social_links">
                                <ul>
                                    <li>
                                        <a href="#"> <i class="fa fa-facebook"></i> </a>
                                    </li>
                                    <li>
                                        <a href="#"> <i class="fa fa-linkedin"></i> </a>
                                    </li>
                                    <li>
                                        <a href="#"> <i class="fa fa-twitter"></i> </a>
                                    </li>
                                </ul>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="col-lg-4 col-md-6">
                    <div class="single_expert">
                        <div class="expert_thumb">
                            <img src="img/experts/2.png" alt="">
                        </div>
                        <div class="experts_name text-center">
                            <h3>Will jacks</h3>
                            <span>Ortho surgeon</span>
                            <div class="social_links">
                                <ul>
                                    <li>
                                        <a href="#"> <i class="fa fa-facebook"></i> </a>
                                    </li>
                                    <li>
                                        <a href="#"> <i class="fa fa-linkedin"></i> </a>
                                    </li>
                                    <li>
                                        <a href="#"> <i class="fa fa-twitter"></i> </a>
                                    </li>
                                </ul>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="col-lg-4 col-md-6">
                    <div class="single_expert">
                        <div class="expert_thumb">
                            <img src="img/experts/3.png" alt="">
                        </div>
                        <div class="experts_name text-center">
                            <h3>Travis Head</h3>
                            <span>MBBS</span>
                            <div class="social_links">
                                <ul>
                                    <li>
                                        <a href="#"> <i class="fa fa-facebook"></i> </a>
                                    </li>
                                    <li>
                                        <a href="#"> <i class="fa fa-linkedin"></i> </a>
                                    </li>
                                    <li>
                                        <a href="#"> <i class="fa fa-twitter"></i> </a>
                                    </li>
                                </ul>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
    <!-- expert_doctors_area_end -->

    <!-- quality_area_start  -->
    <div class="quality_area">
        <div class="container">
            <div class="row justify-content-center ">
                <div class="col-lg-6">
                    <div class="section_title mb-55 text-center">
                        <h3>Quality Health</h3>
                        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore.</p>
                    </div>
                </div>
            </div>
            <div class="row">
                <div class="col-lg-4 col-md-6">
                    <div class="single_quality">
                        <div class="icon">
                            <i class="flaticon-customer-service"></i>
                        </div>
                        <h3>Health Consultation</h3>
                        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt.</p>
                    </div>
                </div>
                <div class="col-lg-4 col-md-6">
                    <div class="single_quality">
                        <div class="icon">
                            <i class="flaticon-find"></i>
                        </div>
                        <h3>Find Health</h3>
                        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt.</p>
                    </div>
                </div>
                <div class="col-lg-4 col-md-6">
                    <div class="single_quality">
                        <div class="icon">
                            <i class="flaticon-doctor"></i>
                        </div>
                        <h3>Search Deoctor</h3>
                        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt.</p>
                    </div>
                </div>
            </div>
        </div>
    </div>
    <!-- quality_areaend  -->

    <!-- Emergency_contact start -->
    <div class="Emergency_contact">
        <div class="Emergency_contact_inner ">
            <div class="container">
                <div class="row align-items-center">
                    <div class="col-lg-6">
                        <div class="single_emergency">
                            <div class="info">
                                <span>We are here for you</span>
                                <h3>Book Appointment</h3>
                            </div>
                            <div class="info_button">
                                <a href="#" class="boxed-btn3-white">Book Appointment
                                </a>
                            </div>
                        </div>
                    </div>
                    <div class="col-lg-6">
                        <div class="single_emergency align-items-center d-flex justify-content-end">
                            <div class="icon">
                                <i class="flaticon-call"></i>
                            </div>
                            <div class="info">
                                <span>Emergency Medical Care</span>
                                <h3>+1-465 4545</h3>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
    <!-- Emergency_contact end -->

    <footer class="footer">
        <div class="footer_top">
            <div class="container">
                <div class="row">
                    <div class="col-xl-4 col-md-6 col-lg-4 ">
                        <div class="footer_widget">
                            <div class="footer_logo">
                                <a href="#">
                                    <img src="img/logo.png" alt="">
                                </a>
                            </div>
                            <p class="address_text">Lorem ipsum dolor sit amet, <br> consectetur adipiscing elit, sed do <br> eiusmod tempor incididunt ut labore.
                            </p>
                            <div class="socail_links">
                                <ul>
                                    <li>
                                        <a href="#">
                                            <i class="ti-facebook"></i>
                                        </a>
                                    </li>
                                    <li>
                                        <a href="#">
                                            <i class="ti-twitter-alt"></i>
                                        </a>
                                    </li>
                                    <li>
                                        <a href="#">
                                            <i class="fa fa-dribbble"></i>
                                        </a>
                                    </li>
                                    <li>
                                        <a href="#">
                                            <i class="fa fa-instagram"></i>
                                        </a>
                                    </li>
                                </ul>
                            </div>

                        </div>
                    </div>
                    <div class="col-xl-4 col-md-6 col-lg-4">
                        <div class="footer_widget">
                            <h3 class="footer_title">
                                Our Departments
                            </h3>
                            <ul class="links">
                                <li><a href="#">Births</a></li>
                                <li><a href="#">Pulmonary</a></li>
                                <li><a href="#">Cardiology</a></li>
                                <li><a href="#">Neurology</a></li>
                                <li><a href="#">Traumatology</a></li>
                                <li><a href="#">Dental</a></li>
                                <li><a href="#">Nuclear</a></li>
                                <li><a href="#">magnetic</a></li>
                                <li><a href="#">Pregnancy</a></li>
                                <li><a href="#">For disabled</a></li>
                                <li><a href="#">X-ray</a></li>
                                <li><a href="#">Prostheses</a></li>
                            </ul>
                        </div>
                    </div>
                    <div class="col-xl-4  col-md-6 col-lg-4">
                        <div class="footer_widget">
                            <h3 class="footer_title">
                                We’re Available
                            </h3>
                            <ul class="meting_time">
                                <li class="d-flex justify-content-between "><span>Monday - Friday</span> <span>8.00 - 18.00</span></li>
                                <li class="d-flex justify-content-between "><span>Saturday	</span> <span>8.00 - 18.00</span></li>
                                <li class="d-flex justify-content-between "><span>Sunday</span> <span>8.00 - 13.00</span></li>
                            </ul>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <div class="copy-right_text">
            <div class="container">
                <div class="row">
                    <div class="bordered_1px "></div>
                    <div class="col-xl-12">
                        <p class="copy_right text-center">
                            <p><!-- Link back to Colorlib can't be removed. Template is licensed under CC BY 3.0. -->
  Copyright &copy;<script>document.write(new Date().getFullYear());</script> All rights reserved | SHIV SUJAN S R(212223040194)
                        </p>
                    </div>
                </div>
            </div>
        </div>
    </footer>

    <!-- link that opens popup -->

    <!-- form itself end-->
    <form id="test-form" class="white-popup-block mfp-hide">
        <div class="popup_box ">
            <div class="popup_inner">
                <h3>
                    Book an 
                <span>Appointment</span>
                </h3>
                <form action="#">
                    <div class="row">
                        <div class="col-xl-12">
                            <select class="form-select wide" id="default-select" class="">
                                <option data-display="Please select doctor to visit">Please select doctor to visit </option>
                                <option value="1">Anaf</option>
                                <option value="2">Nayna Therapy</option>
                                <option value="3">Nadif</option>
                            </select>
                        </div>
                        <div class="col-xl-9">
                            <input type="text"  placeholder="Your name ">
                        </div>
                        <div class="col-xl-3">
                            <input type="text"  placeholder="Your age">
                        </div>
                        <div class="col-xl-6">
                            <input type="text"  placeholder="Phone number ">
                        </div>
                        <div class="col-xl-6">
                            <input type="email"  placeholder="Email Address">
                        </div>
                        <div class="col-xl-6">
                            <input class="datepicker" placeholder="Appointment Date">
                        </div>
                        <div class="col-xl-6">
                            <input class="timepicker" placeholder="Suitable time">
                        </div>
                        <div class="col-xl-12">
                            <button type="submit" class="boxed-btn3">Make an Appointment</button>
                        </div>
                    </div>
                </form>
            </div>
        </div>
    </form>
    <!-- form itself end -->

    <!-- JS here -->
    <script src="js/vendor/modernizr-3.5.0.min.js"></script>
    <script src="js/vendor/jquery-1.12.4.min.js"></script>
    <script src="js/popper.min.js"></script>
    <script src="js/bootstrap.min.js"></script>
    <script src="js/owl.carousel.min.js"></script>
    <script src="js/isotope.pkgd.min.js"></script>
    <script src="js/ajax-form.js"></script>
    <script src="js/waypoints.min.js"></script>
    <script src="js/jquery.counterup.min.js"></script>
    <script src="js/imagesloaded.pkgd.min.js"></script>
    <script src="js/scrollIt.js"></script>
    <script src="js/jquery.scrollUp.min.js"></script>
    <script src="js/wow.min.js"></script>
    <script src="js/nice-select.min.js"></script>
    <script src="js/jquery.slicknav.min.js"></script>
    <script src="js/jquery.magnific-popup.min.js"></script>
    <script src="js/plugins.js"></script>
    <script src="js/gijgo.min.js"></script>
    <!--contact js-->
    <script src="js/contact.js"></script>
    <script src="js/jquery.ajaxchimp.min.js"></script>
    <script src="js/jquery.form.js"></script>
    <script src="js/jquery.validate.min.js"></script>
    <script src="js/mail-script.js"></script>

    <script src="js/main.js"></script>
    <script>
        $('.datepicker').datepicker({
            iconsLibrary: 'fontawesome',
            icons: {
                rightIcon: '<span class="fa fa-calendar"></span>'
            }
        });

        $('.timepicker').timepicker({
            iconsLibrary: 'fontawesome',
            icons: {
                rightIcon: '<span class="fa fa-clock-o"></span>'
            }
        });
    $(document).ready(function() {
    $('.js-example-basic-multiple').select2();
});
    </script>
</body>

</html>
```
blog.html
```
<!doctype html>
<html class="no-js" lang="zxx">

<head>
    <meta charset="utf-8">
    <meta http-equiv="x-ua-compatible" content="ie=edge">
    <title>Docmed</title>
    <meta name="description" content="">
    <meta name="viewport" content="width=device-width, initial-scale=1">

    <!-- <link rel="manifest" href="site.webmanifest"> -->
    <link rel="shortcut icon" type="image/x-icon" href="img/favicon.png">
    <!-- Place favicon.ico in the root directory -->

    <!-- CSS here -->
    <link rel="stylesheet" href="css/bootstrap.min.css">
    <link rel="stylesheet" href="css/owl.carousel.min.css">
    <link rel="stylesheet" href="css/magnific-popup.css">
    <link rel="stylesheet" href="css/font-awesome.min.css">
    <link rel="stylesheet" href="css/themify-icons.css">
    <link rel="stylesheet" href="css/nice-select.css">
    <link rel="stylesheet" href="css/flaticon.css">
    <link rel="stylesheet" href="css/gijgo.css">
    <link rel="stylesheet" href="css/animate.css">
    <link rel="stylesheet" href="css/slicknav.css">
    <link rel="stylesheet" href="css/style.css">
    <!-- <link rel="stylesheet" href="css/responsive.css"> -->
</head>

<body>
    <!--[if lte IE 9]>
            <p class="browserupgrade">You are using an <strong>outdated</strong> browser. Please <a href="https://browsehappy.com/">upgrade your browser</a> to improve your experience and security.</p>
        <![endif]-->

    <!-- header-start -->
    <header>
        <div class="header-area ">
            <div id="sticky-header" class="main-header-area">
                <div class="container">
                    <div class="row align-items-center">
                        <div class="col-xl-3 col-lg-3">
                            <div class="logo-img">
                                <a href="index.html">
                                    <img src="img/logo.png" alt="">
                                </a>
                            </div>
                        </div>
                        <div class="col-xl-9 col-lg-9">
                            <div class="menu_wrap d-none d-lg-block">
                                <div class="menu_wrap_inner d-flex align-items-center justify-content-end">
                                    <div class="main-menu">
                                        <nav>
                                            <ul id="navigation">
                                                <li><a href="index.html">home</a></li>
                                                <li><a href="about.html">About</a></li>
                                                <li><a href="#">blog <i class="ti-angle-down"></i></a>
                                                    <ul class="submenu">
                                                        <li><a href="blog.html">blog</a></li>
                                                        <li><a href="single-blog.html">single-blog</a></li>
                                                    </ul>
                                                </li>
                                                <li><a href="#">pages <i class="ti-angle-down"></i></a>
                                                    <ul class="submenu">
                                                        <li><a href="department.html">Deportment</a></li>
                                                        <li><a href="elements.html">elements</a></li>
                                                    </ul>
                                                </li>
                                                <li><a href="contact.html">Contact</a></li>
                                            </ul>
                                        </nav>
                                    </div>
                                    <div class="book_room">
                                        <div class="book_btn">
                                            <a class="popup-with-form" href="#test-form">Book  Appointment</a>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>
                        <div class="col-12">
                            <div class="mobile_menu d-block d-lg-none"></div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </header>
    <!-- header-end -->
  
    <!-- bradcam_area_start  -->
    <div class="bradcam_area breadcam_bg">
        <div class="container">
            <div class="row">
                <div class="col-xl-12">
                    <div class="bradcam_text">
                        <h3>blog</h3>
                    </div>
                </div>
            </div>
        </div>
    </div>
    <!-- bradcam_area_end  -->


    <!--================Blog Area =================-->
    <section class="blog_area section-padding">
        <div class="container">
            <div class="row">
                <div class="col-lg-8 mb-5 mb-lg-0">
                    <div class="blog_left_sidebar">
                        <article class="blog_item">
                            <div class="blog_item_img">
                                <img class="card-img rounded-0" src="img/blog/single_blog_1.png" alt="">
                                <a href="#" class="blog_item_date">
                                    <h3>15</h3>
                                    <p>Jan</p>
                                </a>
                            </div>

                            <div class="blog_details">
                                <a class="d-inline-block" href="single-blog.html">
                                    <h2>Google inks pact for new 35-storey office</h2>
                                </a>
                                <p>That dominion stars lights dominion divide years for fourth have don't stars is that
                                    he earth it first without heaven in place seed it second morning saying.</p>
                                <ul class="blog-info-link">
                                    <li><a href="#"><i class="fa fa-user"></i> Travel, Lifestyle</a></li>
                                    <li><a href="#"><i class="fa fa-comments"></i> 03 Comments</a></li>
                                </ul>
                            </div>
                        </article>

                        <article class="blog_item">
                            <div class="blog_item_img">
                                <img class="card-img rounded-0" src="img/blog/single_blog_2.png" alt="">
                                <a href="#" class="blog_item_date">
                                    <h3>15</h3>
                                    <p>Jan</p>
                                </a>
                            </div>

                            <div class="blog_details">
                                <a class="d-inline-block" href="single-blog.html">
                                    <h2>Google inks pact for new 35-storey office</h2>
                                </a>
                                <p>That dominion stars lights dominion divide years for fourth have don't stars is that
                                    he earth it first without heaven in place seed it second morning saying.</p>
                                <ul class="blog-info-link">
                                    <li><a href="#"><i class="fa fa-user"></i> Travel, Lifestyle</a></li>
                                    <li><a href="#"><i class="fa fa-comments"></i> 03 Comments</a></li>
                                </ul>
                            </div>
                        </article>

                        <article class="blog_item">
                            <div class="blog_item_img">
                                <img class="card-img rounded-0" src="img/blog/single_blog_3.png" alt="">
                                <a href="#" class="blog_item_date">
                                    <h3>15</h3>
                                    <p>Jan</p>
                                </a>
                            </div>

                            <div class="blog_details">
                                <a class="d-inline-block" href="single-blog.html">
                                    <h2>Google inks pact for new 35-storey office</h2>
                                </a>
                                <p>That dominion stars lights dominion divide years for fourth have don't stars is that
                                    he earth it first without heaven in place seed it second morning saying.</p>
                                <ul class="blog-info-link">
                                    <li><a href="#"><i class="fa fa-user"></i> Travel, Lifestyle</a></li>
                                    <li><a href="#"><i class="fa fa-comments"></i> 03 Comments</a></li>
                                </ul>
                            </div>
                        </article>

                        <article class="blog_item">
                            <div class="blog_item_img">
                                <img class="card-img rounded-0" src="img/blog/single_blog_4.png" alt="">
                                <a href="#" class="blog_item_date">
                                    <h3>15</h3>
                                    <p>Jan</p>
                                </a>
                            </div>

                            <div class="blog_details">
                                <a class="d-inline-block" href="single-blog.html">
                                    <h2>Google inks pact for new 35-storey office</h2>
                                </a>
                                <p>That dominion stars lights dominion divide years for fourth have don't stars is that
                                    he earth it first without heaven in place seed it second morning saying.</p>
                                <ul class="blog-info-link">
                                    <li><a href="#"><i class="fa fa-user"></i> Travel, Lifestyle</a></li>
                                    <li><a href="#"><i class="fa fa-comments"></i> 03 Comments</a></li>
                                </ul>
                            </div>
                        </article>

                        <article class="blog_item">
                            <div class="blog_item_img">
                                <img class="card-img rounded-0" src="img/blog/single_blog_5.png" alt="">
                                <a href="#" class="blog_item_date">
                                    <h3>15</h3>
                                    <p>Jan</p>
                                </a>
                            </div>

                            <div class="blog_details">
                                <a class="d-inline-block" href="single-blog.html">
                                    <h2>Google inks pact for new 35-storey office</h2>
                                </a>
                                <p>That dominion stars lights dominion divide years for fourth have don't stars is that
                                    he earth it first without heaven in place seed it second morning saying.</p>
                                <ul class="blog-info-link">
                                    <li><a href="#"><i class="fa fa-user"></i> Travel, Lifestyle</a></li>
                                    <li><a href="#"><i class="fa fa-comments"></i> 03 Comments</a></li>
                                </ul>
                            </div>
                        </article>

                        <nav class="blog-pagination justify-content-center d-flex">
                            <ul class="pagination">
                                <li class="page-item">
                                    <a href="#" class="page-link" aria-label="Previous">
                                        <i class="ti-angle-left"></i>
                                    </a>
                                </li>
                                <li class="page-item">
                                    <a href="#" class="page-link">1</a>
                                </li>
                                <li class="page-item active">
                                    <a href="#" class="page-link">2</a>
                                </li>
                                <li class="page-item">
                                    <a href="#" class="page-link" aria-label="Next">
                                        <i class="ti-angle-right"></i>
                                    </a>
                                </li>
                            </ul>
                        </nav>
                    </div>
                </div>
                <div class="col-lg-4">
                    <div class="blog_right_sidebar">
                        <aside class="single_sidebar_widget search_widget">
                            <form action="#">
                                <div class="form-group">
                                    <div class="input-group mb-3">
                                        <input type="text" class="form-control" placeholder='Search Keyword'
                                            onfocus="this.placeholder = ''"
                                            onblur="this.placeholder = 'Search Keyword'">
                                        <div class="input-group-append">
                                            <button class="btn" type="button"><i class="ti-search"></i></button>
                                        </div>
                                    </div>
                                </div>
                                <button class="button rounded-0 primary-bg text-white w-100 btn_1 boxed-btn"
                                    type="submit">Search</button>
                            </form>
                        </aside>

                        <aside class="single_sidebar_widget post_category_widget">
                            <h4 class="widget_title">Category</h4>
                            <ul class="list cat-list">
                                <li>
                                    <a href="#" class="d-flex">
                                        <p>Resaurant food</p>
                                        <p>(37)</p>
                                    </a>
                                </li>
                                <li>
                                    <a href="#" class="d-flex">
                                        <p>Travel news</p>
                                        <p>(10)</p>
                                    </a>
                                </li>
                                <li>
                                    <a href="#" class="d-flex">
                                        <p>Modern technology</p>
                                        <p>(03)</p>
                                    </a>
                                </li>
                                <li>
                                    <a href="#" class="d-flex">
                                        <p>Product</p>
                                        <p>(11)</p>
                                    </a>
                                </li>
                                <li>
                                    <a href="#" class="d-flex">
                                        <p>Inspiration</p>
                                        <p>21</p>
                                    </a>
                                </li>
                                <li>
                                    <a href="#" class="d-flex">
                                        <p>Health Care (21)</p>
                                        <p>09</p>
                                    </a>
                                </li>
                            </ul>
                        </aside>

                        <aside class="single_sidebar_widget popular_post_widget">
                            <h3 class="widget_title">Recent Post</h3>
                            <div class="media post_item">
                                <img src="img/post/post_1.png" alt="post">
                                <div class="media-body">
                                    <a href="single-blog.html">
                                        <h3>From life was you fish...</h3>
                                    </a>
                                    <p>January 12, 2019</p>
                                </div>
                            </div>
                            <div class="media post_item">
                                <img src="img/post/post_2.png" alt="post">
                                <div class="media-body">
                                    <a href="single-blog.html">
                                        <h3>The Amazing Hubble</h3>
                                    </a>
                                    <p>02 Hours ago</p>
                                </div>
                            </div>
                            <div class="media post_item">
                                <img src="img/post/post_3.png" alt="post">
                                <div class="media-body">
                                    <a href="single-blog.html">
                                        <h3>Astronomy Or Astrology</h3>
                                    </a>
                                    <p>03 Hours ago</p>
                                </div>
                            </div>
                            <div class="media post_item">
                                <img src="img/post/post_4.png" alt="post">
                                <div class="media-body">
                                    <a href="single-blog.html">
                                        <h3>Asteroids telescope</h3>
                                    </a>
                                    <p>01 Hours ago</p>
                                </div>
                            </div>
                        </aside>
                        <aside class="single_sidebar_widget tag_cloud_widget">
                            <h4 class="widget_title">Tag Clouds</h4>
                            <ul class="list">
                                <li>
                                    <a href="#">project</a>
                                </li>
                                <li>
                                    <a href="#">love</a>
                                </li>
                                <li>
                                    <a href="#">technology</a>
                                </li>
                                <li>
                                    <a href="#">travel</a>
                                </li>
                                <li>
                                    <a href="#">restaurant</a>
                                </li>
                                <li>
                                    <a href="#">life style</a>
                                </li>
                                <li>
                                    <a href="#">design</a>
                                </li>
                                <li>
                                    <a href="#">illustration</a>
                                </li>
                            </ul>
                        </aside>


                        <aside class="single_sidebar_widget instagram_feeds">
                            <h4 class="widget_title">Instagram Feeds</h4>
                            <ul class="instagram_row flex-wrap">
                                <li>
                                    <a href="#">
                                        <img class="img-fluid" src="img/post/post_5.png" alt="">
                                    </a>
                                </li>
                                <li>
                                    <a href="#">
                                        <img class="img-fluid" src="img/post/post_6.png" alt="">
                                    </a>
                                </li>
                                <li>
                                    <a href="#">
                                        <img class="img-fluid" src="img/post/post_7.png" alt="">
                                    </a>
                                </li>
                                <li>
                                    <a href="#">
                                        <img class="img-fluid" src="img/post/post_8.png" alt="">
                                    </a>
                                </li>
                                <li>
                                    <a href="#">
                                        <img class="img-fluid" src="img/post/post_9.png" alt="">
                                    </a>
                                </li>
                                <li>
                                    <a href="#">
                                        <img class="img-fluid" src="img/post/post_10.png" alt="">
                                    </a>
                                </li>
                            </ul>
                        </aside>


                        <aside class="single_sidebar_widget newsletter_widget">
                            <h4 class="widget_title">Newsletter</h4>

                            <form action="#">
                                <div class="form-group">
                                    <input type="email" class="form-control" onfocus="this.placeholder = ''"
                                        onblur="this.placeholder = 'Enter email'" placeholder='Enter email' required>
                                </div>
                                <button class="button rounded-0 primary-bg text-white w-100 btn_1 boxed-btn"
                                    type="submit">Subscribe</button>
                            </form>
                        </aside>
                    </div>
                </div>
            </div>
        </div>
    </section>
    <!--================Blog Area =================-->

<!-- footer start -->
<footer class="footer">
    <div class="footer_top">
        <div class="container">
            <div class="row">
                <div class="col-xl-4 col-md-6 col-lg-4">
                    <div class="footer_widget">
                        <div class="footer_logo">
                            <a href="#">
                                <img src="img/footer_logo.png" alt="">
                            </a>
                        </div>
                        <p>
                                Firmament morning sixth subdue darkness 
                                creeping gathered divide.
                        </p>
                        <div class="socail_links">
                            <ul>
                                <li>
                                    <a href="#">
                                        <i class="ti-facebook"></i>
                                    </a>
                                </li>
                                <li>
                                    <a href="#">
                                        <i class="ti-twitter-alt"></i>
                                    </a>
                                </li>
                                <li>
                                    <a href="#">
                                        <i class="fa fa-instagram"></i>
                                    </a>
                                </li>
                            </ul>
                        </div>

                    </div>
                </div>
                <div class="col-xl-2 offset-xl-1 col-md-6 col-lg-3">
                    <div class="footer_widget">
                        <h3 class="footer_title">
                                Departments
                        </h3>
                        <ul>
                            <li><a href="#">Eye Care</a></li>
                            <li><a href="#">Skin Care</a></li>
                            <li><a href="#">Pathology</a></li>
                            <li><a href="#">Medicine</a></li>
                            <li><a href="#">Dental</a></li>
                        </ul>

                    </div>
                </div>
                <div class="col-xl-2 col-md-6 col-lg-2">
                    <div class="footer_widget">
                        <h3 class="footer_title">
                                Useful Links
                        </h3>
                        <ul>
                            <li><a href="#">About</a></li>
                            <li><a href="#">Blog</a></li>
                            <li><a href="#">About</a></li>
                            <li><a href="#"> Contact</a></li>
                            <li><a href="#"> Appointment</a></li>
                        </ul>
                    </div>
                </div>
                <div class="col-xl-3 col-md-6 col-lg-3">
                    <div class="footer_widget">
                        <h3 class="footer_title">
                                Address
                        </h3>
                        <p>
                            200, D-block, Green lane USA <br>
                            +10 367 467 8934 <br>
                            docmed@contact.com
                        </p>
                    </div>
                </div>
            </div>
        </div>
    </div>
    <div class="copy-right_text">
        <div class="container">
            <div class="footer_border"></div>
            <div class="row">
                <div class="col-xl-12">
                    <p class="copy_right text-center">
                        <p><!-- Link back to Colorlib can't be removed. Template is licensed under CC BY 3.0. -->
  Copyright &copy;<script>document.write(new Date().getFullYear());</script> All rights reserved | SHIVSUJAN 212223040194
                    </p>
                </div>
            </div>
        </div>
    </div>
</footer>
<!-- footer end  -->
<!-- link that opens popup -->

    <!-- form itself end-->
    <form id="test-form" class="white-popup-block mfp-hide">
        <div class="popup_box ">
            <div class="popup_inner">
                <h3>
                    Book an 
                <span>Appointment</span>
                </h3>
                <form action="#">
                    <div class="row">
                        <div class="col-xl-12">
                            <select class="form-select wide" id="default-select" class="">
                                <option data-display="Please select doctor to visit">Please select doctor to visit </option>
                                <option value="1">Anaf</option>
                                <option value="2">Nayna Therapy</option>
                                <option value="3">Nadif</option>
                            </select>
                        </div>
                        <div class="col-xl-9">
                            <input type="text"  placeholder="Your name ">
                        </div>
                        <div class="col-xl-3">
                            <input type="text"  placeholder="Your age">
                        </div>
                        <div class="col-xl-6">
                            <input type="text"  placeholder="Phone number ">
                        </div>
                        <div class="col-xl-6">
                            <input type="email"  placeholder="Email Address">
                        </div>
                        <div class="col-xl-6">
                            <input class="datepicker" placeholder="Appointment Date">
                        </div>
                        <div class="col-xl-6">
                            <input class="timepicker" placeholder="Suitable time">
                        </div>
                        <div class="col-xl-12">
                            <button type="submit" class="boxed-btn3">Make an Appointment</button>
                        </div>
                    </div>
                </form>
            </div>
        </div>
    </form>
    <!-- form itself end -->

    <!-- JS here -->
    <script src="js/vendor/modernizr-3.5.0.min.js"></script>
    <script src="js/vendor/jquery-1.12.4.min.js"></script>
    <script src="js/popper.min.js"></script>
    <script src="js/bootstrap.min.js"></script>
    <script src="js/owl.carousel.min.js"></script>
    <script src="js/isotope.pkgd.min.js"></script>
    <script src="js/ajax-form.js"></script>
    <script src="js/waypoints.min.js"></script>
    <script src="js/jquery.counterup.min.js"></script>
    <script src="js/imagesloaded.pkgd.min.js"></script>
    <script src="js/scrollIt.js"></script>
    <script src="js/jquery.scrollUp.min.js"></script>
    <script src="js/wow.min.js"></script>
    <script src="js/nice-select.min.js"></script>
    <script src="js/jquery.slicknav.min.js"></script>
    <script src="js/jquery.magnific-popup.min.js"></script>
    <script src="js/plugins.js"></script>
    <script src="js/gijgo.min.js"></script>

    <!--contact js-->
    <script src="js/contact.js"></script>
    <script src="js/jquery.ajaxchimp.min.js"></script>
    <script src="js/jquery.form.js"></script>
    <script src="js/jquery.validate.min.js"></script>
    <script src="js/mail-script.js"></script>

    <script src="js/main.js"></script>
    <script>
        $('.datepicker').datepicker({
            iconsLibrary: 'fontawesome',
            icons: {
                rightIcon: '<span class="fa fa-calendar"></span>'
            }
        });

        $('.timepicker').timepicker({
            iconsLibrary: 'fontawesome',
            icons: {
                rightIcon: '<span class="fa fa-clock-o"></span>'
            }
        });
    $(document).ready(function() {
    $('.js-example-basic-multiple').select2();
});
    </script>
</body>
</html>
```
contact.html
```
<!doctype html>
<html class="no-js" lang="zxx">

<head>
    <meta charset="utf-8">
    <meta http-equiv="x-ua-compatible" content="ie=edge">
    <title>Docmed</title>
    <meta name="description" content="">
    <meta name="viewport" content="width=device-width, initial-scale=1">

    <!-- <link rel="manifest" href="site.webmanifest"> -->
    <link rel="shortcut icon" type="image/x-icon" href="img/favicon.png">
    <!-- Place favicon.ico in the root directory -->

    <!-- CSS here -->
    <link rel="stylesheet" href="css/bootstrap.min.css">
    <link rel="stylesheet" href="css/owl.carousel.min.css">
    <link rel="stylesheet" href="css/magnific-popup.css">
    <link rel="stylesheet" href="css/font-awesome.min.css">
    <link rel="stylesheet" href="css/themify-icons.css">
    <link rel="stylesheet" href="css/nice-select.css">
    <link rel="stylesheet" href="css/flaticon.css">
    <link rel="stylesheet" href="css/gijgo.css">
    <link rel="stylesheet" href="css/animate.css">
    <link rel="stylesheet" href="css/slicknav.css">
    <link rel="stylesheet" href="css/style.css">
    <!-- <link rel="stylesheet" href="css/responsive.css"> -->
</head>

<body>
    <!--[if lte IE 9]>
            <p class="browserupgrade">You are using an <strong>outdated</strong> browser. Please <a href="https://browsehappy.com/">upgrade your browser</a> to improve your experience and security.</p>
        <![endif]-->


    <!-- header-start -->
    <header>
        <div class="header-area ">
            <div id="sticky-header" class="main-header-area">
                <div class="container">
                    <div class="row align-items-center">
                        <div class="col-xl-3 col-lg-3">
                            <div class="logo-img">
                                <a href="index.html">
                                    <img src="img/logo.png" alt="">
                                </a>
                            </div>
                        </div>
                        <div class="col-xl-9 col-lg-9">
                            <div class="menu_wrap d-none d-lg-block">
                                <div class="menu_wrap_inner d-flex align-items-center justify-content-end">
                                    <div class="main-menu">
                                        <nav>
                                            <ul id="navigation">
                                                <li><a href="index.html">home</a></li>
                                                <li><a href="about.html">About</a></li>
                                                <li><a href="#">blog <i class="ti-angle-down"></i></a>
                                                    <ul class="submenu">
                                                        <li><a href="blog.html">blog</a></li>
                                                        <li><a href="single-blog.html">single-blog</a></li>
                                                    </ul>
                                                </li>
                                                <li><a href="#">pages <i class="ti-angle-down"></i></a>
                                                    <ul class="submenu">
                                                        <li><a href="department.html">Deportment</a></li>
                                                        <li><a href="elements.html">elements</a></li>
                                                    </ul>
                                                </li>
                                                <li><a href="contact.html">Contact</a></li>
                                            </ul>
                                        </nav>
                                    </div>
                                    <div class="book_room">
                                        <div class="book_btn">
                                            <a class="popup-with-form" href="#test-form">Book  Appointment</a>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>
                        <div class="col-12">
                            <div class="mobile_menu d-block d-lg-none"></div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </header>
    <!-- header-end -->

    <!-- bradcam_area_start  -->
    <div class="bradcam_area breadcam_bg_1">
        <div class="container">
            <div class="row">
                <div class="col-xl-12">
                    <div class="bradcam_text">
                        <h3>Contact</h3>
                    </div>
                </div>
            </div>
        </div>
    </div>
    <!-- bradcam_area_end  -->

    <!-- ================ contact section start ================= -->
    <section class="contact-section">
            <div class="container">
                <div class="d-none d-sm-block mb-5 pb-4">
                    <div id="map" style="height: 480px; position: relative; overflow: hidden;"></div>
                    <script>
                        function initMap() {
                            var uluru = {
                                lat: -25.363,
                                lng: 131.044
                            };
                            var grayStyles = [{
                                    featureType: "all",
                                    stylers: [{
                                            saturation: -90
                                        },
                                        {
                                            lightness: 50
                                        }
                                    ]
                                },
                                {
                                    elementType: 'labels.text.fill',
                                    stylers: [{
                                        color: '#ccdee9'
                                    }]
                                }
                            ];
                            
                            };
                        
                    </script>
                    <script src="https://maps.googleapis.com/maps/api/js?key=AIzaSyDpfS1oRGreGSBU5HHjMmQ3o5NLw7VdJ6I&amp;callback=initMap">

                    </script>
    
                </div>
    
    
                <div class="row">
                    <div class="col-12">
                        <h2 class="contact-title">Get in Touch</h2>
                    </div>
                    <div class="col-lg-8">
                        <form class="form-contact contact_form" action="contact_process.php" method="post" id="contactForm" novalidate="novalidate">
                            <div class="row">
                                <div class="col-12">
                                    <div class="form-group">
                                        <textarea class="form-control w-100" name="message" id="message" cols="30" rows="9" onfocus="this.placeholder = ''" onblur="this.placeholder = 'Enter Message'" placeholder=" Name"></textarea>
                                    </div>
                                </div>
                                <div class="col-sm-6">
                                    <div class="form-group">
                                        <input class="form-control valid" name="name" id="name" type="text" onfocus="this.placeholder = ''" onblur="this.placeholder = 'Enter your name'" placeholder="Enter your name">
                                    </div>
                                </div>
                                <div class="col-sm-6">
                                    <div class="form-group">
                                        <input class="form-control valid" name="email" id="email" type="email" onfocus="this.placeholder = ''" onblur="this.placeholder = 'Enter email address'" placeholder="Email">
                                    </div>
                                </div>
                                <div class="col-12">
                                    <div class="form-group">
                                        <input class="form-control" name="subject" id="subject" type="text" onfocus="this.placeholder = ''" onblur="this.placeholder = 'Enter Subject'" placeholder="Enter Subject">
                                    </div>
                                </div>
                            </div>
                            <div class="form-group mt-3">
                                <button type="submit" class="button button-contactForm boxed-btn">Send</button>
                            </div>
                        </form>
                    </div>
                    <div class="col-lg-3 offset-lg-1">
                        <div class="media contact-info">
                            <span class="contact-info__icon"><i class="ti-home"></i></span>
                            <div class="media-body">
                                <h3>Buttonwood, California.</h3>
                                <p>Rosemead, CA 91770</p>
                            </div>
                        </div>
                        <div class="media contact-info">
                            <span class="contact-info__icon"><i class="ti-tablet"></i></span>
                            <div class="media-body">
                                <h3>8547255552</h3>
                                <p>Mon to Fri 9am to 6pm</p>
                            </div>
                        </div>
                        <div class="media contact-info">
                            <span class="contact-info__icon"><i class="ti-email"></i></span>
                            <div class="media-body">
                                <h3>support@shivsujan.com</h3>
                                <p>Send us your query anytime!</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>
    <!-- ================ contact section end ================= -->
    

    <footer class="footer">
        <div class="footer_top">
            <div class="container">
                <div class="row">
                    <div class="col-xl-4 col-md-6 col-lg-4 ">
                        <div class="footer_widget">
                            <div class="footer_logo">
                                <a href="#">
                                    <img src="img/logo.png" alt="">
                                </a>
                            </div>
                            <p class="address_text">Lorem ipsum dolor sit amet, <br> consectetur adipiscing elit, sed do <br> eiusmod tempor incididunt ut labore.
                            </p>
                            <div class="socail_links">
                                <ul>
                                    <li>
                                        <a href="#">
                                            <i class="ti-facebook"></i>
                                        </a>
                                    </li>
                                    <li>
                                        <a href="#">
                                            <i class="ti-twitter-alt"></i>
                                        </a>
                                    </li>
                                    <li>
                                        <a href="#">
                                            <i class="fa fa-dribbble"></i>
                                        </a>
                                    </li>
                                    <li>
                                        <a href="#">
                                            <i class="fa fa-instagram"></i>
                                        </a>
                                    </li>
                                </ul>
                            </div>

                        </div>
                    </div>
                    <div class="col-xl-4 col-md-6 col-lg-4">
                        <div class="footer_widget">
                            <h3 class="footer_title">
                                Our Departments
                            </h3>
                            <ul class="links">
                                <li><a href="#">Births</a></li>
                                <li><a href="#">Pulmonary</a></li>
                                <li><a href="#">Cardiology</a></li>
                                <li><a href="#">Neurology</a></li>
                                <li><a href="#">Traumatology</a></li>
                                <li><a href="#">Dental</a></li>
                                <li><a href="#">Nuclear</a></li>
                                <li><a href="#">magnetic</a></li>
                                <li><a href="#">Pregnancy</a></li>
                                <li><a href="#">For disabled</a></li>
                                <li><a href="#">X-ray</a></li>
                                <li><a href="#">Prostheses</a></li>
                            </ul>
                        </div>
                    </div>
                    <div class="col-xl-4  col-md-6 col-lg-4">
                        <div class="footer_widget">
                            <h3 class="footer_title">
                                We’re Available
                            </h3>
                            <ul class="meting_time">
                                <li class="d-flex justify-content-between "><span>Monday - Friday</span> <span>8.00 - 18.00</span></li>
                                <li class="d-flex justify-content-between "><span>Saturday	</span> <span>8.00 - 18.00</span></li>
                                <li class="d-flex justify-content-between "><span>Sunday</span> <span>8.00 - 13.00</span></li>
                            </ul>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <div class="copy-right_text">
            <div class="container">
                <div class="row">
                    <div class="bordered_1px "></div>
                    <div class="col-xl-12">
                        <p class="copy_right text-center">
                            <p>
  Copyright &copy;<script>document.write(new Date().getFullYear());</script> All rights reserved | SHIVSUJAN S R (212223040194)
                        </p>
                    </div>
                </div>
            </div>
        </div>
    </footer>

    <!-- link that opens popup -->

    <!-- form itself end-->
    <form id="test-form" class="white-popup-block mfp-hide">
        <div class="popup_box ">
            <div class="popup_inner">
                <h3>
                    Book an 
                <span>Appointment</span>
                </h3>
                <form action="#">
                    <div class="row">
                        <div class="col-xl-12">
                            <select class="form-select wide" id="default-select" class="">
                                <option data-display="Please select doctor to visit">Please select doctor to visit </option>
                                <option value="1">Anaf</option>
                                <option value="2">Nayna Therapy</option>
                                <option value="3">Nadif</option>
                            </select>
                        </div>
                        <div class="col-xl-9">
                            <input type="text"  placeholder="Your name ">
                        </div>
                        <div class="col-xl-3">
                            <input type="text"  placeholder="Your age">
                        </div>
                        <div class="col-xl-6">
                            <input type="text"  placeholder="Phone number ">
                        </div>
                        <div class="col-xl-6">
                            <input type="email"  placeholder="Email Address">
                        </div>
                        <div class="col-xl-6">
                            <input class="datepicker" placeholder="Appointment Date">
                        </div>
                        <div class="col-xl-6">
                            <input class="timepicker" placeholder="Suitable time">
                        </div>
                        <div class="col-xl-12">
                            <button type="submit" class="boxed-btn3">Make an Appointment</button>
                        </div>
                    </div>
                </form>
            </div>
        </div>
    </form>
    <!-- form itself end -->
    
        <!-- JS here -->
        <script src="js/vendor/modernizr-3.5.0.min.js"></script>
        <script src="js/vendor/jquery-1.12.4.min.js"></script>
        <script src="js/popper.min.js"></script>
        <script src="js/bootstrap.min.js"></script>
        <script src="js/owl.carousel.min.js"></script>
        <script src="js/isotope.pkgd.min.js"></script>
        <script src="js/ajax-form.js"></script>
        <script src="js/waypoints.min.js"></script>
        <script src="js/jquery.counterup.min.js"></script>
        <script src="js/imagesloaded.pkgd.min.js"></script>
        <script src="js/scrollIt.js"></script>
        <script src="js/jquery.scrollUp.min.js"></script>
        <script src="js/wow.min.js"></script>
        <script src="js/nice-select.min.js"></script>
        <script src="js/jquery.slicknav.min.js"></script>
        <script src="js/jquery.magnific-popup.min.js"></script>
        <script src="js/plugins.js"></script>
        <script src="js/gijgo.min.js"></script>
    
        <!--contact js-->
        <script src="js/contact.js"></script>
        <script src="js/jquery.ajaxchimp.min.js"></script>
        <script src="js/jquery.form.js"></script>
        <script src="js/jquery.validate.min.js"></script>
        <script src="js/mail-script.js"></script>
    
        <script src="js/main.js"></script>
        <script>
            $('#datepicker').datepicker({
                iconsLibrary: 'fontawesome',
                icons: {
                 rightIcon: '<span class="fa fa-caret-down"></span>'
             }
            });
            $('#datepicker2').datepicker({
                iconsLibrary: 'fontawesome',
                icons: {
                 rightIcon: '<span class="fa fa-caret-down"></span>'
             }
    
            });
        </script>
    </body>
    
    </html>
```
department.html
```
<!doctype html>
<html class="no-js" lang="zxx">

<head>
    <meta charset="utf-8">
    <meta http-equiv="x-ua-compatible" content="ie=edge">
    <title>Medi</title>
    <meta name="description" content="">
    <meta name="viewport" content="width=device-width, initial-scale=1">

    <!-- <link rel="manifest" href="site.webmanifest"> -->
    <link rel="shortcut icon" type="image/x-icon" href="img/favicon.png">
    <!-- Place favicon.ico in the root directory -->

    <!-- CSS here -->
    <link rel="stylesheet" href="css/bootstrap.min.css">
    <link rel="stylesheet" href="css/owl.carousel.min.css">
    <link rel="stylesheet" href="css/magnific-popup.css">
    <link rel="stylesheet" href="css/font-awesome.min.css">
    <link rel="stylesheet" href="css/themify-icons.css">
    <link rel="stylesheet" href="css/nice-select.css">
    <link rel="stylesheet" href="css/flaticon.css">
    <link rel="stylesheet" href="css/gijgo.css">
    <link rel="stylesheet" href="css/animate.css">
    <link rel="stylesheet" href="css/slicknav.css">
    <link rel="stylesheet" href="css/style.css">
</head>

<body>
    <!--[if lte IE 9]>
            <p class="browserupgrade">You are using an <strong>outdated</strong> browser. Please <a href="https://browsehappy.com/">upgrade your browser</a> to improve your experience and security.</p>
        <![endif]-->


    <!-- header-start -->
    <header>
        <div class="header-area ">
            <div id="sticky-header" class="main-header-area">
                <div class="container">
                    <div class="row align-items-center">
                        <div class="col-xl-3 col-lg-3">
                            <div class="logo-img">
                                <a href="index.html">
                                    <img src="img/logo.png" alt="">
                                </a>
                            </div>
                        </div>
                        <div class="col-xl-9 col-lg-9">
                            <div class="menu_wrap d-none d-lg-block">
                                <div class="menu_wrap_inner d-flex align-items-center justify-content-end">
                                    <div class="main-menu">
                                        <nav>
                                            <ul id="navigation">
                                                <li><a href="index.html">home</a></li>
                                                <li><a href="about.html">About</a></li>
                                                <li><a href="#">blog <i class="ti-angle-down"></i></a>
                                                    <ul class="submenu">
                                                        <li><a href="blog.html">blog</a></li>
                                                        <li><a href="single-blog.html">single-blog</a></li>
                                                    </ul>
                                                </li>
                                                <li><a href="#">pages <i class="ti-angle-down"></i></a>
                                                    <ul class="submenu">
                                                        <li><a href="department.html">Deportment</a></li>
                                                        <li><a href="elements.html">elements</a></li>
                                                    </ul>
                                                </li>
                                                <li><a href="contact.html">Contact</a></li>
                                            </ul>
                                        </nav>
                                    </div>
                                    <div class="book_room">
                                        <div class="book_btn">
                                            <a class="popup-with-form" href="#test-form">Book  Appointment</a>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>
                        <div class="col-12">
                            <div class="mobile_menu d-block d-lg-none"></div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </header>
    <!-- header-end -->

    <!-- bradcam_area_start  -->
    <div class="bradcam_area breadcam_bg_1">
        <div class="container">
            <div class="row">
                <div class="col-xl-12">
                    <div class="bradcam_text">
                        <h3>Departments</h3>
                    </div>
                </div>
            </div>
        </div>
    </div>
    <!-- bradcam_area_end  -->

    <!-- depertment_area_start  -->
    <div class="depertment_area">
        <div class="container">
            <div class="row custom_align align-items-end justify-content-between">
                <div class="col-lg-6">
                    <div class="section_title">
                        <h3>Departments</h3>
                        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore.</p>
                    </div>
                </div>
                <div class="col-lg-6">
                    <div class="learn_more_btn text-right">
                        <a href="#" class="boxed-btn">Learn more</a>
                    </div>
                </div>
            </div>
            <div class="row">
                <div class="col-lg-12">
                    <div class="depart_ment_tab mb-30">
                        <ul class="nav" id="myTab" role="tablist">
                            <li class="nav-item">
                                <a class="nav-link active" id="home-tab" data-toggle="tab" href="#home" role="tab" aria-controls="home" aria-selected="true">
                                    <i class="flaticon-teeth"></i>
                                    <h4>Dentistry</h4>
                                </a>
                            </li>
                            <li class="nav-item">
                                <a class="nav-link" id="profile-tab" data-toggle="tab" href="#profile" role="tab" aria-controls="profile" aria-selected="false">
                                    <i class="flaticon-cardiovascular"></i>
                                    <h4>Cardiology</h4>
                                </a>
                            </li>
                            <li class="nav-item">
                                <a class="nav-link" id="contact-tab" data-toggle="tab" href="#contact" role="tab" aria-controls="contact" aria-selected="false">
                                    <i class="flaticon-ear"></i>
                                    <h4>ENT Specialists</h4>
                                </a>
                            </li>
                            <li class="nav-item">
                                <a class="nav-link" id="Astrology-tab" data-toggle="tab" href="#Astrology" role="tab" aria-controls="contact" aria-selected="false">
                                    <i class="flaticon-bone"></i>
                                    <h4>Astrology</h4>
                                </a>
                            </li>
                            <li class="nav-item">
                                <a class="nav-link" id="Neuroanatomy-tab" data-toggle="tab" href="#Neuroanatomy" role="tab" aria-controls="contact" aria-selected="false">
                                    <i class="flaticon-lung"></i>
                                    <h4>Neuroanatomy</h4>
                                </a>
                            </li>
                            <li class="nav-item">
                                <a class="nav-link" id="Blood-tab" data-toggle="tab" href="#Blood" role="tab" aria-controls="contact" aria-selected="false">
                                    <i class="flaticon-cell"></i>
                                    <h4>Blood Screening</h4>
                                </a>
                            </li>
                        </ul>
                    </div>
                </div>
            </div>
            <div class="dept_main_info white-bg">
                <div class="tab-content" id="myTabContent">
                    <div class="tab-pane fade show active" id="home" role="tabpanel" aria-labelledby="home-tab">
                        <!-- single_content  -->
                        <div class="row align-items-center">
                            <div class="col-lg-5">
                                <div class="dept_thumb">
                                    <img src="img/department/1.jpg" alt="">
                                </div>
                            </div>
                            <div class="col-lg-7">
                                <div class="dept_info">
                                    <h3>Dentist with surgical mask holding <br> scaler near patient</h3 >
                                    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Quis ipsum suspendisse ultrices gravida. Risus commodo viverra maecenas accumsan lacus vel facilisis. </p>
                                    <a href="#" class="boxed-btn">Make An Appointment</a>
                                </div>
                            </div>
                        </div>
                        <!-- single_content  -->
                    </div>
                    <div class="tab-pane fade" id="profile" role="tabpanel" aria-labelledby="profile-tab">
                        <!-- single_content  -->
                        <div class="row align-items-center">
                            <div class="col-lg-5">
                                <div class="dept_thumb">
                                    <img src="img/department/1.jpg" alt="">
                                </div>
                            </div>
                            <div class="col-lg-7">
                                <div class="dept_info">
                                    <h3>Dentist with surgical mask holding <br> scaler near patient</h3 >
                                    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Quis ipsum suspendisse ultrices gravida. Risus commodo viverra maecenas accumsan lacus vel facilisis. </p>
                                    <a href="#" class="boxed-btn">Make An Appointment</a>
                                </div>
                            </div>
                        </div>
                        <!-- single_content  -->
                    </div>
                    <div class="tab-pane fade" id="contact" role="tabpanel" aria-labelledby="contact-tab">
                    <!-- single_content  -->
                    <div class="row align-items-center">
                        <div class="col-lg-5">
                            <div class="dept_thumb">
                                <img src="img/department/1.jpg" alt="">
                            </div>
                        </div>
                        <div class="col-lg-7">
                            <div class="dept_info">
                                <h3>Dentist with surgical mask holding <br> scaler near patient</h3 >
                                <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Quis ipsum suspendisse ultrices gravida. Risus commodo viverra maecenas accumsan lacus vel facilisis. </p>
                                <a href="#" class="boxed-btn">Make An Appointment</a>
                            </div>
                        </div>
                    </div>
                    <!-- single_content  -->
                    </div>
                    <div class="tab-pane fade" id="Astrology" role="tabpanel" aria-labelledby="Astrology-tab">
                        <!-- single_content  -->
                        <div class="row align-items-center">
                            <div class="col-lg-5">
                                <div class="dept_thumb">
                                    <img src="img/department/1.jpg" alt="">
                                </div>
                            </div>
                            <div class="col-lg-7">
                                <div class="dept_info">
                                    <h3>Dentist with surgical mask holding <br> scaler near patient</h3 >
                                    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Quis ipsum suspendisse ultrices gravida. Risus commodo viverra maecenas accumsan lacus vel facilisis. </p>
                                    <a href="#" class="boxed-btn">Make An Appointment</a>
                                </div>
                            </div>
                        </div>
                        <!-- single_content  -->
                    </div>
                    <div class="tab-pane fade" id="Neuroanatomy" role="tabpanel" aria-labelledby="Neuroanatomy-tab">
                        <!-- single_content  -->
                        <div class="row align-items-center">
                            <div class="col-lg-5">
                                <div class="dept_thumb">
                                    <img src="img/department/1.jpg" alt="">
                                </div>
                            </div>
                            <div class="col-lg-7">
                                <div class="dept_info">
                                    <h3>Dentist with surgical mask holding <br> scaler near patient</h3 >
                                    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Quis ipsum suspendisse ultrices gravida. Risus commodo viverra maecenas accumsan lacus vel facilisis. </p>
                                    <a href="#" class="boxed-btn">Make An Appointment</a>
                                </div>
                            </div>
                        </div>
                        <!-- single_content  -->
                    </div>
                    <div class="tab-pane fade" id="Blood" role="tabpanel" aria-labelledby="Blood-tab">
                    <!-- single_content  -->
                    <div class="row align-items-center">
                        <div class="col-lg-5">
                            <div class="dept_thumb">
                                <img src="img/department/1.jpg" alt="">
                            </div>
                        </div>
                        <div class="col-lg-7">
                            <div class="dept_info">
                                <h3>Dentist with surgical mask holding <br> scaler near patient</h3 >
                                <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Quis ipsum suspendisse ultrices gravida. Risus commodo viverra maecenas accumsan lacus vel facilisis. </p>
                                <a href="#" class="boxed-btn">Make An Appointment</a>
                            </div>
                        </div>
                    </div>
                    <!-- single_content  -->
                    </div>
                  </div>
            </div>

        </div>
    </div>
    <!-- depertment_area_end  -->

    <!-- quality_area_start  -->
    <div class="quality_area">
        <div class="container">
            <div class="row justify-content-center ">
                <div class="col-lg-6">
                    <div class="section_title mb-55 text-center">
                        <h3>Quality Health</h3>
                        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore.</p>
                    </div>
                </div>
            </div>
            <div class="row">
                <div class="col-lg-4 col-md-6">
                    <div class="single_quality">
                        <div class="icon">
                            <i class="flaticon-customer-service"></i>
                        </div>
                        <h3>Health Consultation</h3>
                        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt.</p>
                    </div>
                </div>
                <div class="col-lg-4 col-md-6">
                    <div class="single_quality">
                        <div class="icon">
                            <i class="flaticon-find"></i>
                        </div>
                        <h3>Find Health</h3>
                        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt.</p>
                    </div>
                </div>
                <div class="col-lg-4 col-md-6">
                    <div class="single_quality">
                        <div class="icon">
                            <i class="flaticon-doctor"></i>
                        </div>
                        <h3>Search Deoctor</h3>
                        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt.</p>
                    </div>
                </div>
            </div>
        </div>
    </div>
    <!-- quality_areaend  -->

    <!-- Emergency_contact start -->
    <div class="Emergency_contact">
        <div class="Emergency_contact_inner ">
            <div class="container">
                <div class="row align-items-center">
                    <div class="col-lg-6">
                        <div class="single_emergency">
                            <div class="info">
                                <span>We are here for you</span>
                                <h3>Book Appointment</h3>
                            </div>
                            <div class="info_button">
                                <a href="#" class="boxed-btn3-white">Book Appointment
                                </a>
                            </div>
                        </div>
                    </div>
                    <div class="col-lg-6">
                        <div class="single_emergency align-items-center d-flex justify-content-end">
                            <div class="icon">
                                <i class="flaticon-call"></i>
                            </div>
                            <div class="info">
                                <span>Emergency Medical Care</span>
                                <h3>+1-465 4545</h3>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
    <!-- Emergency_contact end -->

    <footer class="footer">
        <div class="footer_top">
            <div class="container">
                <div class="row">
                    <div class="col-xl-4 col-md-6 col-lg-4 ">
                        <div class="footer_widget">
                            <div class="footer_logo">
                                <a href="#">
                                    <img src="img/logo.png" alt="">
                                </a>
                            </div>
                            <p class="address_text">Lorem ipsum dolor sit amet, <br> consectetur adipiscing elit, sed do <br> eiusmod tempor incididunt ut labore.
                            </p>
                            <div class="socail_links">
                                <ul>
                                    <li>
                                        <a href="#">
                                            <i class="ti-facebook"></i>
                                        </a>
                                    </li>
                                    <li>
                                        <a href="#">
                                            <i class="ti-twitter-alt"></i>
                                        </a>
                                    </li>
                                    <li>
                                        <a href="#">
                                            <i class="fa fa-dribbble"></i>
                                        </a>
                                    </li>
                                    <li>
                                        <a href="#">
                                            <i class="fa fa-instagram"></i>
                                        </a>
                                    </li>
                                </ul>
                            </div>

                        </div>
                    </div>
                    <div class="col-xl-4 col-md-6 col-lg-4">
                        <div class="footer_widget">
                            <h3 class="footer_title">
                                Our Departments
                            </h3>
                            <ul class="links">
                                <li><a href="#">Births</a></li>
                                <li><a href="#">Pulmonary</a></li>
                                <li><a href="#">Cardiology</a></li>
                                <li><a href="#">Neurology</a></li>
                                <li><a href="#">Traumatology</a></li>
                                <li><a href="#">Dental</a></li>
                                <li><a href="#">Nuclear</a></li>
                                <li><a href="#">magnetic</a></li>
                                <li><a href="#">Pregnancy</a></li>
                                <li><a href="#">For disabled</a></li>
                                <li><a href="#">X-ray</a></li>
                                <li><a href="#">Prostheses</a></li>
                            </ul>
                        </div>
                    </div>
                    <div class="col-xl-4  col-md-6 col-lg-4">
                        <div class="footer_widget">
                            <h3 class="footer_title">
                                We’re Available
                            </h3>
                            <ul class="meting_time">
                                <li class="d-flex justify-content-between "><span>Monday - Friday</span> <span>8.00 - 18.00</span></li>
                                <li class="d-flex justify-content-between "><span>Saturday	</span> <span>8.00 - 18.00</span></li>
                                <li class="d-flex justify-content-between "><span>Sunday</span> <span>8.00 - 13.00</span></li>
                            </ul>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <div class="copy-right_text">
            <div class="container">
                <div class="row">
                    <div class="bordered_1px "></div>
                    <div class="col-xl-12">
                        <p class="copy_right text-center">
                            <p><!-- Link back to Colorlib can't be removed. Template is licensed under CC BY 3.0. -->
  Copyright &copy;<script>document.write(new Date().getFullYear());</script> All rights reserved | SHIVSUJAN S R (212223040194)
                        </p>
                    </div>
                </div>
            </div>
        </div>
    </footer>

    <!-- link that opens popup -->

    <!-- form itself end-->
    <form id="test-form" class="white-popup-block mfp-hide">
        <div class="popup_box ">
            <div class="popup_inner">
                <h3>
                    Book an 
                <span>Appointment</span>
                </h3>
                <form action="#">
                    <div class="row">
                        <div class="col-xl-12">
                            <select class="form-select wide" id="default-select" class="">
                                <option data-display="Please select doctor to visit">Please select doctor to visit </option>
                                <option value="1">Anaf</option>
                                <option value="2">Nayna Therapy</option>
                                <option value="3">Nadif</option>
                            </select>
                        </div>
                        <div class="col-xl-9">
                            <input type="text"  placeholder="Your name ">
                        </div>
                        <div class="col-xl-3">
                            <input type="text"  placeholder="Your age">
                        </div>
                        <div class="col-xl-6">
                            <input type="text"  placeholder="Phone number ">
                        </div>
                        <div class="col-xl-6">
                            <input type="email"  placeholder="Email Address">
                        </div>
                        <div class="col-xl-6">
                            <input class="datepicker" placeholder="Appointment Date">
                        </div>
                        <div class="col-xl-6">
                            <input class="timepicker" placeholder="Suitable time">
                        </div>
                        <div class="col-xl-12">
                            <button type="submit" class="boxed-btn3">Make an Appointment</button>
                        </div>
                    </div>
                </form>
            </div>
        </div>
    </form>
    <!-- form itself end -->

    <!-- JS here -->
    <script src="js/vendor/modernizr-3.5.0.min.js"></script>
    <script src="js/vendor/jquery-1.12.4.min.js"></script>
    <script src="js/popper.min.js"></script>
    <script src="js/bootstrap.min.js"></script>
    <script src="js/owl.carousel.min.js"></script>
    <script src="js/isotope.pkgd.min.js"></script>
    <script src="js/ajax-form.js"></script>
    <script src="js/waypoints.min.js"></script>
    <script src="js/jquery.counterup.min.js"></script>
    <script src="js/imagesloaded.pkgd.min.js"></script>
    <script src="js/scrollIt.js"></script>
    <script src="js/jquery.scrollUp.min.js"></script>
    <script src="js/wow.min.js"></script>
    <script src="js/nice-select.min.js"></script>
    <script src="js/jquery.slicknav.min.js"></script>
    <script src="js/jquery.magnific-popup.min.js"></script>
    <script src="js/plugins.js"></script>
    <script src="js/gijgo.min.js"></script>
    <!--contact js-->
    <script src="js/contact.js"></script>
    <script src="js/jquery.ajaxchimp.min.js"></script>
    <script src="js/jquery.form.js"></script>
    <script src="js/jquery.validate.min.js"></script>
    <script src="js/mail-script.js"></script>

    <script src="js/main.js"></script>
    <script>
        $('.datepicker').datepicker({
            iconsLibrary: 'fontawesome',
            icons: {
                rightIcon: '<span class="fa fa-calendar"></span>'
            }
        });

        $('.timepicker').timepicker({
            iconsLibrary: 'fontawesome',
            icons: {
                rightIcon: '<span class="fa fa-clock-o"></span>'
            }
        });
    $(document).ready(function() {
    $('.js-example-basic-multiple').select2();
});
    </script>
</body>

</html>
```
elements.html
```
<!doctype html>
<html class="no-js" lang="zxx">

<head>
	<meta charset="utf-8">
	<meta http-equiv="x-ua-compatible" content="ie=edge">
	<title>Docmed</title>
	<meta name="description" content="">
	<meta name="viewport" content="width=device-width, initial-scale=1">

	<!-- <link rel="manifest" href="site.webmanifest"> -->
	<link rel="shortcut icon" type="image/x-icon" href="img/favicon.png">
	<!-- Place favicon.ico in the root directory -->

	<!-- CSS here -->
	<link rel="stylesheet" href="css/bootstrap.min.css">
	<link rel="stylesheet" href="css/owl.carousel.min.css">
	<link rel="stylesheet" href="css/magnific-popup.css">
	<link rel="stylesheet" href="css/font-awesome.min.css">
	<link rel="stylesheet" href="css/themify-icons.css">
	<link rel="stylesheet" href="css/nice-select.css">
	<link rel="stylesheet" href="css/flaticon.css">
	<link rel="stylesheet" href="css/gijgo.css">
	<link rel="stylesheet" href="css/animate.css">
	<link rel="stylesheet" href="css/slicknav.css">
	<link rel="stylesheet" href="css/style.css">
	<!-- <link rel="stylesheet" href="css/responsive.css"> -->
</head>

<body>
	<!--[if lte IE 9]>
            <p class="browserupgrade">You are using an <strong>outdated</strong> browser. Please <a href="https://browsehappy.com/">upgrade your browser</a> to improve your experience and security.</p>
        <![endif]-->

    <!-- header-start -->
    <header>
        <div class="header-area ">
            <div id="sticky-header" class="main-header-area">
                <div class="container">
                    <div class="row align-items-center">
                        <div class="col-xl-3 col-lg-3">
                            <div class="logo-img">
                                <a href="index.html">
                                    <img src="img/logo.png" alt="">
                                </a>
                            </div>
                        </div>
                        <div class="col-xl-9 col-lg-9">
                            <div class="menu_wrap d-none d-lg-block">
                                <div class="menu_wrap_inner d-flex align-items-center justify-content-end">
                                    <div class="main-menu">
                                        <nav>
                                            <ul id="navigation">
                                                <li><a href="index.html">home</a></li>
                                                <li><a href="about.html">About</a></li>
                                                <li><a href="#">blog <i class="ti-angle-down"></i></a>
                                                    <ul class="submenu">
                                                        <li><a href="blog.html">blog</a></li>
                                                        <li><a href="single-blog.html">single-blog</a></li>
                                                    </ul>
                                                </li>
                                                <li><a href="#">pages <i class="ti-angle-down"></i></a>
                                                    <ul class="submenu">
                                                        <li><a href="Department.html">Deportment</a></li>
                                                        <li><a href="elements.html">elements</a></li>
                                                    </ul>
                                                </li>
                                                <li><a href="contact.html">Contact</a></li>
                                            </ul>
                                        </nav>
                                    </div>
                                    <div class="book_room">
                                        <div class="book_btn">
                                            <a class="popup-with-form" href="#test-form">Book  Appointment</a>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>
                        <div class="col-12">
                            <div class="mobile_menu d-block d-lg-none"></div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </header>
    <!-- header-end -->

    <!-- bradcam_area_start  -->
    <div class="bradcam_area breadcam_bg_1">
        <div class="container">
            <div class="row">
                <div class="col-xl-12">
                    <div class="bradcam_text">
                        <h3>Elements</h3>
                    </div>
                </div>
            </div>
        </div>
    </div>
    <!-- bradcam_area_end  -->

	<!-- Start Sample Area -->
	<section class="sample-text-area">
		<div class="container box_1170">
			<h3 class="text-heading">Text Sample</h3>
			<p class="sample-text">
				Every avid independent filmmaker has <b>Bold</b> about making that <i>Italic</i> interest documentary,
				or short
				film to show off their creative prowess. Many have great ideas and want to “wow”
				the<sup>Superscript</sup> scene,
				or video renters with their big project. But once you have the<sub>Subscript</sub> “in the can” (no easy
				feat), how
				do you move from a <del>Strike</del> through of master DVDs with the <u>“Underline”</u> marked
				hand-written title
				inside a secondhand CD case, to a pile of cardboard boxes full of shiny new, retail-ready DVDs, with UPC
				barcodes
				and polywrap sitting on your doorstep? You need to create eye-popping artwork and have your project
				replicated.
				Using a reputable full service DVD Replication company like PacificDisc, Inc. to partner with is
				certainly a
				helpful option to ensure a professional end result, but to help with your DVD replication project, here
				are 4 easy
				steps to follow for good DVD replication results:

			</p>
		</div>
	</section>
	<!-- End Sample Area -->

	<!-- Start Button -->
	<section class="button-area">
		<div class="container box_1170 border-top-generic">
			<h3 class="text-heading">Sample Buttons</h3>
			<div class="button-group-area">
				<a href="#" class="genric-btn default">Default</a>
				<a href="#" class="genric-btn primary">Primary</a>
				<a href="#" class="genric-btn success">Success</a>
				<a href="#" class="genric-btn info">Info</a>
				<a href="#" class="genric-btn warning">Warning</a>
				<a href="#" class="genric-btn danger">Danger</a>
				<a href="#" class="genric-btn link">Link</a>
				<a href="#" class="genric-btn disable">Disable</a>
			</div>
			<div class="button-group-area mt-10">
				<a href="#" class="genric-btn default-border">Default</a>
				<a href="#" class="genric-btn primary-border">Primary</a>
				<a href="#" class="genric-btn success-border">Success</a>
				<a href="#" class="genric-btn info-border">Info</a>
				<a href="#" class="genric-btn warning-border">Warning</a>
				<a href="#" class="genric-btn danger-border">Danger</a>
				<a href="#" class="genric-btn link-border">Link</a>
				<a href="#" class="genric-btn disable">Disable</a>
			</div>
			<div class="button-group-area mt-40">
				<a href="#" class="genric-btn default radius">Default</a>
				<a href="#" class="genric-btn primary radius">Primary</a>
				<a href="#" class="genric-btn success radius">Success</a>
				<a href="#" class="genric-btn info radius">Info</a>
				<a href="#" class="genric-btn warning radius">Warning</a>
				<a href="#" class="genric-btn danger radius">Danger</a>
				<a href="#" class="genric-btn link radius">Link</a>
				<a href="#" class="genric-btn disable radius">Disable</a>
			</div>
			<div class="button-group-area mt-10">
				<a href="#" class="genric-btn default-border radius">Default</a>
				<a href="#" class="genric-btn primary-border radius">Primary</a>
				<a href="#" class="genric-btn success-border radius">Success</a>
				<a href="#" class="genric-btn info-border radius">Info</a>
				<a href="#" class="genric-btn warning-border radius">Warning</a>
				<a href="#" class="genric-btn danger-border radius">Danger</a>
				<a href="#" class="genric-btn link-border radius">Link</a>
				<a href="#" class="genric-btn disable radius">Disable</a>
			</div>
			<div class="button-group-area mt-40">
				<a href="#" class="genric-btn default circle">Default</a>
				<a href="#" class="genric-btn primary circle">Primary</a>
				<a href="#" class="genric-btn success circle">Success</a>
				<a href="#" class="genric-btn info circle">Info</a>
				<a href="#" class="genric-btn warning circle">Warning</a>
				<a href="#" class="genric-btn danger circle">Danger</a>
				<a href="#" class="genric-btn link circle">Link</a>
				<a href="#" class="genric-btn disable circle">Disable</a>
			</div>
			<div class="button-group-area mt-10">
				<a href="#" class="genric-btn default-border circle">Default</a>
				<a href="#" class="genric-btn primary-border circle">Primary</a>
				<a href="#" class="genric-btn success-border circle">Success</a>
				<a href="#" class="genric-btn info-border circle">Info</a>
				<a href="#" class="genric-btn warning-border circle">Warning</a>
				<a href="#" class="genric-btn danger-border circle">Danger</a>
				<a href="#" class="genric-btn link-border circle">Link</a>
				<a href="#" class="genric-btn disable circle">Disable</a>
			</div>
			<div class="button-group-area mt-40">
				<a href="#" class="genric-btn default circle arrow">Default<span class="lnr lnr-arrow-right"></span></a>
				<a href="#" class="genric-btn primary circle arrow">Primary<span class="lnr lnr-arrow-right"></span></a>
				<a href="#" class="genric-btn success circle arrow">Success<span class="lnr lnr-arrow-right"></span></a>
				<a href="#" class="genric-btn info circle arrow">Info<span class="lnr lnr-arrow-right"></span></a>
				<a href="#" class="genric-btn warning circle arrow">Warning<span class="lnr lnr-arrow-right"></span></a>
				<a href="#" class="genric-btn danger circle arrow">Danger<span class="lnr lnr-arrow-right"></span></a>
			</div>
			<div class="button-group-area mt-10">
				<a href="#" class="genric-btn default-border circle arrow">Default<span
						class="lnr lnr-arrow-right"></span></a>
				<a href="#" class="genric-btn primary-border circle arrow">Primary<span
						class="lnr lnr-arrow-right"></span></a>
				<a href="#" class="genric-btn success-border circle arrow">Success<span
						class="lnr lnr-arrow-right"></span></a>
				<a href="#" class="genric-btn info-border circle arrow">Info<span
						class="lnr lnr-arrow-right"></span></a>
				<a href="#" class="genric-btn warning-border circle arrow">Warning<span
						class="lnr lnr-arrow-right"></span></a>
				<a href="#" class="genric-btn danger-border circle arrow">Danger<span
						class="lnr lnr-arrow-right"></span></a>
			</div>
			<div class="button-group-area mt-40">
				<a href="#" class="genric-btn primary e-large">Extra Large</a>
				<a href="#" class="genric-btn success large">Large</a>
				<a href="#" class="genric-btn primary">Default</a>
				<a href="#" class="genric-btn success medium">Medium</a>
				<a href="#" class="genric-btn primary small">Small</a>
			</div>
			<div class="button-group-area mt-10">
				<a href="#" class="genric-btn primary-border e-large">Extra Large</a>
				<a href="#" class="genric-btn success-border large">Large</a>
				<a href="#" class="genric-btn primary-border">Default</a>
				<a href="#" class="genric-btn success-border medium">Medium</a>
				<a href="#" class="genric-btn primary-border small">Small</a>
			</div>
		</div>
	</section>
	<!-- End Button -->

	<!-- Start Align Area -->
	<div class="whole-wrap">
		<div class="container box_1170">
			<div class="section-top-border">
				<h3 class="mb-30">Left Aligned</h3>
				<div class="row">
					<div class="col-md-3">
						<img src="img/elements/d.jpg" alt="" class="img-fluid">
					</div>
					<div class="col-md-9 mt-sm-20">
						<p>Recently, the US Federal government banned online casinos from operating in America by making
							it illegal to
							transfer money to them through any US bank or payment system. As a result of this law, most
							of the popular
							online casino networks such as Party Gaming and PlayTech left the United States. Overnight,
							online casino
							players found themselves being chased by the Federal government. But, after a fortnight, the
							online casino
							industry came up with a solution and new online casinos started taking root. These began to
							operate under a
							different business umbrella, and by doing that, rendered the transfer of money to and from
							them legal. A major
							part of this was enlisting electronic banking systems that would accept this new
							clarification and start doing
							business with me. Listed in this article are the electronic banking systems that accept
							players from the United
							States that wish to play in online casinos.</p>
					</div>
				</div>
			</div>
			<div class="section-top-border text-right">
				<h3 class="mb-30">Right Aligned</h3>
				<div class="row">
					<div class="col-md-9">
						<p class="text-right">Over time, even the most sophisticated, memory packed computer can begin
							to run slow if we
							don’t do something to prevent it. The reason why has less to do with how computers are made
							and how they age and
							more to do with the way we use them. You see, all of the daily tasks that we do on our PC
							from running programs
							to downloading and deleting software can make our computer sluggish. To keep this from
							happening, you need to
							understand the reasons why your PC is getting slower and do something to keep your PC
							running at its best. You
							can do this through regular maintenance and PC performance optimization programs</p>
						<p class="text-right">Before we discuss all of the things that could be affecting your PC’s
							performance, let’s
							talk a little about what symptoms</p>
					</div>
					<div class="col-md-3">
						<img src="img/elements/d.jpg" alt="" class="img-fluid">
					</div>
				</div>
			</div>
			<div class="section-top-border">
				<h3 class="mb-30">Definition</h3>
				<div class="row">
					<div class="col-md-4">
						<div class="single-defination">
							<h4 class="mb-20">Definition 01</h4>
							<p>Recently, the US Federal government banned online casinos from operating in America by
								making it illegal to
								transfer money to them through any US bank or payment system. As a result of this law,
								most of the popular
								online casino networks</p>
						</div>
					</div>
					<div class="col-md-4">
						<div class="single-defination">
							<h4 class="mb-20">Definition 02</h4>
							<p>Recently, the US Federal government banned online casinos from operating in America by
								making it illegal to
								transfer money to them through any US bank or payment system. As a result of this law,
								most of the popular
								online casino networks</p>
						</div>
					</div>
					<div class="col-md-4">
						<div class="single-defination">
							<h4 class="mb-20">Definition 03</h4>
							<p>Recently, the US Federal government banned online casinos from operating in America by
								making it illegal to
								transfer money to them through any US bank or payment system. As a result of this law,
								most of the popular
								online casino networks</p>
						</div>
					</div>
				</div>
			</div>
			<div class="section-top-border">
				<h3 class="mb-30">Block Quotes</h3>
				<div class="row">
					<div class="col-lg-12">
						<blockquote class="generic-blockquote">
							“Recently, the US Federal government banned online casinos from operating in America by
							making it illegal to
							transfer money to them through any US bank or payment system. As a result of this law, most
							of the popular
							online casino networks such as Party Gaming and PlayTech left the United States. Overnight,
							online casino
							players found themselves being chased by the Federal government. But, after a fortnight, the
							online casino
							industry came up with a solution and new online casinos started taking root. These began to
							operate under a
							different business umbrella, and by doing that, rendered the transfer of money to and from
							them legal. A major
							part of this was enlisting electronic banking systems that would accept this new
							clarification and start doing
							business with me. Listed in this article are the electronic banking”
						</blockquote>
					</div>
				</div>
			</div>
			<div class="section-top-border">
				<h3 class="mb-30">Table</h3>
				<div class="progress-table-wrap">
					<div class="progress-table">
						<div class="table-head">
							<div class="serial">#</div>
							<div class="country">Countries</div>
							<div class="visit">Visits</div>
							<div class="percentage">Percentages</div>
						</div>
						<div class="table-row">
							<div class="serial">01</div>
							<div class="country"> <img src="img/elements/f1.jpg" alt="flag">Canada</div>
							<div class="visit">645032</div>
							<div class="percentage">
								<div class="progress">
									<div class="progress-bar color-1" role="progressbar" style="width: 80%"
										aria-valuenow="80" aria-valuemin="0" aria-valuemax="100"></div>
								</div>
							</div>
						</div>
						<div class="table-row">
							<div class="serial">02</div>
							<div class="country"> <img src="img/elements/f2.jpg" alt="flag">Canada</div>
							<div class="visit">645032</div>
							<div class="percentage">
								<div class="progress">
									<div class="progress-bar color-2" role="progressbar" style="width: 30%"
										aria-valuenow="30" aria-valuemin="0" aria-valuemax="100"></div>
								</div>
							</div>
						</div>
						<div class="table-row">
							<div class="serial">03</div>
							<div class="country"> <img src="img/elements/f3.jpg" alt="flag">Canada</div>
							<div class="visit">645032</div>
							<div class="percentage">
								<div class="progress">
									<div class="progress-bar color-3" role="progressbar" style="width: 55%"
										aria-valuenow="55" aria-valuemin="0" aria-valuemax="100"></div>
								</div>
							</div>
						</div>
						<div class="table-row">
							<div class="serial">04</div>
							<div class="country"> <img src="img/elements/f4.jpg" alt="flag">Canada</div>
							<div class="visit">645032</div>
							<div class="percentage">
								<div class="progress">
									<div class="progress-bar color-4" role="progressbar" style="width: 60%"
										aria-valuenow="60" aria-valuemin="0" aria-valuemax="100"></div>
								</div>
							</div>
						</div>
						<div class="table-row">
							<div class="serial">05</div>
							<div class="country"> <img src="img/elements/f5.jpg" alt="flag">Canada</div>
							<div class="visit">645032</div>
							<div class="percentage">
								<div class="progress">
									<div class="progress-bar color-5" role="progressbar" style="width: 40%"
										aria-valuenow="40" aria-valuemin="0" aria-valuemax="100"></div>
								</div>
							</div>
						</div>
						<div class="table-row">
							<div class="serial">06</div>
							<div class="country"> <img src="img/elements/f6.jpg" alt="flag">Canada</div>
							<div class="visit">645032</div>
							<div class="percentage">
								<div class="progress">
									<div class="progress-bar color-6" role="progressbar" style="width: 70%"
										aria-valuenow="70" aria-valuemin="0" aria-valuemax="100"></div>
								</div>
							</div>
						</div>
						<div class="table-row">
							<div class="serial">07</div>
							<div class="country"> <img src="img/elements/f7.jpg" alt="flag">Canada</div>
							<div class="visit">645032</div>
							<div class="percentage">
								<div class="progress">
									<div class="progress-bar color-7" role="progressbar" style="width: 30%"
										aria-valuenow="30" aria-valuemin="0" aria-valuemax="100"></div>
								</div>
							</div>
						</div>
						<div class="table-row">
							<div class="serial">08</div>
							<div class="country"> <img src="img/elements/f8.jpg" alt="flag">Canada</div>
							<div class="visit">645032</div>
							<div class="percentage">
								<div class="progress">
									<div class="progress-bar color-8" role="progressbar" style="width: 60%"
										aria-valuenow="60" aria-valuemin="0" aria-valuemax="100"></div>
								</div>
							</div>
						</div>
					</div>
				</div>
			</div>
			<div class="section-top-border">
				<h3>Image Gallery</h3>
				<div class="row gallery-item">
					<div class="col-md-4">
						<a href="img/elements/g1.jpg" class="img-pop-up">
							<div class="single-gallery-image" style="background: url(img/elements/g1.jpg);"></div>
						</a>
					</div>
					<div class="col-md-4">
						<a href="img/elements/g2.jpg" class="img-pop-up">
							<div class="single-gallery-image" style="background: url(img/elements/g2.jpg);"></div>
						</a>
					</div>
					<div class="col-md-4">
						<a href="img/elements/g3.jpg" class="img-pop-up">
							<div class="single-gallery-image" style="background: url(img/elements/g3.jpg);"></div>
						</a>
					</div>
					<div class="col-md-6">
						<a href="img/elements/g4.jpg" class="img-pop-up">
							<div class="single-gallery-image" style="background: url(img/elements/g4.jpg);"></div>
						</a>
					</div>
					<div class="col-md-6">
						<a href="img/elements/g5.jpg" class="img-pop-up">
							<div class="single-gallery-image" style="background: url(img/elements/g5.jpg);"></div>
						</a>
					</div>
					<div class="col-md-4">
						<a href="img/elements/g6.jpg" class="img-pop-up">
							<div class="single-gallery-image" style="background: url(img/elements/g6.jpg);"></div>
						</a>
					</div>
					<div class="col-md-4">
						<a href="img/elements/g7.jpg" class="img-pop-up">
							<div class="single-gallery-image" style="background: url(img/elements/g7.jpg);"></div>
						</a>
					</div>
					<div class="col-md-4">
						<a href="img/elements/g8.jpg" class="img-pop-up">
							<div class="single-gallery-image" style="background: url(img/elements/g8.jpg);"></div>
						</a>
					</div>
				</div>
			</div>
			<div class="section-top-border">
				<div class="row">
					<div class="col-md-4">
						<h3 class="mb-20">Image Gallery</h3>
						<div class="typography">
							<h1>This is header 01</h1>
							<h2>This is header 02</h2>
							<h3>This is header 03</h3>
							<h4>This is header 04</h4>
							<h5>This is header 01</h5>
							<h6>This is header 01</h6>
						</div>
					</div>
					<div class="col-md-4 mt-sm-30">
						<h3 class="mb-20">Unordered List</h3>
						<div class="">
							<ul class="unordered-list">
								<li>Fta Keys</li>
								<li>For Women Only Your Computer Usage</li>
								<li>Facts Why Inkjet Printing Is Very Appealing
									<ul>
										<li>Addiction When Gambling Becomes
											<ul>
												<li>Protective Preventative Maintenance</li>
											</ul>
										</li>
									</ul>
								</li>
								<li>Dealing With Technical Support 10 Useful Tips</li>
								<li>Make Myspace Your Best Designed Space</li>
								<li>Cleaning And Organizing Your Computer</li>
							</ul>
						</div>
					</div>
					<div class="col-md-4 mt-sm-30">
						<h3 class="mb-20">Ordered List</h3>
						<div class="">
							<ol class="ordered-list">
								<li><span>Fta Keys</span></li>
								<li><span>For Women Only Your Computer Usage</span></li>
								<li><span>Facts Why Inkjet Printing Is Very Appealing</span>
									<ol class="ordered-list-alpha">
										<li><span>Addiction When Gambling Becomes</span>
											<ol class="ordered-list-roman">
												<li><span>Protective Preventative Maintenance</span></li>
											</ol>
										</li>
									</ol>
								</li>
								<li><span>Dealing With Technical Support 10 Useful Tips</span></li>
								<li><span>Make Myspace Your Best Designed Space</span></li>
								<li><span>Cleaning And Organizing Your Computer</span></li>
							</ol>
						</div>
					</div>
				</div>
			</div>
			<div class="section-top-border">
				<div class="row">
					<div class="col-lg-8 col-md-8">
						<h3 class="mb-30">Form Element</h3>
						<form action="#">
							<div class="mt-10">
								<input type="text" name="first_name" placeholder="First Name"
									onfocus="this.placeholder = ''" onblur="this.placeholder = 'First Name'" required
									class="single-input">
							</div>
							<div class="mt-10">
								<input type="text" name="last_name" placeholder="Last Name"
									onfocus="this.placeholder = ''" onblur="this.placeholder = 'Last Name'" required
									class="single-input">
							</div>
							<div class="mt-10">
								<input type="text" name="last_name" placeholder="Last Name"
									onfocus="this.placeholder = ''" onblur="this.placeholder = 'Last Name'" required
									class="single-input">
							</div>
							<div class="mt-10">
								<input type="email" name="EMAIL" placeholder="Email address"
									onfocus="this.placeholder = ''" onblur="this.placeholder = 'Email address'" required
									class="single-input">
							</div>
							<div class="input-group-icon mt-10">
								<div class="icon"><i class="fa fa-thumb-tack" aria-hidden="true"></i></div>
								<input type="text" name="address" placeholder="Address" onfocus="this.placeholder = ''"
									onblur="this.placeholder = 'Address'" required class="single-input">
							</div>
							<div class="input-group-icon mt-10">
								<div class="icon"><i class="fa fa-plane" aria-hidden="true"></i></div>
								<div class="form-select" id="default-select"">
											<select>
												<option value=" 1">City</option>
									<option value="1">Dhaka</option>
									<option value="1">Dilli</option>
									<option value="1">Newyork</option>
									<option value="1">Islamabad</option>
									</select>
								</div>
							</div>
							<div class="input-group-icon mt-10">
								<div class="icon"><i class="fa fa-globe" aria-hidden="true"></i></div>
								<div class="form-select" id="default-select"">
											<select>
												<option value=" 1">Country</option>
									<option value="1">Bangladesh</option>
									<option value="1">India</option>
									<option value="1">England</option>
									<option value="1">Srilanka</option>
									</select>
								</div>
							</div>

							<div class="mt-10">
								<textarea class="single-textarea" placeholder="Message" onfocus="this.placeholder = ''"
									onblur="this.placeholder = 'Message'" required></textarea>
							</div>
							<!-- For Gradient Border Use -->
							<!-- <div class="mt-10">
										<div class="primary-input">
											<input id="primary-input" type="text" name="first_name" placeholder="Primary color" onfocus="this.placeholder = ''" onblur="this.placeholder = 'Primary color'">
											<label for="primary-input"></label>
										</div>
									</div> -->
							<div class="mt-10">
								<input type="text" name="first_name" placeholder="Primary color"
									onfocus="this.placeholder = ''" onblur="this.placeholder = 'Primary color'" required
									class="single-input-primary">
							</div>
							<div class="mt-10">
								<input type="text" name="first_name" placeholder="Accent color"
									onfocus="this.placeholder = ''" onblur="this.placeholder = 'Accent color'" required
									class="single-input-accent">
							</div>
							<div class="mt-10">
								<input type="text" name="first_name" placeholder="Secondary color"
									onfocus="this.placeholder = ''" onblur="this.placeholder = 'Secondary color'"
									required class="single-input-secondary">
							</div>
						</form>
					</div>
					<div class="col-lg-3 col-md-4 mt-sm-30">
						<div class="single-element-widget">
							<h3 class="mb-30">Switches</h3>
							<div class="switch-wrap d-flex justify-content-between">
								<p>01. Sample Switch</p>
								<div class="primary-switch">
									<input type="checkbox" id="default-switch">
									<label for="default-switch"></label>
								</div>
							</div>
							<div class="switch-wrap d-flex justify-content-between">
								<p>02. Primary Color Switch</p>
								<div class="primary-switch">
									<input type="checkbox" id="primary-switch" checked>
									<label for="primary-switch"></label>
								</div>
							</div>
							<div class="switch-wrap d-flex justify-content-between">
								<p>03. Confirm Color Switch</p>
								<div class="confirm-switch">
									<input type="checkbox" id="confirm-switch" checked>
									<label for="confirm-switch"></label>
								</div>
							</div>
						</div>
						<div class="single-element-widget mt-30">
							<h3 class="mb-30">Selectboxes</h3>
							<div class="default-select" id="default-select"">
										<select>
											<option value=" 1">English</option>
								<option value="1">Spanish</option>
								<option value="1">Arabic</option>
								<option value="1">Portuguise</option>
								<option value="1">Bengali</option>
								</select>
							</div>
						</div>
						<div class="single-element-widget mt-30">
							<h3 class="mb-30">Checkboxes</h3>
							<div class="switch-wrap d-flex justify-content-between">
								<p>01. Sample Checkbox</p>
								<div class="primary-checkbox">
									<input type="checkbox" id="default-checkbox">
									<label for="default-checkbox"></label>
								</div>
							</div>
							<div class="switch-wrap d-flex justify-content-between">
								<p>02. Primary Color Checkbox</p>
								<div class="primary-checkbox">
									<input type="checkbox" id="primary-checkbox" checked>
									<label for="primary-checkbox"></label>
								</div>
							</div>
							<div class="switch-wrap d-flex justify-content-between">
								<p>03. Confirm Color Checkbox</p>
								<div class="confirm-checkbox">
									<input type="checkbox" id="confirm-checkbox">
									<label for="confirm-checkbox"></label>
								</div>
							</div>
							<div class="switch-wrap d-flex justify-content-between">
								<p>04. Disabled Checkbox</p>
								<div class="disabled-checkbox">
									<input type="checkbox" id="disabled-checkbox" disabled>
									<label for="disabled-checkbox"></label>
								</div>
							</div>
							<div class="switch-wrap d-flex justify-content-between">
								<p>05. Disabled Checkbox active</p>
								<div class="disabled-checkbox">
									<input type="checkbox" id="disabled-checkbox-active" checked disabled>
									<label for="disabled-checkbox-active"></label>
								</div>
							</div>
						</div>
						<div class="single-element-widget mt-30">
							<h3 class="mb-30">Radios</h3>
							<div class="switch-wrap d-flex justify-content-between">
								<p>01. Sample radio</p>
								<div class="primary-radio">
									<input type="checkbox" id="default-radio">
									<label for="default-radio"></label>
								</div>
							</div>
							<div class="switch-wrap d-flex justify-content-between">
								<p>02. Primary Color radio</p>
								<div class="primary-radio">
									<input type="checkbox" id="primary-radio" checked>
									<label for="primary-radio"></label>
								</div>
							</div>
							<div class="switch-wrap d-flex justify-content-between">
								<p>03. Confirm Color radio</p>
								<div class="confirm-radio">
									<input type="checkbox" id="confirm-radio" checked>
									<label for="confirm-radio"></label>
								</div>
							</div>
							<div class="switch-wrap d-flex justify-content-between">
								<p>04. Disabled radio</p>
								<div class="disabled-radio">
									<input type="checkbox" id="disabled-radio" disabled>
									<label for="disabled-radio"></label>
								</div>
							</div>
							<div class="switch-wrap d-flex justify-content-between">
								<p>05. Disabled radio active</p>
								<div class="disabled-radio">
									<input type="checkbox" id="disabled-radio-active" checked disabled>
									<label for="disabled-radio-active"></label>
								</div>
							</div>
						</div>
					</div>
				</div>
			</div>
		</div>
	</div>
	<!-- End Align Area -->


    <footer class="footer">
        <div class="footer_top">
            <div class="container">
                <div class="row">
                    <div class="col-xl-4 col-md-6 col-lg-4 ">
                        <div class="footer_widget">
                            <div class="footer_logo">
                                <a href="#">
                                    <img src="img/logo.png" alt="">
                                </a>
                            </div>
                            <p class="address_text">Lorem ipsum dolor sit amet, <br> consectetur adipiscing elit, sed do <br> eiusmod tempor incididunt ut labore.
                            </p>
                            <div class="socail_links">
                                <ul>
                                    <li>
                                        <a href="#">
                                            <i class="ti-facebook"></i>
                                        </a>
                                    </li>
                                    <li>
                                        <a href="#">
                                            <i class="ti-twitter-alt"></i>
                                        </a>
                                    </li>
                                    <li>
                                        <a href="#">
                                            <i class="fa fa-dribbble"></i>
                                        </a>
                                    </li>
                                    <li>
                                        <a href="#">
                                            <i class="fa fa-instagram"></i>
                                        </a>
                                    </li>
                                </ul>
                            </div>

                        </div>
                    </div>
                    <div class="col-xl-4 col-md-6 col-lg-4">
                        <div class="footer_widget">
                            <h3 class="footer_title">
                                Our Departments
                            </h3>
                            <ul class="links">
                                <li><a href="#">Births</a></li>
                                <li><a href="#">Pulmonary</a></li>
                                <li><a href="#">Cardiology</a></li>
                                <li><a href="#">Neurology</a></li>
                                <li><a href="#">Traumatology</a></li>
                                <li><a href="#">Dental</a></li>
                                <li><a href="#">Nuclear</a></li>
                                <li><a href="#">magnetic</a></li>
                                <li><a href="#">Pregnancy</a></li>
                                <li><a href="#">For disabled</a></li>
                                <li><a href="#">X-ray</a></li>
                                <li><a href="#">Prostheses</a></li>
                            </ul>
                        </div>
                    </div>
                    <div class="col-xl-4  col-md-6 col-lg-4">
                        <div class="footer_widget">
                            <h3 class="footer_title">
                                We’re Available
                            </h3>
                            <ul class="meting_time">
                                <li class="d-flex justify-content-between "><span>Monday - Friday</span> <span>8.00 - 18.00</span></li>
                                <li class="d-flex justify-content-between "><span>Saturday	</span> <span>8.00 - 18.00</span></li>
                                <li class="d-flex justify-content-between "><span>Sunday</span> <span>8.00 - 13.00</span></li>
                            </ul>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <div class="copy-right_text">
            <div class="container">
                <div class="row">
                    <div class="bordered_1px "></div>
                    <div class="col-xl-12">
                        <p class="copy_right text-center">
                            <p><!-- Link back to Colorlib can't be removed. Template is licensed under CC BY 3.0. -->
  Copyright &copy;<script>document.write(new Date().getFullYear());</script> All rights reserved | SHIVSUJAN S R (212223040194)
                        </p>
                    </div>
                </div>
            </div>
        </div>
    </footer>

    <!-- link that opens popup -->

    <!-- form itself end-->
    <form id="test-form" class="white-popup-block mfp-hide">
        <div class="popup_box ">
            <div class="popup_inner">
                <h3>
                    Book an 
                <span>Appointment</span>
                </h3>
                <form action="#">
                    <div class="row">
                        <div class="col-xl-12">
                            <select class="form-select wide" id="default-select" class="">
                                <option data-display="Please select doctor to visit">Please select doctor to visit </option>
                                <option value="1">Anaf</option>
                                <option value="2">Nayna Therapy</option>
                                <option value="3">Nadif</option>
                            </select>
                        </div>
                        <div class="col-xl-9">
                            <input type="text"  placeholder="Your name ">
                        </div>
                        <div class="col-xl-3">
                            <input type="text"  placeholder="Your age">
                        </div>
                        <div class="col-xl-6">
                            <input type="text"  placeholder="Phone number ">
                        </div>
                        <div class="col-xl-6">
                            <input type="email"  placeholder="Email Address">
                        </div>
                        <div class="col-xl-6">
                            <input class="datepicker" placeholder="Appointment Date">
                        </div>
                        <div class="col-xl-6">
                            <input class="timepicker" placeholder="Suitable time">
                        </div>
                        <div class="col-xl-12">
                            <button type="submit" class="boxed-btn3">Make an Appointment</button>
                        </div>
                    </div>
                </form>
            </div>
        </div>
    </form>
    <!-- form itself end -->

	<!-- JS here -->
	<script src="js/vendor/modernizr-3.5.0.min.js"></script>
	<script src="js/vendor/jquery-1.12.4.min.js"></script>
	<script src="js/popper.min.js"></script>
	<script src="js/bootstrap.min.js"></script>
	<script src="js/owl.carousel.min.js"></script>
	<script src="js/isotope.pkgd.min.js"></script>
	<script src="js/ajax-form.js"></script>
	<script src="js/waypoints.min.js"></script>
	<script src="js/jquery.counterup.min.js"></script>
	<script src="js/imagesloaded.pkgd.min.js"></script>
	<script src="js/scrollIt.js"></script>
	<script src="js/jquery.scrollUp.min.js"></script>
	<script src="js/wow.min.js"></script>
	<script src="js/nice-select.min.js"></script>
	<script src="js/jquery.slicknav.min.js"></script>
	<script src="js/jquery.magnific-popup.min.js"></script>
	<script src="js/plugins.js"></script>
	<script src="js/gijgo.min.js"></script>

	<!--contact js-->
	<script src="js/contact.js"></script>
	<script src="js/jquery.ajaxchimp.min.js"></script>
	<script src="js/jquery.form.js"></script>
	<script src="js/jquery.validate.min.js"></script>
	<script src="js/mail-script.js"></script>

	<script src="js/main.js"></script>
    <script>
        $('.datepicker').datepicker({
            iconsLibrary: 'fontawesome',
            icons: {
                rightIcon: '<span class="fa fa-calendar"></span>'
            }
        });

        $('.timepicker').timepicker({
            iconsLibrary: 'fontawesome',
            icons: {
                rightIcon: '<span class="fa fa-clock-o"></span>'
            }
        });
    $(document).ready(function() {
    $('.js-example-basic-multiple').select2();
});
    </script>
</body>
</html>
```
index.html
```
<!doctype html>
<html class="no-js" lang="zxx">

<head>
    <meta charset="utf-8">
    <meta http-equiv="x-ua-compatible" content="ie=edge">
    <title>Medi</title>
    <meta name="description" content="">
    <meta name="viewport" content="width=device-width, initial-scale=1">

    <!-- <link rel="manifest" href="site.webmanifest"> -->
    <link rel="shortcut icon" type="image/x-icon" href="img/favicon.png">
    <!-- Place favicon.ico in the root directory -->

    <!-- CSS here -->
    <link rel="stylesheet" href="css/bootstrap.min.css">
    <link rel="stylesheet" href="css/owl.carousel.min.css">
    <link rel="stylesheet" href="css/magnific-popup.css">
    <link rel="stylesheet" href="css/font-awesome.min.css">
    <link rel="stylesheet" href="css/themify-icons.css">
    <link rel="stylesheet" href="css/nice-select.css">
    <link rel="stylesheet" href="css/flaticon.css">
    <link rel="stylesheet" href="css/gijgo.css">
    <link rel="stylesheet" href="css/animate.css">
    <link rel="stylesheet" href="css/slicknav.css">
    <link rel="stylesheet" href="css/style.css">
    <!-- <link rel="stylesheet" href="css/responsive.css"> -->
</head>

<body>
    <!--[if lte IE 9]>
            <p class="browserupgrade">You are using an <strong>outdated</strong> browser. Please <a href="https://browsehappy.com/">upgrade your browser</a> to improve your experience and security.</p>
        <![endif]-->


    <!-- header-start -->
    <header>
        <div class="header-area ">
            <div id="sticky-header" class="main-header-area">
                <div class="container">
                    <div class="row align-items-center">
                        <div class="col-xl-3 col-lg-3">
                            <div class="logo-img">
                                <a href="index.html">
                                    <img src="img/logo.png" alt="">
                                </a>
                            </div>
                        </div>
                        <div class="col-xl-9 col-lg-9">
                            <div class="menu_wrap d-none d-lg-block">
                                <div class="menu_wrap_inner d-flex align-items-center justify-content-end">
                                    <div class="main-menu">
                                        <nav>
                                            <ul id="navigation">
                                                <li><a href="index.html">home</a></li>
                                                <li><a href="about.html">About</a></li>
                                                <li><a href="#">blog <i class="ti-angle-down"></i></a>
                                                    <ul class="submenu">
                                                        <li><a href="blog.html">blog</a></li>
                                                        <li><a href="single-blog.html">single-blog</a></li>
                                                    </ul>
                                                </li>
                                                <li><a href="#">pages <i class="ti-angle-down"></i></a>
                                                    <ul class="submenu">
                                                        <li><a href="department.html">Deportment</a></li>
                                                        <li><a href="elements.html">elements</a></li>
                                                    </ul>
                                                </li>
                                                <li><a href="contact.html">Contact</a></li>
                                            </ul>
                                        </nav>
                                    </div>
                                    <div class="book_room">
                                        <div class="book_btn">
                                            <a class="popup-with-form" href="#test-form">Book  Appointment</a>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>
                        <div class="col-12">
                            <div class="mobile_menu d-block d-lg-none"></div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </header>
    <!-- header-end -->

    <!-- slider_area_start -->
    <div class="slider_area">
        <div class="slider_active owl-carousel">
            <div class="single_slider  d-flex align-items-center slider_bg_1 overlay">
                <div class="container">
                    <div class="row">
                        <div class="col-xl-12">
                            <div class="slider_text ">
                                <span>the best medical center</span>
                                <h3> <span>Bringing health</span> <br>
                                    to life for the whole family.</h3>
                                <a href="#" class="boxed-btn5">Discover More
                                </a>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
    <!-- slider_area_end -->

    <!-- welcome_clicnic_area_start -->
    <div class="welcome_clicnic_area">
        <div class="container">
            <div class="row align-items-center">
                <div class="col-xl-6 col-lg-6">
                    <div class="welcome_thumb">
                        <div class="thumb_1">
                            <img src="img/about/1.jpg" alt="">
                        </div>
                    </div>
                </div>
                <div class="col-xl-6 col-lg-6">
                    <div class="welcome_docmed_info">
                        <h3>Welcome To
                            <span>Modern Clinic.</span></h3>
                        <p>Lorem ipsum dolor sit amet, consectetur Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veni.</p>
                        <ul>
                            <li> <i class="flaticon-verified"></i> Lorem ipsum dolor sit amet </li>
                            <li> <i class="flaticon-verified"></i> Consectetur adipisicing elit, sed do</li>
                            <li> <i class="flaticon-verified"></i> Eiusmod tempor incididunt ut labore </li>
                        </ul>
                        <a href="about.html" class="boxed-btn6">About us</a>
                    </div>
                </div>
            </div>
        </div>
    </div>
    <!-- welcome_clicnic_area_end -->

    <!-- depertment_area_start  -->
    <div class="depertment_area">
        <div class="container">
            <div class="row custom_align align-items-end justify-content-between">
                <div class="col-lg-6">
                    <div class="section_title">
                        <h3>Departments</h3>
                        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore.</p>
                    </div>
                </div>
                <div class="col-lg-6">
                    <div class="learn_more_btn text-right">
                        <a href="#" class="boxed-btn">Learn more</a>
                    </div>
                </div>
            </div>
            <div class="row">
                <div class="col-lg-12">
                    <div class="depart_ment_tab mb-30">
                        <ul class="nav" id="myTab" role="tablist">
                            <li class="nav-item">
                                <a class="nav-link active" id="home-tab" data-toggle="tab" href="#home" role="tab" aria-controls="home" aria-selected="true">
                                    <i class="flaticon-teeth"></i>
                                    <h4>Dentistry</h4>
                                </a>
                            </li>
                            <li class="nav-item">
                                <a class="nav-link" id="profile-tab" data-toggle="tab" href="#profile" role="tab" aria-controls="profile" aria-selected="false">
                                    <i class="flaticon-cardiovascular"></i>
                                    <h4>Cardiology</h4>
                                </a>
                            </li>
                            <li class="nav-item">
                                <a class="nav-link" id="contact-tab" data-toggle="tab" href="#contact" role="tab" aria-controls="contact" aria-selected="false">
                                    <i class="flaticon-ear"></i>
                                    <h4>ENT Specialists</h4>
                                </a>
                            </li>
                            <li class="nav-item">
                                <a class="nav-link" id="Astrology-tab" data-toggle="tab" href="#Astrology" role="tab" aria-controls="contact" aria-selected="false">
                                    <i class="flaticon-bone"></i>
                                    <h4>Astrology</h4>
                                </a>
                            </li>
                            <li class="nav-item">
                                <a class="nav-link" id="Neuroanatomy-tab" data-toggle="tab" href="#Neuroanatomy" role="tab" aria-controls="contact" aria-selected="false">
                                    <i class="flaticon-lung"></i>
                                    <h4>Neuroanatomy</h4>
                                </a>
                            </li>
                            <li class="nav-item">
                                <a class="nav-link" id="Blood-tab" data-toggle="tab" href="#Blood" role="tab" aria-controls="contact" aria-selected="false">
                                    <i class="flaticon-cell"></i>
                                    <h4>Blood Screening</h4>
                                </a>
                            </li>
                        </ul>
                    </div>
                </div>
            </div>
            <div class="dept_main_info white-bg">
                <div class="tab-content" id="myTabContent">
                    <div class="tab-pane fade show active" id="home" role="tabpanel" aria-labelledby="home-tab">
                        <!-- single_content  -->
                        <div class="row align-items-center">
                            <div class="col-lg-5">
                                <div class="dept_thumb">
                                    <img src="img/department/1.jpg" alt="">
                                </div>
                            </div>
                            <div class="col-lg-7">
                                <div class="dept_info">
                                    <h3>Dentist with surgical mask holding <br> scaler near patient</h3 >
                                    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Quis ipsum suspendisse ultrices gravida. Risus commodo viverra maecenas accumsan lacus vel facilisis. </p>
                                    <a href="#" class="boxed-btn">Make An Appointment</a>
                                </div>
                            </div>
                        </div>
                        <!-- single_content  -->
                    </div>
                    <div class="tab-pane fade" id="profile" role="tabpanel" aria-labelledby="profile-tab">
                        <!-- single_content  -->
                        <div class="row align-items-center">
                            <div class="col-lg-5">
                                <div class="dept_thumb">
                                    <img src="img/department/1.jpg" alt="">
                                </div>
                            </div>
                            <div class="col-lg-7">
                                <div class="dept_info">
                                    <h3>Dentist with surgical mask holding <br> scaler near patient</h3 >
                                    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Quis ipsum suspendisse ultrices gravida. Risus commodo viverra maecenas accumsan lacus vel facilisis. </p>
                                    <a href="#" class="boxed-btn">Make An Appointment</a>
                                </div>
                            </div>
                        </div>
                        <!-- single_content  -->
                    </div>
                    <div class="tab-pane fade" id="contact" role="tabpanel" aria-labelledby="contact-tab">
                    <!-- single_content  -->
                    <div class="row align-items-center">
                        <div class="col-lg-5">
                            <div class="dept_thumb">
                                <img src="img/department/1.jpg" alt="">
                            </div>
                        </div>
                        <div class="col-lg-7">
                            <div class="dept_info">
                                <h3>Dentist with surgical mask holding <br> scaler near patient</h3 >
                                <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Quis ipsum suspendisse ultrices gravida. Risus commodo viverra maecenas accumsan lacus vel facilisis. </p>
                                <a href="#" class="boxed-btn">Make An Appointment</a>
                            </div>
                        </div>
                    </div>
                    <!-- single_content  -->
                    </div>
                    <div class="tab-pane fade" id="Astrology" role="tabpanel" aria-labelledby="Astrology-tab">
                        <!-- single_content  -->
                        <div class="row align-items-center">
                            <div class="col-lg-5">
                                <div class="dept_thumb">
                                    <img src="img/department/1.jpg" alt="">
                                </div>
                            </div>
                            <div class="col-lg-7">
                                <div class="dept_info">
                                    <h3>Dentist with surgical mask holding <br> scaler near patient</h3 >
                                    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Quis ipsum suspendisse ultrices gravida. Risus commodo viverra maecenas accumsan lacus vel facilisis. </p>
                                    <a href="#" class="boxed-btn">Make An Appointment</a>
                                </div>
                            </div>
                        </div>
                        <!-- single_content  -->
                    </div>
                    <div class="tab-pane fade" id="Neuroanatomy" role="tabpanel" aria-labelledby="Neuroanatomy-tab">
                        <!-- single_content  -->
                        <div class="row align-items-center">
                            <div class="col-lg-5">
                                <div class="dept_thumb">
                                    <img src="img/department/1.jpg" alt="">
                                </div>
                            </div>
                            <div class="col-lg-7">
                                <div class="dept_info">
                                    <h3>Dentist with surgical mask holding <br> scaler near patient</h3 >
                                    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Quis ipsum suspendisse ultrices gravida. Risus commodo viverra maecenas accumsan lacus vel facilisis. </p>
                                    <a href="#" class="boxed-btn">Make An Appointment</a>
                                </div>
                            </div>
                        </div>
                        <!-- single_content  -->
                    </div>
                    <div class="tab-pane fade" id="Blood" role="tabpanel" aria-labelledby="Blood-tab">
                    <!-- single_content  -->
                    <div class="row align-items-center">
                        <div class="col-lg-5">
                            <div class="dept_thumb">
                                <img src="img/department/1.jpg" alt="">
                            </div>
                        </div>
                        <div class="col-lg-7">
                            <div class="dept_info">
                                <h3>Dentist with surgical mask holding <br> scaler near patient</h3 >
                                <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Quis ipsum suspendisse ultrices gravida. Risus commodo viverra maecenas accumsan lacus vel facilisis. </p>
                                <a href="#" class="boxed-btn">Make An Appointment</a>
                            </div>
                        </div>
                    </div>
                    <!-- single_content  -->
                    </div>
                  </div>
            </div>

        </div>
    </div>
    <!-- depertment_area_end  -->

    <!-- expert_doctors_area_start -->
    <div class="expert_doctors_area">
        <div class="container">
            <div class="row justify-content-center ">
                <div class="col-lg-6">
                    <div class="section_title mb-55 text-center">
                        <h3>Our Doctors</h3>
                        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore.</p>
                    </div>
                </div>
            </div>
            <div class="row justify-content-center">
                <div class="col-lg-4 col-md-6">
                    <div class="single_expert">
                        <div class="expert_thumb">
                            <img src="img/experts/1.png" alt="">
                        </div>
                        <div class="experts_name text-center">
                            <h3>Jhon Smith</h3>
                            <span>Dentist</span>
                            <div class="social_links">
                                <ul>
                                    <li>
                                        <a href="#"> <i class="fa fa-facebook"></i> </a>
                                    </li>
                                    <li>
                                        <a href="#"> <i class="fa fa-linkedin"></i> </a>
                                    </li>
                                    <li>
                                        <a href="#"> <i class="fa fa-twitter"></i> </a>
                                    </li>
                                </ul>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="col-lg-4 col-md-6">
                    <div class="single_expert">
                        <div class="expert_thumb">
                            <img src="img/experts/2.png" alt="">
                        </div>
                        <div class="experts_name text-center">
                            <h3>Jhon Smith</h3>
                            <span>Dentist</span>
                            <div class="social_links">
                                <ul>
                                    <li>
                                        <a href="#"> <i class="fa fa-facebook"></i> </a>
                                    </li>
                                    <li>
                                        <a href="#"> <i class="fa fa-linkedin"></i> </a>
                                    </li>
                                    <li>
                                        <a href="#"> <i class="fa fa-twitter"></i> </a>
                                    </li>
                                </ul>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="col-lg-4 col-md-6">
                    <div class="single_expert">
                        <div class="expert_thumb">
                            <img src="img/experts/3.png" alt="">
                        </div>
                        <div class="experts_name text-center">
                            <h3>Jhon Smith</h3>
                            <span>Dentist</span>
                            <div class="social_links">
                                <ul>
                                    <li>
                                        <a href="#"> <i class="fa fa-facebook"></i> </a>
                                    </li>
                                    <li>
                                        <a href="#"> <i class="fa fa-linkedin"></i> </a>
                                    </li>
                                    <li>
                                        <a href="#"> <i class="fa fa-twitter"></i> </a>
                                    </li>
                                </ul>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
    <!-- expert_doctors_area_end -->

    <div class="book_apointment_area">
        <div class="container">
            <div class="row justify-content-end">
                <div class="col-lg-7">
                    <div class="popup_box ">
                        <div class="popup_inner">
                            <h3>
                                Book an 
                            <span>Appointment</span>
                            </h3>
                            <form action="#">
                                <div class="row">
                                    <div class="col-xl-12">
                                        <select class="form-select wide" id="default-select" class="">
                                            <option data-display="Please select doctor to visit">Please select doctor to visit </option>
                                            <option value="1">Anaf</option>
                                            <option value="2">Nayna Therapy</option>
                                            <option value="3">Nadif</option>
                                        </select>
                                    </div>
                                    <div class="col-xl-9">
                                        <input type="text"  placeholder="Your name ">
                                    </div>
                                    <div class="col-xl-3">
                                        <input type="text"  placeholder="Your age">
                                    </div>
                                    <div class="col-xl-6">
                                        <input type="text"  placeholder="Phone number ">
                                    </div>
                                    <div class="col-xl-6">
                                        <input type="email"  placeholder="Email Address">
                                    </div>
                                    <div class="col-xl-6">
                                        <input class="datepicker" placeholder="Appointment Date">
                                    </div>
                                    <div class="col-xl-6">
                                        <input class="timepicker" placeholder="Suitable time">
                                    </div>
                                    <div class="col-xl-12">
                                        <button type="submit" class="boxed-btn3">Make an Appointment</button>
                                    </div>
                                </div>
                            </form>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <!-- quality_area_start  -->
    <div class="quality_area">
        <div class="container">
            <div class="row justify-content-center ">
                <div class="col-lg-6">
                    <div class="section_title mb-55 text-center">
                        <h3>Quality Health</h3>
                        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore.</p>
                    </div>
                </div>
            </div>
            <div class="row">
                <div class="col-lg-4 col-md-6">
                    <div class="single_quality">
                        <div class="icon">
                            <i class="flaticon-customer-service"></i>
                        </div>
                        <h3>Health Consultation</h3>
                        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt.</p>
                    </div>
                </div>
                <div class="col-lg-4 col-md-6">
                    <div class="single_quality">
                        <div class="icon">
                            <i class="flaticon-find"></i>
                        </div>
                        <h3>Find Health</h3>
                        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt.</p>
                    </div>
                </div>
                <div class="col-lg-4 col-md-6">
                    <div class="single_quality">
                        <div class="icon">
                            <i class="flaticon-doctor"></i>
                        </div>
                        <h3>Search Deoctor</h3>
                        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt.</p>
                    </div>
                </div>
            </div>
        </div>
    </div>
    <!-- quality_areaend  -->

    <!-- Emergency_contact start -->
    <div class="Emergency_contact">
        <div class="Emergency_contact_inner ">
            <div class="container">
                <div class="row align-items-center">
                    <div class="col-lg-6">
                        <div class="single_emergency">
                            <div class="info">
                                <span>We are here for you</span>
                                <h3>Book Appointment</h3>
                            </div>
                            <div class="info_button">
                                <a href="#" class="boxed-btn3-white">Book Appointment
                                </a>
                            </div>
                        </div>
                    </div>
                    <div class="col-lg-6">
                        <div class="single_emergency align-items-center d-flex justify-content-end">
                            <div class="icon">
                                <i class="flaticon-call"></i>
                            </div>
                            <div class="info">
                                <span>Emergency Medical Care</span>
                                <h3>+1-465 4545</h3>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
    <!-- Emergency_contact end -->

    <footer class="footer">
        <div class="footer_top">
            <div class="container">
                <div class="row">
                    <div class="col-xl-4 col-md-6 col-lg-4 ">
                        <div class="footer_widget">
                            <div class="footer_logo">
                                <a href="#">
                                    <img src="img/logo.png" alt="">
                                </a>
                            </div>
                            <p class="address_text">Lorem ipsum dolor sit amet, <br> consectetur adipiscing elit, sed do <br> eiusmod tempor incididunt ut labore.
                            </p>
                            <div class="socail_links">
                                <ul>
                                    <li>
                                        <a href="#">
                                            <i class="ti-facebook"></i>
                                        </a>
                                    </li>
                                    <li>
                                        <a href="#">
                                            <i class="ti-twitter-alt"></i>
                                        </a>
                                    </li>
                                    <li>
                                        <a href="#">
                                            <i class="fa fa-dribbble"></i>
                                        </a>
                                    </li>
                                    <li>
                                        <a href="#">
                                            <i class="fa fa-instagram"></i>
                                        </a>
                                    </li>
                                </ul>
                            </div>

                        </div>
                    </div>
                    <div class="col-xl-4 col-md-6 col-lg-4">
                        <div class="footer_widget">
                            <h3 class="footer_title">
                                Our Departments
                            </h3>
                            <ul class="links">
                                <li><a href="#">Births</a></li>
                                <li><a href="#">Pulmonary</a></li>
                                <li><a href="#">Cardiology</a></li>
                                <li><a href="#">Neurology</a></li>
                                <li><a href="#">Traumatology</a></li>
                                <li><a href="#">Dental</a></li>
                                <li><a href="#">Nuclear</a></li>
                                <li><a href="#">magnetic</a></li>
                                <li><a href="#">Pregnancy</a></li>
                                <li><a href="#">For disabled</a></li>
                                <li><a href="#">X-ray</a></li>
                                <li><a href="#">Prostheses</a></li>
                            </ul>
                        </div>
                    </div>
                    <div class="col-xl-4  col-md-6 col-lg-4">
                        <div class="footer_widget">
                            <h3 class="footer_title">
                                We’re Available
                            </h3>
                            <ul class="meting_time">
                                <li class="d-flex justify-content-between "><span>Monday - Friday</span> <span>8.00 - 18.00</span></li>
                                <li class="d-flex justify-content-between "><span>Saturday	</span> <span>8.00 - 18.00</span></li>
                                <li class="d-flex justify-content-between "><span>Sunday</span> <span>8.00 - 13.00</span></li>
                            </ul>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <div class="copy-right_text">
            <div class="container">
                <div class="row">
                    <div class="bordered_1px "></div>
                    <div class="col-xl-12">
                        <p class="copy_right text-center">
                            <p><!-- Link back to Colorlib can't be removed. Template is licensed under CC BY 3.0. -->
  Copyright &copy;<script>document.write(new Date().getFullYear());</script> All rights reserved | SHIVSUAJN S R (212223040194)
                        </p>
                    </div>
                </div>
            </div>
        </div>
    </footer>

    <!-- link that opens popup -->

    <!-- form itself end-->
    <form id="test-form" class="white-popup-block mfp-hide">
        <div class="popup_box ">
            <div class="popup_inner">
                <h3>
                    Book an 
                <span>Appointment</span>
                </h3>
                <form action="#">
                    <div class="row">
                        <div class="col-xl-12">
                            <select class="form-select wide" id="default-select" class="">
                                <option data-display="Please select doctor to visit">Please select doctor to visit </option>
                                <option value="1">Anaf</option>
                                <option value="2">Nayna Therapy</option>
                                <option value="3">Nadif</option>
                            </select>
                        </div>
                        <div class="col-xl-9">
                            <input type="text"  placeholder="Your name ">
                        </div>
                        <div class="col-xl-3">
                            <input type="text"  placeholder="Your age">
                        </div>
                        <div class="col-xl-6">
                            <input type="text"  placeholder="Phone number ">
                        </div>
                        <div class="col-xl-6">
                            <input type="email"  placeholder="Email Address">
                        </div>
                        <div class="col-xl-6">
                            <input class="datepicker" placeholder="Appointment Date">
                        </div>
                        <div class="col-xl-6">
                            <input class="timepicker" placeholder="Suitable time">
                        </div>
                        <div class="col-xl-12">
                            <button type="submit" class="boxed-btn3">Make an Appointment</button>
                        </div>
                    </div>
                </form>
            </div>
        </div>
    </form>
    <!-- form itself end -->

    <!-- JS here -->
    <script src="js/vendor/modernizr-3.5.0.min.js"></script>
    <script src="js/vendor/jquery-1.12.4.min.js"></script>
    <script src="js/popper.min.js"></script>
    <script src="js/bootstrap.min.js"></script>
    <script src="js/owl.carousel.min.js"></script>
    <script src="js/isotope.pkgd.min.js"></script>
    <script src="js/ajax-form.js"></script>
    <script src="js/waypoints.min.js"></script>
    <script src="js/jquery.counterup.min.js"></script>
    <script src="js/imagesloaded.pkgd.min.js"></script>
    <script src="js/scrollIt.js"></script>
    <script src="js/jquery.scrollUp.min.js"></script>
    <script src="js/wow.min.js"></script>
    <script src="js/nice-select.min.js"></script>
    <script src="js/jquery.slicknav.min.js"></script>
    <script src="js/jquery.magnific-popup.min.js"></script>
    <script src="js/plugins.js"></script>
    <script src="js/gijgo.min.js"></script>
    <!--contact js-->
    <script src="js/contact.js"></script>
    <script src="js/jquery.ajaxchimp.min.js"></script>
    <script src="js/jquery.form.js"></script>
    <script src="js/jquery.validate.min.js"></script>
    <script src="js/mail-script.js"></script>

    <script src="js/main.js"></script>
    <script>
        $('.datepicker').datepicker({
            iconsLibrary: 'fontawesome',
            icons: {
                rightIcon: '<span class="fa fa-calendar"></span>'
            }
        });

        $('.timepicker').timepicker({
            iconsLibrary: 'fontawesome',
            icons: {
                rightIcon: '<span class="fa fa-clock-o"></span>'
            }
        });
    $(document).ready(function() {
    $('.js-example-basic-multiple').select2();
});
    </script>
</body>

</html>
```
single-blog.html
```
<!doctype html>
<html class="no-js" lang="zxx">

<head>
   <meta charset="utf-8">
   <meta http-equiv="x-ua-compatible" content="ie=edge">
   <title>Docmed</title>
   <meta name="description" content="">
   <meta name="viewport" content="width=device-width, initial-scale=1">

   <!-- <link rel="manifest" href="site.webmanifest"> -->
   <link rel="shortcut icon" type="image/x-icon" href="img/favicon.png">
   <!-- Place favicon.ico in the root directory -->

    <!-- CSS here -->
    <link rel="stylesheet" href="css/bootstrap.min.css">
    <link rel="stylesheet" href="css/owl.carousel.min.css">
    <link rel="stylesheet" href="css/magnific-popup.css">
    <link rel="stylesheet" href="css/font-awesome.min.css">
    <link rel="stylesheet" href="css/themify-icons.css">
    <link rel="stylesheet" href="css/nice-select.css">
    <link rel="stylesheet" href="css/flaticon.css">
    <link rel="stylesheet" href="css/gijgo.css">
    <link rel="stylesheet" href="css/animate.css">
    <link rel="stylesheet" href="css/slicknav.css">
    <link rel="stylesheet" href="css/style.css">
</head>

<body>
   <!--[if lte IE 9]>
            <p class="browserupgrade">You are using an <strong>outdated</strong> browser. Please <a href="https://browsehappy.com/">upgrade your browser</a> to improve your experience and security.</p>
        <![endif]-->
    <!-- header-start -->
    <header>
      <div class="header-area ">
          <div id="sticky-header" class="main-header-area">
              <div class="container">
                  <div class="row align-items-center">
                      <div class="col-xl-3 col-lg-3">
                          <div class="logo-img">
                              <a href="index.html">
                                  <img src="img/logo.png" alt="">
                              </a>
                          </div>
                      </div>
                      <div class="col-xl-9 col-lg-9">
                          <div class="menu_wrap d-none d-lg-block">
                              <div class="menu_wrap_inner d-flex align-items-center justify-content-end">
                                  <div class="main-menu">
                                      <nav>
                                          <ul id="navigation">
                                              <li><a href="index.html">home</a></li>
                                              <li><a href="about.html">About</a></li>
                                              <li><a href="#">blog <i class="ti-angle-down"></i></a>
                                                  <ul class="submenu">
                                                      <li><a href="blog.html">blog</a></li>
                                                      <li><a href="single-blog.html">single-blog</a></li>
                                                  </ul>
                                              </li>
                                              <li><a href="#">pages <i class="ti-angle-down"></i></a>
                                                  <ul class="submenu">
                                                      <li><a href="department.html">Deportment</a></li>
                                                      <li><a href="elements.html">elements</a></li>
                                                  </ul>
                                              </li>
                                              <li><a href="contact.html">Contact</a></li>
                                          </ul>
                                      </nav>
                                  </div>
                                  <div class="book_room">
                                      <div class="book_btn">
                                          <a class="popup-with-form" href="#test-form">Book  Appointment</a>
                                      </div>
                                  </div>
                              </div>
                          </div>
                      </div>
                      <div class="col-12">
                          <div class="mobile_menu d-block d-lg-none"></div>
                      </div>
                  </div>
              </div>
          </div>
      </div>
  </header>
  <!-- header-end -->

  <!-- bradcam_area_start  -->
  <div class="bradcam_area breadcam_bg">
      <div class="container">
          <div class="row">
              <div class="col-xl-12">
                  <div class="bradcam_text">
                      <h3>single Blog</h3>
                  </div>
              </div>
          </div>
      </div>
  </div>
  <!-- bradcam_area_end  -->

   <!--================Blog Area =================-->
   <section class="blog_area single-post-area section-padding">
      <div class="container">
         <div class="row">
            <div class="col-lg-8 posts-list">
               <div class="single-post">
                  <div class="feature-img">
                     <img class="img-fluid" src="img/blog/single_blog_1.png" alt="">
                  </div>
                  <div class="blog_details">
                     <h2>Second divided from form fish beast made every of seas
                        all gathered us saying he our
                     </h2>
                     <ul class="blog-info-link mt-3 mb-4">
                        <li><a href="#"><i class="fa fa-user"></i> Travel, Lifestyle</a></li>
                        <li><a href="#"><i class="fa fa-comments"></i> 03 Comments</a></li>
                     </ul>
                     <p class="excert">
                        MCSE boot camps have its supporters and its detractors. Some people do not understand why you
                        should have to spend money on boot camp when you can get the MCSE study materials yourself at a
                        fraction of the camp price. However, who has the willpower
                     </p>
                     <p>
                        MCSE boot camps have its supporters and its detractors. Some people do not understand why you
                        should have to spend money on boot camp when you can get the MCSE study materials yourself at a
                        fraction of the camp price. However, who has the willpower to actually sit through a
                        self-imposed MCSE training. who has the willpower to actually
                     </p>
                     <div class="quote-wrapper">
                        <div class="quotes">
                           MCSE boot camps have its supporters and its detractors. Some people do not understand why you
                           should have to spend money on boot camp when you can get the MCSE study materials yourself at
                           a fraction of the camp price. However, who has the willpower to actually sit through a
                           self-imposed MCSE training.
                        </div>
                     </div>
                     <p>
                        MCSE boot camps have its supporters and its detractors. Some people do not understand why you
                        should have to spend money on boot camp when you can get the MCSE study materials yourself at a
                        fraction of the camp price. However, who has the willpower
                     </p>
                     <p>
                        MCSE boot camps have its supporters and its detractors. Some people do not understand why you
                        should have to spend money on boot camp when you can get the MCSE study materials yourself at a
                        fraction of the camp price. However, who has the willpower to actually sit through a
                        self-imposed MCSE training. who has the willpower to actually
                     </p>
                  </div>
               </div>
               <div class="navigation-top">
                  <div class="d-sm-flex justify-content-between text-center">
                     <p class="like-info"><span class="align-middle"><i class="fa fa-heart"></i></span> Lily and 4
                        people like this</p>
                     <div class="col-sm-4 text-center my-2 my-sm-0">
                        <!-- <p class="comment-count"><span class="align-middle"><i class="fa fa-comment"></i></span> 06 Comments</p> -->
                     </div>
                     <ul class="social-icons">
                        <li><a href="#"><i class="fa fa-facebook-f"></i></a></li>
                        <li><a href="#"><i class="fa fa-twitter"></i></a></li>
                        <li><a href="#"><i class="fa fa-dribbble"></i></a></li>
                        <li><a href="#"><i class="fa fa-behance"></i></a></li>
                     </ul>
                  </div>
                  <div class="navigation-area">
                     <div class="row">
                        <div
                           class="col-lg-6 col-md-6 col-12 nav-left flex-row d-flex justify-content-start align-items-center">
                           <div class="thumb">
                              <a href="#">
                                 <img class="img-fluid" src="img/post/preview.png" alt="">
                              </a>
                           </div>
                           <div class="arrow">
                              <a href="#">
                                 <span class="lnr text-white ti-arrow-left"></span>
                              </a>
                           </div>
                           <div class="detials">
                              <p>Prev Post</p>
                              <a href="#">
                                 <h4>Space The Final Frontier</h4>
                              </a>
                           </div>
                        </div>
                        <div
                           class="col-lg-6 col-md-6 col-12 nav-right flex-row d-flex justify-content-end align-items-center">
                           <div class="detials">
                              <p>Next Post</p>
                              <a href="#">
                                 <h4>Telescopes 101</h4>
                              </a>
                           </div>
                           <div class="arrow">
                              <a href="#">
                                 <span class="lnr text-white ti-arrow-right"></span>
                              </a>
                           </div>
                           <div class="thumb">
                              <a href="#">
                                 <img class="img-fluid" src="img/post/next.png" alt="">
                              </a>
                           </div>
                        </div>
                     </div>
                  </div>
               </div>
               <div class="blog-author">
                  <div class="media align-items-center">
                     <img src="img/blog/author.png" alt="">
                     <div class="media-body">
                        <a href="#">
                           <h4>Harvard milan</h4>
                        </a>
                        <p>Second divided from form fish beast made. Every of seas all gathered use saying you're, he
                           our dominion twon Second divided from</p>
                     </div>
                  </div>
               </div>
               <div class="comments-area">
                  <h4>05 Comments</h4>
                  <div class="comment-list">
                     <div class="single-comment justify-content-between d-flex">
                        <div class="user justify-content-between d-flex">
                           <div class="thumb">
                              <img src="img/comment/comment_1.png" alt="">
                           </div>
                           <div class="desc">
                              <p class="comment">
                                 Multiply sea night grass fourth day sea lesser rule open subdue female fill which them
                                 Blessed, give fill lesser bearing multiply sea night grass fourth day sea lesser
                              </p>
                              <div class="d-flex justify-content-between">
                                 <div class="d-flex align-items-center">
                                    <h5>
                                       <a href="#">Emilly Blunt</a>
                                    </h5>
                                    <p class="date">December 4, 2017 at 3:12 pm </p>
                                 </div>
                                 <div class="reply-btn">
                                    <a href="#" class="btn-reply text-uppercase">reply</a>
                                 </div>
                              </div>
                           </div>
                        </div>
                     </div>
                  </div>
                  <div class="comment-list">
                     <div class="single-comment justify-content-between d-flex">
                        <div class="user justify-content-between d-flex">
                           <div class="thumb">
                              <img src="img/comment/comment_2.png" alt="">
                           </div>
                           <div class="desc">
                              <p class="comment">
                                 Multiply sea night grass fourth day sea lesser rule open subdue female fill which them
                                 Blessed, give fill lesser bearing multiply sea night grass fourth day sea lesser
                              </p>
                              <div class="d-flex justify-content-between">
                                 <div class="d-flex align-items-center">
                                    <h5>
                                       <a href="#">Emilly Blunt</a>
                                    </h5>
                                    <p class="date">December 4, 2017 at 3:12 pm </p>
                                 </div>
                                 <div class="reply-btn">
                                    <a href="#" class="btn-reply text-uppercase">reply</a>
                                 </div>
                              </div>
                           </div>
                        </div>
                     </div>
                  </div>
                  <div class="comment-list">
                     <div class="single-comment justify-content-between d-flex">
                        <div class="user justify-content-between d-flex">
                           <div class="thumb">
                              <img src="img/comment/comment_3.png" alt="">
                           </div>
                           <div class="desc">
                              <p class="comment">
                                 Multiply sea night grass fourth day sea lesser rule open subdue female fill which them
                                 Blessed, give fill lesser bearing multiply sea night grass fourth day sea lesser
                              </p>
                              <div class="d-flex justify-content-between">
                                 <div class="d-flex align-items-center">
                                    <h5>
                                       <a href="#">Emilly Blunt</a>
                                    </h5>
                                    <p class="date">December 4, 2017 at 3:12 pm </p>
                                 </div>
                                 <div class="reply-btn">
                                    <a href="#" class="btn-reply text-uppercase">reply</a>
                                 </div>
                              </div>
                           </div>
                        </div>
                     </div>
                  </div>
               </div>
               <div class="comment-form">
                  <h4>Leave a Reply</h4>
                  <form class="form-contact comment_form" action="#" id="commentForm">
                     <div class="row">
                        <div class="col-12">
                           <div class="form-group">
                              <textarea class="form-control w-100" name="comment" id="comment" cols="30" rows="9"
                                 placeholder="Write Comment"></textarea>
                           </div>
                        </div>
                        <div class="col-sm-6">
                           <div class="form-group">
                              <input class="form-control" name="name" id="name" type="text" placeholder="Name">
                           </div>
                        </div>
                        <div class="col-sm-6">
                           <div class="form-group">
                              <input class="form-control" name="email" id="email" type="email" placeholder="Email">
                           </div>
                        </div>
                        <div class="col-12">
                           <div class="form-group">
                              <input class="form-control" name="website" id="website" type="text" placeholder="Website">
                           </div>
                        </div>
                     </div>
                     <div class="form-group">
                        <button type="submit" class="button button-contactForm btn_1 boxed-btn">Send Message</button>
                     </div>
                  </form>
               </div>
            </div>
            <div class="col-lg-4">
               <div class="blog_right_sidebar">
                  <aside class="single_sidebar_widget search_widget">
                     <form action="#">
                        <div class="form-group">
                           <div class="input-group mb-3">
                              <input type="text" class="form-control" placeholder='Search Keyword'
                                 onfocus="this.placeholder = ''" onblur="this.placeholder = 'Search Keyword'">
                              <div class="input-group-append">
                                 <button class="btn" type="button"><i class="ti-search"></i></button>
                              </div>
                           </div>
                        </div>
                        <button class="button rounded-0 primary-bg text-white w-100 btn_1 boxed-btn"
                           type="submit">Search</button>
                     </form>
                  </aside>
                  <aside class="single_sidebar_widget post_category_widget">
                     <h4 class="widget_title">Category</h4>
                     <ul class="list cat-list">
                        <li>
                           <a href="#" class="d-flex">
                              <p>Resaurant food</p>
                              <p>(37)</p>
                           </a>
                        </li>
                        <li>
                           <a href="#" class="d-flex">
                              <p>Travel news</p>
                              <p>(10)</p>
                           </a>
                        </li>
                        <li>
                           <a href="#" class="d-flex">
                              <p>Modern technology</p>
                              <p>(03)</p>
                           </a>
                        </li>
                        <li>
                           <a href="#" class="d-flex">
                              <p>Product</p>
                              <p>(11)</p>
                           </a>
                        </li>
                        <li>
                           <a href="#" class="d-flex">
                              <p>Inspiration</p>
                              <p>(21)</p>
                           </a>
                        </li>
                        <li>
                           <a href="#" class="d-flex">
                              <p>Health Care</p>
                              <p>(21)</p>
                           </a>
                        </li>
                     </ul>
                  </aside>
                  <aside class="single_sidebar_widget popular_post_widget">
                     <h3 class="widget_title">Recent Post</h3>
                     <div class="media post_item">
                        <img src="img/post/post_1.png" alt="post">
                        <div class="media-body">
                           <a href="single-blog.html">
                              <h3>From life was you fish...</h3>
                           </a>
                           <p>January 12, 2019</p>
                        </div>
                     </div>
                     <div class="media post_item">
                        <img src="img/post/post_2.png" alt="post">
                        <div class="media-body">
                           <a href="single-blog.html">
                              <h3>The Amazing Hubble</h3>
                           </a>
                           <p>02 Hours ago</p>
                        </div>
                     </div>
                     <div class="media post_item">
                        <img src="img/post/post_3.png" alt="post">
                        <div class="media-body">
                           <a href="single-blog.html">
                              <h3>Astronomy Or Astrology</h3>
                           </a>
                           <p>03 Hours ago</p>
                        </div>
                     </div>
                     <div class="media post_item">
                        <img src="img/post/post_4.png" alt="post">
                        <div class="media-body">
                           <a href="single-blog.html">
                              <h3>Asteroids telescope</h3>
                           </a>
                           <p>01 Hours ago</p>
                        </div>
                     </div>
                  </aside>
                  <aside class="single_sidebar_widget tag_cloud_widget">
                     <h4 class="widget_title">Tag Clouds</h4>
                     <ul class="list">
                        <li>
                           <a href="#">project</a>
                        </li>
                        <li>
                           <a href="#">love</a>
                        </li>
                        <li>
                           <a href="#">technology</a>
                        </li>
                        <li>
                           <a href="#">travel</a>
                        </li>
                        <li>
                           <a href="#">restaurant</a>
                        </li>
                        <li>
                           <a href="#">life style</a>
                        </li>
                        <li>
                           <a href="#">design</a>
                        </li>
                        <li>
                           <a href="#">illustration</a>
                        </li>
                     </ul>
                  </aside>
                  <aside class="single_sidebar_widget instagram_feeds">
                     <h4 class="widget_title">Instagram Feeds</h4>
                     <ul class="instagram_row flex-wrap">
                        <li>
                           <a href="#">
                              <img class="img-fluid" src="img/post/post_5.png" alt="">
                           </a>
                        </li>
                        <li>
                           <a href="#">
                              <img class="img-fluid" src="img/post/post_6.png" alt="">
                           </a>
                        </li>
                        <li>
                           <a href="#">
                              <img class="img-fluid" src="img/post/post_7.png" alt="">
                           </a>
                        </li>
                        <li>
                           <a href="#">
                              <img class="img-fluid" src="img/post/post_8.png" alt="">
                           </a>
                        </li>
                        <li>
                           <a href="#">
                              <img class="img-fluid" src="img/post/post_9.png" alt="">
                           </a>
                        </li>
                        <li>
                           <a href="#">
                              <img class="img-fluid" src="img/post/post_10.png" alt="">
                           </a>
                        </li>
                     </ul>
                  </aside>
                  <aside class="single_sidebar_widget newsletter_widget">
                     <h4 class="widget_title">Newsletter</h4>
                     <form action="#">
                        <div class="form-group">
                           <input type="email" class="form-control" onfocus="this.placeholder = ''"
                              onblur="this.placeholder = 'Enter email'" placeholder='Enter email' required>
                        </div>
                        <button class="button rounded-0 primary-bg text-white w-100 btn_1 boxed-btn"
                           type="submit">Subscribe</button>
                     </form>
                  </aside>
               </div>
            </div>
         </div>
      </div>
   </section>
   <!--================ Blog Area end =================-->

<!-- footer start -->
<footer class="footer">
   <div class="footer_top">
       <div class="container">
           <div class="row">
               <div class="col-xl-4 col-md-6 col-lg-4">
                   <div class="footer_widget">
                       <div class="footer_logo">
                           <a href="#">
                               <img src="img/footer_logo.png" alt="">
                           </a>
                       </div>
                       <p>
                               Firmament morning sixth subdue darkness 
                               creeping gathered divide.
                       </p>
                       <div class="socail_links">
                           <ul>
                               <li>
                                   <a href="#">
                                       <i class="ti-facebook"></i>
                                   </a>
                               </li>
                               <li>
                                   <a href="#">
                                       <i class="ti-twitter-alt"></i>
                                   </a>
                               </li>
                               <li>
                                   <a href="#">
                                       <i class="fa fa-instagram"></i>
                                   </a>
                               </li>
                           </ul>
                       </div>

                   </div>
               </div>
               <div class="col-xl-2 offset-xl-1 col-md-6 col-lg-3">
                   <div class="footer_widget">
                       <h3 class="footer_title">
                               Departments
                       </h3>
                       <ul>
                           <li><a href="#">Eye Care</a></li>
                           <li><a href="#">Skin Care</a></li>
                           <li><a href="#">Pathology</a></li>
                           <li><a href="#">Medicine</a></li>
                           <li><a href="#">Dental</a></li>
                       </ul>

                   </div>
               </div>
               <div class="col-xl-2 col-md-6 col-lg-2">
                   <div class="footer_widget">
                       <h3 class="footer_title">
                               Useful Links
                       </h3>
                       <ul>
                           <li><a href="#">About</a></li>
                           <li><a href="#">Blog</a></li>
                           <li><a href="#">About</a></li>
                           <li><a href="#"> Contact</a></li>
                           <li><a href="#"> Appointment</a></li>
                       </ul>
                   </div>
               </div>
               <div class="col-xl-3 col-md-6 col-lg-3">
                   <div class="footer_widget">
                       <h3 class="footer_title">
                               Address
                       </h3>
                       <p>
                           200, D-block, Green lane USA <br>
                           +10 367 467 8934 <br>
                           docmed@contact.com
                       </p>
                   </div>
               </div>
           </div>
       </div>
   </div>
   <div class="copy-right_text">
       <div class="container">
           <div class="footer_border"></div>
           <div class="row">
               <div class="col-xl-12">
                   <p class="copy_right text-center">
                       <p><!-- Link back to Colorlib can't be removed. Template is licensed under CC BY 3.0. -->
  Copyright &copy;<script>document.write(new Date().getFullYear());</script> All rights reserved | SHIV SUJAN S R (212223040194)
                   </p>
               </div>
           </div>
       </div>
   </div>
</footer>
<!-- footer end  -->
<!-- link that opens popup -->

    <!-- form itself end-->
    <form id="test-form" class="white-popup-block mfp-hide">
      <div class="popup_box ">
          <div class="popup_inner">
              <h3>
                  Book an 
              <span>Appointment</span>
              </h3>
              <form action="#">
                  <div class="row">
                      <div class="col-xl-12">
                          <select class="form-select wide" id="default-select" class="">
                              <option data-display="Please select doctor to visit">Please select doctor to visit </option>
                              <option value="1">Anaf</option>
                              <option value="2">Nayna Therapy</option>
                              <option value="3">Nadif</option>
                          </select>
                      </div>
                      <div class="col-xl-9">
                          <input type="text"  placeholder="Your name ">
                      </div>
                      <div class="col-xl-3">
                          <input type="text"  placeholder="Your age">
                      </div>
                      <div class="col-xl-6">
                          <input type="text"  placeholder="Phone number ">
                      </div>
                      <div class="col-xl-6">
                          <input type="email"  placeholder="Email Address">
                      </div>
                      <div class="col-xl-6">
                          <input class="datepicker" placeholder="Appointment Date">
                      </div>
                      <div class="col-xl-6">
                          <input class="timepicker" placeholder="Suitable time">
                      </div>
                      <div class="col-xl-12">
                          <button type="submit" class="boxed-btn3">Make an Appointment</button>
                      </div>
                  </div>
              </form>
          </div>
      </div>
  </form>
  <!-- form itself end -->


    <!-- form itself end-->
    <form id="test-form" class="white-popup-block mfp-hide">
      <div class="popup_box ">
          <div class="popup_inner">
              <h3>
                  Book an 
              <span>Appointment</span>
              </h3>
              <form action="#">
                  <div class="row">
                      <div class="col-xl-12">
                          <select class="form-select wide" id="default-select" class="">
                              <option data-display="Please select doctor to visit">Please select doctor to visit </option>
                              <option value="1">Anaf</option>
                              <option value="2">Nayna Therapy</option>
                              <option value="3">Nadif</option>
                          </select>
                      </div>
                      <div class="col-xl-9">
                          <input type="text"  placeholder="Your name ">
                      </div>
                      <div class="col-xl-3">
                          <input type="text"  placeholder="Your age">
                      </div>
                      <div class="col-xl-6">
                          <input type="text"  placeholder="Phone number ">
                      </div>
                      <div class="col-xl-6">
                          <input type="email"  placeholder="Email Address">
                      </div>
                      <div class="col-xl-6">
                          <input class="datepicker" placeholder="Appointment Date">
                      </div>
                      <div class="col-xl-6">
                          <input class="timepicker" placeholder="Suitable time">
                      </div>
                      <div class="col-xl-12">
                          <button type="submit" class="boxed-btn3">Make an Appointment</button>
                      </div>
                  </div>
              </form>
          </div>
      </div>
  </form>
  <!-- form itself end -->

  <!-- JS here -->
  <script src="js/vendor/modernizr-3.5.0.min.js"></script>
  <script src="js/vendor/jquery-1.12.4.min.js"></script>
  <script src="js/popper.min.js"></script>
  <script src="js/bootstrap.min.js"></script>
  <script src="js/owl.carousel.min.js"></script>
  <script src="js/isotope.pkgd.min.js"></script>
  <script src="js/ajax-form.js"></script>
  <script src="js/waypoints.min.js"></script>
  <script src="js/jquery.counterup.min.js"></script>
  <script src="js/imagesloaded.pkgd.min.js"></script>
  <script src="js/scrollIt.js"></script>
  <script src="js/jquery.scrollUp.min.js"></script>
  <script src="js/wow.min.js"></script>
  <script src="js/nice-select.min.js"></script>
  <script src="js/jquery.slicknav.min.js"></script>
  <script src="js/jquery.magnific-popup.min.js"></script>
  <script src="js/plugins.js"></script>
  <script src="js/gijgo.min.js"></script>
  <!--contact js-->
  <script src="js/contact.js"></script>
  <script src="js/jquery.ajaxchimp.min.js"></script>
  <script src="js/jquery.form.js"></script>
  <script src="js/jquery.validate.min.js"></script>
  <script src="js/mail-script.js"></script>

  <script src="js/main.js"></script>
  <script>
      $('.datepicker').datepicker({
          iconsLibrary: 'fontawesome',
          icons: {
              rightIcon: '<span class="fa fa-calendar"></span>'
          }
      });

      $('.timepicker').timepicker({
          iconsLibrary: 'fontawesome',
          icons: {
              rightIcon: '<span class="fa fa-clock-o"></span>'
          }
      });
  $(document).ready(function() {
  $('.js-example-basic-multiple').select2();
});
  </script>
</body>

</html>
```


## OUTPUT:
HOME
![alt text](<Screenshot 2024-05-08 214949.png>)
ABOUT US
![alt text](<Screenshot 2024-05-08 215111.png>)
BLOG
![alt text](<Screenshot 2024-05-08 215135.png>)
PAGES
![alt text](<Screenshot 2024-05-08 215159.png>)
CONTACT US
![alt text](<Screenshot 2024-05-08 215450.png>)

## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
