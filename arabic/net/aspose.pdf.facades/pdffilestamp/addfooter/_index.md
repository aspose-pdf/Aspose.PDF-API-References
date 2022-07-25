---
title: AddFooter
second_title: Aspose.PDF لمرجع .NET API
description: إضافة تذييل إلى صفحات المستند.
type: docs
weight: 150
url: /ar/net/aspose.pdf.facades/pdffilestamp/addfooter/
---
## AddFooter(FormattedText, float) {#addfooter}

إضافة تذييل إلى صفحات المستند.

```csharp
public void AddFooter(FormattedText formattedText, float bottomMargin)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| formattedText | FormattedText | كائن FormattedText يحتوي على نص التذييل وخصائص النص. |
| bottomMargin | Single | الهامش في أعلى الصفحة. |

### أمثلة

```csharp
PdfFileStamp stamp = new PdfFileStamp("input.pdf", "output.pdf");
stamp.AddFooter(new FormattedText("Foot of the page"), 10);
```

### أنظر أيضا

* class [FormattedText](../../formattedtext)
* class [PdfFileStamp](../../pdffilestamp)
* مساحة الاسم [Aspose.Pdf.Facades](../../pdffilestamp)
* المجسم [Aspose.PDF](../../../)

---

## AddFooter(FormattedText, float, float, float) {#addfooter_1}

إضافة تذييل إلى صفحات المستند.

```csharp
public void AddFooter(FormattedText formattedText, float bottomMargin, float leftMargin, 
    float rightMargin)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| formattedText | FormattedText | كائن FormattedText يحتوي على نص التذييل وخصائص النص. |
| bottomMargin | Single | الهامش في أسفل الصفحة. |
| leftMargin | Single | الهامش في الجانب الأيسر من الصفحة. |
| rightMargin | Single | الهامش في الجانب الأيمن من الصفحة. |

### أمثلة

```csharp
PdfFileStamp stamp = new PdfFileStamp("input.pdf", "output.pdf");
stamp.AddFooter(new FormattedText("Foot of the page"), 10, 50, 50);
```

### أنظر أيضا

* class [FormattedText](../../formattedtext)
* class [PdfFileStamp](../../pdffilestamp)
* مساحة الاسم [Aspose.Pdf.Facades](../../pdffilestamp)
* المجسم [Aspose.PDF](../../../)

---

## AddFooter(string, float) {#addfooter_4}

إضافة صورة كتذييل إلى صفحات المستند.

```csharp
public void AddFooter(string imageFile, float bottomMargin)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| imageFile | String | اسم ملف الصورة والمسار. |
| bottomMargin | Single | الهامش في أسفل الصفحة. |

### أمثلة

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
Stream input = new FileStream(TestSettings.GetInputFile("test.jpg"), FileMode.Open, FileAccess.Read);
fileStamp.AddFooter("image.jpg", 50);
fileStamp.Close();
```

### أنظر أيضا

* class [PdfFileStamp](../../pdffilestamp)
* مساحة الاسم [Aspose.Pdf.Facades](../../pdffilestamp)
* المجسم [Aspose.PDF](../../../)

---

## AddFooter(string, float, float, float) {#addfooter_5}

إضافة صورة كتذييل للصفحات.

```csharp
public void AddFooter(string imageFile, float bottomMargin, float leftMargin, float rightMargin)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| imageFile | String | Iamge اسم الملف والمسار. |
| bottomMargin | Single | الهامش في أسفل الصفحة. |
| leftMargin | Single | الهامش في الجانب الأيسر من الصفحة. |
| rightMargin | Single | الهامش في الجانب الأيمن من الصفحة. |

### أمثلة

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
Stream input = new FileStream(TestSettings.GetInputFile("test.jpg"), FileMode.Open, FileAccess.Read);
fileStamp.AddFooter("image.jpg", 50, 100, 100);
fileStamp.Close();
```

### أنظر أيضا

* class [PdfFileStamp](../../pdffilestamp)
* مساحة الاسم [Aspose.Pdf.Facades](../../pdffilestamp)
* المجسم [Aspose.PDF](../../../)

---

## AddFooter(Stream, float) {#addfooter_2}

إضافة صورة كتذييل للصفحة.

```csharp
public void AddFooter(Stream imageStream, float bottomMargin)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| imageStream | Stream | دفق يحتوي على بيانات الصورة. |
| bottomMargin | Single | الهامش في أسفل الصفحة. |

### أمثلة

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
Stream input = new FileStream(TestSettings.GetInputFile("test.jpg"), FileMode.Open, FileAccess.Read);
fileStamp.AddFooter(new FileStream("image.jpg", FileMode.Open, FileAccess.Read), 50);
fileStamp.Close();
```

### أنظر أيضا

* class [PdfFileStamp](../../pdffilestamp)
* مساحة الاسم [Aspose.Pdf.Facades](../../pdffilestamp)
* المجسم [Aspose.PDF](../../../)

---

## AddFooter(Stream, float, float, float) {#addfooter_3}

إضافة صورة كتذييل للصفحة.

```csharp
public void AddFooter(Stream imageStream, float bottomMargin, float leftMargin, float rightMargin)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| imageStream | Stream | دفق يحتوي على بيانات الصورة. |
| bottomMargin | Single | الهامش في أسفل الصفحة. |
| leftMargin | Single | الهامش في الجانب الأيسر من الصفحة. |
| rightMargin | Single | الهامش في الجانب الأيمن من الصفحة. |

### أمثلة

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
Stream input = new FileStream(TestSettings.GetInputFile("test.jpg"), FileMode.Open, FileAccess.Read);
fileStamp.AddFooter(new FileStream("image.jpg", FileMode.Open, FileAccess.Read), 50, 50, 50);
fileStamp.Close();
```

### أنظر أيضا

* class [PdfFileStamp](../../pdffilestamp)
* مساحة الاسم [Aspose.Pdf.Facades](../../pdffilestamp)
* المجسم [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
