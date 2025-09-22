<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
<body>
  <h1>Kitty Configuration</h1>

  <p>
    This repository contains a customized configuration for the 
    <a href="https://sw.kovidgoyal.net/kitty/" target="_blank">Kitty terminal emulator</a>.
  </p>

  <h2>Overview</h2>
  <p>
    This configuration improves usability, performance, and aesthetics.
    It includes custom keybindings, color schemes, font settings, and performance tweaks
    to create a productive and visually pleasing terminal environment.
  </p>

  <h2>Features</h2>
  <ul>
    <li>Customized color theme for better readability</li>
    <li>Optimized font and font size settings</li>
    <li>Keybindings for faster navigation and pane management</li>
    <li>Performance tweaks for smooth scrolling and rendering</li>
    <li>Support for ligatures and Unicode</li>
  </ul>

  <h2>Usage</h2>
  <ol>
    <li>
      Install Kitty if you haven’t already:
      <pre><code>sudo apt install kitty</code></pre>
      or follow the instructions for your operating system 
      <a href="https://sw.kovidgoyal.net/kitty/binary/">here</a>.
    </li>
    <li>
      Copy the configuration file(s) to your Kitty config directory:
    </li>
    <li>Restart Kitty to apply the changes.</li>
  </ol>

  <h2>Customization</h2>
  <p>
    You can further edit the configuration file (<code>kitty.conf</code>) to suit your needs. 
    Refer to the official <a href="https://sw.kovidgoyal.net/kitty/conf.html">Kitty documentation</a> 
    for available options.
  </p>
  <h3>My Configuration file: </h3>

```conf
# kitty.conf - Configuración para un aspecto similar a la imagen

# Colores (MBcolors)
foreground            #c0caf5
background            #1a1b26
selection_foreground  #c0caf5
selection_background  #33467c
url_color             #9ece6a
cursor                #c0caf5
cursor_text_color     #1a1b26
active_border_color   #7aa2f7
inactive_border_color #444b6a
bell_border_color     #ff9e64

color0  #15161e
color1  #f7768e
color2  #9ece6a
color3  #e0af68
color4  #7aa2f7
color5  #bb9af7
color6  #7dcfff
color7  #a9b1d6
color8  #414868
color9  #f7768e
color10 #9ece6a
color11 #e0af68
color12 #7aa2f7
color13 #bb9af7
color14 #7dcfff
color15 #c0caf5

# Fuente
font_family       FiraCode Nerd Font
bold_font         auto
italic_font       auto
bold_italic_font  auto
font_size         11.0

# Transparencia (si lo permite el compositor)
background_opacity 0.9

# Bordes y padding
window_padding_width 10
window_border_width 2

# Ajustes adicionales
enable_audio_bell no
shell_integration no

# Deshabilita la barra de pestañas
hide_window_decorations no
```

</body>
</html>
