# CSS-Specificity
If there are two or more conflicting CSS rules that point to the same element, the browser follows some rules to determine which one is most specific and therefore wins out.


What is Specificity?

If there are two or more conflicting CSS rules that point to the same element, 
the browser follows some rules to determine which one is most specific and therefore wins out.

Think of specificity as a score/rank that determines which style declarations are ultimately 
applied to an element.

The universal selector (*) has low specificity, while ID selectors are highly specific! 

Note: Specificity is a common reason why your CSS-rules don't apply to some elements, 
although you think they should.


Specificity Hierarchy
Every selector has its place in the specificity hierarchy. There are four categories which
 define the specificity level of a selector:

Inline styles - An inline style is attached directly to the element to be styled. Example:
 <h1 style="color: #ffffff;">.

IDs - An ID is a unique identifier for the page elements, such as #navbar.

Classes, attributes and pseudo-classes - This category includes .classes, [attributes] and 
pseudo-classes such as :hover, :focus etc.

Elements and pseudo-elements - This category includes element names and pseudo-elements, 
such as h1, div, :before and :after.

