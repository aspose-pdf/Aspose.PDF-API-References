---
title: "TextFragment.Text"
second_title: "Aspose.PDF for .NET API 参考"
description: "TextFragment 属性。获取或设置 TextFragment 对象表示的字符串文本对象。"
type: docs
weight: 130
url: /zh/net/aspose.pdf.text/textfragment/text/
---
## TextFragment.Text property

获取或设置 [`TextFragment`](../) 对象表示的字符串文本对象。

```csharp
public string Text { get; set; }
```

## 示例

示例演示如何搜索文本并用 [`TextFragment`](../) 对象表示的首次出现进行替换。

```csharp
// 打开文档
Document doc = new Document(@"D:\Tests\input.pdf");

// 创建 TextFragmentAbsorber 对象以查找所有 "hello world" 文本出现
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// 接受第一页的吸收器
doc.Pages[1].Accept(absorber);

// 更改首次出现的文本的字体
absorber.TextFragments[1].Text = "hi world";

// 保存文档
doc.Save(@"D:\Tests\output.pdf"); 
```

### 另请参见

* class [TextFragmentAbsorber](../../textfragmentabsorber/)
* class [Document](../../../aspose.pdf/document/)
* class [TextFragment](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


