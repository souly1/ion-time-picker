# ion-time-picker

An ionic/angular time picker (spinner) which is developed in web technologies but looks similar to native.

## Requirements

- Angular 1.*

## ScreenShots
![alt tag](/screenshots/itp1.gif)
![alt tag](/screenshots/itp2.gif)
![alt tag](/screenshots/screenshot1.png)
![alt tag](/screenshots/screenshot2.png)

## Usage

- Add CSS and JS to project:

```html
<link rel="stylesheet" href="wherever-you-put-it/ionTimePicker.min.css">

<script type="text/javascript" src="wherever-you-put-it/ionTimePicker.min.js"></script>
```

Add dependencies on the `ion-time-picker` AngularJS module:

```javascript
angular.module('myApp', ['ion-pickers']);
```

You can now use the directive, add the attribute to your existing DOM element in HTML:
```html
<input type="text" ng-model="value.time" ion-time-picker>
```

## Directive Attributes

- `id (optional)` - Give a unique id to the bound element and drawer will be named {{id}}-drawer
- `ng-model` (optional) - string. Define the model to bind the selected value to. the value of the model is displayed once drawer is open. 
- `ng-change` (optional) - method called after the value has been set
- `sensitivity (optional)` - Define the scroll sensitivity
- `step` (optional) - The distance between two displayed values for minutes, default is 5 minutes
- `openPartScreenDrawerBarrier (optional)` - define the device height in pixels where any value higher than it will open drawer partially and not full screen. use 0 to always open as parital drawer. default is 420px
- `ngDefault` (optional) - if ng-model is null then time selector open on this time as selected. If displaying with AM/PM format is of type: HH:MM AA
- `control` (optional) - control element to control directive from outside (see notes for details)
- `hasClear` (optional) - Whether drawer has clear button or not, if does value set to zero
- `isWithDaytime` (optional) - Is hour with AM/PM of 24H display. If not set uses browser setting
- `deleteOnClose` (optional) - Whether to remove DOM elements and event registration on close of drawer. Better user with many drawers that have a large number of elements Default is false
- `onSet` (optional) - event fired when set button clicked, model is set value. Has two params oldValue and newValue, If returning false from method set canceled. IMPORTANT: only pass method name without brackets
- `onCancel` (optional) - event fired when cancel button clicked. IMPORTANT: only pass method name without brackets
- `onClear` (optional) - event fired when clear button clicked. IMPORTANT: only pass method name without brackets


## Notes

Valid values:
- Step must be a valid positive integer number under 60
- Control methods which can be called:
 * `openDrawer` - opens the time select drawer
 * `closeDrawer` - closes the time select drawer
 * `getCurrentSelection` - returns the current value displayed as selected in time select drawer
 * `isDrawerOpen` - is the drawer currently open or not
 * `prepareDom` - use to manually issue a creation of DOM elements which can be costly. Will do nothing if DOM element already exists.

## Purchase Link
[ion-time-picker](https://gum.co/dCcov)

## What's included
Upon purchase you'll receive a minimized js file and minimized css for immediate use

## License
Use only by person/business specified in payment for one or more end products
TODO
