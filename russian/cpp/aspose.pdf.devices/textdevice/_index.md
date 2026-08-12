---
title: "Aspose::Pdf::Devices::TextDevice класс"
linktitle: "TextDevice"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Devices::TextDevice класс. Представляет класс для преобразования страниц PDF‑документа в текст в C++."
type: docs
weight: 1300
url: /ru/cpp/aspose.pdf.devices/textdevice/
---
## TextDevice class


Представляет класс для преобразования страниц PDF‑документа в текст.

```cpp
class TextDevice : public Aspose::Pdf::Devices::PageDevice
```

## Методы

| Метод | Описание |
| --- | --- |
| [get_Encoding](./get_encoding/)() const | Получает кодировку извлечённого текста. |
| [get_ExtractionOptions](./get_extractionoptions/)() const | Получает параметры извлечения текста. |
| [Process](./process/)(System::SharedPtr\<Page\>, System::SharedPtr\<System::IO::Stream\>) override | Преобразует страницу и сохраняет её как текстовый поток. |
| [set_Encoding](./set_encoding/)(const System::SharedPtr\<System::Text::Encoding\>\&) | Устанавливает кодировку извлечённого текста. |
| [set_ExtractionOptions](./set_extractionoptions/)(const System::SharedPtr\<Text::TextExtractionOptions\>\&) | Устанавливает параметры извлечения текста. |
| [TextDevice](./textdevice/)(const System::SharedPtr\<Text::TextExtractionOptions\>\&) | Инициализирует новый экземпляр [TextDevice](./) с параметрами извлечения текста. |
| [TextDevice](./textdevice/)() | Инициализирует новый экземпляр [TextDevice](./) с режимом форматирования Raw text и кодировкой Unicode. |
| [TextDevice](./textdevice/)(const System::SharedPtr\<System::Text::Encoding\>\&) | Инициализирует новый экземпляр [TextDevice](./) для указанной кодировки. |
| [TextDevice](./textdevice/)(const System::SharedPtr\<Text::TextExtractionOptions\>\&, const System::SharedPtr\<System::Text::Encoding\>\&) | Инициализирует новый экземпляр [TextDevice](./) для указанной кодировки с параметрами извлечения текста. |
## Примечания


Объект [TextDevice](./) в основном используется для извлечения текста со страницы pdf.
## См. также

* Class [PageDevice](../pagedevice/)
* Namespace [Aspose::Pdf::Devices](../)
* Library [Aspose.PDF for C++](../../)
