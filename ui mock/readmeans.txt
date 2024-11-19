

html5 semantics =>
header
footer
aside
nav
figure
figcaption
canvas
svg
article
section

2.css selectors:-
ans.CSS selectors are used to "find" (or select) the HTML elements you want to style.
    Simple selectors (select elements based on name, id, class)
    Combinator selectors (select elements based on a specific relationship between them)
    Pseudo-class selectors (select elements based on a certain state)
    Pseudo-elements selectors (select and style a part of an element)
    Attribute selectors (select elements based on an attribute or attribute value)

    The CSS id Selector
    The id selector uses the id attribute of an HTML element to select a specific element.
    The id of an element is unique within a page, so the id selector is used to  select one unique element.
    To select an element with a specific id, write a hash (#) character, followed by the id of the element.

    The CSS class Selector==>
    The class selector selects HTML elements with a specific class attribute.
    To select elements with a specific class, write a period (.) character, followed by the class name.
    The CSS Universal Selector==>
    The universal selector (*) selects all HTML elements on the page.
    The CSS Grouping Selector==>
    The grouping selector selects all the HTML elements with the same style definitions.
    4 types of combinator selector in css==>
    descendant selector (space)==>
    The descendant selector matches all elements that are descendants of a specified element.
    child selector (>) ==>
    The child selector selects all elements that are the children of a specified element.
    adjacent sibling selector (+)==>
    The adjacent sibling selector is used to select an element that is directly after another specific element.
    Sibling elements must have the same parent element, and "adjacent" means "immediately following".

    general sibling selector (~)==>
    The general sibling selector selects all elements that are next siblings of a specified element.
    
    psuedo classes==>
    A pseudo-class is used to define a special state of an element.
    For example, it can be used to:
    Style an element when a user mouses over it
    Style visited and unvisited links differently
    Style an element when it gets focus
    Anchor Pseudo-classes
    :hover pseudo-class
    The :first-child pseudo-class==> matches a specified element that is the first child of another element.
    example of pseudo elements==>
    :active,:checked,:disabled,:empty,:enabled,:link etc

    What are Pseudo-Elements?

    A CSS pseudo-element is used to style specified parts of an element.

    For example, it can be used to:

    Style the first letter, or line, of an element
    Insert content before, or after, the content of an element
    The ::first-letter Pseudo-element

    The ::first-letter pseudo-element is used to add a special style to the first letter of a text.
    examples of psedo-elements are as follows==>
    ::after,::before,::first-letter,::first-line,::marker,::selection

3.positions ==>
static==>
HTML elements are positioned static by default.
Static positioned elements are not affected by the top, bottom, left, and right properties.An element with position: static; is not positioned in any special way; it is always positioned according to the normal flow of the page:

relative==>
An element with position: relative; is positioned relative to its normal position.

Setting the top, right, bottom, and left properties of a relatively-positioned element will cause it to be adjusted away from its normal position. Other content will not be adjusted to fit into any gap left by the element.

absolute==>
An element with position: absolute; is positioned relative to the nearest positioned ancestor (instead of positioned relative to the viewport, like fixed).

However; if an absolute positioned element has no positioned ancestors, it uses the document body, and moves along with page scrolling.

Note: Absolute positioned elements are removed from the normal flow, and can overlap elements.

fixed==>
An element with position: fixed; is positioned relative to the viewport, which means it always stays in the same place even if the page is scrolled. The top, right, bottom, and left properties are used to position the element.

A fixed element does not leave a gap in the page where it would normally have been located.

sticky==>
An element with position: sticky; is positioned based on the user's scroll position.

A sticky element toggles between relative and fixed, depending on the scroll position. It is positioned relative until a given offset position is met in the viewport - then it "sticks" in place (like position:fixed).

4.a.Block-level Elements

A block-level element always starts on a new line, and the browsers automatically add some space (a margin) before and after the element.

A block-level element always takes up the full width available (stretches out to the left and right as far as it can).

examples==>
div, p, ol, ul, nav, main, figure, formatting

b.An inline element does not start on a new line.

An inline element only takes up as much width as necessary.
An inline element cannot contain a block-level element!

example==>
script, label, span, object, i, a, b, strong

5.image alt
The required alt attribute specifies an alternate text for an image, if the image cannot be displayed.

The alt attribute provides alternative information for an image if a user for some reason cannot view it (because of slow connection, an error in the src attribute, or if the user uses a screen reader).

6.box-sizing
The box-sizing property allows us to include the padding and border in an element's total width and height.
7.cell spacing vs cell padding
cell padding:-
Cell padding is the space between the cell edges and the cell content.
cell spacing:-
Cell spacing is the space between each cell.

8.new features in html 5
ans. audio tags, video tags, vector graphics, header, footer,
figure and figcaption, nav tag,email attribute,local storage,session storage


9.what are tags vs elements
ans. Tags are used to define the beginning and end of an element, while elements consist of the opening tag, content, and closing tag. In other words, tags are the markers that define where an element begins and ends, while elements encompass the entire structure including the content contained within the tags.

10.void elements
A void element is an element in HTML that cannot have any child nodes (i.e., nested elements or text nodes). Void elements only have a start tag; end tags must not be specified for void elements.
examples of void tags ==>
    <area>
    <base>
    <br>
    <col>
    <embed>
    <hr>
    <img>
    <input>

11.interval css vs external vs inline css
ans. External CSS==>
With an external style sheet, you can change the look of an entire website by changing just one file!
Each HTML page must include a reference to the external style sheet file inside the <link> element, inside the head section.  
An external style sheet can be written in any text editor, and must be saved with a .css extension.
The external .css file should not contain any HTML tags.  

   internal css==>

An internal style sheet may be used if one single HTML page has a unique style.
The internal style is defined inside the <style> element, inside the head section.

  inline css==>  An inline style may be used to apply a unique style for a single element.
To use inline styles, add the style attribute to the relevant element. The style attribute can contain any CSS property.

22. id vs class
ids are unique we can give only one id into a single element and can apply to different elements same ids.
but we cannot apply multiple ids to same element

css3 new properties ==>
transition,animation,transform,flex-box,css grids,opacity,text-shadow.

viewport and media query==>
Media queries are used to have different css for different devices its like the if condition for different devices. Viewport meta tag is to set tell the device to take the width according to this tag. Its like a reset for devices if its not used device will adjust the layout according to its default settings.


/// questions asked in mock 
1. block vs inline
2.none vs hidden
ans. visibility:hidden hides the element, but it still takes up space in the layout. display:none removes the element from the document. It does not take up any space.
3.position
4.css3 new features
ans. gradient effects, shadow effects, flexbox, transitions and animations, new selectors, media query , rounded corners, opacity etc
5.margin vs padding
ans. Clears an area outside the border. The margin is transparent
     Negative values are allowed in margin.!!!!
     margin has 4 values= top,right,bottom ,left
     margin has 3 values = top, right-left,bottom
     margin has 2 values= top-bottom, right-left
     margin has 1 values then from all sides
     You can set the margin property to auto to horizontally center the element within its container.

     padding=The CSS padding properties are used to generate space around an element's content, inside of any defined borders
     Negative values are not allowed in padding!!!


6.float
The float property specifies whether an element should float to the left, right, or not at all.
Absolutely positioned elements ignore the float property!
Elements next to a floating element will flow around it. To avoid this, use the clear property
float: none|left|right|initial|inherit;
7.css selectors
CSS selectors are used to "find" (or select) the HTML elements you want to style.

    Simple selectors (select elements based on name, id An id name cannot start with a number!, class)
    Combinator selectors (select elements based on a specific relationship between them)
    Pseudo-class selectors (select elements based on a certain state)
    Pseudo-elements selectors (select and style a part of an element)
    Attribute selectors (select elements based on an attribute or attribute value)

    A CSS selector can contain more than one simple selector. Between the simple selectors, we can include a combinator.

    There are four different combinators in CSS:

    descendant selector (space)
    child selector (>)
    adjacent sibling selector (+)
    general sibling selector (~)

    The adjacent sibling selector is used to select an element that is directly after another specific element.

    Sibling elements must have the same parent element, and "adjacent" means "immediately following".

    pseudo class selector
    :active 	a:active 	Selects the active link
:checked 	input:checked 	Selects every checked <input> element
:disabled 	input:disabled 	Selects every disabled <input> element
:empty 	p:empty 	Selects every <p> element that has no children
:enabled

pseudo class element
::after 	p::after 	Insert content after every <p> element
::before 	p::before 	Insert content before every <p> element
::first-letter 	p::first-letter 	Selects the first letter of every <p> element
::first-line 	p::first-line 	Selects the first line of every <p> element
::marker 	::marker 	Selects the markers of list items
::selection

The double colon replaced the single-colon notation for pseudo-elements in CSS3. This was an attempt from W3C to distinguish between pseudo-classes and pseudo-elements.
[attribute] 	[target] 	Selects all elements with a target attribute
[attribute=value] 	[target="_blank"] 	Selects all elements with target="_blank"
[attribute~=value] 	[title~="flower"] 	Selects all elements with a title attribute that contains a space-separated list of words, one of which is "flower"
[attribute|=value] 	[lang|="en"] 	Selects all elements with a lang attribute value starting with "en"
[attribute^=value] 	a[href^="https"] 	Selects all <a> elements with a href attribute value starting with "https"
[attribute$=value] 	a[href$=".pdf"] 	Selects all <a> elements with a href attribute value ending with ".pdf"
[attribute*=value]





8.id vs class
9.types of css
10.html5 new tags
ans.audio, video, header, footer, aside, nav, command, details, datalist, time, fig, figcaption.
11.square to circle
12.viewport & media


 	







