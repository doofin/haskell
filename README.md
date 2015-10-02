# Toward a pure conceptual world

### Hierarchys of prevalent abstraction --typeclasses

https://wiki.haskell.org/Typeclassopedia

### Visual graphical functional language

http://www.researchgate.net/publication/242377072_A_Visual_Programming_Environment_for_Functional_Languages

### Template Haskell

[| ... |], or [e| ... |], where the "..." is an expression; the quotation has type Q Exp.

[d| ... |], where the "..." is a list of top-level declarations; the quotation has type Q [Dec].

[t| ... |], where the "..." is a type; the quotation has type Q Type.

[p| ... |], where the "..." is a pattern; the quotation has type Q Pat.

http://research.microsoft.com/en-us/um/people/simonpj/papers/meta-haskell/meta-haskell.pdf

https://downloads.haskell.org/~ghc/latest/docs/html/users_guide/template-haskell.html

https://wiki.haskell.org/Template_Haskell

### ghc(Haskell compiler) structure introduction

http://www.aosabook.org/en/ghc.html

### development environment

#### as script
haskell as a script language (runhaskell is included in Haskell bundle)

    #!/usr/bin/env runhaskell
    main :: IO ()
    main = putStr "hello"

haskell turtle lib : invoke bash command 

#### Editor written in haskell
Yi

#### emacs

C-x 5 2
Create a new frame(window) (make-frame-command).



### distribute

https://en.wikibooks.org/wiki/Haskell/Packaging
