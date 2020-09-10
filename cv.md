# Maxim Ryabykh

![Maxim Ryabykh](https://avatars2.githubusercontent.com/u/17301466?s=460&u=4a6f5796c53fb2f519189a0a9eecc2884e8e0f9d&v=4)

## Contacts

**email:** [_ryabykhms@gmail.com_](mailto:ryabykhms@gmail.com)

**tg:** [_@setliststack_](tg://resolve?domain=setliststack)

## Summary

I constantly study something new and enjoy this process. Any work is done by me responsibly, paying attention to detail. My current goal is to become a strong front-end developer.

## Skills

### Markup Languages

- Html
- Xml
- Yml
- Css

### Programming Languages

- PHP
- Javascript
- Pine Script
- Java
- Python

### Frameworks

- Laravel
- React

### Methodologies

- OOP
- BEM

### Version Control

- Git

### Tools

- IDE WebStorm
- IDE VS Code
- IDE PHPStorm

## Code Examples

### From Git

- [Tic Tac Toe](https://github.com/ryabykhms/tic-tac-toe) - tic tac toe game, created by React.js
- [Js Calc Parser](https://github.com/ryabykhms/js-calc-parser) - parser mathematical operations from a string, created by Vanilla.js
- [React Calculator](https://github.com/ryabykhms/react-calc) - calculator, created by React.js
- [React Todo App](https://github.com/ryabykhms/react-todo-app) - todo application from [youtube course](https://www.youtube.com/watch?v=2vujABNBFAY&list=PLNkWIWHIRwME_Gv2vlWAR6TfeSXylYfw4), created by React.js with Redux.js

### For Fun

Code by Pine Script language. It is an indicator based on the breakout of the Bollinger Bands:

```
//@version=3
study("BBAA", overlay=true)
bars_count = input(defval=24, title='Bars Count', type=integer, minval=10, maxval=100)
isHigh = 0
isLow = 0
if (highestbars(high, bars_count) == 0)
    isHigh := 1
if (lowestbars(low, bars_count) == 0)
    isLow := 1
plotshape(isHigh, style=shape.triangledown, color=red)
plotshape(isLow, style=shape.triangleup, location=location.belowbar, color=green)
alertcondition(isHigh == 1, 'BBAA DOWN!', 'DOWN')
alertcondition(isLow == 1, 'BBAA UP!', 'UP')
```

## Experience

- Youtube courses by [Yauhen Kovalchuk](https://www.youtube.com/channel/UCE9ODjNIkOHrnSdkYWLfYhg), [Vladilen Minin](https://www.youtube.com/channel/UCg8ss4xW9jASrqWGP30jXiw) and many others.
- Java Junior Developer. Institute of High Technologies (June 2015 - September 2016):
  - Unit and UI testing the application for the system of operational management of the company.
  - Unit testing applications for monitoring transformer substations.
  - Writing modules for backend applications for monitoring transformer substations
- Freelance (2017 - present):
  - PHP scripts for automatization
  - Site parsers
  - Asterisk call parsers
  - Exchange bots
  - Telegram bots
  - Wordpress sites
  - Wordpress plugins
  - Tradingview indicators and strategies
  - And much more.

## Education

- Belgorod National Research University Bachelor of Science (BS), Computer science, 2012-2016
- Belgorod National State University Master of Computer Applications (MCA), 2016-2018

## English

- Pre-Intermediate (A2)
