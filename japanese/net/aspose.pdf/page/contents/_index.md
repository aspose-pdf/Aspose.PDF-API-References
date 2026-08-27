---
title: "Page.Contents"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Page プロパティ。ページのコンテンツストリーム内のオペレーターのコレクションを取得します。OperatorCollection"
type: docs
weight: 90
url: /ja/net/aspose.pdf/page/contents/
---
## Page.Contents property

ページのコンテンツストリーム内のオペレーターのコレクションを取得します。[`OperatorCollection`](../../operatorcollection/)

```csharp
public OperatorCollection Contents { get; }
```

## 例

例はページのオペレーター ストリームをスキャンする方法を示しています。

```csharp
Document document = new Document("sample.pdf");
Operators contents = document.Pages[1].Contents;
foreach(Operator op in contents)
{
    Console.WriteLine(op);
}
```

### 関連項目

* class [OperatorCollection](../../operatorcollection/)
* class [Page](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


