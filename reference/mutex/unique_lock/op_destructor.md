#デストラクタ (C++11)
```cpp
~unique_lock();
```

##概要
ロックを手放す


##効果
`if (`[`owns_lock()`](./owns_lock.md)`) {` 
`  pm->unlock();` 
`}` 
※`pm`はメンバ変数として保持している、ミューテックスオブジェクトへのポインタ


##例
```cpp
```

###出力
```
```

##バージョン
###言語
- C++11

###処理系
- [Clang](/implementation.md#clang): ??
- [GCC](/implementation.md#gcc): 
- [GCC, C++0x mode](/implementation.md#gcc): 4.7.0
- [ICC](/implementation.md#icc): ??
- [Visual C++](/implementation.md#visual_cpp) ??


##参照

