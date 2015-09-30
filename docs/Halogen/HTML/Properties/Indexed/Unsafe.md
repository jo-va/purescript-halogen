## Module Halogen.HTML.Properties.Indexed.Unsafe

#### `IProp`

``` purescript
newtype IProp (ρ :: # *) i
  = IProp (Prop i)
```

The phantom row `ρ` can be thought of as a context which is synthesized in the
course of constructing a refined HTML expression.

