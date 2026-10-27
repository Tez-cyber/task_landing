# Task 2 — Landing Page

## Reflection

I used CSS Grid for the statistics section because the four cards need to form a clear 2 × 2 layout.

I used Flexbox inside each stat card because the content needs to be arranged vertically.

I used `justify-content: space-between` to distribute the icon, number, title and description evenly inside each card.

I used `gap` instead of margins because it creates consistent spacing between the grid and flex items without adding unnecessary spacing to the outside of the elements.

The hamburger menu uses the CSS checkbox trick. When the checkbox is checked, the navigation menu changes from `display: none` to `display: flex`.

I also used media queries so the layout changes from two columns to one column on smaller screens.