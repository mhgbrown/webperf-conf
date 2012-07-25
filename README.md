# Web Performance Lab (Configuration)
The accompanying configuration for the Web Performance Lab site.

## Rule 3: Add an Expires Header

### Changes
* **Add a far future expires header to certain assets**

	Adjusted the Apache configuration to add a +10 years expires header to assets with the following formats: ico|xml, jpeg, png, gif, js, css, swf

## Rule 4: Gzip Components

### Changes
* **Gzip certain assets**

	Adjusted the Apache configuration to gzip assets of the follow formats: html, plain text, css, js, xml, swf
