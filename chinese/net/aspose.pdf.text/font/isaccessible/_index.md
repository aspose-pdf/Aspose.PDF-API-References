---
title: IsAccessible
second_title: Aspose.PDF for .NET API 参考
description: 获取系统中是否存在安装字体
type: docs
weight: 50
url: /zh/net/aspose.pdf.text/font/isaccessible/
---
## Font.IsAccessible property

获取系统中是否存在（安装）字体。

```csharp
public bool IsAccessible { get; }
```

### 评论

某些操作不适用于系统中找不到的字体。

### 例子

该示例演示如何在第一页搜索文本并获取指示系统中是否安装字体的值。

```csharp
// 打开文档
Document doc = new Document(@"D:\Tests\input.pdf");

// 创建 TextFragmentAbsorber 对象以查找所有“hello world”文本出现
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// 接受第一页的吸收器
doc.Pages[1].Accept(absorber);

// 查看第一个文本出现的字体的 IsSubset 值
if(absorber.TextFragments[1].TextState.Font.IsAccessible)
   Console.Out.WriteLine("the font is installed in the system");
```

### 也可以看看

* class [TextFragmentAbsorber](../../textfragmentabsorber)
* class [Document](../../../aspose.pdf/document)
* class [Font](../../font)
* 命名空间 [Aspose.Pdf.Text](../../font)
* 部件 [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->