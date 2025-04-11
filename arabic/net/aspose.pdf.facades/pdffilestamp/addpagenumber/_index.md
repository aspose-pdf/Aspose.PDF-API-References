---
title: PdfFileStamp.AddPageNumber
second_title: Aspose.PDF for .NET API Reference
description: طريقة PdfFileStamp. إضافة رقم الصفحة إلى الملف. قد يحتوي نص رقم الصفحة على علامة # والتي سيتم استبدالها برقم الصفحة. يتم وضع رقم الصفحة في أسفل الصفحة مركزيًا أفقيًا
type: docs
weight: 130
url: /ar/net/aspose.pdf.facades/pdffilestamp/addpagenumber/
---
## AddPageNumber(string) {#addpagenumber_4}

إضافة رقم الصفحة إلى الملف. قد يحتوي نص رقم الصفحة على علامة # والتي سيتم استبدالها برقم الصفحة. يتم وضع رقم الصفحة في أسفل الصفحة مركزيًا أفقيًا.

```csharp
public void AddPageNumber(string formatString)
```

| Parameter | Type | Description |
| --- | --- | --- |
| formatString | String | نص رقم الصفحة |

## Examples

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber("Page #");
fileStamp.Close();
```

### See Also

* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddPageNumber(FormattedText) {#addpagenumber}

يضيف رقم الصفحة إلى الصفحة. قد يحتوي رقم الصفحة على علامة # والتي سيتم استبدالها برقم الصفحة. يتم وضع رقم الصفحة في أسفل الصفحة مركزيًا أفقيًا.

```csharp
public void AddPageNumber(FormattedText formattedText)
```

| Parameter | Type | Description |
| --- | --- | --- |
| formattedText | FormattedText | سلسلة التنسيق لرقم الصفحة تمثل كـ FormattedText. |

## Examples

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber(new FormattedText("Page #"));
fileStamp.Close();
```

### See Also

* class [FormattedText](../../formattedtext/)
* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddPageNumber(string, int, float, float, float, float) {#addpagenumber_6}

يضيف رقم الصفحة إلى صفحات الوثيقة.

```csharp
public void AddPageNumber(string formatString, int position, float leftMargin, float rightMargin, 
    float topMargin, float bottomMargin)
```

| Parameter | Type | Description |
| --- | --- | --- |
| formatString | String | سلسلة التنسيق لرقم الصفحة. |
| position | Int32 | الموضع الذي سيتم وضع رقم الصفحة فيه على الصفحة. 0-أسفل الوسط، 1-أسفل اليمين، 2-أعلى اليمين، 3 - الجوانب اليمنى، 4 - أعلى الوسط، 5 - أسفل اليسار، 6 - الجوانب اليسرى، 7 - أعلى اليسار. يمكنك استخدام الثوابت التالية: PosBottomMiddle = 0، PosBottomRight = 1، PosUpperRight = 2، PosSidesRight = 3، PosUpperMiddle، PosBottomLeft = 5، PosSidesLeft، PosUpperLeft |
| leftMargin | Single | الهامش على الحافة اليسرى للصفحة. |
| rightMargin | Single | الهامش على الحافة اليمنى للصفحة. |
| topMargin | Single | الهامش على الحافة العليا للصفحة. |
| bottomMargin | Single | الهامش على الحافة السفلية للصفحة. |

## Examples

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber("Page #", PdfFileStamp.PosBottomLeft, 100, 100, 200, 200);
fileStamp.Close();
```

### See Also

* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddPageNumber(string, float, float) {#addpagenumber_7}

يضيف رقم الصفحة في الموضع المحدد على الصفحة.

```csharp
public void AddPageNumber(string formatString, float x, float y)
```

| Parameter | Type | Description |
| --- | --- | --- |
| formatString | String | سلسلة التنسيق. يمكن أن تحتوي سلسلة التنسيق على علامة # والتي سيتم استبدالها برقم الصفحة. |
| x | Single | إحداثي X لرقم الصفحة. |
| y | Single | إحداثي Y لرقم الصفحة. |

## Examples

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber(new FormattedText("Page  #"), 123, 357);
fileStamp.Close();
```

### See Also

* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddPageNumber(FormattedText, int, float, float, float, float) {#addpagenumber_2}

يضيف رقم الصفحة إلى صفحات الوثيقة.

```csharp
public void AddPageNumber(FormattedText formattedText, int position, float leftMargin, 
    float rightMargin, float topMargin, float bottomMargin)
```

| Parameter | Type | Description |
| --- | --- | --- |
| formattedText | FormattedText | كائن FormattedText الذي يمثل تنسيق رقم الصفحة وخصائص النص. |
| position | Int32 | الموضع الذي سيتم وضع رقم الصفحة فيه على الصفحة. 0-أسفل الوسط، 1-أسفل اليمين، 2-أعلى اليمين، 3 - الجوانب اليمنى، 4 - أعلى الوسط، 5 - أسفل اليسار، 6 - الجوانب اليسرى، 7 - أعلى اليسار. يمكنك استخدام الثوابت التالية: PosBottomMiddle = 0، PosBottomRight = 1، PosUpperRight = 2، PosSidesRight = 3، PosUpperMiddle، PosBottomLeft = 5، PosSidesLeft، PosUpperLeft |
| leftMargin | Single | الهامش على الحافة اليسرى للصفحة. |
| rightMargin | Single | الهامش على الحافة اليمنى للصفحة. |
| topMargin | Single | الهامش على الحافة العليا للصفحة. |
| bottomMargin | Single | الهامش على الحافة السفلية للصفحة. |

## Examples

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber(new FormattedText("Page #"), PdfFileStamp.PosBottomLeft, 100, 100, 200, 200);
fileStamp.Close();
```

### See Also

* class [FormattedText](../../formattedtext/)
* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddPageNumber(FormattedText, float, float) {#addpagenumber_3}

يضيف رقم الصفحة في الموضع المحدد على الصفحة.

```csharp
public void AddPageNumber(FormattedText formattedText, float x, float y)
```

| Parameter | Type | Description |
| --- | --- | --- |
| formattedText | FormattedText | نص منسق يمثل تنسيق رقم الصفحة وخصائص النص. يمكن أن تحتوي سلسلة التنسيق على علامة # والتي سيتم استبدالها برقم الصفحة. |
| x | Single | إحداثي X لرقم الصفحة. |
| y | Single | إحداثي Y لرقم الصفحة. |

## Examples

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber(new FormattedText("Page  #"), 123, 357);
fileStamp.Close();
```

### See Also

* class [FormattedText](../../formattedtext/)
* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddPageNumber(string, int) {#addpagenumber_5}

يضيف رقم الصفحة إلى الصفحات.

```csharp
public void AddPageNumber(string formatString, int position)
```

| Parameter | Type | Description |
| --- | --- | --- |
| formatString | String | تنسيق رقم الصفحة. قد يحتوي هذا النص على # والتي سيتم استبدالها برقم الصفحة. |
| position | Int32 | الموضع الذي سيتم وضع رقم الصفحة فيه على الصفحة. 0-أسفل الوسط، 1-أسفل اليمين، 2-أعلى اليمين، 3 - الجوانب اليمنى، 4 - أعلى الوسط، 5 - أسفل اليسار، 6 - الجوانب اليسرى، 7 - أعلى اليسار. يمكنك استخدام الثوابت التالية: PosBottomMiddle = 0، PosBottomRight = 1، PosUpperRight = 2، PosSidesRight = 3، PosUpperMiddle، PosBottomLeft = 5، PosSidesLeft، PosUpperLeft |

## Examples

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber("Page #", PdfFileStamp.PosUpperRight);
fileStamp.Close();
```

### See Also

* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddPageNumber(FormattedText, int) {#addpagenumber_1}

يضيف رقم الصفحة إلى الصفحات.

```csharp
public void AddPageNumber(FormattedText formattedText, int position)
```

| Parameter | Type | Description |
| --- | --- | --- |
| formattedText | FormattedText | كائن FormattedText الذي يحتوي على تنسيق رقم الصفحة وخصائص النص. قد يحتوي هذا النص على # والتي سيتم استبدالها برقم الصفحة. |
| position | Int32 | الموضع الذي سيتم وضع رقم الصفحة فيه على الصفحة. 0-أسفل الوسط، 1-أسفل اليمين، 2-أعلى اليمين، 3 - الجوانب اليمنى، 4 - أعلى الوسط، 5 - أسفل اليسار، 6 - الجوانب اليسرى، 7 - أعلى اليسار. يمكنك استخدام الثوابت التالية: PosBottomMiddle = 0، PosBottomRight = 1، PosUpperRight = 2، PosSidesRight = 3، PosUpperMiddle، PosBottomLeft = 5، PosSidesLeft، PosUpperLeft |

## Examples

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber("Page #", PdfFileStamp.PosUpperRight);
fileStamp.Close();
```

### See Also

* class [FormattedText](../../formattedtext/)
* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)