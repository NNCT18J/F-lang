ENGLISH | 日本語
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
### 実行結果
```
それ感想だよね？
```

## Other samples
There's a lot of sample for F-lang beginners in samples

- `sample.c` - それ感想だよね？
- `sample2.c` - 15カ年分のそれ感想だよね？
- `sample3.c` - 決まったデータのバブルソート
- `sample4.c` - 可変数個のデータに対するバブルソート