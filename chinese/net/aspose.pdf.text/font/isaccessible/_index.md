---
title: "Font.IsAccessible"
second_title: "Aspose.PDF for .NET API 参考"
description: "Font 属性。获取指示系统中是否已安装该字体的状态"
type: docs
weight: 50
url: /zh/net/aspose.pdf.text/font/isaccessible/
---
## Font.IsAccessible property

获取指示字体是否已在系统中存在（已安装）的信息。

```csharp
public bool IsAccessible { get; }
```

## 备注

某些操作在系统中未找到的字体上不可用。

## 示例

示例演示如何在首页搜索文本并获取指示系统是否已安装该字体的值。

```csharp
// 打开文档
Document doc = new Document(@"D:\Tests\input.pdf");

// 创建 TextFragmentAbsorber 对象以查找所有 "hello world" 文本出现
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// 接受第一页的吸收器
doc.Pages[1].Accept(absorber);

// 查看首次文本出现的字体 IsSubset 值
if(absorber.TextFragments[1].TextState.Font.IsAccessible)
   Console.Out.WriteLine("the font is installed in the system");
```

### 另请参见

* class [TextFragmentAbsorber](../../textfragmentabsorber/)
* class [Document](../../../aspose.pdf/document/)
* class [Font](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


