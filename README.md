LiveScript Major Mode
=======================

An Emacs major mode for [LiveScript][ls], a language that compiles to
JavaScript.

Provides syntax highlighting, indentation support, imenu support,
a menu bar, and a few cute commands.

As LiveScript is a fork of Coco, which is a fork of CoffeeScript, this
mode is a fork of [coffeescript-mode][csm].

## imenu

If you're using imenu, `livescript-mode` should work just fine. This
means users of [textmate.el][tm] will find that `⇧⌘T`
(`textmate-go-to-symbol`) mostly works as expected.

If you're not using imenu check out [this page][im] or textmate.el for
a really awesome way to jump quickly to a function's definition in a
file.

## Commands

If you have `easymenu` you can get to any of these commands from the
menu bar.

## Bugs

Please file bugs at <http://github.com/bdowning/livescript-mode/issues>

[ls]: http://livescript.net/
[csm]: https://github.com/defunkt/coffee-mode
[tm]: http://github.com/defunkt/textmate.el
[im]: http://chopmo.blogspot.com/2008/09/quickly-jumping-to-symbols.html
