---
title: "TextAbsorber.Text"
second_title: "Aspose.PDF for .NET API 参考"
description: "TextAbsorber 属性。获取 TextAbsorber 在 PDF Document 或 Page 上提取的文本。"
type: docs
weight: 50
url: /zh/net/aspose.pdf.text/textabsorber/text/
---
## TextAbsorber.Text property

获取 [`TextAbsorber`](../) 在 PDF Document 或 Page 上提取的文本。

```csharp
public virtual string Text { get; }
```

## 示例

此示例演示如何从 PDF Document 的所有 Page 提取文本。

```csharp
// 打开文档
Document doc = new Document(inFile);

// 创建 TextAbsorber 对象以提取文本
TextAbsorber absorber = new TextAbsorber();

// 接受所有文档页面的吸收器
doc.Pages.Accept(absorber);

// 获取提取的文本
string extractedText = absorber.Text;

```

### 另请参见

* class [TextAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


