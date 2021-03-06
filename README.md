# csswizardry-grids.less

A LESS port of [csswizardry-grids](https://github.com/csswizardry/csswizardry-grids) ( originally SASS )

**Simple, fluid, nestable, flexible, Sass-based, responsive grid system.**

* Fully responsive
* Infinitely nestable
* Endless possible combinations
* Simple to understand, human-friendly classes
* Robust
* Simple
* No `.clear` or `.last` classes
* It just _works_

Please see [Responsive grid systems; a solution?](http://csswizardry.com/2013/02/responsive-grid-systems-a-solution/)
for a comprehensive overview of the principles of the grid system.

## Setup

Simply fill in/adjust the relevant variables.

* `@gutter` controls how much space there is between columns.
* `@lap-start` and `@desk-start` tell csswizardry-grids.less when to fire particular
  media queries to service those particular sizes. Note that csswizardry-grids
  works out the ends of any other breakpoints by using these numbers.

## Basic usage

If you are using traditional classes then an example, basic usage might look
like this:

    <div class="grid">
    
        <div class="grid__item  one-whole  lap-one-half  desk-two-thirds">
            ...
        </div>
    
        <div class="grid__item  one-whole  lap-one-half  desk-one-third">
            ...
        </div>
    
    </div>

## Demo

There is a very simple demo which can be found at
[csswizardry.github.com/csswizardry-grids](http://csswizardry.github.com/csswizardry-grids).
