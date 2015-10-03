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

https://ghc.haskell.org/trac/ghc/wiki/Commentary/Compiler

https://ghc.haskell.org/trac/ghc/wiki/Commentary

systemF : http://git.haskell.org/ghc.git/blob/refs/heads/master:/docs/core-spec/core-spec.pdf

ghc api : https://wiki.haskell.org/GHC/As_a_library

ghc haddock dir: 
file:///usr/local/haskell/ghc-7.8.3-x86_64/share/doc/ghc/html/libraries/ghc-7.8.3/index.html

### development environment

#### as script
haskell as a script language (runhaskell is included in Haskell bundle)

    #!/usr/bin/env runhaskell
    main :: IO ()
    main = putStr "hello"

haskell turtle lib : invoke bash command 

IO:

https://hackage.haskell.org/package/filemanip-0.3.6.3/docs/System-FilePath-Find.html

#### Editor written in haskell

Yi https://github.com/yi-editor/yi
    *auto complete https://github.com/yi-editor/yi/issues/779

#### emacs

C-x 5 2
Create a new frame(window) (make-frame-command).



### distribute

https://en.wikibooks.org/wiki/Haskell/Packaging
