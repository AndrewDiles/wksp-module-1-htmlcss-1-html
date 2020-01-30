# HTML Comprehension Questions


## Q1 - For each of the following HTML documents, is the HTML valid?

Type true/false in the provided [ ].

a) [false] `<div><span>hello</span></div>`

b) [false]

```html
<ul>
    <li>one</li>
</ul>
```

c) [false] 

`<ul>
    <li>
        <img/>
        <ol>
            <li>one</li>
        </ol>`
    </li>
</ul>

## Q2 - What is a screenreader and why should we care about them?

_Feel free to use the powers of Google here, but please provide link(s) to your source(s)_

A screenreader enables individuals with certain disabilities to access the content of the internet despite those disabilities.  i.e. it helps bridge the gap between commonly used techonology and their specific needs.

https://en.wikipedia.org/wiki/Screen_reader




## Q3 - For each of the following cases, which tags will be needed?

a) You want to create a webpage with the photos from your latest vacation

Do we assume the mandatory tags that all hmtl documents contain do not need to be said? 
i.e. <!DOCTYPE html>, <head>, <title> <body> etc...

<img> which contains a src and an alt.
<ul> or <ol> and <li> to list your pictures.
<p>, <div> to add witty comments...

b) You want to create a website that lists all the art gallery websites in your city and links to their website.

Aside from some mandatory things, you would specifically make use of
<ul> or <ol> and <li> to make a list links to the sites.
You would also need anchor elements with href s to direct your links: <a href="https://www.museum'saddress.orgorwhatever">Words chosen to be seen as the link</a>

c) You want to sell designer hats. You need to receive orders from the user.

inside a <form> you would have <input> s with various types, likely text, email, perhaps password if you were forcing the user to make an account.

## Q4 - Can a button be a child of a button? Explain your reasoning

No.  Interactive elements can not be the children of interactive elements. But imagine having a button inside another, when you click the inside one, does it click them both or just the inside one?  You could probably design an array of buttons to look like there is a working button inside the other one, but it would not be scripted to be its child.




## Q5 - What is the most generic tag you can use?

<div>


## Q6 - What do the following achronyms stand for?

a) `a` anchor

b) `ol` ordered list

c) `ul` unordered list

d) `li` list

e) `tr` table row

f) `th` table head

g) `td` table data

## Q7 - Usually, `td` elements are children of what kind of elements?

<tr>

## Q8 - What is the difference between td and th?

Table heads should only be used once and at the top of a table to include the header that the data will be types of.
Table data is the content of the table's rows.

## Q9 - Which tag makes the text appear bigger: h1 or h3?

h1 by default, however you could probably use css to alter that.

## Q10 - In which situation can you use self closing tags?

Situartions in which the tag has no text to display.

## Q11 - What is autofilling and why is it important?

Autofilling is when a browser assumes or suggests values to be filled based on what data the user had previously entered.  It can be useful when entering repitiive data.

## Q12 - Which attributes are always present in an img element?

<src> and <alt>

## Q13 - Which attribute is always present for an anchor tag?

<href>

