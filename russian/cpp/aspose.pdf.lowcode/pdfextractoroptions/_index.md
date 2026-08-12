---
title: "Aspose::Pdf::LowCode::PdfExtractorOptions class"
linktitle: "PdfExtractorOptions"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::LowCode::PdfExtractorOptions class. Представляет параметры для плагинов TextExtractor и ImageExtractor на C++."
type: docs
weight: 6000
url: /ru/cpp/aspose.pdf.lowcode/pdfextractoroptions/
---
## PdfExtractorOptions class


Представляет параметры для плагинов [TextExtractor](../textextractor/) и [ImageExtractor](../imageextractor/).

```cpp
class PdfExtractorOptions : public Aspose::Pdf::LowCode::IPluginOptions,
                            public Aspose::Pdf::LowCode::IDataContainer
```

## Методы

| Метод | Описание |
| --- | --- |
| [AddInput](./addinput/)(System::SharedPtr\<IDataSource\>) override | Добавляет новый источник данных в коллекцию данных плагина [PdfExtractor](../pdfextractor/). |
| [get_Inputs](./get_inputs/)() override | Возвращает коллекцию данных плагина [PdfExtractor](../pdfextractor/). |
| virtual [get_OperationName](./get_operationname/)() | Возвращает имя операции. |
## Примечания


Класс [PdfExtractorOptions](./) содержит базовые функции для добавления данных (файлов, потоков), представляющих входные PDF‑документы. Пожалуйста, создайте [TextExtractorOptions](../textextractoroptions/) или [ImageExtractorOptions](../imageextractoroptions/) вместо этого.
## См. также

* Class [IPluginOptions](../ipluginoptions/)
* Class [IDataContainer](../idatacontainer/)
* Namespace [Aspose::Pdf::LowCode](../)
* Library [Aspose.PDF for C++](../../)
