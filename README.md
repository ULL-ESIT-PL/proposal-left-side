# Function expressions on the left side of assignments

Provides assignable functions that are curried and can be partially modified like in `f(2) = 3`

## Status

This proposal is currently an  internal draft. 

## Contributors 

There are no champions at this time. People involved:

- Pablo Santana González 
- Adrián Mora Rodríguez
- Casiano Rodríguez León ([@crguezl](https://github.com/crguezl))
- Coromoto León Hernández ([@coromoto](http://github.com/coromoto)

## Overview / Motivation


### Principles:


## Specification Text

Has to be written s.t. like in [here](https://tc39.es/proposal-temporal/).

## Documentation

Reference documentation and examples can be found below.

- [Temporal Documentation (English)](https://tc39.es/proposal-temporal/docs/index.html)

A cookbook to help you get started and learn the ins and outs of Temporal is available [here](https://tc39.es/proposal-temporal/docs/cookbook.html)

## Implementations

| Polyfill                                                                         | Repo                                                                                | Status                  |
| -------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------- | ----------------------- |
| **[@js-temporal/polyfill](https://www.npmjs.com/package/@js-temporal/polyfill)** | [js-temporal/temporal-polyfill](https://github.com/js-temporal/temporal-polyfill)   | Alpha release available |
| **[temporal-polyfill](https://www.npmjs.com/package/temporal-polyfill)**         | [fullcalendar/temporal-polyfill](https://github.com/fullcalendar/temporal-polyfill) | Beta release available  |

If you're working on a polyfill, please file an issue or PR so we can add yours here.

A [non-production polyfill](./polyfill) was built to validate this proposal.
This polyfill continues to live in this repo, but only for the purposes of running tests and powering the documentation "playground" as described below.

**DO NOT use this polyfill in your own projects!
Instead, please use a polyfill from the table above.**

## Documentation Playground

When viewing the [reference documentation](https://tc39.es/proposal-temporal/docs/index.html), the non-production polyfill is automatically loaded in your browser, so you can try out Temporal by opening your browser's developer tools console.
