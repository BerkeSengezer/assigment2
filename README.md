# Assignment 2

This project contains one HTML file and two different CSS stylesheets.

## File Organization

- `index.html` - Contains the HTML structure with six box elements labeled A through F.
- `styleA.css` - Styles the page according to Version A.
- `styleB.css` - Styles the page according to Version B.

To switch between the two versions, change the stylesheet link in `index.html`:

```html
<link rel="stylesheet" href="styleA.css">
```

or:

```html
<link rel="stylesheet" href="styleB.css">
```

## Challenges

The main challenge in Version A was keeping all six boxes equally spaced vertically while also making sure that the boxes stayed centered and did not change size. Flexbox was used to solve this layout requirement.

The main challenge in Version B was keeping boxes A through E on the same line when the browser window becomes smaller and keeping box F fixed in the bottom-right corner. Inline-block elements, white-space control, and fixed positioning were used for this behavior.
