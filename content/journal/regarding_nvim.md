---
title: "noob.md"
slug:
category:
summary: noob just like you know
description: noob just like you know
cover:
  image:
  alt:
  caption:
  relative: false
showtoc: true
weight: 1
---

### ~Guide to Using Neovim

This guide provides essential tips and commands when using Neovim. Instead of spending time searching for specific commands, you can find the most important ones right here. These commands can be customized in your nvim setup but most of them are defualt, and most of them are customed to my taste. Check my [`setup`](https://github.com/Dudeiebot/nvim)

#### Key Modes in Neovim

- **Normal Mode:** The default mode for Neovim.
- **Command Mode:** Used for executing commands.
- **Visual Mode:** For selecting and copying (yanking) text.
- **Insert Mode:** For inserting text.

#### NVIM_TREE

- **Create a File:** Press `a` in the nvim_tree pane. You can also create folder by adding `\` at the end of the name. Ensure you check the location before creating new items.
- **Open a File:** Use `o` or `enter` on the file's directory.
- **Toggle nvim_tree:** Press `ctrl-n`.
- **Navigate:** Use `ctrl-h` to navigate between nvim and the tree pane.

#### Commands That Work

`Ensure you are in normal mode for these commands to work.`
- **Change Theme:** Use `<leader>th` to customize your theme.
- **Suspended Mode:** `ctrl-z` takes you to terminal suspended mode. Use `fg` to return to your buffer.
- **Open Folders:** Use `<leader>sB` without nvim-tree.
- **Close Buffer:** Close an opened buffer with `<leader>x` or `:bd`.
- **Navigate in Command Mode:** Use `esc` or `ctrl-c` to navigate.

#### Navigation

- Use `j`, `k`, `l`, and `h` for navigation.
- Speed up with `B`, `W`, `J`, `K`, `L`, `H`, also use it for backward movement. Combine navigation keys with numbers for faster movement (e.g `50j`).
- Jump between functions with `{` and `}`.
- Go to the beginning or end of a file with `gg` and `GG`, respectively. Navigate directly to a line with `:<line_number>`.

#### Split Screen

- **Horizontal Split:** Use `split`.
- **Vertical Split:** Use `vsplit`.

#### Saving and Quitting

- **Save:** Use `:w`.
- **Quit:** Use `:q` or `:q!` for a hard quit or maybe get stuck forever.


#### Terminal et Neovim

- **Open Terminal:** Use `ctrl-t` for a floating terminal, `<leader>h` or `<leader>v` for horizontal or vertical splits.
- **Show Opened Terminals:** Use `<leader>pt`.

#### Macros

- **Record a Macro:** Press `q` followed by the key you want to save the command sequence to. End recording with `q` and replay the macro with `@` followed by the key.

#### Searching

- Use `/` to search within the file. Navigate through instances with `n` (forward) and `N` (backward).


### CMD on the go  
- Yanking a line with `yy`, yanking a word with `ye`, yanking matching sequence with `y%`.  
- `zz` to centre your cursor.  
- Deleting a line with `dd`, deleting a word with `de`,deleting matching sequence with `d%`.  
- If you want to Change the same words(let say in a json file), use `shift ;` which displays some certain strings that can follow this pattern`s/word you want to change/new word`.
- Go to definitions, use `ctrl-]`
- Use `gc` or `gd` for comment out a line of code.
- Switch between lowercase and uppercase with `~`.
- Use `.` to repeat the last action.
- `*` for checking instances where word are used in the file and moving through all highlighted words
- `o` for  taking you below a  new line and `O` for taking you above a new line, also you get to be in insert mode also.
- `x` delete a letter, and you can add nos to the back also for more deleting.  
- Use `r` to replace a letter, `R` for replacing multiple letters.
- Highlight lines fully with `shift-v` and the curly brackets.
- Indent with `<` or `>`.
- `A` takes you to the end of the line, `0` takes you to the beginning of a line and capital `I` takes to the beginning and putting in insert mode.
- `%` comes in handy in between brackets to flip around them, you can move from the bracket opening `{` to the bracket close `}` with the sign, or around other brackets also.


### Talks
An easy way to remember `d` as Delete and `c` as Change, `w` as Forward and `b` as backward, `t` as to and `f` as find, `b` as beginning and `e` as end.  
For real this are just normal english, like `d 2 w` called delete 2 word will practically delete 2 word.  
`dt` and `ct` followed by the lettering or symbol you want to delete can be helpful also, it will equally delete of change to the side.  

