---
title: Class Font
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.Text.Font. Представляет объект шрифта
type: docs
weight: 10510
url: /ru/net/aspose.pdf.text/font/
---
## Класс Шрифт

Представляет объект шрифта.

```csharp
public sealed class Font
```

## Свойства

| Название | Описание |
| --- | --- |
| [BaseFont](../../aspose.pdf.text/font/basefont/) { get; } | Получает значение BaseFont объекта шрифта PDF. Также известен как имя PostScript шрифта. |
| [DecodedFontName](../../aspose.pdf.text/font/decodedfontname/) { get; } | Иногда шрифты PDF (обычно китайские/японские/корейские шрифты) могут иметь специфическое имя шрифта. Это имя является значением свойства шрифта PDF "BaseFont", и иногда это свойство может быть представлено в шестнадцатеричной форме. Если прочитать это имя напрямую, оно может быть представлено в нечитаемой форме. Чтобы получить читаемую форму, необходимо декодировать имя шрифта по правилам, специфичным для этого шрифта. Это свойство возвращает декодированное имя шрифта, поэтому используйте его в случаях, когда вы сталкиваетесь с нечитаемым [`FontName`](./fontname/). Если свойство [`FontName`](./fontname/) имеет читаемую форму, это свойство будет таким же, как и [`FontName`](./fontname/), поэтому вы можете использовать это свойство в любых случаях, когда вам нужно получить имя шрифта в читаемой форме. |
| [FontName](../../aspose.pdf.text/font/fontname/) { get; } | Получает имя шрифта объекта `Font`. |
| [FontOptions](../../aspose.pdf.text/font/fontoptions/) { get; } | Полезные свойства для настройки поведения шрифта |
| [IsAccessible](../../aspose.pdf.text/font/isaccessible/) { get; } | Получает информацию о том, присутствует ли шрифт (установлен) в системе. |
| [IsEmbedded](../../aspose.pdf.text/font/isembedded/) { get; set; } | Получает или устанавливает значение, указывающее, встроен ли шрифт. Шрифт на основе IFont будет автоматически подмножен и встроен |
| [IsSubset](../../aspose.pdf.text/font/issubset/) { get; set; } | Получает или устанавливает значение, указывающее, является ли шрифт подмножеством. Шрифт на основе IFont будет автоматически подмножен и встроен |

## Методы

| Название | Описание |
| --- | --- |
| [GetLastFontEmbeddingError](../../aspose.pdf.text/font/getlastfontembeddingerror/)() | Цель этого метода - вернуть описание ошибки, если попытка встроить шрифт не удалась. Если ошибок нет, возвращает пустую строку. |
| [MeasureString](../../aspose.pdf.text/font/measurestring/)(string, float) | Измеряет строку. |
| [Save](../../aspose.pdf.text/font/save/)(Stream) | Сохраняет шрифт в поток. Обратите внимание, что шрифт сохраняется в промежуточный формат TTF, предназначенный для использования только в преобразованной копии оригинального документа. Файл шрифта не предназначен для использования вне контекста оригинального документа. |

## Примеры

Пример демонстрирует, как искать текст на первой странице и изменить шрифт первого найденного вхождения.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// Create font and mark it to be embedded
Font font = FontRepository.FindFont("Arial");
font.IsEmbedded = true;

// Change font of the first text occurrence
absorber.TextFragments[1].TextState.Font = font;


// Save document
doc.Save(@"D:\Tests\output.pdf"); 
```

### См. также

* класс [TextFragmentAbsorber](../textfragmentabsorber/)
* класс [FontRepository](../fontrepository/)
* класс [Document](../../aspose.pdf/document/)
* пространство имен [Aspose.Pdf.Text](../../aspose.pdf.text/)
* сборка [Aspose.PDF](../../)