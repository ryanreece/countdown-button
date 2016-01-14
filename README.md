# Behold, the countdown button
The countdown button is a simple html button that when clicked, will replace
its contents via pseudo elements to countdown 3-2-1 and then display a stop
icon.

## Usage
* When the button is clicked, an active class must be added to the button element to initiate the countdown and radar animation.
* When the countdown is finished and recording starts, a finish class must be added to the button element to replace the big radar animation.

## Variables
Several variables can be defined to control the look and feel of the button.
They are outlined here.
`$button-size` Defines the size of the button.
`$button-color` Defines the color of the button background.
`$radar-size-increase` The size of the radar animation is based on the button's size plus this value.
`$radar-size` Calculated based on the `$button-size` and `$radar-size-increase`.
`$radar-color` The color of the radar animation. Since it uses opacity, keeping this the same as the `$button-color` looks best.
`$font-scale-size` The size of the font in relation to the button size. Default is 0.5.
`$font-size` The calculated size of the countdown text and pause icon.

## SASS Commands
`sass style.scss:style.css`
`sass --watch style.scss:style.css`