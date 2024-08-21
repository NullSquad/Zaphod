# Zaphod &middot; [![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/NullSquad/Zaphod/blob/main/LICENSE)

Zaphod is the multi-faceted, multi-purpose JavaScript library that makes building user interfaces as cool and effortless as cruising through the galaxy with two heads and three arms!

* **Multi-Component Architecture:**: Build reusable, self-contained components that can be assembled into complex UIs.
* **Virtual DOM:** Experience fast, efficient rendering with Zaphod's virtual DOM implementation, ensuring smooth and responsive interfaces.
* **State Management:** Manage state with simplicity and elegance, allowing for reactive and dynamic user experiences.
* **Minimalistic and Modular:** Zaphod is designed to be minimal yet powerful, offering core functionality without unnecessary bloat.

## Examples

```js
import { createRoot } from 'zaphod-dom/client';

// Clear the existing HTML content
document.body.innerHTML = '<div id="app"></div>';

// Render your Zaphod component instead
const root = createRoot(document.getElementById('app'));
root.render(<h1>Hello, world</h1>);
```

This example will render "Hello, world" into the page.

### License

Zaphod is [MIT licensed](./LICENSE).
