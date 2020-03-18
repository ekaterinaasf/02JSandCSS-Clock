# 02JSandCSS-Clock
## DOM

| tag name | attributes                  | role                                                   |
| -------- | --------------------------- | ------------------------------------------------------ |
| `<div>`  | `class="clock"`             | the div element that represents the clock |
| `<div>`  | `class="hand hour-hand"` | the div element that contains hour hand             |
| `<div>`  | `class="hand min-hand"`  | the div element that contains minute hand            |
| `<div>`  | `class="hand second-hand"` | the div element that contains second hand            |

## Styling

| class name | description                      | role                                  |
| ---------- | -------------------------------- | ------------------------------------- |
| `.body`   | sets style for the position of the clock on the page | sets the clock in the middle of the page |
| `.clock`     | sets styles for the whole clock | makes the image of the clock |
| `.clock-face` | styles the interface of the clock | creates styles and position for clock hands               |
| `.hand`      | sets styles for hands of the clock    |  creates styles for hands       |


## Script

| type              | description       | role           |
| ----------------- | ----------------- | ------------------ |
| `setDate` | set minutes, seconds and hours of current time | create a function to display current time|
