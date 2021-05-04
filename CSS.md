# CSS
#### I've read about CSS (cascading style sheet).
#### I want to share breifly what is css.

## What Is The CSS?

* ####  CSS is the language we use to style a Web page.
* CSS stands for Cascading Style Sheets.
* CSS describes how HTML elements are to be displayed on screen, paper, or in other media.
* CSS saves a lot of work. It can control the layout of multiple web pages all at once.
* External stylesheets are stored in CSS files.

## Why To Use CSS?
  * CSS is used to define styles for your web pages, including the design, layout and variations in display for different devices and screen sizes.

## CSS Solved a Big Problem
* HTML was NEVER intended to contain tags for formatting a web page!

* HTML was created to describe the content of a web page, like:

`<h1>This is a heading</h1> `

`<p>This is a paragraph.</p>`

    When tags like `<font>`, and color attributes were added to the HTML 3.2 specification, it started a nightmare for web developers. Development of large websites, where fonts and color information were added to every single page, became a long and expensive process.

#### To solve this problem, the World Wide Web Consortium (W3C) created CSS.

#### CSS removed the style formatting from the HTML page!

# How To Add CSS
   * When a browser reads a style sheet, it will format the HTML document according to the information in the style sheet.

# Three Ways to Insert CSS
#### There are three ways of inserting a style sheet:

  * External CSS
  * Internal CSS
  * Inline CSS

# External CSS
* With an external style sheet, you can change the look of an entire website by changing just one file!

* Each HTML page must include a reference to the external style sheet file inside the <link> element, inside the head section

* An external style sheet can be written in any text editor, and must be saved with a .css extension.

* The external .css file should not contain any HTML tags.

```<link rel="stylesheet" href="mystyle.css">```

# Internal CSS
* An internal style sheet may be used if one single HTML page has a unique style.

* The internal style is defined inside the <style> element, inside the head section.

```<style>
body {
  background-color: linen;
}

h1 {
  color: maroon;
  margin-left: 40px;
}
</style>
```
# Inline CSS

* An inline style may be used to apply a unique style for a single element.

* To use inline styles, add the style attribute to the relevant element. The style attribute can contain any CSS property.

```<h1 style="color:blue;text-align:center;">This is a heading</h1>```.

# Multiple Style Sheets

  * If some properties have been defined for the same selector (element) in different style sheets, the value from the last read style sheet will be used. 


# SS color Property

Example
Set the text-color for different elements:
```
body {
  color: red;
}

h1 {
  color: #00ff00;
}

p.ex {
  color: rgb(0,0,255);
}
```
### Definition and Usage
* The color property specifies the color of text.

[here](https://www.w3schools.com/cssref/) you can found css refrences.

# CSS Tools: Reset CSS

The goal of a reset stylesheet is to reduce browser inconsistencies in things like default line heights, margins and font sizes of headings, and so on. The general reasoning behind this was discussed in a May 2007 post, if you're interested. Reset styles quite often appear in CSS frameworks, and the original "meyerweb reset" found its way into Blueprint, among others.