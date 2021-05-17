---
title: "HTML5"
metaTitle: "Syntax Highlighting is the meta title tag for this page"
metaDescription: "This is the meta description for this page"
---

HTML5 is the most recent rendition of the Hypertext Markup Language, also referred to as the WWW (World Wide Web)'s fundamental language. This markup language augments a text file with bits of code, and this code, which we call markup, describes the structure of the document.

HTML5 introduces some new features including:

- Adding new parsing rules to enhance flexibility.
- Adding New attributes.
- Allow offline editing.
- Support (Web SQL)
- Support Protocol and MIME handler registration. These features can be used to change the way of user interaction with documents.
- Geolocation
- Offline Application Cache
- Client-side database
- Error Handling
- New Structure and new multimedia elements.
- Browser Support and compatibility.

#### Tags

Tags: An HTML tag tells the browser how to render the HTML web page in a certain defined format. HTML uses angular brackets, < and >, to enclose the tags, the symbol / for closing the tag, and is used for many reasons like:

changing the appearance of text,
showing a graphic,
linking to another web page.

#### Attributes

All HTML elements can have attributes that give added information about an element.

Attributes are placed directly after the name of a tag, inside the two angled brackets. Attributes only appear in opening tags or in self-closing tags. They can not be used within closing tags. Attributes usually come in name/value pairs, like name="value".

Some attribute examples:
- href
- name
- value
- width
- height

#### Headings

HTML documents can support 6 levels of headings from level 1 ```<h1>``` to level 6 ```<h6>```.

#### Semantics in HTML

Semantic HTML provides meaning to the web page as opposed to just presentation. A ```<p>``` tag, for example, indicates that the enclosed text is a paragraph. This is both semantic and presentational as we as humans know what paragraphs are, and the browsers know how to display them.

On the other hand, tags such as ```<b>``` and ```<i>``` are not semantic markup. They only tell the browser how the text should look (bold or italic), and do not add meaning to the markup. In semantic HTML, these are replaced by ```<strong>``` for strong text and ```<em>``` for emphasized text respectively.

#### Storage in HTML5

Session Storage: The data or details from only the user’s current browsing session are stored. Once the user closes the browser, the storage data gets removed automatically.

Local Storage: The data stays safe and does not get cleared automatically when the user closes the browser. The data instead needs to be deleted manually to remove it from storage.

#### Server Sent Events & Web Sockets

A server-sent event is when a web page automatically receives updates from a server. This functionality used to be available earlier as well, except that it was not automated because the web page would have to check if there were any changes. The updates immediately arrive with server-sent events.

Websockets connections can provide both ship statistics to the browser and acquire information from the browser. A real-life example of an application that might use WebSockets is a chat application.

### Meta Data

Meta tags store information about the web page—known as metadata that is not necessarily visible to end-users (unless the page source code is revealed).

We place these in the ```<head>``` tag.