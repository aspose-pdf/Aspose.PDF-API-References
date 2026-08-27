---
title: "TextBuilder.AppendParagraph"
second_title: "Aspose.PDF for .NET API 参考"
description: "TextBuilder 方法。将文本段落追加到 Pdf 页面。"
type: docs
weight: 20
url: /zh/net/aspose.pdf.text/textbuilder/appendparagraph/
---
## TextBuilder.AppendParagraph method

将文本段落追加到 Pdf 页面。

```csharp
public void AppendParagraph(TextParagraph textParagraph)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| textParagraph | TextParagraph | 文本段落对象。 |

## 示例

此示例演示如何创建文本段落对象并将其追加到 Pdf 页面。

```csharp
Document doc = new Document(inFile);

Page page = (Page)doc.Pages[1];

// 创建文本段落
TextParagraph paragraph = new TextParagraph();
           
// 设置段落矩形
paragraph.Rectangle = new Rectangle(100, 600, 200, 700);

// 设置自动换行选项
paragraph.FormattingOptions.WrapMode = TextFormattingOptions.WordWrapMode.ByWords;

// 追加字符串行
paragraph.AppendLine("the quick brown fox jumps over the lazy dog");
paragraph.AppendLine("line2");
paragraph.AppendLine("line3");

// 使用 TextBuilder 将段落追加到 Pdf 页面
TextBuilder textBuilder = new TextBuilder(page);
textBuilder.AppendParagraph(paragraph);

// 保存 Pdf 文档
doc.Save(outFile);
```

### 另请参见

* class [TextParagraph](../../textparagraph/)
* class [TextBuilder](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


