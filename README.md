# Scripts Collection

Some good scripts to make a cool terminal :wink:
---

### zsh

https://github.com/robbyrussell/oh-my-zsh

### VIM CONFIG

https://github.com/astronaut1712/vimrc

### BASH GIT PROMPT

https://github.com/astronaut1712/bash-git-prompt

### SCREEN CONFIG

Add the following code to ~/.screenrc file:

```bash
defshell /bin/bash
startup_message off
#caption always "%{Wb} %H %{Bk}| %{Ck}%-w%50>%{Cb} %n %t %{-}%+w%<%{- Wk}%{Bk} | %=%{Wb} %C "
hardstatus on
hardstatus alwayslastline
hardstatus string "%{.bW}%-w%{.rY}%n %t%{-}%+w %=%{..G} %H(%l) %{..Y} %Y/%m/%d %C%a "
vbell off
bind w windowlist -b
bind ^w windowlist -b
altscreen on
# Shift+0 through 9 to select windows 10 through 19
bind  ! select 11
bind  @ select 12
bind \# select 13
bind  $ select 14
bind  % select 15
bind \^ select 16
bind  & select 17
bind  * select 18
bind  ( select 19
bind  ) select 10

# PREVIOUS WINDOW
# # Ctrl + Alt + Left from gnome-terminal
bindkey ^[[1;7C prev
#
# # NEXT WINDOW
# # Ctrl + Alt + Right from gnome-terminal
bindkey ^[[1;7D next
```
