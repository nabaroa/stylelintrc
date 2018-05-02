# .stylelintrc

Add the `.stylelintrc`file on the root of your project in order to have a config
file to lint the styles.

[Stylelint info](https://stylelint.io/user-guide/cli/)

## How to use

`npm install -g stylelint`

Autofixing errors:

`stylelint "foo/**/*.css | less | scss" --fix`

The errors that couldn´t be fixed appear on the console and must be fixed by hand.

## About the rules

The rules used in `.stylelintrc`is a mix between [stylelint-config-recommended](https://github.com/stylelint/stylelint-config-recommended)
and [stylelint-config-standard](https://github.com/stylelint/stylelint-config-standard)
