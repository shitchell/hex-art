# hexlabs css art

this is my entry into the 2021 hexlabs css art competition 😊  
[github.io/hex-art](https://shitchell.github.io/hex-art/)

while fairly simple, my goal was to create a page that uses *no html*. there
are only two HTML tags used--the opening and closing `<style>` and `</style>`
tags required to add css to the page.

## how it works

all modern browsers will create an `<html>`, `<head>`, and `<body>` tag when
those are missing from the page. this allows me, in spite of not explicitly
including any elements on my page, to make use of 4 css pseudo-elements:
`html::before`, `html::after`, `body::before`, and `body::after`. i use this to
add 2 hexagons and 2 words to the page.

the final addition to the page for stylistic effect is the background. since
this is meant to be artful, a radial gradient with a slow 20s animation was used
to produce a subtle contrast with the hexlabs homages.

## credit where due

this page uses the hexlabs font as found on [hexlabs.org](https://hexlabs.org/)
and the GT primary colors as described at
[brand.gatech.edu/our-look/colors](https://brand.gatech.edu/our-look/colors).
