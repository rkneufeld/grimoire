## Arities
[]
[f]
[f g]
[f g h]
[f1 f2 f3 & fs]

## Documentation
Takes a set of functions and returns a fn that is the composition
  of those fns.  The returned fn takes a variable number of args,
  applies the rightmost of fns to the args, the next
  fn (right-to-left) to the result, etc.
