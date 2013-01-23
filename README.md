PSD Checklist
============

Every PSD needs to be prepped for development. This is a starting point.


# Checklist for Outputting PSD's

## If this design supposed to be responsive: (preferred)

	[] Different width breakpoints are defined, and different layers or PSDs associated with those breakpoints are included
	[] Behavioral changes for each breakpoint are noted in a "notes" layer
	[] The widths and heights used take into consideration the devices that are commonly used at these breakpoints (i.e. below 480w is usually touch-based mobile with limited height, 500w-1000w is tablets and laptops, above 1000 is usually desktops/laptops)
	[] Information flow is not changed significantly; style of elements is the primary difference
	-OR-
	[] The mobile version of this site is completely separate and should be hosted on a different subdomain

## EMAIL:

_Note: these guidelines override all guidelines above and below. HTML emails are wonky, and will be for a long time._
	
	[] Design does not include interactive elements other than hovering and links
	[] Primary content portions of design are implemented with system fonts
	[] Width of all content does not exceed 600px
	[] Transparency isn't used
	[] There are no "navigation" elements
	[] As few images are used as possible, and the design is readable without them

## ALL DESIGNS:

	[] All layers are either in named folders (for sections) or have names themselves
	[] Blending modes have been removed or merged
	[] Dynamic elements are not using blending modes
	[] Notes have been made inside the document in a "notes" layer
	-OR-
	[] Notes have been attached next to the document in a .txt file
	[] There is a final.jpg, a flattened final.jpg, a logo.ai or logo.svg file and a design_notes.txt file in the artwork directory
	[] Font names and used weights have been included in notes
	[] Relevant logo has been included in _vector_ format
	[] Unused layers have been deleted
	[] Content pieces are labeled in a sane way (slide 1, slide 2; ad 1, ad 2, Header, Nav, P)
	[] Different "views" have their own folders, so that they don't look like unused layers you forgot to delete. Use a naming structure like "VIEW: Home Page; VIEW: About Page; VIEW: Single Blog Post" to easily identify these different views. If there are shared elements, put them in a shared folder.
	[] Background image has been optimized for web.(*)
	[] Used icon fonts where possible
	[] Used WebFonts where possible
	[] Font sizes can be fluid (this is important for responsive designs)
	[] Design is scaled to actual size in pixels (if responsive, this applies only to breakpoints)
	[] Used some sort of grid or repeatable size system with guides; spacing and margin are uniform
	[] Color mode of all elements, including vectors, is RGB (not CMYK)
	[] Four or less web fonts are being loaded (This includes styles, as they are loaded as their own font!)
	[] Which Frame/theme are you using? Did you work from another design to get to this one?
		Note: the reason this one is important is because there may be a LOT of reusable code in the other project.
	[] This design has been reviewed for feasability on the web

	(*)This means different things for different projects, but generally anything larger than 960x700 for a background image is too much of a load for mobile devices; background images should usually be able to repeat unless they are actually designed to appear only once on the page. Consider what happens beyond the bounds of the document; if it's not seamless but the texture goes to the edge, what happens outside of that? Make sure you talk to the front-end dev that will work on this project so you can discuss the size of the images in general.

## Optional (if you want control over these things):

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