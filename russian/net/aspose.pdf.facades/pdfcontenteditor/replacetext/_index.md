---
title: PdfContentEditor.ReplaceText
second_title: Aspose.PDF for .NET API Reference
description: Метод PdfContentEditor. Заменяет текст в PDF-файле на указанной странице. Объект TextState может быть указан для заменяемого текста
type: docs
weight: 450
url: /ru/net/aspose.pdf.facades/pdfcontenteditor/replacetext/
---
## ReplaceText(string, int, string, TextState) {#replacetext_1}

Заменяет текст в PDF-файле на указанной странице. Объект [`TextState`](../../../aspose.pdf.text/textstate/) (семейство шрифтов, цвет) может быть указан для заменяемого текста.

```csharp
public bool ReplaceText(string srcString, int thePage, string destString, TextState textState)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| srcString | String | Строка, которую нужно заменить. |
| thePage | Int32 | Номер страницы (0 означает "все страницы"). |
| destString | String | Заменяемая строка. |
| textState | TextState | Состояние текста (цвет текста, шрифт и т.д.). |

### Возвращаемое значение

Возвращает true, если замена была выполнена.

## Примеры

Пример демонстрирует, как заменить текст на первой странице PDF-документа и установить свойства текста [`TextState`](../../../aspose.pdf.text/textstate/) для нового текста.

```csharp
// open document
Document doc = new Document(inFile);

// Create font and mark it to be embedded
Aspose.Pdf.Text.Font font = FontRepository.FindFont("Courier New");
font.IsEmbedded = true;

// create PdfContentEditor object to edit text
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf(doc);

// create textState object
TextState textState = new TextState();
textState.Font = font;
textState.FontSize = 17;
textState.FontStyle = FontStyle.Bold | FontStyle.Italic;
textState.ForegroundColor = Color.Red;

// change text with specified font
editor.ReplaceText("hello world", 1, "hi world", textState);

// save document
doc.Save(outFile);
```

### См. также

* класс [TextState](../../../aspose.pdf.text/textstate/)
* класс [PdfContentEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)

---

## ReplaceText(string, string) {#replacetext_2}

Заменяет текст в PDF-файле.

```csharp
public bool ReplaceText(string srcString, string destString)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| srcString | String | Строка, которую нужно заменить. |
| destString | String | Заменяющая строка. |

### Возвращаемое значение

Возвращает true, если замена была выполнена.

## Примеры

Пример демонстрирует, как заменить текст в PDF-документе.

```csharp
// open document
Document doc = new Document(inFile);

// create PdfContentEditor object to edit text
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf(doc);

// change text 
editor.ReplaceText("hello world", "hi world");

// save document
doc.Save(outFile);
```

### См. также

* класс [PdfContentEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)

---

## ReplaceText(string, int, string) {#replacetext}

Заменяет текст в PDF-файле на указанной странице.

```csharp
public bool ReplaceText(string srcString, int thePage, string destString)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| srcString | String | Строка, которую нужно заменить. |
| thePage | Int32 | Номер страницы (0 для всех страниц) |
| destString | String | Заменяющая строка. |

### Возвращаемое значение

Возвращает true, если замена была выполнена.

## Примеры

Пример демонстрирует, как заменить текст в PDF-документе на указанной странице.

```csharp
// open document
Document doc = new Document(inFile);

// create PdfContentEditor object to edit text
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf(doc);

// change text 
editor.ReplaceText("hello world", 1, "hi world");

// save document
doc.Save(outFile);
```

### См. также

* класс [PdfContentEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)

---

## ReplaceText(string, string, TextState) {#replacetext_3}

Заменяет текст в PDF-файле, используя указанный объект [`TextState`](../../../aspose.pdf.text/textstate/).

```csharp
public bool ReplaceText(string srcString, string destString, TextState textState)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| srcString | String | Строка, которую нужно заменить |
| destString | String | Заменяющая строка |
| textState | TextState | Состояние текста (цвет текста, шрифт и т.д.) |

### Возвращаемое значение

Возвращает true, если замена была выполнена.

## Примеры

Пример демонстрирует, как заменить текст и установить свойства текста [`TextState`](../../../aspose.pdf.text/textstate/) для нового текста.

```csharp
// open document
Document doc = new Document(inFile);

// Create font and mark it to be embedded
Aspose.Pdf.Text.Font font = FontRepository.FindFont("Courier New");
font.IsEmbedded = true;

// create PdfContentEditor object to edit text
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf(doc);

// create textState object
TextState textState = new TextState();
textState.Font = font;
textState.FontStyle = FontStyle.Bold | FontStyle.Italic;

// change text with specified font
editor.ReplaceText("hello world", "hi world", textState);

// save document
doc.Save(outFile);
```

### См. также

* класс [TextState](../../../aspose.pdf.text/textstate/)
* класс [PdfContentEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)

---

## ReplaceText(string, string, int) {#replacetext_4}

Заменяет текст в PDF-файле и устанавливает размер шрифта.

```csharp
public bool ReplaceText(string srcString, string destString, int fontSize)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| srcString | String | Строка, которую нужно заменить. |
| destString | String | Заменяющая строка. |
| fontSize | Int32 | Размер шрифта. |

### Возвращаемое значение

Возвращает true, если замена была выполнена.

## Примеры

Пример демонстрирует, как заменить текст и установить размер шрифта для нового текста.

```csharp
// open document
Document doc = new Document(inFile);

// Create font and mark it to be embedded
Aspose.Pdf.Text.Font font = FontRepository.FindFont("Courier New");
font.IsEmbedded = true;

// create PdfContentEditor object to edit text
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf(doc);

// change text with specified font
editor.ReplaceText("hello world", "hi world", 14);

// save document
doc.Save(outFile);
```

### См. также

* класс [PdfContentEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)