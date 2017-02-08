This is a **NOT** a mirror of http://www.vim.org/scripts/script.php?script_id=2771,
or https://github.com/vim-scripts/Conque-Shell
because the both of these sources are missing the Python files in autoload directory!
So I was forced to mirror the original svn from http://code.google.com/p/conque/.

*Conque-shell* is a Vim plugin allowing users to execute and interact with programs, typically a shell such as *bash*, inside a buffer window. The goal is always to keep the terminal behavior as close as possible to its native interface, while adding the additional features of *Vim* on top.

# WEBSITE

For more information http://code.google.com/p/conque/

# SCREENSHOTS

http://Conque.googlecode.com/svn/wiki/screenshot/colors.jpg

http://Conque.googlecode.com/svn/wiki/screenshot/mysql.jpg

http://Conque.googlecode.com/svn/wiki/screenshot/send.jpg

http://Conque.googlecode.com/svn/wiki/screenshot/shells.jpg

# USAGE

Type `:ConqueTerm <command>` to run your command in vim, for example:

```
:ConqueTerm bash
```
```
:ConqueTerm mysql -h localhost -u joe -p sock_collection
```
```
:ConqueTerm ipython
```

To open `ConqueTerm` in a new horizontal or vertical buffer use:

```
:ConqueTermSplit <command>
:ConqueTermVSplit <command>
:ConqueTermTab <command>
```

All text typed in insert mode will be sent to your shell. 

Use the `<F9>` key to send a visual selection from any buffer to the shell.

For more help type `:help ConqueTerm`

