---
title: "Aspose::Pdf::GroupProcessor::IPdfTypeExtractor class"
linktitle: "IPdfTypeExtractor"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::GroupProcessor::IPdfTypeExtractor class. Представляет интерфейс для взаимодействия с извлекателем в C++."
type: docs
weight: 400
url: /ru/cpp/aspose.pdf.groupprocessor/ipdftypeextractor/
---
## IPdfTypeExtractor class


Представляет интерфейс для взаимодействия с извлекателем.

```cpp
class IPdfTypeExtractor : public Aspose::Pdf::GroupProcessor::IDocumentTextExtractor,
                          public Aspose::Pdf::GroupProcessor::IDocumentPageTextExtractor,
                          public System::IDisposable
```

## Методы

| Метод | Описание |
| --- | --- |
| virtual [Dispose](./dispose/)() | Освободить. |
| virtual [ExtractAllText](./extractalltext/)() | Возвращает коллекцию извлечённых текстовых значений. |
| virtual [ExtractPageText](./extractpagetext/)(int32_t) | Возвращает текст страницы. |
| virtual [get_IsFastExtractionUsed](./get_isfastextractionused/)() | Возвращает, используется ли быстрый механизм извлечения. |
| virtual [get_PageCount](./get_pagecount/)() | Возвращает количество страниц. |
| virtual [get_Version](./get_version/)() | Возвращает версию. |
## См. также

* Class [IDocumentTextExtractor](../idocumenttextextractor/)
* Class [IDocumentPageTextExtractor](../idocumentpagetextextractor/)
* Class [IDisposable](../../system/idisposable/)
* Namespace [Aspose::Pdf::GroupProcessor](../)
* Library [Aspose.PDF for C++](../../)
