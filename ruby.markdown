### Embedded document: One way to quicly comment out a block of code

Put the code block in a
    =begin
    
    =end
_NOTE: `=` character must be the first character in the line_

- - -


### Backtick command execution: Invoke system command

    `ls` # execute this command using the system shell, and receive the output as string

    listcmd = 'ls'
    Kernel.`(listcmd)   # in fact it is the Kernel.` method.

