# &lt;status-indicator/&gt;

A web component to show status indicator as colored dots. [Demo](https://tnhu.github.io/status-indicator/).

![Screenshot](https://i.imgur.com/v1vJ3Ue.gif)

## Install

```bash
npm i status-indicator
```

## Usage

Import status-indicator.css in your CSS or JavaScript.

CSS:

```css
@import 'status-indicator'
```

JavaScript:

```javascript
import 'status-indicator/styles.css'
```

HTML/React:

```html
<status-indicator active pulse></status-indicator>
```

### API

```html
<status-indicator active|positive|intermediary|negative|pulse></status-indicator>
```

You are able to customize the dot by CSS variables, default configuration is listed below.

```css
:root {
  --status-indicator-size: 10px;
  --status-indicator-animation-duration: 2s;

  --status-indicator-color: rgb(216, 226, 233);
  --status-indicator-color-semi: rgba(216, 226, 233, .5);
  --status-indicator-color-transparent: rgba(216, 226, 233, 0);

  --status-indicator-color-active: rgb(0, 149, 255);
  --status-indicator-color-active-semi: rgba(0, 149, 255, .5);
  --status-indicator-color-active-transparent: rgba(0, 149, 255, 0);

  --status-indicator-color-positive: rgb(75, 210, 143);
  --status-indicator-color-positive-semi: rgba(75, 210, 143, .5);
  --status-indicator-color-positive-transparent: rgba(75, 210, 143, 0);

  --status-indicator-color-intermediary: rgb(255, 170, 0);
  --status-indicator-color-intermediary-semi: rgba(255, 170, 0, .5);
  --status-indicator-color-intermediary-transparent: rgba(255, 170, 0, 0);

  --status-indicator-color-negative: rgb(255, 77, 77);
  --status-indicator-color-negative-semi: rgba(255, 77, 77, .5);
  --status-indicator-color-negative-transparent: rgba(255, 77, 77, 0);
}
```

### Supported Browsers

Latest versions of Chrome/Firefox/Safari/IE/Opera.

### LICENSE

MIT