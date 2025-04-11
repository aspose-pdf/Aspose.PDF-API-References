---
title: Page.Contents
second_title: Aspose.PDF for .NET API Reference
description: ページプロパティ。ページのコンテンツストリーム内のオペレーターのコレクションを取得します。 [`OperatorCollection`](../../operatorcollection/)
type: docs
weight: 90
url: /ja/net/aspose.pdf/page/contents/
---
## ページ.コンテンツプロパティ

ページのコンテンツストリーム内のオペレーターのコレクションを取得します。 [`OperatorCollection`](../../operatorcollection/)

```csharp
public OperatorCollection Contents { get; }
```

## 例

例は、ページのオペレーターストリームをスキャンする方法を示しています。

```csharp
Document document = new Document("sample.pdf");
Operators contents = document.Pages[1].Contents;
foreach(Operator op in contents)
{
    Console.WriteLine(op);
}
```

### 参照

* クラス [OperatorCollection](../../operatorcollection/)
* クラス [Page](../)
* 名前空間 [Aspose.Pdf](../../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../../)