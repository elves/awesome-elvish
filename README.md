# awesome-elvish

A curated list of awesome Elvish packages, modules, and tools that support Elvish.

| Icon | Description |
| ---- | ----------- |
| 📦 | An Elvish package (a collection of related modules) - install directly with [epm](https://elv.sh/ref/epm.html#epm) |
| 🧩 | An Elvish module - install the package that contains it (usually just the Git repo) with epm |
| 🛠 | An external tool that supports Elvish |

## Prompt Themes

| Item | Description |
| ---- | ----------- |
| 🧩 [github.com/muesli/elvish-libs/powerline](https://github.com/muesli/elvish-libs/blob/master/theme/powerline.elv) | Powerline style prompt theme |
| 🧩 [github.com/zzamboni/elvish-themes/chain](https://github.com/zzamboni/elvish-themes/blob/master/chain.org) | Super configurable prompt theme with Git support |
| 🧩 [github.com/champii/elvish-base/prompt](https://github.com/champii/elvish-base/blob/master/prompt.elv) | Very basic prompt over two lines with simple git support |
| 🧩 [gitlab.com/SneakyThunder/silver-prompt-elv/silver](https://gitlab.com/SneakyThunder/silver-prompt-elv/-/blob/master/silver.elv) | Elvish integration for [silver](https://github.com/reujab/silver/), a cross-shell customizable powerline-like prompt written in Rust |
| 🛠 [Starship](https://starship.rs) | A cross-shell, minimal, blazingly-fast prompt written in Rust |
| 🛠 [oh-my-posh](https://ohmyposh.dev) | A cross-shell, highly configurable, blazingly-fast prompt written in Go |

## Completion Scripts

| Item | Description |
| ---- | ----------- |
| 📦 [github.com/xiaq/edit.elv](https://github.com/xiaq/edit.elv) | Includes completion scripts for `go` and `git` |
| 📦 [zzamboni/elvish-completions](https://github.com/zzamboni/elvish-completions) | Includes completion scripts for `cd`, `git`, `vcsh` |
| 📦 [aca/elvish-bash-completion](https://github.com/aca/elvish-bash-completion) | Converts any bash completion to elvish |
| 🛠 [rsteube/carapace-bin](https://github.com/rsteube/carapace-bin) | Built-in completions for [over 400 commands](https://rsteube.github.io/carapace-bin/completers.html), and support for custom completions |

## Editor Support

| Editor | Plugin |
| ------ | ------ |
| [Emacs](https://www.gnu.org/software/emacs/) | [elvish-mode](https://github.com/ALSchwalm/elvish-mode) |
| [Vim](http://www.vim.org/) | [elvish.vim](https://github.com/dmix/elvish.vim) |
| [Atom](https://atom.io/) | [language-elvish](https://atom.io/packages/language-elvish) |
| [Kakoune](http://kakoune.org/) | Builtin support; [kak-lsp](https://github.com/kak-lsp/kak-lsp) also has builtin LSP configuration for Elvish |
| [VSCode](https://code.visualstudio.com/) | [official extension](https://marketplace.visualstudio.com/items?itemName=elves.elvish) |
| [Sublime Text 3](https://www.sublimetext.com) | [elvish_syntax_for_sublime](https://github.com/href/elvish_syntax_for_sublime) |
| [PyCharm](https://www.jetbrains.com/pycharm) | [elvish-lang-plugin](https://github.com/sblundy/elvish-lang-plugin) |
| [Micro](https://github.com/zyedidia/micro) | [elvish-micro-syntax](https://github.com/kolbycrouch/elvish-micro-syntax) |
| [Helix](https://github.com/helix-editor/helix) | Builtin support, including integration with `elvish -lsp` |

## General Tools With Built-in Support for Elvish

| Item | Description |
| ---- | ----------- |
| 🛠 [x-cmd](https://www.x-cmd.com/) | x-cmd is a vast and interesting collection of tools guided by the Unix philosophy, with [support for Elvish](https://www.x-cmd.com/mod/elv). |
| 🛠 [pixi](https://pixi.sh/) | pixi is a performant new cross-platform package manager for Conda-forge packages that [supports Elvish completions](https://pixi.sh/latest/#autocompletion). It simplifies activation/deactivation compared to Conda/Mamba (and also allows global installs) and so works better with non-posix shells. |
| 🛠 [dorothy](https://github.com/bevry/dorothy) | Bring your dotfile commands to any shell. Sensible defaults and hundreds of commands preloaded. Supports Elvish on macOS, Linux, Windows. |

## Terminal Integration

| Terminal | Item | Description |
| -------- | ---- | ----------- |
| iTerm2 | 🧩 [github.com/zzamboni/elvish-modules/iterm2](https://github.com/zzamboni/elvish-modules/blob/master/iterm2.org) | Support for iTerm2 [Shell Integration](https://iterm2.com/documentation-shell-integration.html) features. |

## General Libraries (Modules)

| Item | Description |
| ---- | ----------- |
| 📦 [github.com/muesli/elvish-libs](https://github.com/muesli/elvish-libs) |
|  🧩 [git](https://github.com/muesli/elvish-libs/blob/master/git.elv) | Git utility functions (mainly for prompts) |
| 📦 [github.com/zzamboni/elvish-modules](https://github.com/zzamboni/elvish-modules/) |
|  🧩 [alias](https://github.com/zzamboni/elvish-modules/blob/master/alias.org) | Support for persistent aliases and for parsing bash-style alias commands. |
|  🧩 [bang-bang](https://github.com/zzamboni/elvish-modules/blob/master/bang-bang.org) | Support for the traditional `!!` and `!$` keybindings |
|  🧩 [dir](https://github.com/zzamboni/elvish-modules/blob/master/dir.org) | Directory stack and support for `cd -` to mean "previous directory" |
|  🧩 [long-running-notifications](https://github.com/zzamboni/elvish-modules/blob/master/long-running-notifications.org) | Notifications for long-running commands |
|  🧩 [nix](https://github.com/zzamboni/elvish-modules/blob/master/nix.org) | Environment setting and some wrapper utilities for the [Nix](https://nixos.org/nix/) package manager. |
|  🧩 [prompt-hooks](https://github.com/zzamboni/elvish-modules/blob/master/prompt_hooks.org) | Utilities for manipulating prompt hooks. |
|  🧩 [proxy](https://github.com/zzamboni/elvish-modules/blob/master/proxy.org) | A module for manipulating and auto-setting proxy variables |
|  🧩 [spinners](https://github.com/zzamboni/elvish-modules/blob/master/spinners.org) | A module to generate different styles of progress spinners for use in Elvish scripts. |
|  🧩 [terminal-title](https://github.com/zzamboni/elvish-modules/blob/master/terminal-title.org) | A module for automatically setting the terminal title. |
| 📦 [github.com/iwoloschin/elvish-packages](https://github.com/iwoloschin/elvish-packages) |
|  🧩 [python](https://github.com/iwoloschin/elvish-packages/blob/master/python.elv) | Support for Python virtual environments |
|  🧩 [update](https://github.com/iwoloschin/elvish-packages/blob/master/update.elv) | A tool to check if a newer version of Elvish is available. |
| 📦 [github.com/jkbr-19/sindarin-term](https://github.com/jkbr-19/sindarin-term) |
|  🧩 [date-elv](https://github.com/jkbr-19/sindarin-term/blob/master/date-elv.elv) | A module for printing the date in elvish (Sindarin) written in Elvish |
| 📦 [github.com/champii/elvish-base](https://github.com/champii/elvish-base) |
|  🧩 [git](https://github.com/champii/elvish-base/blob/master/git.elv) | Git helpers |
|  🧩 [utils](https://github.com/champii/elvish-base/blob/master/utils.elv) | Helpers for usual shell manipulation |
|  🧩 [fs](https://github.com/champii/elvish-base/blob/master/fs.elv) | FS helpers and object oriented files |
| 🧩 [github.com/href/elvish-gitstatus/gitstatus](https://github.com/href/elvish-gitstatus/blob/master/gitstatus.elv) | [Gitstatus](https://github.com/romkatv/gitstatus) integration for Elvish. |
| 📦 [github.com/doubleagent/rivendell](https://github.com/doubleagent/rivendell) |
|  🧩 [fun](https://github.com/doubleagent/rivendell/blob/master/fun.elv) | Helps your elvish code to be more functional |
|  🧩 [lazy](https://github.com/doubleagent/rivendell/blob/master/lazy.elv) | Gives you access to lazy iterators, infinite sequences, and multiple higher-level iterators |
| 🧩 [github.com/kolbycrouch/elvish-libs/pure](https://github.com/kolbycrouch/elvish-libs/tree/master/pure) | Pure elvish utility libraries |
| 🧩 [github.com/gergelyk/elvish-libs/python](https://github.com/gergelyk/elvish-libs/blob/main/python.elv) | Evaluate Python inplace. Switch venv automatically. |
| 📦 [github.com/krader1961/elvish-lib](https://github.com/krader1961/elvish-lib) |
|  🧩 [cmd-duration](https://github.com/krader1961/elvish-lib/blob/master/cmd-duration.elv) | Provides function `human-readable` to make it easy to include a human friendly representation, in your prompt, of the duration of the most recent command. |
|  🧩 [util-unix](https://github.com/krader1961/elvish-lib/blob/master/util-unix.elv) | Provides command `ulimit` for displaying and modifying the `unix:rlimits` variable in a manner more like traditional POSIX shells. |
| 📦 [github.com/iandol/elvish-modules](https://github.com/iandol/elvish-modules) |
|  🧩 [mamba](https://github.com/iandol/elvish-modules/blob/main/mamba.elv) | support for `conda` / `mamba` / `micromamba` package manager. For more complex conda recipes that run POSIX scripts, it captures the environment and imports it for elvish. |
|  🧩 [cmds](https://github.com/krader1961/elvish-lib/blob/master/util-unix.elv) | utility functions to perform helpful shell actions: add/remove (`append-to-path`, `prepend-to-path`, `remove-from-path`) or filter (`filter`, `filter-out`, `filter-re`, `filter-re-out`) lists like the path list; `if-external` - check a executable then run tasks if it is, or is not present; list utils `list-unique`, `list-diff`, `list-append`, `list-intersect`, `list-find` and several others. |
| 📦 [github.com/tesujimath/bash-env-elvish](https://github.com/tesujimath/bash-env-elvish) |
|  🧩 [bash-env](https://github.com/tesujimath/bash-env-elvish/blob/main/bash-env.elv) | Import Bash environment into Elvish. |
|  🧩 [virtualenv](https://github.com/tesujimath/bash-env-elvish/blob/main/virtualenv.elv) | Activate/deactivate Python virtualenv. |
|  🧩 [nvm](https://github.com/tesujimath/bash-env-elvish/blob/main/nvm.elv) | Support for NVM (node version manager). |
|  🧩 [lmod](https://github.com/tesujimath/bash-env-elvish/blob/main/lmod.elv) | Support for [Lmod Environment Modules](https://lmod.readthedocs.io/en/latest/index.html). |
| 📦 [github.com/tesujimath/elvish-tap](https://github.com/tesujimath/elvish-tap) |
|  🧩 [tap](https://github.com/tesujimath/elvish-tap/blob/main/tap.elv) | [Test Anything Protocol](https://testanything.org/) (TAP) for Elvish. |
| 📦 [github.com/tesujimath/direlv](https://github.com/tesujimath/direlv) |
|  🧩 [direlv](https://github.com/tesujimath/direlv/blob/main/direlv.elv) | Directory activation for Elvish in the spirit of [direnv](https://direnv.net/) |

## More Awesome Elvish Stuff

| Item | Description |
| ---- | ----------- |
| 🛠 [ajeetdsouza/zoxide](https://github.com/ajeetdsouza/zoxide) | A fast alternative to `cd` that learns your habits. |
| 📄 [zzamboni/dot_elvish](https://github.com/zzamboni/dot_elvish/blob/master/rc.org) | Documented `rc.elv` file, using many of the modules above. |
| 📄 [darcy-shen/oh-my-elvish](https://github.com/darcy-shen/oh-my-elvish) | User-friendly, productive and cross-platform elvish configuration. |
| 🛠 [elvish.nix](https://github.com/tesujimath/elvish.nix) | Nix support for Elvish packages, a multi-user-friendly alternative to `epm`. |
