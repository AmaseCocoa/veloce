# veloce
easy, fast compiled language.

## Purpose
* Create a language with a syntax that is easy to understand and performs as well or better than C.
## Compiler
* Here's an experimental compiler using Python: [AmaseCocoa/pveloce](https://github.com/AmaseCocoa/pveloce)
* The Phase 1 compiler will be Go.
* There are plans to eventually rewrite the compiler itself in Veloce.

## Syntax
```
println("Hello")

fn greeting(name: string) {
  println(f"Hello, {name}!")
}

greeting("Veloce") // Hello, Veloce!
```
## Todo
* Compatibility with other languages
* Interpreter mode (executes code without the need to compile, like Node.js, etc., but with lower performance)
