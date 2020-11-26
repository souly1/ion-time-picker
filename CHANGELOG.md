#2.6.1 (2020-11-26)#

Bug Fixes:

 Taking ng-disabled into consideration
 
#2.6.0 (2019-12-01)#

Bug Fixes:

 Removed hammer js

#2.5.0 (2017-03-22)#

Features:

- Added support to manually load DOM elements and events using the control method 'prepareDom'
- Added ability to specify we want to delete drawer DOM element and events on drawer close using directive attribute 'deleteOnClose'

#2.2.1 (2016-03-02)#

 Bug Fixes:

 - class naming with spaces caused issues

#2.2.0 (2016-10-22)#

Features:

- Refactoring clicking event

Bug Fixes:

- Better iOS support
#2.1.0 (2016-10-15)#

Features:

- Added support for IOS 10

#2.0.5 (2016-09-07)#

Features:

- Ability to define when to open drawer full screen given the device height using new attribute 'openPartScreenDrawerBarrier'

#2.0.4 (2016-07-27)#

Bug Fixes:

- Supporting more browser types causing an issue retrieving selected value from ng-modal

#2.0.3 (2016-07-27)#

Features:

- Clicking Android hardware back button closes drawer

#2.0.1 (2016-07-21)#

Bug Fixes:

- Issues when using var module = angular.module in code with the directives, things would start to break.

#2.0.0 (2016-07-14)#

Features:

- Added change log
- **BREAKING CHANGE**: module name changed to: `ion-pickers`
- **BREAKING CHANGE**: changed classes `inp-content` & `inp-container` to `ios-content` & `ios-container`

Bug Fixes:

- Issue with `getCurrentSelection` ran on elements prior to opening drawer

#1.2.3 (2016-07-03)#

Bug Fixes: 

- Fixed issue with values in certain situations would not write to ngModel
