---
title: PdfFileStamp.AddFooter
second_title: Aspose.PDF for .NET API Reference
description: طريقة PdfFileStamp. يضيف تذييلًا إلى صفحات المستند
type: docs
weight: 110
url: /ar/net/aspose.pdf.facades/pdffilestamp/addfooter/
---
## AddFooter(FormattedText, float) {#addfooter}

يضيف تذييلًا إلى صفحات المستند.

```csharp
public void AddFooter(FormattedText formattedText, float bottomMargin)
```

| Parameter     | Type          | Description                                                             |
| ------------- | ------------- | ----------------------------------------------------------------------- |
| formattedText | FormattedText | كائن FormattedText الذي يحتوي على نص التذييل وخصائص النص.              |
| bottomMargin  | Single        | هامش في أعلى الصفحة.                                                   |

## أمثلة

```csharp
PdfFileStamp stamp = new PdfFileStamp("input.pdf", "output.pdf");
stamp.AddFooter(new FormattedText("Foot of the page"), 10);
```

### انظر أيضًا

* فئة [FormattedText](../../formattedtext/)
* فئة [PdfFileStamp](../)
* مساحة الاسم [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* التجميع [Aspose.PDF](../../../)

---

## AddFooter(FormattedText, float, float, float) {#addfooter_1}

يضيف تذييلًا إلى صفحات المستند.

```csharp
public void AddFooter(FormattedText formattedText, float bottomMargin, float leftMargin, 
    float rightMargin)
```

| Parameter     | Type          | Description                                                      |
| ------------- | ------------- | ---------------------------------------------------------------- |
| formattedText | FormattedText | كائن FormattedText الذي يحتوي على نص التذييل وخصائص النص.         |
| bottomMargin  | Single        | هامش في أسفل الصفحة.                                             |
| leftMargin    | Single        | هامش في الجانب الأيسر من الصفحة.                                |
| rightMargin   | Single        | هامش في الجانب الأيمن من الصفحة.                                |

## أمثلة

```csharp
PdfFileStamp stamp = new PdfFileStamp("input.pdf", "output.pdf");
stamp.AddFooter(new FormattedText("Foot of the page"), 10, 50, 50);
```

### انظر أيضًا

* فئة [FormattedText](../../formattedtext/)
* فئة [PdfFileStamp](../)
* مساحة الاسم [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* التجميع [Aspose.PDF](../../../)

---

## AddFooter(string, float) {#addfooter_4}

يضيف صورة كتذييل لصفحات المستند.

```csharp
public void AddFooter(string imageFile, float bottomMargin)
```

| Parameter   | Type   | Description                     |
| ----------- | ------ | ------------------------------- |
| imageFile   | String | اسم ملف الصورة والمسار.         |
| bottomMargin| Single | هامش في أسفل الصفحة.             |

## أمثلة

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
Stream input = new FileStream(TestSettings.GetInputFile("test.jpg"), FileMode.Open, FileAccess.Read);
fileStamp.AddFooter("image.jpg", 50);
fileStamp.Close();
```

### انظر أيضًا

* فئة [PdfFileStamp](../)
* مساحة الاسم [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* التجميع [Aspose.PDF](../../../)

---

## AddFooter(string, float, float, float) {#addfooter_5}

يضيف صورة كتذييل للصفحات.

```csharp
public void AddFooter(string imageFile, float bottomMargin, float leftMargin, float rightMargin)
```

| Parameter   | Type   | Description                                  |
| ----------- | ------ | -------------------------------------------- |
| imageFile   | String | Iamge file name and path.                    |
| bottomMargin| Single | هامش في أسفل الصفحة.                         |
| leftMargin  | Single | هامش في الجانب الأيسر من الصفحة.            |
| rightMargin | Single | هامش في الجانب الأيمن من الصفحة.            |

## أمثلة

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
Stream input = new FileStream(TestSettings.GetInputFile("test.jpg"), FileMode.Open, FileAccess.Read);
fileStamp.AddFooter("image.jpg", 50, 100, 100);
fileStamp.Close();
```

### انظر أيضًا

* فئة [PdfFileStamp](../)
* مساحة الاسم [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* التجميع [Aspose.PDF](../../../)

---

## AddFooter(Stream, float) {#addfooter_2}

يضيف صورة كتذييل للصفحة.

```csharp
public void AddFooter(Stream imageStream, float bottomMargin)
```

| Parameter    | Type   | Description                              |
| ------------ | ------ | ---------------------------------------- |
| imageStream  | Stream | Stream يحتوي على بيانات الصورة.         |
| bottomMargin | Single | هامش في أسفل الصفحة.                      |

## أمثلة

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
Stream input = new FileStream(TestSettings.GetInputFile("test.jpg"), FileMode.Open, FileAccess.Read);
fileStamp.AddFooter(new FileStream("image.jpg", FileMode.Open, FileAccess.Read), 50);
fileStamp.Close();
```

### انظر أيضًا

* فئة [PdfFileStamp](../)
* مساحة الاسم [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* التجميع [Aspose.PDF](../../../)

---

## AddFooter(Stream, float, float, float) {#addfooter_3}

يضيف صورة كتذييل للصفحة.

```csharp
public void AddFooter(Stream imageStream, float bottomMargin, float leftMargin, float rightMargin)
```

| Parameter    | Type   | Description                              |
| ------------ | ------ | ---------------------------------------- |
| imageStream  | Stream | Stream يحتوي على بيانات الصورة.         |
| bottomMargin | Single | هامش في أسفل الصفحة.                      |
| leftMargin   | Single | هامش في الجانب الأيسر من الصفحة.            |
| rightMargin  | Single | هامش في الجانب الأيمن من الصفحة.            |

## أمثلة

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
Stream input = new FileStream(TestSettings.GetInputFile("test.jpg"), FileMode.Open, FileAccess.Read);
fileStamp.AddFooter(new FileStream("image.jpg", FileMode.Open, FileAccess.Read), 50, 50, 50);
fileStamp.Close();
```

### انظر أيضًا

* فئة [PdfFileStamp](../)
* مساحة الاسم [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* التجميع [Aspose.PDF](../../../)