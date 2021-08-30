# JSudokuSolver
A "one-liner" sudoku solver in the [J programming language](https://en.wikipedia.org/wiki/J_(programming_language))

Here it is:
```
q=:0
s=:3 :0
z=.i.3[g=.]{~[:<(z+[:{.[);z+[:{:[
l=.(([:{:[){[:|:]),]{~[:{.[
d=.I.0=,y.if.0=$d do.qprintf'y 'return.end.d=.{.d
e=.y((i.10)-.(l,(<.&.(%&3)@[,@g])))~(<.d%9),9|d
if.0=#e do.return.end.s"2 e((<(<.d%9);9|d)})"0 2 y
)
```
