---
title: "TextFragment.Segments"
second_title: "Aspose.PDF for .NET API 参考"
description: "TextFragment 属性。获取当前 TextFragment 的文本段。"
type: docs
weight: 120
url: /zh/net/aspose.pdf.text/textfragment/segments/
---
## TextFragment.Segments property

获取当前 [`TextFragment`](../) 的文本段。

```csharp
public TextSegmentCollection Segments { get; set; }
```

## 备注

简而言之，[`TextSegment`](../../textsegment/) 对象是 [`TextFragment`](../) 对象的子对象。高级用户可以直接访问段以执行更复杂的文本编辑场景。有关详细信息，请查看 [`TextFragment`](../) 对象的描述。

## 示例

示例演示如何遍历 [`TextFragment`](../) 中的所有 [`TextSegment`](../../textsegment/) 对象。

```csharp
// 打开文档
Document doc = new Document(@"D:\Tests\input.pdf");

// 创建 TextFragmentAbsorber 对象以查找所有 "hello world" 文本出现
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// 接受第一页的吸收器
doc.Pages[1].Accept(absorber);

// 遍历所有文本段并输出它们的文本和位置信息。
foreach (TextSegment segment in absorber.TextFragments[1].Segments)
{
    Console.Out.WriteLine(string.Format("segment text: {0}", segment.Text));
    Console.Out.WriteLine(string.Format("segment X indent: {0}", segment.Position.XIndent));
    Console.Out.WriteLine(string.Format("segment Y indent: {0}", segment.Position.YIndent));
}

```

### 另请参见

* class [TextFragmentAbsorber](../../textfragmentabsorber/)
* class [Document](../../../aspose.pdf/document/)
* class [TextSegment](../../textsegment/)
* class [TextSegmentCollection](../../textsegmentcollection/)
* class [TextFragment](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


