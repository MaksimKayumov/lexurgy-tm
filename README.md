# lexurgy-tm
An implementation of Wolfram 2-state 3-symbol Turing machine in Lexurgy sound applier.
## How it works
Tape is represented as follows: 0 is z, 1 is o, 2 is t. Either a or b (depending on the state) is added before cell that pointer is pointing at. l is added at the beginning of tape and r at the end. After sound changes are applied to current tape The next state of a tape is outputted.
### Examples
After sound changes applied string lazr would become lzobzr. If we applie sound changes to lzobzr then it would become lzzaotzr and if we applie sound changes to that string then we would get lzzazttzzr Which represents:

0 0 0 2 2 0 0

And pointer is on third zero
