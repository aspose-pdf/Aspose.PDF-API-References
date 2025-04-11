---
title: Font.IsAccessible
second_title: Aspose.PDF for .NET API Reference
description: 字体属性。获取指示字体是否已安装在系统中的信息
type: docs
weight: 50
url: /zh/net/aspose.pdf.text/font/isaccessible/
---
## Font.IsAccessible 属性

获取指示字体是否存在（已安装）在系统中的信息。

```csharp
public bool IsAccessible { get; }
```

## 备注

某些操作在找不到的字体上不可用。

## 示例

该示例演示如何在第一页上搜索文本并获取指示字体是否已安装在系统中的值。

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// View font's IsSubset value of first text occurrence
if(absorber.TextFragments[1].TextState.Font.IsAccessible)
   Console.Out.WriteLine("the font is installed in the system");
```

### 另请参阅

* 类 [TextFragmentAbsorber](../../textfragmentabsorber/)
* 类 [Document](../../../aspose.pdf/document/)
* 类 [Font](../)
* 命名空间 [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* 程序集 [Aspose.PDF](../../../)