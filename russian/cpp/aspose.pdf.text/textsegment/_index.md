---
title: "Класс Aspose::Pdf::Text::TextSegment"
linktitle: "TextSegment"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс Aspose::Pdf::Text::TextSegment. Представляет сегмент текста PDF на C++."
type: docs
weight: 5100
url: /ru/cpp/aspose.pdf.text/textsegment/
---
## TextSegment class


Представляет сегмент текста [Pdf](../../aspose.pdf/).

```cpp
class TextSegment : public System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| [get_BaselinePosition](./get_baselineposition/)() const | Получает позицию текста, представленного объектом [TextSegment](./). YIndent структуры [Position](../position/) представляет координату базовой линии сегмента текста. |
| [get_Characters](./get_characters/)() | Получает коллекцию объектов [CharInfo](../charinfo/), представляющих информацию о символах в сегменте текста. |
| [get_EndCharIndex](./get_endcharindex/)() const | Получает индекс конечного символа текущего сегмента в операторе отображения текста (Tj, TJ). |
| [get_Hyperlink](./get_hyperlink/)() const | Получает гиперссылку сегмента (для генератора PDF). |
| [get_Position](./get_position/)() const | Получает позицию текста, представленного объектом [TextSegment](./). |
| [get_Rectangle](./get_rectangle/)() | Получает прямоугольник [TextSegment](./). |
| [get_StartCharIndex](./get_startcharindex/)() const | Получает начальный индекс символа текущего сегмента в операторе отображения текста (Tj, TJ) сегмента. |
| [get_Text](./get_text/)() const | Получает объект текста [System::String](../../system/string/), который представляет объект [TextSegment](./). |
| [get_TextEditOptions](./get_texteditoptions/)() const | Получает параметры редактирования текста. Параметры определяют специальное поведение, когда запрашиваемый символ нельзя отобразить шрифтом. |
| [get_TextState](./get_textstate/)() const | Получает состояние текста для текста, который представляет объект [TextSegment](./). |
| static [MyHtmlEncode](./myhtmlencode/)(const System::String\&) | Кодирует строку как html. |
| [set_BaselinePosition](./set_baselineposition/)(const System::SharedPtr\<Aspose::Pdf::Text::Position\>\&) | Получает позицию текста, представленного объектом [TextSegment](./). YIndent структуры [Position](../position/) представляет координату базовой линии сегмента текста. |
| [set_Hyperlink](./set_hyperlink/)(const System::SharedPtr\<Aspose::Pdf::Hyperlink\>\&) | Устанавливает гиперссылку сегмента (для генератора pdf). |
| [set_Position](./set_position/)(const System::SharedPtr\<Aspose::Pdf::Text::Position\>\&) | Получает позицию текста, представленного объектом [TextSegment](./). |
| [set_Text](./set_text/)(const System::String\&) | Устанавливает объект текста [System::String](../../system/string/), который представляет объект [TextSegment](./). |
| [set_TextEditOptions](./set_texteditoptions/)(const System::SharedPtr\<Aspose::Pdf::Text::TextEditOptions\>\&) | Устанавливает параметры редактирования текста. Параметры определяют специальное поведение, когда запрашиваемый символ нельзя отобразить шрифтом. |
| [set_TextState](./set_textstate/)(const System::SharedPtr\<Aspose::Pdf::Text::TextState\>\&) | Устанавливает состояние текста для текста, который представляет объект [TextSegment](./). |
| [TextSegment](./textsegment/)() | Создаёт объект [TextSegment](./). |
| [TextSegment](./textsegment/)(const System::String\&) | Создаёт объект [TextSegment](./). |
## Примечания


В нескольких словах, объекты [TextSegment](./) являются дочерними для объекта [TextFragment](../textfragment/).

Подробно:

[Text](../) of pdf document in [Aspose::Pdf](../../aspose.pdf/) is represented by two basic objects: [TextFragment](../textfragment/) and [TextSegment](./)

Различия между ними в основном завсят от контекста.

Рассмотрим следующую ситуацию. Пользователь ищет текст "hello world", чтобы работать с ним, изменять его свойства, просматривать и т.д.
```cpp
Document doc = new Document(docFile);
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");
doc.Pages[1].Accept(absorber);
```
Физическое представление текста PDF очень сложное. Текст "hello world" может состоять из нескольких физически независимых сегментов текста.

Модель текста [Aspose.Pdf](../../aspose.pdf/) по сути устанавливает, что объект [TextFragment](../textfragment/) предоставляет набор единой логической операции над набором физических объектов [TextSegment](./), которые представляют запрос пользователя.

В сценарии поиска текста, [TextFragment](../textfragment/) является логическим представлением текста "hello world", а коллекция объектов [TextSegment](./) представляет все физические сегменты, которые формируют объект текста "hello world".

Таким образом, [TextFragment](../textfragment/) близок к логическому представлению текста. А [TextSegment](./) близок к физическому представлению текста.

Очевидно, каждый объект [TextSegment](./) может иметь собственные свойства шрифта, цвета и позиционирования.

[TextFragment](../textfragment/) provides simple way to change text with it's properties: set font, set font size, set font color etc. Meanwhile [TextSegment](./) objects are accessible and users are able to operate with [TextSegment](./) objects independently. 
## См. также

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf::Text](../)
* Library [Aspose.PDF for C++](../../)
