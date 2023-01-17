# Catppuccin Mocha
thm_bg="#1e1e2e"
thm_fg="#cdd6f4"
thm_fg1="#a6adc8"
thm_cyan="#89dceb"
thm_black="#181825"
thm_gray="#313244"
thm_magenta="#cba6f7"
thm_pink="#f5c2e7"
thm_red="#f38ba8"
thm_green="#a6e3a1"
thm_yellow="#f9e2af"
thm_blue="#89b4fa"
thm_orange="#fab387"
thm_mocha_mantle="#181825"

# 定制状态栏
set -g status "on"
set -g status-justify left
set -g status-interval 1

set -g status-left-length 300
set -g status-right-length 150

# 设置状态栏样式
set -g status-style bg=$thm_bg,fg=$thm_bg # 状态栏前景背景色

# 设置窗口列表颜色
setw -g window-status-style bg=$thm_bg,fg=$thm_bg

# 设置活动通知窗口颜色
setw -g window-status-activity-style bg=$thm_bg,fg=$thm_fg

# Set active pane border color
set -g pane-active-border-style bg=$thm_bg,fg=$thm_red

# Set inactive pane border color
setw -g pane-border-style bg=$thm_bg,fg=$thm_black

# Writing commands inactive
set -g message-command-style bg=$thm_bg,fg=$thm_bg

# Bell
setw -g window-status-bell-style bg=$thm_bg,fg=$thm_fg

show_session="#[fg=$thm_mocha_mantle,bg=$thm_blue,bold] ❐#[fg=$thm_mocha_mantle,bg=$thm_blue,bold] #S #[fg=$thm_blue,bg=$thm_bg]"
heartbeat_segment=" #[fg=$thm_green,bg=$thm_bg]♥ "
show_date_time="#[fg=$thm_blue,bg=$thm_bg]#[fg=$thm_black,bg=$thm_blue,bold] #[fg=$thm_bg,bg=$thm_blue] %Y-%m-%d %H:%M:%S "

set -g status-left "$show_session$heartbeat_segment"
set -g status-right "$show_date_time"

setw -g window-status-current-format "#[bg=$thm_blue,fg=$thm_bg]#[fg=$thm_gray,bg=$thm_blue,bold] #I #[fg=$thm_gray,bg=$thm_blue,bold] #W #[fg=$thm_blue,bg=$thm_black]"
setw -g window-status-format "#[fg=$thm_black,bg=$thm_fg1,noitalics]#[fg=$thm_bg,bg=$thm_fg1] #I #[fg=$thm_bg,bg=$thm_fg1] #W #[fg=$thm_fg1,bg=$thm_black]"
