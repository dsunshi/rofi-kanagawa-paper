# Gruvbox Material Rofi theme

<p align="center">A simple Gruvbox Material <a href="https://github.com/davatorium/rofi">Rofi</a> color theme.</p>

Based on the <a href="https://github.com/sainnhe/gruvbox-material">Gruvbox Material</a> color palette.</p>

---

<p align="center"><img src="https://raw.githubusercontent.com/undiabler/nord-rofi-theme/master/image1.png"/><img src="https://raw.githubusercontent.com/undiabler/nord-rofi-theme/master/image2.png"/><blockquote>Font: <a href="https://damieng.com/blog/2008/05/26/envy-code-r-preview-7-coding-font-released">Envy Code R</a> 10px.</blockquote></p>

## Getting started
### Installation

1. Copy <a href="gruvbox-material.rasi">gruvbox-material.rasi</a> file to `~/.config/rofi/gruvbox-material.rasi`
2. Add the following lines to your rofi config (`~/.config/rofi/config.rasi`):
```
configuration {
    font: "Envy Code R 10";
    line-margin: 10;

    display-ssh:    "";
    display-run:    "";
    display-drun:   "";
    display-window: "";
    display-combi:  "";
    show-icons:     true;
}

@theme "~/.config/rofi/gruvbox-material.rasi"
```
