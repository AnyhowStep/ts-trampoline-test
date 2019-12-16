### `trampoline-test`

Created for,

https://github.com/microsoft/TypeScript/issues/26980#issuecomment-566206039

-----

### Instructions

1. `npm install`
1. `npm run build`

Check output in `dist` directory.

Check diagnostics from `tsc` output.

-----

The output for my laptop,
```
> tsc

Files:                         35
Lines:                       7592
Nodes:                      22476
Identifiers:                 6802
Symbols:                   485370
Types:                     220971
Memory used:              153478K
Assignability cache size:    3546
Identity cache size:            0
Subtype cache size:             0
I/O Read time:              0.00s
Parse time:                 0.12s
Program time:               0.13s
Bind time:                  0.05s
Check time:                 1.83s
transformTime time:         0.04s
Source Map time:            0.00s
commentTime time:           0.01s
I/O Write time:             0.00s
printTime time:             0.07s
Emit time:                  0.07s
Total time:                 2.09s
```