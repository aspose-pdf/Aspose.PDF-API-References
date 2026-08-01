---
title: "OperatorCollection.Item"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "OperatorCollection プロパティ。インデックスで演算子を取得します"
type: docs
weight: 40
url: /ja/net/aspose.pdf/operatorcollection/item/
---
## OperatorCollection indexer

インデックスでオペレーターを取得します。

```csharp
public override Operator this[int index] { get; set; }
```

| パラメーター | 説明 |
| --- | --- |
| インデックス | 演算子のインデックス。番号は 1 から始まります。 |

### 戻り値

要求されたインデックスの演算子

## 例

例では、インデックスでページコンテンツの演算子を取得する方法を示しています。

```csharp
Document doc = new Document("input.pdf");
OperatorCollection oc = doc.Pages[1].Contents;
Operator first = oc[1];
```

### 関連項目

* class [Operator](../../operator/)
* class [OperatorCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


