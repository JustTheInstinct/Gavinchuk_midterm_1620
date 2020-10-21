# Short Answer Questions

Jordan Gavinchuk
A01234576
Midterm for ACIT 1620 October 21 - 22, 2020
BCIT

## Q1 Explain what Git and GitHub are. How are they different? 

Git is a version control system that is used to track changes made in code.

Github is a website that hosting software to Git. It is used to push code online where others can aquire pushed code and modify it.

The difference between them are that Git is used to manage the changes in code while Github assists in putting it online and distributing it to anyone that wants to see or edit the code.

## Q2 What is a 'Branch' in Git? How could you create a new branch and what would you commonly use a branch for? 

A branch in Git essentially is a snapshot of changes that have been made. A main branch is used to update the final product while other branches are used to act as "suggested" updates which can then replace the original if needed.

A branch is created with the following input

`git branch "name of branch"`

Branches are used to experiment adding new features without impacting the original product. This is useful as you do not need to backtrack if the experiment does not get implemented.

## Q3 What is the http status code you get when a resource is not found? What category of status code does this belong to (other status codes that start with the same number)? Does this status code indicate if the representation is permanent?

Status code is Error: 404

The http code starting with the number 4 represents a client side error.

Error: 404 does not provide if the status is permanent. In most cases, the user inputted the incorrect web address (Not permanent). Other cases sugegst that the resources were removed (permanent).

## Q4 What is not correct about styling of the given h2 element in the code below? Which color will the h2 be and why?

The stlying is attempting to reference the h2 element multiple times. The color of the h2 in the document will be red as CSS is applied to the latest style called.

## Q5 List and briefly describe the parts of a URL.

A URL or web address is a reference to a resource on the internet.
URL Examples:

### Example of another used sub-domain (leads to nowhere):
https://mail.gogle.com

### Example of a query (leads nowhere):
https://www.youtobe.com/watch?v=dQw4w9WgXcQ&ab.html

# https://:
The protocol of the website that is being accessed. The protocol determines how the data is sent to a machine.

# www. and mail.:
The Sub-domain of the website. A sub-domain is a domain of a domain or a specific part of the website.

# gogle and youtobe:
The domain name of a website. Used to give a website a "Name" rather than use the web address.

# .com:
The top-level domain of a website. Determines the root used of a website.

# /watch:
The file path of a website. Website uses a file path to navigate to where the user should be.

# ?v=dQw4w9WgXcQ&ab:
Query Sring of a website. The query that the computer recieves and processes.

## Q6 What is an http header? Provide examples of three http header fields and briefly describe what each does.

HTTP headers are a service that provides additional information with the response of an HTTP request between server and client.

3 Header fields include GET: Aquires data from a specific resource. POST: Sends data to a server to update a specified resource. DELETE: Removes specified resource.

## Q7 Describe the CSS box model? From inside to outside what are the different parts of the box model?

The CSS box model is a widly recognized style design for web development. The model is applied when altering any object in a web document.

The box model from the inside out consists of the following in order: Content (And the width and height along with the content), Padding, Border, and then Margin.

## Q8 Briefly describe the 4 CSS Combinator selectors that we looked at in class. Provide an example of each.

Decendant Selector: References all elements within a tab. Tabs must be adjacent. (within "this element" affect "these elements")
Ex.
`p ul li a {color = #fff}`

Child Selector: References all elements that are children of a selected tab. All tabs within selected element are affected. (within "this element" affect all "these elements")
Ex.
`p > ul {color = #fff}`

General Sibling Selector: References tabs after the first element. (after "this element" ~ affect "that element")
Ex.
`p ~ ul {color = #fff}`

Adjacent Sibling Selector: References element that is adjacent to target element. (after "this element" + affect the next "that element")
Ex.
`p + ul {color = #fff}`

## Q9 Will these two paragraphs appear on two separate lines? Why?

Yes. When a paragragh tag is closed, a new line is created.

## Q10 Identify and explain two of the errors that exist in the code snippet below.

Img tag error: Although the src declaration is correct, there is no reference to alt declaration, width, or height. This can give unwanted image sizes.
a tag errors: Missing sub-domain on URL, title should not be present in the a closing tag.