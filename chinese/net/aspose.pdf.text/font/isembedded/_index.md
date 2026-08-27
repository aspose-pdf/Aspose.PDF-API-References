---
title: "Font.IsEmbedded"
second_title: "Aspose.PDF for .NET API 参考"
description: "Font 属性。获取或设置指示字体是否已嵌入的值。基于 IFont 的字体将自动进行子集化并嵌入"
type: docs
weight: 60
url: /zh/net/aspose.pdf.text/font/isembedded/
---
## Font.IsEmbedded property

获取或设置指示字体是否已嵌入的值。基于 IFont 的字体将自动进行子集化并嵌入。

```csharp
public bool IsEmbedded { get; set; }
```

## 示例

以下示例演示如何查找字体、将其标记为嵌入、在文档页面上搜索文本并替换文本字体。

```csharp
// 创建字体并标记为嵌入
Font font = FontRepository.FindFont("Arial");
font.IsEmbedded = true;

// 打开文档
Document doc = new Document(@"D:\Tests\input.pdf");

// 创建 TextFragmentAbsorber 对象以查找所有 "hello world" 文本出现
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");
// 为第一页接受吸收器
doc.Pages[1].Accept(absorber);

// 更改首次文本出现的字体
absorber.TextFragments[1].TextState.Font = font;

// 保存文档
doc.Save(@"D:\Tests\output.pdf"); 
```

### 另请参见

* class [TextFragmentAbsorber](../../textfragmentabsorber/)
* class [FontRepository](../../fontrepository/)
* class [Document](../../../aspose.pdf/document/)
* class [Font](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


