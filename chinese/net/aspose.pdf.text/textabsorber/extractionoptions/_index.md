---
title: "TextAbsorber.ExtractionOptions"
second_title: "Aspose.PDF for .NET API 参考"
description: "TextAbsorber 属性。获取或设置文本提取选项。"
type: docs
weight: 30
url: /zh/net/aspose.pdf.text/textabsorber/extractionoptions/
---
## TextAbsorber.ExtractionOptions property

获取或设置文本提取选项。

```csharp
public virtual TextExtractionOptions ExtractionOptions { get; set; }
```

## 备注

允许在提取期间定义文本格式模式 [`TextExtractionOptions`](../../textextractionoptions/)。默认模式为 Pure。

## 示例

此示例演示如何设置 Pure 文本格式模式并执行文本提取。

```csharp
// 打开文档
Document doc = new Document(inFile);

// 创建 TextAbsorber 对象以使用格式提取文本。
TextAbsorber absorber = new TextAbsorber();

// 设置 Pure 文本格式模式。
absorber.ExtractionOptions = new TextExtractionOptions(TextExtractionOptions.TextFormattingMode.Pure);

// 接受所有文档页面的吸收器
doc.Pages.Accept(absorber);

// 获取提取的文本
string extractedText = absorber.Text;
```

### 另请参见

* class [TextExtractionOptions](../../textextractionoptions/)
* class [TextAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


