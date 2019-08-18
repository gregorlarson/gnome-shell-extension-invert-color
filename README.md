# gnome-shell-extension-invert-color
GNOME Shell extension for inverting the color of windows

Based on https://github.com/maiself/gnome-shell-extension-invert-color

Changed the shader to a matrix-thirds, which does not invert the red/green colors
so it is useful for viewing diffs (code inspections, which I do a lot of).

The matrix-thirds shader was copied from:
https://github.com/vn971/linux-color-inversion.git
