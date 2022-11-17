---
title: TextFragmentAbsorber
second_title: Aspose.PDF для справки по Java API
description: Представляет объект-поглотитель текстовых фрагментов.
type: docs
weight: 373
url: /ru/java/com.aspose.pdf/textfragmentabsorber/
---
**Наследование:**
java.lang.Object, [com.aspose.pdf.TextAbsorber](../../com.aspose.pdf/textabsorber)
```
public final class TextFragmentAbsorber extends TextAbsorber
```

Представляет объект-поглотитель текстовых фрагментов. Выполняет текстовый поиск и предоставляет доступ к результатам поиска через коллекцию TextFragmentAbsorber.TextFragments.

--------------------

```
The example demonstrates how to find text on the first PDF document page and replace the text and it's font.

 // Открыть документ
 Document doc = new Document("D:\\Tests\\input.pdf");
 // Найти шрифт, который будет использоваться для изменения шрифта текста документа
 com.aspose.pdf.Font font = FontRepository.findFont("Arial");
 // Создайте объект TextFragmentAbsorber, чтобы найти все вхождения текста «hello world».
 TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");
 // Принять поглотитель для первой страницы
 doc.getPages().get(1).accept(absorber);
 // Изменить текст и шрифт первого вхождения текста
 absorber.getTextFragments().get_Item(1).setText ( "hi world");
 absorber.getTextFragments().get_Item(1).getTextState().setFont ( font);
 // Сохранить документ
 doc.save("D:\\Tests\\output.pdf");
```

--------------------

Объект TextFragmentAbsorber в основном используется в сценарии текстового поиска. Когда поиск завершен, вхождения представляются объектами TextFragment, содержащимися в коллекции TextFragmentAbsorber.TextFragments. Объект TextFragment предоставляет доступ к тексту вхождения поиска, свойствам текста, а также позволяет редактировать текст и изменять состояние текста (шрифт, размер шрифта, цвет и т. д.).
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [TextFragmentAbsorber()](#TextFragmentAbsorber--) | Инициализирует новый экземпляр TextFragmentAbsorber, который выполняет поиск во всех текстовых сегментах документа или страницы. |
| [TextFragmentAbsorber(TextEditOptions textEditOptions)](#TextFragmentAbsorber-com.aspose.pdf.TextEditOptions-) | Инициализирует новый экземпляр TextFragmentAbsorber с параметрами редактирования текста, который выполняет поиск по всем текстовым сегментам документа или страницы. |
| [TextFragmentAbsorber(String phrase)](#TextFragmentAbsorber-java.lang.String-) | Инициализирует новый экземпляр класса TextFragmentAbsorber для указанной текстовой фразы. |
| [TextFragmentAbsorber(Pattern regex)](#TextFragmentAbsorber-java.util.regex.Pattern-) |  Инициализирует новый экземпляр[TextFragmentAbsorber](../../com.aspose.pdf/textfragmentabsorber)class для указанного объекта класса System.Text.RegularExpressions.Regex. |
| [TextFragmentAbsorber(String phrase, TextSearchOptions textSearchOptions)](#TextFragmentAbsorber-java.lang.String-com.aspose.pdf.TextSearchOptions-) | Инициализирует новый экземпляр класса TextFragmentAbsorber для указанной текстовой фразы и параметров текстового поиска. |
| [TextFragmentAbsorber(Pattern regex, TextSearchOptions textSearchOptions)](#TextFragmentAbsorber-java.util.regex.Pattern-com.aspose.pdf.TextSearchOptions-) |  Инициализирует новый экземпляр[TextFragmentAbsorber](../../com.aspose.pdf/textfragmentabsorber) class для указанной текстовой фразы и опций текстового поиска. |
| [TextFragmentAbsorber(String phrase, TextSearchOptions textSearchOptions, TextEditOptions textEditOptions)](#TextFragmentAbsorber-java.lang.String-com.aspose.pdf.TextSearchOptions-com.aspose.pdf.TextEditOptions-) | Инициализирует новый экземпляр класса TextFragmentAbsorber для указанной текстовой фразы, параметров поиска текста и параметров редактирования текста. |
| [TextFragmentAbsorber(Pattern regex, TextEditOptions textEditOptions)](#TextFragmentAbsorber-java.util.regex.Pattern-com.aspose.pdf.TextEditOptions-) |  Инициализирует новый экземпляр[TextFragmentAbsorber](../../com.aspose.pdf/textfragmentabsorber) класс для указанной текстовой фразы и параметров редактирования текста. |
| [TextFragmentAbsorber(String phrase, TextEditOptions textEditOptions)](#TextFragmentAbsorber-java.lang.String-com.aspose.pdf.TextEditOptions-) | Инициализирует новый экземпляр класса TextFragmentAbsorber для указанной текстовой фразы и параметров редактирования текста. |
## Методы

| Метод | Описание |
| --- | --- |
| [applyForAllFragments(Font font)](#applyForAllFragments-com.aspose.pdf.Font-) | Применяет шрифт ко всем фрагментам текста, которые были поглощены. |
| [applyForAllFragments(Font font, float fontSize)](#applyForAllFragments-com.aspose.pdf.Font-float-) | Применяет шрифт и размер ко всем фрагментам текста, которые были поглощены. |
| [applyForAllFragments(float fontSize)](#applyForAllFragments-float-) | Применяет размер шрифта ко всем фрагментам текста, которые были поглощены. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getErrors()](#getErrors--) | Список объектов TextExtractionError. |
| [getExtractionOptions()](#getExtractionOptions--) | Получает параметры извлечения текста. |
| [getPhrase()](#getPhrase--) | Получает фразу, которую TextFragmentAbsorber ищет в документе или странице PDF. |
| [getText()](#getText--) | Получает извлеченный текст, который TextAbsorber извлекает из документа или страницы PDF. |
| [getTextEditOptions()](#getTextEditOptions--) | Получает параметры редактирования текста. |
| [getTextFragments()](#getTextFragments--) | Получает коллекцию вхождений поиска, представленных объектами TextFragment. |
| [getTextReplaceOptions()](#getTextReplaceOptions--) | Получает параметры замены текста. |
| [getTextSearchOptions()](#getTextSearchOptions--) | Получает параметры поиска. |
| [hasErrors()](#hasErrors--) | Значение указывает, были ли обнаружены ошибки при извлечении текста. |
| [hasErrors_Fragment()](#hasErrors-Fragment--) | Значение указывает, были ли обнаружены ошибки при извлечении текста. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeAllText(Document document)](#removeAllText-com.aspose.pdf.Document-) | Удаляет весь текст из документа. |
| [removeAllText(Page page)](#removeAllText-com.aspose.pdf.Page-) | Удаляет весь текст с указанной страницы. |
| [removeAllText(Page page, Rectangle rect)](#removeAllText-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Удаляет текст внутри указанного прямоугольника с указанной страницы. |
| [reset()](#reset--) | Очищает коллекцию TextFragments этого объекта TextFragmentAbsorber. |
| [setExtractionOptions(TextExtractionOptions value)](#setExtractionOptions-com.aspose.pdf.TextExtractionOptions-) | Задает параметры извлечения текста. |
| [setPhrase(String value)](#setPhrase-java.lang.String-) | Задает фразу, которую TextFragmentAbsorber ищет в документе или странице PDF. |
| [setTextEditOptions(TextEditOptions value)](#setTextEditOptions-com.aspose.pdf.TextEditOptions-) | Задает параметры редактирования текста. |
| [setTextFragments(TextFragmentCollection value)](#setTextFragments-com.aspose.pdf.TextFragmentCollection-) | Задает набор вхождений поиска, представленных объектами TextFragment. |
| [setTextReplaceOptions(TextReplaceOptions value)](#setTextReplaceOptions-com.aspose.pdf.TextReplaceOptions-) | Задает параметры замены текста. |
| [setTextSearchOptions(TextSearchOptions value)](#setTextSearchOptions-com.aspose.pdf.TextSearchOptions-) | Задает параметры поиска. |
| [toString()](#toString--) |  |
| [visit(IDocument pdf)](#visit-com.aspose.pdf.IDocument-) | Выполняет поиск по указанному документу. |
| [visit(Page page)](#visit-com.aspose.pdf.Page-) | Выполняет поиск на указанной странице. |
| [visit(XForm xForm)](#visit-com.aspose.pdf.XForm-) | Выполняет поиск по указанному объекту формы. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TextFragmentAbsorber() {#TextFragmentAbsorber--}
```
public TextFragmentAbsorber()
```


Инициализирует новый экземпляр TextFragmentAbsorber, который выполняет поиск во всех текстовых сегментах документа или страницы.

--------------------

```
The example demonstrates how to find text on the first PDF document page and replace the text.

 // Открыть документ
 Document doc = new Document("D:\\Tests\\input.pdf");
 // Найти шрифт, который будет использоваться для изменения шрифта текста документа
 Font font = FontRepository.findFont("Arial");
 // Создайте объект TextFragmentAbsorber
 TextFragmentAbsorber absorber = new TextFragmentAbsorber();
 // Заставьте поглотитель искать все вхождения текста «hello world»
 absorber.setPhrase ( "hello world");
 // Принять поглотитель для первой страницы
 doc.getPages().get(1).accept(absorber);
 // Изменить текст первого вхождения текста
 absorber.getTextFragments().get_Item(1).setText ( "hi world");
 // Сохранить документ
 doc.save("D:\\Tests\\output.pdf");
```

--------------------

Выполняет текстовый поиск и предоставляет доступ к результатам поиска через коллекцию TextFragmentAbsorber.TextFragments.

### TextFragmentAbsorber(TextEditOptions textEditOptions) {#TextFragmentAbsorber-com.aspose.pdf.TextEditOptions-}
```
public TextFragmentAbsorber(TextEditOptions textEditOptions)
```


Инициализирует новый экземпляр TextFragmentAbsorber с параметрами редактирования текста, который выполняет поиск по всем текстовым сегментам документа или страницы.

--------------------

```
The example demonstrates how to find all text fragments on the first PDF document page and replace font for them.

  // Открыть документ
  Document doc = new Document("D:\\Tests\\input.pdf");

  // Создайте объект TextFragmentAbsorber
  TextFragmentAbsorber absorber = new TextFragmentAbsorber(new TextEditOptions(TextEditOptions.FontReplace
  .RemoveUnusedFonts));

  // Принять поглотитель для первой страницы
  doc.getPages()get(1).accept(absorber);

  // Найти шрифт Courier
  Font font = FontRepository.findFont("Courier");
  // Установить шрифт для всех текстовых фрагментов
  for (TextFragment textFragment : ```
(Iterable)
```absorber.TextFragments)
  {
      textFragment.getTextState().setFont ( font);
  }
  // Сохранить документ
  doc.save("D:\\Tests\\output.pdf");
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| textEditOptions | [TextEditOptions](../../com.aspose.pdf/texteditoptions) | Параметры редактирования текста (позволяет включить некоторые функции редактирования).

--------------------

Выполняет текстовый поиск и предоставляет доступ к результатам поиска через коллекцию TextFragmentAbsorber.TextFragments.|

### TextFragmentAbsorber(String phrase) {#TextFragmentAbsorber-java.lang.String-}
```
public TextFragmentAbsorber(String phrase)
```


Инициализирует новый экземпляр класса TextFragmentAbsorber для указанной текстовой фразы.

--------------------

```
The example demonstrates how to find text on the first PDF document page and replace the text and it's font.

 // Открыть документ
 Document doc = new Document("D:\\Tests\\input.pdf");
 // Найти шрифт, который будет использоваться для изменения шрифта текста документа
 com.aspose.pdf.Font font = FontRepository.findFont("Arial");
 // Создайте объект TextFragmentAbsorber, чтобы найти все вхождения текста «hello world».
 TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");
 // Принять поглотитель для первой страницы
 doc.getPages().get_Item(1).accept(absorber);
 // Изменить текст и шрифт первого вхождения текста
 absorber.getTextFragments().get_Item(1).setText ( "hi world");
 absorber.getTextFragments().get_Item(1).getTextState().setFont ( font);
 // Сохранить документ
 doc.save("D:\\Tests\\output.pdf");
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| phrase | java.lang.String | Фраза, которую ищет TextFragmentAbsorber

--------------------

 Выполняет текстовый поиск по указанной фразе и предоставляет доступ к результатам поиска через коллекцию TextFragmentAbsorber.TextFragments.|

### TextFragmentAbsorber(Pattern regex) {#TextFragmentAbsorber-java.util.regex.Pattern-}
```
public TextFragmentAbsorber(Pattern regex)
```


 Инициализирует новый экземпляр[TextFragmentAbsorber](../../com.aspose.pdf/textfragmentabsorber)class для указанного объекта класса System.Text.RegularExpressions.Regex.

--------------------

В примере показано, как найти текст на первой странице документа PDF и заменить текст и его шрифт.

```
// Открыть документ
  Document doc = new Document("input.pdf");
  // Найти шрифт, который будет использоваться для изменения шрифта текста документа
  Font font = FontRepository.findFont("Arial");
  // Создайте объект TextAbsorber, чтобы найти все экземпляры входного регулярного выражения.
  TextFragmentAbsorber absorber = new TextFragmentAbsorber(new Regex("h\\w*?o"));
  // Принять поглотитель для первой страницы
  doc.getPages().get_item(1).accept(absorber);
  // мы должны найти слово «привет» и заменить его на «Привет»
  absorber.getTextFragments().get_item(1).setText("Hi");
  // Сохранить документ
  doc.save("output.pdf");
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| regex | java.util.regex.Pattern |  Объект класса System.Text.RegularExpressions.Regex, который[TextFragmentAbsorber](../../com.aspose.pdf/textfragmentabsorber) поиски

--------------------

Выполняет текстовый поиск по указанной фразе и предоставляет доступ к результатам поиска через TextFragmentAbsorber.TextFragments (\#getTextFragments.getTextFragments/\ Коллекция #setTextFragments(TextFragmentCollection).setTextFragments(TextFragmentCollection)) .|

### TextFragmentAbsorber(String phrase, TextSearchOptions textSearchOptions) {#TextFragmentAbsorber-java.lang.String-com.aspose.pdf.TextSearchOptions-}
```
public TextFragmentAbsorber(String phrase, TextSearchOptions textSearchOptions)
```


Инициализирует новый экземпляр класса TextFragmentAbsorber для указанной текстовой фразы и параметров текстового поиска.

--------------------

```
The example demonstrates how to find text with regular expression on the first PDF document page and replace
 the text.

 // Открыть документ
 Document doc = new Document("D:\\Tests\\input.pdf");
 //Создайте объект TextFragmentAbsorber, который ищет все слова, начинающиеся с «h» и заканчивающиеся на «o», используя обычные
 expression.
 TextFragmentAbsorber absorber = new TextFragmentAbsorber("h\\w*?o", new TextSearchOptions(true));
 // мы должны найти слово «привет» и заменить его на «Привет»
 doc.getPages().get_Item(1).accept(absorber);
 absorber.getTextFragments().get_Item(1).setText ( "Hi");

 // Сохранить документ
 doc.save("D:\\Tests\\output.pdf");
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| phrase | java.lang.String | Фраза, которую ищет TextFragmentAbsorber |
| textSearchOptions | [TextSearchOptions](../../com.aspose.pdf/textsearchoptions) | Параметры текстового поиска (позволяет включить некоторые функции поиска. Например, поиск по регулярному выражению)

--------------------

 Выполняет текстовый поиск по указанной фразе и предоставляет доступ к результатам поиска через коллекцию TextFragmentAbsorber.TextFragments.|

### TextFragmentAbsorber(Pattern regex, TextSearchOptions textSearchOptions) {#TextFragmentAbsorber-java.util.regex.Pattern-com.aspose.pdf.TextSearchOptions-}
```
public TextFragmentAbsorber(Pattern regex, TextSearchOptions textSearchOptions)
```


 Инициализирует новый экземпляр[TextFragmentAbsorber](../../com.aspose.pdf/textfragmentabsorber) class для указанной текстовой фразы и опций текстового поиска.

--------------------

В примере показано, как найти текст с помощью регулярного выражения на первой странице документа PDF и заменить текст.

```
// Открыть документ
  Document doc = new Document("input.pdf");
  // Создайте объект TextFragmentAbsorber, который ищет все слова, начинающиеся с «h» и заканчивающиеся на «o», с использованием регулярного выражения.
  TextFragmentAbsorber absorber = new TextFragmentAbsorber(new Regex("h\\w*?o"), new TextSearchOptions(true));
  // мы должны найти слово «привет» и заменить его на «Привет»
  doc.getPages().get_Item(1).accept(absorber);
  absorber.getTextFragments.get_Item(1).setText("Hi");
  // Сохранить документ
  doc.save("output.pdf");
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| regex | java.util.regex.Pattern |  Объект класса Regex, который[TextFragmentAbsorber](../../com.aspose.pdf/textfragmentabsorber) поиски |
| textSearchOptions | [TextSearchOptions](../../com.aspose.pdf/textsearchoptions) | Параметры текстового поиска (позволяет включить некоторые функции поиска.)

--------------------

Выполняет текстовый поиск по указанной фразе и предоставляет доступ к результатам поиска через TextFragmentAbsorber.TextFragments (\#getTextFragments.getTextFragments/\ Коллекция #setTextFragments(TextFragmentCollection).setTextFragments(TextFragmentCollection)) .|

### TextFragmentAbsorber(String phrase, TextSearchOptions textSearchOptions, TextEditOptions textEditOptions) {#TextFragmentAbsorber-java.lang.String-com.aspose.pdf.TextSearchOptions-com.aspose.pdf.TextEditOptions-}
```
public TextFragmentAbsorber(String phrase, TextSearchOptions textSearchOptions, TextEditOptions textEditOptions)
```


Инициализирует новый экземпляр класса TextFragmentAbsorber для указанной текстовой фразы, параметров поиска текста и параметров редактирования текста. Параметры редактирования текста пока не поддерживаются.

--------------------

```
The example demonstrates how to find text with regular expression on the first PDF document page and replace
 the text.

 // Открыть документ
 Document doc = new Document("D:\\Tests\\input.pdf");
 //Создайте объект TextFragmentAbsorber, который ищет все слова, начинающиеся с «h» и заканчивающиеся на «o», используя обычные
 expression.
 TextFragmentAbsorber absorber = new TextFragmentAbsorber("h\w*?o", new TextSearchOptions(true));
 // мы должны найти слово «привет» и заменить его на «Привет»
 doc.getPages().get_item(1).accept(absorber);
 absorber.getTextFragments().get_Item(1).setText ( "Hi");
 // Сохранить документ
 doc.save("D:\\Tests\\output.pdf");
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| phrase | java.lang.String | Фраза, которую ищет TextFragmentAbsorber |
| textSearchOptions | [TextSearchOptions](../../com.aspose.pdf/textsearchoptions) | Параметры текстового поиска (позволяет включить некоторые функции поиска. Например, поиск по регулярному выражению) |
| textEditOptions | [TextEditOptions](../../com.aspose.pdf/texteditoptions) | Параметры редактирования текста (позволяет включить некоторые функции редактирования. Например, определить особое поведение, когда запрашиваемый символ не может быть написан шрифтом). Параметр пока не поддерживается.

--------------------

 Выполняет текстовый поиск по указанной фразе и предоставляет доступ к результатам поиска через коллекцию TextFragmentAbsorber.TextFragments.|

### TextFragmentAbsorber(Pattern regex, TextEditOptions textEditOptions) {#TextFragmentAbsorber-java.util.regex.Pattern-com.aspose.pdf.TextEditOptions-}
```
public TextFragmentAbsorber(Pattern regex, TextEditOptions textEditOptions)
```


 Инициализирует новый экземпляр[TextFragmentAbsorber](../../com.aspose.pdf/textfragmentabsorber) класс для указанной текстовой фразы и параметров редактирования текста.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| regex | java.util.regex.Pattern |  Объект класса System.Text.RegularExpressions.Regex, который[TextFragmentAbsorber](../../com.aspose.pdf/textfragmentabsorber) поиски |
| textEditOptions | [TextEditOptions](../../com.aspose.pdf/texteditoptions) | Параметры редактирования текста (позволяет включить некоторые функции редактирования).

--------------------

Выполняет текстовый поиск по указанной фразе и предоставляет доступ к результатам поиска через TextFragmentAbsorber.TextFragments (\#getTextFragments.getTextFragments/\ Коллекция #setTextFragments(TextFragmentCollection).setTextFragments(TextFragmentCollection)) .|

### TextFragmentAbsorber(String phrase, TextEditOptions textEditOptions) {#TextFragmentAbsorber-java.lang.String-com.aspose.pdf.TextEditOptions-}
```
public TextFragmentAbsorber(String phrase, TextEditOptions textEditOptions)
```


Инициализирует новый экземпляр класса TextFragmentAbsorber для указанной текстовой фразы и параметров редактирования текста.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| phrase | java.lang.String | Фраза, которую ищет TextFragmentAbsorber |
| textEditOptions | [TextEditOptions](../../com.aspose.pdf/texteditoptions) | Параметры редактирования текста (позволяет включить некоторые функции редактирования).

--------------------

 Выполняет текстовый поиск по указанной фразе и предоставляет доступ к результатам поиска через коллекцию TextFragmentAbsorber.TextFragments.|

### applyForAllFragments(Font font) {#applyForAllFragments-com.aspose.pdf.Font-}
```
public void applyForAllFragments(Font font)
```


Применяет шрифт ко всем фрагментам текста, которые были поглощены. Это работает быстрее, чем перебор фрагментов, если все фрагменты на странице (страницах) были поглощены. В противном случае он работает аналогично циклу.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| font | [Font](../../com.aspose.pdf/font) |  Шрифт текста. |

### applyForAllFragments(Font font, float fontSize) {#applyForAllFragments-com.aspose.pdf.Font-float-}
```
public void applyForAllFragments(Font font, float fontSize)
```


Применяет шрифт и размер ко всем фрагментам текста, которые были поглощены. Это работает быстрее, чем перебор фрагментов, если все фрагменты на странице (страницах) были поглощены. В противном случае он работает аналогично циклу.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| font | [Font](../../com.aspose.pdf/font) |  Шрифт текста. |
| fontSize | float | Размер шрифта текста. |

### applyForAllFragments(float fontSize) {#applyForAllFragments-float-}
```
public void applyForAllFragments(float fontSize)
```


Применяет размер шрифта ко всем фрагментам текста, которые были поглощены. Это работает быстрее, чем перебор фрагментов, если все фрагменты на странице (страницах) были поглощены. В противном случае он работает аналогично циклу.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| fontSize | float | Размер шрифта текста. |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Возвращает:**
логический
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Возвращает:**
java.lang.Класс<?>
### getErrors() {#getErrors--}
```
public List<TextExtractionError> getErrors()
```


Список объектов TextExtractionError. Он содержит информацию об ошибках, обнаруженных при извлечении текста. Поиск ошибок будет производиться, только если TextSearchOptions.LogTextExtractionErrors = true; И это может снизить производительность.

**Возвращает:**
java.util.List<com.aspose.pdf.TextExtractionError> — Список объектов TextExtractionError
### getExtractionOptions() {#getExtractionOptions--}
```
public TextExtractionOptions getExtractionOptions()
```


Получает параметры извлечения текста.

**Возвращает:**
[TextExtractionOptions](../../com.aspose.pdf/textextractionoptions) - Объект TextExtractionOptions
### getPhrase() {#getPhrase--}
```
public String getPhrase()
```


Получает фразу, которую TextFragmentAbsorber ищет в документе или странице PDF.

**Возвращает:**
java.lang.String — строковое значение

--------------------

```
The example demonstrates how to perform search text several times and perform text replacements.

 // Открыть документ
 Document doc = new Document("D:\\Tests\\input.pdf");
 // Создайте объект TextFragmentAbsorber, чтобы найти все вхождения текста «привет»
 TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello");
 doc.getPages().get(1).accept(absorber);
 absorber.getTextFragments().get_Item(1).setText ( "Hi");
 // найти другое слово и заменить его
 absorber.setPhrase ( "world");
 doc.getPages().get(1).accept(absorber);
 absorber.getTextFragments().get_Item(1).setText ( "John");
 // Сохранить документ
 doc.save("D:\\Tests\\output.pdf");
```
### getText() {#getText--}
```
public String getText()
```


Получает извлеченный текст, который TextAbsorber извлекает из документа или страницы PDF.

**Возвращает:**
java.lang.String
### getTextEditOptions() {#getTextEditOptions--}
```
public TextEditOptions getTextEditOptions()
```


Получает параметры редактирования текста. Опции определяют особое поведение, когда запрошенный символ не может быть написан шрифтом.

**Возвращает:**
[TextEditOptions](../../com.aspose.pdf/texteditoptions) - Объект TextEditOptions
### getTextFragments() {#getTextFragments--}
```
public TextFragmentCollection getTextFragments()
```


Получает коллекцию вхождений поиска, представленных объектами TextFragment.

**Возвращает:**
[TextFragmentCollection](../../com.aspose.pdf/textfragmentcollection) - Объект TextFragmentCollection

--------------------

```
The example demonstrates how to find text on the first PDF document page and replace all search occurrences
 with new text.

 // Открыть документ
 Document doc = new Document("D:\\Tests\\input.pdf");
 // Найти шрифт, который будет использоваться для изменения шрифта текста документа
 Font font = FontRepository.findFont("Arial");
 // Создайте объект TextFragmentAbsorber, чтобы найти все вхождения текста «hello world».
 TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");
 // Принять поглотитель для первой страницы
 doc.getPages().get(1).accept(absorber);
 //Изменить текст всех вхождений поиска
 for (TextFragment textFragment : ```
(Iterable)
```absorber.getTextFragments())
 {
     textFragment.setText ( "hi world");
 }
 // Сохранить документ
 doc.save("D:\\Tests\\output.pdf");
```
### getTextReplaceOptions() {#getTextReplaceOptions--}
```
public TextReplaceOptions getTextReplaceOptions()
```


Получает параметры замены текста. Опции определяют поведение при замене текста фрагмента на более короткий/длинный.

**Возвращает:**
[TextReplaceOptions](../../com.aspose.pdf/textreplaceoptions) - Значение TextReplaceOptions
### getTextSearchOptions() {#getTextSearchOptions--}
```
public TextSearchOptions getTextSearchOptions()
```


Получает параметры поиска. Параметры включают поиск с использованием регулярных выражений.

**Возвращает:**
[TextSearchOptions](../../com.aspose.pdf/textsearchoptions) - Объект TextSearchOptions

--------------------

```
The example demonstrates how to perform search text using regular expression.

 // Открыть документ
 Document doc = new Document("D:\\Tests\\input.pdf");
 // Создайте объект TextFragmentAbsorber
 TextFragmentAbsorber absorber = new TextFragmentAbsorber();
 // заставить поглотитель искать все слова, начинающиеся с «h» и заканчивающиеся на «o», используя регулярное выражение.
 absorber.setPhrase ( "h\w*?o");
 absorber.setTextSearchOptions ( new TextSearchOptions(true));
 // мы должны найти слово «привет» и заменить его на «Привет»
 doc.getPages().get(1).accept(absorber);
 absorber.getTextFragments().get_Item(1).setText ( "Hi");
 // Сохранить документ
 doc.save("D:\\Tests\\output.pdf");
```
### hasErrors() {#hasErrors--}
```
public boolean hasErrors()
```


Значение указывает, были ли обнаружены ошибки при извлечении текста. Поиск ошибок будет производиться, только если TextSearchOptions.LogTextExtractionErrors = true; И это может снизить производительность.

**Возвращает:**
boolean - логическое значение
### hasErrors_Fragment() {#hasErrors-Fragment--}
```
public boolean hasErrors_Fragment()
```


Значение указывает, были ли обнаружены ошибки при извлечении текста. Поиск ошибок будет производиться, только если TextSearchOptions.LogTextExtractionErrors = true; И это может снизить производительность.

**Возвращает:**
boolean - логическое значение
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Возвращает:**
инт
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### removeAllText(Document document) {#removeAllText-com.aspose.pdf.Document-}
```
public void removeAllText(Document document)
```


Удаляет весь текст из документа.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| document | [Document](../../com.aspose.pdf/document) | Объект PDF-документа. |

### removeAllText(Page page) {#removeAllText-com.aspose.pdf.Page-}
```
public void removeAllText(Page page)
```


Удаляет весь текст с указанной страницы.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | Объект страницы документа PDF. |

### removeAllText(Page page, Rectangle rect) {#removeAllText-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
```
public final void removeAllText(Page page, Rectangle rect)
```


Удаляет текст внутри указанного прямоугольника с указанной страницы.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | Объект страницы документа PDF. |
| rect | [Rectangle](../../com.aspose.pdf/rectangle) | [Rectangle](../../com.aspose.pdf/rectangle) чтобы удалить текст внутри. |

### reset() {#reset--}
```
public void reset()
```


Очищает коллекцию TextFragments этого объекта TextFragmentAbsorber.

### setExtractionOptions(TextExtractionOptions value) {#setExtractionOptions-com.aspose.pdf.TextExtractionOptions-}
```
public void setExtractionOptions(TextExtractionOptions value)
```


Задает параметры извлечения текста.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [TextExtractionOptions](../../com.aspose.pdf/textextractionoptions) | Объект TextExtractionOptions |

### setPhrase(String value) {#setPhrase-java.lang.String-}
```
public void setPhrase(String value)
```


Задает фразу, которую TextFragmentAbsorber ищет в документе или странице PDF.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String | Строковое значение

--------------------

```
The example demonstrates how to perform search text several times and perform text replacements.

              // Открыть документ
              Document doc = new Document("D:\\Tests\\input.pdf");
              // Создайте объект TextFragmentAbsorber, чтобы найти все вхождения текста «привет»
              TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello");
              doc.getPages().get(1).accept(absorber);
              absorber.getTextFragments().get_Item(1).setText ( "Hi");
              // найти другое слово и заменить его
              absorber.setPhrase ( "world");
              doc.getPages().get(1).accept(absorber);
              absorber.getTextFragments().get_Item(1).setText ( "John");
              // Сохранить документ
              doc.save("D:\\Tests\\output.pdf");
``` |

### setTextEditOptions(TextEditOptions value) {#setTextEditOptions-com.aspose.pdf.TextEditOptions-}
```
public void setTextEditOptions (значение TextEditOptions)
```


Sets text edit options. The options define special behavior when requested symbol cannot be written with font.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [TextEditOptions](../../com.aspose.pdf/texteditoptions) | TextEditOptions object |

### setTextFragments(TextFragmentCollection value) {#setTextFragments-com.aspose.pdf.TextFragmentCollection-}
```
public void setTextFragments (значение TextFragmentCollection)
```


Sets collection of search occurrences that are presented with  TextFragment  objects.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [TextFragmentCollection](../../com.aspose.pdf/textfragmentcollection) | TextFragmentCollection object

--------------------

```
В примере показано, как найти текст на первой странице документа PDF и заменить все поисковые запросы.
              вхождения с новым текстом.

              // Open document
              Document doc = new Document("D:\\Tests\\input.pdf");
              // Find font that will be used to change document text font
              Font font = FontRepository.findFont("Arial");
              // Create TextFragmentAbsorber object to find all "hello world" text occurrences
              TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");
              // Accept the absorber for first page
              doc.getPages().get(1).accept(absorber);
              // Change text of all search occurrences
              for (TextFragment textFragment : ```
(Повторяемый)
```absorber.getTextFragments())
              {
                  textFragment.setText ( "hi world");
              }
              // Сохранить документ
              doc.save("D:\\Tests\\output.pdf");
``` |

### setTextReplaceOptions(TextReplaceOptions value) {#setTextReplaceOptions-com.aspose.pdf.TextReplaceOptions-}
```
public void setTextReplaceOptions (значение TextReplaceOptions)
```


Sets text replace options. The options define behavior when fragment text is replaced to more short/long.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [TextReplaceOptions](../../com.aspose.pdf/textreplaceoptions) | TextReplaceOptions value |

### setTextSearchOptions(TextSearchOptions value) {#setTextSearchOptions-com.aspose.pdf.TextSearchOptions-}
```
public void setTextSearchOptions (значение TextSearchOptions)
```


Sets search options. The options enable search using regular expressions.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [TextSearchOptions](../../com.aspose.pdf/textsearchoptions) | TextSearchOptions object

--------------------

```
В примере показано, как выполнить поиск текста с помощью регулярного выражения.

              // Open document
              Document doc = new Document("D:\\Tests\\input.pdf");
              // Create TextFragmentAbsorber object
              TextFragmentAbsorber absorber = new TextFragmentAbsorber();
              // make the absorber to search all words starting 'h' and ending 'o' using regular expression.
              absorber.setPhrase ( "h\w*?o");
              absorber.setTextSearchOptions ( new TextSearchOptions(true));
              // we should find "hello" word and replace it with "Hi"
              doc.getPages().get(1).accept(absorber);
              absorber.getTextFragments().get_Item(1).setText ( "Hi");
              // Save document
              doc.save("D:\\Tests\\output.pdf");
``` |

### toString() {#toString--}
```
публичная строка toString()
```




**Returns:**
java.lang.String
### visit(IDocument pdf) {#visit-com.aspose.pdf.IDocument-}
```
публичное недействительное посещение (IDocument pdf)
```


Performs search on the specified document.

--------------------

```
В примере показано, как найти текст в документе PDF и заменить текст во всех случаях поиска.

 // Открыть документ
 Документ документ = новый документ("D:\\Тесты\\input.pdf");
 // Находим шрифт, который будет использоваться для изменения шрифта текста документа
 Шрифт font = FontRepository.findFont("Arial");
 // Создаем объект TextFragmentAbsorber для поиска всех вхождений текста "hello world"
 Поглотитель TextFragmentAbsorber = новый TextFragmentAbsorber («привет, мир»);
 // Принять поглотитель для первой страницы
 поглотитель.визит(док);
 // Изменяем текст первого вхождения текста
 поглотитель.getTextFragments().get_Item(1).setText ("привет, мир");
 // Сохранить документ
 документ.сохранить("Д:\\Тесты\\output.pdf");
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pdf | [IDocument](../../com.aspose.pdf/idocument) | PDF document object. |

### visit(Page page) {#visit-com.aspose.pdf.Page-}
```
публичный недействительный визит (страница страницы)
```


Performs search on the specified page.

--------------------

```
В примере показано, как найти текст на первой странице документа PDF и заменить текст.

 // Открыть документ
 Документ документ = новый документ("D:\\Тесты\\input.pdf");
 // Находим шрифт, который будет использоваться для изменения шрифта текста документа
 Шрифт font = FontRepository.findFont("Arial");
 // Создаем объект TextFragmentAbsorber для поиска всех вхождений текста "hello world"
 Поглотитель TextFragmentAbsorber = новый TextFragmentAbsorber («привет, мир»);
 // Принять поглотитель для первой страницы
 поглотитель.посетить(doc.getPages().get(1));
 // Изменить текст всех вхождений поиска
 for (TextFragment textFragment: ```
(Повторяемый)
```absorber.getTextFragments())
 {
     textFragment.setText ( "hi world");
 }
 // Сохранить документ
 doc.save("D:\\Tests\\output.pdf");
```

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | Объект страницы документа PDF. |

### visit(XForm xForm) {#visit-com.aspose.pdf.XForm-}
```
public void visit(XForm xForm)
```


Выполняет поиск по указанному объекту формы.

**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| xForm | [XForm](../../com.aspose.pdf/xform) | Объект формы PDF. |

### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Параметры:**

| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |
