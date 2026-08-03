---
title: "PdfProducer.Produce"
second_title: "Aspose.PDF för .NET API‑referens"
description: "PdfProducer-metod. Skapa PDF-strömmen med angivet importformat. Detta exempel visar hur man producerar Pdf-ström från CGM-ström"
type: docs
weight: 10
url: /sv/net/aspose.pdf.facades/pdfproducer/produce/
---
## Produce(Stream, ImportFormat, Stream) {#produce}

Skapa PDF‑strömmen med angivet importformat. Detta exempel visar hur man producerar en Pdf‑ström från en CGM‑ström.

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
| inputStream | Stream | Inmatningsström. |
| format | ImportFormat | Importformat. |
| outputStream | Stream | Utdata-PDF-ström. |

### Undantag

| undantag | villkor |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception/) | Undantaget kastas när en fil är ogiltig. |
| ArgumentNullException | Inmatnings- eller utdataström är null |

### Se även

* enum [ImportFormat](../../../aspose.pdf/importformat/)
* class [PdfProducer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Produce(string, ImportFormat, Stream) {#produce_4}

Skapa PDF‑strömmen med angivet importformat. Detta exempel visar hur man producerar en Pdf‑ström från en CGM‑fil.

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
| inputFileName | String | Inmatningsfilnamn. |
| format | ImportFormat | Importformat. |
| outputStream | Stream | Utdata-PDF-ström. |

### Undantag

| undantag | villkor |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception/) | Undantaget kastas när en fil är ogiltig. |
| ArgumentNullException | Utdataström är null |
| ArgumentException | Inmatningsfilnamn är en tom sträng |

### Se även

* enum [ImportFormat](../../../aspose.pdf/importformat/)
* class [PdfProducer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Produce(Stream, ImportFormat, string) {#produce_1}

Skapa PDF‑filen med angivet importformat. Detta exempel visar hur man producerar en Pdf‑fil från en CGM‑ström.

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
| inputStream | Stream | Inmatningsström. |
| format | ImportFormat | Importformat. |
| outputFileName | String | Utdata-PDF-fil |

### Undantag

| undantag | villkor |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception/) | Undantaget kastas när en fil är ogiltig. |
| ArgumentNullException | Inmatningsström är null |
| ArgumentException | Utdatafilnamn är en tom sträng |

### Se även

* enum [ImportFormat](../../../aspose.pdf/importformat/)
* class [PdfProducer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Produce(string, ImportFormat, string) {#produce_5}

Skapa PDF‑filen med angivet importformat. Detta exempel visar hur man producerar en Pdf‑fil från en CGM‑fil.

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
| inputFileName | String | Inmatningsfilnamn. |
| format | ImportFormat | Importformat. |
| outputFileName | String | Utdata-PDF-fil |

### Undantag

| undantag | villkor |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception/) | Undantaget kastas när en fil är ogiltig. |
| ArgumentException | Inmatnings- eller utdatafilnamn är en tom sträng |

### Se även

* enum [ImportFormat](../../../aspose.pdf/importformat/)
* class [PdfProducer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Produce(string, ImportOptions, Stream) {#produce_6}

Skapa PDF‑strömmen med angivet importalternativ. Detta exempel visar hur man producerar en Pdf‑ström från en CGM‑fil.

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
| inputFileName | String | Inmatningsfilnamn. |
| options | ImportOptions | Importalternativ. |
| outputStream | Stream | Utdata-PDF-ström. |

### Undantag

| undantag | villkor |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception/) | Undantaget kastas när en fil är ogiltig. |
| ArgumentNullException | Utdataström är null |
| ArgumentException | Inmatningsfilnamn är en tom sträng |

### Se även

* class [ImportOptions](../../../aspose.pdf/importoptions/)
* class [PdfProducer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Produce(Stream, ImportOptions, string) {#produce_3}

Skapa PDF‑filen med angivet importalternativ. Detta exempel visar hur man producerar en Pdf‑fil från en CGM‑ström.

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
| inputStream | Stream | Inmatningsström. |
| options | ImportOptions | Importalternativ. |
| outputFileName | String | Utdata PDF-fil. |

### Undantag

| undantag | villkor |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception/) | Undantaget kastas när en fil är ogiltig. |
| ArgumentNullException | Inmatningsström är null |
| ArgumentException | Utdatafilnamn är en tom sträng |

### Se även

* class [ImportOptions](../../../aspose.pdf/importoptions/)
* class [PdfProducer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Produce(string, ImportOptions, string) {#produce_7}

Skapa PDF‑filen med angivet importalternativ. Detta exempel visar hur man producerar en Pdf‑fil från en CGM‑fil.

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
| inputFileName | String | Inmatningsfilnamn. |
| options | ImportOptions | Importalternativ. |
| outputFileName | String | Utdata-PDF-ström. |

### Undantag

| undantag | villkor |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception/) | Undantaget kastas när en fil är ogiltig. |
| ArgumentException | Inmatnings- eller utdatafilnamn är en tom sträng |

### Se även

* class [ImportOptions](../../../aspose.pdf/importoptions/)
* class [PdfProducer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Produce(Stream, ImportOptions, Stream) {#produce_2}

Skapa PDF‑filen med angivet importalternativ. Detta exempel visar hur man producerar en Pdf‑ström från en CGM‑ström.

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
| inputStream | Stream | Inmatningsström. |
| options | ImportOptions | Importalternativ. |
| outputStream | Stream | Utdata-PDF-ström. |

### Undantag

| undantag | villkor |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception/) | Undantaget kastas när en fil är ogiltig. |
| ArgumentNullException | In- eller utmatningsström är null. |

### Se även

* class [ImportOptions](../../../aspose.pdf/importoptions/)
* class [PdfProducer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


