#  c++ macros for python code

You use it like a string split on the newline character, then parse that list, do preprocessor logic as an interpreter, print or execute.

# Why?

Because compiling large bundles of code takes time and energy the developer doesn't have time to waste. Or maybe they have time to setup a thing that will  keen most of the code they write structured to run correctly. Or compiling the code in the initial language took up time and added unneeded or unwanted complexity. Then you'd make something like this to see what they code would look like with a bunch of defined macros or predefined macros you seed in. Or maybe one is debugging code and you need an interpreter to point out the bug while it is running without using gdb. Or maybe one needed to get a feel of what c++ was like with a simple emulator built on python without compiling but doing the equivalent reaching down into the low level functionality of c++ & assembly.

And it was a simpler to find one piece needed to add macros into python the simple way.
