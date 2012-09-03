# Distance Js

## Description
jQuery Calculate Distance between 2 locations

## Usage

### Require
	* >= jQuery 1.4

### How to use
		<script type="text/javascript" src="distance.js"></script>

		<script type="text/javascript">
			Distance.init();
		</script>

specify 3 attributes to the parent elements ([data-with-distance] optional, data-lat, data-lng) and inside the parent attribute put the element class=distance

		<li data-with-distance="true" data-lat="52.4800" data-lng="-1.9100">
			Distance from your location to Birmingham about : 	<span class="distance"></span>
		</li>
