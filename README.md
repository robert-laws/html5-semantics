# HTML5 - Semantics - Examples

(Express usages)
// MAC - "start":"open http://localhost:8080 && node app.js"
// PC - "start": "start http://localhost:8080 & node app.js"

## Beginning Semantic Elements

These are the most basic building blocks for semantic HTML5.

* header
* nav
* main
* footer

## Adding some complexity

Within the main content area an article will encompass the sub-content divisions. Sections general form part of something else, but an article exists on its own. An aside is included within an article if it relates to the article, but it can be placed outside the wrapping article if its content is indirectly from the article.

Ex. ``article`` is content that could be taken out of the page and stand on its own as a distinct piece of infomration. ``section`` is content that needs to be grouped together logically.

* article
* section

## HTML5 Content Model

Flow content - included in the normal flow of the webpage document. Used as a parent content element that can contain children elements.

Metadata content

Phrasing content - used for phrasing content in a particular way.

Embedded content - imports other resources into the document.

Interactive content - users can interact with this type of content.

Heading content - header of a seciton (h1-h6)

Sectioning content - defines the scope of new sections within a document.

### HTML5 Sectioning Elements

* article - stand alone content
* aside - related to adjacent content but distinctive in some way
* nav
* section

### HTML5 Semantic Grouping Elements

* footer
* header
* main - surrounds main content of the page

## Using Headings Properly

Headings ``h1`` - ``h6`` are semantically very imporant to organize the content outline of the page.