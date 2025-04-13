# catppuccin-minimal-tmux
A very minimal tmux theme for catppucin Macchiato
Inspired by minimal tmux theme that you can find here ![link](https://github.com/niksingh710/minimal-tmux-status/)

Clone the repository into the plugins directory of tmux.
And then add the following to the bottom of tmux.conf


There are some things you can configure in your tmux
```
set -g @minimal-tmux-justify "left"
set -g @minimal-tmux-indicator-str "  tmux  "
set -g @minimal-tmux-indicator true
set -g @minimal-tmux-status "bottom"

# Enables or disables the left and right status bar
set -g @minimal-tmux-right true
set -g @minimal-tmux-left true

set -g @minimal-tmux-expanded-icon "󰊓 "

set -g @minimal-tmux-show-expanded-icons-for-all-tabs true

set -g @minimal-tmux-status-right-extra ""
set -g @minimal-tmux-status-left-extra ""

set -g @minimal-tmux-use-arrow true
set -g @minimal-tmux-right-arrow " "
set -g @minimal-tmux-left-arrow " "
set -g @minimal-tmux-left-padding "   "  
set -g @minimal-tmux-right-padding "   "

# Not recommended to change these values
set -g @minimal-tmux-status-right " #S "
set -g @minimal-tmux-status-left ""

# If getting strings cut in left status or right
set -g status-right-length 40
set -g status-left-length 30

run '~/.config/tmux/plugins/catppucin-minimal-tmux/catppuccin.tmux'

```
