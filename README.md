# CHERI permissions

Explains CHERI capabilities, when the output is printed from [the `pp_cap` function](https://github.com/capablevms/cheri-examples/blob/master/include/common.h#L10).
Explanations are sourced from Section 3.2 Capabilities, from the ["Capability Hardware Enhanced RISC Instructions: CHERI Instruction-set architecture" technical report](https://www.cl.cam.ac.uk/techreports/UCAM-CL-TR-850.pdf).

For example, the input

``` sh
Tag: 1, Perms: 2c177, Type: 1, Address: 110bd1, Base: 100000, End: 1311c0, Flags: 0, Length: 311c0, Offset: 10bd1
```

Would be valid for the processor
