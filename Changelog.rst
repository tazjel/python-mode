Changelog
=========

## 2012-01-17 0.5.5
-------------------
* Add a sign for info messages from pylint.
  (c) Fredrik Henrysson
* Change motion keys: vic - viC, dam - daM and etc
* Add 'g:pymode_lint_onfly' option

## 2012-01-09 0.5.3
-------------------
* Prevent the configuration from breaking python-mode
  (c) Dirk Wallenstein

## 2012-01-08 0.5.2
-------------------
* Fix ropeomnicompletion
* Add preview documentation

## 2012-01-06 0.5.1
-------------------
* Happy new year!
* Objects and motion  fixes

## 2011-11-30 0.5.0
-------------------
* Add python objects and motions (beta)
  :h pymode_motion

## 2011-11-27 0.4.8
-------------------
* Add `PyLintWindowToggle` command
* Fix some bugs

## 2011-11-23 0.4.6
-------------------
* Enable all syntax highlighting
  For old settings set in your vimrc:
    let g:pymode_syntax_builtin_objs = 0
    let g:pymode_syntax_builtin_funcs = 0

* Change namespace of syntax variables
  See README

## 2011-11-18 0.4.5
-------------------
* Add 'g:pymode_syntax' option
* Highlight 'self' keyword

## 2011-11-16 0.4.4
-------------------
* Minor fixes

## 2011-11-11 0.4.3
-------------------
* Fix pyflakes

## 2011-11-09 0.4.2
-------------------
* Add FAQ
* Some refactoring and fixes

## 2011-11-08 0.4.0
-------------------
* Add alternative code checker "pyflakes"
  See :h 'pymode_lint_checker'
* Update install docs

## 2011-10-30 0.3.3
-------------------
* Fix RopeShowDoc

## 2011-10-28 0.3.2
-------------------
* Add 'g:pymode_options_*' stuff, for ability
  to disable default pymode options for python buffers

## 2011-10-27 0.3.1
-------------------
* Add 'g:pymode_rope_always_show_complete_menu' option
* Some pylint fixes

## 2011-10-25 0.3.0
-------------------
* Add g:pymode_lint_minheight and g:pymode_lint_maxheight
  options
* Fix PyLintToggle
* Fix Rope and PyLint libs loading

## 2011-10-21 0.2.12
--------------------
* Auto open cwindow with results
  on rope find operations

## 2011-10-20 0.2.11
--------------------
* Add 'pymode_lint_jump' option

## 2011-10-19 0.2.10
--------------------
* Minor fixes (virtualenv loading, buffer commands)

## 2011-10-18 0.2.6
-------------------
* Add <C-space> shortcut for macvim users.
* Add VIRTUALENV support

## 2011-10-17 0.2.4
-------------------
* Add current work path to sys.path
* Add 'g:pymode' option (disable/enable pylint and rope)
* Fix pylint copyright
* Hotfix rope autocomplete

## 2011-10-15 0.2.1
-------------------
* Change rope variables (ropevim_<name> -> pymode_rope_<name>)
* Add "pymode_rope_auto_project" option (default: 1)
* Update and fix docs
* 'pymode_rope_extended_complete' set by default
* Auto generate rope project and cache
* "<C-c>r a" for RopeAutoImport

## 2011-10-12 0.1.4
-------------------
* Add default pylint configuration

## 2011-10-12 0.1.3
-------------------
* Fix pylint and update docs

## 2011-10-11 0.1.2
-------------------
* First public release
