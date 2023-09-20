# Challenge 01 HTML, CSS, and Git: Code Refactor (Breakdown and Review With Notes and Resources) 

## User Story

```
AS A marketing agency
I WANT a codebase that follows accessibility standards
```

A codebase that follows the [Web Content Accessibility Guidelines](https://developer.mozilla.org/en-US/docs/Web/Accessibility/Understanding_WCAG)

```
SO THAT our own site is optimized for search engines
```

These [guidelines](https://developer.mozilla.org/en-US/docs/Web/Accessibility/Understanding_WCAG) for search engine and web browser optimization include... 

1. [Perceivable](https://developer.mozilla.org/en-US/docs/Web/Accessibility/Understanding_WCAG/Perceivable): Users must be able to perceive it in some way, using one or more of their senses.

2. [Operable](https://developer.mozilla.org/en-US/docs/Web/Accessibility/Understanding_WCAG/Operable): Users must be able to control UI elements (e.g. buttons must be clickable in some way — mouse, keyboard, voice command, etc.).

3. [Understandable](https://developer.mozilla.org/en-US/docs/Web/Accessibility/Understanding_WCAG/Understandable): The content must be understandable to its users.

4. [Robust](https://developer.mozilla.org/en-US/docs/Web/Accessibility/Understanding_WCAG/Robust): The content must be developed using well-adopted web standards that will work across different browsers, now and in the future.


## Acceptance Criteria
1. 
```
GIVEN a webpage meets accessibility standards
WHEN I view the source code
THEN I find semantic HTML elements
```
[Semantic Elements](https://www.w3schools.com/html/html5_semantic_elements.asp) are elements that clearly describe their meaning to both the browser and the developer.
### My Changes

`<!--"nav" changed from "div" to provide SEO-->`

    <nav>
        ...
    </nav>
---
`<!--"section" changed from "div" to provide SEO-->`
    
    <section class="hero">
        ...
    </section>
---
`<!--"section" changed from "div" to provide SEO-->`

    <section class="content">
        ...
    </section>
---
`<!--"article" changed from "div" to provide SEO-->`

    <article id="search-engine-optimization" class="search-engine-optimization">
        ...
    </article>
---
`<!--"article" changed from "div" to provide SEO-->`

    <article id="online-reputation-management" class="online-reputation-management">
        ...
    </article>
---
`<!--"article" changed from "div" to provide SEO-->`

    <article id="social-media-marketing" class="social-media-marketing">
        ...
    </article>
---
`<!--"aside" changed from "div" to provide SEO-->`

    <aside class="benefits">
        ...
    </aside>
---
`<!--"section" changed from "div" to provide SEO-->`

    <section class="benefit-lead">
        ...
    </section>
---
`<!--"section" changed from "div" to provide SEO-->`

    <section class="benefit-brand">
        ...
    </section>
---
`<!--"section" changed from "div" to provide SEO-->`

    <section class="benefit-cost">
        ...
    </section>
---
`<!--"footer" changed from "div" to provide SEO-->`

    <footer class="footer">
        ...
    </footer>
---
2. 
```
WHEN I view the structure of the HTML elements
THEN I find that the elements follow a logical structure independent of styling and positioning
```
[Logical structure](https://www.w3schools.com/html/html_css.asp) independant of styling and positioning is crucial to developing code that is clean, easy to read, and easy to maintain. 
### My Changes

I attemted to order the selectors as they read in the HTML,
global and most important at the top, then by selector, left
to right then top to bottom.

---
3. 
```
WHEN I view the icon and image elements
THEN I find accessible alt attributes
```
[Alt](https://www.w3schools.com/tags/att_img_alt.asp) attributes are important for accessing web apps with a slow connection or alternative hardware such as screen readers.
### My Changes

Line 38: `<img src="./assets/images/search-engine-optimization.jpg" class="float-left" alt="SEO Seach Engine Optimization is good for content, headings, mobile compatibility, social media, link building and back linking."/>`

Line 47: `<img src="./assets/images/online-reputation-management.jpg" class="float-right" alt="Graphical representation of site visitors increasing after Horiseon services."/>`

Line 56: `<img src="./assets/images/social-media-marketing.jpg" class="float-left" alt="SEO Seach Engine Optimization increases marketing opportunity through social media."/>`

Line 70: `<img src="./assets/images/lead-generation.png" alt="Lead generation is increased with Seach Engine Optimization and creates a higher work flow with less work from you. "/>`

Line 79: `<img src="./assets/images/brand-awareness.png" alt="Seach Engine Optimization creates brand awareness by recommending your business to more searches and increases visibility." />`

Line 88: `<img src="./assets/images/cost-management.png" alt="Search Engine Optimization is cost effective by getting more eyes on your business and increasing rankings." />`

---
4.
```
WHEN I view the heading attributes
THEN they fall in sequential order
```
`<h1>` defines the most important [heading](https://www.w3schools.com/tags/tag_hn.asp). `<h6>` defines the least important heading.
### My Changes


`<!--"h4" changed from "h2" to provide SEO-->`

    <h4>Made with ❤️️ by Horiseon</h4>
---

5.
```
WHEN I view the title element
THEN I find a concise, descriptive title
```
The [page title](https://www.w3schools.com/tags/tag_title.asp) is used by search engine algorithms to decide the order when listing pages in search results.
### My Changes

Line 7: `<title>Horiseon SEO</title>`



![https://dylanozzy.github.io/SEO-Website/](./assets\images\SEOWebsiteSS.jpg)
[Link](https://dylanozzy.github.io/SEO-Website/) to deploy.