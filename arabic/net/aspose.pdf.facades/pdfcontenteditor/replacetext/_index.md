---
title: "PdfContentEditor.ReplaceText"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة PdfContentEditor. تستبدل النص في ملف PDF في الصفحة المحددة. يمكن تحديد عائلة الخط واللون لكائن TextState للنص المستبدل"
type: docs
weight: 450
url: /ar/net/aspose.pdf.facades/pdfcontenteditor/replacetext/
---
## ReplaceText(string, int, string, TextState) {#replacetext_1}

يستبدل النص في ملف PDF في الصفحة المحددة. يمكن تحديد كائن [`TextState`](../../../aspose.pdf.text/textstate/) (عائلة الخط، اللون) للنص المستبدل.

```csharp
public bool ReplaceText(string srcString, int thePage, string destString, TextState textState)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| srcString | String | السلسلة المراد استبدالها. |
| thePage | Int32 | رقم الصفحة (0 يعني "جميع الصفحات"). |
| destString | String | السلسلة المستبدلة. |
| textState | TextState | حالة النص (لون النص، الخط، إلخ). |

### قيمة الإرجاع

يرجع true إذا تم الاستبدال.

## أمثلة

يوضح المثال كيفية استبدال النص في الصفحة الأولى من مستند PDF وتعيين خصائص النص لكائن [`TextState`](../../../aspose.pdf.text/textstate/) للنص الجديد.

```csharp
// فتح المستند
Document doc = new Document(inFile);

// إنشاء خط وتحديده ليتم تضمينه
Aspose.Pdf.Text.Font font = FontRepository.FindFont("Courier New");
font.IsEmbedded = true;

// إنشاء كائن PdfContentEditor لتعديل النص
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf(doc);

// إنشاء كائن textState
TextState textState = new TextState();
textState.Font = font;
textState.FontSize = 17;
textState.FontStyle = FontStyle.Bold | FontStyle.Italic;
textState.ForegroundColor = Color.Red;

// تغيير النص باستخدام الخط المحدد
editor.ReplaceText("hello world", 1, "hi world", textState);

// حفظ المستند
doc.Save(outFile);
```

### انظر أيضًا

* class [TextState](../../../aspose.pdf.text/textstate/)
* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ReplaceText(string, string) {#replacetext_2}

يستبدل النص في ملف PDF.

```csharp
public bool ReplaceText(string srcString, string destString)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| srcString | String | السلسلة المراد استبدالها. |
| destString | String | استبدال السلسلة. |

### قيمة الإرجاع

يرجع true إذا تم الاستبدال.

## أمثلة

يوضح المثال كيفية استبدال النص في مستند PDF.

```csharp
// فتح المستند
Document doc = new Document(inFile);

// إنشاء كائن PdfContentEditor لتعديل النص
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf(doc);

// تغيير النص 
editor.ReplaceText("hello world", "hi world");

// حفظ المستند
doc.Save(outFile);
```

### انظر أيضًا

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ReplaceText(string, int, string) {#replacetext}

يستبدل النص في ملف PDF في الصفحة المحددة.

```csharp
public bool ReplaceText(string srcString, int thePage, string destString)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| srcString | String | السلسلة المراد استبدالها. |
| thePage | Int32 | رقم الصفحة (0 لجميع الصفحات) |
| destString | String | استبدال السلسلة. |

### قيمة الإرجاع

يرجع true إذا تم الاستبدال.

## أمثلة

يوضح المثال كيفية استبدال النص في مستند PDF في الصفحة المحددة.

```csharp
// فتح المستند
Document doc = new Document(inFile);

// إنشاء كائن PdfContentEditor لتعديل النص
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf(doc);

// تغيير النص 
editor.ReplaceText("hello world", 1, "hi world");

// حفظ المستند
doc.Save(outFile);
```

### انظر أيضًا

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ReplaceText(string, string, TextState) {#replacetext_3}

يستبدل النص في ملف PDF باستخدام كائن [`TextState`](../../../aspose.pdf.text/textstate/) المحدد.

```csharp
public bool ReplaceText(string srcString, string destString, TextState textState)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| srcString | String | النص المراد استبداله |
| destString | String | استبدال النص |
| textState | TextState | حالة النص (لون النص، الخط إلخ) |

### قيمة الإرجاع

يرجع true إذا تم الاستبدال.

## أمثلة

يوضح المثال كيفية استبدال النص وتعيين خصائص نص [`TextState`](../../../aspose.pdf.text/textstate/) للنص الجديد.

```csharp
// فتح المستند
Document doc = new Document(inFile);

// إنشاء خط وتحديده ليتم تضمينه
Aspose.Pdf.Text.Font font = FontRepository.FindFont("Courier New");
font.IsEmbedded = true;

// إنشاء كائن PdfContentEditor لتعديل النص
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf(doc);

// إنشاء كائن textState
TextState textState = new TextState();
textState.Font = font;
textState.FontStyle = FontStyle.Bold | FontStyle.Italic;

// تغيير النص باستخدام الخط المحدد
editor.ReplaceText("hello world", "hi world", textState);

// حفظ المستند
doc.Save(outFile);
```

### انظر أيضًا

* class [TextState](../../../aspose.pdf.text/textstate/)
* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ReplaceText(string, string, int) {#replacetext_4}

يستبدل النص في ملف PDF ويضبط حجم الخط.

```csharp
public bool ReplaceText(string srcString, string destString, int fontSize)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| srcString | String | النص المراد استبداله. |
| destString | String | استبدال السلسلة. |
| fontSize | Int32 | حجم الخط. |

### قيمة الإرجاع

يرجع true إذا تم الاستبدال.

## أمثلة

يوضح المثال كيفية استبدال النص وتعيين حجم الخط للنص الجديد.

```csharp
// فتح المستند
Document doc = new Document(inFile);

// إنشاء خط وتحديده ليتم تضمينه
Aspose.Pdf.Text.Font font = FontRepository.FindFont("Courier New");
font.IsEmbedded = true;

// إنشاء كائن PdfContentEditor لتعديل النص
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf(doc);

// تغيير النص باستخدام الخط المحدد
editor.ReplaceText("hello world", "hi world", 14);

// حفظ المستند
doc.Save(outFile);
```

### انظر أيضًا

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


