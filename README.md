# jQuery Domino Effect

A simple jQuery plugin that generates a 'domino' effect on selected elements by fading them in one at a time, without using nested callbacks.

## Usage

Include the jquery.domino.js script
`<script src="jquery.domino.js"></script>`

Call the `domino` function on your selectors.
`$('.items').domino();`

##Options

Currently only one option is available, the delay between items showing. Default is 400ms.

`$('.items').domino({
	//change to 1 second
	speed: 1000
});`