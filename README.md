# Obsidian Portugues

**Obsidian notes for my learning of Portugues.**

 ![maintained](https://img.shields.io/badge/maintained-green)
 ![ready_for_use](https://img.shields.io/badge/ready_for_use-green)

## Motivation

Once I was in Brasil, I discovered that my knowledge of Spanish and Italian is not enough.  
I have to learn some Portugues. It is not that easy, but it is not that hard.  
I need to write my notes somewhere. I choose Obsidian. It looks nice.  
Obviously I wanted to use my laptop, table and smartphone.  
To make all that in sync I will use git and Github repository.
Git on laptop is a no-brainer.
On android table and smartphone I use `Termux` and there I installed git. Android is basically a bastard son of Google and Linux.

## Git and GitHub

It is easy to use git and GitHub.
After initiating the repository and connecting it with the remote repository is just:

```bash
git add .
git commit -m "message"
git push
```

and in the other direction

```bash
git pull
```

## Add Portugues characters to the keyboard

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
