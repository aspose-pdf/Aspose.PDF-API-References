---
title: "TextFragmentAbsorber.TextFragmentAbsorber"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Конструктор TextFragmentAbsorber. Инициализирует новый экземпляр TextFragmentAbsorber, который выполняет поиск всех текстовых сегментов документа или страницы."
type: docs
weight: 10
url: /ru/net/aspose.pdf.text/textfragmentabsorber/textfragmentabsorber/
---
## TextFragmentAbsorber() {#constructor}

Инициализирует новый экземпляр [`TextFragmentAbsorber`](../), который выполняет поиск всех текстовых сегментов документа или страницы.

```csharp
public TextFragmentAbsorber()
```

## Примечания

Выполняет поиск текста и предоставляет доступ к результатам поиска через коллекцию [`TextFragments`](../textfragments/).

## Примеры

Пример демонстрирует, как найти текст на первой странице PDF‑документа и заменить его.

```csharp
// Открыть документ
Document doc = new Document(@"D:\Tests\input.pdf");

// Найдите шрифт, который будет использоваться для изменения шрифта текста документа
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// Создайте объект TextFragmentAbsorber
TextFragmentAbsorber absorber = new TextFragmentAbsorber();

// Заставьте абсорбер искать все вхождения текста "hello world"
absorber.Phrase = "hello world";

// Примите поглотитель для первой страницы
doc.Pages[1].Accept(absorber);

// Измените текст первого вхождения
absorber.TextFragments[1].Text = "hi world";

// Сохранить документ
doc.Save(@"D:\Tests\output.pdf");  
```

### См. также

* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(TextEditOptions) {#constructor_1}

Инициализирует новый экземпляр [`TextFragmentAbsorber`](../) с параметрами редактирования текста, который выполняет поиск всех текстовых сегментов документа или страницы.

```csharp
public TextFragmentAbsorber(TextEditOptions textEditOptions)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| textEditOptions | TextEditOptions | Параметры редактирования текста (Позволяют включать некоторые функции редактирования). |

## Примечания

Выполняет поиск текста и предоставляет доступ к результатам поиска через коллекцию [`TextFragments`](../textfragments/).

## Примеры

В примере демонстрируется, как найти все фрагменты текста на первой странице PDF‑документа и заменить шрифт для них.

```csharp
// Открыть документ
Document doc = new Document(@"D:\Tests\input.pdf");

// Создайте объект TextFragmentAbsorber
TextFragmentAbsorber absorber = new TextFragmentAbsorber(new TextEditOptions(TextEditOptions.FontReplace.RemoveUnusedFonts));

// Примите поглотитель для первой страницы
doc.Pages[1].Accept(absorber);

// Найти шрифт Courier
Pdf.Text.Font font = FontRepository.FindFont("Courier");

// Установить шрифт для всех фрагментов текста
foreach (TextFragment textFragment in absorber.TextFragments)
{
    textFragment.TextState.Font = font;
}

// Сохранить документ
doc.Save(@"D:\Tests\output.pdf");
```

### См. также

* class [TextEditOptions](../../texteditoptions/)
* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(string) {#constructor_2}

Инициализирует новый экземпляр класса [`TextFragmentAbsorber`](../) для указанной текстовой фразы.

```csharp
public TextFragmentAbsorber(string phrase)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| phrase | String | Фраза, которую ищет [`TextFragmentAbsorber`](../). |

## Примечания

Выполняет поиск текста указанной фразы и предоставляет доступ к результатам поиска через коллекцию [`TextFragments`](../textfragments/).

## Примеры

Пример демонстрирует, как найти текст на первой странице PDF‑документа и заменить текст и его шрифт.

```csharp
// Открыть документ
Document doc = new Document(@"D:\Tests\input.pdf");

// Найдите шрифт, который будет использоваться для изменения шрифта текста документа
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// Создайте объект TextFragmentAbsorber для поиска всех вхождений текста "hello world"
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Примите поглотитель для первой страницы
doc.Pages[1].Accept(absorber);

// Измените текст и шрифт первого вхождения текста
absorber.TextFragments[1].Text = "hi world";
absorber.TextFragments[1].TextState.Font = font;

// Сохранить документ
doc.Save(@"D:\Tests\output.pdf");  
```

### См. также

* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(Regex) {#constructor_6}

Инициализирует новый экземпляр класса [`TextFragmentAbsorber`](../) для указанного объекта класса System.Text.RegularExpressions.Regex.

```csharp
public TextFragmentAbsorber(Regex regex)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| regex | Regex | Объект класса System.Text.RegularExpressions.Regex, который ищет [`TextFragmentAbsorber`](../). |

## Примечания

Выполняет поиск текста указанной фразы и предоставляет доступ к результатам поиска через коллекцию [`TextFragments`](../textfragments/).

## Примеры

Пример демонстрирует, как найти текст на первой странице PDF‑документа и заменить текст и его шрифт.

```csharp
// Открыть документ
Document doc = new Document(@"D:\Tests\input.pdf");

// Найдите шрифт, который будет использоваться для изменения шрифта текста документа
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// Создайте объект TextAbsorber, чтобы найти все вхождения входного регулярного выражения.
TextFragmentAbsorber absorber = new TextFragmentAbsorber(new System.Text.RegularExpressions.Regex(@"h\w*?o"));

// Примите поглотитель для первой страницы
doc.Pages[1].Accept(absorber);

// Мы должны найти слово "hello" и заменить его на "Hi".
doc.Pages[1].Accept(absorber);
absorber.TextFragments[1].Text = "Hi";

// Сохранить документ
doc.Save(@"D:\Tests\output.pdf");
```

### См. также

* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(string, TextSearchOptions) {#constructor_4}

Инициализирует новый экземпляр класса [`TextFragmentAbsorber`](../) для указанной текстовой фразы и параметров поиска текста.

```csharp
public TextFragmentAbsorber(string phrase, TextSearchOptions textSearchOptions)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| phrase | String | Фраза, которую ищет [`TextFragmentAbsorber`](../). |
| textSearchOptions | TextSearchOptions | Параметры поиска текста (Позволяют включать некоторые функции поиска. Например, поиск с использованием регулярных выражений). |

## Примечания

Выполняет поиск текста указанной фразы и предоставляет доступ к результатам поиска через коллекцию [`TextFragments`](../textfragments/).

## Примеры

В примере демонстрируется, как найти текст с помощью регулярного выражения на первой странице PDF‑документа и заменить его.

```csharp
// Открыть документ
Document doc = new Document(@"D:\Tests\input.pdf");

// Создайте объект TextFragmentAbsorber, который ищет все слова, начинающиеся на 'h' и заканчивающиеся на 'o', используя регулярное выражение.
TextFragmentAbsorber absorber = new TextFragmentAbsorber(@"h\w*?o", new TextSearchOptions(true));

// Мы должны найти слово "hello" и заменить его на "Hi".
doc.Pages[1].Accept(absorber);
absorber.TextFragments[1].Text = "Hi"; 
 
// Сохранить документ
doc.Save(@"D:\Tests\output.pdf");  
```

### См. также

* class [TextSearchOptions](../../textsearchoptions/)
* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(Regex, TextSearchOptions) {#constructor_8}

Инициализирует новый экземпляр класса [`TextFragmentAbsorber`](../) для указанной текстовой фразы и параметров поиска текста.

```csharp
public TextFragmentAbsorber(Regex regex, TextSearchOptions textSearchOptions)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| regex | Regex | Объект класса System.Text.RegularExpressions.Regex, который ищет [`TextFragmentAbsorber`](../). |
| textSearchOptions | TextSearchOptions | Параметры поиска текста (Позволяют включать некоторые функции поиска.) |

## Примечания

Выполняет поиск текста указанной фразы и предоставляет доступ к результатам поиска через коллекцию [`TextFragments`](../textfragments/).

## Примеры

В примере демонстрируется, как найти текст с помощью регулярного выражения на первой странице PDF‑документа и заменить его.

```csharp
// Открыть документ
Document doc = new Document(@"D:\Tests\input.pdf");

// Создайте объект TextFragmentAbsorber, который ищет все слова, начинающиеся на 'h' и заканчивающиеся на 'o', используя регулярное выражение.
TextFragmentAbsorber absorber = new TextFragmentAbsorber(new System.Text.RegularExpressions.Regex(@"h\w*?o"), new TextSearchOptions(true));

// Мы должны найти слово "hello" и заменить его на "Hi".
doc.Pages[1].Accept(absorber);
absorber.TextFragments[1].Text = "Hi";

// Сохранить документ
doc.Save(@"D:\Tests\output.pdf");
```

### См. также

* class [TextSearchOptions](../../textsearchoptions/)
* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(Regex[], TextSearchOptions) {#constructor_9}

Инициализирует новый экземпляр класса [`TextFragmentAbsorber`](../) для указанной текстовой фразы и параметров поиска текста.

```csharp
public TextFragmentAbsorber(Regex[] regexes, TextSearchOptions textSearchOptions)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| regexes | Regex[] | Массив объектов класса System.Text.RegularExpressions.Regex, которые ищет [`TextFragmentAbsorber`](../). |
| textSearchOptions | TextSearchOptions | Параметры поиска текста (Позволяют включать некоторые функции поиска.). |

## Примечания

Выполняет поиск текста указанного массива фраз и предоставляет доступ к результатам поиска через словарь [`RegexResults`](../regexresults/).

## Примеры

В примере демонстрируется, как найти текст с помощью массива регулярных выражений на первой странице PDF‑документа.

```csharp
// Открыть документ
Document doc = new Document(@"D:\Tests\input.pdf");

var regexes = new Regex[]
{
new Regex( @"expression1", RegexOptions.IgnoreCase),
new Regex( @"expression2", RegexOptions.IgnoreCase),
};
// Создайте объект TextFragmentAbsorber, который ищет все слова, начинающиеся на 'h' и заканчивающиеся на 'o', используя регулярное выражение.
TextFragmentAbsorber absorber = new TextFragmentAbsorber(regexes, new TextSearchOptions(true));
doc.Pages[1].Accept(absorber);
// Получить результаты 
var results = absorber.RegexResults;
```

### См. также

* class [TextSearchOptions](../../textsearchoptions/)
* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(string, TextSearchOptions, TextEditOptions) {#constructor_5}

Инициализирует новый экземпляр класса [`TextFragmentAbsorber`](../) для указанной текстовой фразы, параметров поиска текста и параметров редактирования текста.

```csharp
public TextFragmentAbsorber(string phrase, TextSearchOptions textSearchOptions, 
    TextEditOptions textEditOptions)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| phrase | String | Фраза, которую ищет [`TextFragmentAbsorber`](../). |
| textSearchOptions | TextSearchOptions | Параметры поиска текста (Позволяют включать некоторые функции поиска. Например, поиск с использованием регулярных выражений). |
| textEditOptions | TextEditOptions | Параметры редактирования текста (Позволяют включать некоторые функции редактирования). |

## Примечания

Выполняет поиск текста указанной фразы и предоставляет доступ к результатам поиска через коллекцию [`TextFragments`](../textfragments/).

## Примеры

В примере демонстрируется, как найти текст с помощью регулярного выражения на первой странице PDF‑документа и заменить его.

```csharp
// Открыть документ
Document doc = new Document(@"D:\Tests\input.pdf");

// Создайте объект TextFragmentAbsorber, который ищет все слова, начинающиеся на 'h' и заканчивающиеся на 'o', используя регулярное выражение.
TextFragmentAbsorber absorber = new TextFragmentAbsorber(@"h\w*?o", new TextSearchOptions(true));

// Мы должны найти слово "hello" и заменить его на "Hi".
doc.Pages[1].Accept(absorber);
absorber.TextFragments[1].Text = "Hi"; 

// Сохранить документ
doc.Save(@"D:\Tests\output.pdf");  
```

### См. также

* class [TextSearchOptions](../../textsearchoptions/)
* class [TextEditOptions](../../texteditoptions/)
* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(string, TextEditOptions) {#constructor_3}

Инициализирует новый экземпляр класса [`TextFragmentAbsorber`](../) для указанной текстовой фразы и параметров редактирования текста.

```csharp
public TextFragmentAbsorber(string phrase, TextEditOptions textEditOptions)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| phrase | String | Фраза, которую ищет [`TextFragmentAbsorber`](../). |
| textEditOptions | TextEditOptions | Параметры редактирования текста (Позволяют включать некоторые функции редактирования). |

## Примечания

Выполняет поиск текста указанной фразы и предоставляет доступ к результатам поиска через коллекцию [`TextFragments`](../textfragments/).

### См. также

* class [TextEditOptions](../../texteditoptions/)
* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(Regex, TextEditOptions) {#constructor_7}

Инициализирует новый экземпляр класса [`TextFragmentAbsorber`](../) для указанной текстовой фразы и параметров редактирования текста.

```csharp
public TextFragmentAbsorber(Regex regex, TextEditOptions textEditOptions)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| regex | Regex | Объект класса System.Text.RegularExpressions.Regex, который ищет [`TextFragmentAbsorber`](../). |
| textEditOptions | TextEditOptions | Параметры редактирования текста (Позволяют включать некоторые функции редактирования). |

## Примечания

Выполняет поиск текста указанной фразы и предоставляет доступ к результатам поиска через коллекцию [`TextFragments`](../textfragments/).

### См. также

* class [TextEditOptions](../../texteditoptions/)
* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


