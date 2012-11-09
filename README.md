PSD Checklist
============

Every PSD needs to be prepped for development. This is a starting point.


Checklist for Outputting PSD's

	[] All layers are either in named folders (for sections) or have names themselves
	[] Blending modes have been removed or merged
	[] Notes have been made inside the document
	[] Notes have been attached next to the document in a .txt file
	[] There is a final.jpg, a flattened final.jpg, a logo.ai or logo.svg file and a design_notes.txt file in the artwork directory
	[] Font names have been included in notes
	[] Relevant logo has been included in vector format
	[] Unused layers have been deleted
	[] Content pieces are labeled in a sane way (slide 1, slide 2; ad 1, ad 2)
	[] Different "views" have their own folders, so that they don't look like unused layers you forgot to delete
	[] Background image has been optimized for web.(*)
	[] Used icon fonts where possible (you can use some layer styles with these)
	[] Used WebFonts where possible (you can use some layer styles with these)
	[] Font sizes are specified in pixels (not pts)
	[] Design is scaled to actual size in pixels
	[] Used some sort of grid or repeatable size system with guides
	[] Color mode of all elements, including vectors, is RGB (not CMYK)
	[] Two or less web fonts are being loaded
	[] No more than 4 total webfont weights are being used
	[] Which Frame/theme are you using? Did you work from another design to get to this one?
		Note: the reason this one is important is because there may be a LOT of reusable code in the other project.

	(*)This means different things for different projects, but generally anything larger than 960x700 for a background image is too big; background images should usually be able to repeat unless they are actually designed to appear only once on the page. Consider what happens beyond the bounds of the document; if it's not seamless but the texture goes to the edge, what happens outside of that? Make sure you talk to the front-end dev that will work on this project so you can discuss the size of the images in general.

Optional (if you want control over these things):

	[] Added button, link, iconand other hoverable item (pictures, for instance) states (hover, clicking, visited previously, and )
	[] Specific variants of fonts that may not be on Google Fonts or typekit have been included
	[] Fontkit provider is specified if multiple providers exist for this font.
		[] Google Web Fonts		[ ] FontSquirrel kit 	[] Typekit
	[] Any specific interaction elements are outlined in notes


============================================================================
Additional Notes (Why any of the checkboxes above are not checked) Go Below:
============================================================================


============================================================================
============================================================================

THE FINAL ITEM: (not to be checked until everything above is checked)

	[ ] Design has been approved, and is ready for development.
		It has been shared via Dropbox with: [Name of front-end Dev, email]