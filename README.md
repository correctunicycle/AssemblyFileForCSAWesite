# Assembly Files For CSA Wesite
example asssembly files for use with the pipelining website accessible here: https://csawebsite.herokuapp.com
The website will parse the assembly instructions out of the file, and only these should be edited as the parsing code uses the consistent formatting of the objdump output of Arm assembly instructions to parse out the assembly. Because of this the assembly instructions must be separated from the machine opcodes by a tab, and the operands of the instruction must also be separated from the instruction by a tab.
These are some simple examples, but the website should work with any of the instructions listed on the homepage of the website, in any combination, with the only limatation being the number of instructions, which must be 5.
