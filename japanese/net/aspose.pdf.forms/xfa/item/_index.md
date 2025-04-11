---
title: XFA.Item
second_title: Aspose.PDF for .NET API Reference
description: XFA プロパティ。パスに従ってデータノードの値を取得または設定します
type: docs
weight: 50
url: /ja/net/aspose.pdf.forms/xfa/item/
---
## XFA インデクサー

*path* に従ってデータノードの値を取得または設定します。

```csharp
public string this[string path] { get; set; }
```

| パラメーター | 説明 |
| --- | --- |
| path | データノードのパス。例: form1[0].Subform1[0].Subform2[0].Subform3[0].TextField[0]。データが各ノードの単一の出現のみを含む場合でも、インデックスを含めることを確認してください。つまり、node1[0].node2[0]... と書きます。node1.node2... の代わりに。 |

### 戻り値

データノードの値。

### 参照

* クラス [XFA](../)
* 名前空間 [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* アセンブリ [Aspose.PDF](../../../)