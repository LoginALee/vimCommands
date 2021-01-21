# Basics about VIM

## What is VIM anyway?

Vim is a highly configurable text editor built to enable efficient text editing.
It is an improved version of the vi editor distributed with most UNIX systems. Vim is distributed free as charityware


The best way to learn Vim is by reading its documentation, but in this repo im going to collect some
of the basics in order to learn it myself :) , so there are some notations that will help us read the
instructions or commands better, let's get to it shall we?

## Commands

In Normal mode, commands are designed to be typed as a sequence of keystrokes. 

Example: 

### Notation	Meaning
x		Press x once
dw		In sequence, press **d**, then **w**
dap		In sequence, press **d**, **a**, then **p**


These may be a little short sequences, but some are longer.

When we see a notation suck as **<C-p>**, it doesn't mean "Press <, then C, then -, and so on". The **<C-p>** notation
is equivalent to **Ctrl-p**, which means "Press the <Ctrl> and p keys at the same time".

Example:

### Notation	Meaning
<C-n>		Press <Ctrl> and n at the same time
g<C-]>		Press g, followed by <Ctrl> and ] at the same time
<C-r>0		Press <Ctrl> and r at the same time, then 0
<C-w><C-=>	Press <Ctrl> and w at the same time, then <Ctrl> and = at the same time


### Placeholders

Some commands must be followed by a particular kind of keystroke. while other commands can be followed by any key on the keyboard.

Example:

### Notation	Meaning
f{char}		Press f, followedd by any other character
`{a-z}		Press `, followed by any lowercase letter
m{a-zA-Z}	Press m, followed by any lowercase or uppercase letter
d{motion}	Press d, followed by any motion command
<C-r>{register}	Press <Ctrl> and r at the same time, followed by the address of a register

Some keys are called by name, some examples are:

### Notation	Meaning
<Esc>		Press the Escape key
<CR>		Press the carriage return key (also known as <Enter>
<Ctrl>		Press the Control key
<Tab>		Press the Tab key
<Shift>		Press the Shift key
<S-Tab>		Press the <Shift> and <Tab> keys at the same time
<Up>		Press the up arrow key
<Down>		Press the down arrow key
.





