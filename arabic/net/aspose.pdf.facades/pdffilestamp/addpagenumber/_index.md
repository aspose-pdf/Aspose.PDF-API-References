---
title: "PdfFileStamp.AddPageNumber"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة PdfFileStamp. إضافة رقم الصفحة إلى الملف. قد يحتوي نص رقم الصفحة على علامة # التي سيتم استبدالها برقم الصفحة. يتم وضع رقم الصفحة في أسفل الصفحة متمركزًا أفقيًا."
type: docs
weight: 130
url: /ar/net/aspose.pdf.facades/pdffilestamp/addpagenumber/
---
## AddPageNumber(string) {#addpagenumber_4}

يضيف رقم الصفحة إلى الملف. قد يحتوي نص رقم الصفحة على علامة # التي سيتم استبدالها برقم الصفحة. يتم وضع رقم الصفحة في أسفل الصفحة مركّزًا أفقيًا.

```csharp
public void AddPageNumber(string formatString)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| formatString | String | نص رقم الصفحة |

## أمثلة

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber("Page #");
fileStamp.Close();
```

### انظر أيضًا

* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddPageNumber(FormattedText) {#addpagenumber}

يضيف رقم الصفحة إلى الصفحة. قد يحتوي رقم الصفحة على علامة # التي سيتم استبدالها برقم الصفحة. يتم وضع رقم الصفحة في أسفل الصفحة مركّزًا أفقيًا.

```csharp
public void AddPageNumber(FormattedText formattedText)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| formattedText | FormattedText | سلسلة التنسيق لرقم الصفحة تمثل كـ FormattedText. |

## أمثلة

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber(new FormattedText("Page #"));
fileStamp.Close();
```

### انظر أيضًا

* class [FormattedText](../../formattedtext/)
* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddPageNumber(string, int, float, float, float, float) {#addpagenumber_6}

يضيف رقم الصفحة إلى صفحات المستند.

```csharp
public void AddPageNumber(string formatString, int position, float leftMargin, float rightMargin, 
    float topMargin, float bottomMargin)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| formatString | String | سلسلة التنسيق لرقم الصفحة. |
| الموضع | Int32 | الموضع الذي سيتم وضع رقم الصفحة فيه على الصفحة. 0-أسفل وسط، 1-أسفل يمين، 2-أعلى يمين، 3-الجانبين يمين، 4-أعلى وسط،5-أسفل يسار،6-الجانبين يسار،7-أعلى يسار. يمكنك استخدام الثوابت التالية: PosBottomMiddle = 0, PosBottomRight = 1, PosUpperRight = 2, PosSidesRight = 3, PosUpperMiddle, PosBottomLeft = 5, PosSidesLeft, PosUpperLeft |
| leftMargin | Single | الهامش على الحافة اليسرى للصفحة. |
| rightMargin | Single | الهامش على الحافة اليمنى للصفحة. |
| topMargin | Single | الهامش على الحافة العلوية للصفحة. |
| bottomMargin | Single | الهامش على الحافة السفلية للصفحة. |

## أمثلة

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber("Page #", PdfFileStamp.PosBottomLeft, 100, 100, 200, 200);
fileStamp.Close();
```

### انظر أيضًا

* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddPageNumber(string, float, float) {#addpagenumber_7}

يضيف رقم الصفحة في الموضع المحدد على الصفحة.

```csharp
public void AddPageNumber(string formatString, float x, float y)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| formatString | String | سلسلة التنسيق. يمكن أن تحتوي سلسلة التنسيق على علامة # التي سيتم استبدالها برقم الصفحة. |
| x | Single | الإحداثي X لرقم الصفحة. |
| y | Single | الإحداثي Y لرقم الصفحة. |

## أمثلة

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber(new FormattedText("Page  #"), 123, 357);
fileStamp.Close();
```

### انظر أيضًا

* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddPageNumber(FormattedText, int, float, float, float, float) {#addpagenumber_2}

يضيف رقم الصفحة إلى صفحات المستند.

```csharp
public void AddPageNumber(FormattedText formattedText, int position, float leftMargin, 
    float rightMargin, float topMargin, float bottomMargin)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| formattedText | FormattedText | كائن FormattedText الذي يمثل تنسيق رقم الصفحة وخصائص النص. |
| الموضع | Int32 | الموضع الذي سيتم وضع رقم الصفحة فيه على الصفحة. 0-أسفل وسط، 1-أسفل يمين، 2-أعلى يمين، 3-الجانبين يمين، 4-أعلى وسط،5-أسفل يسار،6-الجانبين يسار،7-أعلى يسار. يمكنك استخدام الثوابت التالية: PosBottomMiddle = 0, PosBottomRight = 1, PosUpperRight = 2, PosSidesRight = 3, PosUpperMiddle, PosBottomLeft = 5, PosSidesLeft, PosUpperLeft |
| leftMargin | Single | الهامش على الحافة اليسرى للصفحة. |
| rightMargin | Single | الهامش على الحافة اليمنى للصفحة. |
| topMargin | Single | الهامش على الحافة العلوية للصفحة. |
| bottomMargin | Single | الهامش على الحافة السفلية للصفحة. |

## أمثلة

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber(new FormattedText("Page #"), PdfFileStamp.PosBottomLeft, 100, 100, 200, 200);
fileStamp.Close();
```

### انظر أيضًا

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

| معامل | النوع | الوصف |
| --- | --- | --- |
| formattedText | FormattedText | النص المنسق الذي يمثل تنسيق رقم الصفحة وخصائص النص. يمكن أن يحتوي سلسلة التنسيق على علامة # التي سيتم استبدالها برقم الصفحة. |
| x | Single | الإحداثي X لرقم الصفحة. |
| y | Single | الإحداثي Y لرقم الصفحة. |

## أمثلة

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber(new FormattedText("Page  #"), 123, 357);
fileStamp.Close();
```

### انظر أيضًا

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

| معامل | النوع | الوصف |
| --- | --- | --- |
| formatString | String | تنسيق رقم الصفحة. قد يحتوي هذا النص على # التي سيتم استبدالها برقم الصفحة. |
| الموضع | Int32 | الموضع الذي سيتم وضع رقم الصفحة فيه على الصفحة. 0-أسفل وسط، 1-أسفل يمين، 2-أعلى يمين، 3-الجانبين يمين، 4-أعلى وسط،5-أسفل يسار،6-الجانبين يسار،7-أعلى يسار. يمكنك استخدام الثوابت التالية: PosBottomMiddle = 0, PosBottomRight = 1, PosUpperRight = 2, PosSidesRight = 3, PosUpperMiddle, PosBottomLeft = 5, PosSidesLeft, PosUpperLeft |

## أمثلة

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber("Page #", PdfFileStamp.PosUpperRight);
fileStamp.Close();
```

### انظر أيضًا

* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddPageNumber(FormattedText, int) {#addpagenumber_1}

يضيف رقم الصفحة إلى الصفحات.

```csharp
public void AddPageNumber(FormattedText formattedText, int position)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| formattedText | FormattedText | كائن FormattedText الذي يحتوي على تنسيق رقم الصفحة وخصائص النص. قد يحتوي هذا النص على # التي سيتم استبدالها برقم الصفحة. |
| الموضع | Int32 | الموضع الذي سيتم وضع رقم الصفحة فيه على الصفحة. 0-أسفل وسط، 1-أسفل يمين، 2-أعلى يمين، 3-الجانبين يمين، 4-أعلى وسط،5-أسفل يسار،6-الجانبين يسار،7-أعلى يسار. يمكنك استخدام الثوابت التالية: PosBottomMiddle = 0, PosBottomRight = 1, PosUpperRight = 2, PosSidesRight = 3, PosUpperMiddle, PosBottomLeft = 5, PosSidesLeft, PosUpperLeft |

## أمثلة

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber("Page #", PdfFileStamp.PosUpperRight);
fileStamp.Close();
```

### انظر أيضًا

* class [FormattedText](../../formattedtext/)
* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


