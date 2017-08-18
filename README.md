# &lt;status-indicator/&gt;

A web component to show status indicator as colored dots. [Demo](https://2z6nk70qx0.codesandbox.io/)

## Install

```bash
npm i status-indicator
```

## Usage

Import status-indicator.css in your CSS or JavaScript

```css
@import 'status-indicator'
```

```javascript
import 'status-indicator/styles.css'
```

```html
<status-indicator></status-indicator>
```

### API

```html
<status-indicator active|positive|intermediary|negative|pulse></status-indicator>
```

You are able to customize the dot by CSS variables, default configuration is listed below.

```css
:root {
  --status-indicator-color: 216, 226, 233;            /* #D8E2E9 */
  --status-indicator-color-active: 0, 149, 255;       /* #0095FF */
  --status-indicator-color-positive: 75, 210, 143;    /* #4BD28F */
  --status-indicator-color-intermediary: 255, 170, 0; /* #FFAA00 */
  --status-indicator-color-negative: 255, 77, 77;     /* #FF4D4D */
  --status-indicator-size: 10px;
  --status-indicator-animation-time: 2s;
  --status-indicator-pulse-start-alpha: .5;
  --status-indicator-pulse-end-alpha: 0;
}
```

### LICENSE

MIT