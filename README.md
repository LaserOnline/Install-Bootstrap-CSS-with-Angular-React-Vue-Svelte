
## Install Bootstrap CSS with Angular React, Vue, Svelte

[React](https://react-bootstrap.netlify.app/docs/getting-started/introduction)


Create your project
```bash
  npm create vite@latest
  cd my-project
```

npm Install Bootstrap 
```bash
  npm install react-bootstrap bootstrap
```

yarn Install Bootstrap 
```bash
  yarn install react-bootstrap bootstrap
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

npm Install Bootstrap
```bash
  npm install vue bootstrap bootstrap-vue
```

yarn Install Bootstrap
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

npm Install Bootstrap
```bash
  npm install bootstrap
```

yarn Install Bootstrap
```bash
  yarn install bootstrap
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
---

[Angular]([https://bootstrap-vue.org/docs](https://www.freecodecamp.org/news/how-to-add-bootstrap-css-framework-to-an-angular-application/))

Icon Bootstrap
```bash
npm install bootstrap bootstrap-icons
```

import in angular.json
```bash
"styles": [
  "node_modules/bootstrap-icons/font/bootstrap-icons.css",
],
```

```bash
ng add @ng-bootstrap/ng-bootstrap
```

```bash
npm install ngx-bootstrap --save
```

app.module.ts
```bash
import { NgModule } from '@angular/core';
import { BrowserModule } from '@angular/platform-browser';
import { ModalModule } from 'ngx-bootstrap/modal';
import { AppRoutingModule } from './app-routing.module';
import { AppComponent } from './app.component';
import { NgbModule } from '@ng-bootstrap/ng-bootstrap';

@NgModule({
  declarations: [
    AppComponent
  ],
  imports: [
    BrowserModule,
    ModalModule.forRoot(),
    AppRoutingModule,
    NgbModule
  ],
  providers: [],
  bootstrap: [AppComponent]
})
export class AppModule { }
```

angular.json

css
```bash
"node_modules/bootstrap/dist/js/bootstrap.bundle.min.js"
"node_modules/bootstrap/css/bootstrap.css",
"src/styles.css",
```

scss
```bash
"node_modules/bootstrap/dist/js/bootstrap.bundle.min.js"
"node_modules/bootstrap/scss/bootstrap.scss",
"src/styles.scss"
```

sass
```bash
"node_modules/bootstrap/dist/js/bootstrap.bundle.min.js"
"node_modules/bootstrap/sass/bootstrap.sass",
"src/styles.sass"
```

Test
```bash
<div class="alert alert-warning" role="alert">
    A simple dark alert—check it out!
</div>
```

---
