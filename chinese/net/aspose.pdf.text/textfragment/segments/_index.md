---
title: TextFragment.Segments
second_title: Aspose.PDF for .NET API Reference
description: TextFragment 属性。获取当前 TextFragment 的文本段
type: docs
weight: 120
url: /zh/net/aspose.pdf.text/textfragment/segments/
---
## TextFragment.Segments 属性

获取当前 [`TextFragment`](../) 的文本段。

```csharp
public TextSegmentCollection Segments { get; set; }
```

## 备注

简单来说，[`TextSegment`](../../textsegment/) 对象是 [`TextFragment`](../) 对象的子对象。高级用户可以直接访问段以执行更复杂的文本编辑场景。有关详细信息，请查看 [`TextFragment`](../) 对象描述。

## 示例

该示例演示如何导航所有 [`TextSegment`](../../textsegment/) 对象在 [`TextFragment`](../) 内部。

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// Navigate all text segments and out their text and placement info
foreach (TextSegment segment in absorber.TextFragments[1].Segments)
{
    Console.Out.WriteLine(string.Format("segment text: {0}", segment.Text));
    Console.Out.WriteLine(string.Format("segment X indent: {0}", segment.Position.XIndent));
    Console.Out.WriteLine(string.Format("segment Y indent: {0}", segment.Position.YIndent));
}

```

### 另请参阅

* 类 [TextFragmentAbsorber](../../textfragmentabsorber/)
* 类 [Document](../../../aspose.pdf/document/)
* 类 [TextSegment](../../textsegment/)
* 类 [TextSegmentCollection](../../textsegmentcollection/)
* 类 [TextFragment](../)
* 命名空间 [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* 程序集 [Aspose.PDF](../../../)