# Summary of Markdown

## Italics and Bold 
To make a phrase _Italics_, you can surround words with underscore (_). For examples, `_this_` would look like _this_.

To make a phrase **Bold**, surround words with two asterisks (\*\*). For example, `**this**` would look like **this**.

You can use `bold and italics` at the same time. For example, \*\*\_this\_\*\* would look like **_this_**.

## Headers
There are 6 types of Headers. To make a header in Markdown, put \# in the front the phrase. **Attention**: there should be a blank space between \# and the phrase. The number of \# represents the size of the Headers. For example \# is Header one, the largest one. \#\# is Header two, the second largest one.


## Links
* **Inline link**  
 Put the context in `[ ]` and link address in `( )` follows. This will generate a link for the context.   
 For example \[google\]\(www.google.com\) will looks like this: [google](www.google.com).

 * **Referrence link**  
 It is a Similar idea with inline link. The link address will be used like a variable. If you want to \[link A\] represent a link. You write \[link A\]: www.tudelft.nl. Then you can use \[link A\] as a variable to represent that link.
 For example, \[TU Delft\]\[link A\] will look like this [TU Delft][link A].  
An advantage of the reference link style is that multiple links to the same place only need to be updated once

## Images
Image of syntax is nearly the same as links, both inline link and reference link. You only need to put ! in the front.   
For example,\!\[cat\]\(https://ichef.bbci.co.uk/news/660/cpsprodpb/12A9B/production/_111434467_gettyimages-1143489763.jpg\) will display a image of cat  
![cat](https://ichef.bbci.co.uk/news/660/cpsprodpb/12A9B/production/_111434467_gettyimages-1143489763.jpg)

## Blockquotes
A blockquote is a sentence or paragraph that's been specially formatted to draw attention to the reader. You can use it for a quote from another source.

To use block quotes, put this simple \> (greater than) in front of the phrase.

\> Long Long ago,there is a temple upon the monutain  
This will look like
> Long Long ago,there is a temple upon the monutain.

If you want to use bolckquotes in multiple lines. Use \> in each line, even its a blank line.

\> Long Long ago,there is a \*\*temple\*\* upon the monutain.  
\>  
\> An old man lives in the temple.    
Such texts will display like 
> Long Long ago,there is a **temple** upon the monutain .
>
> An old man lives in the temple.

Italics, bold and links all can be used in blcokquotes.

## Lists
There are two types of lists, unordered and ordered.  
 To create an unordered list, you'll want to preface each item in the list with an asterisk ( * ).  
 \* Milk  
 \* Water   
 \* Tea   
 This will look like
 * Milk  
 * Water   
 * Tea 

To create an ordered list, just preface with numbers.  
\1. Milk  
\2. Water  
\3. Tea  
will display as

1. Milk
2. Water
3. Tea

Nested list is also avaiable. Just precede one more sapce for the nested list.
* Drink
  1. Cola
  2. Tea
  3. Cocktail
* Food
  * Rice
  * Noodle
* Fruit
  * Apple
  * Banana

## Paragraphs
There are two ways of formating paragraphs: **soft break** and **hard break**.  
Two blank sapces at the end of a line will have a soft break.

This is line one.··  
This is line two.··  

It will displace as: (· represents blank space)

This is line one.  
This is line two.

Hard break is an empty line.

This is line one.  
\ empty line  
This is line two.

It will look as 

This is line one.  
 
This is line two.

Reference
1. [markdowntutorial](https://www.markdowntutorial.com/lesson/1/)
2. [markdownguide](https://www.markdownguide.org/)
