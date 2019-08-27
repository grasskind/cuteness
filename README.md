## Happy Birthday!
<head>
  <link rel = "stylesheet" type = "text/css" href = "style.css" />
</head>

<div class="bss-slides">
    <figure>
        <img src="1.jpg" width="100%" />
    </figure>
    <figure>
        <img src="2.jpg" width="100%" />
    </figure>
    <figure>
        <img src="3.jpg" width="100%" /> 
    </figure>

</div>
<script type="text/javascript" src="better-simple-slideshow.js"></script>
<script>
  var opts = {
            // default selector is "figure"
            selector: ".my-selector",
            //auto-advancing slides? accepts boolean (true/false) or object
            auto : { 
                // speed to advance slides at. accepts number of milliseconds
                speed : 1000, 
                // pause advancing on mouseover? accepts boolean
                pauseOnHover : true 
            },
            // show fullscreen toggle? accepts boolean
            fullScreen : false, 
            // support swiping on touch devices? accepts boolean, requires hammer.js
            swipe : true 
        };
  makeBSS('.bss-slides', opts);
</script>
