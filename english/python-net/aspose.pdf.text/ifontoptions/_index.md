---
title: IFontOptions
second_title: Aspose.PDF for Python via .NET API Reference
description: Useful properties to tune Font behaviour
type: docs
weight: 180
url: /python-net/aspose.pdf.text/ifontoptions/
---

## IFontOptions class

Useful properties to tune Font behaviour

The IFontOptions type exposes the following members:
## Properties
| Name | Description |
| :- | :- |
|notify_about_font_embedding_error|Sometimes it's not possible to embed desired font into document. There are many reasons, for example<br/>            license restrictions or when desired font was not found on destination computer.<br/>            When this situation comes it's not simply to detect, because desired font is embedded via set <br/>            of property flag Font.IsEmbedded = true; Of course it's possible to read this property immediately after it was set but<br/>            it's not convenient approach. Flag NotifyAboutFontEmbeddingError enforces exception mechanism <br/>            for cases when attempt to embed font became failed. If this flag is set an exception of type<br/>            [FontEmbeddingException](/pdf/python-net/aspose.pdf/fontembeddingexception/) will be thrown. By default false.|

### See Also

* namespace [aspose.pdf.text](/pdf/python-net/aspose.pdf.text/)
* assembly [Aspose.PDF](/pdf/python-net/)

