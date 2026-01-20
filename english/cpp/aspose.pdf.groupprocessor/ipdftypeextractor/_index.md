---
title: Aspose::Pdf::GroupProcessor::IPdfTypeExtractor class
linktitle: IPdfTypeExtractor
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::GroupProcessor::IPdfTypeExtractor class. Represents interface to interacting with extractor in C++.'
type: docs
weight: 400
url: /cpp/aspose.pdf.groupprocessor/ipdftypeextractor/
---
## IPdfTypeExtractor class


Represents interface to interacting with extractor.

```cpp
class IPdfTypeExtractor : public Aspose::Pdf::GroupProcessor::IDocumentTextExtractor,
                          public Aspose::Pdf::GroupProcessor::IDocumentPageTextExtractor,
                          public System::IDisposable
```

## Methods

| Method | Description |
| --- | --- |
| virtual [Dispose](./dispose/)() | Dispose. |
| virtual [ExtractAllText](./extractalltext/)() | Returns collection of extracted text values. |
| virtual [ExtractPageText](./extractpagetext/)(int32_t) | Returns page text. |
| virtual [get_IsFastExtractionUsed](./get_isfastextractionused/)() | Returns if fast extraction mechanism used. |
| virtual [get_PageCount](./get_pagecount/)() | Returns page count. |
| virtual [get_Version](./get_version/)() | Returns version. |
## See Also

* Class [IDocumentTextExtractor](../idocumenttextextractor/)
* Class [IDocumentPageTextExtractor](../idocumentpagetextextractor/)
* Class [IDisposable](../../system/idisposable/)
* Namespace [Aspose::Pdf::GroupProcessor](../)
* Library [Aspose.PDF for C++](../../)
