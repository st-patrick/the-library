# the-library
perfect frontend library

translating popular frontend patterns into reusable bootstrap combos

common patterns, components, etc...
kind of like tailwind but instead of standardizing details, it standardizes combinations

aka "the familiar" ... cause it's things that are so common now, you feel familiar about them so most designs implement some variation of it 

"the rough cut" which also often is the most work that is automatable. Spacing, color, images, ... require "feeling"


Basically shorthand codes would be good that translate that indented overview into bootstrap
most easily CTA -> <button{...}


feature ideas:
+ browse templates by outline description
+ brose templates visually
+ "layover" function. Take a screenshot and easily overlay it to confirm correctness or find issues. Pauspapier
+ make it framework independent
+ find quickest implementation as in page speed / responsiveness


MVP:
+ a compiler that turns the highly abstract indented syntax into bootstrap HTML as a starting point


Demonstrate use-cases:
+ show how one would describe a design in this high-level meta-language stuff and see it being converted into hackable bootstrap code and then on top of that discover similar designs and what flavors to use, ...
+ make it load and animate faster than some of the "originals"


Problems:
+ how would one even browse the library? Visually? Or searching? Or both?
	Browsing templates... definitely visual
	Even for me it's hard to scroll what is starting to feel seemingly endless
	
Implementation ideas:
+ start with simple javascript functions like Slalom(3, LeftRight) and later create a "real" compiler
+ reduce to 2 breakpoints (from 5 of original bootstrap)
+ createTemplate(nav=1, header=1, content=6, wowserConcentration=0.5) 
+ simple randomizer that uses existing code and rolls the dice on order, etc..
	and also randomizes across other variables
		trendy fonts
			e.g. from google fonts
		positioning of text inside full size image
		font / heading sizes
		actual copy text with e.g. chatGPT
		color themes = palettes (e.g. from khroma)
		placeholder images
			mockups
			cc0 art
			photos
	maaaybe in the future randomize across trickier things
		striped bg rhythm
		animation of content
		responsive behaviour
		

other:
+ use it to create a bazillion templates simply by mixing and matching sections and re-theming them.

samples of flavor:
+ obvious patterns like here but lots of brand flavor
	+ https://www.starbucks.com/
	+ https://medium.com/about 
	+ https://cook.blueapron.com/
