---
title: Produce
second_title: Aspose.PDF لمرجع .NET API
description: قم بإنتاج دفق PDF باستخدام تنسيق الاستيراد المحدد. يوضح هذا النموذج كيفية إنتاج دفق Pdf من دفق CGM.
type: docs
weight: 10
url: /ar/net/aspose.pdf.facades/pdfproducer/produce/
---
## Produce(Stream, ImportFormat, Stream) {#produce}

قم بإنتاج دفق PDF باستخدام تنسيق الاستيراد المحدد. يوضح هذا النموذج كيفية إنتاج دفق Pdf من دفق CGM.

```csharp
string inputFile = "myImage.cgm";
string outputFile = "myPdf.pdf";
using (FileStream inputStream = File.OpenRead(inputFile))
using (FileStream outputStream = File.Create(outputFile))
{
    PdfProducer.Produce(inputStream, ImportFormat.Cgm, outputStream);
}
```

```csharp
public static void Produce(Stream inputStream, ImportFormat format, Stream outputStream)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| inputStream | Stream | تيار الإدخال. |
| format | ImportFormat | تنسيق الاستيراد. |
| outputStream | Stream | إخراج دفق PDF. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception) | يتم طرح الاستثناء عندما يكون الملف غير صالح. |
| ArgumentNullException | دفق الإدخال أو الإخراج فارغ |

### أنظر أيضا

* enum [ImportFormat](../../../aspose.pdf/importformat)
* class [PdfProducer](../../pdfproducer)
* مساحة الاسم [Aspose.Pdf.Facades](../../pdfproducer)
* المجسم [Aspose.PDF](../../../)

---

## Produce(string, ImportFormat, Stream) {#produce_4}

قم بإنتاج دفق PDF باستخدام تنسيق الاستيراد المحدد. يوضح هذا النموذج كيفية إنتاج دفق Pdf من ملف CGM.

```csharp
string inputFile = "myImage.cgm";
string outputFile = "myPdf.pdf";
using (FileStream outputStream = File.Create(outputFile))
{
    PdfProducer.Produce(inputFile, ImportFormat.Cgm, outputStream);
}
```

```csharp
public static void Produce(string inputFileName, ImportFormat format, Stream outputStream)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| inputFileName | String | اسم ملف الإدخال. |
| format | ImportFormat | تنسيق الاستيراد. |
| outputStream | Stream | إخراج دفق PDF. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception) | يتم طرح الاستثناء عندما يكون الملف غير صالح. |
| ArgumentNullException | دفق الإخراج فارغ |
| ArgumentException | اسم ملف الإدخال عبارة عن سلسلة فارغة |

### أنظر أيضا

* enum [ImportFormat](../../../aspose.pdf/importformat)
* class [PdfProducer](../../pdfproducer)
* مساحة الاسم [Aspose.Pdf.Facades](../../pdfproducer)
* المجسم [Aspose.PDF](../../../)

---

## Produce(Stream, ImportFormat, string) {#produce_1}

قم بإنتاج ملف PDF باستخدام تنسيق الاستيراد المحدد. يوضح هذا النموذج كيفية إنتاج ملف Pdf من دفق CGM.

```csharp
string inputFile = "myImage.cgm";
string outputFile = "myPdf.pdf";
using (FileStream inputStream = File.OpenRead(inputFile))
using (FileStream outputStream = File.Create(outputFile))
{
    PdfProducer.Produce(inputStream, ImportFormat.Cgm, outputStream);
}
```

```csharp
public static void Produce(Stream inputStream, ImportFormat format, string outputFileName)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| inputStream | Stream | تيار الإدخال. |
| format | ImportFormat | تنسيق الاستيراد. |
| outputFileName | String | إخراج ملف PDF |

### استثناءات

| استثناء | حالة |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception) | يتم طرح الاستثناء عندما يكون الملف غير صالح. |
| ArgumentNullException | دفق الإدخال فارغ |
| ArgumentException | اسم ملف الإخراج عبارة عن سلسلة فارغة |

### أنظر أيضا

* enum [ImportFormat](../../../aspose.pdf/importformat)
* class [PdfProducer](../../pdfproducer)
* مساحة الاسم [Aspose.Pdf.Facades](../../pdfproducer)
* المجسم [Aspose.PDF](../../../)

---

## Produce(string, ImportFormat, string) {#produce_5}

قم بإنتاج ملف PDF باستخدام تنسيق الاستيراد المحدد. يوضح هذا النموذج كيفية إنتاج ملف Pdf من ملف CGM.

```csharp
string inputFile = "myImage.cgm";
string outputFile = "myPdf.pdf";
PdfProducer.Produce(inputFile, ImportFormat.Cgm, outputFile);
```

```csharp
public static void Produce(string inputFileName, ImportFormat format, string outputFileName)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| inputFileName | String | اسم ملف الإدخال. |
| format | ImportFormat | تنسيق الاستيراد. |
| outputFileName | String | إخراج ملف PDF |

### استثناءات

| استثناء | حالة |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception) | يتم طرح الاستثناء عندما يكون الملف غير صالح. |
| ArgumentException | اسم ملف الإدخال أو الإخراج عبارة عن سلسلة فارغة |

### أنظر أيضا

* enum [ImportFormat](../../../aspose.pdf/importformat)
* class [PdfProducer](../../pdfproducer)
* مساحة الاسم [Aspose.Pdf.Facades](../../pdfproducer)
* المجسم [Aspose.PDF](../../../)

---

## Produce(string, ImportOptions, Stream) {#produce_6}

قم بإنتاج دفق PDF باستخدام خيار الاستيراد المحدد. يوضح هذا النموذج كيفية إنتاج دفق Pdf من ملف CGM.

```csharp
string inputFile = "myImage.cgm";
string outputFile = "myPdf.pdf";
ImportOptions importOptions = new CgmImportOptions();
using (FileStream outputStream = File.Create(outputFile))
{
    PdfProducer.Produce(inputFile, importOptions, outputStream);
}
```

```csharp
public static void Produce(string inputFileName, ImportOptions options, Stream outputStream)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| inputFileName | String | اسم ملف الإدخال. |
| options | ImportOptions | خيار الاستيراد. |
| outputStream | Stream | إخراج دفق PDF. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception) | يتم طرح الاستثناء عندما يكون الملف غير صالح. |
| ArgumentNullException | دفق الإخراج فارغ |
| ArgumentException | اسم ملف الإدخال عبارة عن سلسلة فارغة |

### أنظر أيضا

* class [ImportOptions](../../../aspose.pdf/importoptions)
* class [PdfProducer](../../pdfproducer)
* مساحة الاسم [Aspose.Pdf.Facades](../../pdfproducer)
* المجسم [Aspose.PDF](../../../)

---

## Produce(Stream, ImportOptions, string) {#produce_3}

قم بإنتاج ملف PDF باستخدام خيار الاستيراد المحدد. يوضح هذا النموذج كيفية إنتاج ملف Pdf من دفق CGM.

```csharp
string inputFile = "myImage.cgm";
string outputFile = "myPdf.pdf";
ImportOptions importOptions = new CgmImportOptions();
using (FileStream inputStream = File.OpenRead(inputFile))
{
    PdfProducer.Produce(inputStream, importOptions, outputFile);
}
```

```csharp
public static void Produce(Stream inputStream, ImportOptions options, string outputFileName)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| inputStream | Stream | تيار الإدخال. |
| options | ImportOptions | خيار الاستيراد. |
| outputFileName | String | إخراج ملف PDF. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception) | يتم طرح الاستثناء عندما يكون الملف غير صالح. |
| ArgumentNullException | دفق الإدخال فارغ |
| ArgumentException | اسم ملف الإخراج عبارة عن سلسلة فارغة |

### أنظر أيضا

* class [ImportOptions](../../../aspose.pdf/importoptions)
* class [PdfProducer](../../pdfproducer)
* مساحة الاسم [Aspose.Pdf.Facades](../../pdfproducer)
* المجسم [Aspose.PDF](../../../)

---

## Produce(string, ImportOptions, string) {#produce_7}

قم بإنتاج ملف PDF باستخدام خيار الاستيراد المحدد. يوضح هذا النموذج كيفية إنتاج ملف Pdf من ملف CGM.

```csharp
string inputFile = "myImage.cgm";
string outputFile = "myPdf.pdf";
ImportOptions importOptions = new CgmImportOptions();
PdfProducer.Produce(inputStream, importOptions, outputStream);
```

```csharp
public static void Produce(string inputFileName, ImportOptions options, string outputFileName)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| inputFileName | String | اسم ملف الإدخال. |
| options | ImportOptions | خيار الاستيراد. |
| outputFileName | String | إخراج دفق PDF. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception) | يتم طرح الاستثناء عندما يكون الملف غير صالح. |
| ArgumentException | اسم ملف الإدخال أو الإخراج عبارة عن سلسلة فارغة |

### أنظر أيضا

* class [ImportOptions](../../../aspose.pdf/importoptions)
* class [PdfProducer](../../pdfproducer)
* مساحة الاسم [Aspose.Pdf.Facades](../../pdfproducer)
* المجسم [Aspose.PDF](../../../)

---

## Produce(Stream, ImportOptions, Stream) {#produce_2}

قم بإنتاج ملف PDF باستخدام خيار الاستيراد المحدد. يوضح هذا النموذج كيفية إنتاج دفق Pdf من دفق CGM.

```csharp
string inputFile = "myImage.cgm";
string outputFile = "myPdf.pdf";
ImportOptions importOptions = new CgmImportOptions();
using (FileStream inputStream = File.OpenRead(inputFile))
using (FileStream outputStream = File.Create(outputFile))
{
    PdfProducer.Produce(inputStream, importOptions, outputStream);
}
```

```csharp
public static void Produce(Stream inputStream, ImportOptions options, Stream outputStream)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| inputStream | Stream | تيار الإدخال. |
| options | ImportOptions | خيار الاستيراد. |
| outputStream | Stream | إخراج دفق PDF. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception) | يتم طرح الاستثناء عندما يكون الملف غير صالح. |
| ArgumentNullException | دفق الإدخال أو الإخراج فارغ. |

### أنظر أيضا

* class [ImportOptions](../../../aspose.pdf/importoptions)
* class [PdfProducer](../../pdfproducer)
* مساحة الاسم [Aspose.Pdf.Facades](../../pdfproducer)
* المجسم [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
