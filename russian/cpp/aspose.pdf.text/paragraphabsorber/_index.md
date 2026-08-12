---
title: "Aspose::Pdf::Text::ParagraphAbsorber class"
linktitle: "ParagraphAbsorber"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Text::ParagraphAbsorber class. Представляет объект‑поглотитель объектов структуры страницы, таких как разделы и абзацы. Выполняет поиск разделов и абзацев текста и предоставляет доступ к прямоугольникам и полигону, описывающим их в координатном пространстве текста. Также выполняет поиск текстовых сегментов и предоставляет доступ к результатам поиска через коллекции TextFragments, сгруппированные по элементам структуры в C++."
type: docs
weight: 2600
url: /ru/cpp/aspose.pdf.text/paragraphabsorber/
---
## ParagraphAbsorber class


Представляет объект-абсорбер структурных объектов страницы, таких как секции и абзацы. Выполняет поиск секций и абзацев текста и предоставляет доступ к прямоугольникам и полигонам, описывающим их в координатном пространстве текста. Также выполняет поиск текстовых сегментов и предоставляет доступ к результатам поиска через коллекции [TextFragments](../), сгруппированные по структурным элементам.

```cpp
class ParagraphAbsorber : public System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| [get_IsMulticolumnParagraphsAllowed](./get_ismulticolumnparagraphsallowed/)() const | Получает значение, указывающее, могут ли начальные строки текста следующего раздела рассматриваться как продолжение последнего абзаца предыдущего раздела. |
| [get_PageMarkups](./get_pagemarkups/)() const | Получает коллекцию [PageMarkup](../pagemarkup/), которые были поглощены. |
| [get_ParagraphAbsorberOptions](./get_paragraphabsorberoptions/)() const | Получает [ParagraphAbsorberOptions](../paragraphabsorberoptions/). |
| [get_SectionsSearchDepth](./get_sectionssearchdepth/)() const | Получает значение, указывающее, сколько раз будут выполнены последовательные поиски более мелких элементов структуры. Глубина поиска по умолчанию равна 3. Это означает три поиска горизонтально разделённых разделов (заголовки, абзацы и т.д.) и три поиска вертикально разделённых (колонки). |
| [get_TextReplaceOptions](./get_textreplaceoptions/)() const | Получает [TextReplaceOptions](../textreplaceoptions/). |
| [ParagraphAbsorber](./paragraphabsorber/)() | Инициализирует новый экземпляр [ParagraphAbsorber](./), который выполняет поиск разделов/абзацев в документе или на странице. |
| [ParagraphAbsorber](./paragraphabsorber/)(int32_t) | Инициализирует новый экземпляр [ParagraphAbsorber](./), который выполняет поиск разделов/абзацев в документе или на странице. |
| [ParagraphAbsorber](./paragraphabsorber/)(const System::SharedPtr\<Aspose::Pdf::Text::ParagraphAbsorberOptions\>\&) | Инициализирует новый экземпляр [ParagraphAbsorber](./), который выполняет поиск разделов/абзацев в документе или на странице с указанными параметрами. |
| [ParagraphAbsorber](./paragraphabsorber/)(int32_t, const System::SharedPtr\<Aspose::Pdf::Text::ParagraphAbsorberOptions\>\&) | Инициализирует новый экземпляр [ParagraphAbsorber](./), который выполняет поиск разделов/абзацев в документе или на странице с указанными параметрами. |
| [set_IsMulticolumnParagraphsAllowed](./set_ismulticolumnparagraphsallowed/)(bool) | Устанавливает значение, указывающее, могут ли начальные строки текста следующего раздела рассматриваться как продолжение последнего абзаца предыдущего раздела. |
| [set_ParagraphAbsorberOptions](./set_paragraphabsorberoptions/)(const System::SharedPtr\<Aspose::Pdf::Text::ParagraphAbsorberOptions\>\&) | Устанавливает [ParagraphAbsorberOptions](../paragraphabsorberoptions/). |
| [set_SectionsSearchDepth](./set_sectionssearchdepth/)(int32_t) | Устанавливает значение, указывающее, сколько раз будут выполнены последовательные поиски более мелких элементов структуры. Глубина поиска по умолчанию равна 3. Это означает три поиска горизонтально разделённых разделов (заголовки, абзацы и т.д.) и три поиска вертикально разделённых (колонки). |
| [set_TextReplaceOptions](./set_textreplaceoptions/)(const System::SharedPtr\<Aspose::Pdf::Text::TextReplaceOptions\>\&) | Устанавливает [TextReplaceOptions](../textreplaceoptions/). |
| [Visit](./visit/)(const System::SharedPtr\<Document\>\&) | Выполняет поиск разделов и абзацев в указанном [Document](../../aspose.pdf/document/). |
| [Visit](./visit/)(const System::SharedPtr\<Page\>\&) | Выполняет поиск в указанной [Page](../../aspose.pdf/page/). |
## Примечания


Когда поиск завершится, коллекция [ParagraphAbsorber::PageMarkups](../) будет содержать объекты [PageMarkup](../pagemarkup/), представляющие структуру страницы коллекциями [MarkupSection](../markupsection/) и [MarkupParagraph](../markupparagraph/). Объект [TextFragment](../textfragment/) предоставляет доступ к найденному тексту, его свойствам и позволяет редактировать текст и изменять его состояние (шрифт, размер шрифта, цвет и т.д.).
## См. также

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf::Text](../)
* Library [Aspose.PDF for C++](../../)
