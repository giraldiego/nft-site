# Build an NFT Site

## About Scrimba

At Scrimba our goal is to create the best possible coding school at the cost of a gym membership! 💜
If we succeed with this, it will give anyone who wants to become a software developer a realistic shot at succeeding, regardless of where they live and the size of their wallets 🎉
The Frontend Developer Career Path aims to teach you everything you need to become a Junior Developer, or you could take a deep-dive with one of our advanced courses 🚀

- [Our courses](https://scrimba.com/allcourses)
- [The Frontend Career Path](https://scrimba.com/learn/frontend)
- [Become a Scrimba Pro member](https://scrimba.com/pricing)

Happy Coding!

## Semantic HTML

https://developer.mozilla.org/en-US/docs/Glossary/semantics

-   [`<header>`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/header) Site title, logo and nav
-   [`<section>`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/section) A stand-alone section
-   [`<footer>`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/footer) Copyright, Ts ^ Cs, etc.
-   [`<main>`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/main) The page's unique content

## Setup CSS Basics

## Aside: Margins - Strange behaviour

> When an element touches its parent, its top and bottom margins will merge with the margis of the parent element.

**Solution:** Use padding in the parent element.

## Style first section image

https://css-tricks.com/almanac/properties/w/width/
```css
width: 100%;
```

## Style first section text

`<p>` has the same `font-size` set in `body`
`<h2>` is 1.5x times the `font-size` set in `body`

## Aside: hover and active states
https://www.w3schools.com/css/css_pseudo_classes.asp

### pseudo selectors
```css
 /* unvisited link */
a:link {
  color: #FF0000;
}

/* visited link */
a:visited {
  color: #00FF00;
}

/* mouse over link */
a:hover {
  color: #FF00FF;
}

/* selected link */
a:active {
  color: #0000FF;
} 
```

## Style first section links
https://developer.mozilla.org/en-US/docs/Web/CSS/text-decoration

## Aside: background full width

> Use Containers

```css
<div class="container">
</div>
```

## CSS Organisation
```css
/* Typography */
/* links */
/* layout */
```

## Set layout for second section
```css
.section-two {
  color: whitesmoke;
  background-color: #5f29a3;
}

.section-two__img-container {
  display: flex;
  justify-content: space-between;
}

.section-two__img {
  width: 300px;
  border-radius: 4.6px;
}
```

## Grouping selectors

## Specifity
https://developer.mozilla.org/en-US/docs/Web/CSS/Specificity

CSS Points:
`id > class > elements`

## Compound selectors

> Element selector = 1
   Class selector = 10
   Id selector = 100

## Links vs Buttons

- Buttons for actions that affect the website's front-end or back-end
- Links for navigation to somewhere on the same page, within the site, or elsewhere.

## Aside: Inline-block

### Block elements
- Stack on top of each other. 
- `div, p, h1` are all examples of block elements.
- Set height and margin top and bottom

### Inline elements
- Sit side by side. 
- `span` and `a` are examples of inline elements.
- Can't set height and margin top and bottom.

### Inline-block elements
- Sit side by side.
- `button` and `input` are examples of inline-block elements.
- Set height and margin top and bottom


