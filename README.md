# MyAtomFiles

This repo contains my atom configuration files.

![MyAtom](.img/atom.png)

## Usage

The used packages are in `myPackages.txt`, use `apm` to install them:

```
apm install --packages-file myPackages.txt
```

## External programs for packages

- For `linter`:
    - `linter-php`: `php`<sup>[B](#B)</sup>
    - `linter-scss-lint`: `scss_lint`<sup>[R](#R)</sup>
    - `linter-shellcheck`: `shellcheck`<sup>[B](#B)</sup>
    - `linter-tidy`: [`tidy5`](http://www.htacg.org/tidy-html5/)
    - `linter-gcc`: `gcc` & `g++`<sup>[B](#B)</sup>
- For `script`
    - `bash`<sup>[B](#B)</sup>
    - `coffeescript`<sup>[N](#N)</sup>
    - `php`<sup>[B](#B)</sup>
    - `python`<sup>[B](#B)</sup>
    - `sass`<sup>[N](#N)</sup>
- For `atom-fuzzy-grep`: `ag`<sup>[B](#B)</sup>, The Silver Searcher.

-----------------------------

*<a id="B"><sup>B</sup></a> Present by default or easily installable on your system.*

*<a id="R"><sup>R</sup></a> A ruby gem: `gem install rubyGem`*

*<a id="N"><sup>N</sup></a> A npm package: `npm -g install npmPackage`*
