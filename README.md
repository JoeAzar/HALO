HALO - Haskell List Operations (in Java)
====
This library includes the methods: takeWhile(), any(), all(), dropWhile(), reverse(), elem(), elemIndices(), elemIndex(), findIndex(), findIndices(), lines(), unlines(), words(), unwords(), and concat() for 2D arrays and 1D String arrays.

This library also includes a parser for boolean expressions. While I won't make any guarantees, I have tested it as thoroughly as I can, and it seems to be working flawlessly. A few things to note, however:

You cannot use the "!" operator in an expression (yet).

For comparison of strings, use ==, !=, etc...

For exponentiation, use ^

PEMDAS ("order of operations") is followed for mathematical expressions.

Boolean operators (namely && and ||) retain their short circuit properties.

Otherwise, expressions can be written very similar to a normal if statement.

As I have written the parser myself, I would not recommend using these operations in any truly performance critical code.

Give it a try! I'd love to hear your comments and criticism. Also, you can download this library as a .jar here: https://mega.co.nz/#!8tMChYiY!Kv8qFV5nciLJHeuqATmenE7oW6YVR93Ot1T1DDc-Voo
