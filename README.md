---
language: html, css
tags: html5, semantic elements, forms, input, audio, video, media, css, style, syntax, selectors
type: quiz
resources: 0
---

???

# Quiz - CSS Fundamentals

?: 1. CSS stands for Cascading Style Sheet?

( ) TRUE
( ) FALSE

?: 2. It is impossible to validate CSS to check if it is correct?

( ) TRUE
( ) FALSE

?: 3. Which of the following code demonstrates an CSS comment?

( ) // This is a comment in CSS
( ) /* This is a comment in CSS */
( ) &lt;!-- This is a comment in CSS --&gt;
( ) # This is a CSS comment

?: 4. Which is the correct (and most specific) CSS selector statement to select the text inside the HTML element and change the text color to red in the following example:

```html
&lt;p&gt;Lorem Ipsum&lt;/p&gt;
```

( ) p &gt; { color:red }
( ) p { text-color:red; }
( ) p { color:red; }
( ) None of the above.

?: 5. Which is the correct (and most specific) CSS selector statement to select the text inside the HTML element and change the text color to red in the following example:

```html
&lt;ul&gt;
   &lt;li class="redtext"&gt;Gravy&lt;/li&gt;
   &lt;li&gt;Turkey&lt;/li&gt;
   &lt;li&gt;Potato&lt;/li&gt;
&lt;/ul&gt;
```

( ) .redtext { color:red; }
( ) #redtext { color:red; }
( ) li &gt; redtext { color:red; }
( ) None of the above.

?: 6. Which is the correct (and most specific) CSS selector statement to select the text inside the HTML element and change the text color to red in the following example:

```html
&lt;div id="media"&gt;
   Lorem Ipsum Dolores.
&lt;/div&gt;
```

( ) .media { color:red; }
( ) div &gt; media { color:red; }
( ) #media { color:red; }
( ) None of the above.

?: 7. You can apply multiple CSS IDs to the same element.

( ) TRUE
( ) FALSE

?: 8. You can apply multiple CSS Classes to the same element.

( ) TRUE
( ) FALSE

?: 9. In the following example, list the CSS definition for the letter 'p':

```css
p { color:red; }
```

( ) Selector
( ) Property
( ) Value
( ) Declaration

?: 10. In the following example, list the CSS definition for the statement 'color:red;':

```css
p { color:red; }
```

( ) Selector
( ) Property
( ) Value
( ) Declaration

?: 11. In the following example, list the CSS definition for the word 'color':

```css
p { color:red; }
```

( ) Selector
( ) Property
( ) Value
( ) Declaration

?: 12. In the following example, list the CSS definition for the word 'red':

```css
p { color:red; }
```

( ) Selector
( ) Property
( ) Value
( ) Declaration

?: 13. In the following example, which is the correct (and most specific) CSS selector statement to select all of the descendent &lt;li&gt; inside of  &lt;ul id="salsa"&gt; and style their text color red (note: only style &lt;li&gt; inside &lt;ul id="salsa&gt;, NOT &lt;li&gt; elsewhere in the page):

```html
&lt;ul id="salsa"&gt;
   &lt;li&gt;Hot&lt;/li&gt;
   &lt;li&gt;Medium&lt;/li&gt;
   &lt;li&gt;Mild&lt;/li&gt;
&lt;/ul&gt;
```

( ) ul li { color: red; }
( ) #salsa li { color: red; }
( ) li.salsa { color: red; }
( ) .salsa #li { color: red; }

?: 14. Which is the correct (and most specific) CSS selector statement to select the text inside the HTML element and change the text color to red when the user hovers over it with their mouse:

```html
&lt;a href="index.html"&gt;Home&lt;/a&gt;
```

( ) #hover { color: red; }
( ) a.hover { color: red; }
( ) a:hover { color: red; }
( ) None of the above.

?: 15. The Developer Tools can be used to see the given CSS styles applied to a specific element and can be used to preview style changes in the browser.

( ) TRUE
( ) FALSE

???