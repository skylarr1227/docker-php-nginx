# Zillow + PHP and AJAX

<a href="http://mikeparda.com/zillow" target="_blank">Live Demo Here</a>

This is a simple example of using the Zillow web service API with PHP and AJAX.  Other stuff used: Google Maps API (for autocomplete), Bootstrap (with a Bootswatch theme), Font Awesome, and jQuery BlockUI.  

The meat of the PHP is in the Zillow.class.php file if that's what your looking for (I was when I made this), if you are looking for a starting point how to connect to the Zillow web service API and start getting info back right away, check it out.

Everything you need (jQuery, Bootstrap, BlockUI, etc) comes with it, you just need a Google Maps API key and a Zillow Web Service API Key, see below for where to put them

# How to get a Zillow API Key:
Read more about the Zillow web service API and how to get a key (its free):
http://www.zillow.com/howto/api/APIOverview.htm

# Where to put your keys:
Google Maps API Key: Line 78 of 'home.php'
<br>
Zillow API Key: Line 16 of 'Zillow.class.php'

Simple and maybe a building block to get you started, feel free to contribute to improving it's capabilities.  pardamike@gmail.com

# Credits/External Resources Used:

Bootstrap 3.3.6
<br>
jQuery 2.2.2
<br>
jQuery Block UI
<br>
Font Awesome 4.5
<br>
Bootswatch Flatly Theme
<br>
Google Maps
<br>
Zillow Web Service API
