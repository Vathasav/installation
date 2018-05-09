---
layout: master
---

# Terminal editors

Usually, when we want to create a text document, what we do is to use a program like Word. When the icon for Word is clicked, a graphical user interface (GUI) opens with an area to type what you want and menus and icons to perform operations like copy-paste and save. 

When we work on the terminal we do not have a GUI. But there are programs called “terminal text editors”, that we can use to type text. We can do the same open, type,find,cut,copy,paste,save operations on these editors as well. However, we have to use keyboard shortcuts instead of the mouse. The keyboard shortcuts involves pressing and holding the Ctrl key or the Alt and pressing another key at the same time. There are some examples of such editors below.

## Nano:
Easiest to use but with minimal functionality. This comes installed as default on most Linux distributions.  If you do not already have a favorite editor, we recommend this to be used with this during the course.  
### How to use it:
The keyboard shortcuts are displayed at the bottom of the editor window. Using this shortcuts involves pressing and holding down the control key (Ctrl) on your keyboard and pressing another key. The pressing down and holding the Ctrl key is represented by a hat "^".  

#### To create or open a files called mytext.txt
```shell
 nano mytext.txt
```
#### To save content    
Ctrl + o (hold the Ctrl key and press the o)
#### To close a file 
Ctrl + x (hold the Ctrl key and press the x)
#### To move up, down, left or right with the document
Use the arrow keys and Page-up, Page-down keys
#### Delete text
Navigate to where the text to be deleted located in the document using arrow keys. Use the Delete or Backspace keys to delete text. 
#### To find 
Ctrl + w then type the word to find and press enter (please note it is w not f as in most other editors) 

Tutorial :https://www.tutorialspoint.com/articles/how-to-use-nano-text-editor

## Vi/Vim
 This editor takes a little effort to get started. But has more functionality than Nano, especially if you write programming code. Syntax highlighting, clever copy-paste and better refactoring are some features.  

#### To create or open a files called mytext.txt
```shell
 vi mytext.txt
```
Interactive VIM tutorial : http://www.openvim.com/
      
## Emacs:
  The most powerful and takes much effort to get started. Once you get started there is "nothing" you can not do with this. This is the favorite editor for hard-core programmers, they write, version control  and even compile and run all from the editor it self. 

#### To create or open a files called mytext.txt
```shell
 emacs mytext.txt
```
Emacs guided tour:https://www.gnu.org/software/emacs/tour/
