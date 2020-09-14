# AngularLibrary
Angular module that demonstrates the concept of designing an npm library.
More information can be found [here](https://www.npmjs.com/package/@samuel-wahome/nglib).

## Install
First, you have to install the module through npm:
`npm i @samuel-wahome/nglib`

Afterwards you need to import the `NglibModule` in your module:
```javascript
import {NgModule} from'@angular/core';
import {NglibModule} from '@samuel-wahome/nglib';
 @NgModule({
  imports: [NglibModule]
})
export class YourModule {};
```
# Example
```<lib-nglib></lib-nglib>```
