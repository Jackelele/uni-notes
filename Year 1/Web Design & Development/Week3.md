# CSS I

## Content vs Display

* Semantics vs Styling
* Content and Style evolve in different ways and at
different speeds
    * Content tends to be added to or changed over time
    * Style tends to be modified / re-written
* Good principle to split Content and Style
    * HTML -> Markup of the content
    * CSS -> Apply styling to the Markup

## Cascading Style Sheets

* Official standard for styling HTML pages
*  Styles are defined as a list of rules
    * Styles can be defined
    * As an external file (good)
    * In-line as an HTML attribute (generally bad)

# External Style Sheet

* You should always define your page styling in a separate .css file
* Use the ```<link>``` tag to link the stylesheet into your HTML page in the head section.

```<link rel="stylesheet" href="path/to/stylesheet.css"/>```

## HTML Atrributes for CSS

* id attribute
    * Uniquely identifies that element within the page

```<article id="page">...</article>```

* class attribute
    * Attaches one or more class names to the element
    * Class names cannot contain space or the full-stop

```<p class="highlight source">…</article>```

## CSS Rule

<img src="https://elele.team/upload/mEYaKO.png">

## CSS Selectors

* HTML tag selector
    * Selector format: tag-name
    * Example: h1 {...}
* HTML id selector
    * Selector format: #value-of-the-id
    * Example: #title {...}
* Pseudo-Selector
    * Selector format: selector:pseudo-selector()
    * Example: p:first-child() {...}

## CSS Selectors

<img src="https://elele.team/upload/vadXjg.png">

* You can combine selectors to create complex or specific selectors

<img src="https://elele.team/upload/h61DUS.png">


## CSS Property

* All properties use the same structure

```property-name: property-value;```

* Property values format depends on the property
    * Properties allow you to control
    * Fonts
    * Colour
    * Size
    * Margins
    * Positioning
    *  …

## CSS Specificity

* Multiple CSS rules can apply to the same element
```<header class=“red left”></header>```
    * Specificity
    * Defines the order in which they are applied
    * Calculated based on the selector
    * Basic order (increasing specificity)
    * Tag selector
    * Class selector
    * Pseudo-class selector
    * ID selector
    
## Calculating CSS Specificity

<img src="https://elele.team/upload/bmNP8t.png">

## In-line Style

* HTML provides a style attribute
    * Attaches CSS properties to that one element

* AVOID!
    * Any change in styling requires editing the HTML
    * document

