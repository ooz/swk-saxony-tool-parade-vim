# SWK Tool Parade - VIM

Vi(m) presentation for the Softwerkskammer Saxony Tool Parade meetup

Leipzig, 2016/04/19

by Oliver Z.

## Why still use VIM in 2016

 * It's available on all UNIX(-like) systems
 * Directly accessible from the command line (e.g. for sudo editing)
 * Lightweight, if you need to handle really large files
 * Extensible like any major editor
 * You can reuse the learned navigation commands in Gmail, Xmonad

## Getting out of it

Force quit without saving:

    Esc :q!

Save and quit:

    Esc :wq

## Modes

3 modi: command, insert, visual

### Command Mode

 * Default
 * Entered characters are processed as commands

Enter by hitting Esc or Ctrl + c

### Insert Mode

 * a, i insert after/before current character
 * A, I insert at the end/beginning of the line
 * o, O insert in line below/above current line

### Visual Mode

 * v normal mark
 * Ctrl + v for block mark
 * Shift +v for marking whole lines

## Block editing and replacing text

    ########################################
    #                                      #
    #                                      #
    #                                      #
    #                                      #
    #                                      #
    #                                      #
    #                                      #
    #                                      #
    #                                      #
    #                                      #
    ########################################

 * Use v to mark lines
 * Use I to insert at the beginning of a line
 * Type what you want to insert, e.g. "//", "#"
 * Hit Esc
 * Mark area, use r to replace marked characters with a new one

```python
def foobar(arg):
    print "Do something"
    print "Do even more"
    print "Do most"
```

## Formatting

Mark the text, type gq

This is a really really really really really really really really really long line, that I would like to format to 80 characters per line.
This is a really really really really really really really really really long line, that I would like to format to 80 characters per line.
This is a really really really really really really really really really long line, that I would like to format to 80 characters per line.
This is a really really really really really really really really really long line, that I would like to format to 80 characters per line.
This is a really really really really really really really really really long line, that I would like to format to 80 characters per line.
This is a really really really really really really really really really long line, that I would like to format to 80 characters per line.
This is a really really really really really really really really really long line, that I would like to format to 80 characters per line.
This is a really really really really really really really really really long line, that I would like to format to 80 characters per line.

## Movement

    w, e, b word-wise movement

    g       goto command
    gv      goto last visual selection
    gg      goto first line
    42gg    goto line 42
    G       goto last line

## Links

[Vim tips](http://rayninfo.co.uk/vimtips.html)

[Using tabs](http://vim.wikia.com/wiki/Using_tab_pages)
