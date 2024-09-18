---
title: Aspose::Pdf::Text::IFontOptions::set_NotifyAboutFontEmbeddingError method
linktitle: set_NotifyAboutFontEmbeddingError
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Text::IFontOptions::set_NotifyAboutFontEmbeddingError method. Sometimes it''s not possible to embed desired font into document. There are many reasons, for example license restrictions or when desired font was not found on destination computer. When this situation comes it''s not simply to detect, because desired font is embedded via set of property flag Font.IsEmbedded = true; Of course it''s possible to read this property immediately after it was set but it''s not convenient approach. Flag NotifyAboutFontEmbeddingError enforces exception mechanism for cases when attempt to embed font became failed. If this flag is set an exception of type Aspose::Pdf::FontEmbeddingException will be thrown. By default false in C++.'
type: docs
weight: 200
url: /cpp/aspose.pdf.text/ifontoptions/set_notifyaboutfontembeddingerror/
---
## IFontOptions::set_NotifyAboutFontEmbeddingError method


Sometimes it's not possible to embed desired font into document. There are many reasons, for example license restrictions or when desired font was not found on destination computer. When this situation comes it's not simply to detect, because desired font is embedded via set of property flag Font.IsEmbedded = true; Of course it's possible to read this property immediately after it was set but it's not convenient approach. Flag NotifyAboutFontEmbeddingError enforces exception mechanism for cases when attempt to embed font became failed. If this flag is set an exception of type [Aspose::Pdf::FontEmbeddingException](../../../aspose.pdf/fontembeddingexception/) will be thrown. By default false.

```cpp
virtual void Aspose::Pdf::Text::IFontOptions::set_NotifyAboutFontEmbeddingError(bool value)=0
```

## See Also

* Class [IFontOptions](../)
* Namespace [Aspose::Pdf::Text](../../)
* Library [Aspose.PDF for C++](../../../)
