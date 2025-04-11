---
title: IFontOptions.NotifyAboutFontEmbeddingError
second_title: Aspose.PDF for .NET API Reference
description: IFontOptions 属性。有时无法将所需字体嵌入文档中。原因有很多，例如许可证限制或在目标计算机上未找到所需字体。当这种情况发生时，检测并不简单，因为所需字体是通过属性标志 Font.IsEmbedded = true 嵌入的；当然，可以在设置此属性后立即读取它，但这并不是一个方便的方法。标志 NotifyAboutFontEmbeddingError 强制在尝试嵌入字体失败时使用异常机制。如果设置了此标志，将抛出类型为 [`FontEmbeddingException`](../../../aspose.pdf/fontembeddingexception/) 的异常。默认值为 false。
type: docs
weight: 10
url: /zh/net/aspose.pdf.text/ifontoptions/notifyaboutfontembeddingerror/
---
## IFontOptions.NotifyAboutFontEmbeddingError 属性

有时无法将所需字体嵌入文档中。原因有很多，例如许可证限制或在目标计算机上未找到所需字体。当这种情况发生时，检测并不简单，因为所需字体是通过属性标志 Font.IsEmbedded = true 嵌入的；当然，可以在设置此属性后立即读取它，但这并不是一个方便的方法。标志 NotifyAboutFontEmbeddingError 强制在尝试嵌入字体失败时使用异常机制。如果设置了此标志，将抛出类型为 [`FontEmbeddingException`](../../../aspose.pdf/fontembeddingexception/) 的异常。默认值为 false。

```csharp
public bool NotifyAboutFontEmbeddingError { get; set; }
```

### 另请参阅

* 接口 [IFontOptions](../)
* 命名空间 [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* 程序集 [Aspose.PDF](../../../)