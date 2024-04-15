---
title: Interface IFontOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Text.IFontOptions interface. Useful properties to tune Font behaviour
type: docs
weight: 8200
url: /net/aspose.pdf.text/ifontoptions/
---
## IFontOptions interface

Useful properties to tune Font behaviour

```csharp
public interface IFontOptions
```

## Properties

| Name | Description |
| --- | --- |
| [NotifyAboutFontEmbeddingError](../../aspose.pdf.text/ifontoptions/notifyaboutfontembeddingerror/) { get; set; } | Sometimes it's not possible to embed desired font into document. There are many reasons, for example license restrictions or when desired font was not found on destination computer. When this situation comes it's not simply to detect, because desired font is embedded via set of property flag Font.IsEmbedded = true; Of course it's possible to read this property immediately after it was set but it's not convenient approach. Flag NotifyAboutFontEmbeddingError enforces exception mechanism for cases when attempt to embed font became failed. If this flag is set an exception of type [`FontEmbeddingException`](../../aspose.pdf/fontembeddingexception/) will be thrown. By default false. |

### See Also

* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


