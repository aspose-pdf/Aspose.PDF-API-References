---
title: Interface IFontOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Text.IFontOptions 接口。用于调整字体行为的有用属性
type: docs
weight: 10610
url: /zh/net/aspose.pdf.text/ifontoptions/
---
## IFontOptions 接口

用于调整字体行为的有用属性

```csharp
public interface IFontOptions
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [NotifyAboutFontEmbeddingError](../../aspose.pdf.text/ifontoptions/notifyaboutfontembeddingerror/) { get; set; } | 有时无法将所需字体嵌入文档中。原因有很多，例如许可证限制或在目标计算机上找不到所需字体。当这种情况发生时，检测并不简单，因为所需字体是通过属性标志 Font.IsEmbedded = true; 嵌入的。当然，可以在设置后立即读取此属性，但这并不是一个方便的方法。标志 NotifyAboutFontEmbeddingError 强制在尝试嵌入字体失败时使用异常机制。如果设置了此标志，将抛出类型为 [`FontEmbeddingException`](../../aspose.pdf/fontembeddingexception/) 的异常。默认值为 false。 |

### 另请参阅

* 命名空间 [Aspose.Pdf.Text](../../aspose.pdf.text/)
* 程序集 [Aspose.PDF](../../)