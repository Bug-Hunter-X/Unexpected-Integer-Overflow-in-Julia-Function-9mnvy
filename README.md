# Julia Integer Overflow Bug

This repository demonstrates a subtle integer overflow bug in a Julia function.  The `myfunction` is designed to return the square of its input if positive, and the negative of the square if negative. However, it exhibits unexpected behavior when the input is 0 due to an edge case not explicitly handled.

The solution involves adding a check for 0 input to prevent the potential overflow issue.