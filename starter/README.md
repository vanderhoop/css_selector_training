# Get Selective; An Introductory CSS Selector Exercise

The purpose of this exercise is to get novice web developers simple, meaningful repetitions using CSS selectors.

### Directions

__Pre-requisite:__ read [Chris Coyier's excellent, easy-to-understand introduction to CSS Selectors](http://css-tricks.com/how-css-selectors-work/)

__IMPORTANT:__ 
  - This is strictly a CSS exercise, so *don't change the html*. 
  - Additionally, there are pre-written styles for this exercise. Don't alter them, as this exercise was designed for you to work *around* what was already written. Do your work solely in the [`stylesheets/style.css`](stylesheets/style.css) file. 

1. Read [Chris Coyiers introduction to CSS Selectors](http://css-tricks.com/how-css-selectors-work/).
1. Select any and all `h1` tags that might be on the page
  - set the h1's `text-tranform` property to `uppercase`
1. Select any and all anchor (`<a>`) tags on the page
  - remove the underline from the anchor tags by setting their `text-decoration` to `none`
1. Select and and all paragraph tags on the page
  - set the paragraphs' `font-weight` attribute to `bold`
1. Select the div with the class of `green`
  - set its `background-color` attribute to a nice shade of green: `rgb(148, 179, 148)`
  - set its `border` attribute to `5px dashed green`
1. Select all the elements that have the class of `ring`
  - set the rings' `border-color` property to `gray`
1. Select all the elements that have the class of `example`
  - set the example text's `font-style` attribute to `italic`
1. Select the div with the id of "bullseye"
  - set its `background-color` to a deep shade of red: `#D04A41`
1. Use the `:hover` pseudo-selector to make the bullseye's opacity shoot down to `0.5` when hovered over.
1. *Simultaneously* select the `h1` and `h2` tags
  - set the pair's `font-size` to `3em`
1. Select the div that has the two following classes: `target` & `container`
  - set its `background-color` to `#facade`
1. Someone put an innapropriate example for the color yellow into the HTML. We're going to use CSS to make this innapropriate text invisible
  - select the *second* paragraph tag within the div of class `yellow`
    - set its `opacity` to `0.0`
1. Each of the colored boxes has two paragraph tags. Select all of the *first* paragraphs within the colored boxes
  - set all of the first paragraphs' `text-decoration` to `underline`

#### A Picture of Completion

![image](complete.png)

