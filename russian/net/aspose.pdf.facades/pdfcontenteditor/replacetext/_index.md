---
title: ReplaceText
second_title: Aspose.PDF для справочника API .NET
description: Заменяет текст в файле PDF на указанной странице.TextStateaspose.pdf.text/textstate объект семейство шрифтов цвет может быть указан для заменяемого текста.
type: docs
weight: 450
url: /ru/net/aspose.pdf.facades/pdfcontenteditor/replacetext/
---
## ReplaceText(string, int, string, TextState) {#replacetext_1}

Заменяет текст в файле PDF на указанной странице.[`TextState`](../../../aspose.pdf.text/textstate) объект (семейство шрифтов, цвет) может быть указан для заменяемого текста.

```csharp
public bool ReplaceText(string srcString, int thePage, string destString, TextState textState)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| srcString | String | Заменяемая строка. |
| thePage | Int32 | Номер страницы (0 означает «все страницы»). |
| destString | String | Заменяемая строка. |
| textState | TextState | Состояние текста (цвет текста, шрифт и т. д.). |

### Возвращаемое значение

Возвращает true, если замена была произведена.

### Примеры

В примере показано, как заменить текст на первой странице документа PDF и установить[`TextState`](../../../aspose.pdf.text/textstate) свойства текста для нового текста.

```csharp
// открыть документ
Document doc = new Document(inFile);

// Создаем шрифт и помечаем его для встраивания
Aspose.Pdf.Text.Font font = FontRepository.FindFont("Courier New");
font.IsEmbedded = true;

// создаем объект PdfContentEditor для редактирования текста
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf(doc);

// создать объект textState
TextState textState = new TextState();
textState.Font = font;
textState.FontSize = 17;
textState.FontStyle = FontStyle.Bold | FontStyle.Italic;
textState.ForegroundColor = Color.Red;

// изменить текст указанным шрифтом
editor.ReplaceText("hello world", 1, "hi world", textState);

// сохранить документ
doc.Save(outFile);
```

### Смотрите также

* class [TextState](../../../aspose.pdf.text/textstate)
* class [PdfContentEditor](../../pdfcontenteditor)
* пространство имен [Aspose.Pdf.Facades](../../pdfcontenteditor)
* сборка [Aspose.PDF](../../../)

---

## ReplaceText(string, string) {#replacetext_2}

Заменяет текст в файле PDF.

```csharp
public bool ReplaceText(string srcString, string destString)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| srcString | String | Заменяемая строка. |
| destString | String | Замена строки. |

### Возвращаемое значение

Возвращает true, если замена была произведена.

### Примеры

В примере показано, как заменить текст в документе PDF.

```csharp
// открыть документ
Document doc = new Document(inFile);

// создаем объект PdfContentEditor для редактирования текста
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf(doc);

// изменить текст 
editor.ReplaceText("hello world", "hi world");

// сохранить документ
doc.Save(outFile);
```

### Смотрите также

* class [PdfContentEditor](../../pdfcontenteditor)
* пространство имен [Aspose.Pdf.Facades](../../pdfcontenteditor)
* сборка [Aspose.PDF](../../../)

---

## ReplaceText(string, int, string) {#replacetext}

Заменяет текст в файле PDF на указанной странице.

```csharp
public bool ReplaceText(string srcString, int thePage, string destString)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| srcString | String | Жало подлежит замене. |
| thePage | Int32 | Номер страницы (0 для всех страниц) |
| destString | String | Замена строки. |

### Возвращаемое значение

Возвращает true, если замена была произведена.

### Примеры

В примере показано, как заменить текст в документе PDF на указанной странице.

```csharp
// открыть документ
Document doc = new Document(inFile);

// создаем объект PdfContentEditor для редактирования текста
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf(doc);

// изменить текст 
editor.ReplaceText("hello world", 1, "hi world");

// сохранить документ
doc.Save(outFile);
```

### Смотрите также

* class [PdfContentEditor](../../pdfcontenteditor)
* пространство имен [Aspose.Pdf.Facades](../../pdfcontenteditor)
* сборка [Aspose.PDF](../../../)

---

## ReplaceText(string, string, TextState) {#replacetext_3}

Заменяет текст в файле PDF, используя указанный[`TextState`](../../../aspose.pdf.text/textstate) объект.

```csharp
public bool ReplaceText(string srcString, string destString, TextState textState)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| srcString | String | Строка для замены |
| destString | String | Замена строки |
| textState | TextState | Состояние текста (цвет текста, шрифт и т. д.) |

### Возвращаемое значение

Возвращает true, если замена была произведена.

### Примеры

Пример демонстрирует, как заменить текст и установить[`TextState`](../../../aspose.pdf.text/textstate) свойства текста для нового текста.

```csharp
// открыть документ
Document doc = new Document(inFile);

// Создаем шрифт и помечаем его для встраивания
Aspose.Pdf.Text.Font font = FontRepository.FindFont("Courier New");
font.IsEmbedded = true;

// создаем объект PdfContentEditor для редактирования текста
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf(doc);

// создать объект textState
TextState textState = new TextState();
textState.Font = font;
textState.FontStyle = FontStyle.Bold | FontStyle.Italic;

// изменить текст указанным шрифтом
editor.ReplaceText("hello world", "hi world", textState);

// сохранить документ
doc.Save(outFile);
```

### Смотрите также

* class [TextState](../../../aspose.pdf.text/textstate)
* class [PdfContentEditor](../../pdfcontenteditor)
* пространство имен [Aspose.Pdf.Facades](../../pdfcontenteditor)
* сборка [Aspose.PDF](../../../)

---

## ReplaceText(string, string, int) {#replacetext_4}

Заменяет текст в файле PDF и устанавливает размер шрифта.

```csharp
public bool ReplaceText(string srcString, string destString, int fontSize)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| srcString | String | Строка для замены. |
| destString | String | Замена строки. |
| fontSize | Int32 | Размер шрифта. |

### Возвращаемое значение

Возвращает true, если замена была произведена.

### Примеры

Пример демонстрирует, как заменить текст и установить размер шрифта для нового текста.

```csharp
// открыть документ
Document doc = new Document(inFile);

// Создаем шрифт и помечаем его для встраивания
Aspose.Pdf.Text.Font font = FontRepository.FindFont("Courier New");
font.IsEmbedded = true;

// создаем объект PdfContentEditor для редактирования текста
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf(doc);

// изменить текст указанным шрифтом
editor.ReplaceText("hello world", "hi world", 14);

// сохранить документ
doc.Save(outFile);
```

### Смотрите также

* class [PdfContentEditor](../../pdfcontenteditor)
* пространство имен [Aspose.Pdf.Facades](../../pdfcontenteditor)
* сборка [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
