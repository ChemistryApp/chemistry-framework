# Chemistry Framework

[![Bower version](https://badge.fury.io/bo/chemistry-framework.svg)](http://badge.fury.io/bo/chemistry-framework)
[![GitHub version](https://badge.fury.io/gh/ChemistryApp%2Fchemistry-framework.svg)](http://badge.fury.io/gh/ChemistryApp%2Fchemistry-framework)

A front-end framework with assets to be able to scaffold and prototype screens for the Chemistry iPad application.

### Fonts

This framework utilizes the [Merriweather Sans](https://www.google.com/fonts/specimen/Merriweather+Sans) typeface family from [Google Fonts](https://www.google.com/fonts).

If you would like to use a different typeface, you will need to redefine the global font-family for 3 elements:

* body
* button, .button
* input[type="text"], input[type="email"], input[type="password"], input[type="tel"], input[type="number"], textarea

like so:

```
[ELEMENT] {
    font-family: '[YOUR FONT NAME]', sans-serif;
}
```

### Dependencies

The following code sets are dependencies. Refer to their respective documentation for support.

* [Ionicons](https://github.com/driftyco/ionicons)
