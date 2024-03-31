# The Mythic Programming Language

Mythic is a general-purpose programming language designed for empowering
developers to write secure software without shoving complexity in your face.

Website: [https://mythic-lang.org](https://mythic-lang.org)
<br/>
<br/>

<br/>

## Installing

#### [How to install](https://mythic-lang.org/install)

Instructions for downloading and installing the Mythic compiler.

<br/>
<br/>
<br/>

## Learn Mythic

#### [Documentation](https://mythic-lang.org/learn)

Documentation on how to program in mythic.

#### [Community](https://discord.gg/qURCVCA7KP)

Chat with Mythic programmers on the community Discord.

<br/>
<br/>

## Caution

* The Mythic language is still under development.

<br/>
<br/>

## Syntax Example
```mythic
import 
    path::to::library::{a,b}
    "path/to/file_1"
    "/Users/foo/file_2"
;

mod other 
    /*
        Block comment
    */
;

fn main()
    // Variables
    let non_reassignable = 1
    var mutable = 2

    // Negative number with ~
    const COMP_VALUE: int = ~3
    static non_changable = 4
    
    foo() // function call
    Bar.g() // method

    #(1,2) // Tuple creation
    #[1,2,3] // List creation

    struct Point{x: int, y: int}
    let tree = Point{x: 22, y: 39}

    enum Drink
    | Water
    | Soda
    ;
    let fav = Drink.Water

    match fav
    | Water => print('refreshing')
    | _ => 
    ;

    for (i in 1..10)
        print('😄')
    ;

    if (condition) 
    elif (condition) 
    ;
    "Thanks for all the fish."
;
```