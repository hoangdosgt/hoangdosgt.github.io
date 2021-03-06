layout: page
title: "PAGE detail"
permalink: /detail
<!doctype html>
<html lang="en">
  <head>
    <!-- Required meta tags -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">

    <!-- Bootstrap CSS -->
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/css/bootstrap.min.css" integrity="sha384-Vkoo8x4CGsO3+Hhxv8T/Q5PaXtkKtu6ug5TOeNV6gBiFeWPGFN9MuhOf23Q9Ifjh" crossorigin="anonymous">

    <link rel="preconnect" href="https://fonts.gstatic.com">
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@300;500&display=swap" rel="stylesheet">
    <link rel="shortcut icon" href="assets/img/SaigonThink1.png">

    <title>Huan Vu Self-introduce</title>
    <style>
    * {
        margin: 0;
        width: 100%;
        box-sizing: border-box;
        background-color: #e8eaef;
    }

    /* Create three equal columns that floats next to each other */
    .column {
      float: left;
      width: 33.33%;
      padding: 10px;
      height: 300px; /* Should be removed. Only for demonstration */
    }

    /* Clear floats after the columns */
    .row:after {
      content: "";
      display: table;
      clear: both;
    }
    .avata{
        width: 144px !important;
        height: 144px;
        border-radius: 9999px;
    }

    .left{
        width: 25%;
    }

    .right {
        width: 75%;
        font-size: 14px;
    }
    .project{
        position: relative;
        display: -webkit-box;
        display: -ms-flexbox;
        display: flex;
        -ms-flex-wrap: wrap;
        flex-wrap: wrap;
        background-color: #fff;
        padding: 1.2rem 2rem;
        background-repeat: no-repeat;
        font-size: .875rem;
        margin-bottom: 1.5rem;
        background-image: -webkit-gradient(linear,left top,right top,color-stop(1%,#c3c8d5),color-stop(35%,#c3c8d5),color-stop(35%,#d2d6e0),to(#d2d6e0));
        background-image: linear-gradient(90deg,#c3c8d5 1%,#c3c8d5 35%,#d2d6e0 0,#d2d6e0);
        background-size: 100% 4px;
        background-repeat: no-repeat;
    }
    a{
        background-color: transparent;
    }

    p{
        background-color: transparent;
    }

    u{
        background-color: transparent;
    }

    h5{
        background-color: transparent;
    }

    .font-light {
        font-weight: 300;
    }

    .font-header {

    }

    .text-2xl {
        font-size: 1.5rem;
    }

    .font-black {
        font-weight: 900;
    }

    .text-5xl {
        font-size: 3rem;
    }

    .break-words {
        word-wrap: break-word;
    }

    .mb-6 {
        margin-bottom: 1.5rem;
    }

    .bg-front {
        background-color: #1f1f1f;
    }   

    .w-auto {
        width: auto;
    }

    .mt-6 {
        margin-top: 1.5rem;
    }

    .bg-black{
        background-color: black;
    }
    .text-lg {
        font-size: 1.125rem;
    }
    .text-back {
        color: #e8eaef;
    }
    .px-3 {
        padding-left: .75rem;
        padding-right: .75rem;
    }
    .py-1 {
        padding-top: .25rem;
        padding-bottom: .25rem;
    }

    .font-bold {
        font-weight: 700;
    }

    @media (min-width: 992px)
    .lg\:px-8 {
        padding-left: 2rem;
        padding-right: 2rem;
    }

    .p-4 {
        padding: 1rem;
    }

    .justify-between {
        -webkit-box-pack: justify;
        -ms-flex-pack: justify;
        justify-content: space-between;
    }

    .flex {
        display: -webkit-box;
        display: -ms-flexbox;
        display: flex;
    }

    .contact{
        width: 142px;
        height: auto;
        font-family: Source Sans Pro,sans-serif;
        display: inline-block;
        text-decoration: none;
        font-weight: 600;
        padding-left: 1.5rem;
        padding-right: 1.5rem;
        line-height: 1.25;
        cursor: pointer;
        outline: 0;
        -webkit-transition: opacity .2s ease-out;
        transition: opacity .2s ease-out;
        will-change: opacity;
        padding: .5rem 1.5rem;
        border-radius: 1rem;
        -ms-flex-item-align: start;
        align-self: flex-start;
        background-color: #eee841;
        color: initial;
    }

    .contact-text{
        background-color: transparent;
        width: unset;
    }

    .title{
        margin-top: 20px;
    }

    .mb-0{
        margin-bottom: 0;
    }

    .logo{
        width: 90px;
    }

    .author{
        font-family: 'Roboto', sans-serif;
    }

    </style>
  </head>
  <body>
    <div class="flex justify-between p-4 lg:px-8">
    <span class="inline-flex w-14 h-14 lg:mt-4 font-header font-bold text-xl justify-center items-center text-front border-2 border-solid border-front rounded-full">
        <img src="assets/img/SaigonThink1.png" class="logo">
    </span>
    <a href="#contact" class="contact ">
        <span class="hidden lg:block contact-text">Contact me</span>
    </a>
    </div>
        <div class="container">
              <div class="column left">
                <div class="row" id="overview">
                    <h2 class="font-header font-light text-front text-2xl leading-none author">CEO</h2>
                    <h1 class="font-header font-black text-front text-5xl leading-none break-words mb-6 author">?????o V??</h1>
                    <img src="assets/img/daovo.jpg" class="avata">
                </div>
              </div>
              <div class="column right">

                <div class="row" id="company">
                    <h5>Company</h5>
                    <h3 class="font-header font-light text-2xl text-front leading-tight mb-0">Saigonthink</h3>
                </div>
                <div class="row" id="about">
                    <h5 class="title">ABOUT</h5>
                    <p class="mb-0">
                        Collaborating with leaders to solve their customer's most challenging problems on Azure.
                    </p>
                </div>
                <div class="row" id="projects">
                    <h5 class="title">Programs</h5>
                    <div class="project">
                        <h5 class="background-white">Azure Fundamentals</h5>
                        <p class="background-white">2019, Sep 09   ???  2 minute read</p>
                        <p class="w-full">
                            Azure Fundamentals training at HCMC Skype Group Please join group chat on skype to discuss...
                        </p>
                    </div> 
                    <div class="project">
                        <h5 class="background-white">How I Rest From Work</h5>
                        <p class="background-white">2017, Sep 12   ???  4 minute read</p>
                        <p class="w-full">
                            Fam locavore snackwave bushwick +1 sartorial. Selfies portland knausgaard synth. Pop-up art party marfa deep...
                        </p>
                    </div> 
                    <div class="project">
                        <h5 class="background-white">The Best Organizer Software</h5>
                        <p class="background-white">2017, Sep 11   ???  3 minute read</p>
                        <p class="w-full">
                            Church-key blog messenger bag, selfies umami man braid mlkshk. Pork belly cornhole meditation tumblr meh...
                        </p>
                    </div> 
                    <div class="project">
                        <h5 class="background-white">How To Start Programming</h5>
                        <p class="background-white">2017, Sep 11   ???  3 minute read</p>
                        <p class="w-full">
                            Post-ironic jean shorts bushwick umami, synth beard austin hell of meh kitsch distillery sustainable plaid...
                        </p>
                    </div> 
                    <div class="project">
                        <h5 class="background-white">10 Tips To Improve Your Workflow</h5>
                        <p class="background-white">2017, Sep 11   ???  5 minute read</p>
                        <p class="w-full">
                            Asymmetrical portland enamel pin af heirloom ramps authentic thundercats. Synth truffaut schlitz aesthetic, palo santo...
                        </p>
                    </div> 
                    <div class="project">
                        <h5 class="background-white">Conference on Javascript</h5>
                        <p class="background-white">2017, Sep 09   ???  2 minute read</p>
                        <p class="w-full">
                            Jean shorts organic cornhole, gochujang post-ironic chicharrones authentic flexitarian viral PBR&B forage wolf. Man braid...
                        </p>
                    </div> 
                    <div class="project">
                        <h5 class="background-white">Welcome to Jekyll!</h5>
                        <p class="background-white">2017, Apr 06   ???  1 minute read</p>
                        <p class="w-full">
                            You???ll find this post in your _posts directory. Go ahead and edit it and re-build...
                        </p>
                    </div> 
                </div>
              </div>
        </div>

    <!-- Optional JavaScript -->
    <!-- jQuery first, then Popper.js, then Bootstrap JS -->
    <script src="https://code.jquery.com/jquery-3.4.1.slim.min.js" integrity="sha384-J6qa4849blE2+poT4WnyKhv5vZF5SrPo0iEjwBvKU7imGFAV0wwj1yYfoRSJoZ+n" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.0/dist/umd/popper.min.js" integrity="sha384-Q6E9RHvbIyZFJoft+2mJbHaEWldlvI9IOYy5n3zV9zzTtmI3UksdQRVvoxMfooAo" crossorigin="anonymous"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/js/bootstrap.min.js" integrity="sha384-wfSDF2E50Y2D1uUdj0O3uMBJnjuUD4Ih7YwaYd1iqfktj0Uod8GCExl3Og8ifwB6" crossorigin="anonymous"></script>
  </body>
</html>
