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
angular.module('myApp', ['ion-time-picker']);
```

You can now use the directive, add the attribute to your existing DOM element in HTML:
```html
<input type="text" ng-model="value" ion-time-picker>
```

## Directive Attributes

- `id (optional)` - Give a unique id to the bound element and drawer will be named {{id}}-drawer
- `ng-model` (optional) - Define the model to bind the selected value to. the value of the model is displayed once drawer is open
- `ng-change` (optional) - method called after the value has been set
- `sensitivity (optional)` - Define the scroll sensitivity
- `step` (optional) - The distance between two displayed values for minutes, default is 5 minutes
- `ngDefault` (optional) - if ng-model is null then time selector open on this time as selected. If displaying with AM/PM format is of type: HH:MM AA
- `control` (optional) - control element to control directive from outside (see notes for details)
- `hasClear` (optional) - Whether drawer has clear button or not, if does value set to zero
- `isWithDaytime` (optional) - Is hour with AM/PM of 24H display. If not set uses browser setting
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

## Purchase Link
[https://gum.co/dCcov](https://gum.co/dCcov)

## What's included
Upon purchase you'll receive a minimized js file and minimized css for immediate use

## License
Use only by person/business specified in payment for one or more end products
TODO
