# AssemblyProject

This is where we will come up with some instructions.

Arithmetic:

    0xA...

        + 0xA0
        - 0xA1
        * 0xA2
        % 0xA3

Conditionals:

    0xC...

        == 0xC0
        != 0xC1
        <= 0xC2
        >= 0xC3
        <  0xC4
        >  0xC5

Jumping:

    Lable 0x1...

    0xD...

        jmp 0xD0
        cmp 0xD1        
        je  0xD2
        jl  0xD3
        jg  0xD4
        jle 0xD5
        jge 0xD6

Output:

    OxF...

        cout     0xF0 (0xF00Reg)
        mem dump 0xF1 (dumps all)
        reg dump 0xF2 (dumps all)

Input:

    0xE...

        mov 0xE0
        mov from another reg 0xE1
        Cin to reg 0xE2

Registers:

    regs[0x0]->regs[0xF]