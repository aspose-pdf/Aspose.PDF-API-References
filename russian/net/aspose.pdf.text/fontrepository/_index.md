---
title: Class FontRepository
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.Text.FontRepository. Выполняет поиск шрифтов. Ищет в системных установленных шрифтах и стандартных Pdf шрифтах. Также предоставляет функциональность для открытия пользовательских шрифтов
type: docs
weight: 10540
url: /ru/net/aspose.pdf.text/fontrepository/
---
## Класс FontRepository

Выполняет поиск шрифтов. Ищет в системных установленных шрифтах и стандартных Pdf шрифтах. Также предоставляет функциональность для открытия пользовательских шрифтов.

```csharp
public sealed class FontRepository
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [FontRepository](fontrepository/)() | Конструктор по умолчанию. |

## Свойства

| Имя | Описание |
| --- | --- |
| static [Sources](../../aspose.pdf.text/fontrepository/sources/) { get; } | Получает коллекцию источников шрифтов. |
| static [Substitutions](../../aspose.pdf.text/fontrepository/substitutions/) { get; } | Получает коллекцию стратегий замены шрифтов. |

## Методы

| Имя | Описание |
| --- | --- |
| static [FindFont](../../aspose.pdf.text/fontrepository/findfont/#findfont)(string) | Ищет и возвращает шрифт с указанным именем шрифта. |
| static [FindFont](../../aspose.pdf.text/fontrepository/findfont/#findfont_3)(string, bool) | Ищет и возвращает шрифт с указанным именем шрифта, игнорируя или учитывая чувствительность к регистру. |
| static [FindFont](../../aspose.pdf.text/fontrepository/findfont/#findfont_1)(string, FontStyles) | Ищет и возвращает шрифт с указанным именем шрифта и стилем шрифта. |
| static [FindFont](../../aspose.pdf.text/fontrepository/findfont/#findfont_2)(string, FontStyles, bool) | Ищет и возвращает шрифт с указанным именем шрифта и стилем шрифта, игнорируя или учитывая чувствительность к регистру. |
| static [LoadFonts](../../aspose.pdf.text/fontrepository/loadfonts/)() | Загружает системные установленные шрифты и стандартные Pdf шрифты. Этот метод был разработан для ускорения процесса загрузки шрифтов. По умолчанию шрифты загружаются при первом запросе на любой шрифт. Использование этого метода загружает системные и стандартные Pdf шрифты немедленно перед открытием любого Pdf документа. |
| static [OpenFont](../../aspose.pdf.text/fontrepository/openfont/#openfont_1)(string) | Открывает шрифт с указанным путем к файлу шрифта. |
| static [OpenFont](../../aspose.pdf.text/fontrepository/openfont/#openfont)(Stream, FontTypes) | Открывает шрифт с указанным потоком шрифта. |
| static [OpenFont](../../aspose.pdf.text/fontrepository/openfont/#openfont_2)(string, string) | Открывает шрифт с указанным путем к файлу шрифта и путем к файлу метрик. |
| static [ReloadFonts](../../aspose.pdf.text/fontrepository/reloadfonts/)() | Перезагружает все шрифты, указанные свойством [`Sources`](./sources/) |

## Примеры

Пример демонстрирует, как найти шрифт и заменить шрифт текста на первой странице.

```csharp
// Find font
Font font = FontRepository.FindFont("Arial");

// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// Change font of the first text occurrence
absorber.TextFragments[1].TextState.Font = font;

// Save document
doc.Save(@"D:\Tests\output.pdf"); 
```

### См. также

* класс [TextFragmentAbsorber](../textfragmentabsorber/)
* класс [Document](../../aspose.pdf/document/)
* пространство имен [Aspose.Pdf.Text](../../aspose.pdf.text/)
* сборка [Aspose.PDF](../../)