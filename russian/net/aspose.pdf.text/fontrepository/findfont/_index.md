---
title: FontRepository.FindFont
second_title: Aspose.PDF for .NET API Reference
description: Метод FontRepository. Ищет и возвращает шрифт с указанным именем шрифта
type: docs
weight: 40
url: /ru/net/aspose.pdf.text/fontrepository/findfont/
---
## FindFont(string) {#findfont}

Ищет и возвращает шрифт с указанным именем шрифта.

```csharp
public static Font FindFont(string fontName)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fontName | String | Имя шрифта. |

### Возвращаемое значение

Объект шрифта.

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

* класс [Font](../../font/)
* класс [FontRepository](../)
* пространство имен [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* сборка [Aspose.PDF](../../../)

---

## FindFont(string, bool) {#findfont_3}

Ищет и возвращает шрифт с указанным именем шрифта, игнорируя или учитывая чувствительность к регистру.

```csharp
public static Font FindFont(string fontName, bool ignoreCase)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fontName | String | Имя шрифта. |
| ignoreCase | Boolean | чувствительность к регистру |

### Возвращаемое значение

Объект шрифта.

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

* класс [Font](../../font/)
* класс [FontRepository](../)
* пространство имен [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* сборка [Aspose.PDF](../../../)

---

## FindFont(string, FontStyles) {#findfont_1}

Ищет и возвращает шрифт с указанным именем шрифта и стилем шрифта.

```csharp
public static Font FindFont(string fontFamilyName, FontStyles stl)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fontFamilyName | String | Имя семейства шрифтов. |
| stl | FontStyles | Значение стиля шрифта. |

### Возвращаемое значение

Объект шрифта, соответствующий параметрам запроса поиска.

## Примеры

Пример демонстрирует, как найти шрифт и заменить шрифт текста на первой странице.

```csharp
// Find font
Font font = FontRepository.FindFont("Arial", FontStyle.Italic);

// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object to find all "hello world" text occurences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// Change font of the first text occurence
absorber.TextFragments[1].TextState.Font = font;

// Save document
doc.Save(@"D:\Tests\output.pdf"); 
```

### См. также

* класс [Font](../../font/)
* перечисление [FontStyles](../../fontstyles/)
* класс [FontRepository](../)
* пространство имен [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* сборка [Aspose.PDF](../../../)

---

## FindFont(string, FontStyles, bool) {#findfont_2}

Ищет и возвращает шрифт с указанным именем шрифта и стилем шрифта, игнорируя или учитывая чувствительность к регистру.

```csharp
public static Font FindFont(string fontFamilyName, FontStyles stl, bool ignoreCase)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fontFamilyName | String | Имя семейства шрифтов. |
| stl | FontStyles | Значение стиля шрифта. |
| ignoreCase | Boolean | чувствительность к регистру |

### Возвращаемое значение

Объект шрифта, соответствующий параметрам запроса поиска.

## Примеры

Пример демонстрирует, как найти шрифт и заменить шрифт текста на первой странице.

```csharp
// Find font
Font font = FontRepository.FindFont("Arial", FontStyle.Italic);

// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object to find all "hello world" text occurences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// Change font of the first text occurence
absorber.TextFragments[1].TextState.Font = font;

// Save document
doc.Save(@"D:\Tests\output.pdf"); 
```

### См. также

* класс [Font](../../font/)
* перечисление [FontStyles](../../fontstyles/)
* класс [FontRepository](../)
* пространство имен [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* сборка [Aspose.PDF](../../../)