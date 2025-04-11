---
title: OperatorCollection.Item
second_title: Aspose.PDF for .NET API Reference
description: OperatorCollection プロパティ。インデックスによってオペレーターを取得します
type: docs
weight: 40
url: /ja/net/aspose.pdf/operatorcollection/item/
---
## OperatorCollection インデクサー

インデックスによってオペレーターを取得します。

```csharp
public override Operator this[int index] { get; set; }
```

| パラメーター | 説明 |
| --- | --- |
| index | オペレーターのインデックス。番号付けは 1 から始まります。 |

### 戻り値

要求されたインデックスからのオペレーター

## 例

例は、インデックスによってページコンテンツのオペレーターを取得する方法を示しています。

```csharp
Document doc = new Document("input.pdf");
OperatorCollection oc = doc.Pages[1].Contents;
Operator first = oc[1];
```

### 参照

* クラス [Operator](../../operator/)
* クラス [OperatorCollection](../)
* 名前空間 [Aspose.Pdf](../../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../../)