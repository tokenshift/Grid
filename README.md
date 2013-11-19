# Grid

*Small, simple, powerful CSS grid*

See <tokenshift.github.io/Grid/> for detailed instructions.

## Class Reference

### Basics

* **`.row`**
  Container for horizontally aligned set of grid cells.
* **`.cell-#`**
  A `#`-column cell.

### Positioning

* **`.push-#`**
  Move the cell `#` columns to the right.

* **`.pull-#`**
  Move the cell `#` columns to the left.
* **`.center`**
  Center the cell in the row.

### Nesting

* **`.inner`**
  Applied to a `.row` to remove the outer margin.

### Responsive

These classes override cell styles for specific screen sizes.

* **`.cell-{prefix}-#`**
* **`.push-{prefix}-#`**
* **`.pull-{prefix}-#`**
* **`.show-{prefix}`**
  Show the cell ONLY at the specified screen size.
* **`.hide-{prefix}`**
  Show the cell EXCEPT at the specified screen size.

#### Screen Sizes

* **Small** (prefix: s)
  Up to 767px.
* **Medium** (prefix: m)
  768px to 959px.
* **Large** (prefix: l)
  960px and above.
