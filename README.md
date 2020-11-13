ENGLISH | [日本語](https://github.com/NNCT3J/F-lang/blob/main/README_JP.md)
# F-lang
Library for C-lang which can output "それ感想だよね？" within shortest codes in the whole world (maybe).

# Warning
This library isn't worked for **GCC** (because it's not allowed to use multi-byte characters for define).  
We recommend **Visual Studio 2019** for Windows users and **CLang** for UNIX users.

# Usage
Just include `"flang.h"` like:
```
#include "flang.h" //relative path of "flang.h"
```


# Sample
## それ感想だよね？
Like "Hello world" for F-lang.
```
#include "../flang.h" //relative path of "flang.h"
#include 表紙

それ 感想 だよ ね？
```
### Result
```
それ感想だよね？
```

## Other samples
There's a lot of sample for F-lang beginners in [samples](https://github.com/NNCT3J/F-lang/blob/main/samples).

- `sample.c` - [それ感想だよね？](https://github.com/NNCT3J/F-lang/blob/main/samples/sample.c)
- `sample2.c` - [それ感想だよね？ for 15 years](https://github.com/NNCT3J/F-lang/blob/main/samples/sample2.c)
- `sample3.c` - [Bubble sort for fixed data](https://github.com/NNCT3J/F-lang/blob/main/samples/sample3.c)
- `sample4.c` - [Bubble sort for variable data](https://github.com/NNCT3J/F-lang/blob/main/samples/sample4.c)