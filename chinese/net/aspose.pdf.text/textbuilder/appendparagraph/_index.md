---
title: TextBuilder.AppendParagraph
second_title: Aspose.PDF for .NET API Reference
description: TextBuilder 方法。将文本段落附加到 Pdf 页面
type: docs
weight: 20
url: /zh/net/aspose.pdf.text/textbuilder/appendparagraph/
---
## TextBuilder.AppendParagraph 方法

将文本段落附加到 Pdf 页面。

```csharp
public void AppendParagraph(TextParagraph textParagraph)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| textParagraph | TextParagraph | 文本段落对象。 |

## 示例

该示例演示如何创建文本段落对象并将其附加到 Pdf 页面。

```csharp
Document doc = new Document(inFile);

Page page = (Page)doc.Pages[1];

// create text paragraph
TextParagraph paragraph = new TextParagraph();
           
// set the paragraph rectangle
paragraph.Rectangle = new Rectangle(100, 600, 200, 700);

// set word wrapping options
paragraph.FormattingOptions.WrapMode = TextFormattingOptions.WordWrapMode.ByWords;

// append string lines
paragraph.AppendLine("the quick brown fox jumps over the lazy dog");
paragraph.AppendLine("line2");
paragraph.AppendLine("line3");

// append the paragraph to the Pdf page with the TextBuilder
TextBuilder textBuilder = new TextBuilder(page);
textBuilder.AppendParagraph(paragraph);

// save Pdf document
doc.Save(outFile);
```

### 另请参阅

* 类 [TextParagraph](../../textparagraph/)
* 类 [TextBuilder](../)
* 命名空间 [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* 程序集 [Aspose.PDF](../../../)