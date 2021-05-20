---
title: "Deep Dive into Semantic HTML"
metaTitle: "Syntax Highlighting is the meta title tag for this page"
metaDescription: "This is the meta description for this page"
---

HTML (HyperText Markup Language) defines the structure, content, and meaning of the web.

HTML uses "markup" to annotate text, images, and other content for display in a Web browser. It utilizes elements such as: ```<article>, <section>, <p>, <div>, <span>, <img>, <aside>, <audio>, <canvas>, <datalist>, <details>, <embed>, <nav>, <output>, <progress>, <video>, <ul>, <ol>, <li>```

Elements are used to enclose, wrap, or "mark up" different parts of content to provide structure or make the content appear or act in a certain way.


```anatomy of an HTML element
<h1>Deep Dive into Semantic HTML</h1>
```
``<h1>`` represents the opening HTML tag
``Deep Dive into Semantic HTML`` represents the content of the element
``</h1>`` represents the closing tag

- The opening tag: This consists of the name of the element (in this example, h1 for a first level header element), wrapped in opening and closing angle brackets. This opening tag marks where the element begins or starts to take effect.
- The content: This is the content of the element. In this example, it says ``Deep Dive into Semantic HTML``.
- The closing tag: This is the same as the opening tag, except that it includes a forward slash before the element name. This marks where the element ends. Failing to include a closing tag is a common beginner error that can produce peculiar results.

### Declaring HTML Standards

To maintain compatibility with the greatest possible number of web pages, modern web browsers are generally developed with multiple rendering modes: in "standards mode" pages are rendered according to the HTML and CSS specifications, while in "quirks mode" attempts are made to emulate the behavior of older browsers.

When W3C, was introduced, browsers could not just start using them as doing so would break most existing sites on the web. Browsers introduced two modes to treat new standards compliant sites differently from old legacy sites.    Layout engines in browsers uses three modes:
1. Quirks mode: In quirks mode, layout emulates nonstandard behavior in Navigator 4 and IE 5. These were needed for websites written before introduction of web standards. 
2. Full standard mode: In this mode, the behavior described is same as described by HTML and CSS specifications. Most of the modern browsers uses full standard mode.  
3. Almost standard Mode: In almost standard mode there is very small number of quirks implementation. 
   

Make sure you put the DOCTYPE right at the beginning of your HTML document. Anything before the DOCTYPE, like a comment or an XML declaration will trigger quirks mode in Internet Explorer 9 and older. The DOCTYPE as, ```<!DOCTYPE html>```, is the simplest possible, and the one recommended by HTML5. Earlier versions of the HTML standard recommended other variants, but all existing browsers today will use full standards mode for this DOCTYPE, even the dated Internet Explorer 6. 

What does a DOCTYPE do?#
DOCTYPE is an abbreviation for DOCument TYPE. A DOCTYPE is always associated to a DTD - for Document Type Definition.

A DTD defines how documents of a certain type should be structured (i.e. a button can contain a span but not a div), whereas a DOCTYPE declares what DTD a document supposedly respects (i.e. this document respects the HTML DTD).

For webpages, the DOCTYPE declaration is required. It is used to tell user agents what version of the HTML specifications your document respects. Once a user agent has recognized a correct DOCTYPE, it will trigger the no-quirks mode matching this DOCTYPE for reading the document. If a user agent doesn't recognize a correct DOCTYPE, it will trigger the quirks mode.

The DOCTYPE declaration for the HTML5 standards is <!DOCTYPE html>.


