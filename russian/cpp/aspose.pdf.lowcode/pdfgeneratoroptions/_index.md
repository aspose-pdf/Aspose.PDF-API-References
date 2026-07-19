---
title: "Aspose::Pdf::LowCode::PdfGeneratorOptions class"
linktitle: "PdfGeneratorOptions"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::LowCode::PdfGeneratorOptions class. Представляет параметры для плагинов Generator в C++."
type: docs
weight: 6100
url: /ru/cpp/aspose.pdf.lowcode/pdfgeneratoroptions/
---
## PdfGeneratorOptions class


Представляет параметры для плагинов Generator.

```cpp
class PdfGeneratorOptions : public Aspose::Pdf::LowCode::IPluginOptions,
                            public Aspose::Pdf::LowCode::IDataContainer,
                            public Aspose::Pdf::LowCode::ISaveInstruction
```

## Методы

| Метод | Описание |
| --- | --- |
| [AddInput](./addinput/)(System::SharedPtr\<IDataSource\>) override | Добавляет новый источник данных в коллекцию данных плагина PdfGenerator. |
| [AddOutput](./addoutput/)(System::SharedPtr\<IDataSource\>) override | Добавляет новый источник данных в коллекцию данных плагина PdfGenerator. |
| [get_Inputs](./get_inputs/)() override | Возвращает коллекцию данных плагина PdfGenerator. |
| [get_Outputs](./get_outputs/)() override | Получает коллекцию добавленных целей для сохранения результатов операции. |
## См. также

* Class [IPluginOptions](../ipluginoptions/)
* Class [IDataContainer](../idatacontainer/)
* Class [ISaveInstruction](../isaveinstruction/)
* Namespace [Aspose::Pdf::LowCode](../)
* Library [Aspose.PDF for C++](../../)
