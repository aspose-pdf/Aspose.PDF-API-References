---
title: PdfContentEditor.ReplaceText
second_title: Aspose.PDF for .NET API Reference
description: طريقة PdfContentEditor. تستبدل النص في ملف PDF في الصفحة المحددة. يمكن تحديد لون عائلة خط كائن TextState للنص المستبدل
type: docs
weight: 450
url: /ar/net/aspose.pdf.facades/pdfcontenteditor/replacetext/
---
## ReplaceText(string, int, string, TextState) {#replacetext_1}

تستبدل النص في ملف PDF في الصفحة المحددة. يمكن تحديد كائن [`TextState`](../../../aspose.pdf.text/textstate/) (عائلة الخط، اللون) للنص المستبدل.

```csharp
public bool ReplaceText(string srcString, int thePage, string destString, TextState textState)
```

| Parameter | Type | Description |
| --- | --- | --- |
| srcString | String | السلسلة التي سيتم استبدالها. |
| thePage | Int32 | رقم الصفحة (0 يعني "جميع الصفحات"). |
| destString | String | السلسلة المستبدلة. |
| textState | TextState | حالة النص (لون النص، الخط، إلخ). |

### Return Value

ترجع true إذا تم الاستبدال.

## Examples

توضح المثال كيفية استبدال النص في الصفحة الأولى من مستند PDF وتعيين خصائص نص [`TextState`](../../../aspose.pdf.text/textstate/) للنص الجديد.

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

### See Also

* class [TextState](../../../aspose.pdf.text/textstate/)
* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ReplaceText(string, string) {#replacetext_2}

تستبدل النص في ملف PDF.

```csharp
public bool ReplaceText(string srcString, string destString)
```

| Parameter | Type | Description |
| --- | --- | --- |
| srcString | String | السلسلة التي سيتم استبدالها. |
| destString | String | السلسلة المستبدلة. |

### Return Value

ترجع true إذا تم الاستبدال.

## Examples

توضح المثال كيفية استبدال النص في مستند PDF.

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

### See Also

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ReplaceText(string, int, string) {#replacetext}

تستبدل النص في ملف PDF في الصفحة المحددة.

```csharp
public bool ReplaceText(string srcString, int thePage, string destString)
```

| Parameter | Type | Description |
| --- | --- | --- |
| srcString | String | السلسلة التي سيتم استبدالها. |
| thePage | Int32 | رقم الصفحة (0 لجميع الصفحات) |
| destString | String | السلسلة المستبدلة. |

### Return Value

ترجع true إذا تم الاستبدال.

## Examples

توضح المثال كيفية استبدال النص في مستند PDF في الصفحة المحددة.

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

### See Also

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ReplaceText(string, string, TextState) {#replacetext_3}

تستبدل النص في ملف PDF باستخدام كائن [`TextState`](../../../aspose.pdf.text/textstate/) المحدد.

```csharp
public bool ReplaceText(string srcString, string destString, TextState textState)
```

| Parameter | Type | Description |
| --- | --- | --- |
| srcString | String | السلسلة التي سيتم استبدالها |
| destString | String | السلسلة المستبدلة |
| textState | TextState | حالة النص (لون النص، الخط، إلخ) |

### Return Value

ترجع true إذا تم الاستبدال.

## Examples

توضح المثال كيفية استبدال النص وتعيين خصائص نص [`TextState`](../../../aspose.pdf.text/textstate/) للنص الجديد.

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

### See Also

* class [TextState](../../../aspose.pdf.text/textstate/)
* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ReplaceText(string, string, int) {#replacetext_4}

تستبدل النص في ملف PDF وتحدد حجم الخط.

```csharp
public bool ReplaceText(string srcString, string destString, int fontSize)
```

| Parameter | Type | Description |
| --- | --- | --- |
| srcString | String | السلسلة التي سيتم استبدالها. |
| destString | String | السلسلة المستبدلة. |
| fontSize | Int32 | حجم الخط. |

### Return Value

ترجع true إذا تم الاستبدال.

## Examples

توضح المثال كيفية استبدال النص وتحديد حجم الخط للنص الجديد.

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

### See Also

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)