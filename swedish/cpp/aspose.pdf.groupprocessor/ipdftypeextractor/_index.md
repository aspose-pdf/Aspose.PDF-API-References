---
title: "Aspose::Pdf::GroupProcessor::IPdfTypeExtractor klass"
linktitle: "IPdfTypeExtractor"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::GroupProcessor::IPdfTypeExtractor klass. Representerar gränssnitt för interaktion med extraheraren i C++."
type: docs
weight: 400
url: /sv/cpp/aspose.pdf.groupprocessor/ipdftypeextractor/
---
## IPdfTypeExtractor class


Representerar ett gränssnitt för att interagera med extraheraren.

```cpp
class IPdfTypeExtractor : public Aspose::Pdf::GroupProcessor::IDocumentTextExtractor,
                          public Aspose::Pdf::GroupProcessor::IDocumentPageTextExtractor,
                          public System::IDisposable
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| virtual [Dispose](./dispose/)() | Frigör. |
| virtual [ExtractAllText](./extractalltext/)() | Returnerar samling av extraherade textvärden. |
| virtual [ExtractPageText](./extractpagetext/)(int32_t) | Returnerar sidtext. |
| virtual [get_IsFastExtractionUsed](./get_isfastextractionused/)() | Returnerar om snabb extraheringsmekanism används. |
| virtual [get_PageCount](./get_pagecount/)() | Returnerar sidantal. |
| virtual [get_Version](./get_version/)() | Returnerar version. |
## Se även

* Class [IDocumentTextExtractor](../idocumenttextextractor/)
* Class [IDocumentPageTextExtractor](../idocumentpagetextextractor/)
* Class [IDisposable](../../system/idisposable/)
* Namespace [Aspose::Pdf::GroupProcessor](../)
* Library [Aspose.PDF for C++](../../)
