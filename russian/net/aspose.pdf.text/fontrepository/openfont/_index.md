---
title: FontRepository.OpenFont
second_title: Aspose.PDF for .NET API Reference
description: Метод FontRepository. Открывает шрифт с указанным потоком шрифта
type: docs
weight: 60
url: /ru/net/aspose.pdf.text/fontrepository/openfont/
---
## OpenFont(Stream, FontTypes) {#openfont}

Открывает шрифт с указанным потоком шрифта.

```csharp
public static Font OpenFont(Stream fontStream, FontTypes fontType)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fontStream | Stream | Поток шрифта. |
| fontType | FontTypes | Значение типа шрифта. |

### Возвращаемое значение

Объект шрифта.

## Примеры

Пример демонстрирует, как открыть шрифт и заменить шрифт текста на первой странице.

```csharp
// Open font
using (FileStream fontStream = File.OpenRead(@"C:\WINDOWS\Fonts\arial.ttf"))
{
    Font font = FontRepository.OpenFont(fontStream, , FontTypes.TTF);

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
}
```

### См. также

* класс [Font](../../font/)
* перечисление [FontTypes](../../fonttypes/)
* класс [FontRepository](../)
* пространство имен [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* сборка [Aspose.PDF](../../../)

---

## OpenFont(string) {#openfont_1}

Открывает шрифт с указанным путем к файлу шрифта.

```csharp
public static Font OpenFont(string fontFilePath)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fontFilePath | String | Путь к файлу шрифта. |

### Возвращаемое значение

Объект шрифта.

## Примеры

Пример демонстрирует, как открыть шрифт и заменить шрифт текста на первой странице.

```csharp
// Open font
Font font = FontRepository.OpenFont(@"C:\WINDOWS\Fonts\arial.ttf");

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

* класс [Font](../../font/)
* класс [FontRepository](../)
* пространство имен [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* сборка [Aspose.PDF](../../../)

---

## OpenFont(string, string) {#openfont_2}

Открывает шрифт с указанным путем к файлу шрифта и путем к файлу метрик.

```csharp
public static Font OpenFont(string fontFilePath, string metricsFilePath)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fontFilePath | String | Путь к файлу шрифта. |
| metricsFilePath | String | Путь к файлу метрик шрифта. |

### Возвращаемое значение

Объект шрифта.

## Примеры

Пример демонстрирует, как открыть шрифт Type1 с метриками и заменить шрифт текста на первой странице.

```csharp
// Open font
Font font = FontRepository.OpenFont("courier.pfb", "courier.afm");

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

* класс [Font](../../font/)
* класс [FontRepository](../)
* пространство имен [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* сборка [Aspose.PDF](../../../)