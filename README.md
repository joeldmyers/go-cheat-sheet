# go-cheat-sheet
Notes


## struct

like a custom type in Typescript

## interface

Like a custom type that gives methods given for a particular type.

## Pointers

Pointer type stores location of a variable.

```
func main() {
  var name string
  var namePointer *string
  
  name = "Johnny"
  namePointer = &name
  nameValue = &namePointer
}
```

_&_ in front of variable name means that we want to pull the pointer address from an actual value. 

_*_ in front of variable name means we want to "dereference" or get the actual value of a pointer.

_*_ in front of a type means that it's a pointer.

_*_ in front of a variable means that it's a value.

