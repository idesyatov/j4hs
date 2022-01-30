# j4hs

## Some snippets for hs

* ### [MyPrint.hs](MyPrint.hs)

Unescaping printing (Maybe useful for educational purposes but for debugging, as well! When you have functions that are defined on strings representing words of other languages, with non-ASCII characters)

Example

```sh
Prelude> names = [("Hello","world"), ("Привет","Мир")]
Prelude> print names
[("Hello","world"),("\1055\1088\1080\1074\1077\1090","\1052\1080\1088")]
Prelude>
Prelude>
Prelude> :load MyPrint
[1 of 1] Compiling MyPrint          ( MyPrint.hs, interpreted )
*MyPrint>
*MyPrint>
*MyPrint> names = [("Hello","world"), ("Привет","Мир")]
*MyPrint> myPrint names
[("Hello","world"),("Привет","Мир")]

```
