# go-cheat-sheet
Notes


## struct

like a custom type in Typescript

## Pointers

Pointer type stores location of a variable.

```
func main() {
  var name string
  var namePointer *string
}

& in front of variable name means that we want to pull the pointer address from an actual value. * in front of variable name means we want to "dereference" or get the actual value of a pointer.

* in front of a type means that it's a pointer.

* in front of a variable means that it's a value.

