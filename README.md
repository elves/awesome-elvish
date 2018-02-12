# awesome-elvish

The official list of awesome unofficial Elvish modules.

## Packages (installable using [epm](https://elvish.io/ref/epm.html))

These packages include most of the modules listed below. You can
install them by typing `epm:install <package name>` and then load the
corresponding modules.

  * [github.com/muesli/elvish-libs](https://github.com/muesli/elvish-libs): various libraries and the Powerline theme by [muesli](https://github.com/muesli).
  * [github.com/xiaq/edit.elv](https://github.com/xiaq/edit.elv): collection of Elvish editor plugins, including [smart-matcher.elv](https://github.com/xiaq/edit.elv/blob/master/smart-matcher.elv) and completions for `go`.
  * [github.com/zzamboni/elvish-completions](https://github.com/zzamboni/elvish-completions): completions by [zzamboni](https://github.com/zzamboni), including `git` and `vcsh`.
  * [github.com/zzamboni/elvish-modules](https://github.com/zzamboni/elvish-modules/): various libraries by [zzamboni](https://github.com/zzamboni).
  * [github.com/zzamboni/elvish-themes](https://github.com/zzamboni/elvish-themes/): the Chain theme by [zzamboni](https://github.com/zzamboni).

## Prompt Themes
  * [chain.elv](https://github.com/zzamboni/elvish-themes/blob/master/chain.org): Super configurable prompt theme with Git support
  * [powerline.elv](https://github.com/muesli/elvish-libs/blob/master/theme/powerline.elv): Powerline style prompt theme

## Completion Scripts
  * [xiaq/edit.elv/compl](https://github.com/xiaq/edit.elv/tree/master/compl): xiaq's completion scripts, now including one for `go`.
  * [zzamboni/elvish-completions](https://github.com/zzamboni/elvish-completions): zzamboni's completion scripts, including `git` and `vcsh`.

## Elvish Libraries
  * [alias.elv](https://github.com/zzamboni/elvish-modules/blob/master/alias.org): Support for persistent aliases and for parsing bash-style alias commands.
  * [bang-bang.elv](https://github.com/zzamboni/elvish-modules/blob/master/bang-bang.org): Support for the traditional `!!` and `!$` keybindings
  * [dir.elv](https://github.com/zzamboni/elvish-modules/blob/master/dir.org): Directory stack and support for `cd -` to mean "previous directory"
  * [git.elv](https://github.com/muesli/elvish-libs/blob/master/git.elv): Git utility functions (mainly for prompts).
  * [long-running-notifications.elv](https://github.com/zzamboni/elvish-modules/blob/master/long-running-notifications.org): Notifications for long-running commands
  * [nix.elv](https://github.com/zzamboni/elvish-modules/blob/master/nix.org): Environment setting and some wrapper utilities for the [Nix](https://nixos.org/nix/) package manager.
  * [prompt-hooks.elv](https://github.com/zzamboni/elvish-modules/blob/master/prompt_hooks.org): Utilities for manipulating prompt hooks.
  * [proxy.elv](https://github.com/zzamboni/elvish-modules/blob/master/proxy.org): A module for manipulating and auto-setting proxy variables
  * [terminal-title.elv](https://github.com/zzamboni/elvish-modules/blob/master/terminal-title.org): A module for automatically setting the terminal title.

## Editor support
  * [elvish-mode](https://github.com/ALSchwalm/elvish-mode) package for Emacs.
  * [elvish.vim](https://github.com/dmix/elvish.vim) plugin for Vim.
  * [language-elvish](https://atom.io/packages/language-elvish) package for Atom.

## More Awesome Elvish Stuff
  * [zzamboni/dot_elvish](https://github.com/zzamboni/dot_elvish/blob/master/rc.org): Documented `rc.elv` file, using many of the modules above.
