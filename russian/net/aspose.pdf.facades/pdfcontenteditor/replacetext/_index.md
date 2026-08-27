---
title: "PdfContentEditor.ReplaceText"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод PdfContentEditor. Заменяет текст в PDF‑файле на указанной странице. Можно указать семейство шрифта и цвет объекта TextState для заменяемого текста."
type: docs
weight: 450
url: /ru/net/aspose.pdf.facades/pdfcontenteditor/replacetext/
---
## ReplaceText(string, int, string, TextState) {#replacetext_1}

Заменяет текст в PDF‑файле на указанной странице. Объект [`TextState`](../../../aspose.pdf.text/textstate/) (семейство шрифта, цвет) можно указать для заменяемого текста.

```csharp
public bool ReplaceText(string srcString, int thePage, string destString, TextState textState)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| srcString | String | Строка, которую нужно заменить. |
| thePage | Int32 | Номер страницы (0 означает «все страницы»). |
| destString | String | Заменённая строка. |
| textState | TextState | Состояние текста (цвет текста, шрифт и т.д.). |

### Возвращаемое значение

Возвращает true, если замена была выполнена.

## Примеры

В примере показано, как заменить текст на первой странице PDF‑документа и установить свойства текста [`TextState`](../../../aspose.pdf.text/textstate/) для нового текста.

```csharp
// открыть документ
Document doc = new Document(inFile);

// Создайте шрифт и пометьте его для встраивания
Aspose.Pdf.Text.Font font = FontRepository.FindFont("Courier New");
font.IsEmbedded = true;

// создать объект PdfContentEditor для редактирования текста
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf(doc);

// создать объект textState
TextState textState = new TextState();
textState.Font = font;
textState.FontSize = 17;
textState.FontStyle = FontStyle.Bold | FontStyle.Italic;
textState.ForegroundColor = Color.Red;

// изменить текст с указанным шрифтом
editor.ReplaceText("hello world", 1, "hi world", textState);

// сохранить документ
doc.Save(outFile);
```

### См. также

* class [TextState](../../../aspose.pdf.text/textstate/)
* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ReplaceText(string, string) {#replacetext_2}

Заменяет текст в PDF‑файле.

```csharp
public bool ReplaceText(string srcString, string destString)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| srcString | String | Строка, которую нужно заменить. |
| destString | String | Замена строки. |

### Возвращаемое значение

Возвращает true, если замена была выполнена.

## Примеры

В примере показано, как заменить текст в PDF‑документе.

```csharp
// открыть документ
Document doc = new Document(inFile);

// создать объект PdfContentEditor для редактирования текста
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf(doc);

// изменить текст 
editor.ReplaceText("hello world", "hi world");

// сохранить документ
doc.Save(outFile);
```

### См. также

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ReplaceText(string, int, string) {#replacetext}

Заменяет текст в PDF‑файле на указанной странице.

```csharp
public bool ReplaceText(string srcString, int thePage, string destString)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| srcString | String | Строка, которую нужно заменить. |
| thePage | Int32 | Номер страницы (0 — все страницы) |
| destString | String | Замена строки. |

### Возвращаемое значение

Возвращает true, если замена была выполнена.

## Примеры

В примере показано, как заменить текст в PDF‑документе на указанной странице.

```csharp
// открыть документ
Document doc = new Document(inFile);

// создать объект PdfContentEditor для редактирования текста
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf(doc);

// изменить текст 
editor.ReplaceText("hello world", 1, "hi world");

// сохранить документ
doc.Save(outFile);
```

### См. также

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ReplaceText(string, string, TextState) {#replacetext_3}

Заменяет текст в PDF‑файле, используя указанный объект [`TextState`](../../../aspose.pdf.text/textstate/).

```csharp
public bool ReplaceText(string srcString, string destString, TextState textState)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| srcString | String | Строка для замены |
| destString | String | Строка замены |
| textState | TextState | Состояние текста (цвет текста, шрифт и т.д.) |

### Возвращаемое значение

Возвращает true, если замена была выполнена.

## Примеры

В примере демонстрируется, как заменить текст и установить свойства текста [`TextState`](../../../aspose.pdf.text/textstate/) для нового текста.

```csharp
// открыть документ
Document doc = new Document(inFile);

// Создайте шрифт и пометьте его для встраивания
Aspose.Pdf.Text.Font font = FontRepository.FindFont("Courier New");
font.IsEmbedded = true;

// создать объект PdfContentEditor для редактирования текста
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf(doc);

// создать объект textState
TextState textState = new TextState();
textState.Font = font;
textState.FontStyle = FontStyle.Bold | FontStyle.Italic;

// изменить текст с указанным шрифтом
editor.ReplaceText("hello world", "hi world", textState);

// сохранить документ
doc.Save(outFile);
```

### См. также

* class [TextState](../../../aspose.pdf.text/textstate/)
* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ReplaceText(string, string, int) {#replacetext_4}

Заменяет текст в PDF‑файле и задает размер шрифта.

```csharp
public bool ReplaceText(string srcString, string destString, int fontSize)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| srcString | String | Строка для замены. |
| destString | String | Замена строки. |
| fontSize | Int32 | Размер шрифта. |

### Возвращаемое значение

Возвращает true, если замена была выполнена.

## Примеры

В примере демонстрируется, как заменить текст и установить размер шрифта для нового текста.

```csharp
// открыть документ
Document doc = new Document(inFile);

// Создайте шрифт и пометьте его для встраивания
Aspose.Pdf.Text.Font font = FontRepository.FindFont("Courier New");
font.IsEmbedded = true;

// создать объект PdfContentEditor для редактирования текста
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf(doc);

// изменить текст с указанным шрифтом
editor.ReplaceText("hello world", "hi world", 14);

// сохранить документ
doc.Save(outFile);
```

### См. также

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


