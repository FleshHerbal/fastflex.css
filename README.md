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
| align_{value} | start, center, end | `align-items` | - |
| justify_{value} | end,start, center, space_between, space_arount | `justify-content` | - |
| clickable | - | - | When hovering over an element, creates transparency |
| line_scroll_disable_all | all, y, x | `overflow` | Disable scrolling on certain sides |
| width_{value} | 5, 10, 15, 20, 25. 33, 50, 66, 75, 85, 100, | `width: 50%;` | Example: `<div class="width_33"></div>` |
| full_height | - | `height: 100%;` | - |
| margin_clear | - | `margin: 0` | - |
| margin_v10_h5 | - | `margin: 10px 5px 10px 5px` | - |
| margin_v5_h10 | - | `margin: 5px 10px 5px 10px` | - |
| margin_h5 | - | `margin: 0px 5px 0px 5px` | - |
| margin_h{value} | 5, 10, 15, 20 | `margin: 0px 10px 0px 10px` | - |
| margin_v{value} |  5, 10, 15, 20 | `margin: 5px 0px 5px 0px;` | - |
| margin_lf_{value} | 5, 10, 15, 20 | `margin-left: 5px;` | - |
| margin_rh_{value} | 5, 10, 15, 20 | `margin-right: 5px;` | - |
| margin_top_{value} | 5, 10, 15, 20 | `margin-top: 5px;` | - |
| margin_bottom | 5. 10, 15, 20 | `` | - |
| padding_clear | - | `padding: 0` | - |
| padding_v10_h5 | - | `padding: 10px 5px 10px 5px;` | - |
| padding_v5_h10 | - | `padding: 5px 10px 5px 10px;` | - |
| padding_h{value} | 5, 10, 15, 20 | `padding: 0px 5px 0px 5px;` | - |
| padding_v{5} | 5, 10, 15, 20 | `padding: 5px 0px 5px 0px;` | - |
| padding_lf_{value} | 5, 10, 15, 20 | `padding-left: 5px;` | - |
| padding_rh_{value} | 5, 10, 15, 20 | `padding-right: 5px;` | - |
| padding_top_{value} | 5, 10, 15, 20 | `padding-top: 5px;` | - |
| padding_bottom_{value} | 5, 10, 15, 20 | `padding-bottom: 5px;` | - |

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
