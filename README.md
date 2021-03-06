# jQuery AnySlider 1.5.2
AnySlider is a jQuery plugin which allows you to create a slider for any kind of HTML content.

http://jonathanwilsson.com/anyslider/

## Development
The current beta/unstable version can be found in the "develop" branch. Not recommended for production sites.

Please send all pull requests to the "develop" branch as well.

## Features
* Continuous autoplay.
* Custom easings.
* Fade or slide transition.
* Highly customizable appearance and lots of options.
* Keyboard navigation.
* Multiple sliders on one page supported.
* Navigation bullets.
* No CSS or HTML-structure enforced, you're 100% in charge.
* Slide any content or using any element. HTML, images and YouTube clips. Or mix &lt;div&gt;s, &lt;span&gt;s and &lt;section&gt;s. AnySlider doesn't care.
* Small, 1.4 kB minified and gzipped.
* Supported in all major browsers.
* Touch support.

## Options
* afterChange (Default function ()) function A function to call after each slide change.
* afterSetup (Default function ()) function A function to call after the slider has been setup.
* animation (Default slide") string Transition, one of the following:
	* fade Fades between slides.
	* slide A sliding aniamtion between slides.
* beforeChange (Default function ()) function A function to call before each slide change.
* bullets (Default true) boolean Whether or not to display navigation bullets. Setting this to false will prevent the bullets from being drawn at all.
* delay (Default 300) integer The delay (in milliseconds) between two fading slides.
* easing (Default "swing") string Name of a custom easing. For example via the jQuery Easing plugin. Only used when "animation" is "slide" or "fadeSlide".
* interval (Default 5000) integer Number of milliseconds to pause on each slide. Setting this option to 0 will disable autoplay.
* keyboardNav (Default true) boolean Allow for keyboard navigation using the left and right arrow keys.
* nextLabel (Default "Next slide") string Label for the next button.
* pauseOnHover (Default true) boolean Pause the autoplay on hover?
* prevLabel (Default "Previous slide") string Label for the previous button.
* responsive (Default true) boolean Whether to enable responsive support.
* rtl (Default false) boolean Whether to slide right-to-left instead of left-to-right when autoplay is enabled.
* showControls (Default true) boolean Show/hide controls. Setting this to false will prevent the controls from being drawn at all.
* speed (Default 400) int The animation time in milliseconds. Setting this option to 0 will disable animation.
* startSlide (Default 1) int Number of the starting slide. Starting from 1.
* touch (Default true) boolean Whether to enable the ability to swipe between slides.

Minimum required jQuery version is 1.5.0.

## License
Free to use and abuse under the [MIT license](http://www.opensource.org/licenses/mit-license.php).

## Copyright
Copyright 2011-2013 Jonathan Wilsson.