---
title: Aspose::Pdf::Text::IFontOptions class
linktitle: IFontOptions
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Text::IFontOptions class. Useful properties to tune Font behaviour in C++.'
type: docs
weight: 1700
url: /cpp/aspose.pdf.text/ifontoptions/
---
## IFontOptions class


Useful properties to tune [Font](../font/) behaviour.

```cpp
class IFontOptions : public virtual System::Object
```

## Methods

| Method | Description |
| --- | --- |
| virtual [get_NotifyAboutFontEmbeddingError](./get_notifyaboutfontembeddingerror/)() | Sometimes it's not possible to embed desired font into document. There are many reasons, for example license restrictions or when desired font was not found on destination computer. When this situation comes it's not simply to detect, because desired font is embedded via set of property flag Font.IsEmbedded = true; Of course it's possible to read this property immediately after it was set but it's not convenient approach. Flag NotifyAboutFontEmbeddingError enforces exception mechanism for cases when attempt to embed font became failed. If this flag is set an exception of type [Aspose::Pdf::FontEmbeddingException](../../aspose.pdf/fontembeddingexception/) will be thrown. By default false. |
| virtual [set_NotifyAboutFontEmbeddingError](./set_notifyaboutfontembeddingerror/)(bool) | Sometimes it's not possible to embed desired font into document. There are many reasons, for example license restrictions or when desired font was not found on destination computer. When this situation comes it's not simply to detect, because desired font is embedded via set of property flag Font.IsEmbedded = true; Of course it's possible to read this property immediately after it was set but it's not convenient approach. Flag NotifyAboutFontEmbeddingError enforces exception mechanism for cases when attempt to embed font became failed. If this flag is set an exception of type [Aspose::Pdf::FontEmbeddingException](../../aspose.pdf/fontembeddingexception/) will be thrown. By default false. |
## See Also

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf::Text](../)
* Library [Aspose.PDF for C++](../../)
