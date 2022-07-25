---
title: TextFragmentAbsorber
second_title: Aspose.PDF для справочника API .NET
description: Инициализирует новый экземплярTextFragmentAbsorberaspose.pdf.text/textfragmentabsorber который выполняет поиск всех текстовых сегментов документа или страницы.
type: docs
weight: 10
url: /ru/net/aspose.pdf.text/textfragmentabsorber/textfragmentabsorber/
---
## TextFragmentAbsorber() {#constructor}

Инициализирует новый экземпляр[`TextFragmentAbsorber`](../../textfragmentabsorber) который выполняет поиск всех текстовых сегментов документа или страницы.

```csharp
public TextFragmentAbsorber()
```

### Примечания

Выполняет текстовый поиск и предоставляет доступ к результатам поиска через[`TextFragments`](../textfragments) коллекция.

### Примеры

В примере показано, как найти текст на первой странице документа PDF и заменить текст.

```csharp
// Открыть документ
Document doc = new Document(@"D:\Tests\input.pdf");

// Находим шрифт, который будет использоваться для изменения шрифта текста документа
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// Создаем объект TextFragmentAbsorber
TextFragmentAbsorber absorber = new TextFragmentAbsorber();

// Заставляем поглотитель искать все вхождения текста "hello world"
absorber.Phrase = "hello world";

// Принять поглотитель для первой страницы
doc.Pages[1].Accept(absorber);

// Изменяем текст первого вхождения текста
absorber.TextFragments[1].Text = "hi world";

// Сохранить документ
doc.Save(@"D:\Tests\output.pdf");  
```

### Смотрите также

* class [TextFragmentAbsorber](../../textfragmentabsorber)
* пространство имен [Aspose.Pdf.Text](../../textfragmentabsorber)
* сборка [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(TextEditOptions) {#constructor_1}

Инициализирует новый экземпляр[`TextFragmentAbsorber`](../../textfragmentabsorber)с опциями редактирования текста, выполняющими поиск по всем текстовым сегментам документа или страницы.

```csharp
public TextFragmentAbsorber(TextEditOptions textEditOptions)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| textEditOptions | TextEditOptions | Параметры редактирования текста (позволяет включить некоторые функции редактирования). |

### Примечания

Выполняет текстовый поиск и предоставляет доступ к результатам поиска через[`TextFragments`](../textfragments) коллекция.

### Примеры

В примере показано, как найти все текстовые фрагменты на первой странице PDF-документа и заменить для них шрифт.

```csharp
// Открыть документ
Document doc = new Document(@"D:\Tests\input.pdf");

// Создаем объект TextFragmentAbsorber
TextFragmentAbsorber absorber = new TextFragmentAbsorber(new TextEditOptions(TextEditOptions.FontReplace.RemoveUnusedFonts));

// Принять поглотитель для первой страницы
doc.Pages[1].Accept(absorber);

// Находим шрифт Courier
Pdf.Text.Font font = FontRepository.FindFont("Courier");

// Установить шрифт для всех текстовых фрагментов
foreach (TextFragment textFragment in absorber.TextFragments)
{
    textFragment.TextState.Font = font;
}

// Сохранить документ
doc.Save(@"D:\Tests\output.pdf");
```

### Смотрите также

* class [TextEditOptions](../../texteditoptions)
* class [TextFragmentAbsorber](../../textfragmentabsorber)
* пространство имен [Aspose.Pdf.Text](../../textfragmentabsorber)
* сборка [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(string) {#constructor_2}

Инициализирует новый экземпляр[`TextFragmentAbsorber`](../../textfragmentabsorber) класс для указанной текстовой фразы.

```csharp
public TextFragmentAbsorber(string phrase)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| phrase | String | Фраза о том, что[`TextFragmentAbsorber`](../../textfragmentabsorber) поиски |

### Примечания

Выполняет текстовый поиск по указанной фразе и предоставляет доступ к результатам поиска через[`TextFragments`](../textfragments) коллекция.

### Примеры

Пример демонстрирует, как найти текст на первой странице документа PDF и заменить текст и его шрифт.

```csharp
// Открыть документ
Document doc = new Document(@"D:\Tests\input.pdf");

// Находим шрифт, который будет использоваться для изменения шрифта текста документа
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// Создаем объект TextFragmentAbsorber для поиска всех вхождений текста "hello world"
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Принять поглотитель для первой страницы
doc.Pages[1].Accept(absorber);

// Изменяем текст и шрифт первого вхождения текста
absorber.TextFragments[1].Text = "hi world";
absorber.TextFragments[1].TextState.Font = font;

// Сохранить документ
doc.Save(@"D:\Tests\output.pdf");  
```

### Смотрите также

* class [TextFragmentAbsorber](../../textfragmentabsorber)
* пространство имен [Aspose.Pdf.Text](../../textfragmentabsorber)
* сборка [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(Regex) {#constructor_6}

Инициализирует новый экземпляр[`TextFragmentAbsorber`](../../textfragmentabsorber) класс для указанного объекта класса System.Text.RegularExpressions.Regex.

```csharp
public TextFragmentAbsorber(Regex regex)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| regex | Regex | Объект класса System.Text.RegularExpressions.Regex, который[`TextFragmentAbsorber`](../../textfragmentabsorber) поиски |

### Примечания

Выполняет текстовый поиск по указанной фразе и предоставляет доступ к результатам поиска через[`TextFragments`](../textfragments) коллекция.

### Примеры

Пример демонстрирует, как найти текст на первой странице документа PDF и заменить текст и его шрифт.

```csharp
// Открыть документ
Document doc = new Document(@"D:\Tests\input.pdf");

// Находим шрифт, который будет использоваться для изменения шрифта текста документа
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// Создаем объект TextAbsorber, чтобы найти все экземпляры входного регулярного выражения
TextFragmentAbsorber absorber = new TextFragmentAbsorber(new System.Text.RegularExpressions.Regex(@"h\w*?o"));

// Принять поглотитель для первой страницы
doc.Pages[1].Accept(absorber);

// мы должны найти слово "hello" и заменить его на "Hi"
doc.Pages[1].Accept(absorber);
absorber.TextFragments[1].Text = "Hi";

// Сохранить документ
doc.Save(@"D:\Tests\output.pdf");
```

### Смотрите также

* class [TextFragmentAbsorber](../../textfragmentabsorber)
* пространство имен [Aspose.Pdf.Text](../../textfragmentabsorber)
* сборка [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(string, TextSearchOptions) {#constructor_4}

Инициализирует новый экземпляр[`TextFragmentAbsorber`](../../textfragmentabsorber)класс для указанной текстовой фразы и опций текстового поиска.

```csharp
public TextFragmentAbsorber(string phrase, TextSearchOptions textSearchOptions)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| phrase | String | Фраза о том, что[`TextFragmentAbsorber`](../../textfragmentabsorber) поиски |
| textSearchOptions | TextSearchOptions | Параметры текстового поиска (позволяет включить некоторые функции поиска. Например, поиск по регулярному выражению) |

### Примечания

Выполняет текстовый поиск по указанной фразе и предоставляет доступ к результатам поиска через[`TextFragments`](../textfragments) коллекция.

### Примеры

В примере показано, как найти текст с помощью регулярного выражения на первой странице документа PDF и заменить текст.

```csharp
// Открыть документ
Document doc = new Document(@"D:\Tests\input.pdf");

// Создаем объект TextFragmentAbsorber, который ищет все слова, начинающиеся с «h» и заканчивающиеся на «o», используя регулярное выражение.
TextFragmentAbsorber absorber = new TextFragmentAbsorber(@"h\w*?o", new TextSearchOptions(true));

// мы должны найти слово "hello" и заменить его на "Hi"
doc.Pages[1].Accept(absorber);
absorber.TextFragments[1].Text = "Hi"; 
 
// Сохранить документ
doc.Save(@"D:\Tests\output.pdf");  
```

### Смотрите также

* class [TextSearchOptions](../../textsearchoptions)
* class [TextFragmentAbsorber](../../textfragmentabsorber)
* пространство имен [Aspose.Pdf.Text](../../textfragmentabsorber)
* сборка [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(Regex, TextSearchOptions) {#constructor_8}

Инициализирует новый экземпляр[`TextFragmentAbsorber`](../../textfragmentabsorber) класс для указанной текстовой фразы и опций текстового поиска.

```csharp
public TextFragmentAbsorber(Regex regex, TextSearchOptions textSearchOptions)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| regex | Regex | Объект класса System.Text.RegularExpressions.Regex, который[`TextFragmentAbsorber`](../../textfragmentabsorber) поиски |
| textSearchOptions | TextSearchOptions | Параметры текстового поиска (позволяет включить некоторые функции поиска.) |

### Примечания

Выполняет текстовый поиск по указанной фразе и предоставляет доступ к результатам поиска через[`TextFragments`](../textfragments) коллекция.

### Примеры

В примере показано, как найти текст с помощью регулярного выражения на первой странице документа PDF и заменить текст.

```csharp
// Открыть документ
Document doc = new Document(@"D:\Tests\input.pdf");

// Создаем объект TextFragmentAbsorber, который ищет все слова, начинающиеся с «h» и заканчивающиеся на «o», используя регулярное выражение.
TextFragmentAbsorber absorber = new TextFragmentAbsorber(new System.Text.RegularExpressions.Regex(@"h\w*?o"), new TextSearchOptions(true));

// мы должны найти слово "hello" и заменить его на "Hi"
doc.Pages[1].Accept(absorber);
absorber.TextFragments[1].Text = "Hi";

// Сохранить документ
doc.Save(@"D:\Tests\output.pdf");
```

### Смотрите также

* class [TextSearchOptions](../../textsearchoptions)
* class [TextFragmentAbsorber](../../textfragmentabsorber)
* пространство имен [Aspose.Pdf.Text](../../textfragmentabsorber)
* сборка [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(string, TextSearchOptions, TextEditOptions) {#constructor_5}

Инициализирует новый экземпляр[`TextFragmentAbsorber`](../../textfragmentabsorber) класс для указанной текстовой фразы, параметров поиска текста и параметров редактирования текста.

```csharp
public TextFragmentAbsorber(string phrase, TextSearchOptions textSearchOptions, 
    TextEditOptions textEditOptions)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| phrase | String | Фраза о том, что[`TextFragmentAbsorber`](../../textfragmentabsorber) поиски |
| textSearchOptions | TextSearchOptions | Параметры текстового поиска (позволяет включить некоторые функции поиска. Например, поиск по регулярному выражению) |
| textEditOptions | TextEditOptions | Параметры редактирования текста (позволяет включить некоторые функции редактирования). |

### Примечания

Выполняет текстовый поиск по указанной фразе и предоставляет доступ к результатам поиска через[`TextFragments`](../textfragments) коллекция.

### Примеры

В примере показано, как найти текст с помощью регулярного выражения на первой странице документа PDF и заменить текст.

```csharp
// Открыть документ
Document doc = new Document(@"D:\Tests\input.pdf");

// Создаем объект TextFragmentAbsorber, который ищет все слова, начинающиеся с «h» и заканчивающиеся на «o», используя регулярное выражение.
TextFragmentAbsorber absorber = new TextFragmentAbsorber(@"h\w*?o", new TextSearchOptions(true));

// мы должны найти слово "hello" и заменить его на "Hi"
doc.Pages[1].Accept(absorber);
absorber.TextFragments[1].Text = "Hi"; 

// Сохранить документ
doc.Save(@"D:\Tests\output.pdf");  
```

### Смотрите также

* class [TextSearchOptions](../../textsearchoptions)
* class [TextEditOptions](../../texteditoptions)
* class [TextFragmentAbsorber](../../textfragmentabsorber)
* пространство имен [Aspose.Pdf.Text](../../textfragmentabsorber)
* сборка [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(string, TextEditOptions) {#constructor_3}

Инициализирует новый экземпляр[`TextFragmentAbsorber`](../../textfragmentabsorber) класс для указанной текстовой фразы и параметров редактирования текста.

```csharp
public TextFragmentAbsorber(string phrase, TextEditOptions textEditOptions)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| phrase | String | Фраза о том, что[`TextFragmentAbsorber`](../../textfragmentabsorber) поиски |
| textEditOptions | TextEditOptions | Параметры редактирования текста (позволяет включить некоторые функции редактирования). |

### Примечания

Выполняет текстовый поиск по указанной фразе и предоставляет доступ к результатам поиска через[`TextFragments`](../textfragments) коллекция.

### Смотрите также

* class [TextEditOptions](../../texteditoptions)
* class [TextFragmentAbsorber](../../textfragmentabsorber)
* пространство имен [Aspose.Pdf.Text](../../textfragmentabsorber)
* сборка [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(Regex, TextEditOptions) {#constructor_7}

Инициализирует новый экземпляр[`TextFragmentAbsorber`](../../textfragmentabsorber) класс для указанной текстовой фразы и параметров редактирования текста.

```csharp
public TextFragmentAbsorber(Regex regex, TextEditOptions textEditOptions)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| regex | Regex | Объект класса System.Text.RegularExpressions.Regex, который[`TextFragmentAbsorber`](../../textfragmentabsorber) поиски |
| textEditOptions | TextEditOptions | Параметры редактирования текста (позволяет включить некоторые функции редактирования). |

### Примечания

Выполняет текстовый поиск по указанной фразе и предоставляет доступ к результатам поиска через[`TextFragments`](../textfragments) коллекция.

### Смотрите также

* class [TextEditOptions](../../texteditoptions)
* class [TextFragmentAbsorber](../../textfragmentabsorber)
* пространство имен [Aspose.Pdf.Text](../../textfragmentabsorber)
* сборка [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
