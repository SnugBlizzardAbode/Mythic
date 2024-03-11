# The Mythic Programming Language

Mythic is a general-purpose programming language designed for empowering
developers to write secure software without shoving complexity in your face.

Website: [https://mythic-lang.org](https://mythic-lang.org)
<br/>
<br/>

```mythic
mod player
    enum Mushroom
    | Blue
    | Brown
    | Red
    ;

    enum State
    | Mario 
    | SuperMario
    | MiniMario
    | FireMario
    ;

    class Mario
        struct {
        state = State.Mario,
        coin = 0,
        }

        fn eat_shroom(var self, shroom)
            use State
            match #(self.state,shroom)
            | #(Mario, Brown) => self.state = SuperMario
            | #(_, Blue) => self.state = MiniMario
            | #(_, Red) => self.state = FireMario
            | #(_, Brown) => 
            ;
        ;
    ; // end class
; // end module

fn main()
    let user = player::Mario{}
    user.eat_shroom(Mushroom.Brown)

    let b = #(1,"ok") // tuple
    let c = #[1,2,3]  // list creation
    c[0] // accessing index 

    let d = check::Bar.Yay // enum instance
    // :: only for accessing modules

    if (condition)
        // blah
    elif (condition)
        // mm
    else
        // else uhhh
    ;
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