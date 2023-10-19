
## Install Bootstrap CSS with React, Vue, Svelte

[React](https://react-bootstrap.netlify.app/docs/getting-started/introduction)


Create your project
```bash
  npm create vite@latest
  cd my-project
```

Install Bootstrap CSS 
```bash
  npm install react-bootstrap bootstrap
```

main.tsx
```bash
import 'bootstrap/dist/css/bootstrap.min.css';
```


Test
```bash
<div className="alert alert-warning" role="alert">
    A simple dark alert—check it out!
</div>
```

---

[Vue](https://bootstrap-vue.org/docs)

Create your project
```bash
  npm create vite@latest
  cd my-project
```

Install Bootstrap CSS
```bash
  npm install vue bootstrap bootstrap-vue
```

```bash
  yarn add vue bootstrap bootstrap-vue
```

import to main.js
```bash
import 'bootstrap/dist/css/bootstrap.css'
import 'bootstrap-vue/dist/bootstrap-vue.css'
```

Test
```bash
<div className="alert alert-warning" role="alert">
    A simple dark alert—check it out!
</div>
```

---

[Svelte](https://sveltestrap.js.org/?path=/story/getting-started-get-started--get-started)

Create your project
```bash
  npm create vite@latest
  cd my-project
```

Install Bootstrap CSS
```bash
  npm install bootstrap
```

main.ts
```bash
  import 'bootstrap/dist/css/bootstrap.min.css';
```

Test
```bash
  <div class="alert alert-warning" role="alert">
      A simple dark alert—check it out!
  </div>
```
