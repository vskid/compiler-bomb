# compiler-bomb
A compiler bomb with devastating consequences if you even try to compile/run it.

## Explanation ##
uint64_t is an unsigned 64-bit integer type.

The tilde (~) is the bitwise NOT operator in C (it flips the bits of a value).

(uint64_t)0 is 0000000000000000000000000000000000000000000000000000000000000000 in binary.

By applying the bitwise NOT operator, we get a... big number (2^64).

### Credits ###

Big thanks to PPCG user Digital Trauma for his original implementation. My version is really just an expansion from that.
