# Personal Zinc setup

These are snapshots of the Zinc configuration and Ctrl+click helper in use on this computer. The helper opens text files in Micro and other files with the desktop default. The config uses `/home/sahil/.local/bin/zinc-open-file`; adjust that path on another machine.

To restore these settings, copy `config` to `~/.config/zinc/config` and `zinc-open-file` to `~/.local/bin/zinc-open-file`, then make the helper executable. Existing settings will be overwritten.

The Bash configuration also uses `eza --icons=auto --color=auto --group-directories-first` for `ls`, and reports the current directory using OSC 7 to support Zinc file links. These Bash settings are maintained separately in `~/.bashrc`.
