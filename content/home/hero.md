+++
# Hero widget.
widget = "hero"
active = true
date = 2017-10-15T00:00:00

title = ""

# Order that this section will appear in.
weight = 3

# Overlay a color or image (optional).
#   Deactivate an option by commenting out the line, prefixing it with `#`.
[header]
  overlay_color = "#2962fea1"  # An HTML color value.
  overlay_img = "back.jpg"  # Image path relative to your `static/img/` folder.
  overlay_filter = 0.5  # Darken the image. Value in range 0-1.

# Call to action button (optional).
#   Activate the button by specifying a URL and button label below.
#   Deactivate by commenting out parameters, prefixing lines with `#`.
[cta]
  #url = "./post/getting-started/"
  #label = '<i class="fas fa-download"></i> Install Now'
+++


  <style>
  canvas{ display: block; vertical-align: bottom; position:absolute; top:-2%; right:0%; z-index:-1; }
  #test{background:rgba(0,0,0,0.5);} 
  section#hero{
    height:100vh !important;
    text-align:center;
    padding-top:30vh;
  }

@import url(https://fonts.googleapis.com/css?family=Josefin+Sans:300,400);

html, body {
  height: 100%;
}
.typed-cursor{
  color:white;
}

.demo a {
  position: absolute;
  bottom: 20px;
  left: 50%;
  z-index: 100;
  display: inline-block;
  -webkit-transform: translate(0, -50%);
  transform: translate(0, -50%);
 
  text-decoration: none;
  transition: opacity .3s;
}
.demo a:hover {
  text-decoration: none;
}

#section06 a {
  padding-top: 70px;
}
#section06 a span {
  position: absolute;
  top: 50;
  left: 50%;
  width: 24px;
  height: 24px;
  margin-left: -12px;
  border-left: 1px solid;
  border-bottom: 1px solid;
  border-color:#fff;
  -webkit-transform: rotateZ(-45deg);
  transform: rotateZ(-45deg);
  -webkit-animation: sdb06 1.5s infinite;
  animation: sdb06 1.5s infinite;
  box-sizing: border-box;
}
@-webkit-keyframes sdb06 {
  0% {
    -webkit-transform: rotateY(0) rotateZ(-45deg) translate(0, 0);
    opacity: 0;
  }
  50% {
    opacity: 1;
  }
  100% {
    -webkit-transform: rotateY(720deg) rotateZ(-45deg) translate(-20px, 20px);
    opacity: 0;
  }
}
@keyframes sdb06 {
  0% {
    transform: rotateY(0) rotateZ(-45deg) translate(0, 0);
    opacity: 0;
  }
  50% {
    opacity: 1;
  }
  100% {
    transform: rotateY(720deg) rotateZ(-45deg) translate(-20px, 20px);
    opacity: 0;
  }
}

#section07 a {
  padding-top: 80px;
}
#section07 a span {
  position: absolute;
  top: 74vh;
  left: 50%;
  width: 24px;
  height: 24px;
  margin-left: -12px;
  border-left: 1px solid;
  border-bottom: 1px solid;
  border-color:inherit;
  -webkit-transform: rotate(-45deg);
  transform: rotate(-45deg);
  -webkit-animation: sdb07 2s infinite;
  animation: sdb07 2s infinite;
  opacity: 0;
  box-sizing: border-box;
}
#section07 a span:nth-of-type(1) {
  -webkit-animation-delay: 0s;
  animation-delay: 0s;
}
#section07 a span:nth-of-type(2) {
  top: 76vh;
  -webkit-animation-delay: .15s;
  animation-delay: .15s;
}
#section07 a span:nth-of-type(3) {
  top: 78vh;
  -webkit-animation-delay: .3s;
  animation-delay: .3s;
}
@-webkit-keyframes sdb07 {
  0% {
    opacity: 0;
  }
  50% {
    opacity: 1;
  }
  100% {
    opacity: 0;
  }
}
@keyframes sdb07 {
  0% {
    opacity: 0;
  }
  50% {
    opacity: 1;
  }
  100% {
    opacity: 0;
  }
}

</style>
<!-- <div id="dev" style="white-space: nowrap; display:inline;"></div>
<br> -->

<div id="name" style="white-space: nowrap; display:inline; color:#fff;"></div>
<br>
<div id="app" style="white-space: nowrap; display:inline; color:#fff;"></div>
<br>
<!-- <section id="section06" class="demo" style="margin-top:20vh;">
  <a href="#about" style="color:inherit"><span></span>About Me</a>
</section> -->
<section id="section07" class="demo" style="margin-top:20vh;">
  <a href="#about" style="color:#fff"><span></span><span></span><span></span>About Me</a>
</section>

<!-- <div id="test">
  <a id="academic-release" href="https://sourcethemes.com/academic/updates" data-repo="gcushen/hugo-academic">
  Latest release
  </a>
</div> -->
<!-- <div class="mt-3">
  <a class="github-button" href="https://github.com/gcushen/hugo-academic" data-icon="octicon-star" data-size="large" data-show-count="true" aria-label="Star this on GitHub">Star</a>
</div> -->

<!-- <script async defer src="https://buttons.github.io/buttons.js"></script> -->
<script async defer src="https://cdn.jsdelivr.net/particles.js/2.0.0/particles.min.js"> </script> 

<script>
particlesJS("hero", {"particles":{"number":{"value":50,"density":{"enable":true,"value_area":1000}},"color":{"value":"#ffffff"},"shape":{"type":"polygon","stroke":{"width":0,"color":"#000000"},"polygon":{"nb_sides":6},"image":{"src":"img/github.svg","width":100,"height":100}},"opacity":{"value":0.5,"random":true,"anim":{"enable":false,"speed":0.5,"opacity_min":0.1,"sync":true}},"size":{"value":4,"random":true,"anim":{"enable":false,"speed":40,"size_min":0.1,"sync":false}},"line_linked":{"enable":true,"distance":150,"color":"#ffffff","opacity":0.4,"width":1},"move":{"enable":true,"speed":2,"direction":"none","random":true,"straight":false,"out_mode":"out","bounce":true,"attract":{"enable":true,"rotateX":600,"rotateY":1200}}},"interactivity":{"detect_on":"canvas","events":{"onhover":{"enable":true,"mode":"grab"},"onclick":{"enable":true,"mode":"repulse"},"resize":true},"modes":{"grab":{"distance":400,"line_linked":{"opacity":1}},"bubble":{"distance":400,"size":40,"duration":2,"opacity":8,"speed":3},"repulse":{"distance":200,"duration":0.4},"push":{"particles_nb":4},"remove":{"particles_nb":2}}},"retina_detect":true});
// particlesJS("hero", {
//   particles: {
//     number: {
//       value: 52,
//       density: {
//         enable: true,
//         value_area: 631.3280775270874
//       }
//     },
//     color: {
//       value: "#fff"
//     },
//     shape: {
//       type: "circle",
//       stroke: {
//         width: 0,
//         color: "#000000"
//       },
//       polygon: {
//         nb_sides: 5
//       },
//       image: {
//         src: "img/github.svg",
//         width: 100,
//         height: 100
//       }
//     },
//     opacity: {
//       value: 0.5,
//       random: true,
//       anim: {
//         enable: false,
//         speed: 1,
//         opacity_min: 0.1,
//         sync: false
//       }
//     },
//     size: {
//       value: 5,
//       random: true,
//       anim: {
//         enable: false,
//         speed: 40,
//         size_min: 0.1,
//         sync: false
//       }
//     },
//     line_linked: {
//       enable: false,
//       distance: 500,
//       color: "#ffffff",
//       opacity: 0.4,
//       width: 2
//     },
//     move: {
//       enable: true,
//       speed: 1.5,
//       direction: "bottom",
//       random: false,
//       straight: false,
//       out_mode: "out",
//       bounce: false,
//       attract: {
//         enable: false,
//         rotateX: 600,
//         rotateY: 1200
//       }
//     }
//   },
//   interactivity: {
//     detect_on: "canvas",
//     events: {
//       onhover: {
//         enable: false,
//         mode: "bubble"
//       },
//       onclick: {
//         enable: true,
//         mode: "repulse"
//       },
//       resize: true
//     },
//     modes: {
//       grab: {
//         distance: 400,
//         line_linked: {
//           opacity: 0.5
//         }
//       },
//       bubble: {
//         distance: 400,
//         size: 4,
//         duration: 0.3,
//         opacity: 1,
//         speed: 3
//       },
//       repulse: {
//         distance: 200,
//         duration: 0.4
//       },
//       push: {
//         particles_nb: 4
//       },
//       remove: {
//         particles_nb: 2
//       }
//     }
//   },
//   retina_detect: true
// });
// var count_particles, stats, update;
// stats = new Stats();
// stats.setMode(0);
// stats.domElement.style.position = "absolute";
// stats.domElement.style.left = "0px";
// stats.domElement.style.top = "0px";
// document.body.appendChild(stats.domElement);
// count_particles = document.querySelector(".js-count-particles");
// update = function() {
//   stats.begin();
//   stats.end();
//   if (window.pJSDom[0].pJS.particles && window.pJSDom[0].pJS.particles.array) {
//     count_particles.innerText = window.pJSDom[0].pJS.particles.array.length;
//   }
//   requestAnimationFrame(update);
// };
// requestAnimationFrame(update);

  </script>

<!-- <script  src="https://unpkg.com/typewriter-effect@2.3.1/dist/core.js"></script> -->
<script src="https://cdn.jsdelivr.net/npm/typed.js@2.0.9"></script>
<script
  src="https://cdnjs.cloudflare.com/ajax/libs/jquery/2.1.3/jquery.min.js"
></script>
<script> 
$(function() {
  $('a[href*=\\#about]').on('click', function(e) {
    e.preventDefault();
    $('html, body').animate({ scrollTop: $($(this).attr('href')).offset().top}, 500, 'linear');
  });
});


  var typedname = new Typed('#name', {
    strings: ['Hi, I am Prasanna...'],
    typeSpeed: 0,
    backSpeed: 0,
    fadeOut: false,
    loop: false,
    showCursor:false,
    startDelay: 100
  });
 var typed2 = new Typed('#app', {
    strings: ['I am a <strong>Grad Student</strong>...', 'I am a <strong>Machine Learning Enthusiast</strong>...', 'I am a <strong>Software Developer</strong>...', 'I am a <strong>anime fan</strong>...'],
    typeSpeed: 40,
    backSpeed: 20,
    fadeOut: false,
    loop: true,
    showCursor:true,
    startDelay:2000
  });
    
</script> 
