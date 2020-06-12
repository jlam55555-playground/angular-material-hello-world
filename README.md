# angular-material-hello-world
Learning how to use @angular/material

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 9.0.6.

### Creating this module
```shell script
$ ng new PROJECT_NAME
$ ng add @angular/material
```
and then you need to import all of the angular modules you would like to use, e.g. (`src/app/material/material.module.s`).
```javascript
import { MatButtonModule } from '@angular/material/button';
import { MatCheckboxModule } from '@angular/material/checkbox';
import { MatIconModule } from '@angular/material/icon';
// ...

@NgModule({
  imports: [
    MatButtonModule,
    MatCheckboxModule,
    MatIconModule,
    // ...
  ],
  exports: [
    MatButtonModule,
    MatCheckboxModule,
    MatIconModule,
    // ...
  ]
})
export class MaterialModule { }
```
and import `MaterialModule` into your main app module.
