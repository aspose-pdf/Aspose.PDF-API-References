---
title: PdfFileStamp.AddHeader
second_title: Aspose.PDF for .NET API Reference
description: طريقة PdfFileStamp. تضيف رأسًا إلى الصفحة
type: docs
weight: 120
url: /ar/net/aspose.pdf.facades/pdffilestamp/addheader/
---
## AddHeader(FormattedText, float) {#addheader}

تضيف رأسًا إلى الصفحة.

```csharp
public void AddHeader(FormattedText formattedText, float topMargin)
```

| Parameter | Type | Description |
| --- | --- | --- |
| formattedText | FormattedText | نص الرأس وخصائص النص. |
| topMargin | Single | الهامش في أعلى الصفحة. |

## Examples

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddHeader(new FormattedText("Head of the page"), 50);
fileStamp.Close();
```

### See Also

* class [FormattedText](../../formattedtext/)
* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddHeader(FormattedText, float, float, float) {#addheader_1}

تضيف رأسًا إلى صفحات الملف.

```csharp
public void AddHeader(FormattedText formattedText, float topMargin, float leftMargin, 
    float rightMargin)
```

| Parameter | Type | Description |
| --- | --- | --- |
| formattedText | FormattedText | كائن نص منسق يحتوي على نص الصفحة وخصائصه. |
| topMargin | Single | الهامش في أعلى الصفحة. |
| leftMargin | Single | الهامش على الجانب الأيسر من الصفحة. |
| rightMargin | Single | الهامش على الجانب الأيمن من الصفحة. |

## Examples

```csharp
PdfFileStamp stamp = new PdfFileStamp("input.pdf", "output.pdf");
stamp.AddHeader(new FormattedText("Head of the page"), 10, 50, 50);
```

### See Also

* class [FormattedText](../../formattedtext/)
* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddHeader(string, float) {#addheader_4}

تضيف صورة كرأس إلى صفحات الملف.

```csharp
public void AddHeader(string imageFile, float topMargin)
```

| Parameter | Type | Description |
| --- | --- | --- |
| imageFile | String | مسار ملف الصورة. |
| topMargin | Single | الهامش في أعلى الصفحة. |

## Examples

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
Stream input = new FileStream(TestSettings.GetInputFile("test.jpg"), FileMode.Open, FileAccess.Read);
fileStamp.AddHeader("image.jpg", 50);
fileStamp.Close();
```

### See Also

* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddHeader(string, float, float, float) {#addheader_5}

تضيف صورة كرأس على الصفحات.

```csharp
public void AddHeader(string imageFile, float topMargin, float leftMargin, float rightMargin)
```

| Parameter | Type | Description |
| --- | --- | --- |
| imageFile | String | مسار ملف الصورة. |
| topMargin | Single | الهامش في أعلى الصفحة. |
| leftMargin | Single | الهامش على الجانب الأيسر من الصفحة. |
| rightMargin | Single | الهامش على الجانب الأيمن من الصفحة. |

## Examples

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
Stream input = new FileStream(TestSettings.GetInputFile("test.jpg"), FileMode.Open, FileAccess.Read);
fileStamp.AddHeader("image.jpg", 50, 100, 100);
fileStamp.Close();
```

### See Also

* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddHeader(Stream, float) {#addheader_2}

تضيف صورة كرأس على الصفحات.

```csharp
public void AddHeader(Stream imageStream, float topMargin)
```

| Parameter | Type | Description |
| --- | --- | --- |
| imageStream | Stream | تدفق الصورة. |
| topMargin | Single | الهامش في أعلى الصفحة. |

## Examples

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
Stream input = new FileStream(TestSettings.GetInputFile("test.jpg"), FileMode.Open, FileAccess.Read);
fileStamp.AddHeader(new FileStream("image.jpg", FileMode.Open, FileAccess.Read), 50);
fileStamp.Close();
```

### See Also

* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddHeader(Stream, float, float, float) {#addheader_3}

تضيف صورة في أعلى الصفحة.

```csharp
public void AddHeader(Stream inputStream, float topMargin, float leftMargin, float rightMargin)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | Stream | تدفق يحتوي على بيانات الصورة. |
| topMargin | Single | الهامش في أعلى الصفحة. |
| leftMargin | Single | الهامش على الجانب الأيسر من الصفحة. |
| rightMargin | Single | الهامش على الجانب الأيمن من الصفحة. |

## Examples

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
Stream input = new FileStream(TestSettings.GetInputFile("test.jpg"), FileMode.Open, FileAccess.Read);
fileStamp.AddHeader(new FileStream("image.jpg", FileMode.Open, FileAccess.Read), 50, 100, 100);
fileStamp.Close();
```

### See Also

* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)