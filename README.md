# programming-language-idea-history
Tracing where features and concepts come from in programming languages

## List of languages to start with

* **Today's Big Three**: Java, JavaScript, Python
* **GC languages**: C#, Kotlin, D, Go, Nim, Zig, Scala, Clojure, Swift, Dart, Haxe
* **GC-less languages**: C, C++, Rust
* **FP languages**: Haskell, Racket, SML, OCaml, F#, Elm, PureScript
* **Scripting languages**: Lua, Julia, R, Ruby, Matlab, VBA, Groovy, PowerShell, Erlang, Perl, PHP, TypeScript
* **Declarative languages**: CSS, HTML, SQL
* **Forgotten languages**: Ada, Awk, HyperTalk, Modula-3, Self, Smalltalk, Oberon, Algol 60, Algol 68, Cobol, Fortress, BASIC, Simula, Oz, Prolog, Dylan, Delphi, PL/I, APL

## Link to a talk about `else`

[This talk](https://github.com/ericfischer/if-then-else/blob/master/if-then-else.md) is great, and lays out the history of if-else. [HN discussion](https://news.ycombinator.com/item?id=25406211).

## Link to C language history

[From the Internet Archive](https://web.archive.org/web/20080724200738/http://cm.bell-labs.com/who/dmr/chist.html).

In which I learn that the reason B and C use `break` (as opposed to a separate keyword like `endcase`) to escape out of `switch` statements, is that B was based on an older version of BCPL, before BCPL got the `endcase` keyword.

Interestingly, Perl 6/Raku re-introduced the difference with its `succeed` keyword.

## The separate compilation in ML was inspired by Modula

See https://github.com/masak/interesting-papers/issues/450 for details.

## Nim was inspired by Modula/Oberon

Its type and module systems were, according to [this HN thread](https://news.ycombinator.com/item?id=26275553).
