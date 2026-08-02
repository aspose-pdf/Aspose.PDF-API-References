---
title: "Класс ParagraphAbsorber"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Класс Aspose.Pdf.Text.ParagraphAbsorber. Представляет объект‑поглотитель объектов структуры страницы, таких как разделы и абзацы. Выполняет поиск разделов и абзацев текста и предоставляет доступ к прямоугольникам и полигону, описывающим их в координатном пространстве текста. Также выполняет поиск текстовых сегментов и предоставляет доступ к результатам поиска через коллекции TextFragments, сгруппированные по элементам структуры."
type: docs
weight: 10850
url: /ru/net/aspose.pdf.text/paragraphabsorber/
---
## ParagraphAbsorber class

Представляет объект-абсорбер объектов структуры страницы, таких как секции и абзацы. Выполняет поиск секций и абзацев текста и предоставляет доступ к прямоугольникам и полигонам, описывающим их в координатном пространстве текста. Также выполняет поиск текстовых сегментов и предоставляет доступ к результатам поиска через коллекции !:TextFragments, сгруппированные по структурным элементам.

```csharp
public class ParagraphAbsorber
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [ParagraphAbsorber](paragraphabsorber/#constructor)() | Инициализирует новый экземпляр `ParagraphAbsorber`, который выполняет поиск разделов/абзацев документа или страницы. |
| [ParagraphAbsorber](paragraphabsorber/#constructor_2)(int) | Инициализирует новый экземпляр `ParagraphAbsorber`, который выполняет поиск разделов/абзацев документа или страницы. |
| [ParagraphAbsorber](paragraphabsorber/#constructor_1)(ParagraphAbsorberOptions) | Инициализирует новый экземпляр `ParagraphAbsorber`, который выполняет поиск разделов/абзацев документа или страницы с указанными параметрами. |
| [ParagraphAbsorber](paragraphabsorber/#constructor_3)(int, ParagraphAbsorberOptions) | Инициализирует новый экземпляр `ParagraphAbsorber`, который выполняет поиск разделов/абзацев документа или страницы с указанными параметрами. |

## Свойства

| Имя | Описание |
| --- | --- |
| [IsMulticolumnParagraphsAllowed](../../aspose.pdf.text/paragraphabsorber/ismulticolumnparagraphsallowed/) { get; set; } | Получает или задает значение, указывающее, могут ли начальные строки текста следующего раздела рассматриваться как продолжение последнего абзаца предыдущего раздела. |
| [PageMarkups](../../aspose.pdf.text/paragraphabsorber/pagemarkups/) { get; } | Получает коллекцию [`PageMarkup`](../pagemarkup/), которые были поглощены. |
| [ParagraphAbsorberOptions](../../aspose.pdf.text/paragraphabsorber/paragraphabsorberoptions/) { get; set; } | Получает или задает ParagraphAbsorberOptions. |
| [SectionsSearchDepth](../../aspose.pdf.text/paragraphabsorber/sectionssearchdepth/) { get; set; } | Получает или задает значение, определяющее, сколько раз будут выполнены последовательные поиски более мелких элементов структуры. Глубина поиска по умолчанию — 3. Это означает три поиска по горизонтально разделённым разделам (заголовки, абзацы и т.д.) и три поиска по вертикально разделённым (колонки). |
| [TextReplaceOptions](../../aspose.pdf.text/paragraphabsorber/textreplaceoptions/) { get; set; } | Получает или задает TextReplaceOptions. |

## Методы

| Имя | Описание |
| --- | --- |
| [Visit](../../aspose.pdf.text/paragraphabsorber/visit/#visit)(Document) | Выполняет поиск разделов и абзацев в указанном [`Document`](../../aspose.pdf/document/). |
| [Visit](../../aspose.pdf.text/paragraphabsorber/visit/#visit_1)(Page) | Выполняет поиск в указанной [`Page`](../../aspose.pdf/page/). |

## Примечания

Когда поиск завершится, коллекция [`PageMarkups`](./pagemarkups/) будет содержать объекты [`PageMarkup`](../pagemarkup/), представляющие структуру страницы коллекциями [`MarkupSection`](../markupsection/) и [`MarkupParagraph`](../markupparagraph/). Объект [`TextFragment`](../textfragment/) предоставляет доступ к найденному тексту, его свойствам и позволяет редактировать текст и изменять его состояние (шрифт, размер шрифта, цвет и т.д.).

## Примеры

Пример демонстрирует, как найти первый текстовый сегмент каждого абзаца на первой странице PDF‑документа и выделить его.

```csharp
// Открыть документ
Document doc = new Document("input.pdf");

// Создать объект ParagraphAbsorber
ParagraphAbsorber absorber = new ParagraphAbsorber();

// Примите поглотитель для первой страницы
absorber.Visit(doc.Pages[1]);

// Получить объект разметки первой страницы
PageMarkup markup = absorber.PageMarkups[0];

// Пройти по элементам структуры текста страницы, чтобы найти первый фрагмент текста каждого абзаца
foreach (MarkupSection section in markup.Sections)
{
    foreach (MarkupParagraph paragraph in section.Paragraphs)
    {
        TextFragment fragment = paragraph.Fragments[0];
        // Обновить свойства текста
        fragment.TextState.BackgroundColor = Color.LightBlue;
    }
}

// Сохранить документ
doc.Save(GetOutputPath("output.pdf"));
```

### См. также

* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


