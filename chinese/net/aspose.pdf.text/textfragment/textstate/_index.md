---
title: "TextFragment.TextState"
second_title: "Aspose.PDF for .NET API 参考"
description: "TextFragment 属性。获取或设置 TextFragment 对象所表示文本的文本状态。"
type: docs
weight: 150
url: /zh/net/aspose.pdf.text/textfragment/textstate/
---
## TextFragment.TextState property

获取或设置 [`TextFragment`](../) 对象所表示文本的文本状态。

```csharp
public TextFragmentState TextState { get; }
```

## 备注

提供一种更改文本以下属性的方法：Font FontSize FontStyle ForegroundColor BackgroundColor

## 示例

示例演示如何使用 `TextState` 对象更改文本的颜色和字体大小。

```csharp
// 打开文档
Document doc = new Document(@"D:\Tests\input.pdf");

// 创建 TextFragmentAbsorber 对象以查找所有 "hello world" 文本出现
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// 接受第一页的吸收器
doc.Pages[1].Accept(absorber);

// 更改首次出现的文本的前景颜色
absorber.TextFragments[1].TextState.ForegroundColor = Color.FromRgb(System.Drawing.Color.Red);

// 更改首次文本出现的字体大小
absorber.TextFragments[1].TextState.FontSize = 15;

// 保存文档
doc.Save(@"D:\Tests\output.pdf");  
```

### 另请参见

* class [TextFragmentAbsorber](../../textfragmentabsorber/)
* class [Document](../../../aspose.pdf/document/)
* class [TextFragmentState](../../textfragmentstate/)
* class [TextFragment](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


