# The Mythic Programming Language

Mythic is a general-purpose programming language designed for empowering
developers to write secure software without shoving complexity in your face.

Website: [https://mythic-lang.org](https://mythic-lang.org)
<br/>
<br/>

```mythic
package library::path{a,b}
import path/to/file

mod other;

/*
    Block comment
*/

fn main()
// Variables
    let non_reassignable = 1
    var mutable = 2
    const COMP_VALUE: int = 3
    static non_changable = 4
    
    foo() // function call
    Bar.g() // method

    #(1,2) // Tuple
    #[1,2,3] // List

    struct Point{x: int, y: int}
    Point{x: 22, y: 39}

    "Thanks for all the fish."
;
```
<br/>

## Installing

#### [How to install](https://mythic-lang.org/install)

Instructions for downloading and installing the Mythic compiler.
<br/>
<br/>

## Learn Mythic

#### [Documentation](https://mythic-lang.org/learn)

Documentation on how to program in mythic.

#### [Community](https://discord.gg/qURCVCA7KP)

Chat with Mythic programmers on the community Discord.

<br/>

## Caution

* The Mythic language is still under development.