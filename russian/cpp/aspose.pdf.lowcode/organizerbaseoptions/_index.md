---
title: "Класс Aspose::Pdf::LowCode::OrganizerBaseOptions"
linktitle: "OrganizerBaseOptions"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс Aspose::Pdf::LowCode::OrganizerBaseOptions. Представляет базовые параметры для плагинов на C++."
type: docs
weight: 5200
url: /ru/cpp/aspose.pdf.lowcode/organizerbaseoptions/
---
## OrganizerBaseOptions class


Представляет базовые параметры для плагинов.

```cpp
class OrganizerBaseOptions : public Aspose::Pdf::LowCode::IPluginOptions,
                             public Aspose::Pdf::LowCode::IDataContainer,
                             public Aspose::Pdf::LowCode::ISaveInstruction
```

## Методы

| Метод | Описание |
| --- | --- |
| [AddInput](./addinput/)(System::SharedPtr\<IDataSource\>) override | Добавляет новый источник данных в коллекцию данных плагина PdfOrganizer. |
| [AddOutput](./addoutput/)(System::SharedPtr\<IDataSource\>) override | Добавляет новый источник данных в коллекцию данных плагина PdfOrganizer. |
| [get_CloseInputStreams](./get_closeinputstreams/)() const | Закрывать входные потоки после завершения операции. |
| [get_CloseOutputStreams](./get_closeoutputstreams/)() const | Закрывать выходные потоки после завершения операции. |
| [get_Inputs](./get_inputs/)() override | Возвращает коллекцию данных плагина OrganizerOptions. |
| [get_Outputs](./get_outputs/)() override | Получает коллекцию добавленных целей для сохранения результатов операции. |
| [set_CloseInputStreams](./set_closeinputstreams/)(bool) | Закрывать входные потоки после завершения операции. |
| [set_CloseOutputStreams](./set_closeoutputstreams/)(bool) | Закрывать выходные потоки после завершения операции. |
## См. также

* Class [IPluginOptions](../ipluginoptions/)
* Class [IDataContainer](../idatacontainer/)
* Class [ISaveInstruction](../isaveinstruction/)
* Namespace [Aspose::Pdf::LowCode](../)
* Library [Aspose.PDF for C++](../../)
