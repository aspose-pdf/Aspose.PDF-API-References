---
title: Produce
second_title: Aspose.PDF för .NET API Referens
description: Producera PDF-strömmen med angivet importformat.  Detta exempel visar hur man producerar PDF-ström från CGM-ström.
type: docs
weight: 10
url: /sv/net/aspose.pdf.facades/pdfproducer/produce/
---
## Produce(Stream, ImportFormat, Stream) {#produce}

Producera PDF-strömmen med angivet importformat.  Detta exempel visar hur man producerar PDF-ström från CGM-ström.

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

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputStream | Stream | Ingångsström. |
| format | ImportFormat | Importformat. |
| outputStream | Stream | Utdata PDF-ström. |

### Undantag

| undantag | skick |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception) | Undantaget görs när en fil är ogiltig. |
| ArgumentNullException | In- eller utströmmen är null |

### Se även

* enum [ImportFormat](../../../aspose.pdf/importformat)
* class [PdfProducer](../../pdfproducer)
* namnutrymme [Aspose.Pdf.Facades](../../pdfproducer)
* hopsättning [Aspose.PDF](../../../)

---

## Produce(string, ImportFormat, Stream) {#produce_4}

Producera PDF-strömmen med angivet importformat.  Detta exempel visar hur man producerar PDF-ström från CGM-fil.

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

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputFileName | String | Inmatat filnamn. |
| format | ImportFormat | Importformat. |
| outputStream | Stream | Utdata PDF-ström. |

### Undantag

| undantag | skick |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception) | Undantaget görs när en fil är ogiltig. |
| ArgumentNullException | Utdataströmmen är null |
| ArgumentException | Indatafilnamnet är en tom sträng |

### Se även

* enum [ImportFormat](../../../aspose.pdf/importformat)
* class [PdfProducer](../../pdfproducer)
* namnutrymme [Aspose.Pdf.Facades](../../pdfproducer)
* hopsättning [Aspose.PDF](../../../)

---

## Produce(Stream, ImportFormat, string) {#produce_1}

Skapa PDF-filen med angivet importformat.  Det här exemplet visar hur man skapar en pdf-fil från CGM stream.

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

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputStream | Stream | Ingångsström. |
| format | ImportFormat | Importformat. |
| outputFileName | String | Utdata PDF-fil |

### Undantag

| undantag | skick |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception) | Undantaget görs när en fil är ogiltig. |
| ArgumentNullException | Ingångsströmmen är null |
| ArgumentException | Utdatafilnamnet är en tom sträng |

### Se även

* enum [ImportFormat](../../../aspose.pdf/importformat)
* class [PdfProducer](../../pdfproducer)
* namnutrymme [Aspose.Pdf.Facades](../../pdfproducer)
* hopsättning [Aspose.PDF](../../../)

---

## Produce(string, ImportFormat, string) {#produce_5}

Skapa PDF-filen med angivet importformat.  Detta exempel visar hur man skapar en pdf-fil från CGM-fil.

```csharp
string inputFile = "myImage.cgm";
string outputFile = "myPdf.pdf";
PdfProducer.Produce(inputFile, ImportFormat.Cgm, outputFile);
```

```csharp
public static void Produce(string inputFileName, ImportFormat format, string outputFileName)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputFileName | String | Inmatat filnamn. |
| format | ImportFormat | Importformat. |
| outputFileName | String | Utdata PDF-fil |

### Undantag

| undantag | skick |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception) | Undantaget görs när en fil är ogiltig. |
| ArgumentException | In- eller utdatafilnamnet är en tom sträng |

### Se även

* enum [ImportFormat](../../../aspose.pdf/importformat)
* class [PdfProducer](../../pdfproducer)
* namnutrymme [Aspose.Pdf.Facades](../../pdfproducer)
* hopsättning [Aspose.PDF](../../../)

---

## Produce(string, ImportOptions, Stream) {#produce_6}

Producera PDF-strömmen med det angivna importalternativet.  Detta exempel visar hur man producerar PDF-ström från CGM-fil.

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

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputFileName | String | Inmatat filnamn. |
| options | ImportOptions | Importalternativ. |
| outputStream | Stream | Utdata PDF-ström. |

### Undantag

| undantag | skick |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception) | Undantaget görs när en fil är ogiltig. |
| ArgumentNullException | Utdataströmmen är null |
| ArgumentException | Indatafilnamnet är en tom sträng |

### Se även

* class [ImportOptions](../../../aspose.pdf/importoptions)
* class [PdfProducer](../../pdfproducer)
* namnutrymme [Aspose.Pdf.Facades](../../pdfproducer)
* hopsättning [Aspose.PDF](../../../)

---

## Produce(Stream, ImportOptions, string) {#produce_3}

Skapa PDF-filen med det angivna importalternativet.  Det här exemplet visar hur man skapar en pdf-fil från CGM stream.

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

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputStream | Stream | Ingångsström. |
| options | ImportOptions | Importalternativ. |
| outputFileName | String | Utdata PDF-fil. |

### Undantag

| undantag | skick |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception) | Undantaget görs när en fil är ogiltig. |
| ArgumentNullException | Ingångsströmmen är null |
| ArgumentException | Utdatafilnamnet är en tom sträng |

### Se även

* class [ImportOptions](../../../aspose.pdf/importoptions)
* class [PdfProducer](../../pdfproducer)
* namnutrymme [Aspose.Pdf.Facades](../../pdfproducer)
* hopsättning [Aspose.PDF](../../../)

---

## Produce(string, ImportOptions, string) {#produce_7}

Skapa PDF-filen med det angivna importalternativet.  Detta exempel visar hur man skapar en pdf-fil från CGM-fil.

```csharp
string inputFile = "myImage.cgm";
string outputFile = "myPdf.pdf";
ImportOptions importOptions = new CgmImportOptions();
PdfProducer.Produce(inputStream, importOptions, outputStream);
```

```csharp
public static void Produce(string inputFileName, ImportOptions options, string outputFileName)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputFileName | String | Inmatat filnamn. |
| options | ImportOptions | Importalternativ. |
| outputFileName | String | Utdata PDF-ström. |

### Undantag

| undantag | skick |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception) | Undantaget görs när en fil är ogiltig. |
| ArgumentException | In- eller utdatafilnamnet är en tom sträng |

### Se även

* class [ImportOptions](../../../aspose.pdf/importoptions)
* class [PdfProducer](../../pdfproducer)
* namnutrymme [Aspose.Pdf.Facades](../../pdfproducer)
* hopsättning [Aspose.PDF](../../../)

---

## Produce(Stream, ImportOptions, Stream) {#produce_2}

Skapa PDF-filen med det angivna importalternativet.  Detta exempel visar hur man producerar PDF-ström från CGM-ström.

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

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputStream | Stream | Ingångsström. |
| options | ImportOptions | Importalternativ. |
| outputStream | Stream | Utdata PDF-ström. |

### Undantag

| undantag | skick |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception) | Undantaget görs när en fil är ogiltig. |
| ArgumentNullException | In- eller utströmmen är null. |

### Se även

* class [ImportOptions](../../../aspose.pdf/importoptions)
* class [PdfProducer](../../pdfproducer)
* namnutrymme [Aspose.Pdf.Facades](../../pdfproducer)
* hopsättning [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
