# Create URL Title #

This plugin takes the tag data (the text in between the tag pair) and outputs a url title (strips spaces and non-alphanumeric characters) from it.

## Usage
	{exp:create_url_title}
	
	The brown cow jumps over the moon.
	
	{/exp:create_url_title}

	the_brown_cow_jumps_over_the_moon

## Parameters

* separator - the word separator, accepts "-", "_", or "dash", if not specified, uses your default word separator
* lowercase - set to no to prevent conversion to all lowercase