---
title: ReplaceText
second_title: Aspose.PDF لمرجع .NET API
description: يستبدل النص في ملف PDF بالصفحة المحددة.TextStateaspose.pdf.text/textstate يمكن تحديد الكائن عائلة الخط  اللون لاستبدال النص.
type: docs
weight: 450
url: /ar/net/aspose.pdf.facades/pdfcontenteditor/replacetext/
---
## ReplaceText(string, int, string, TextState) {#replacetext_1}

يستبدل النص في ملف PDF بالصفحة المحددة.[`TextState`](../../../aspose.pdf.text/textstate) يمكن تحديد الكائن (عائلة الخط ، اللون) لاستبدال النص.

```csharp
public bool ReplaceText(string srcString, int thePage, string destString, TextState textState)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| srcString | String | السلسلة المراد استبدالها. |
| thePage | Int32 | رقم الصفحة (0 تعني "كل الصفحات"). |
| destString | String | السلسلة المستبدلة. |
| textState | TextState | حالة النص (لون النص ، الخط ، إلخ). |

### قيمة الإرجاع

يعود صحيحا إذا تم الاستبدال.

### أمثلة

يوضح المثال كيفية استبدال النص في الصفحة الأولى من مستند PDF وتعيينه[`TextState`](../../../aspose.pdf.text/textstate) خصائص النص للنص الجديد.

```csharp
// فتح المستند
Document doc = new Document(inFile);

// إنشاء الخط ووضع علامة عليه ليتم تضمينه
Aspose.Pdf.Text.Font font = FontRepository.FindFont("Courier New");
font.IsEmbedded = true;

// إنشاء كائن PdfContentEditor لتحرير النص
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf(doc);

// إنشاء كائن حالة النص
TextState textState = new TextState();
textState.Font = font;
textState.FontSize = 17;
textState.FontStyle = FontStyle.Bold | FontStyle.Italic;
textState.ForegroundColor = Color.Red;

// تغيير النص بالخط المحدد
editor.ReplaceText("hello world", 1, "hi world", textState);

// حفظ الوثيقة
doc.Save(outFile);
```

### أنظر أيضا

* class [TextState](../../../aspose.pdf.text/textstate)
* class [PdfContentEditor](../../pdfcontenteditor)
* مساحة الاسم [Aspose.Pdf.Facades](../../pdfcontenteditor)
* المجسم [Aspose.PDF](../../../)

---

## ReplaceText(string, string) {#replacetext_2}

يستبدل النص في ملف PDF .

```csharp
public bool ReplaceText(string srcString, string destString)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| srcString | String | السلسلة المراد استبدالها. |
| destString | String | استبدال السلسلة. |

### قيمة الإرجاع

يعود صحيحا إذا تم الاستبدال.

### أمثلة

يوضح المثال كيفية استبدال النص في مستند PDF.

```csharp
// فتح المستند
Document doc = new Document(inFile);

// إنشاء كائن PdfContentEditor لتحرير النص
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf(doc);

// تغيير النص 
editor.ReplaceText("hello world", "hi world");

// حفظ الوثيقة
doc.Save(outFile);
```

### أنظر أيضا

* class [PdfContentEditor](../../pdfcontenteditor)
* مساحة الاسم [Aspose.Pdf.Facades](../../pdfcontenteditor)
* المجسم [Aspose.PDF](../../../)

---

## ReplaceText(string, int, string) {#replacetext}

يستبدل النص في ملف PDF بالصفحة المحددة.

```csharp
public bool ReplaceText(string srcString, int thePage, string destString)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| srcString | String | اللدغة المراد استبدالها. |
| thePage | Int32 | رقم الصفحة (0 لجميع الصفحات) |
| destString | String | استبدال السلسلة. |

### قيمة الإرجاع

يعود صحيحا إذا تم الاستبدال.

### أمثلة

يوضح المثال كيفية استبدال النص في مستند PDF على الصفحة المحددة.

```csharp
// فتح المستند
Document doc = new Document(inFile);

// إنشاء كائن PdfContentEditor لتحرير النص
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf(doc);

// تغيير النص 
editor.ReplaceText("hello world", 1, "hi world");

// حفظ الوثيقة
doc.Save(outFile);
```

### أنظر أيضا

* class [PdfContentEditor](../../pdfcontenteditor)
* مساحة الاسم [Aspose.Pdf.Facades](../../pdfcontenteditor)
* المجسم [Aspose.PDF](../../../)

---

## ReplaceText(string, string, TextState) {#replacetext_3}

يستبدل النص في ملف PDF باستخدام المحدد[`TextState`](../../../aspose.pdf.text/textstate) الكائن .

```csharp
public bool ReplaceText(string srcString, string destString, TextState textState)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| srcString | String | سيتم استبدال السلسلة |
| destString | String | استبدال السلسلة |
| textState | TextState | حالة النص (لون النص ، الخط ، إلخ) |

### قيمة الإرجاع

يعود صحيحا إذا تم الاستبدال.

### أمثلة

يوضح المثال كيفية استبدال النص والتعيين[`TextState`](../../../aspose.pdf.text/textstate) خصائص النص للنص الجديد.

```csharp
// فتح المستند
Document doc = new Document(inFile);

// إنشاء الخط ووضع علامة عليه ليتم تضمينه
Aspose.Pdf.Text.Font font = FontRepository.FindFont("Courier New");
font.IsEmbedded = true;

// إنشاء كائن PdfContentEditor لتحرير النص
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf(doc);

// إنشاء كائن حالة النص
TextState textState = new TextState();
textState.Font = font;
textState.FontStyle = FontStyle.Bold | FontStyle.Italic;

// تغيير النص بالخط المحدد
editor.ReplaceText("hello world", "hi world", textState);

// حفظ الوثيقة
doc.Save(outFile);
```

### أنظر أيضا

* class [TextState](../../../aspose.pdf.text/textstate)
* class [PdfContentEditor](../../pdfcontenteditor)
* مساحة الاسم [Aspose.Pdf.Facades](../../pdfcontenteditor)
* المجسم [Aspose.PDF](../../../)

---

## ReplaceText(string, string, int) {#replacetext_4}

يستبدل النص في ملف PDF ويعين حجم الخط.

```csharp
public bool ReplaceText(string srcString, string destString, int fontSize)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| srcString | String | سيتم استبدال السلسلة. |
| destString | String | استبدال السلسلة. |
| fontSize | Int32 | حجم الخط. |

### قيمة الإرجاع

يعود صحيحا إذا تم الاستبدال.

### أمثلة

يوضح المثال كيفية استبدال النص وتعيين حجم الخط للنص الجديد.

```csharp
// فتح المستند
Document doc = new Document(inFile);

// إنشاء الخط ووضع علامة عليه ليتم تضمينه
Aspose.Pdf.Text.Font font = FontRepository.FindFont("Courier New");
font.IsEmbedded = true;

// إنشاء كائن PdfContentEditor لتحرير النص
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf(doc);

// تغيير النص بالخط المحدد
editor.ReplaceText("hello world", "hi world", 14);

// حفظ الوثيقة
doc.Save(outFile);
```

### أنظر أيضا

* class [PdfContentEditor](../../pdfcontenteditor)
* مساحة الاسم [Aspose.Pdf.Facades](../../pdfcontenteditor)
* المجسم [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
