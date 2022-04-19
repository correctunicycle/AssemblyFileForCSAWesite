# Assembly Files For CSA pipelining website
Example asssembly files for use with the pipelining website accessible here: https://csawebsite.herokuapp.com
The website will parse the assembly instructions out of the file, in order for it to do this the following formatting must be adhered to:
* Instructions separated from operands with a tab (Not spaces!)
* operands separated by a space
* There must be 5 instructions defined in the uploaded .txt file, no more, no less.

The website will recognise any combination of letters and numbers as valid instruction operands. In the example files notation like X1 and X2 is used, but ab, xy, 569Z etc would all be equalid valid. The only exception is if they include a hash key, in which case they will be recognised as numeric constants.
If these formatting rules are not adhered to the website will fail to parse the instructions correctly and produce incorrect output.

