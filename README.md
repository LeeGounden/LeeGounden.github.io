<!DOCTYPE html>
<html lang="en">
<head>
<title>New Phone</title>
<meta charset="UTF-8">
<!--Style Sheet-->
<link rel="stylesheet" type="text/css" href="css/flexslider.css" media="screen">
<link rel="stylesheet" type="text/css" href="css/sequence.css" media="screen">
<link rel="stylesheet" type="text/css" href="css/lightbox.css" media="screen">
<link rel="stylesheet" type="text/css" href="css/style.css" media="all">
<!--Special Styles-->
<link rel="stylesheet" type="text/css" href="css/style.css" title="default" media="screen">

<!--Responsive-->
<link rel="stylesheet" type="text/css" href="css/responsitive.css" media="all">
<!--Google fonts-->
<link href='http://fonts.googleapis.com/css?family=Russo+One&subset=latin,latin-ext,cyrillic' rel='stylesheet' type='text/css'>
<link href='http://fonts.googleapis.com/css?family=Open+Sans:400,700,300&subset=latin,cyrillic' rel='stylesheet' type='text/css'>
<link href='http://fonts.googleapis.com/css?family=Lato:300,400,700,900' rel='stylesheet' type='text/css'>
<!--Javascript-->
<script src="js/jquery-1.7.2.min.js"></script>
<!--[if lt IE9]>
<script src="js/html5.js"></script>
<script src="js/IE7.js"></script>
<![endif]-->
</head>
<body>
<header class="dark">
  <nav>
    <div id="logo">
      <h1>New Phone</h1>
    </div>
    <div id="menu">
      <ul>
        <li> <a href="#slider" >Home</a> <a href="#services" >Tech Specs</a> <a href="#work">images</a> <a href="#about">features</a> <a href="#blog">reviews</a> <a href="#contact">Purchase</a> </li>
      </ul>
    </div>
  </nav>
</header>
<!--
Nb: bugs out at the moment ...
<div id="switcher"> <a class="switch-button open"></a>
  <div class="content">
    <ul class="headercolor">
      <span>Header color</span>
      <li class="red"><a href="#light">Light</a></li>
      <li class="blue"><a href="#dark">Dark</a></li>
    </ul>
    <ul class="theme">
      <span>Theme</span>
      <li><a href="#" rel="default" class="styleswitch">default</a></li>
      <li><a href="#" rel="elegant" class="styleswitch">elegant</a></li>
      <li><a href="#" rel="modern" class="styleswitch">modern</a></li>
      <li><a href="#" rel="colorfull" class="styleswitch">colorfull</a></li>
    </ul>
  </div>
</div>-->
<section id="slider">
  <div id="sequence-preloader">
    <div class="preloading"> <img src="images/icons/loader.gif" alt=""> </div>
  </div>
  <div id="slideshow"> <img class="prev" src="images/prev.png" alt=""> <img class="next" src="images/next.png" alt="">
    <ul>
      <li> <img class="backgrd" src="images/bg/glass.jpg" alt=""> <img class="overlay" src="images/bg/ice.png" alt=""> <img class="image1" src="images/wow.png" alt=""> <img class="image2" src="images/cellphone2.png" alt="">
        <div class="info">
          <h2>Cellphone name</h2>
          <p>wow,<br/>
            wow</p>
        </div>
        <a href="purchase.html" class="more">Purchase</a> </li>
      <li> <img class="backgrd" src="images/bg/orange.jpg" alt=""> <img class="image1" src="images/wow.png" alt=""> <img class="image2" src="images/cellphone.png" alt="">
        <div class="info">
          <h2>another feature</h2>
          <p>wow,<br/>
            more wow </p>
        </div>
        <a href="more.html" class="more">Purchase</a> </li>
      <li> <img class="backgrd" src="images/bg/blue.jpg" alt=""> <img class="image1" src="images/wow.png" alt=""> <img class="image2" src="images/cellphone3.png" alt="">
        <div class="info blue">
          <h2>tech</h2>
          <p>feauture 1<br/>
            wow</p>
        </div>
      </li>
    </ul>
  </div>
</section>
<section id="services" class="container dark">
  <div class="content">
    <div class="title icon-power">
      <h1>Tech specs<span>amazing</span></h1>
      <div class="description"></div>
    </div>
    <div class="full">
      <div class="column-half">
        <p><a href="more.html">Learn more</a> about the phone.</p>
      </div>
      <div class="column-half">
        <div class="image"><img src="images/cellphone2.png" alt=""></div>
      </div>
    </div>
    <div class="full">
      <div class="column-one-forth">
        <ul class="list">
          <h3>feature</h3>
          <li>Things</li>
          <li>Memory</li>
          <li>cCamera <span>(Stuff)</span></li>
          <li>Detonation button</li>
        </ul>
      </div>
      <div class="column-one-forth">
        <ul class="list">
          <h3>Its a cellphone</h3>
          <li>Does phone things</li>
          <li>more stuff</li>
          <li>stuff</li>
          <li>stuff</li>
        </ul>
      </div>
      <div class="column-one-forth">
        <ul class="list">
          <h3>Development</h3>
          <li>Made</li>
          <li>By</li>
          <li>Orphaned</li>
          <li>Seals</li>
        </ul>
      </div>
      <div class="column-one-forth last">
        <ul class="list">
          <h3>Information</h3>
          <li>stuff</li>
          <li>stuff</li>
          <li>stuff</li>
          <li>stuff</li>
        </ul>
      </div>
    </div>
  </div>
</section>
<section id="work" class="container light">
  <div class="content">
    <div class="title icon-preview">
      <h1>images <span>of phones and whatnot</span></h1>
      <div class="description">
        <nav id="filter"></nav>
      </div>
    </div>
    <article class="portfolio">
      <ul id="stage">
        <li data-tags="phone">
          <div class="thumb"><a rel="lightbox" href="images/sample/cellphone2.png"><img src="images/sample/cellphone2.png" alt=""></a></div>
          <div class="info">
            <h3>phone</h3>
            <p>information</p>
          </div>
        </li>
        <li data-tags="internals">
          <div class="thumb"><a rel="lightbox" href="images/sample/cellphone.png"><img src="images/sample/cellphone2.png" alt=""></a></div>
          <div class="info">
            <h3>cellphone</h3>
            <p>more information</p>
          </div>
        </li>
        <li data-tags="externals">
          <div class="thumb"><a rel="lightbox" href="images/sample/cellphone3.png"><img src="images/sample/cellphone2.png" alt=""></a></div>
          <div class="info">
            <h3>phone</h3>
            <p>information</p>
          </div>
        </li>
       
          <div class="info">
            <h3>cellphone2.png</h3>
            <p>cellphone2.png</p>
          </div>
        </li>
      </ul>
    </article>
  </div>
</section>
<section id="about" class="container dark">
  <div class="content">
    <div class="title icon-and">
      <h1>Features <span> more</span></h1>
      <div class="description">
        <p>phone things</p>
      </div>
    </div>
    <div class="full">
      <div class="image"><img src="images/sample/cellphone2.png" alt=""></div>
      <div class="divider"></div>
      <div class="column-half">
        <div class="subtitle">
          <h3>POWER</h3>
        </div>
        <p>Cellphone stuff</p>
      </div>
      <div class="column-half last">
        <div class="subtitle">
          <h3>things:</h3>
        </div>
        <ul id="skills">
          <li><span title="50"></span>
            <p>power <strong>50%</strong></p>
          </li>
          <li><span title="98"></span>
            <p>awesome <strong>98%</strong></p>
          </li>
          <li><span title="55"></span>
            <p>thingies <strong>55%</strong></p>
          </li>
          <li><span title="100"></span>
            <p>wubwub <strong>100%</strong></p>
          </li>
          <li><span title="75"></span>
            <p>more things <strong>75%</strong></p>
          </li>
          <li><span title="80"></span>
            <p>pretty <strong>80%</strong></p>
          </li>
        </ul>
        <!--END skills-->
      </div>
      <div class="column-half">
        <div class="subtitle">
          <h3>stuff</h3>
        </div>
        <div class="accordion" id="list1">
          <!--Accordion-->
          <a>stuff</a>
          <div>
            <p>stuff</p>
          </div>
          <a>stuff</a>
          <div>
            <p>stuff</p>
          </div>
          <a>stuff</a>
          <div>
            <p>stuff</p>
          </div>
        </div>
        <!--Accordion end-->
      </div>
      <div class="column-half last">
        <div class="subtitle">
          <h3>More things</h3>
        </div>
        <ul class="tabs-nav">
          <li class="active-tab"><a href="#tab1">First</a></li>
          <li><a href="#tab2">Second</a></li>
          <li><a href="#tab3">Third</a></li>
        </ul>
        <!-- end tab navigation -->
        <div class="tabs-container">
          <div class="tab-content" id="tab1">
            <p>stuff</p>
          </div>
          <!-- end tab1 -->
          <div class="tab-content" id="tab2">
            <p>stuff</p>
          </div>
          <!-- end tab2 -->
          <div class="tab-content" id="tab3">
            <p>stuff</p>
          </div>
          <!-- end tab3 -->
        </div>
        <!-- end tab container -->
      </div>
      <div id="shot" class="full">
        <div class="subtitle">
          <h3>Pictures</h3>
        </div>
        <div class="shot medium">
          <div id="shotById" class="dribbble-shot">
            <div><a href="#"><img src="images/sample/cellphone.png" alt=""></a></div>
          </div>
        </div>
        <div class="shot"> <img src="images/sample/cellphone2.png" alt=""> </div>
        <div class="shot"> <img src="images/sample/cellphone3.png" alt=""> </div>
        <div class="shot"> <img src="images/sample/cellphone.png" alt=""> </div>
        <div class="shot"> <img src="images/sample/cellphone2.png" alt=""> </div>
      </div>
    </div>
  </div>
</section>
<section id="blog" class="container light">
  <div class="content">
    <div class="title icon-note">
      <h1>tReviews <span> and stuff</span></h1>
      <div class="description">
        <p>nice</p>
      </div>
    </div>
    <div id="box">
      <article class="post">
        <figure><img src="images/sample/cellphone2.png" alt=""></figure>
        <figcaption>thing <span>stuff</span></figcaption>
      </article>
      
      <article class="post">
        <figure>
          <p>It does phone things.</p>
        </figure>
        <figcaption>I have no idea what i'm doing.<span> Some potato paper</span></figcaption>
      </article>

    </div>
  </div>
</section>
<section id="contact" class="container dark second">
  <div class="content">
    <div class="title icon-phone">
      <h1>Purchase <span>buy The phone</span></h1>
      <div class="description"> </div>
    </div>
 
          <div class="column-half last">
            <div id="imgae"></div>
            <p>Buy the Phone here</p>
          </div>
             <a href="purchase.html">   <div class="image"><img src="images/buy.png" alt=""></div>
             </a>
      </div>
    </div>
  </div>
</section>
<footer> 
  <section class="footer">
    <p>New Phone</p>
  </section>
</footer>
<!--Javascript-->

<script src="js/jquery.flexslider-min.js"></script>
<script src="js/sequence.jquery-min.js"></script>
<script src="js/waypoints.min.js"></script>
<script src="js/quicksand.js"></script>
<script src="js/jquery.masonery.js"></script>


<script src="js/jquery.accordion.js"></script>
<script src="js/lightbox.js"></script>

<script src="js/custom.js"></script>
<!--Sequence slider-->
<script>
var options = {
    autoPlay: true,
    nextButton: ".next",
    prevButton: ".prev",
    preloader: "#sequence-preloader",
    prependPreloader: false,
    prependPreloadingComplete: "#sequence-preloader, #slideshow",
    animateStartingFrameIn: true,
    transitionThreshold: 500,
    nextButtonAlt: " ",
    prevButtonAlt: " ",
    afterPreload: function () {
        $(".prev, .next").fadeIn(500);
        if (!slideShow.transitionsSupported) {
            $("#slideshow").animate({
                "opacity": "1"
            }, 1000);
        }
    }
};
var slideShow = $("#slideshow").sequence(options).data("sequence");
if (!slideShow.transitionsSupported || slideShow.prefix == "-o-") {
    $("#slideshow").animate({
        "opacity": "1"
    }, 1000);
    slideShow.preloaderFallback();
}
</script>

<script>
if (typeof jQuery == 'undefined') {
    document.write(unescape("%3Cscript src='js/jquery.js'%3E%3C/script%3E"));
}
</script>

</body>
</html>
