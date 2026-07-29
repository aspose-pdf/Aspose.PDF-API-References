---
title: "TextFragmentAbsorber.TextFragments"
second_title: "Aspose.PDF for .NET API 参考"
description: "TextFragmentAbsorber 属性。获取搜索出现次数的集合，该集合由 TextFragment 对象表示"
type: docs
weight: 90
url: /zh/net/aspose.pdf.text/textfragmentabsorber/textfragments/
---
## TextFragmentAbsorber.TextFragments property

获取搜索出现次数的集合，该集合由 [`TextFragment`](../../textfragment/) 对象表示。

```csharp
public TextFragmentCollection TextFragments { get; set; }
```

## 示例

示例演示了如何在第一个 PDF 文档页面上查找文本并将所有搜索出现次数替换为新文本。

```csharp
// 打开文档
Document doc = new Document(@"D:\Tests\input.pdf");

// 查找用于更改文档文本字体的字体
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// 创建 TextFragmentAbsorber 对象以查找所有 "hello world" 文本出现
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// 接受第一页的吸收器
doc.Pages[1].Accept(absorber);

// 更改所有搜索匹配项的文本。
foreach (TextFragment textFragment in absorber.TextFragments)
{
    textFragment.Text = "hi world";
}

// 保存文档
doc.Save(@"D:\Tests\output.pdf");  
```

### 另请参见

* class [TextFragmentCollection](../../textfragmentcollection/)
* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


