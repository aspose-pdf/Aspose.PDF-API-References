---
title: "Aspose::Pdf::LowCode::PdfConverterOptions class"
linktitle: "PdfConverterOptions"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс Aspose::Pdf::LowCode::PdfConverterOptions. Представляет параметры для плагинов конвертера Pdf на C++."
type: docs
weight: 5800
url: /ru/cpp/aspose.pdf.lowcode/pdfconverteroptions/
---
## PdfConverterOptions class


Представляет параметры для плагинов конвертера [Pdf](../../aspose.pdf/).

```cpp
class PdfConverterOptions : public Aspose::Pdf::LowCode::IPluginOptions,
                            public Aspose::Pdf::LowCode::IDataContainer,
                            public Aspose::Pdf::LowCode::ISaveInstruction
```

## Методы

| Метод | Описание |
| --- | --- |
| [AddInput](./addinput/)(System::SharedPtr\<IDataSource\>) override | Добавляет новый источник данных в коллекцию данных плагина PdfConverter. |
| [AddOutput](./addoutput/)(System::SharedPtr\<IDataSource\>) override | Добавляет новый источник данных в коллекцию данных плагина PdfToXLSXConverterOptions. |
| [get_Inputs](./get_inputs/)() override | Возвращает коллекцию данных плагина [PdfConverterOptions](./). |
| virtual [get_OperationName](./get_operationname/)() | Возвращает имя операции. |
| [get_Outputs](./get_outputs/)() override | Получает коллекцию добавленных целей для сохранения результатов операции. |
## См. также

* Class [IPluginOptions](../ipluginoptions/)
* Class [IDataContainer](../idatacontainer/)
* Class [ISaveInstruction](../isaveinstruction/)
* Namespace [Aspose::Pdf::LowCode](../)
* Library [Aspose.PDF for C++](../../)
