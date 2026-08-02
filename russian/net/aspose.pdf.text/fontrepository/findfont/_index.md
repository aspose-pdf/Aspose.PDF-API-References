---
title: "FontRepository.FindFont"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод FontRepository. Ищет и возвращает шрифт с указанным именем"
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

* class [Font](../../font/)
* class [FontRepository](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## FindFont(string, bool) {#findfont_3}

Ищет и возвращает шрифт с указанным именем шрифта, игнорируя или учитывая регистр.

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

* class [Font](../../font/)
* class [FontRepository](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## FindFont(string, FontStyles) {#findfont_1}

Ищет и возвращает шрифт с указанным именем шрифта и стилем шрифта.

```csharp
public static Font FindFont(string fontFamilyName, FontStyles stl)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fontFamilyName | String | Имя семейства шрифта. |
| stl | FontStyles | Значение стиля шрифта. |

### Возвращаемое значение

Объект шрифта, соответствующий параметрам поискового запроса.

## Примеры

Пример демонстрирует, как найти шрифт и заменить шрифт текста на первой Page.

```csharp
// Найти шрифт
Font font = FontRepository.FindFont("Arial", FontStyle.Italic);

// Открыть документ
Document doc = new Document(@"D:\Tests\input.pdf");

// Создайте объект TextFragmentAbsorber, чтобы найти все вхождения текста "hello world"
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Примите поглотитель для первой страницы
doc.Pages[1].Accept(absorber);

// Измените шрифт первого вхождения текста
absorber.TextFragments[1].TextState.Font = font;

// Сохранить документ
doc.Save(@"D:\Tests\output.pdf"); 
```

### См. также

* class [Font](../../font/)
* enum [FontStyles](../../fontstyles/)
* class [FontRepository](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## FindFont(string, FontStyles, bool) {#findfont_2}

Ищет и возвращает шрифт с указанным именем шрифта и стилем шрифта, игнорируя или учитывая регистр.

```csharp
public static Font FindFont(string fontFamilyName, FontStyles stl, bool ignoreCase)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fontFamilyName | String | Имя семейства шрифта. |
| stl | FontStyles | Значение стиля шрифта. |
| ignoreCase | Boolean | чувствительность к регистру |

### Возвращаемое значение

Объект шрифта, соответствующий параметрам поискового запроса.

## Примеры

Пример демонстрирует, как найти шрифт и заменить шрифт текста на первой Page.

```csharp
// Найти шрифт
Font font = FontRepository.FindFont("Arial", FontStyle.Italic);

// Открыть документ
Document doc = new Document(@"D:\Tests\input.pdf");

// Создайте объект TextFragmentAbsorber, чтобы найти все вхождения текста "hello world"
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Примите поглотитель для первой страницы
doc.Pages[1].Accept(absorber);

// Измените шрифт первого вхождения текста
absorber.TextFragments[1].TextState.Font = font;

// Сохранить документ
doc.Save(@"D:\Tests\output.pdf"); 
```

### См. также

* class [Font](../../font/)
* enum [FontStyles](../../fontstyles/)
* class [FontRepository](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


