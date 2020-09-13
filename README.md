# AngularLibrary
Angular module that demonstrates the concept of designing a library.

## Install
First, you have to install the module through npm:
`npm i @samuel-wahome/nglib`

Afterwards you need to import the `NglibModule` in your module:
```import {NgModule} from'@angular/core';
import {NglibModule} from '@samuel-wahome/nglib';
 @NgModule({
  imports: [NglibModule]
})
export class YourModule {};
```
# Example
```<lib-nglib></lib-nglib>```
