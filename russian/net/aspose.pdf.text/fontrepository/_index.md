---
title: "Класс FontRepository"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Класс Aspose.Pdf.Text.FontRepository. Выполняет поиск шрифтов. Ищет в системных установленных шрифтах и стандартных шрифтах Pdf. Также предоставляет возможность открывать пользовательские шрифты."
type: docs
weight: 10720
url: /ru/net/aspose.pdf.text/fontrepository/
---
## FontRepository class

Выполняет поиск шрифтов. Ищет среди системно установленных шрифтов и стандартных PDF‑шрифтов. Также предоставляет возможность открывать пользовательские шрифты.

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
| static [FindFont](../../aspose.pdf.text/fontrepository/findfont/#findfont_3)(string, bool) | Ищет и возвращает шрифт с указанным именем шрифта, игнорируя или учитывая регистр. |
| static [FindFont](../../aspose.pdf.text/fontrepository/findfont/#findfont_1)(string, FontStyles) | Ищет и возвращает шрифт с указанным именем шрифта и стилем шрифта. |
| static [FindFont](../../aspose.pdf.text/fontrepository/findfont/#findfont_2)(string, FontStyles, bool) | Ищет и возвращает шрифт с указанным именем шрифта и стилем шрифта, игнорируя или учитывая регистр. |
| static [LoadFonts](../../aspose.pdf.text/fontrepository/loadfonts/)() | Загружает системные шрифты и стандартные шрифты Pdf. Этот метод был разработан для ускорения процесса загрузки шрифтов. По умолчанию шрифты загружаются при первом запросе любого шрифта. Использование этого метода загружает системные и стандартные шрифты Pdf сразу перед открытием любого Pdf Document. |
| static [OpenFont](../../aspose.pdf.text/fontrepository/openfont/#openfont_1)(string) | Открывает шрифт по указанному пути к файлу шрифта. |
| static [OpenFont](../../aspose.pdf.text/fontrepository/openfont/#openfont)(Stream, FontTypes) | Открывает шрифт из указанного потока шрифта. |
| static [OpenFont](../../aspose.pdf.text/fontrepository/openfont/#openfont_2)(string, string) | Открывает шрифт по указанному пути к файлу шрифта и пути к файлу метрик. |
| static [ReloadFonts](../../aspose.pdf.text/fontrepository/reloadfonts/)() | Перезагружает все шрифты, указанные свойством [`Sources`](./sources/) |

## Примеры

Пример демонстрирует, как найти шрифт и заменить шрифт текста на первой Page.

```csharp
// Найти шрифт
Font font = FontRepository.FindFont("Arial");

// Открыть документ
Document doc = new Document(@"D:\Tests\input.pdf");

// Создайте объект TextFragmentAbsorber для поиска всех вхождений текста "hello world"
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Примите поглотитель для первой страницы
doc.Pages[1].Accept(absorber);

// Изменить шрифт первого вхождения текста
absorber.TextFragments[1].TextState.Font = font;

// Сохранить документ
doc.Save(@"D:\Tests\output.pdf"); 
```

### См. также

* class [TextFragmentAbsorber](../textfragmentabsorber/)
* class [Document](../../aspose.pdf/document/)
* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


