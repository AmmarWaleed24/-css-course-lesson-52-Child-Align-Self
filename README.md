# Align-Self in CSS

The `align-self` property controls the alignment of an individual flex item along the cross-axis, overriding the container’s `align-items` property.

## Values:
- **`auto`** (default) → Inherits from `align-items` of the container.
- **`flex-start`** → Aligns the item to the start of the cross-axis.
- **`flex-end`** → Aligns the item to the end of the cross-axis.
- **`center`** → Centers the item along the cross-axis.
- **`baseline`** → Aligns based on the text baseline.
- **`stretch`** → Stretches the item to fill the container.

## Example:
```css
.item {
    align-self: flex-end;
}
```
The specific item will be aligned to the end of the cross-axis, regardless of the container’s `align-items` value.

## Example Output:
![Align-Self Example](Screenshot%202025-02-17%20090728.png)

---

## License
This project is open-source. Feel free to use and modify it as needed.

## Author
[Your Name](https://github.com/yourgithub)
