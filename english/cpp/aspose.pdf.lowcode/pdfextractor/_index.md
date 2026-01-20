---
title: Aspose::Pdf::LowCode::PdfExtractor class
linktitle: PdfExtractor
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::LowCode::PdfExtractor class. Represents base functionality to extract text, images, and other types of content that may occur on the pages of PDF documents in C++.'
type: docs
weight: 5900
url: /cpp/aspose.pdf.lowcode/pdfextractor/
---
## PdfExtractor class


Represents base functionality to extract text, images, and other types of content that may occur on the pages of PDF documents.

```cpp
class PdfExtractor : public Aspose::Pdf::LowCode::IPlugin,
                     public System::IDisposable
```

## Methods

| Method | Description |
| --- | --- |
| [Dispose](./dispose/)() override | Implementation of IDisposable. Actually, it is not necessary for [PdfExtractor](./). |
| [Process](./process/)(System::SharedPtr\<IPluginOptions\>) override | Starts [PdfExtractor](./) processing with the specified parameters. |
## Remarks


The [TextExtractor](../textextractor/) object is used to extract text, or [ImageExtractor](../imageextractor/) to extract images. 
## See Also

* Class [IPlugin](../iplugin/)
* Class [IDisposable](../../system/idisposable/)
* Namespace [Aspose::Pdf::LowCode](../)
* Library [Aspose.PDF for C++](../../)
