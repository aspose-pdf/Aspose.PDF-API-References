---
title: AddPageNumber
second_title: Aspose.PDF لمرجع .NET API
description: أضف رقم الصفحة إلى الملف. قد يحتوي نص رقم الصفحة على علامة  والتي سيتم استبدالها برقم الصفحة. يتم وضع رقم الصفحة في أسفل الصفحة يتم توسيطه أفقيًا.
type: docs
weight: 170
url: /ar/net/aspose.pdf.facades/pdffilestamp/addpagenumber/
---
## AddPageNumber(string) {#addpagenumber_4}

أضف رقم الصفحة إلى الملف. قد يحتوي نص رقم الصفحة على علامة # والتي سيتم استبدالها برقم الصفحة. يتم وضع رقم الصفحة في أسفل الصفحة يتم توسيطه أفقيًا.

```csharp
public void AddPageNumber(string formatString)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| formatString | String | نص رقم الصفحة |

### أمثلة

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber("Page #");
fileStamp.Close();
```

### أنظر أيضا

* class [PdfFileStamp](../../pdffilestamp)
* مساحة الاسم [Aspose.Pdf.Facades](../../pdffilestamp)
* المجسم [Aspose.PDF](../../../)

---

## AddPageNumber(FormattedText) {#addpagenumber}

يضيف رقم الصفحة إلى الصفحة. قد يحتوي رقم الصفحة على علامة # والتي سيتم استبدالها برقم الصفحة . يتم وضع رقم الصفحة في أسفل الصفحة في المنتصف أفقيًا .

```csharp
public void AddPageNumber(FormattedText formattedText)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| formattedText | FormattedText | تمثل سلسلة التنسيق لرقم الصفحة على أنها FormattedText. |

### أمثلة

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber(new FormattedText("Page #"));
fileStamp.Close();
```

### أنظر أيضا

* class [FormattedText](../../formattedtext)
* class [PdfFileStamp](../../pdffilestamp)
* مساحة الاسم [Aspose.Pdf.Facades](../../pdffilestamp)
* المجسم [Aspose.PDF](../../../)

---

## AddPageNumber(string, int, float, float, float, float) {#addpagenumber_6}

يضيف رقم الصفحة إلى صفحات المستند.

```csharp
public void AddPageNumber(string formatString, int position, float leftMargin, float rightMargin, 
    float topMargin, float bottomMargin)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| formatString | String | سلسلة تنسيق لرقم الصفحة. |
| position | Int32 | الموضع حيث سيتم وضع رقم الصفحة على الصفحة. 0 - الوسط السفلي ، 1 - أسفل اليمين ، 2 - أعلى اليمين ، 3 - الجوانب اليمنى ، 4 - الوسط العلوي ، 5 - اليسار السفلي ، 6 - الجوانب اليسرى ، 7 - اليسار العلوي. يمكنك استخدام الثوابت التالية: PosBottomMiddle = 0 ، PosBottomRight = 1 ، PosUpperRight = 2 ، PosSidesRight = 3 ، PosUpperMiddle ، PosBottomLeft = 5 ، PosSidesLeft ، PosUpperLeft |
| leftMargin | Single | الهامش على الحافة اليسرى من الصفحة. |
| rightMargin | Single | الهامش على الحافة اليمنى من الصفحة. |
| topMargin | Single | الهامش على الحافة العلوية للصفحة. |
| bottomMargin | Single | الهامش على الحافة السفلية للصفحة. |

### أمثلة

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber("Page #", PdfFileStamp.PosBottomLeft, 100, 100, 200, 200);
fileStamp.Close();
```

### أنظر أيضا

* class [PdfFileStamp](../../pdffilestamp)
* مساحة الاسم [Aspose.Pdf.Facades](../../pdffilestamp)
* المجسم [Aspose.PDF](../../../)

---

## AddPageNumber(string, float, float) {#addpagenumber_7}

يضيف رقم الصفحة في الموضع المحدد بالصفحة.

```csharp
public void AddPageNumber(string formatString, float x, float y)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| formatString | String | تنسيق السلسلة. يمكن أن تحتوي سلسلة التنسيق على علامة # والتي سيتم استبدالها برقم الصفحة. |
| x | Single | تنسيق X لرقم الصفحة. |
| y | Single | تنسيق Y لرقم الصفحة. |

### أمثلة

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber(new FormattedText("Page  #"), 123, 357);
fileStamp.Close();
```

### أنظر أيضا

* class [PdfFileStamp](../../pdffilestamp)
* مساحة الاسم [Aspose.Pdf.Facades](../../pdffilestamp)
* المجسم [Aspose.PDF](../../../)

---

## AddPageNumber(FormattedText, int, float, float, float, float) {#addpagenumber_2}

يضيف رقم الصفحة إلى صفحات المستند.

```csharp
public void AddPageNumber(FormattedText formattedText, int position, float leftMargin, 
    float rightMargin, float topMargin, float bottomMargin)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| formattedText | FormattedText | كائن FormattedText يمثل تنسيق رقم الصفحة وخصائصه في النص. |
| position | Int32 | الموضع حيث سيتم وضع رقم الصفحة على الصفحة. 0 - الوسط السفلي ، 1 - أسفل اليمين ، 2 - أعلى اليمين ، 3 - الجوانب اليمنى ، 4 - الوسط العلوي ، 5 - اليسار السفلي ، 6 - الجوانب اليسرى ، 7 - اليسار العلوي. يمكنك استخدام الثوابت التالية: PosBottomMiddle = 0 ، PosBottomRight = 1 ، PosUpperRight = 2 ، PosSidesRight = 3 ، PosUpperMiddle ، PosBottomLeft = 5 ، PosSidesLeft ، PosUpperLeft |
| leftMargin | Single | الهامش على الحافة اليسرى من الصفحة. |
| rightMargin | Single | الهامش على الحافة اليمنى من الصفحة. |
| topMargin | Single | الهامش على الحافة العلوية للصفحة. |
| bottomMargin | Single | الهامش على الحافة السفلية للصفحة. |

### أمثلة

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber(new FormattedText("Page #"), PdfFileStamp.PosBottomLeft, 100, 100, 200, 200);
fileStamp.Close();
```

### أنظر أيضا

* class [FormattedText](../../formattedtext)
* class [PdfFileStamp](../../pdffilestamp)
* مساحة الاسم [Aspose.Pdf.Facades](../../pdffilestamp)
* المجسم [Aspose.PDF](../../../)

---

## AddPageNumber(FormattedText, float, float) {#addpagenumber_3}

يضيف رقم الصفحة في الموضع المحدد بالصفحة.

```csharp
public void AddPageNumber(FormattedText formattedText, float x, float y)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| formattedText | FormattedText | نص منسق يمثل تنسيق رقم الصفحة وخصائص النص . يمكن أن تحتوي سلسلة التنسيق على علامة # والتي سيتم استبدالها برقم الصفحة. |
| x | Single | تنسيق X لرقم الصفحة. |
| y | Single | تنسيق Y لرقم الصفحة. |

### أمثلة

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber(new FormattedText("Page  #"), 123, 357);
fileStamp.Close();
```

### أنظر أيضا

* class [FormattedText](../../formattedtext)
* class [PdfFileStamp](../../pdffilestamp)
* مساحة الاسم [Aspose.Pdf.Facades](../../pdffilestamp)
* المجسم [Aspose.PDF](../../../)

---

## AddPageNumber(string, int) {#addpagenumber_5}

يضيف رقم الصفحة إلى الصفحات.

```csharp
public void AddPageNumber(string formatString, int position)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| formatString | String | تنسيق رقم الصفحة. قد يحتوي هذا النص على # والتي سيتم استبدالها برقم الصفحة. |
| position | Int32 | الموضع حيث سيتم وضع رقم الصفحة على الصفحة. 0 - الوسط السفلي ، 1 - أسفل اليمين ، 2 - أعلى اليمين ، 3 - الجوانب اليمنى ، 4 - الوسط العلوي ، 5 - اليسار السفلي ، 6 - الجوانب اليسرى ، 7 - اليسار العلوي. يمكنك استخدام الثوابت التالية: PosBottomMiddle = 0 ، PosBottomRight = 1 ، PosUpperRight = 2 ، PosSidesRight = 3 ، PosUpperMiddle ، PosBottomLeft = 5 ، PosSidesLeft ، PosUpperLeft |

### أمثلة

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber("Page #", PdfFileStamp.PosUpperRight);
fileStamp.Close();
```

### أنظر أيضا

* class [PdfFileStamp](../../pdffilestamp)
* مساحة الاسم [Aspose.Pdf.Facades](../../pdffilestamp)
* المجسم [Aspose.PDF](../../../)

---

## AddPageNumber(FormattedText, int) {#addpagenumber_1}

يضيف رقم الصفحة إلى الصفحات.

```csharp
public void AddPageNumber(FormattedText formattedText, int position)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| formattedText | FormattedText | كائن FormattedText يحتوي على تنسيق رقم الصفحة وخصائص النص. قد يحتوي هذا النص على # والتي سيتم استبدالها برقم الصفحة. |
| position | Int32 | الموضع حيث سيتم وضع رقم الصفحة على الصفحة. 0 - الوسط السفلي ، 1 - أسفل اليمين ، 2 - أعلى اليمين ، 3 - الجوانب اليمنى ، 4 - الوسط العلوي ، 5 - اليسار السفلي ، 6 - الجوانب اليسرى ، 7 - اليسار العلوي. يمكنك استخدام الثوابت التالية: PosBottomMiddle = 0 ، PosBottomRight = 1 ، PosUpperRight = 2 ، PosSidesRight = 3 ، PosUpperMiddle ، PosBottomLeft = 5 ، PosSidesLeft ، PosUpperLeft |

### أمثلة

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber("Page #", PdfFileStamp.PosUpperRight);
fileStamp.Close();
```

### أنظر أيضا

* class [FormattedText](../../formattedtext)
* class [PdfFileStamp](../../pdffilestamp)
* مساحة الاسم [Aspose.Pdf.Facades](../../pdffilestamp)
* المجسم [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
