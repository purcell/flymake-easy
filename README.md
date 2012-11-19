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
[melpa]: http://melpa.milkbox.net

<hr>

[![](http://api.coderwall.com/purcell/endorsecount.png)](http://coderwall.com/purcell)

[![](http://www.linkedin.com/img/webpromo/btn_liprofile_blue_80x15.png)](http://uk.linkedin.com/in/stevepurcell)

[Steve Purcell's blog](http://www.sanityinc.com/) // [@sanityinc on Twitter](https://twitter.com/sanityinc)

