---
title: "IFontOptions.NotifyAboutFontEmbeddingError"
second_title: "Aspose.PDF for .NET API 参考"
description: "IFontOptions 属性。有时无法将所需字体嵌入文档。原因很多，例如许可证限制或在目标计算机上未找到所需字体。当出现这种情况时，由于所需字体是通过属性标志 Font.IsEmbedded = true 嵌入的，检测并不容易。当然可以在设置后立即读取此属性，但这并不方便。标志 NotifyAboutFontEmbeddingError 为此类嵌入字体失败的情况强制使用异常机制。如果设置了此标志，将抛出类型为 FontEmbeddingException 的异常。默认值为 false"
type: docs
weight: 10
url: /zh/net/aspose.pdf.text/ifontoptions/notifyaboutfontembeddingerror/
---
## IFontOptions.NotifyAboutFontEmbeddingError property

有时无法将所需字体嵌入文档。原因很多，例如许可证限制或在目标计算机上未找到所需字体。当出现这种情况时，由于所需字体是通过属性标志 Font.IsEmbedded = true 嵌入的，检测并不容易。当然可以在设置后立即读取此属性，但这并不方便。标志 NotifyAboutFontEmbeddingError 为嵌入字体失败的情况强制使用异常机制。如果设置了此标志，将抛出类型为 [`FontEmbeddingException`](../../../aspose.pdf/fontembeddingexception/) 的异常。默认值为 false。

```csharp
public bool NotifyAboutFontEmbeddingError { get; set; }
```

### 另请参见

* interface [IFontOptions](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


