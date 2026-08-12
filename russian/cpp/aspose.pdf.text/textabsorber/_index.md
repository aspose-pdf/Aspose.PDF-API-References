---
title: "Aspose::Pdf::Text::TextAbsorber class"
linktitle: "TextAbsorber"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Text::TextAbsorber класс. Представляет объект‑поглотитель текста. Выполняет извлечение текста и предоставляет доступ к результату через объект TextAbsorber::Text в C++."
type: docs
weight: 3600
url: /ru/cpp/aspose.pdf.text/textabsorber/
---
## TextAbsorber class


Представляет объект‑поглотитель текста. Выполняет извлечение текста и предоставляет доступ к результату через объект [TextAbsorber::Text](../).

```cpp
class TextAbsorber : public System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| [get_Errors](./get_errors/)() const | Список объектов [TextExtractionError](../textextractionerror/). Содержит информацию об ошибках, найденных во время извлечения текста. Поиск ошибок будет выполнен только если TextSearchOptions.LogTextExtractionErrors = true; и это может снизить производительность. |
| virtual [get_ExtractionOptions](./get_extractionoptions/)() | Получает параметры извлечения текста. |
| [get_HasErrors](./get_haserrors/)() const | Значение указывает, были ли обнаружены ошибки во время извлечения текста. Поиск ошибок будет выполнен только если TextSearchOptions.LogTextExtractionErrors = true; и это может снизить производительность. |
| virtual [get_Text](./get_text/)() | Получает извлечённый текст, который [TextAbsorber](./) извлекает из PDF‑документа или страницы. |
| virtual [get_TextSearchOptions](./get_textsearchoptions/)() | Получает параметры поиска текста. |
| virtual [set_ExtractionOptions](./set_extractionoptions/)(System::SharedPtr\<TextExtractionOptions\>) | Устанавливает параметры извлечения текста. |
| virtual [set_TextSearchOptions](./set_textsearchoptions/)(System::SharedPtr\<Aspose::Pdf::Text::TextSearchOptions\>) | Устанавливает параметры поиска текста. |
| [TextAbsorber](./textabsorber/)() | Инициализирует новый экземпляр [TextAbsorber](./). |
| [TextAbsorber](./textabsorber/)(const System::SharedPtr\<TextExtractionOptions\>\&) | Инициализирует новый экземпляр [TextAbsorber](./) с параметрами извлечения. |
| [TextAbsorber](./textabsorber/)(const System::SharedPtr\<TextExtractionOptions\>\&, const System::SharedPtr\<Aspose::Pdf::Text::TextSearchOptions\>\&) | Инициализирует новый экземпляр [TextAbsorber](./) с параметрами извлечения и поиска текста. |
| [TextAbsorber](./textabsorber/)(const System::SharedPtr\<Aspose::Pdf::Text::TextSearchOptions\>\&) | Инициализирует новый экземпляр [TextAbsorber](./) с параметрами поиска текста. |
| virtual [Visit](./visit/)(System::SharedPtr\<Page\>) | Извлекает текст на указанной странице. |
| virtual [Visit](./visit/)(System::SharedPtr\<XForm\>) | Извлекает текст в указанном [XForm](../../aspose.pdf/xform/). |
| virtual [Visit](./visit/)(System::SharedPtr\<Document\>) | Извлекает текст в указанном документе. |
## Примечания


Объект [TextAbsorber](./) используется для извлечения текста из документа [Pdf](../../aspose.pdf/) или его страницы.
## См. также

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf::Text](../)
* Library [Aspose.PDF for C++](../../)
