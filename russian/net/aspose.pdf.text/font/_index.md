---
title: "Класс Font"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Класс Aspose.Pdf.Text.Font. Представляет объект шрифта"
type: docs
weight: 10690
url: /ru/net/aspose.pdf.text/font/
---
## Font class

Представляет объект шрифта.

```csharp
public sealed class Font
```

## Свойства

| Имя | Описание |
| --- | --- |
| [BaseFont](../../aspose.pdf.text/font/basefont/) { get; } | Получает значение BaseFont объекта шрифта PDF. Также известное как имя PostScript шрифта. |
| [DecodedFontName](../../aspose.pdf.text/font/decodedfontname/) { get; } | Иногда шрифты PDF (обычно китайские/японские/корейские шрифты) могут иметь специфическое имя шрифта. Это имя является значением свойства PDF‑шрифта "BaseFont", и иногда это свойство может быть представлено в шестнадцатеричной форме. Если читать это имя напрямую, оно может отображаться в нечитаемом виде. Чтобы получить читаемую форму, необходимо декодировать имя шрифта по правилам, специфичным для данного шрифта. Это свойство возвращает декодированное имя шрифта, поэтому используйте его в случаях, когда вы сталкиваетесь с нечитаемым [`FontName`](./fontname/). Если свойство [`FontName`](./fontname/) имеет читаемую форму, это свойство будет таким же, как [`FontName`](./fontname/), так что вы можете использовать его в любых случаях, когда нужно получить имя шрифта в читаемом виде. |
| [FontName](../../aspose.pdf.text/font/fontname/) { get; } | Получает имя шрифта объекта `Font`. |
| [FontOptions](../../aspose.pdf.text/font/fontoptions/) { get; } | Полезные свойства для настройки поведения шрифта |
| [IsAccessible](../../aspose.pdf.text/font/isaccessible/) { get; } | Получает индикатор того, установлен ли шрифт в системе. |
| [IsEmbedded](../../aspose.pdf.text/font/isembedded/) { get; set; } | Получает или задает значение, указывающее, встроен ли шрифт. Шрифт, основанный на IFont, будет автоматически подмножеством и встроен. |
| [IsSubset](../../aspose.pdf.text/font/issubset/) { get; set; } | Получает или задает значение, указывающее, является ли шрифт подмножеством. Шрифт, основанный на IFont, будет автоматически подмножеством и встроен. |

## Методы

| Имя | Описание |
| --- | --- |
| [GetLastFontEmbeddingError](../../aspose.pdf.text/font/getlastfontembeddingerror/)() | Цель этого метода — вернуть описание ошибки, если попытка встроить шрифт не удалась. Если ошибок нет, возвращается пустая строка. |
| [MeasureString](../../aspose.pdf.text/font/measurestring/)(string, float) | Измеряет строку. |
| [Save](../../aspose.pdf.text/font/save/)(Stream) | Сохраняет шрифт в поток. Обратите внимание, что шрифт сохраняется во временный формат TTF, предназначенный только для использования в преобразованной копии оригинального документа. Файл шрифта не предназначен для использования вне контекста оригинального документа. |

## Примеры

Пример демонстрирует, как искать текст на первой странице и изменить шрифт первого найденного вхождения.

```csharp
// Открыть документ
Document doc = new Document(@"D:\Tests\input.pdf");

// Создайте объект TextFragmentAbsorber для поиска всех вхождений текста "hello world"
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Примите поглотитель для первой страницы
doc.Pages[1].Accept(absorber);

// Создайте шрифт и пометьте его для встраивания
Font font = FontRepository.FindFont("Arial");
font.IsEmbedded = true;

// Изменить шрифт первого вхождения текста
absorber.TextFragments[1].TextState.Font = font;


// Сохранить документ
doc.Save(@"D:\Tests\output.pdf"); 
```

### См. также

* class [TextFragmentAbsorber](../textfragmentabsorber/)
* class [FontRepository](../fontrepository/)
* class [Document](../../aspose.pdf/document/)
* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


