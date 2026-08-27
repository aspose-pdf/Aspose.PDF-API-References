---
title: "PdfProducer.Produce"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة PdfProducer. إنتاج تدفق PDF باستخدام تنسيق الاستيراد المحدد. يوضح هذا المثال كيفية إنتاج تدفق PDF من تدفق CGM."
type: docs
weight: 10
url: /ar/net/aspose.pdf.facades/pdfproducer/produce/
---
## Produce(Stream, ImportFormat, Stream) {#produce}

إنتاج تدفق PDF باستخدام تنسيق الاستيراد المحدد. يوضح هذا المثال كيفية إنتاج تدفق Pdf من تدفق CGM.

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

| معامل | النوع | الوصف |
| --- | --- | --- |
| inputStream | Stream | تدفق الإدخال. |
| format | ImportFormat | تنسيق الاستيراد. |
| outputStream | Stream | تدفق PDF الناتج. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception/) | يتم إلقاء الاستثناء عندما يكون الملف غير صالح. |
| ArgumentNullException | تدفق الإدخال أو الإخراج هو null |

### انظر أيضًا

* enum [ImportFormat](../../../aspose.pdf/importformat/)
* class [PdfProducer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Produce(string, ImportFormat, Stream) {#produce_4}

إنتاج تدفق PDF باستخدام تنسيق الاستيراد المحدد. يوضح هذا المثال كيفية إنتاج تدفق Pdf من ملف CGM.

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

| معامل | النوع | الوصف |
| --- | --- | --- |
| inputFileName | String | اسم ملف الإدخال. |
| format | ImportFormat | تنسيق الاستيراد. |
| outputStream | Stream | تدفق PDF الناتج. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception/) | يتم إلقاء الاستثناء عندما يكون الملف غير صالح. |
| ArgumentNullException | تدفق الإخراج هو null |
| ArgumentException | اسم ملف الإدخال هو سلسلة فارغة |

### انظر أيضًا

* enum [ImportFormat](../../../aspose.pdf/importformat/)
* class [PdfProducer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Produce(Stream, ImportFormat, string) {#produce_1}

إنتاج ملف PDF باستخدام تنسيق الاستيراد المحدد. يوضح هذا المثال كيفية إنتاج ملف Pdf من تدفق CGM.

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

| معامل | النوع | الوصف |
| --- | --- | --- |
| inputStream | Stream | تدفق الإدخال. |
| format | ImportFormat | تنسيق الاستيراد. |
| outputFileName | String | ملف PDF الناتج |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception/) | يتم إلقاء الاستثناء عندما يكون الملف غير صالح. |
| ArgumentNullException | تدفق الإدخال هو null |
| ArgumentException | اسم ملف الإخراج هو سلسلة فارغة |

### انظر أيضًا

* enum [ImportFormat](../../../aspose.pdf/importformat/)
* class [PdfProducer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Produce(string, ImportFormat, string) {#produce_5}

إنتاج ملف PDF باستخدام تنسيق الاستيراد المحدد. يوضح هذا المثال كيفية إنتاج ملف Pdf من ملف CGM.

```csharp
string inputFile = "myImage.cgm";
string outputFile = "myPdf.pdf";
PdfProducer.Produce(inputFile, ImportFormat.Cgm, outputFile);
```

```csharp
public static void Produce(string inputFileName, ImportFormat format, string outputFileName)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| inputFileName | String | اسم ملف الإدخال. |
| format | ImportFormat | تنسيق الاستيراد. |
| outputFileName | String | ملف PDF الناتج |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception/) | يتم إلقاء الاستثناء عندما يكون الملف غير صالح. |
| ArgumentException | اسم ملف الإدخال أو الإخراج هو سلسلة فارغة |

### انظر أيضًا

* enum [ImportFormat](../../../aspose.pdf/importformat/)
* class [PdfProducer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Produce(string, ImportOptions, Stream) {#produce_6}

إنتاج تدفق PDF باستخدام خيار الاستيراد المحدد. يوضح هذا المثال كيفية إنتاج تدفق Pdf من ملف CGM.

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

| معامل | النوع | الوصف |
| --- | --- | --- |
| inputFileName | String | اسم ملف الإدخال. |
| options | ImportOptions | خيار الاستيراد. |
| outputStream | Stream | تدفق PDF الناتج. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception/) | يتم إلقاء الاستثناء عندما يكون الملف غير صالح. |
| ArgumentNullException | تدفق الإخراج هو null |
| ArgumentException | اسم ملف الإدخال هو سلسلة فارغة |

### انظر أيضًا

* class [ImportOptions](../../../aspose.pdf/importoptions/)
* class [PdfProducer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Produce(Stream, ImportOptions, string) {#produce_3}

إنتاج ملف PDF باستخدام خيار الاستيراد المحدد. يوضح هذا المثال كيفية إنتاج ملف Pdf من تدفق CGM.

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

| معامل | النوع | الوصف |
| --- | --- | --- |
| inputStream | Stream | تدفق الإدخال. |
| options | ImportOptions | خيار الاستيراد. |
| outputFileName | String | ملف PDF الناتج. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception/) | يتم إلقاء الاستثناء عندما يكون الملف غير صالح. |
| ArgumentNullException | تدفق الإدخال هو null |
| ArgumentException | اسم ملف الإخراج هو سلسلة فارغة |

### انظر أيضًا

* class [ImportOptions](../../../aspose.pdf/importoptions/)
* class [PdfProducer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Produce(string, ImportOptions, string) {#produce_7}

إنتاج ملف PDF باستخدام خيار الاستيراد المحدد. يوضح هذا المثال كيفية إنتاج ملف Pdf من ملف CGM.

```csharp
string inputFile = "myImage.cgm";
string outputFile = "myPdf.pdf";
ImportOptions importOptions = new CgmImportOptions();
PdfProducer.Produce(inputStream, importOptions, outputStream);
```

```csharp
public static void Produce(string inputFileName, ImportOptions options, string outputFileName)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| inputFileName | String | اسم ملف الإدخال. |
| options | ImportOptions | خيار الاستيراد. |
| outputFileName | String | تدفق PDF الناتج. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception/) | يتم إلقاء الاستثناء عندما يكون الملف غير صالح. |
| ArgumentException | اسم ملف الإدخال أو الإخراج هو سلسلة فارغة |

### انظر أيضًا

* class [ImportOptions](../../../aspose.pdf/importoptions/)
* class [PdfProducer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Produce(Stream, ImportOptions, Stream) {#produce_2}

إنتاج ملف PDF باستخدام خيار الاستيراد المحدد. يوضح هذا المثال كيفية إنتاج تدفق Pdf من تدفق CGM.

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

| معامل | النوع | الوصف |
| --- | --- | --- |
| inputStream | Stream | تدفق الإدخال. |
| options | ImportOptions | خيار الاستيراد. |
| outputStream | Stream | تدفق PDF الناتج. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception/) | يتم إلقاء الاستثناء عندما يكون الملف غير صالح. |
| ArgumentNullException | تدفق الإدخال أو الإخراج هو null. |

### انظر أيضًا

* class [ImportOptions](../../../aspose.pdf/importoptions/)
* class [PdfProducer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


