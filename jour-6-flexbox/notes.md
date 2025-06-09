# Jour 6 : flexbox

Flexbox allow to align horizontally and vertically  
Automatically positions elements inside a container

CSS rule on parents to apply to childrens

```css
[parent] {
  display: flex;
}
```

An item in a flex container (flex item) acts like an inline-block

## main axis and cross axis

main axis = left-right  
cross axis (secondary axis) = top-bottom
![Flex layout, via MDN](https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/CSS_layout/Flexbox/flex_terms.png)

With flex-direction: column, main axis becomes top-bottom and cross axis becomes left-right

## aligning items inside a flex container

main axis : `justify-content`  
cross axis : `align-items`

## view height

vh is a unit for the height of elements, it is a percentage of the height the viewer can see / is displayed
