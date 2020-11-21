# variables
reference a variable with `%varname`.
## global variables
there are some global variables
| name     | description   |
| -------- | ------------- |
| `%true`  | boolean true  |
| `%false` | boolean false |
## unnamed variables
variables don't need to have names, you can create an unnamed variable by providing number instead of `varname`.
```agar
set %0 0
add %0 1
// now %0 is 1
```