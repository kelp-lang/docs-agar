# Instructions
| symbol    | usage                         | description                                                          |
| --------- | ----------------------------- | -------------------------------------------------------------------- |
| `add`     | `add %var1 %var2 %result`     | add `%var1` and `%var2` together                                     |
| `sub`     | `sub %var1 %var2 %result`     | subtract `%var2` from `%var1`                                        |
| `eq`      | `eq %var1 %var2 %result`      | set `%result` to `%true` if equal, otherwise `%false`                |
| `neq`     | `eq %var1 %var2 %result`      | set `%result` to `%false` if equal, otherwise `%true`                |
| `ret`     | `ret type`                    | specifies type of the result                                         |
| `app`     | `app %args :blockname %ret`   | applies `%args` to a function and sets the value of the `%result`    |
| `val_cpy` | `val_cpy %var`                | sets value of parent block to `%var` by copying the value            |
| `val`     | `val %var`                    | sets value of parent block to `%var` by copying pointer              |
| `set`     | `set %var1 (%var2|primitive)` | sets value of `%var1` to `%var2` or primitive by copying the pointer |
| `jmp`     | `jump :name %ret?`            | jumps to a specific block                                            |
| `jmp_eq`  | `jmp_eq %var :name %ret?`     | jumps to block only if `%var` is `%true`                             |
| `jmp_neq` | `jmp_neq %var :name %ret?`    | jumps to block only if `%var` is `%false`                            |