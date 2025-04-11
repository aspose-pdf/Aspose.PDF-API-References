---
title: TextFragment.TextState
second_title: Aspose.PDF for .NET API Reference
description: TextFragment 属性。获取或设置 TextFragment 对象所表示文本的文本状态
type: docs
weight: 150
url: /zh/net/aspose.pdf.text/textfragment/textstate/
---
## TextFragment.TextState 属性

获取或设置 [`TextFragment`](../) 对象所表示文本的文本状态。

```csharp
public TextFragmentState TextState { get; }
```

## 备注

提供了一种更改文本以下属性的方法：字体 字体大小 字体样式 前景色 背景色

## 示例

该示例演示如何使用 `TextState` 对象更改文本的颜色和字体大小。

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// Change foreground color of the first text occurrence
absorber.TextFragments[1].TextState.ForegroundColor = Color.FromRgb(System.Drawing.Color.Red);

// Change font size of the first text occurrence
absorber.TextFragments[1].TextState.FontSize = 15;

// Save document
doc.Save(@"D:\Tests\output.pdf");  
```

### 另请参阅

* 类 [TextFragmentAbsorber](../../textfragmentabsorber/)
* 类 [Document](../../../aspose.pdf/document/)
* 类 [TextFragmentState](../../textfragmentstate/)
* 类 [TextFragment](../)
* 命名空间 [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* 程序集 [Aspose.PDF](../../../)