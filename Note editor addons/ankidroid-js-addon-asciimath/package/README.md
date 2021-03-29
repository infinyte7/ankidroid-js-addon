# AnkiDroid js addon asciimath
Type less and use addon to convert to math jax

Convert ASCII math notation and (some) LaTeX to Presentation MathML

## Install
1. Download AnkiDroid.JS version from [release page](https://github.com/infinyte7/Anki-Android/releases)

2. Copy ```npm i ankidroid-js-addon-asciimath```

5. Paste in AnkiDroid
    
    `
    AnkiDroid -> Addons -> Import Addons
    `

6. Wait for installation to complete

7. Change note type from options menu to view reviewer / note editor addons

8. Turn on to use in reviewer / note editor

## Usage
1. Open note editor
2. Type equation (not mathjax but equation like in calculator)
3. Click bottom ```Σ``` (Sigma) button to convert

## Example
[Fourier transform](https://en.wikipedia.org/wiki/Fourier_transform)

```
hat f \(xi)=int_(-infty)^(infty)f(x)e^(-2pi x xi)dx
```

Converted to MathJax using js addon

```
\(\hat{{f}}{\left(\xi\right)}={\int_{{-\infty}}^{{\infty}}}{f{{\left({x}\right)}}}{e}^{{-{2}\pi{x}\xi}}{\left.{d}{x}\right.}\)
```

## Demo
<img src="https://raw.githubusercontent.com/infinyte7/ankidroid-js-addon/main/images/demo_ascii_math.gif" height=450></img>


## Learn more
- http://asciimath.org/
- https://en.wikipedia.org/wiki/AsciiMath

## License and Credits
### asciimathml
The project use following projects to convert asciimath to mathjax.
- https://github.com/asciimath/asciimathml
- https://github.com/asciimath/asciimathml/tree/master/asciimath-based
<br>
Copyright (c) 2014 Peter Jipsen and other ASCIIMathML.js contributors
<br>
MIT License

### ankidroid-js-addon-asciimath
Mani
<br>
MIT License