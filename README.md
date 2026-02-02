# Compiler for a custom and 'simplified' version of C, FanC
This is a compiler my classmate Rouya and I (Bisan) created as part of our compilation theory class. 
It was a semester-long project 

# What is a compiler
A compiler is essentially a translator.

# SO, what did we translate FanC to in this project? 
We translated FanC to LLVM IR. A low-level 'intermediate' abstract assembly-like language. 

# Why LLVM?
As mentioned above, LLVM IR is ABSTRACT. It doesn't target any hardware-dependent architecture. Most assembly versions out there are specifically designed to run on certain architecture. 
We didn't want to target a specific architecture (86X / ARM ect).

# High-level design overview
