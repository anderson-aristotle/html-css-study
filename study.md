# HTML CSS Study

Take some time to read through `Getting to Know CSS`. Once you have completed
the reading, follow the directions in the `CSS Diner` game to help you learn and
implement CSS.

Once you are done, use your favorite search engine and the provided readings to
research and respond to the following questions.

In your responses, be sure to cite any relevant sources you consulted in your
search. We ask you to write responses in your own words in order to see how you
process what you've read. Please do not respond with direct quotes from source
material. Instead, digest what you've read and repeat it in your own voice.

## Required Readings

- [How to Use The HTML5 Sectioning Elements](http://blog.teamtreehouse.com/use-html5-sectioning-elements)
- [Building Forms](https://learn.shayhowe.com/html-css/building-forms/)
- [Getting to Know CSS](https://learn.shayhowe.com/html-css/getting-to-know-css/)
- [CSS Diner](https://flukeout.github.io/) (Only levels 1-15)

## Response Questions

### HTML: Semantic Elements

1. What is the importance of using semantic HTML elements?

    ```md
  Semantic HTML allows programmers to understand the order in which elements appear on the page.
    ```

1. List 5 alternatives to using a `div` element.

    ```md
    Real tags help with semantic HTML elements: sections, headers, footer, nav, and aside.
    ```

### HTML: Forms

List 6 values for the `type` attribute on `input` elements.

```md
checkbox, button, imagine, hidden, file, time
```

### CSS: Cascading Properties

Explain how cascading works with CSS properties.

```md
When a single element has multiple styles, the elements will inherit its style from
the parent element or from top down.
```

### CSS: Combining Selectors

Given the following HTML:

```html
<div class='user-profiles'>
  <ul class='profile-list'>
     <li>User 1</li>
     <li>User 2</li>
     <li>User 2</li>
  </ul>
</div>

<div class='team-profiles'>
  <ul class='profile-list'>
     <li>Team 1</li>
     <li>Team 2</li>
     <li>Team 3</li>
  </ul>
</div>
```
And the following CSS:

```css
.team-profiles .profile-list li:first-child {
   background-color: red;
}
```

Which HTML element(s) will receive the red background?

  ```md
  team 1, <li>
  ```

## Additional Resources

- [Complex CSS Selectors](https://learn.shayhowe.com/advanced-html-css/complex-selectors/)
- [HTML & CSS](https://learn.shayhowe.com/html-css/)
- [Advanced HTML & CSS](https://learn.shayhowe.com/advanced-html-css/)
- [CSS Diner](https://flukeout.github.io/) (levels 16-32)
