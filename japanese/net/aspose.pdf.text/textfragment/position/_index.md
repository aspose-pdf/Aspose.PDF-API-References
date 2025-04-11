---
title: TextFragment.Position
second_title: Aspose.PDF for .NET API Reference
description: TextFragment プロパティ。TextFragment オブジェクトで表されるテキストの位置を取得または設定します。
type: docs
weight: 90
url: /ja/net/aspose.pdf.text/textfragment/position/
---
## TextFragment.Position プロパティ

[`TextFragment`](../) オブジェクトで表されるテキストの位置を取得または設定します。

```csharp
public Position Position { get; set; }
```

## 例

この例では、[`TextFragment`](../) オブジェクトで表されるテキストの配置を表示する方法を示します。

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// View text and placement info of first text occurrence
TextFragment firstOccurrence = absorber.TextFragments[1];

Console.Out.WriteLine(string.Format("fragment text: {0}", firstOccurrence.Text));
Console.Out.WriteLine(string.Format("fragment X indent: {0}", firstOccurrence.Position.XIndent));
Console.Out.WriteLine(string.Format("fragment Y indent: {0}", firstOccurrence.Position.YIndent));

```

### 関連項目

* クラス [TextFragmentAbsorber](../../textfragmentabsorber/)
* クラス [Document](../../../aspose.pdf/document/)
* クラス [TextSegment](../../textsegment/)
* クラス [Position](../../position/)
* クラス [TextFragment](../)
* 名前空間 [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* アセンブリ [Aspose.PDF](../../../)