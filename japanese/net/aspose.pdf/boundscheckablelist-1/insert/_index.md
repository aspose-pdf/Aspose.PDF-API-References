---
title: BoundsCheckableList1.Insert
second_title: Aspose.PDF for .NET API Reference
description: BoundsCheckableList メソッド。指定されたインデックスに System.Collections.Generic.List に要素を挿入します。
type: docs
weight: 110
url: /ja/net/aspose.pdf/boundscheckablelist-1/insert/
---
## BoundsCheckableList&lt;T&gt;.Insert メソッド

指定されたインデックスに System.Collections.Generic.List に要素を挿入します。

```csharp
public void Insert(int index, T item)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| index | Int32 | アイテムを挿入するゼロベースのインデックス。 |
| item | T | 挿入するオブジェクト。参照型の場合、値は null であることができます。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentOutOfRangeException | *index* が 0 未満です。 -または- *index* が Count より大きいです。 |

### 参照

* クラス [BoundsCheckableList&lt;T&gt;](../)
* 名前空間 [Aspose.Pdf](../../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../../)