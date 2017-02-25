#Linux下终端Terminator的一些配置技术
###配置文件的位置
`~/.config/termonator/config`
###一个不错的Terminator配置
```aidl
[global_config]
  suppress_multiple_term_dialog = True
[keybindings]
[layouts]
  [[default]]
    [[[child0]]]
      fullscreen = False
      last_active_term = 0d886773-ac21-44a4-8590-4be900097bb5
      last_active_window = True
      maximised = True
      order = 0
      parent = ""
      position = 65:24
      size = 2495, 1416
      title = zhuzh@notebook: ~
      type = Window
    [[[child1]]]
      order = 0
      parent = child0
      position = 1244
      ratio = 0.499799599198
      type = HPaned
    [[[child3]]]
      order = 1
      parent = child1
      position = 705
      ratio = 0.5
      type = VPaned
    [[[terminal2]]]
      order = 0
      parent = child1
      profile = default
      type = Terminal
      uuid = 0d886773-ac21-44a4-8590-4be900097bb5
    [[[terminal4]]]
      order = 0
      parent = child3
      profile = default
      type = Terminal
      uuid = 801e2772-27d3-4195-9e36-e748cb448931
    [[[terminal5]]]
      order = 1
      parent = child3
      profile = None
      type = Terminal
      uuid = 57173e52-b5dd-45c4-928e-7b74504de8d4
[plugins]
[profiles]
  [[default]]
    background_darkness = 0.92
    background_image = None
    background_type = transparent
    cursor_color = "#3036ec"
    custom_command = tmux
    font = 文泉驿等宽微米黑 16
    foreground_color = "#00ff00"
    login_shell = True
    show_titlebar = False
    use_system_font = False
```