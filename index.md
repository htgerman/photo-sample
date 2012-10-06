<div>
    <head_place>
        <meta http-equiv="X-UA-Compatible" content="IE=edge,chrome=1">
        <meta name="viewport" content="width=device-width, initial-scale=1, maximum-scale=1">
        <link rel="stylesheet" href="css/iview.css" />
        <link rel="stylesheet" href="css/skin 4/style.css" />
        <script type="text/javascript" src="js/iview.js"></script>
        <script type="text/javascript" src="js/jquery.easing.js"></script>
        <script type="text/javascript" src="js/raphael-min.js"></script>
        <script>
                    $(document).ready(function(){
                        $('#iview').iView({
                            pauseTime: 7000,
                            pauseOnHover: true,
                            directionNavHoverOpacity: 0,
                            timer: "Bar",
                            timerDiameter: "50%",
                            timerPadding: 0,
                            timerStroke: 7,
                            timerBarStroke: 0,
                            timerColor: "#FFF",
                            timerPosition: "bottom-right"

                        });
                    });
                </script>
    </head_place>
    <div class="iviewcontainer">
		<div id="iview">
			<div data-iview:image="photos/slide1.jpg" data-iview:transition="slice-top-fade,slice-right-fade">
				<div class="iview-caption caption1" data-x="80" data-y="200">iView<sup>&trade;</sup></div>
				<div class="iview-caption" data-x="80" data-y="275" data-transition="wipeRight">Made to measure flamenco fashion</div>
				<div class="iview-caption" data-x="254" data-y="320" data-transition="wipeLeft"><i>from Granada, Spain</i></div>
			</div>

			<div data-iview:image="photos/slide2.jpg" data-iview:transition="zigzag-drop-top,zigzag-drop-bottom" data-iview:pausetime="3000">
				<div class="iview-caption caption5" data-x="60" data-y="280" data-transition="wipeDown">Captions can be positioned and resized freely</div>
				<div class="iview-caption caption6" data-x="300" data-y="350" data-transition="wipeUp"><a href="#">Example URL-link</a></div>
			</div>

			<div data-iview:image="photos/slide3.jpg">
				<div class="iview-caption caption4" data-x="50" data-y="80" data-width="312" data-transition="fade">Some of iView's Options:</div>
				<div class="iview-caption blackcaption" data-x="50" data-y="135" data-transition="wipeLeft" data-easing="easeInOutElastic">Touch swipe for iOS and Android devices</div>
				<div class="iview-caption blackcaption" data-x="50" data-y="172" data-transition="wipeLeft" data-easing="easeInOutElastic">Image And Thumbs Fully Resizable</div>
				<div class="iview-caption blackcaption" data-x="50" data-y="209" data-transition="wipeLeft" data-easing="easeInOutElastic">Customizable Transition Effect</div>
				<div class="iview-caption blackcaption" data-x="50" data-y="246" data-transition="wipeLeft" data-easing="easeInOutElastic">Freely Positionable and Stylable Captions</div>
				<div class="iview-caption blackcaption" data-x="50" data-y="283" data-transition="wipeLeft" data-easing="easeInOutElastic">Cross Browser Compatibility!</div>
			</div>

			<div data-iview:image="photos/slide4.jpg">
				<div class="iview-caption caption7" data-x="0" data-y="0" data-width="180" data-transition="wipeRight"><h3>The Responsive Caption</h3>This is the product that you all have been waiting for! Customize this slider with just a little HTML and CSS to your very needs. Give each slider some captions to transport your message. All in all it works on every browser (including IE6 / 7 / 8) and on iOS and Android devices!</div>
			</div>

            <div data-iview:image="photos/slide5.jpg">
				<div class="iview-caption caption7" data-x="0" data-y="0" data-width="180" data-transition="wipeRight"><h3>Bata de Cola</h3>Made to your measurements from a large variety of colours and materials to ensure you enjoy your bata de cola course or make an impression on stage.</div>
			</div>

			<div data-iview:image="photos/slide6.jpg">
				<div class="iview-caption caption5" data-x="60" data-y="150" data-transition="wipeLeft">Elastic practice skirts</div>
				<div class="iview-caption caption6" data-x="160" data-y="230" data-transition="wipeRight">Get Yours Now!</div>
			</div>
		</div>
    </div>
</div>

<span data-lift="if?extra_true=has_blog">Welcome to my blog.  Here are my most recent blog posts:</span>

<div data-lift="if?extra_true=has_blog">
      <div data-lift="blog.simple"></div>
</div>

[title: Home]: /