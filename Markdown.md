# **Markdown Instruction Document**
## *What is Markdown?*
Markdown is a simple form of text that non programmers can write that is easy to read and can be converted directly to HTML. 
You can write it once and export it anywhere. It uses very simple formatting syntax and it is simpler than HTML. 
It also doesn't have all of the menus associated with most text editing programs. To format text, Markdown uses punctuation
and characters you're already familiar with such as; 
- Hashtags, 
- Asterisk, 
- Minus' or plus' etc. 

## *What is Markdown used for? Why?*
Markdown can be used to format headers, emphasis, and lists, and to add images and links. The concept is to produce files that are as simple to read as plain text, but that have everything you require to create HTML to distribute on the web. This brings us to the next part of Markdown. Markdown is also a text processor, whereby it takes Markdown text input and gives out correct HTML output.

## *Markdown Syntax*
### *Headings*
This is how you create heading 1 and 2 using Markdown:
```
# This is Heading 1
## This is Heading 2
```
And this is the rendered result:
# This is a Heading 1
## This is a Heading 2
Escentically to create headings you simply put the coresponding number of hashs for the level of the heading in front of each line you want to be a heading. However there is an alternative method:
```
This is also Heading 1
======================
This is also Heading 2
----------------------
```
And this renders the results:

This is also Heading 1
======================
This is also Heading 2
----------------------
For this second method you replace the hashs with equals symbols for heading 1 or dashs for heading 2 which aesthetically act as an underliner which promotes the text above to headings.

### *Lists*
You can make a list by using asterisks, minus' or plus character, however the only thing to look out for it to ensure that you use the same character consistently within the list. You have to enter the space bar after each character. To create an ordered list you begin with the number and then use a full stop or a bracket  ')' and a space. If you didn't want to start a list then you can backslash to escape. 
``` 
* - Asterisk character 
+ - Plus character 
- - Minus character 
1. - Number with full stop 
) - Bracket and space 
\ - Backslash to escape 
```
An example of a list is: 
```
1. Orange 
2. Apple
3. Strawberry 
4. Banana 
5. Grape
```

### *Block quotes*

A block quote is a quotation in a text document that is away from the main text as a paragraph. Each time you use > you are writing a paragraph.

> #### Blockquoted header
>
> This is block quoted text.
>
> Here is the more quoted text.
> 

Here is an example of what it would look like:
```
> #### Blockquoted header
>
> This is block quoted text.
>
> Here is the more quoted text.
> 
```
#Code block

~~~~
This is a 
piece of code 
in a block
~~~~

```
This too
```

To do the above: 

\~~~~
This is a 
piece of code 
in a block
\~~~~

\```
This too
\```
To show code, you can also use return and indent(four spaces):

	It will display every character typed in it, like this: !><@
##Images##
To show an image you use:

	![](file/path)
>An example of this would be:
![](http://markdown-here.com/img/logo-2015/austin.png)

	![](http://markdown-here.com/img/logo-2015/austin.png)

##Emphasis##
There are two types of emphasis, __bold__ and _italics_

	To use italics, surround the words with 1 _underscore_ or *asterisk*
	To use bold, surround the words with 2 __underscores__ or **asterisks**
