---
title: "OutputIntents.CopyTo"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "OutputIntents メソッド。コレクションの要素を、特定の arrayIndex から配列へコピーします"
type: docs
weight: 70
url: /ja/net/aspose.pdf/outputintents/copyto/
---
## OutputIntents.CopyTo method

コレクションの要素を*array*にコピーし、特定の*arrayIndex*から配列に配置します。

```csharp
public void CopyTo(OutputIntent[] array, int arrayIndex)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| 配列 | OutputIntent[] | コレクションからコピーされた出力インテントの宛先となる一次元配列です。配列はゼロベースインデックスである必要があります。 |
| arrayIndex | Int32 | *array* のコピー開始位置のゼロベースインデックスです。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentNullException | *array* が null です。 |
| ArgumentOutOfRangeException | *arrayIndex* が 0 未満です。 |
| ArgumentException | ソース [`OutputIntents`](../) の要素数が、*arrayIndex* から宛先 *array* の末尾までの利用可能なスペースより大きいです。 |

### 関連項目

* class [OutputIntent](../../outputintent/)
* class [OutputIntents](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


