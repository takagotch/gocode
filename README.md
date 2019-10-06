### gocode
---
https://github.com/nsf/gocode

```go
// type_alias_build_hack_18.go

func typeAliasSpec(name string, typ ast.Expr) *ast.TypeSpec {
  return &ast.TypeSpec{
    Name: ast.NewIdent(name),
    Type: typ,
  }
}

func isAliasTypeSpec(t *ast.TypeSpec) bool {
  return false
}
```

```
```

```
```


