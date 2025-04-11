---
title: PdfProducer.Produce
second_title: Aspose.PDF for .NET API Reference
description: PdfProducer metod. Producera PDF-ström med angivet importformat. Detta exempel visar hur man producerar Pdf-ström från CGM-ström
type: docs
weight: 10
url: /sv/net/aspose.pdf.facades/pdfproducer/produce/
---
## Produce(Stream, ImportFormat, Stream) {#produce}

Producera PDF-ström med angivet importformat. Detta exempel visar hur man producerar Pdf-ström från CGM-ström.

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
| inputStream | Stream | Indata-ström. |
| format | ImportFormat | Importformat. |
| outputStream | Stream | Utdata PDF-ström. |

### Undantag

| undantag | villkor |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception/) | Undantaget kastas när en fil är ogiltig. |
| ArgumentNullException | Indata- eller utdata-ström är null |

### Se Även

* enum [ImportFormat](../../../aspose.pdf/importformat/)
* class [PdfProducer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Produce(string, ImportFormat, Stream) {#produce_4}

Producera PDF-ström med angivet importformat. Detta exempel visar hur man producerar Pdf-ström från CGM-fil.

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
| inputFileName | String | Indata filnamn. |
| format | ImportFormat | Importformat. |
| outputStream | Stream | Utdata PDF-ström. |

### Undantag

| undantag | villkor |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception/) | Undantaget kastas när en fil är ogiltig. |
| ArgumentNullException | Utdata-ström är null |
| ArgumentException | Indata filnamn är en tom sträng |

### Se Även

* enum [ImportFormat](../../../aspose.pdf/importformat/)
* class [PdfProducer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Produce(Stream, ImportFormat, string) {#produce_1}

Producera PDF-fil med angivet importformat. Detta exempel visar hur man producerar Pdf-fil från CGM-ström.

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
| inputStream | Stream | Indata-ström. |
| format | ImportFormat | Importformat. |
| outputFileName | String | Utdata PDF-fil |

### Undantag

| undantag | villkor |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception/) | Undantaget kastas när en fil är ogiltig. |
| ArgumentNullException | Indata-ström är null |
| ArgumentException | Utdata filnamn är en tom sträng |

### Se Även

* enum [ImportFormat](../../../aspose.pdf/importformat/)
* class [PdfProducer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Produce(string, ImportFormat, string) {#produce_5}

Producera PDF-fil med angivet importformat. Detta exempel visar hur man producerar Pdf-fil från CGM-fil.

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
| inputFileName | String | Indata filnamn. |
| format | ImportFormat | Importformat. |
| outputFileName | String | Utdata PDF-fil |

### Undantag

| undantag | villkor |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception/) | Undantaget kastas när en fil är ogiltig. |
| ArgumentException | Indata eller utdata filnamn är en tom sträng |

### Se Även

* enum [ImportFormat](../../../aspose.pdf/importformat/)
* class [PdfProducer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Produce(string, ImportOptions, Stream) {#produce_6}

Producera PDF-ström med angiven importoption. Detta exempel visar hur man producerar Pdf-ström från CGM-fil.

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
| inputFileName | String | Indata filnamn. |
| options | ImportOptions | Importoption. |
| outputStream | Stream | Utdata PDF-ström. |

### Undantag

| undantag | villkor |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception/) | Undantaget kastas när en fil är ogiltig. |
| ArgumentNullException | Utdata-ström är null |
| ArgumentException | Indata filnamn är en tom sträng |

### Se Även

* class [ImportOptions](../../../aspose.pdf/importoptions/)
* class [PdfProducer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Produce(Stream, ImportOptions, string) {#produce_3}

Producera PDF-fil med angiven importoption. Detta exempel visar hur man producerar Pdf-fil från CGM-ström.

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
| inputStream | Stream | Indata-ström. |
| options | ImportOptions | Importoption. |
| outputFileName | String | Utdata PDF-fil. |

### Undantag

| undantag | villkor |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception/) | Undantaget kastas när en fil är ogiltig. |
| ArgumentNullException | Indata-ström är null |
| ArgumentException | Utdata filnamn är en tom sträng |

### Se Även

* class [ImportOptions](../../../aspose.pdf/importoptions/)
* class [PdfProducer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Produce(string, ImportOptions, string) {#produce_7}

Producera PDF-fil med angiven importoption. Detta exempel visar hur man producerar Pdf-fil från CGM-fil.

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
| inputFileName | String | Indata filnamn. |
| options | ImportOptions | Importoption. |
| outputFileName | String | Utdata PDF-ström. |

### Undantag

| undantag | villkor |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception/) | Undantaget kastas när en fil är ogiltig. |
| ArgumentException | Indata eller utdata filnamn är en tom sträng |

### Se Även

* class [ImportOptions](../../../aspose.pdf/importoptions/)
* class [PdfProducer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Produce(Stream, ImportOptions, Stream) {#produce_2}

Producera PDF-fil med angiven importoption. Detta exempel visar hur man producerar Pdf-ström från CGM-ström.

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
| inputStream | Stream | Indata-ström. |
| options | ImportOptions | Importoption. |
| outputStream | Stream | Utdata PDF-ström. |

### Undantag

| undantag | villkor |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception/) | Undantaget kastas när en fil är ogiltig. |
| ArgumentNullException | Indata- eller utdata-ström är null. |

### Se Även

* class [ImportOptions](../../../aspose.pdf/importoptions/)
* class [PdfProducer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)