---
title: "Font.IsSubset"
second_title: "Aspose.PDF for .NET API 参考"
description: "Font 属性。获取或设置指示字体是否为子集的值。基于 IFont 的字体将自动进行子集化并嵌入"
type: docs
weight: 70
url: /zh/net/aspose.pdf.text/font/issubset/
---
## Font.IsSubset property

获取或设置指示字体是否为子集的值。基于 IFont 的字体将自动进行子集化并嵌入。

```csharp
public bool IsSubset { get; set; }
```

## 示例

示例演示如何在首页搜索文本并获取指示字体是否为子集的值。

```csharp
// 打开文档
Document doc = new Document(@"D:\Tests\input.pdf");

// 创建 TextFragmentAbsorber 对象以查找所有 "hello world" 文本出现
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// 接受第一页的吸收器
doc.Pages[1].Accept(absorber);

// 查看首次文本出现的字体 IsSubset 值
if(absorber.TextFragments[1].TextState.Font.IsSubset)
   Console.Out.WriteLine("the font is a subset");
```

### 另请参见

* class [TextFragmentAbsorber](../../textfragmentabsorber/)
* class [Document](../../../aspose.pdf/document/)
* class [Font](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


