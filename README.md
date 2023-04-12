# fastflex.css
A simple css style build library. Serves to speed up the development of websites.

fastflax.css is a wrapper over basic css properties. It includes: flex properties, working with flex positioning, changing the width and height of elements, colors, positioning and styles of text and other functions.

## Connection

```HTML
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/FleshHerbal/fastflex.css@c340886dd0cd646d9891b875aed11ef10ed95550/fastflex.css"> 
```

## Class names
### Positioning
| NAME | VALUES | CORRESPONDS | DECRIPTION |
|:----------------|:---------:|:----------------|:----------------:|
| c_column | - | `flex-direction: column;` | - |
| c_row | - | `flex-direction: row;` | - |
| align_start | - | `align-items: flex-start;` | - |
| align_center | - | `align-items: center;` | - |
| align_end | - | `align-items: flex-end;` | - |
| justify_end | - | `justify-content: flex-end;` | - |
| justify_start | - | `justify-content: flex-start;` | - |
| justify_center | - | `align-items: center;` | - |
| justify_space_between | - | `justify-content: space-between;` | - |
| justify_space_around | - | `justify-content: space-around;` | - |
| clickable | - | - | When hovering over an element, creates transparency |
| line_scroll_disable_all | - | `overflow: hidden;` | - |
| line_scroll_disable_y | - | `overflow-y: hidden;` | - |
| line_scroll_disable_x | - | `overflow-x: hidden;` | - |
| width_{value} | 5, 10, 15, 20, 25. 33, 50, 66, 75, 85, 100, | `width: 50%;` | Example: `<div class="width_33"></div>` |
| full_height | - | `height: 100%;` | - |



### Text and fonts
| NAME | VALUES | CORRESPONDS | DECRIPTION |
|:----------------|:---------:|:----------------|:----------------:|
| font_s_{value} | from 12 to max 40 | `font-size: 20px;` | Text height in pixels |
| text_pos_center | - | `text-align: center;` | Positions text in the center |
| text_pos_left | - | `text-align: left;` | Positions text to the left |
| text_pos_right | - | `text-align: right;` | Positions text to the right |
| font_w_b | - | `font-weight: bold;` | - |
| font_w_{value} | from 100 to max 900 | `font-weight: 500;` | Example: `<div class="font_w_500"></div>` |
| font_a_u_rem | - | `text-decoration: none;` | Removes a property from an element: "text-decoration" |

|  | - | `` | - |
|  | - | `` | - |
|  | - | `` | - |
|  | - | `` | - |
|  | - | `` | - |
|  | - | `` | - |
