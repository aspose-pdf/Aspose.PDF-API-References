---
title: "Font.FontName"
second_title: "Aspose.PDF for .NET API 参考"
description: "Font 属性。获取 Font 对象的字体名称。"
type: docs
weight: 30
url: /zh/net/aspose.pdf.text/font/fontname/
---
## Font.FontName property

获取 [`Font`](../) 对象的字体名称。

```csharp
public string FontName { get; }
```

## 示例

示例演示了如何在首页搜索文本并查看首次文本出现的字体名称。

```csharp
// 打开文档
Document doc = new Document(@"D:\Tests\input.pdf");

// 创建 TextFragmentAbsorber 对象以查找所有 "hello world" 文本出现
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// 接受第一页的吸收器
doc.Pages[1].Accept(absorber);

// 查看首次文本出现的字体名称
Console.Out.WriteLine(absorber.TextFragments[1].TextState.Font.FontName); 
```

### 另请参见

* class [TextFragmentAbsorber](../../textfragmentabsorber/)
* class [Document](../../../aspose.pdf/document/)
* class [Font](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


