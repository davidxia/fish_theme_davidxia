## davidxia

A fish shell theme optimized for people who use:

* Solarized
* Git
* Unicode-compatible fonts and terminals (I use Monaco for Powerline)

For Mac users, I highly recommend iTerm2 + Solarized Dark.

*On Arch Linux, the characters for parts of the prompt are different. I had to
change `segment_separator` and `right_segment_separator` to `\uE0B0` and `\uE0B2`,
respectively. You can download the Monaco for Powerline font
[here][aur-monaco-powerline-font-fixed-git].*

![davidxia theme](https://f.cloud.github.com/assets/1765209/255379/452c668e-8c0b-11e2-8a8e-d1d13e57d15f.png)

### Installation

Save `fish_prompt.fish` as `~/.config/fish/functions/fish_prompt.fish`.

#### Characteristics

* If the previous command failed (✘)
* User @ Hostname (if user is not DEFAULT_USER, which can then be set in your profile)
* Git status
* Branch (⭠) or detached head (➦)
* Current branch / SHA1 in detached head state
* Dirty working directory (±, color change)
* Working directory
* Elevated (root) privileges (⚡)


Ported from https://gist.github.com/agnoster/3712874.

  [aur-monaco-powerline-font-fixed-git][https://aur.archlinux.org/packages/monaco-powerline-font-fixed-git/]
