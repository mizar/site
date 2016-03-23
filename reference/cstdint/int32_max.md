#INT32_MAX
* cstdint[meta header]
* macro[meta id-type]
* cpp11[meta cpp]

```cpp
#define INT32_MAX implementation-defined
```
* implementation-defined[italic]

##概要
[`int32_t`](int32_t.md) の最大値を表す定数。

ビット数32をNとして、このマクロの値は2<sup>N-1</sup> - 1である2147483647となる。

その値の型は、[`int32_t`](int32_t.md)を整数昇格したものとなる。

なお、このマクロは [`int32_t`](int32_t.md) が定義されていない場合には定義されない。

##例
```cpp
#include <iostream>
#include <cstdint>

int main()
{
  std::int32_t max_value = INT32_MAX;
  std::cout << static_cast<long>(max_value) << std::endl;
}
```
* std::int32_t[link int32_t.md]
* std::cout[link /reference/iostream/cout.md]
* std::endl[link /reference/ostream/endl.md]


###出力
```
2147483647
```


##バージョン
###言語
- C++11

###処理系
- [Clang C++11 mode](/implementation.md#clang): 3.3
- [GCC, C++11 mode](/implementation.md#gcc): 4.4
- [ICC](/implementation.md#icc): ??
- [Visual C++](/implementation.md#visual_cpp): ??
