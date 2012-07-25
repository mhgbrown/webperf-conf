# Web Performance Lab (Configuration)
The accompanying configuration for the Web Performance Lab site.

## Rule 3: Add an Expires Header

### Changes
* **Add a far future expires header to certain assets**

	Adjusted the Apache configuration to add a +10 years expires header to assets with the following formats: ico|xml, jpeg, png, gif, js, css, swf. This reduces the amount of subsequent requests that need to occur because the user agent can serve fresh files from its cache without performing a conditional get request.

## Rule 4: Gzip Components

### Changes
* **Gzip certain assets**

	Adjusted the Apache configuration to gzip assets of the follow formats: html, plain text, css, js, xml. Care was taken to not gzip components that were already in a compressed format like jpegs and pngs. Compression may make these files larger than they originally are.
