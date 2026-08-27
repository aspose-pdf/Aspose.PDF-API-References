---
title: "TextFragment.Position"
second_title: "Aspose.PDF for .NET API 参考"
description: "TextFragment 属性。获取或设置由 TextFragment 对象表示的文本位置。"
type: docs
weight: 90
url: /zh/net/aspose.pdf.text/textfragment/position/
---
## TextFragment.Position property

获取或设置由 [`TextFragment`](../) 对象表示的文本位置。

```csharp
public Position Position { get; set; }
```

## 示例

示例演示如何查看由 [`TextFragment`](../) 对象表示的文本的放置位置。

```csharp
// 打开文档
Document doc = new Document(@"D:\Tests\input.pdf");

// 创建 TextFragmentAbsorber 对象以查找所有 "hello world" 文本出现
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// 接受第一页的吸收器
doc.Pages[1].Accept(absorber);

// 查看首次出现的文本及其位置信息。
TextFragment firstOccurrence = absorber.TextFragments[1];

Console.Out.WriteLine(string.Format("fragment text: {0}", firstOccurrence.Text));
Console.Out.WriteLine(string.Format("fragment X indent: {0}", firstOccurrence.Position.XIndent));
Console.Out.WriteLine(string.Format("fragment Y indent: {0}", firstOccurrence.Position.YIndent));

```

### 另请参见

* class [TextFragmentAbsorber](../../textfragmentabsorber/)
* class [Document](../../../aspose.pdf/document/)
* class [TextSegment](../../textsegment/)
* class [Position](../../position/)
* class [TextFragment](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


