# HTML Comprehension Questions

## Q1 - For each of the following HTML documents, is the HTML valid?

Type true/false in the provided [ ].

a) [false] `<div><span>hello</div></span>`

b) [true]

```html
<ul>
<li>one</li>
</ol>
```

c) [false] `<ul></ul><img/><ol><li>one</li></ol>`

## Q2 - What is a screenreader and why should we care about them?


A screen reader is some kind of "assistive technology" (a piece of software, browser extension or else) used by visual impaired people to actually "read out loud" (or render it in braille) an HTML page.

NVDA seems to be a good example of one https://en.wikipedia.org/wiki/NonVisual_Desktop_Access

As would Google index and rank our website based on the quality of the HTML written in our pages ; screenreaders rely on the "readability" of our HTML (or in fact its "accessibilty"). Good use of HTML tags makes for more accessible website, efficient for the indexation, as it allow for anyone using a screenreader to actually browse it.


## Q3 - For each of the following cases, which tags will be needed?

a) You want to create a webpage with the photos from your latest vacation
<html>
    <img
  src="https://vacation.com/images/anywhere-sunset.png"
  alt="Sunset from my last trip"
/>
    <img
  src="https://vacation.com/images/anywhere-sunset2.png"
  alt="Another sunset from my last trip"
/>

b) You want to create a website that lists all the art gallery websites in your city and links to their website.
<ul>
    <li>Art Gallery 1<a href="http://artgallery1"></a>
    <li>Art Gallery 2<a href="http://artgallery2"></a>

c) You want to sell designer hats. You need to receive orders from the user.

 <label>Item :</label>
  <input type="text">

## Q4 - Can a `button` be a child of a `button`? Explain your reasoning
A button can't be a child of a button (could there be a clickable button embedded in another clickable button - doesn't make much sense to me).


## Q5 - What is the most generic tag you can use?
<div/> seems to be the answer

## Q6 - What do the following achronyms stand for?

a) `a` Anchor

b) `ol` Ordered List

c) `ul` Unordered List

d) `li`List item

e) `tr`Table Row

f) `th`Table Header

g) `td`Table Data

## Q7 - Usually, `td` elements are children of what kind of elements?
<tr>

## Q8 - What is the difference between td and th?
<td> is table data (actual elements of data in the table)
<th> is table header (names of the columns for example)

## Q9 - Which tag makes the text appear bigger: h1 or h3?
h1 is the biggest heading


## Q10 - In which situation can you use self closing tags?
Whenever our element doesn't have any child

## Q11 - What is autofilling and why is it important?
Autofilling or autocomplete (?) let your browser fill out forms on the web for you. For an input to be autofilled, you need to allow your HTML form to be autocompleted (autocomplete="on") and therefore your inputs must be part of a form (I guess)

## Q12 - Which attributes are always present in an img element?

A source (src=)
An alt description (alt=) for when the image is missing or a screenreader is used

## Q13 - Which attribute is always present for an anchor tag?

The href= attribute that allow to specify the URL of the website you want to show a link to in your webpage.