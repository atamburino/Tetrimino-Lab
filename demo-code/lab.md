# Lab Reflection

At the end of this lab, I gained a better understanding of the importance of focusing on the specific elements I need and approaching them with a different perspective. I also noticed a significant improvement in my troubleshooting and testing skills. For example, in this lab and in the one where I worked with other pieces, I found that leveraging **border-radius** and **padding** was crucial for accurately locating and testing the elements I was working on.

However, I realized I needed to work more on understanding the `order` property. While I used it during the lab, I didn't fully grasp it at first. After watching a video on the topic, I gained a clearer understanding. Here are some of my notes on order.


# CSS `order` Property

The `order` property in CSS is used to control the order of flex items within a flex container, allowing you to rearrange elements without changing the HTML structure.

## Syntax

```css
.element {
    order: <integer>;
}
```
- **Default value:** 0
- **Negative values:** Items with lower (or negative) values appear first.
- **Positive values:** Items with higher values appear later.

```css
Example
.item1 { order: 2; }  /* Displayed second */
.item2 { order: 1; }  /* Displayed first */
.item3 { order: 3; }  /* Displayed third */
```

## Use Cases

- **Reordering Items:** Easily rearrange items visually without altering the HTML structure.
- **Responsive Design Adjustments:** Adapt layouts dynamically to fit different screen sizes and orientations.

## Caution

- **Accessibility:** Ensure proper tab order and screen reader navigation to maintain an accessible experience for all users.
- **Performance:** Be cautious with excessive use in complex layouts, as it can impact rendering performance.
