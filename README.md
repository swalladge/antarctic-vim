# Antarctic Vim

A bleak, functional colorscheme with a splash of colour where needed.

Copyright © 2019 Samuel Walladge


## About

A light colour scheme designed to be functional. It is not designed to look
pretty, but rather be readable in high glare conditions, use little coloured
text (inspired by `syntax off` and semantic highlighting), and not include any
eye-straining colour/contrast combinations.

Should work out of the box for 256 colour terminals and 24bit gui/terminals.
If something doesn't look quite right, please open and issue with a description
of the problem and ideally a screenshot.

Inspired by numerous web articles about light colour themes and less colourful
syntax highlighting. I don't expect anyone else to like or use this. It's
published on GitHub so I can install it with the rest of the Vim plugins I use.
Most colour and typography choices are arbitrary and reflect my whims or
laziness.

## Screenshots

![](https://static.swalladge.net/vim/antarctic-vim/screenshot1.png)

![](https://static.swalladge.net/vim/antarctic-vim/screenshot2.png)

![](https://static.swalladge.net/vim/antarctic-vim/screenshot3.png)


## Installation

`:h packages` or use a package manager of your choice.


## Usage

```
:colorscheme antarctic
```


## Configuration

There is no configuration. If you want to customize the colours, you are free
to fork the repository and make changes as you wish (see development info
below). Please consider making a pull request back to the original repository
if you feel your changes may benefit the wider community.


## Development

This colour scheme is developed using
[romainl](https://github.com/romainl/)'s [erb
template](https://gist.github.com/romainl/5cd2f4ec222805f49eca). Ruby must be
installed (for the `erb` command).

Edit the variables in `colors/paper.erb` and run `make` to build
`colors/antarctic.vim`. `colors/antarctic.vim` should not be edited directly.



## License

```
The MIT License (MIT)

Copyright (c) 2019 Samuel Walladge

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```
