![Pub Version (including pre-releases)](https://img.shields.io/pub/v/console_bars?include_prereleases)
![GitHub last commit](https://img.shields.io/github/last-commit/RohitEdathil/ConsoleBars)
![GitHub language count](https://img.shields.io/github/languages/count/RohitEdathil/ConsoleBars)
![GitHub top language](https://img.shields.io/github/languages/top/RohitEdathil/ConsoleBars)

A package for creating an awesome progress bar in console.

## Usage

Code:

```dart
final p = FillingBar(desc: "Loading", total: 1000, time: true, percentage:true);
  for (var i = 0; i < 1000; i++) {
    p.increment();
    sleep(Duration(milliseconds: 10));
  }
```

Result:

![Animation](https://github.com/RohitEdathil/ConsoleBars/blob/master/img/Animation.gif)
```
Loading : ████████████████████████████████████████.................... 673/1000 67.3% [ 0:00:13.28 / 0:00:06.45 ]
```
