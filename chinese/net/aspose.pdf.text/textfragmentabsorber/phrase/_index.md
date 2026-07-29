---
title: "TextFragmentAbsorber.Phrase"
second_title: "Aspose.PDF for .NET API 参考"
description: "TextFragmentAbsorber 属性。获取或设置 TextFragmentAbsorber 在 PDF 文档或页面上搜索的短语。"
type: docs
weight: 50
url: /zh/net/aspose.pdf.text/textfragmentabsorber/phrase/
---
## TextFragmentAbsorber.Phrase property

获取或设置 [`TextFragmentAbsorber`](../) 在 PDF 文档或页面上搜索的短语。

```csharp
public string Phrase { get; set; }
```

## 示例

示例演示了如何多次执行文本搜索并进行文本替换。

```csharp
// 打开文档
Document doc = new Document(@"D:\Tests\input.pdf");

// 创建 TextFragmentAbsorber 对象以查找所有 \"hello\" 文本出现。
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello");

doc.Pages[1].Accept(absorber);
absorber.TextFragments[1].Text = "Hi";

// 搜索另一个词并替换它。
absorber.Phrase = "world";

doc.Pages[1].Accept(absorber);
absorber.TextFragments[1].Text = "John";

// 保存文档
doc.Save(@"D:\Tests\output.pdf");  
```

### 另请参见

* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


