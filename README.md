# WHU-BeamerTemplate (武汉大学主题Beamer模板)

![LaTeX Validation](https://github.com/T0nyX1ang/WHU-BeamerTemplate/workflows/LaTeX%20Validation/badge.svg)
![Releases](https://img.shields.io/github/v/release/T0nyX1ang/WHU-BeamerTemplate)

## Introduction

This beamer template is designed for slides using beautiful spots in Wuhan University. To use this template, please use `\usetheme{WHUSpot}` in the preamble. As you can see, this template is made for my beloved school.

## Usage

* Download this template on Github. If you want to use a stable version, please refer to the [Release page](https://github.com/T0nyX1ang/WHU-BeamerTemplate/releases), if you want to find out the latest build, please refer to the [Github Action page](https://github.com/T0nyX1ang/WHU-BeamerTemplate/actions) for successful builds.
* Make sure you have installed TeX Live (greater than TeX Live 2018). Lower TeX Live versions may be acceptable, but they were not tested.
* Compile `demo-default.tex` with **XeLaTeX**, and `demo-default.pdf` will be generated.
 
## Further Customizations
* Building this project on Overleaf (With XeLaTeX) is also acceptable.
* If you want to globally install this template, please create a folder named `beamertheme-WHUSpot`, put `/colors`, `/models`, `beamerthemeWHUSpot.sty` and `import.sty` into it, move this folder inside `$TEXMF/tex/latex` folder and run `texhash`.
* If you want to design your own color styles, please refer to `/color` folder and provide all of the required commands.

## Contribution

* Open an issue if you encounter a bug or want to propose new features.
* Pull requests are **greatly** welcomed, and they will be validated with several tests.

## License

* This project (excluding the Logo of Wuhan University) is licensed under LaTeX Project Public License, version 1.3c or later. See `LICENSE` and `MANIFEST` for more details.
* Wuhan University maintains the copyright of The Logo of Wuhan University, which should not be used in ANY COMMERCIAL PRODUCTS.
* `import.sty` is free of restriction in distribution, and we put this file to handle backwards compatibility in loading models and color styles.

## More details

* Refer to the `demo-default.pdf` that has been compiled by yourself, or see the [Github Action page](https://github.com/T0nyX1ang/WHU-BeamerTemplate/actions) for 
`demo-document` artifacts.
