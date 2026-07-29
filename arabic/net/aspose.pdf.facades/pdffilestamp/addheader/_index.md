---
title: "PdfFileStamp.AddHeader"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة PdfFileStamp. تضيف رأسًا إلى الصفحة."
type: docs
weight: 120
url: /ar/net/aspose.pdf.facades/pdffilestamp/addheader/
---
## AddHeader(FormattedText, float) {#addheader}

يضيف رأسًا إلى الصفحة.

```csharp
public void AddHeader(FormattedText formattedText, float topMargin)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| formattedText | FormattedText | نص الرأس وخصائص النص. |
| topMargin | Single | الهامش في أعلى الصفحة. |

## أمثلة

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddHeader(new FormattedText("Head of the page"), 50);
fileStamp.Close();
```

### انظر أيضًا

* class [FormattedText](../../formattedtext/)
* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddHeader(FormattedText, float, float, float) {#addheader_1}

يضيف رأسًا إلى صفحات الملف.

```csharp
public void AddHeader(FormattedText formattedText, float topMargin, float leftMargin, 
    float rightMargin)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| formattedText | FormattedText | كائن النص المنسق الذي يحتوي على نص الصفحة وخصائصه. |
| topMargin | Single | الهامش في أعلى الصفحة. |
| leftMargin | Single | الهامش في الجانب الأيسر من الصفحة. |
| rightMargin | Single | الهامش في الجانب الأيمن من الصفحة. |

## أمثلة

```csharp
PdfFileStamp stamp = new PdfFileStamp("input.pdf", "output.pdf");
stamp.AddHeader(new FormattedText("Head of the page"), 10, 50, 50);
```

### انظر أيضًا

* class [FormattedText](../../formattedtext/)
* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddHeader(string, float) {#addheader_4}

يضيف صورة ك رأس إلى صفحات الملف.

```csharp
public void AddHeader(string imageFile, float topMargin)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| imageFile | String | المسار إلى ملف الصورة. |
| topMargin | Single | الهامش في أعلى الصفحة. |

## أمثلة

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
Stream input = new FileStream(TestSettings.GetInputFile("test.jpg"), FileMode.Open, FileAccess.Read);
fileStamp.AddHeader("image.jpg", 50);
fileStamp.Close();
```

### انظر أيضًا

* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddHeader(string, float, float, float) {#addheader_5}

يضيف صورة ك رأس على الصفحات.

```csharp
public void AddHeader(string imageFile, float topMargin, float leftMargin, float rightMargin)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| imageFile | String | المسار إلى ملف الصورة. |
| topMargin | Single | الهامش في أعلى الصفحة. |
| leftMargin | Single | الهامش في الجانب الأيسر من الصفحة. |
| rightMargin | Single | الهامش في الجانب الأيمن من الصفحة. |

## أمثلة

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
Stream input = new FileStream(TestSettings.GetInputFile("test.jpg"), FileMode.Open, FileAccess.Read);
fileStamp.AddHeader("image.jpg", 50, 100, 100);
fileStamp.Close();
```

### انظر أيضًا

* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddHeader(Stream, float) {#addheader_2}

يضيف صورة ك رأس على الصفحات.

```csharp
public void AddHeader(Stream imageStream, float topMargin)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| imageStream | Stream | المجري الخاص بالصورة. |
| topMargin | Single | الهامش في أعلى الصفحة. |

## أمثلة

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
Stream input = new FileStream(TestSettings.GetInputFile("test.jpg"), FileMode.Open, FileAccess.Read);
fileStamp.AddHeader(new FileStream("image.jpg", FileMode.Open, FileAccess.Read), 50);
fileStamp.Close();
```

### انظر أيضًا

* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddHeader(Stream, float, float, float) {#addheader_3}

يضيف صورة في أعلى الصفحة.

```csharp
public void AddHeader(Stream inputStream, float topMargin, float leftMargin, float rightMargin)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| inputStream | Stream | دفق يحتوي على بيانات الصورة. |
| topMargin | Single | الهامش في أعلى الصفحة. |
| leftMargin | Single | الهامش في الجانب الأيسر من الصفحة. |
| rightMargin | Single | الهامش في الجانب الأيمن من الصفحة. |

## أمثلة

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
Stream input = new FileStream(TestSettings.GetInputFile("test.jpg"), FileMode.Open, FileAccess.Read);
fileStamp.AddHeader(new FileStream("image.jpg", FileMode.Open, FileAccess.Read), 50, 100, 100);
fileStamp.Close();
```

### انظر أيضًا

* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


