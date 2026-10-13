# Let Us start Learning HTML
---------
Basic HTML Course

## Basic Website folder structure
-----------
```
site-name/
├── images/    -> hold images to be used in website
|  ├── logo.png    
├── css/      -> hold css files
├── js/       -> hold client side scripting files
├── index.htm
└── README.md
```

## Language of Webpage - HTML (HyperText Markup Language)
-------------------------------------------------------
1. 	HTML is a document structuring language not a programming language.
2. 	One file per webpage.
3.  Webpages can be save with extension `'.htm'` or `'.html'`. Though cases for filenameing are not important but small letters are preferred while saving
	Name like `INDEX.HTM`, `index.htm`, `Index.Htm`, `InDex.HTm` are considered same names in Windows but these are treated as different files in unix based OS
4. 	HTML is a case insensitive language but lower case is preferred.
5. 	HTML instructions are called **tags**. Tag is enclosed between `<` and `>`.
   - Most of the tags are paired as opening and closing tags
		`<tag>....</tag>.` **Example:** For paragraph we will use	`<p>...</p>`.
	 - Few tags don't have closing tags, they are known as 'empty' or 'void' tags.
		Example: line break	<br>, horizontal rule <hr>, images <img>.
	c.	Block tags output always start at new line, examples - paragraphs, headings.
	d.	Inline tags get fitted in the normal flow of the document. These are usually
	    formatting tags such as bold, italic etc.
	e.  Output and behaviour of a tag can be controlled by its properties called 
	    attributes. Most of the attributes are optional. Values assigned to these 
		attributes must be enclosed between single ('') or double quotes ("") irrespective 
		whether it is text or number. Attributes are specified in the body of 
		opening tag.
		<tag attr="value"></tag>
		Example: <p align="justify"></p> 
		<img src="images/deer.png" width="50%">
6.	Web pages can be previewed in web browsers such as chrome, mozilla, edge, 
    safari, opera etc.
