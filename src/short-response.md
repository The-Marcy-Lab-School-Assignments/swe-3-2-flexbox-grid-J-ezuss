# Short Response Questions

Answer the following questions in 2-4 sentences each. Be specific and use vocabulary from the lessons.

## Question 1: Flexbox Basics

What is the difference between a **flex container** and a **flex item**? How do you make an element a flex container?

**Your Answer:**
A flex container is the parent element that controls layout using Flexbox, while flex items are its direct children that are arranged inside it. You make an element a flex container by setting display: flex

## Question 2: Main Axis vs Cross Axis

In Flexbox, what is the **main axis** and what is the **cross axis**? How do `justify-content` and `align-items` work with these axes?

**Your Answer:**
In Flexbox, the main axis is the direction the items go (row or column), and the cross axis goes the opposite way.
justify-content moves items along the main axis, and align-items moves items along the cross axis.

## Question 3: Flexbox vs Grid

When would you use **Flexbox** vs **CSS Grid**? Give an example of a layout that would be better suited for each.

**Your Answer:**
You would use Flexbox when you want to arrange items in one direction (row or column), like a navigation bar.
You would use CSS Grid for two-dimensional layouts (rows and columns), like a full webpage layout with header, sidebar, and content.

## Question 4: The `fr` Unit

What does the `fr` unit do in CSS Grid? Explain what `grid-template-columns: 1fr 2fr 1fr` would create.

**Your Answer:**
The fr unit in CSS Grid divides up the available space into fractions.
grid-template-columns: 1fr 2fr 1fr creates three columns where the middle column is twice as wide as the two side columns.

## Question 5: Media Queries

What is a **media query** and why are they important for **responsive web design**? Write an example of a media query that applies styles for screens 768px and wider.

**Your Answer:**
A media query is CSS that lets you change styles based on screen size or device.
They are important for responsive web design because they help websites look good on phones, tablets, and desktops.
An example would be

```css
@media (min-width: 768px) {
  body {
    background-color: lightblue;
  }
}
```

## Question 6: Mobile-First Design

What does **mobile-first design** mean? What are the benefits of taking a mobile-first approach versus a desktop-first approach?

**Your Answer:**
Mobile-first design means you design and write CSS for small screens first (like phones) and then add styles for larger screens.
