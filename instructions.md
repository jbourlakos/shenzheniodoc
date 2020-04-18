# Instructions

## Basic

```
nop                     ; Do nothing

mov     R/I     R       ; Assign #1 to #2

jmp     L               ; Go to label L

slp     R/I             ; Sleep for #1 time units

slx     P               ; Sleep until value in P
```

## Arithmetic

```
add     R/I             ; Add #1 in acc

sub     R/I             ; Subtruct #1 from acc

mul     R/I             ; Multiply acc by #1

not                     ; Invert acc

dgt     R/I             ;

dst     R/I     R/I     ;
```

## Test Instructions

```
teq     R/I     R/I     ; Set acc to ??? if #1 equals #2

tgt     R/I     R/I     ; Set acc to ??? if #1 is greater than #2

tlt     R/I     R/I     ; Set acc to ??? if #1 is less than #2

tcp     R/I     R/I     ;
```
