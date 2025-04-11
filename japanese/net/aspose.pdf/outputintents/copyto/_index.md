---
title: OutputIntents.CopyTo
second_title: Aspose.PDF for .NET API Reference
description: OutputIntents メソッド。コレクションの要素を特定の arrayIndex から配列にコピーします。
type: docs
weight: 70
url: /ja/net/aspose.pdf/outputintents/copyto/
---
## OutputIntents.CopyTo メソッド

コレクションの要素を *array* にコピーし、特定の *arrayIndex* から配列にコピーを開始します。

```csharp
public void CopyTo(OutputIntent[] array, int arrayIndex)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| array | OutputIntent[] | コレクションからコピーされた出力インテントの宛先である一次元配列。配列はゼロベースのインデックスでなければなりません。 |
| arrayIndex | Int32 | コピーが開始される *array* 内のゼロベースのインデックス。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentNullException | *array* が null です。 |
| ArgumentOutOfRangeException | *arrayIndex* が 0 未満です。 |
| ArgumentException | ソースの [`OutputIntents`](../) の要素数が、宛先 *array* の *arrayIndex* から末尾までの利用可能なスペースを超えています。 |

### 参照

* クラス [OutputIntent](../../outputintent/)
* クラス [OutputIntents](../)
* 名前空間 [Aspose.Pdf](../../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../../)