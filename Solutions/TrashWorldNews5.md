# XA
```
GRAB 300
COPY F X
REPL START
MARK COPYSTART
COPY F M
COPY F X
REPL START
JUMP COPYSTART

MARK START
LINK 800
LINK 799
GRAB 212

MARK COMPARE
TEST F = X
FJMP COMPARE
SEEK -1
COPY M X
COPY X F
```

# XB
```
LINK 800
GRAB 200
LINK 800
HALT
```