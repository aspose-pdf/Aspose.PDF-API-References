---
title: "FontRepository.OpenFont"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод FontRepository. Открывает шрифт с указанным потоком шрифта"
type: docs
weight: 60
url: /ru/net/aspose.pdf.text/fontrepository/openfont/
---
## OpenFont(Stream, FontTypes) {#openfont}

Открывает шрифт из указанного потока шрифта.

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
// Открыть шрифт
using (FileStream fontStream = File.OpenRead(@"C:\WINDOWS\Fonts\arial.ttf"))
{
    Font font = FontRepository.OpenFont(fontStream, , FontTypes.TTF);

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
}
```

### См. также

* class [Font](../../font/)
* enum [FontTypes](../../fonttypes/)
* class [FontRepository](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## OpenFont(string) {#openfont_1}

Открывает шрифт по указанному пути к файлу шрифта.

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
// Открыть шрифт
Font font = FontRepository.OpenFont(@"C:\WINDOWS\Fonts\arial.ttf");

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

## OpenFont(string, string) {#openfont_2}

Открывает шрифт по указанному пути к файлу шрифта и пути к файлу метрик.

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
// Открыть шрифт
Font font = FontRepository.OpenFont("courier.pfb", "courier.afm");

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


