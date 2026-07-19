---
title: "Aspose::Pdf::Text::TextFragment класс"
linktitle: "TextFragment"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Text::TextFragment класс. Представляет фрагмент текста Pdf в C++."
type: docs
weight: 4300
url: /ru/cpp/aspose.pdf.text/textfragment/
---
## TextFragment class


Представляет фрагмент текста [Pdf](../../aspose.pdf/).

```cpp
class TextFragment : public Aspose::Pdf::BaseParagraph
```

## Методы

| Метод | Описание |
| --- | --- |
| [Clone](./clone/)() override | Клонировать фрагмент. |
| virtual [CloneWithSegments](./clonewithsegments/)() | Клонировать фрагмент со всеми сегментами. |
| [get_BaselinePosition](./get_baselineposition/)() | Возвращает позицию текста для текста, представленного объектом [TextFragment](./). YIndent структуры [Position](../position/) представляет координату базовой линии фрагмента текста. |
| [get_EndNote](./get_endnote/)() const | Возвращает примечание в конце абзаца (только для генерации pdf). |
| [get_FootNote](./get_footnote/)() const | Возвращает сноску абзаца (только для генерации pdf). |
| [get_Form](./get_form/)() const | Возвращает объект формы, содержащий [TextFragment](./). |
| [get_HorizontalAlignment](./get_horizontalalignment/)() override | Возвращает горизонтальное выравнивание фрагмента текста. |
| [get_Page](./get_page/)() const | Получает страницу, содержащую [TextFragment](./). |
| [get_Position](./get_position/)() | Получает позицию текста для текста, представленного объектом [TextFragment](./). |
| [get_Rectangle](./get_rectangle/)() | Получает прямоугольник [TextFragment](./). |
| [get_ReplaceOptions](./get_replaceoptions/)() const | Получает параметры замены текста. Параметры определяют поведение, когда текст фрагмента заменяется на более короткий/длинный. |
| [get_Segments](./get_segments/)() const | Получает сегменты текста для текущего [TextFragment](./). |
| [get_Text](./get_text/)() | Получает объект текста [System::String](../../system/string/), который представляет объект [TextFragment](./). |
| [get_TextEditOptions](./get_texteditoptions/)() const | Получает параметры редактирования текста. Параметры определяют специальное поведение, когда запрашиваемый символ нельзя отобразить шрифтом. |
| [get_TextState](./get_textstate/)() | Получает состояние текста для текста, который представляет объект [TextFragment](./). |
| [get_VerticalAlignment](./get_verticalalignment/)() override | Получает вертикальное выравнивание текстового фрагмента. |
| [get_WrapLinesCount](./get_wraplinescount/)() const | Получает количество строк переноса для этого абзаца (только для генерации PDF) |
| [IsolateTextSegments](./isolatetextsegments/)(int32_t, int32_t) | Получает [TextSegment](../textsegment/)(ы), представляющие указанную часть текста [TextFragment](./). |
| [set_BaselinePosition](./set_baselineposition/)(const System::SharedPtr\<Aspose::Pdf::Text::Position\>\&) | Возвращает позицию текста для текста, представленного объектом [TextFragment](./). YIndent структуры [Position](../position/) представляет координату базовой линии фрагмента текста. |
| [set_EndNote](./set_endnote/)(const System::SharedPtr\<Note\>\&) | Устанавливает конечную сноску абзаца.(только для генерации PDF) |
| [set_FootNote](./set_footnote/)(const System::SharedPtr\<Note\>\&) | Устанавливает сноску внизу абзаца.(только для генерации PDF) |
| [set_HorizontalAlignment](./set_horizontalalignment/)(Aspose::Pdf::HorizontalAlignment) override | Устанавливает горизонтальное выравнивание текстового фрагмента. |
| [set_Hyperlink](./set_hyperlink/)(System::SharedPtr\<Aspose::Pdf::Hyperlink\>) override | Устанавливает гиперссылку фрагмента. |
| [set_Position](./set_position/)(const System::SharedPtr\<Aspose::Pdf::Text::Position\>\&) | Устанавливает позицию текста для текста, представленного объектом [TextFragment](./). |
| [set_Segments](./set_segments/)(const System::SharedPtr\<TextSegmentCollection\>\&) | Получает сегменты текста для текущего [TextFragment](./). |
| [set_Text](./set_text/)(const System::String\&) | Устанавливает объект текста [System::String](../../system/string/), который представляет объект [TextFragment](./). |
| [set_TextEditOptions](./set_texteditoptions/)(const System::SharedPtr\<Aspose::Pdf::Text::TextEditOptions\>\&) | Устанавливает параметры редактирования текста. Параметры определяют специальное поведение, когда запрашиваемый символ нельзя отобразить шрифтом. |
| [set_VerticalAlignment](./set_verticalalignment/)(Aspose::Pdf::VerticalAlignment) override | Устанавливает вертикальное выравнивание текстового фрагмента. |
| [set_WrapLinesCount](./set_wraplinescount/)(int32_t) | Устанавливает количество строк переноса для этого абзаца (только для генерации PDF) |
| [TextFragment](./textfragment/)() | Инициализирует новый экземпляр объекта [TextFragment](./). |
| [TextFragment](./textfragment/)(const System::SharedPtr\<TabStops\>\&) | Инициализирует новый экземпляр объекта [TextFragment](./) с предопределёнными позициями [TabStops](../tabstops/). |
| [TextFragment](./textfragment/)(const System::String\&) | Создаёт объект [TextFragment](./) с единственным объектом [TextSegment](../textsegment/) внутри. Указывает строку текста внутри сегмента. |
| [TextFragment](./textfragment/)(const System::String\&, const System::SharedPtr\<TabStops\>\&) | Создаёт объект [TextFragment](./) с единственным объектом [TextSegment](../textsegment/) внутри и предопределёнными позициями [TabStops](../tabstops/). |
## Примечания


В нескольких словах, объект [TextFragment](./) содержит список объектов [TextSegment](../textsegment/).

Подробно: [Text](../) PDF‑документа в [Aspose::Pdf](../../aspose.pdf/) представляется двумя базовыми объектами: [TextFragment](./) и [TextSegment](../textsegment/)

Различия между ними в основном завсят от контекста.

Рассмотрим следующую ситуацию. Пользователь ищет текст "hello world", чтобы работать с ним, изменять его свойства, просматривать и т.д.
```cpp
Document doc = new Document(docFile);
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");
doc.Pages[1].Accept(absorber);
```
Физическое представление текста PDF очень сложное. Текст "hello world" может состоять из нескольких физически независимых сегментов текста.

Модель текста [Aspose.Pdf](../../aspose.pdf/) по сути устанавливает, что объект [TextFragment](./) предоставляет единый набор логических операций над набором физических объектов [TextSegment](../textsegment/), представляющих запрос пользователя.

В сценарии поиска текста [TextFragment](./) является логическим представлением текста "hello world", а коллекция объектов [TextSegment](../textsegment/) представляет все физические сегменты, составляющие объект текста "hello world".

Таким образом, [TextFragment](./) близок к логическому представлению текста. А [TextSegment](../textsegment/) близок к физическому представлению текста.

Очевидно, каждый объект [TextSegment](../textsegment/) может иметь свои собственные свойства шрифта, цвета и позиционирования.

[TextFragment](./) provides simple way to change text with it's properties: set font, set font size, set font color etc. Meanwhile [TextSegment](../textsegment/) objects are accessible and users are able to operate with [TextSegment](../textsegment/) objects independently.

[Note](../../aspose.pdf/note/) that changing [TextFragment](./) properties may change inner [Segments](../) collection because [TextFragment](./) is an aggregate object and it may rearrange internal segments or merge them into single segment. If your requirement is to leave the [Segments](../) collection unchanged, please change inner segments individually. 
## См. также

* Class [BaseParagraph](../../aspose.pdf/baseparagraph/)
* Namespace [Aspose::Pdf::Text](../)
* Library [Aspose.PDF for C++](../../)
