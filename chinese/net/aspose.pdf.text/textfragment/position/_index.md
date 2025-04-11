---
title: TextFragment.Position
second_title: Aspose.PDF for .NET API Reference
description: TextFragment 属性。获取或设置由 TextFragment 对象表示的文本位置
type: docs
weight: 90
url: /zh/net/aspose.pdf.text/textfragment/position/
---
## TextFragment.Position 属性

获取或设置由 [`TextFragment`](../) 对象表示的文本位置。

```csharp
public Position Position { get; set; }
```

## 示例

该示例演示如何查看由 [`TextFragment`](../) 对象表示的文本的放置位置。

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

### 另请参阅

* 类 [TextFragmentAbsorber](../../textfragmentabsorber/)
* 类 [Document](../../../aspose.pdf/document/)
* 类 [TextSegment](../../textsegment/)
* 类 [Position](../../position/)
* 类 [TextFragment](../)
* 命名空间 [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* 程序集 [Aspose.PDF](../../../)