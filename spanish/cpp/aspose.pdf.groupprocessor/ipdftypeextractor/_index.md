---
title: "Aspose::Pdf::GroupProcessor::IPdfTypeExtractor clase"
linktitle: "IPdfTypeExtractor"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::GroupProcessor::IPdfTypeExtractor clase. Representa una interfaz para interactuar con el extractor en C++."
type: docs
weight: 400
url: /es/cpp/aspose.pdf.groupprocessor/ipdftypeextractor/
---
## IPdfTypeExtractor class


Representa la interfaz para interactuar con el extractor.

```cpp
class IPdfTypeExtractor : public Aspose::Pdf::GroupProcessor::IDocumentTextExtractor,
                          public Aspose::Pdf::GroupProcessor::IDocumentPageTextExtractor,
                          public System::IDisposable
```

## Métodos

| Método | Descripción |
| --- | --- |
| virtual [Dispose](./dispose/)() | Liberar. |
| virtual [ExtractAllText](./extractalltext/)() | Devuelve una colección de valores de texto extraídos. |
| virtual [ExtractPageText](./extractpagetext/)(int32_t) | Devuelve el texto de la página. |
| virtual [get_IsFastExtractionUsed](./get_isfastextractionused/)() | Devuelve si se utilizó el mecanismo de extracción rápida. |
| virtual [get_PageCount](./get_pagecount/)() | Devuelve el recuento de páginas. |
| virtual [get_Version](./get_version/)() | Devuelve la versión. |
## Ver también

* Class [IDocumentTextExtractor](../idocumenttextextractor/)
* Class [IDocumentPageTextExtractor](../idocumentpagetextextractor/)
* Class [IDisposable](../../system/idisposable/)
* Namespace [Aspose::Pdf::GroupProcessor](../)
* Library [Aspose.PDF for C++](../../)
