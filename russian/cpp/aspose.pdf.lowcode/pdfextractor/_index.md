---
title: "Класс Aspose::Pdf::LowCode::PdfExtractor"
linktitle: "PdfExtractor"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс Aspose::Pdf::LowCode::PdfExtractor. Представляет базовый функционал для извлечения текста, изображений и других типов содержимого, которые могут встречаться на страницах PDF‑документов на C++."
type: docs
weight: 5900
url: /ru/cpp/aspose.pdf.lowcode/pdfextractor/
---
## PdfExtractor class


Представляет базовую функциональность для извлечения текста, изображений и других типов содержимого, которые могут присутствовать на страницах PDF‑документов.

```cpp
class PdfExtractor : public Aspose::Pdf::LowCode::IPlugin,
                     public System::IDisposable
```

## Методы

| Метод | Описание |
| --- | --- |
| [Dispose](./dispose/)() override | Реализация IDisposable. На самом деле, это не требуется для [PdfExtractor](./). |
| [Process](./process/)(System::SharedPtr\<IPluginOptions\>) override | Запускает обработку [PdfExtractor](./) с указанными параметрами. |
## Примечания


Объект [TextExtractor](../textextractor/) используется для извлечения текста, а [ImageExtractor](../imageextractor/) — для извлечения изображений.
## См. также

* Class [IPlugin](../iplugin/)
* Class [IDisposable](../../system/idisposable/)
* Namespace [Aspose::Pdf::LowCode](../)
* Library [Aspose.PDF for C++](../../)
