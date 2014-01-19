# Haskell for Light Table

A plugin that supports inline-evaluation of Haskell code in Light Table.

It spawns a `ghci` process in the background and sends code and commands
to it. It can currently evaluate the current selection or line and display
the type of expressions. Because it uses `ghci` you should also be able
to `import` libraries and do other things that `ghci` supports.

## todo

* select expressions/forms (ideally by asking a proper haskell parser,
    but maybe a guessing based on indentation would also work?)
* show documentation for variables (haddock, hoogle?)
* search for functions that fit a given type (hoogle supports this but
    might not have an api)

## ideas

* this interaction style might be suitable for other language
    plugins (spawning a repl, sending commands to it)