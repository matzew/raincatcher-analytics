# FeedHenry WFM Analytics

This module contains a set of Angular directives to represent analytics with flow and charts.

## Client-side usage

### Client-side usage (via broswerify)

#### Setup
This module is packaged in a CommonJS format, exporting the name of the Angular namespace.  The module can be included in an angular.js as follows:

```javascript
angular.module('app', [
, require('fh-wfm-analytics')
...
])
```

#### Directives

| Name | Attributes |
| ---- | ----------- |
| analytics-piechart | workers, workorders |
| analytics-barchart | workorders |
| analytics-areachart | workorders |

For a more complete example, please check the [demo portal app](https://github.com/feedhenry-staff/wfm-portal/tree/master/src/app/analytics).
