---
title: TextFragmentAbsorber.TextFragmentAbsorber
second_title: Aspose.PDF for .NET API Reference
description: Конструктор TextFragmentAbsorber. Инициализирует новый экземпляр TextFragmentAbsorber, который выполняет поиск всех текстовых сегментов документа или страницы
type: docs
weight: 10
url: /ru/net/aspose.pdf.text/textfragmentabsorber/textfragmentabsorber/
---
## TextFragmentAbsorber() {#constructor}

Инициализирует новый экземпляр [`TextFragmentAbsorber`](../), который выполняет поиск всех текстовых сегментов документа или страницы.

```csharp
public TextFragmentAbsorber()
```

## Remarks

Выполняет поиск текста и предоставляет доступ к результатам поиска через коллекцию [`TextFragments`](../textfragments/).

## Examples

Пример демонстрирует, как найти текст на первой странице PDF-документа и заменить текст.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Find font that will be used to change document text font
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// Create TextFragmentAbsorber object
TextFragmentAbsorber absorber = new TextFragmentAbsorber();

// Make the absorber to search all "hello world" text occurrences
absorber.Phrase = "hello world";

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// Change text of the first text occurrence
absorber.TextFragments[1].Text = "hi world";

// Save document
doc.Save(@"D:\Tests\output.pdf");  
```

### See Also

* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(TextEditOptions) {#constructor_1}

Инициализирует новый экземпляр [`TextFragmentAbsorber`](../) с параметрами редактирования текста, который выполняет поиск всех текстовых сегментов документа или страницы.

```csharp
public TextFragmentAbsorber(TextEditOptions textEditOptions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| textEditOptions | TextEditOptions | Параметры редактирования текста (Позволяет включить некоторые функции редактирования). |

## Remarks

Выполняет поиск текста и предоставляет доступ к результатам поиска через коллекцию [`TextFragments`](../textfragments/).

## Examples

Пример демонстрирует, как найти все текстовые фрагменты на первой странице PDF-документа и заменить шрифт для них.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object
TextFragmentAbsorber absorber = new TextFragmentAbsorber(new TextEditOptions(TextEditOptions.FontReplace.RemoveUnusedFonts));

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// Find Courier font
Pdf.Text.Font font = FontRepository.FindFont("Courier");

// Set the font for all the text fragments
foreach (TextFragment textFragment in absorber.TextFragments)
{
    textFragment.TextState.Font = font;
}

// Save document
doc.Save(@"D:\Tests\output.pdf");
```

### See Also

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

| Parameter | Type | Description |
| --- | --- | --- |
| phrase | String | Фраза, которую ищет [`TextFragmentAbsorber`](../) |

## Remarks

Выполняет поиск текста указанной фразы и предоставляет доступ к результатам поиска через коллекцию [`TextFragments`](../textfragments/).

## Examples

Пример демонстрирует, как найти текст на первой странице PDF-документа и заменить текст и его шрифт.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Find font that will be used to change document text font
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// Change text and font of the first text occurrence
absorber.TextFragments[1].Text = "hi world";
absorber.TextFragments[1].TextState.Font = font;

// Save document
doc.Save(@"D:\Tests\output.pdf");  
```

### See Also

* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(Regex) {#constructor_6}

Инициализирует новый экземпляр класса [`TextFragmentAbsorber`](../) для указанного объекта класса System.Text.RegularExpressions.Regex.

```csharp
public TextFragmentAbsorber(Regex regex)
```

| Parameter | Type | Description |
| --- | --- | --- |
| regex | Regex | Объект класса System.Text.RegularExpressions.Regex, который ищет [`TextFragmentAbsorber`](../) |

## Remarks

Выполняет поиск текста указанной фразы и предоставляет доступ к результатам поиска через коллекцию [`TextFragments`](../textfragments/).

## Examples

Пример демонстрирует, как найти текст на первой странице PDF-документа и заменить текст и его шрифт.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Find font that will be used to change document text font
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// Create TextAbsorber object to find all instances of the input regex
TextFragmentAbsorber absorber = new TextFragmentAbsorber(new System.Text.RegularExpressions.Regex(@"h\w*?o"));

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// we should find "hello" word and replace it with "Hi"
doc.Pages[1].Accept(absorber);
absorber.TextFragments[1].Text = "Hi";

// Save document
doc.Save(@"D:\Tests\output.pdf");
```

### See Also

* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(string, TextSearchOptions) {#constructor_4}

Инициализирует новый экземпляр класса [`TextFragmentAbsorber`](../) для указанной текстовой фразы и параметров поиска текста.

```csharp
public TextFragmentAbsorber(string phrase, TextSearchOptions textSearchOptions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| phrase | String | Фраза, которую ищет [`TextFragmentAbsorber`](../) |
| textSearchOptions | TextSearchOptions | Параметры поиска текста (Позволяет включить некоторые функции поиска. Например, поиск с использованием регулярного выражения) |

## Remarks

Выполняет поиск текста указанной фразы и предоставляет доступ к результатам поиска через коллекцию [`TextFragments`](../textfragments/).

## Examples

Пример демонстрирует, как найти текст с использованием регулярного выражения на первой странице PDF-документа и заменить текст.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object that searches all words starting 'h' and ending 'o' using regular expression.
TextFragmentAbsorber absorber = new TextFragmentAbsorber(@"h\w*?o", new TextSearchOptions(true));

// we should find "hello" word and replace it with "Hi"
doc.Pages[1].Accept(absorber);
absorber.TextFragments[1].Text = "Hi"; 
 
// Save document
doc.Save(@"D:\Tests\output.pdf");  
```

### See Also

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

| Parameter | Type | Description |
| --- | --- | --- |
| regex | Regex | Объект класса System.Text.RegularExpressions.Regex, который ищет [`TextFragmentAbsorber`](../) |
| textSearchOptions | TextSearchOptions | Параметры поиска текста (Позволяет включить некоторые функции поиска.) |

## Remarks

Выполняет поиск текста указанной фразы и предоставляет доступ к результатам поиска через коллекцию [`TextFragments`](../textfragments/).

## Examples

Пример демонстрирует, как найти текст с использованием регулярного выражения на первой странице PDF-документа и заменить текст.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object that searches all words starting 'h' and ending 'o' using regular expression.
TextFragmentAbsorber absorber = new TextFragmentAbsorber(new System.Text.RegularExpressions.Regex(@"h\w*?o"), new TextSearchOptions(true));

// we should find "hello" word and replace it with "Hi"
doc.Pages[1].Accept(absorber);
absorber.TextFragments[1].Text = "Hi";

// Save document
doc.Save(@"D:\Tests\output.pdf");
```

### See Also

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

| Parameter | Type | Description |
| --- | --- | --- |
| regexes | Regex[] | Массив объектов класса System.Text.RegularExpressions.Regex, который ищет [`TextFragmentAbsorber`](../) |
| textSearchOptions | TextSearchOptions | Параметры поиска текста (Позволяет включить некоторые функции поиска.). |

## Remarks

Выполняет поиск текста указанного массива фраз и предоставляет доступ к результатам поиска через словарь [`RegexResults`](../regexresults/).

## Examples

Пример демонстрирует, как найти текст с использованием массива регулярных выражений на первой странице PDF-документа.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

var regexes = new Regex[]
{
new Regex( @"expression1", RegexOptions.IgnoreCase),
new Regex( @"expression2", RegexOptions.IgnoreCase),
};
// Create TextFragmentAbsorber object that searches all words starting 'h' and ending 'o' using regular expression.
TextFragmentAbsorber absorber = new TextFragmentAbsorber(regexes, new TextSearchOptions(true));
doc.Pages[1].Accept(absorber);
// Get results of 
var results = absorber.RegexResults;
```

### See Also

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

| Parameter | Type | Description |
| --- | --- | --- |
| phrase | String | Фраза, которую ищет [`TextFragmentAbsorber`](../) |
| textSearchOptions | TextSearchOptions | Параметры поиска текста (Позволяет включить некоторые функции поиска. Например, поиск с использованием регулярного выражения) |
| textEditOptions | TextEditOptions | Параметры редактирования текста (Позволяет включить некоторые функции редактирования). |

## Remarks

Выполняет поиск текста указанной фразы и предоставляет доступ к результатам поиска через коллекцию [`TextFragments`](../textfragments/).

## Examples

Пример демонстрирует, как найти текст с использованием регулярного выражения на первой странице PDF-документа и заменить текст.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object that searches all words starting 'h' and ending 'o' using regular expression.
TextFragmentAbsorber absorber = new TextFragmentAbsorber(@"h\w*?o", new TextSearchOptions(true));

// we should find "hello" word and replace it with "Hi"
doc.Pages[1].Accept(absorber);
absorber.TextFragments[1].Text = "Hi"; 

// Save document
doc.Save(@"D:\Tests\output.pdf");  
```

### See Also

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

| Parameter | Type | Description |
| --- | --- | --- |
| phrase | String | Фраза, которую ищет [`TextFragmentAbsorber`](../) |
| textEditOptions | TextEditOptions | Параметры редактирования текста (Позволяет включить некоторые функции редактирования). |

## Remarks

Выполняет поиск текста указанной фразы и предоставляет доступ к результатам поиска через коллекцию [`TextFragments`](../textfragments/).

### See Also

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

| Parameter | Type | Description |
| --- | --- | --- |
| regex | Regex | Объект класса System.Text.RegularExpressions.Regex, который ищет [`TextFragmentAbsorber`](../) |
| textEditOptions | TextEditOptions | Параметры редактирования текста (Позволяет включить некоторые функции редактирования). |

## Remarks

Выполняет поиск текста указанной фразы и предоставляет доступ к результатам поиска через коллекцию [`TextFragments`](../textfragments/).

### See Also

* class [TextEditOptions](../../texteditoptions/)
* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)