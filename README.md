
# ARB Converter

[![pub package](https://img.shields.io/pub/v/like_button.svg)](https://pub.dartlang.org/packages/like_button) [![GitHub license](https://img.shields.io/github/license/fluttercandies/like_button)](https://github.com/fluttercandies/like_button/blob/master/LICENSE)

This package can used for crate multiple language arb file easily.



## Installation

To use ARB Converter, add it to your dependencies in `pubspec.yaml`:
```yaml
dependencies :
  arb_converter : ^0.0.1
```

## Usage

- crate arb_converter.yaml with
 ```yaml
default_loc: "assets/en.arb"
default_lang: "en"
output: "assets/"
languages:
  hi: intl_hi
  ml: intl_ml
 ```
- set the default arb file and run th following command

```dart    
 dart run arb_converter
```  


## Issues and feedback

Please file issues and feedback using the Github issues page for this repository.

If you have any suggestions or feedback, please send an email to __chegz.dev@gmail.com__ and we'll be happy to hear from you!
