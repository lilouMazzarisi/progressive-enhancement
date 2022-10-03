# HTML is about semantics

**What is "semantics" ?**
Semantics marks up what a series of information is to be considered as. 
- adds hierarchy and
- structures a text
*= That's what HTML is for!*

To make proper HTML code, one must think about the structure of its text. 

### Why is semantics so important ?

1 - SEO : your website's findability / visibility on Google
2 - Accessibility : all humans, no matter their handicap have to access the information.

**Semantic is actually pretty easy** 

Semantics =  choosing the right tags and attributes to represent your content. 
GOLDEN RULE -> as little code as possible, but as much as necessary.

**Tags**
Tags are used to indicate the semantic function of a portion of content in "blocks". Most html blocks work with an opening tag and a closing tag.

*Syntax example :*
*<p>This is a paragraph (hence the P letter).</p>*
+----------------------------+
| h1 | Heading | 
+----------------------------+
| h2 | Subheading | 
+----------------------------+
| section | section is a thematic grouping of content. A general rule is that the section element is appropriate only if the element’s contents would be listed explicitly in the document’s outline.
+----------------------------+
| blockquote | represents a section that is quoted from another source.|
+----------------------------+
q | phrasing content quoted from another source.|
+----------------------------+
img | picture |
+----------------------------+
p | paragraph  |
+----------------------------+
figure | The figure element represents some flow content. Typically referenced as a single unit from the main flow of the document.|
+----------------------------+
caption | the title of the table that is its parent, if it has a parent and that is a table element. |
+----------------------------+
table | The table element represents data with more than one dimension, in the form of a table. Tables must not be used as layout aids. |
+----------------------------+
th | table head = name/category of the row or column |
+----------------------------+
tr | table row |
+----------------------------+
td | table data = content in the table  |
+----------------------------+
ul | unordered list with dots|
+----------------------------+
ol | orderd list with # |
+----------------------------+
li | list item |


!! **div** or **span** : they do not provide any semantics.
