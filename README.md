[![Melpa Status](http://melpa.org/packages/flymake-easy-badge.svg)](http://melpa.org/#/flymake-easy)
[![Melpa Stable Status](http://stable.melpa.org/packages/flymake-easy-badge.svg)](http://stable.melpa.org/#/flymake-easy)

flymake-easy.el
===============

Helpers for easily building Emacs flymake checkers.

Installation
=============

If you choose not to use one of the convenient packages in
[Melpa][melpa] and [Marmalade][marmalade], you'll need to add the
directory containing `flymake-easy.el` to your `load-path`, and then
`(require 'flymake-easy)`.

Usage
=====

This library provides the `flymake-easy-load` helper function for
setting up flymake checkers. Just call that function with the
appropriate arguments in a major mode hook function.

See [`flymake-ruby`](https://github.com/purcell/flymake-ruby) for an
example.

[marmalade]: http://marmalade-repo.org
[melpa]: http://melpa.org

<hr>

[💝 Support this project and my other Open Source work](https://www.patreon.com/sanityinc)

[💼 LinkedIn profile](https://uk.linkedin.com/in/stevepurcell)

[✍ sanityinc.com](http://www.sanityinc.com/)
