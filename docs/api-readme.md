# LitElement API Documentation

## Install @polymer/lit-element

```
npm install --save @polymer/lit-element@^1.0.0
```

## Modules

### [lit-element](/api/modules/_lit_element_.html)

Contains LitElement base class. Import `LitElement` and `html` from this module to create a component:

```js
import { LitElement, html } from '@polymer/lit-element';

class MyElement extends LitElement {
  render() {
      return html`<p>your template here</p>`;
  }
}

customElements.define('my-element', MyElement);
```

Inherits API functionality from [updating-element](#updating-element).

### [updating-element](/api/modules/_lib_updating_element_.html)

Custom Element base class that supports declaring observable properties, reflecting attributes to properties, and the core update lifecycle methods.