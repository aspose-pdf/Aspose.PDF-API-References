---
title: "PdfFileStamp.AddFooter"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة PdfFileStamp. يضيف تذييلًا إلى صفحات المستند"
type: docs
weight: 110
url: /ar/net/aspose.pdf.facades/pdffilestamp/addfooter/
---
## AddFooter(FormattedText, float) {#addfooter}

يضيف تذييلًا إلى صفحات المستند.

```csharp
public void AddFooter(FormattedText formattedText, float bottomMargin)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| formattedText | FormattedText | كائن FormattedText الذي يحتوي على نص التذييل وخصائص النص. |
| bottomMargin | Single | الهامش في أعلى الصفحة. |

## أمثلة

```csharp
PdfFileStamp stamp = new PdfFileStamp("input.pdf", "output.pdf");
stamp.AddFooter(new FormattedText("Foot of the page"), 10);
```

### انظر أيضًا

* class [FormattedText](../../formattedtext/)
* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddFooter(FormattedText, float, float, float) {#addfooter_1}

يضيف تذييلًا إلى صفحات المستند.

```csharp
public void AddFooter(FormattedText formattedText, float bottomMargin, float leftMargin, 
    float rightMargin)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| formattedText | FormattedText | كائن FormattedText الذي يحتوي على نص التذييل وخصائص النص. |
| bottomMargin | Single | الهامش في أسفل الصفحة. |
| leftMargin | Single | الهامش في الجانب الأيسر من الصفحة. |
| rightMargin | Single | الهامش في الجانب الأيمن من الصفحة. |

## أمثلة

```csharp
PdfFileStamp stamp = new PdfFileStamp("input.pdf", "output.pdf");
stamp.AddFooter(new FormattedText("Foot of the page"), 10, 50, 50);
```

### انظر أيضًا

* class [FormattedText](../../formattedtext/)
* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddFooter(string, float) {#addfooter_4}

يضيف صورة ك تذييل إلى صفحات المستند.

```csharp
public void AddFooter(string imageFile, float bottomMargin)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| imageFile | String | اسم ملف الصورة والمسار. |
| bottomMargin | Single | الهامش في أسفل الصفحة. |

## أمثلة

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
Stream input = new FileStream(TestSettings.GetInputFile("test.jpg"), FileMode.Open, FileAccess.Read);
fileStamp.AddFooter("image.jpg", 50);
fileStamp.Close();
```

### انظر أيضًا

* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddFooter(string, float, float, float) {#addfooter_5}

يضيف صورة ك تذييل للصفحات.

```csharp
public void AddFooter(string imageFile, float bottomMargin, float leftMargin, float rightMargin)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| imageFile | String | اسم ملف الصورة والمسار. |
| bottomMargin | Single | الهامش في أسفل الصفحة. |
| leftMargin | Single | الهامش في الجانب الأيسر من الصفحة. |
| rightMargin | Single | الهامش في الجانب الأيمن من الصفحة. |

## أمثلة

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
Stream input = new FileStream(TestSettings.GetInputFile("test.jpg"), FileMode.Open, FileAccess.Read);
fileStamp.AddFooter("image.jpg", 50, 100, 100);
fileStamp.Close();
```

### انظر أيضًا

* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddFooter(Stream, float) {#addfooter_2}

يضيف صورة ك تذييل للصفحة.

```csharp
public void AddFooter(Stream imageStream, float bottomMargin)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| imageStream | Stream | المجري يحتوي على بيانات الصورة. |
| bottomMargin | Single | الهامش في أسفل الصفحة. |

## أمثلة

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
Stream input = new FileStream(TestSettings.GetInputFile("test.jpg"), FileMode.Open, FileAccess.Read);
fileStamp.AddFooter(new FileStream("image.jpg", FileMode.Open, FileAccess.Read), 50);
fileStamp.Close();
```

### انظر أيضًا

* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddFooter(Stream, float, float, float) {#addfooter_3}

يضيف صورة ك تذييل للصفحة.

```csharp
public void AddFooter(Stream imageStream, float bottomMargin, float leftMargin, float rightMargin)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| imageStream | Stream | المجري يحتوي على بيانات الصورة. |
| bottomMargin | Single | الهامش في أسفل الصفحة. |
| leftMargin | Single | الهامش في الجانب الأيسر من الصفحة. |
| rightMargin | Single | الهامش في الجانب الأيمن من الصفحة. |

## أمثلة

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
Stream input = new FileStream(TestSettings.GetInputFile("test.jpg"), FileMode.Open, FileAccess.Read);
fileStamp.AddFooter(new FileStream("image.jpg", FileMode.Open, FileAccess.Read), 50, 50, 50);
fileStamp.Close();
```

### انظر أيضًا

* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


