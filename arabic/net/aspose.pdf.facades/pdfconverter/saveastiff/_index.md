---
title: SaveAsTIFF
second_title: Aspose.PDF لمرجع .NET API
description: يحول كل صفحات مستند pdf إلى صور ويحفظ الصور في ملف TIFF واحد.
type: docs
weight: 160
url: /ar/net/aspose.pdf.facades/pdfconverter/saveastiff/
---
## SaveAsTIFF(string) {#saveastiff_10}

يحول كل صفحات مستند pdf إلى صور ويحفظ الصور في ملف TIFF واحد.

```csharp
public void SaveAsTIFF(string outputFile)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| outputFile | String | ملف لحفظ صورة TIFF. |

### أمثلة

```csharp
[C#]
PdfConverter converter = new PdfConverter();
converter.BindPdf(@"D:\Test\test.pdf");
converter.DoConvert();
converter.SaveAsTIFF(@"D:\Test\test.tiff");	

[Visual Basic]
Dim converter As PdfConverter =  New PdfConverter() 
converter.BindPdf("D:\Test\test.pdf")
converter.DoConvert()
converter.SaveAsTIFF(@"D:\Test\test.tiff")
```

### أنظر أيضا

* class [PdfConverter](../../pdfconverter)
* مساحة الاسم [Aspose.Pdf.Facades](../../pdfconverter)
* المجسم [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, CompressionType) {#saveastiff_11}

يحول كل صفحات مستند pdf إلى صور ويحفظ الصور في ملف TIFF واحد.

```csharp
public void SaveAsTIFF(string outputFile, CompressionType compressionType)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| outputFile | String | ملف الإخراج. |
| compressionType | CompressionType | نوع الضغط. |

### أمثلة

```csharp
[C#]
PdfConverter converter = new PdfConverter();
converter.BindPdf(@"D:\Test\test.pdf");
converter.DoConvert();
converter.SaveAsTIFF(@"D:\Test\test.tiff");
[Visual Basic]
Dim converter As PdfConverter =  New PdfConverter()
converter.BindPdf("D:\Test\test.pdf")
converter.DoConvert()
converter.SaveAsTIFF(@"D:\Test\test.tiff")
```

### أنظر أيضا

* enum [CompressionType](../../../aspose.pdf.devices/compressiontype)
* class [PdfConverter](../../pdfconverter)
* مساحة الاسم [Aspose.Pdf.Facades](../../pdfconverter)
* المجسم [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, int, int) {#saveastiff_16}

يحول كل صفحات مستند pdf إلى صور ذات أبعاد ويحفظ الصور في ملف TIFF واحد.

```csharp
public void SaveAsTIFF(string outputFile, int imageWidth, int imageHeight)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| outputFile | String | اسم الملف المطلوب حفظ صورة TIFF |
| imageWidth | Int32 | عرض الصورة ، الوحدة بالبكسل. |
| imageHeight | Int32 | ارتفاع الصورة ، الوحدة بالبكسل. |

### أنظر أيضا

* class [PdfConverter](../../pdfconverter)
* مساحة الاسم [Aspose.Pdf.Facades](../../pdfconverter)
* المجسم [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, PageSize) {#saveastiff_14}

يحول كل صفحات مستند pdf إلى صور بحجم الصفحة ويحفظ الصور في ملف TIFF واحد.

```csharp
public void SaveAsTIFF(string outputFile, PageSize pageSize)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| outputFile | String | اسم الملف المطلوب حفظ صورة TIFF |
| pageSize | PageSize | حجم صفحة الصورة. |

### أنظر أيضا

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfConverter](../../pdfconverter)
* مساحة الاسم [Aspose.Pdf.Facades](../../pdfconverter)
* المجسم [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, PageSize, TiffSettings) {#saveastiff_15}

يحول كل صفحات مستند pdf إلى صور بحجم الصفحة ويحفظ الصور في ملف TIFF واحد.

```csharp
public void SaveAsTIFF(string outputFile, PageSize pageSize, TiffSettings settings)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| outputFile | String | اسم الملف المطلوب حفظ صورة TIFF |
| pageSize | PageSize | حجم صفحة الصورة. |
| settings | TiffSettings | كائن الإعدادات الذي يعرف معلمات TIFF. |

### أنظر أيضا

* class [PageSize](../../../aspose.pdf/pagesize)
* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings)
* class [PdfConverter](../../pdfconverter)
* مساحة الاسم [Aspose.Pdf.Facades](../../pdfconverter)
* المجسم [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, int, int, CompressionType) {#saveastiff_17}

يحول كل صفحات مستند pdf إلى صور ذات أبعاد ويحفظ الصور في ملف TIFF واحد.

```csharp
public void SaveAsTIFF(string outputFile, int imageWidth, int imageHeight, 
    CompressionType compressionType)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| outputFile | String | اسم الملف المطلوب حفظ صورة TIFF |
| imageWidth | Int32 | عرض الصورة ، الوحدة بالبكسل. |
| imageHeight | Int32 | ارتفاع الصورة ، الوحدة بالبكسل. |
| compressionType | CompressionType | نوع الضغط. |

### أنظر أيضا

* enum [CompressionType](../../../aspose.pdf.devices/compressiontype)
* class [PdfConverter](../../pdfconverter)
* مساحة الاسم [Aspose.Pdf.Facades](../../pdfconverter)
* المجسم [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, int, int, TiffSettings) {#saveastiff_18}

يحول كل صفحات مستند pdf إلى صور ذات أبعاد ويحفظ الصور في ملف TIFF واحد.

```csharp
public void SaveAsTIFF(string outputFile, int imageWidth, int imageHeight, TiffSettings settings)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| outputFile | String | اسم الملف المطلوب حفظ صورة TIFF |
| imageWidth | Int32 | عرض الصورة ، الوحدة بالبكسل. |
| imageHeight | Int32 | ارتفاع الصورة ، الوحدة بالبكسل. |
| settings | TiffSettings | كائن الإعدادات الذي يعرف معلمات TIFF. |

### أنظر أيضا

* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings)
* class [PdfConverter](../../pdfconverter)
* مساحة الاسم [Aspose.Pdf.Facades](../../pdfconverter)
* المجسم [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, int, int, TiffSettings, IIndexBitmapConverter) {#saveastiff_19}

يحول كل صفحات مستند pdf إلى صور ذات أبعاد ويحفظ الصور في ملف TIFF واحد.

```csharp
public void SaveAsTIFF(string outputFile, int imageWidth, int imageHeight, TiffSettings settings, 
    IIndexBitmapConverter converter)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| outputFile | String | اسم الملف المطلوب حفظ صورة TIFF |
| imageWidth | Int32 | عرض الصورة ، الوحدة بالبكسل. |
| imageHeight | Int32 | ارتفاع الصورة ، الوحدة بالبكسل. |
| settings | TiffSettings | كائن الإعدادات الذي يعرف معلمات TIFF. |
| converter | IIndexBitmapConverter | محول خارجي |

### أنظر أيضا

* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings)
* interface [IIndexBitmapConverter](../../../aspose.pdf/iindexbitmapconverter)
* class [PdfConverter](../../pdfconverter)
* مساحة الاسم [Aspose.Pdf.Facades](../../pdfconverter)
* المجسم [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream) {#saveastiff}

يحول كل صفحات مستند pdf إلى صور ويحفظ الصور في دفق TIFF واحد.

```csharp
public void SaveAsTIFF(Stream outputStream)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| outputStream | Stream | الدفق لحفظ صورة TIFF. |

### أنظر أيضا

* class [PdfConverter](../../pdfconverter)
* مساحة الاسم [Aspose.Pdf.Facades](../../pdfconverter)
* المجسم [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, CompressionType) {#saveastiff_1}

يحول كل صفحات مستند pdf إلى صور ويحفظ الصور في ملف TIFF واحد.

```csharp
public void SaveAsTIFF(Stream outputStream, CompressionType compressionType)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| outputStream | Stream | تيار الإخراج. |
| compressionType | CompressionType | نوع الضغط. |

### أنظر أيضا

* enum [CompressionType](../../../aspose.pdf.devices/compressiontype)
* class [PdfConverter](../../pdfconverter)
* مساحة الاسم [Aspose.Pdf.Facades](../../pdfconverter)
* المجسم [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, PageSize) {#saveastiff_4}

يحول كل صفحات مستند pdf إلى صور بحجم الصفحة ويحفظ الصور في دفق TIFF واحد.

```csharp
public void SaveAsTIFF(Stream outputStream, PageSize pageSize)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| outputStream | Stream | الدفق لحفظ صورة TIFF. |
| pageSize | PageSize | حجم صفحة الصورة. |

### أنظر أيضا

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfConverter](../../pdfconverter)
* مساحة الاسم [Aspose.Pdf.Facades](../../pdfconverter)
* المجسم [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, PageSize, TiffSettings) {#saveastiff_5}

يحول كل صفحات مستند pdf إلى صور بحجم الصفحة ويحفظ الصور في دفق TIFF واحد.

```csharp
public void SaveAsTIFF(Stream outputStream, PageSize pageSize, TiffSettings settings)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| outputStream | Stream | الدفق لحفظ صورة TIFF. |
| pageSize | PageSize | حجم صفحة الصورة. |
| settings | TiffSettings | كائن الإعدادات الذي يعرف معلمات TIFF. |

### أنظر أيضا

* class [PageSize](../../../aspose.pdf/pagesize)
* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings)
* class [PdfConverter](../../pdfconverter)
* مساحة الاسم [Aspose.Pdf.Facades](../../pdfconverter)
* المجسم [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, int, int) {#saveastiff_6}

يحول كل صفحات مستند pdf إلى صور ذات أبعاد ويحفظ الصور في دفق TIFF واحد.

```csharp
public void SaveAsTIFF(Stream outputStream, int imageWidth, int imageHeight)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| outputStream | Stream | الدفق لحفظ صورة TIFF. |
| imageWidth | Int32 | عرض الصورة ، الوحدة بالبكسل. |
| imageHeight | Int32 | ارتفاع الصورة ، الوحدة بالبكسل. |

### أنظر أيضا

* class [PdfConverter](../../pdfconverter)
* مساحة الاسم [Aspose.Pdf.Facades](../../pdfconverter)
* المجسم [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, int, int, CompressionType) {#saveastiff_7}

يحول كل صفحات مستند pdf إلى صور ذات أبعاد ويحفظ الصور في دفق TIFF واحد.

```csharp
public void SaveAsTIFF(Stream outputStream, int imageWidth, int imageHeight, 
    CompressionType compressionType)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| outputStream | Stream | الدفق لحفظ صورة TIFF. |
| imageWidth | Int32 | عرض الصورة ، الوحدة بالبكسل. |
| imageHeight | Int32 | ارتفاع الصورة ، الوحدة بالبكسل. |
| compressionType | CompressionType | نوع الضغط. |

### أنظر أيضا

* enum [CompressionType](../../../aspose.pdf.devices/compressiontype)
* class [PdfConverter](../../pdfconverter)
* مساحة الاسم [Aspose.Pdf.Facades](../../pdfconverter)
* المجسم [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, int, int, TiffSettings) {#saveastiff_8}

يحول كل صفحات مستند pdf إلى صور ذات أبعاد ويحفظ الصور في دفق TIFF واحد.

```csharp
public void SaveAsTIFF(Stream outputStream, int imageWidth, int imageHeight, TiffSettings settings)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| outputStream | Stream | الدفق لحفظ صورة TIFF. |
| imageWidth | Int32 | عرض الصورة ، الوحدة بالبكسل. |
| imageHeight | Int32 | ارتفاع الصورة ، الوحدة بالبكسل. |
| settings | TiffSettings | كائن الإعدادات الذي يعرف معلمات TIFF. |

### أنظر أيضا

* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings)
* class [PdfConverter](../../pdfconverter)
* مساحة الاسم [Aspose.Pdf.Facades](../../pdfconverter)
* المجسم [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, int, int, TiffSettings, IIndexBitmapConverter) {#saveastiff_9}

يحول كل صفحات مستند pdf إلى صور ذات أبعاد ويحفظ الصور في دفق TIFF واحد.

```csharp
public void SaveAsTIFF(Stream outputStream, int imageWidth, int imageHeight, TiffSettings settings, 
    IIndexBitmapConverter converter)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| outputStream | Stream | الدفق لحفظ صورة TIFF. |
| imageWidth | Int32 | عرض الصورة ، الوحدة بالبكسل. |
| imageHeight | Int32 | ارتفاع الصورة ، الوحدة بالبكسل. |
| settings | TiffSettings | كائن الإعدادات الذي يعرف معلمات TIFF. |
| converter | IIndexBitmapConverter | محول خارجي |

### أنظر أيضا

* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings)
* interface [IIndexBitmapConverter](../../../aspose.pdf/iindexbitmapconverter)
* class [PdfConverter](../../pdfconverter)
* مساحة الاسم [Aspose.Pdf.Facades](../../pdfconverter)
* المجسم [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, TiffSettings) {#saveastiff_12}

يحول كل صفحات مستند pdf إلى صور بها ويحفظ الصور في ملف TIFF واحد.

```csharp
public void SaveAsTIFF(string outputFile, TiffSettings settings)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| outputFile | String | اسم الملف المطلوب حفظ صورة TIFF |
| settings | TiffSettings | كائن الإعدادات الذي يعرف معلمات TIFF. |

### أنظر أيضا

* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings)
* class [PdfConverter](../../pdfconverter)
* مساحة الاسم [Aspose.Pdf.Facades](../../pdfconverter)
* المجسم [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, TiffSettings, IIndexBitmapConverter) {#saveastiff_13}

يحول كل صفحات مستند pdf إلى صور بها ويحفظ الصور في ملف TIFF واحد.

```csharp
public void SaveAsTIFF(string outputFile, TiffSettings settings, IIndexBitmapConverter converter)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| outputFile | String | اسم الملف المطلوب حفظ صورة TIFF |
| settings | TiffSettings | كائن الإعدادات الذي يعرف معلمات TIFF. |
| converter | IIndexBitmapConverter | محول خارجي |

### أنظر أيضا

* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings)
* interface [IIndexBitmapConverter](../../../aspose.pdf/iindexbitmapconverter)
* class [PdfConverter](../../pdfconverter)
* مساحة الاسم [Aspose.Pdf.Facades](../../pdfconverter)
* المجسم [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, TiffSettings) {#saveastiff_2}

يحول كل صفحات مستند pdf إلى صور ويحفظ الصور في دفق TIFF واحد.

```csharp
public void SaveAsTIFF(Stream outputStream, TiffSettings settings)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| outputStream | Stream | الدفق لحفظ صورة TIFF. |
| settings | TiffSettings | كائن الإعدادات الذي يعرف معلمات TIFF. |

### أنظر أيضا

* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings)
* class [PdfConverter](../../pdfconverter)
* مساحة الاسم [Aspose.Pdf.Facades](../../pdfconverter)
* المجسم [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, TiffSettings, IIndexBitmapConverter) {#saveastiff_3}

يحول كل صفحات مستند pdf إلى صور ويحفظ الصور في دفق TIFF واحد.

```csharp
public void SaveAsTIFF(Stream outputStream, TiffSettings settings, IIndexBitmapConverter converter)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| outputStream | Stream | الدفق لحفظ صورة TIFF. |
| settings | TiffSettings | كائن الإعدادات الذي يعرف معلمات TIFF. |
| converter | IIndexBitmapConverter | محول خارجي |

### أنظر أيضا

* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings)
* interface [IIndexBitmapConverter](../../../aspose.pdf/iindexbitmapconverter)
* class [PdfConverter](../../pdfconverter)
* مساحة الاسم [Aspose.Pdf.Facades](../../pdfconverter)
* المجسم [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
