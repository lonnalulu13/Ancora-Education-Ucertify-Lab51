# Ancora-Education-Ucertify-Lab51
# Editing Files using the Vim Editor

> **Original Lab Source**
> 
> This lab was available through:
>
> [https://ancoraeducation.ucertify.com/app/?func=navigate_items&item_sequence=4]

## Objective of the Lab 
In this lab, you will learn to edit, display, and manage files using the vim editor. 
### Editor used 
Vim: Vim is a Unix text editor that's included in Linux, BSD, and macOS. It's known for being fast and efficient, in part because it's a small application that can run in a terminal (although it also has a graphical interface), but mostly because it can be controlled entirely with the keyboard with no need for menus or a mouse. 
## Instructions 
### STEP 1 
From the left sidebar, open the Terminal window. 
### STEP 2 
Execute the following command to copy the /usr/share/doc/python-serial/README.txt file into your current directory: 
```bash
cp /usr/share/doc/python3-serial/README.rst example.txt
```
### CAUTION
* This file was chosen because it is on the system by default and is a rather large file.
### STEP 3 
Execute the following command to open the example.txt file in a vim editor:
```bash
vim example.txt
```
### STEP 4
Perform the following in the vim editor:

a.Press e to select the edit-only mode. 

b.Enter (12) or press the down arrow key to move down 12 lines. 

c.Press i to go to the insert mode, and at the beginning of the line, enter i welcome user 

d.Press the Esc key to exit the insert mode. 

e.Enter (38G) or (:38) to to go to line 38. 

f.Enter (dd) to delete the current line.

g.Press the down arrow key. 

h.Press (O) to open a new line below the current line. 

i.Enter the text (Review this data)into the document.

j.To return to the command mode, press the Esc key. 

k.Enter (1G) or (:1) to go to the top of the file.

l.Enter 3) to move forward three sentences. 

m.Enter (4w) to move forward four words. 

n.Type (/example) and press Enter to search for the term example.

o.Enter (n) to continue to the next occurrence of the search term.

p.Enter (dw) to delete the current word. 

q.Enter (G) to go to the end of the document.

r.Execute ($P) to paste the text from the buffer at the end of the current line. 

s.Type (:wq) and press Enter to save and quit the document.
### STEP 5
Execute the following command in the Terminal window to run the vimtutor:
```bash
vimtutor
```
### STEP 6
Press Ctrl+Z to exit.
## Disclaimer

This repository is for **educational and personal learning purposes only**.  

The original lab content belongs to **uCertify / Ancora Education** and remains their copyrighted material.  
This repository is not affiliated with, endorsed by, or sponsored by uCertify or Ancora Education.  

No copyright infringement is intended.  
Use of any tools or techniques mentioned here should only be performed in authorized, legal environments.
