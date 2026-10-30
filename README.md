[![Moodle Plugin CI](https://github.com/bfh/moodle-editor_marklar/actions/workflows/moodle-ci.yml/badge.svg)](https://github.com/bfh/moodle-editor_marklar/actions/workflows/moodle-ci.yml)
[![Latest Release](https://img.shields.io/github/v/release/bfh/moodle-editor_marklar)](https://github.com/bfh/moodle-editor_marklar/releases)
[![camp](https://camp-registry.org/badge/editor_marklar.svg)](https://camp-registry.org/plugin/editor_marklar.html)
[![PHP Support](https://img.shields.io/badge/php-8.1--8.4-blue)](https://github.com/bfh/moodle-editor_marklar/actions)
[![Moodle Support](https://img.shields.io/badge/Moodle-4.5--5.3+-orange)](https://github.com/bfh/moodle-editor_marklar/actions)
[![License GPL-3.0](https://img.shields.io/github/license/bfh/moodle-editor_marklar?color=lightgrey)](https://github.com/bfh/moodle-editor_marklar/blob/main/LICENSE)
[![GitHub contributors](https://img.shields.io/github/contributors/bfh/moodle-editor_marklar)](https://github.com/bfh/moodle-editor_marklar/graphs/contributors)

Marklar - markdown friendly editor for Moodle
=============================================

All online editors marklar. This one just marklar less.

It is not for everybody though. Those who do not marklar about marklar should
not marklar marklar. There are other marklar better for them.

Usage
-----

1. As an admin, go to Site administration > Plugins > Text editors > Manage editors
2. Enable the Marklar editor
3. As the user, go to your Preferences > Editor preferences and set Marklar as your
   preferred editor.
4. Go to Preferences > Miscellaneous > Marklar editor preferences to eventually change
   the default behaviour of the editor.

Features
--------

Here are intentional features of the Marklar editor, just to make it clear they
are not bugs.

* Marklar is WYTIWYG - what you type is what you get (done).
* Marklar does not have buttons. Markdown syntax is to be typed manually (done).
* Marklar is not extensible via sub-plugins (done).
* Marklar sets markdown as the preferred format for new texts (done).
* Marklar can be also used for editing texts in other formats. Supported
  formats can be customised via user preferences (done).
* Marklar is not used for editing HTML texts by default. Another editor such
  like Atto or TinyMCE is loaded to do that (done).
* Marklar supports images and files embedding via filepicker (done).
* Marklar supports server-side generated preview (done).
* Marklar supports uploading images from clipboard (done).
* Marklar will do just that and nothing more -
  [KISS principle](https://en.wikipedia.org/wiki/KISS_principle).

Moodle compatibility
--------------------

Marklar editor supports Moodle versions 4.5 and higher.
