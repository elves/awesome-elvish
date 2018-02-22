# awesome-elvish

The official list of awesome unofficial Elvish modules.

Each module is listed under the package to which it belongs. You can
install each package using [epm](https://elvish.io/ref/epm.html) with:

```
use epm
epm:install <package name>
```

## Prompt Themes
  * Package [github.com/muesli/elvish-libs](https://github.com/muesli/elvish-libs)
    * [github.com/muesli/elvish-libs/powerline](https://github.com/muesli/elvish-libs/blob/master/theme/powerline.elv): Powerline style prompt theme
  * Package [github.com/zzamboni/elvish-themes](https://github.com/zzamboni/elvish-themes/)
    * [github.com/zzamboni/elvish-themes/chain](https://github.com/zzamboni/elvish-themes/blob/master/chain.org): Super configurable prompt theme with Git support

## Completion Scripts
  * Package [github.com/xiaq/edit.elv](https://github.com/xiaq/edit.elv)
    * [github.com/xiaq/edit.elv/compl/go](https://github.com/xiaq/edit.elv/blob/master/compl/go.elv): completions for `go`
  * Package [zzamboni/elvish-completions](https://github.com/zzamboni/elvish-completions)
    * [github.com/zzamboni/elvish-completions/cd](https://github.com/zzamboni/elvish-completions/blob/master/cd.org): completion for `cd`
    * [github.com/zzamboni/elvish-completions/git](https://github.com/zzamboni/elvish-completions/blob/master/git.org): completion for `git`
    * [github.com/zzamboni/elvish-completions/vcsh](https://github.com/zzamboni/elvish-completions/blob/master/vcsh.org): completion for `vcsh`

## Elvish Libraries
  * Package [github.com/muesli/elvish-libs](https://github.com/muesli/elvish-libs)
    * [github.com/muesli/elvish-libs/git](https://github.com/muesli/elvish-libs/blob/master/git.elv): Git utility functions (mainly for prompts).
  * Package [github.com/zzamboni/elvish-modules](https://github.com/zzamboni/elvish-modules/)
    * [github.com/zzamboni/elvish-modules/alias](https://github.com/zzamboni/elvish-modules/blob/master/alias.org): Support for persistent aliases and for parsing bash-style alias commands.
    * [github.com/zzamboni/elvish-modules/bang-bang](https://github.com/zzamboni/elvish-modules/blob/master/bang-bang.org): Support for the traditional `!!` and `!$` keybindings
    * [github.com/zzamboni/elvish-modules/dir](https://github.com/zzamboni/elvish-modules/blob/master/dir.org): Directory stack and support for `cd -` to mean "previous directory"
    * [github.com/zzamboni/elvish-modules/long-running-notifications](https://github.com/zzamboni/elvish-modules/blob/master/long-running-notifications.org): Notifications for long-running commands
    * [github.com/zzamboni/elvish-modules/nix](https://github.com/zzamboni/elvish-modules/blob/master/nix.org): Environment setting and some wrapper utilities for the [Nix](https://nixos.org/nix/) package manager.
    * [github.com/zzamboni/elvish-modules/prompt-hooks](https://github.com/zzamboni/elvish-modules/blob/master/prompt_hooks.org): Utilities for manipulating prompt hooks.
    * [github.com/zzamboni/elvish-modules/proxy](https://github.com/zzamboni/elvish-modules/blob/master/proxy.org): A module for manipulating and auto-setting proxy variables
    * [github.com/zzamboni/elvish-modules/terminal-title](https://github.com/zzamboni/elvish-modules/blob/master/terminal-title.org): A module for automatically setting the terminal title.
  * Package [github.com/iwoloschin/elvish-packages](https://github.com/iwoloschin/elvish-packages)
    * [github.com/iwoloschin/elvish-packages/python](https://github.com/iwoloschin/elvish-packages/blob/master/python.elv): Support for Python virtual environments

## Editor support
  * [elvish-mode](https://github.com/ALSchwalm/elvish-mode) package for [Emacs](https://www.gnu.org/software/emacs/).
  * [elvish.vim](https://github.com/dmix/elvish.vim) plugin for [Vim](http://www.vim.org/).
  * [language-elvish](https://atom.io/packages/language-elvish) package for [Atom](https://atom.io/).
  * [elvish.kak](https://github.com/notramo/elvish.kak) language file for [Kakoune](http://kakoune.org/).

## More Awesome Elvish Stuff
  * [zzamboni/dot_elvish](https://github.com/zzamboni/dot_elvish/blob/master/rc.org): Documented `rc.elv` file, using many of the modules above.
