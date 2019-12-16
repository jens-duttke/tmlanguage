# Schema for `tmLanguage` files

This is a [JSON&nbsp;schema](https://json-schema.org) for [TextMate&nbsp;grammar](https://macromates.com/manual/en/language_grammars) definitions.

Can be used to get intellisense working when editing grammar definitions within [Visual&nbsp;Studio&nbsp;Code](https://code.visualstudio.com/).

## About this fork

This fork contains some improvements over the original code by Martin Ring, like

- Disallow additional props in pattern definition to prevent typos like "pattern" instead of "patterns"
- Correctly specify "while" and "whileCapture"
- Specify the possible values for "include"
- Allow additional properties in document root
- Some smaller fixes
