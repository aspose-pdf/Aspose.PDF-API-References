---
title: FindFont
second_title: Aspose.PDF для справочника API .NET
description: Ищет и возвращает шрифт с указанным именем шрифта.
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
| fontName | String | Название шрифта. |

### Возвращаемое значение

Объект шрифта.

### Примеры

В примере показано, как найти шрифт и заменить шрифт текста первой страницы.

```csharp
// Найти шрифт
Font font = FontRepository.FindFont("Arial");

// Открыть документ
Document doc = new Document(@"D:\Tests\input.pdf");

// Создаем объект TextFragmentAbsorber для поиска всех вхождений текста "hello world"
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Принять поглотитель для первой страницы
doc.Pages[1].Accept(absorber);

// Изменяем шрифт первого вхождения текста
absorber.TextFragments[1].TextState.Font = font;

// Сохранить документ
doc.Save(@"D:\Tests\output.pdf"); 
```

### Смотрите также

* class [Font](../../font)
* class [FontRepository](../../fontrepository)
* пространство имен [Aspose.Pdf.Text](../../fontrepository)
* сборка [Aspose.PDF](../../../)

---

## FindFont(string, bool) {#findfont_3}

Ищет и возвращает шрифт с указанным именем шрифта, игнорируя или учитывая чувствительность к регистру.

```csharp
public static Font FindFont(string fontName, bool ignoreCase)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fontName | String | Название шрифта. |
| ignoreCase | Boolean | чувствительность к регистру |

### Возвращаемое значение

Объект шрифта.

### Примеры

В примере показано, как найти шрифт и заменить шрифт текста первой страницы.

```csharp
// Найти шрифт
Font font = FontRepository.FindFont("Arial");

// Открыть документ
Document doc = new Document(@"D:\Tests\input.pdf");

// Создаем объект TextFragmentAbsorber для поиска всех вхождений текста "hello world"
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Принять поглотитель для первой страницы
doc.Pages[1].Accept(absorber);

// Изменяем шрифт первого вхождения текста
absorber.TextFragments[1].TextState.Font = font;

// Сохранить документ
doc.Save(@"D:\Tests\output.pdf"); 
```

### Смотрите также

* class [Font](../../font)
* class [FontRepository](../../fontrepository)
* пространство имен [Aspose.Pdf.Text](../../fontrepository)
* сборка [Aspose.PDF](../../../)

---

## FindFont(string, FontStyles) {#findfont_1}

Ищет и возвращает шрифт с указанным именем и стилем шрифта.

```csharp
public static Font FindFont(string fontFamilyName, FontStyles stl)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fontFamilyName | String | Название семейства шрифтов. |
| stl | FontStyles | Значение стиля шрифта. |

### Возвращаемое значение

Объект шрифта, соответствующий параметрам поискового запроса.

### Примеры

В примере показано, как найти шрифт и заменить шрифт текста первой страницы.

```csharp
// Найти шрифт
Font font = FontRepository.FindFont("Arial", FontStyle.Italic);

// Открыть документ
Document doc = new Document(@"D:\Tests\input.pdf");

// Создаем объект TextFragmentAbsorber для поиска всех вхождений текста "hello world"
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Принять поглотитель для первой страницы
doc.Pages[1].Accept(absorber);

// Изменяем шрифт первого вхождения текста
absorber.TextFragments[1].TextState.Font = font;

// Сохранить документ
doc.Save(@"D:\Tests\output.pdf"); 
```

### Смотрите также

* class [Font](../../font)
* enum [FontStyles](../../fontstyles)
* class [FontRepository](../../fontrepository)
* пространство имен [Aspose.Pdf.Text](../../fontrepository)
* сборка [Aspose.PDF](../../../)

---

## FindFont(string, FontStyles, bool) {#findfont_2}

Ищет и возвращает шрифт с указанным именем шрифта и стилем шрифта игнорируя или учитывая чувствительность к регистру.

```csharp
public static Font FindFont(string fontFamilyName, FontStyles stl, bool ignoreCase)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fontFamilyName | String | Название семейства шрифтов. |
| stl | FontStyles | Значение стиля шрифта. |
| ignoreCase | Boolean | чувствительность к регистру |

### Возвращаемое значение

Объект шрифта, соответствующий параметрам поискового запроса.

### Примеры

В примере показано, как найти шрифт и заменить шрифт текста первой страницы.

```csharp
// Найти шрифт
Font font = FontRepository.FindFont("Arial", FontStyle.Italic);

// Открыть документ
Document doc = new Document(@"D:\Tests\input.pdf");

// Создаем объект TextFragmentAbsorber для поиска всех вхождений текста "hello world"
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Принять поглотитель для первой страницы
doc.Pages[1].Accept(absorber);

// Изменяем шрифт первого вхождения текста
absorber.TextFragments[1].TextState.Font = font;

// Сохранить документ
doc.Save(@"D:\Tests\output.pdf"); 
```

### Смотрите также

* class [Font](../../font)
* enum [FontStyles](../../fontstyles)
* class [FontRepository](../../fontrepository)
* пространство имен [Aspose.Pdf.Text](../../fontrepository)
* сборка [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
