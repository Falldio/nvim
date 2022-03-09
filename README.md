# <center>My NeoVim</center>
> Yet another `NeoVim` configuration~

> Basic Vim guidance should be found [here](http://www.oualline.com/vim-cook.html)!
```
__   __    _       _  __     _                    
\ \ / /__ | | ___ | |/ /___ | | ___   _ _ __ __ _ 
 \ V / _ \| |/ _ \| ' // _ \| |/ / | | | '__/ _` |
  | | (_) | | (_) | . \ (_) |   <| |_| | | | (_| |
  |_|\___/|_|\___/|_|\_\___/|_|\_\\__,_|_|  \__,_|
                                                  
```
[TOC]

# Cursor Control (Normal & Visual)
|              Key               | Control                                        |
|:------------------------------:|------------------------------------------------|
|  <kbd>h</kbd> / <kbd>H</kbd>   | left                                           |
|  <kbd>l</kbd> / <kbd>L</kbd>   | right                                          |
|  <kbd>j</kbd> / <kbd>J</kbd>   | down                                           |
|  <kbd>k</kbd> / <kbd>K</kbd>   | up                                             |
|  <kbd>w</kbd> / <kbd>W</kbd>   | move cursor to the next (10) word              |
|  <kbd>b</kbd> / <kbd>B</kbd>   | move cursor to the front (10) word             |
| <kbd>Ctrl</kbd> + <kbd>h</kbd> | move cursor to the first charactor of the line |
| <kbd>Ctrl</kbd> + <kbd>l</kbd> | move cursor to the last charactor of the line  |
|  <kbd>g</kbd> + <kbd>g</kbd>   | top of the file                                |
|          <kbd>G</kbd>          | bottom of the file                             |
| <kbd>Ctrl</kbd> + <kbd>o</kbd> | move cursor backward, kind of like undo        |
| <kbd>Ctrl</kbd> + <kbd>i</kbd> | move cursor foreward, kind of like redo        |

# General Commands
|                       Key                       | Control                                                          |
|:-----------------------------------------------:|------------------------------------------------------------------|
|                  <kbd>o</kbd>                   | add a new line below the current line and switch to Insert mode  |
|                  <kbd>O</kbd>                   | add a new line above the current line and switch to Insert mode  |
|                  <kbd>A</kbd>                   | append the current line                                          |
|                  <kbd>I</kbd>                   | insert at the start of the current line                          |
|                  <kbd>Q</kbd>                   | quit NeoVim                                                      |
|                  <kbd>S</kbd>                   | save file                                                        |
|                  <kbd>R</kbd>                   | reload `init.vim`                                                |
|    <kbd>:</kbd> + <kbd>e</kbd> + `filepath`     | open file                                                        |
|           <kbd>g</kbd> + <kbd>f</kbd>           | open file at the path where cursor is pointing at                |
|           <kbd>z</kbd> + <kbd>z</kbd>           | set the current line to the center of the screen                 |
| <kbd>:</kbd> + <kbd>%</kbd> + <kbd>Tohtml</kbd> | export current file as a html file (so you can save it PDF, etc) |

# Spell Check
|                      Key                       | Control                       |
|:----------------------------------------------:|-------------------------------|
| <kbd>Space</kbd> + <kbd>s</kbd> + <kbd>c</kbd> | toggle spell check            |
|          <kbd>z</kbd> + <kbd>=</kbd>           | open spell correct suggestion |
|         <kbd>Ctrl</kbd> + <kbd>x</kbd>         | open complete suggestion      |

# File Open Shortcuts
|                              Key                              | Control                   |
|:-------------------------------------------------------------:|---------------------------|
| <kbd>Space</kbd> + <kbd>z</kbd> + <kbd>r</kbd> + <kbd>c</kbd> | open `init.vim` in NeoVim |
|        <kbd>Space</kbd> + <kbd>r</kbd> + <kbd>c</kbd>         | open `init.vim` in NeoVim |

# Screen Split & Tabs
|                                 Key                                  | Control                                         |
|:--------------------------------------------------------------------:|-------------------------------------------------|
|            <kbd>Space</kbd> + <kbd>s</kbd> + <kbd>l</kbd>            | vertical screen split and focus on the right    |
|            <kbd>Space</kbd> + <kbd>s</kbd> + <kbd>h</kbd>            | vertical screen split and focus on the left     |
|            <kbd>Space</kbd> + <kbd>s</kbd> + <kbd>j</kbd>            | horizontal screen split and focus on the bottom |
|            <kbd>Space</kbd> + <kbd>s</kbd> + <kbd>k</kbd>            | horizontal screen split and focus on the top    |
|                   <kbd>Space</kbd> + Direction Key                   | switch window                                   |
| <kbd>Up</kbd> / <kbd>Down</kbd> / <kbd>Left</kbd> / <kbd>Right</kbd> | adjust window size                              |
|                     <kbd>t</kbd> + <kbd>u</kbd>                      | open a new tab                                  |
|                     <kbd>t</kbd> + <kbd>h</kbd>                      | go one tab left                                 |
|                     <kbd>t</kbd> + <kbd>l</kbd>                      | go one tab right                                |

# Search
|                    Key                    | Control              |
|:-----------------------------------------:|----------------------|
| <kbd>/</kbd> + `query` + <kbd>Enter</kbd> | search something     |
|    <kbd>Space</kbd> + <kbd>Enter</kbd>    | clear search results |
|               <kbd>n</kbd>                | find next result     |
|               <kbd>N</kbd>                | find previous result |

# Placeholder
|                      Key                       | Control                                                         |
|:----------------------------------------------:|-----------------------------------------------------------------|
|      <kbd>Space</kbd> + <kbd>Space</kbd>       | find the next placeholder, clear it and switch into insert mode |
| <kbd>Space</kbd> + <kbd>p</kbd> + <kbd>h</kbd> | insert a placeholder at current position                        |

# Comment
|                      Key                       | Control   |
|:----------------------------------------------:|-----------|
| <kbd>Space</kbd> + <kbd>c</kbd> + <kbd>c</kbd> | comment   |
| <kbd>Space</kbd> + <kbd>c</kbd> + <kbd>u</kbd> | uncomment |
