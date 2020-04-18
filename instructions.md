# Instructions

## Basic

```
nop                     # Do nothing

mov     R/I     R       # Copy value of #1 to #2

jmp     L               # Go to label L

slp     R/I             # Sleep for #1 time units

slx     X               # Sleep until data are read from X pin
```

## Arithmetic

```
add     R/I             ; Add #1 in acc

sub     R/I             ; Subtruct #1 from acc

mul     R/I             ; Multiply acc by #1

not                     ; If acc == 0 acc = 100 else acc = 0

dgt     R/I             ; Read the #1-th digit of acc to acc

dst     R/I     R/I     ; Change the #1-th digit of acc to value of #2
```

## Test Instructions

```
teq     R/I     R/I     ; If #1 == #2, Enable + instruction else enable - instruction

tgt     R/I     R/I     ; If #1 > #2, Enable + instruction else enable - instruction

tlt     R/I     R/I     ; If #1 < #2, Enable + instruction else enable - instruction

tcp     R/I     R/I     ; If #1 > #2, Enable + instruction, if #1 < #2 enable - instruction
```
