# Ionic-Base

***Ionic-Base*** is an Ionic App that included the base ionic-develop tech.

***NOTE:*** This was built alongside 3.3 of Ionic.

## Installation

```bash
npm install
```

## Requirements & Notes

* WKWebView - With UIWebView, scroll events don't continue firing after your finger has left the screen, and while scroll momentum is still in effect. This works in WKWebView.
* Crosswalk - I looked at Android without Crosswalk for about 2 minutes and doubt I'll spent more that that.
* Windows? - I don't know and haven't tested it at all.


## TODO

1. ~~Resize method.~~
2. Improve performance or provide fallback animation / cancellation for older devices.
   * Shrinkage works like butter on an iPhone 6s, but is janky on iPhone 5 and Galaxy S3 (with Crosswalk). Though both of those devices are from 2012, and possibly not worth fussing about.
   * Perfomance advice and device testing are welcome.
3. Hide footers & tabs.
4. Consider independently hiding toolbars within a header.


## Author

[Kim Wong](https://patrickmcd.com) ([Github](https://github.com/kimwong) / [Facebook](https://www.feacebook.com/f))

## Licence

This project is licensed under the MIT license. See the [LICENSE](LICENSE.md) file for more info.
