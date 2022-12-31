# 日本語版C言語

## これは何？

これは日本版C言語、C言語のキーワードは、日本語に置き換えました。

## 現在の状態

Jp_C.hわ、日本語変数の定義が実装されました。

Jp_std_funcs.hわ、 一般的な標準関数日本語呼び出しが実装されています。

例えば：

```C
文字 変数A[] = "Hello, world!\n";
for(整数 変数B = 0; 変数B < 10; 変数B++)
{
    出力をフォーマット("%c\n", 変数A[変数B]);
}

```

## 使用方法

Demo*.c みてください、
```C 
#include "Jp_C.h"
#include "Jp_std_funcs.h"
```
ヘッダー ファイルは参照を参照を宣言する必要があります

