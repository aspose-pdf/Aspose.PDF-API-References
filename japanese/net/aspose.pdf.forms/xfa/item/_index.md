---
title: "XFA.Item"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "XFA プロパティ。パスに従ってデータノードの値を取得または設定します"
type: docs
weight: 50
url: /ja/net/aspose.pdf.forms/xfa/item/
---
## XFA indexer

*path* に従ってデータノードの値を取得または設定します。

```csharp
public string this[string path] { get; set; }
```

| パラメーター | 説明 |
| --- | --- |
| パス | データノードのパス。例: form1[0].Subform1[0].Subform2[0].Subform3[0].TextField[0]。各ノードが単一であってもインデックスを必ず含めてください。つまり node1[0].node2[0]... と書き、node1.node2... と書かないでください。 |

### 戻り値

データノードの値。

### 関連項目

* class [XFA](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)


