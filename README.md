# SWK Tool Parade - VIM

Vi(m) presentation for the Softwerkskammer Saxony Tool Parade meetup

Leipzig, 2016/04/19

by Oliver Zscheyge

## Why still use VIM in 2016

 * It's available on all UNIX(-like) systems
 * Directly accessible from the command line (e.g. for sudo editing)
 * Lightweight
 * If you need to handle really large files
 * Extensible like any major editor
 * You can reuse the learned navigation commands in Gmail, Xmonad

## Modes

### Command Mode

### Insert Mode

### Visual Mode

## Getting out of it

## Inserting and replacing text

## Block editing

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

    def foobar(arg):
        print "Do something"
        print "Do even more"
        print "Do most"

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

