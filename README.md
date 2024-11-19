# Obsidian Portugues

Obsidian notes for my learning of Portugues.

## community plugin for ShellCommands

I want to open a terminal wezterm with git-bash on Win11 from Obsidian.  
Obsidian Shell command hotkey Shift+Ctrl+j  

```bash
start "" "C:\Program Files\WezTerm\wezterm-gui.exe" start --cwd {{vault_path}} -- "C:\\Program Files\\Git\\bin\\bash.exe" -l
```

## Add special characters to the keyboard

In the folder "MSKLC keyboard layout" there is the program to change the windows keyboard layout.  
The file "LucKey.klc" has the new layout definition.  

Portuguese makes use of five diacritics:

- cedilla (ç)
- acute accent (á, é, í, ó, ú)
- circumflex accent (â, ê, ô)
- tilde (ã, õ)

My Win11 keyboard is Slovenian.
It has some characters we need in Portuguese:

- altgr + + prepares for ç
- altgr + 9 prepares for á, é, í, ó, ú
- altgr + 3 prepares for â, ô, BUT not for ê

But it does not have the other characters.

I will use MSKLC to customize the keyboard "Slovenian - Custom LucKey".

- altgr + 3 prepares for ê
- altgr + 1 prepares for ã, õ
