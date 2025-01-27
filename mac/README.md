# CapsLock Enhancement Mac

## ANSI 60 Key and Keycap change

My external keyboard has a small ANSI 60 keys layout that is different from both my Mac and Windows laptop's UK ISO keyboards. It's reprogrammed with firmware to have the left modifier keys (<kbd>Ctrl</kbd>/<kbd>Win</kbd>/<kbd>Alt</kbd>) swapped to (<kbd>Ctrl_L</kbd>/<kbd>Alt</kbd>/<kbd>Ctrl_R</kbd>) to allow the same finger positions for the same Hyper shortcuts defined in both MacOS and Windows.

![ansi-60](../docs/img/ansi-60-remapped.png)

## Hyper CapsLock Mac

Mac keyboard layout is designed slightly different than normal ANSI/ISO layouts. Its wider and slighly left moved <kbd>⌘</kbd> key is more ergonomics for usual <kbd>⌘</kbd>+<kbd>C</kbd> or <kbd>⌘</kbd>+<kbd>V</kbd>. And it allows slighly easier reach for <kbd>T</kbd>, <kbd>Y</kbd>, <kbd>G</kbd>, <kbd>V</kbd> and <kbd>B</kbd> keys when <kbd>CapsLock</kbd> and <kbd>⌘</kbd> are both pressed.

Use **Karabiner-Elements**'s simple rule to change <kbd>Ctrl_R</kbd> to <kbd>Cmd_L</kbd> for the external ANSI keyboard only. All other complex rules defined in the JSON file can then be loaded for consistent Hyper features.

![hyper-mac](/mac/images/hyper-caps-lock-mac.png)
