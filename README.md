This ALU is a combination circuit that operate on 4-bit numbers. It has two inputs A and B, and an output Y. It has four operations that can be selected: add, subtract, set-less-than, and bit-wise-AND. To select an operation, the ALU has a 2-bit select input Sel which selects as follows:

Sel = 00: operation = add
Sel = 01: operation = sub
Sel = 10: operation = set-less-than
Sel = 11: operation = bit-wise-AND

There are three 4-bit registers: RegA, RegB and RegY. They are all synchronized with the lcock signal of the Basys board. RegA and RegB have a load input and a clear input. 
# ALU
