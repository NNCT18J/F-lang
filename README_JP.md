[ENGLISH](https://github.com/NNCT3J/F-lang) | 日本語
# F言語
「それ感想だよね？」を(自称)最速で出力できるC言語ライブラリ

# Warning
本ライブラリは**GCC**では動作しません(defineでマルチバイト文字を使えないため)．  
そのため，Windowsでは**Visual Studio 2019**，UNIX系では**CLang**などをお使いください．

# 使い方
`"flang.h"`を次のようにincludeしてください:
```
#include "flang.h" //"flang.h"の相対パスを指定
```

# サンプル
## それ感想だよね？
F言語で言う"Hello world"みたいな位置づけです．
```
#include "../flang.h" //relative path of "flang.h"
#include 表紙

それ 感想 だよ ね？
```
### 実行結果
```
それ感想だよね？
```

## その他のサンプル
F言語の学習者向けに豊富なサンプルが[samples](https://github.com/NNCT3J/F-lang/blob/main/samples)に置いてあります．

- `sample.c` - [それ感想だよね？](https://github.com/NNCT3J/F-lang/blob/main/samples/sample.c)
- `sample2.c` - [15カ年分のそれ感想だよね？](https://github.com/NNCT3J/F-lang/blob/main/samples/sample2.c)
- `sample3.c` - [決まったデータのバブルソート](https://github.com/NNCT3J/F-lang/blob/main/samples/sample3.c)
- `sample4.c` - [可変数個のデータに対するバブルソート](https://github.com/NNCT3J/F-lang/blob/main/samples/sample4.c)