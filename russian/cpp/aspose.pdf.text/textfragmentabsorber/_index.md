---
title: "класс Aspose::Pdf::Text::TextFragmentAbsorber"
linktitle: "TextFragmentAbsorber"
second_title: "Справочник API Aspose.PDF для C++"
description: "класс Aspose::Pdf::Text::TextFragmentAbsorber. Представляет объект‑поглотитель текстовых фрагментов. Выполняет поиск текста и предоставляет доступ к результатам поиска через коллекцию TextFragmentAbsorber::TextFragments в C++."
type: docs
weight: 4400
url: /ru/cpp/aspose.pdf.text/textfragmentabsorber/
---
## TextFragmentAbsorber class


Представляет объект‑поглотитель фрагментов текста. Выполняет поиск текста и предоставляет доступ к результатам поиска через коллекцию [TextFragmentAbsorber::TextFragments](../).

```cpp
class TextFragmentAbsorber : public Aspose::Pdf::Text::TextAbsorber
```

## Методы

| Метод | Описание |
| --- | --- |
| [ApplyForAllFragments](./applyforallfragments/)(const System::SharedPtr\<Font\>\&) | Применяет шрифт ко всем поглощённым текстовым фрагментам. Это работает быстрее, чем перебор фрагментов, если все фрагменты на странице(ах) были поглощены. В противном случае работает аналогично перебору. |
| [ApplyForAllFragments](./applyforallfragments/)(float) | Применяет размер шрифта ко всем поглощённым текстовым фрагментам. Это работает быстрее, чем перебор фрагментов, если все фрагменты на странице(ах) были поглощены. В противном случае работает аналогично перебору. |
| [ApplyForAllFragments](./applyforallfragments/)(const System::SharedPtr\<Font\>\&, float) | Применяет шрифт и размер ко всем поглощённым текстовым фрагментам. Это работает быстрее, чем перебор фрагментов, если все фрагменты на странице(ах) были поглощены. В противном случае работает аналогично перебору. |
| [get_Errors](./get_errors/)() | Список объектов [TextExtractionError](../textextractionerror/). Содержит информацию об ошибках, найденных во время извлечения текста. Поиск ошибок будет выполнен только если TextSearchOptions.LogTextExtractionErrors = true; и это может снизить производительность. |
| [get_ExtractionOptions](./get_extractionoptions/)() override | Получает параметры извлечения текста. |
| [get_HasErrors](./get_haserrors/)() | Значение указывает, были ли обнаружены ошибки во время извлечения текста. Поиск ошибок будет выполнен только если TextSearchOptions.LogTextExtractionErrors = true; и это может снизить производительность. |
| [get_Phrase](./get_phrase/)() const | Получает фразу, которую [TextFragmentAbsorber](./) ищет в PDF‑документе или на странице. |
| [get_RegexResults](./get_regexresults/)() const | Получает словарь вхождений поиска, где ключом является класс [System.Text.RegularExpressions.Regex](../../system.text.regularexpressions/regex/), а значением — [TextFragment](../textfragment/). |
| [get_Text](./get_text/)() override | Получает извлечённый текст, который [TextAbsorber](../textabsorber/) извлекает из PDF‑документа или со страницы. |
| [get_TextEditOptions](./get_texteditoptions/)() const | Получает параметры редактирования текста. Параметры определяют специальное поведение, когда запрашиваемый символ нельзя отобразить шрифтом. |
| [get_TextFragments](./get_textfragments/)() | Получает коллекцию вхождений поиска, представленных объектами [TextFragment](../textfragment/). |
| [get_TextReplaceOptions](./get_textreplaceoptions/)() const | Получает параметры замены текста. Параметры определяют поведение, когда текст фрагмента заменяется на более короткий/длинный. |
| [get_TextSearchOptions](./get_textsearchoptions/)() override | Получает параметры поиска. Параметры позволяют выполнять поиск с использованием регулярных выражений. |
| [RemoveAllText](./removealltext/)(const System::SharedPtr\<Page\>\&) | Удаляет весь текст с указанной страницы. |
| [RemoveAllText](./removealltext/)(const System::SharedPtr\<Page\>\&, const System::SharedPtr\<Rectangle\>\&) | Удаляет текст внутри указанного прямоугольника на указанной странице. |
| [RemoveAllText](./removealltext/)(const System::SharedPtr\<Document\>\&) | Удаляет весь текст из документа. |
| [Reset](./reset/)() | Очищает коллекцию TextFragments этого объекта [TextFragmentAbsorber](./). |
| [set_ExtractionOptions](./set_extractionoptions/)(System::SharedPtr\<TextExtractionOptions\>) override | Устанавливает параметры извлечения текста. |
| [set_Phrase](./set_phrase/)(const System::String\&) | Устанавливает фразу, которую [TextFragmentAbsorber](./) ищет в PDF‑документе или на странице. |
| [set_TextEditOptions](./set_texteditoptions/)(const System::SharedPtr\<Aspose::Pdf::Text::TextEditOptions\>\&) | Устанавливает параметры редактирования текста. Параметры определяют специальное поведение, когда запрашиваемый символ нельзя отобразить шрифтом. |
| [set_TextFragments](./set_textfragments/)(const System::SharedPtr\<TextFragmentCollection\>\&) | Получает коллекцию вхождений поиска, представленных объектами [TextFragment](../textfragment/). |
| [set_TextReplaceOptions](./set_textreplaceoptions/)(const System::SharedPtr\<Aspose::Pdf::Text::TextReplaceOptions\>\&) | Устанавливает параметры замены текста. Параметры определяют поведение при замене текста фрагмента на более короткий/длинный. |
| [set_TextSearchOptions](./set_textsearchoptions/)(System::SharedPtr\<Aspose::Pdf::Text::TextSearchOptions\>) override | Устанавливает параметры поиска. Параметры позволяют выполнять поиск с использованием регулярных выражений. |
| [TextFragmentAbsorber](./textfragmentabsorber/)() | Инициализирует новый экземпляр [TextFragmentAbsorber](./), который выполняет поиск всех текстовых сегментов документа или страницы. |
| [TextFragmentAbsorber](./textfragmentabsorber/)(const System::SharedPtr\<Aspose::Pdf::Text::TextEditOptions\>\&) | Инициализирует новый экземпляр [TextFragmentAbsorber](./) с параметрами редактирования текста, который выполняет поиск всех текстовых сегментов документа или страницы. |
| [TextFragmentAbsorber](./textfragmentabsorber/)(const System::String\&) | Инициализирует новый экземпляр класса [TextFragmentAbsorber](./) для указанной текстовой фразы. |
| [TextFragmentAbsorber](./textfragmentabsorber/)(const System::SharedPtr\<System::Text::RegularExpressions::Regex\>\&) | Инициализирует новый экземпляр класса [TextFragmentAbsorber](./) для указанного объекта класса [System.Text.RegularExpressions.Regex](../../system.text.regularexpressions/regex/). |
| [TextFragmentAbsorber](./textfragmentabsorber/)(const System::String\&, const System::SharedPtr\<Aspose::Pdf::Text::TextSearchOptions\>\&) | Инициализирует новый экземпляр класса [TextFragmentAbsorber](./) для указанной текстовой фразы и параметров поиска текста. |
| [TextFragmentAbsorber](./textfragmentabsorber/)(const System::SharedPtr\<System::Text::RegularExpressions::Regex\>\&, const System::SharedPtr\<Aspose::Pdf::Text::TextSearchOptions\>\&) | Инициализирует новый экземпляр класса [TextFragmentAbsorber](./) для указанной текстовой фразы и параметров поиска текста. |
| [TextFragmentAbsorber](./textfragmentabsorber/)(const System::ArrayPtr\<System::SharedPtr\<System::Text::RegularExpressions::Regex\>\>\&, const System::SharedPtr\<Aspose::Pdf::Text::TextSearchOptions\>\&) | Инициализирует новый экземпляр класса [TextFragmentAbsorber](./) для указанной текстовой фразы и параметров поиска текста. |
| [TextFragmentAbsorber](./textfragmentabsorber/)(const System::String\&, const System::SharedPtr\<Aspose::Pdf::Text::TextSearchOptions\>\&, const System::SharedPtr\<Aspose::Pdf::Text::TextEditOptions\>\&) | Инициализирует новый экземпляр класса [TextFragmentAbsorber](./) для указанной текстовой фразы, параметров поиска текста и параметров редактирования текста. |
| [TextFragmentAbsorber](./textfragmentabsorber/)(const System::String\&, const System::SharedPtr\<Aspose::Pdf::Text::TextEditOptions\>\&) | Инициализирует новый экземпляр класса [TextFragmentAbsorber](./) для указанной текстовой фразы и параметров редактирования текста. |
| [TextFragmentAbsorber](./textfragmentabsorber/)(const System::SharedPtr\<System::Text::RegularExpressions::Regex\>\&, const System::SharedPtr\<Aspose::Pdf::Text::TextEditOptions\>\&) | Инициализирует новый экземпляр класса [TextFragmentAbsorber](./) для указанной текстовой фразы и параметров редактирования текста. |
| [Visit](./visit/)(System::SharedPtr\<Page\>) override | Выполняет поиск на указанной странице. |
| [Visit](./visit/)(System::SharedPtr\<Document\>) override | Выполняет поиск в указанном документе. |
| [Visit](./visit/)(System::SharedPtr\<XForm\>) override | Выполняет поиск в указанном объекте формы. |
## Примечания


Объект [TextFragmentAbsorber](./) в основном используется в сценарии поиска текста. После завершения поиска вхождения представлены объектами [TextFragment](../textfragment/), которые содержатся в коллекции [TextFragmentAbsorber::TextFragments](../). Объект [TextFragment](../textfragment/) предоставляет доступ к тексту найденного вхождения, его свойствам и позволяет редактировать текст и изменять состояние текста (шрифт, размер шрифта, цвет и т.д.).
## См. также

* Class [TextAbsorber](../textabsorber/)
* Namespace [Aspose::Pdf::Text](../)
* Library [Aspose.PDF for C++](../../)
