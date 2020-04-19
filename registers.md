# Registers, memory, values

## Generic symbols

```
R   ; Any register

I   ; Integer from -999 to 999

R/I ; Register or integer

P   ; Simple I/O Pin register (p0, p1, ...)

L   ; Label (see instruction jmp)

X   ; XBus register (x0, x1, ...)
```

## MCxxxx registers

```
acc   ; accumulator, general-purpose register, affected by arithmetic
dat   ; general-purpose register
p0-p1 ; Simple I/O registers
x0-x3 ; XBus I/O registers
null  ; pseudo-register, reading value is zero, writing does nothing
```
