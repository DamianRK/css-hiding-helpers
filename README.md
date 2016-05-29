# Hiding helper classes for responsive

## Requirements
	
Working perfectly with: https://github.com/DamianRK/magento-gulp-sass
Requires:
* bp() mixin
* $bp-xsmall, $bp-small, $bp-medium, $bp-large, $bp-xlarge variables

## Usage

Class name      | Description           | Default range
----------------|-----------------------|--------------------
.hide-xsmall    | Hide on $bp-xsmall    | x <= 479px
.hide-small     | Hide on $bp-small     | 479px < x <= 599px 
.hide-medium    | Hide on $bp-medium    | 599px < x <= 770px 
.hide-large     | Hide on $bp-large     | 770px < x <= 979px 
.hide-xlarge    | Hide on $bp-xlarge    | 979px < x 
                |                       |  
.hide-mobile    | Hide on $bp-mobile    | x <= 599px
.hide-tablet    | Hide on $bp-tablet    | 599px < x <= 979px 
.hide-desktop   | Hide on $bp-desktop   | 979px < x 


### Authors ###

* Damian Bogdanowicz <damian.bogdanowicz@gmail.com>
* [http://dbogdanowicz.pl](http://dbogdanowicz.pl)
