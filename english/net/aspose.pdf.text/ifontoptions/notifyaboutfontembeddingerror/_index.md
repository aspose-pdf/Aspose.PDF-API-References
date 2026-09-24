---
title: "IFontOptions.NotifyAboutFontEmbeddingError"
linktitle: "NotifyAboutFontEmbeddingError"
articleTitle: "NotifyAboutFontEmbeddingError"
second_title: "Aspose.PDF for .NET"
description: "Sometimes it's not possible to embed desired font into document. There are many reasons, for example license restrictions or when desired font was not found ..."
type: docs
weight: 10
url: "/net/aspose.pdf.text/ifontoptions/notifyaboutfontembeddingerror/"
product_version: "26.9.0"
---
## IFontOptions.NotifyAboutFontEmbeddingError property

Sometimes it's not possible to embed desired font into document. There are many reasons, for example
 license restrictions or when desired font was not found on destination computer.
 When this situation comes it's not simply to detect, because desired font is embedded via set 
 of property flag Font.IsEmbedded = true; Of course it's possible to read this property immediately after it was set but
 it's not convenient approach. Flag NotifyAboutFontEmbeddingError enforces exception mechanism 
 for cases when attempt to embed font became failed. If this flag is set an exception of type
 [`FontEmbeddingException`](../../../aspose.pdf/fontembeddingexception/) will be thrown. By default false.

```csharp
public bool NotifyAboutFontEmbeddingError { get; set; }
```

### Property Value

bool

### See Also

* interface [IFontOptions](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

