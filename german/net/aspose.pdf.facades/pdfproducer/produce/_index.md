---
title: Produce
second_title: Aspose.PDF für .NET-API-Referenz
description: Erzeugt den PDF-Stream unter Verwendung des angegebenen Importformats.  Dieses Beispiel zeigt wie ein PDF-Stream aus einem CGM-Stream erstellt wird.
type: docs
weight: 10
url: /de/net/aspose.pdf.facades/pdfproducer/produce/
---
## Produce(Stream, ImportFormat, Stream) {#produce}

Erzeugt den PDF-Stream unter Verwendung des angegebenen Importformats.  Dieses Beispiel zeigt, wie ein PDF-Stream aus einem CGM-Stream erstellt wird.

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

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputStream | Stream | Eingabestrom. |
| format | ImportFormat | Format importieren. |
| outputStream | Stream | PDF-Stream ausgeben. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception) | Die Ausnahme wird ausgelöst, wenn eine Datei ungültig ist. |
| ArgumentNullException | Eingabe- oder Ausgabestream ist null |

### Siehe auch

* enum [ImportFormat](../../../aspose.pdf/importformat)
* class [PdfProducer](../../pdfproducer)
* namensraum [Aspose.Pdf.Facades](../../pdfproducer)
* Montage [Aspose.PDF](../../../)

---

## Produce(string, ImportFormat, Stream) {#produce_4}

Erzeugt den PDF-Stream unter Verwendung des angegebenen Importformats.  Dieses Beispiel zeigt, wie ein PDF-Stream aus einer CGM-Datei erstellt wird.

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

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputFileName | String | Dateinamen eingeben. |
| format | ImportFormat | Format importieren. |
| outputStream | Stream | PDF-Stream ausgeben. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception) | Die Ausnahme wird ausgelöst, wenn eine Datei ungültig ist. |
| ArgumentNullException | Ausgabestrom ist null |
| ArgumentException | Der Name der Eingabedatei ist eine leere Zeichenfolge |

### Siehe auch

* enum [ImportFormat](../../../aspose.pdf/importformat)
* class [PdfProducer](../../pdfproducer)
* namensraum [Aspose.Pdf.Facades](../../pdfproducer)
* Montage [Aspose.PDF](../../../)

---

## Produce(Stream, ImportFormat, string) {#produce_1}

Erzeugt die PDF-Datei unter Verwendung des angegebenen Importformats.  Dieses Beispiel zeigt, wie eine PDF-Datei aus einem CGM-Stream erstellt wird.

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

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputStream | Stream | Eingabestrom. |
| format | ImportFormat | Format importieren. |
| outputFileName | String | PDF-Datei ausgeben |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception) | Die Ausnahme wird ausgelöst, wenn eine Datei ungültig ist. |
| ArgumentNullException | Der Eingabestream ist null |
| ArgumentException | Der Name der Ausgabedatei ist eine leere Zeichenfolge |

### Siehe auch

* enum [ImportFormat](../../../aspose.pdf/importformat)
* class [PdfProducer](../../pdfproducer)
* namensraum [Aspose.Pdf.Facades](../../pdfproducer)
* Montage [Aspose.PDF](../../../)

---

## Produce(string, ImportFormat, string) {#produce_5}

Erzeugt die PDF-Datei unter Verwendung des angegebenen Importformats.  Dieses Beispiel zeigt, wie eine PDF-Datei aus einer CGM-Datei erstellt wird.

```csharp
string inputFile = "myImage.cgm";
string outputFile = "myPdf.pdf";
PdfProducer.Produce(inputFile, ImportFormat.Cgm, outputFile);
```

```csharp
public static void Produce(string inputFileName, ImportFormat format, string outputFileName)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputFileName | String | Dateinamen eingeben. |
| format | ImportFormat | Format importieren. |
| outputFileName | String | PDF-Datei ausgeben |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception) | Die Ausnahme wird ausgelöst, wenn eine Datei ungültig ist. |
| ArgumentException | Der Name der Eingabe- oder Ausgabedatei ist eine leere Zeichenfolge |

### Siehe auch

* enum [ImportFormat](../../../aspose.pdf/importformat)
* class [PdfProducer](../../pdfproducer)
* namensraum [Aspose.Pdf.Facades](../../pdfproducer)
* Montage [Aspose.PDF](../../../)

---

## Produce(string, ImportOptions, Stream) {#produce_6}

Produziert den PDF-Stream mit der angegebenen Importoption.  Dieses Beispiel zeigt, wie ein PDF-Stream aus einer CGM-Datei erstellt wird.

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

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputFileName | String | Dateinamen eingeben. |
| options | ImportOptions | Importoption. |
| outputStream | Stream | PDF-Stream ausgeben. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception) | Die Ausnahme wird ausgelöst, wenn eine Datei ungültig ist. |
| ArgumentNullException | Ausgabestrom ist null |
| ArgumentException | Der Name der Eingabedatei ist eine leere Zeichenfolge |

### Siehe auch

* class [ImportOptions](../../../aspose.pdf/importoptions)
* class [PdfProducer](../../pdfproducer)
* namensraum [Aspose.Pdf.Facades](../../pdfproducer)
* Montage [Aspose.PDF](../../../)

---

## Produce(Stream, ImportOptions, string) {#produce_3}

Produzieren Sie die PDF-Datei mit der angegebenen Importoption.  Dieses Beispiel zeigt, wie eine PDF-Datei aus einem CGM-Stream erstellt wird.

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

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputStream | Stream | Eingabestrom. |
| options | ImportOptions | Importoption. |
| outputFileName | String | PDF-Datei ausgeben. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception) | Die Ausnahme wird ausgelöst, wenn eine Datei ungültig ist. |
| ArgumentNullException | Der Eingabestream ist null |
| ArgumentException | Der Name der Ausgabedatei ist eine leere Zeichenfolge |

### Siehe auch

* class [ImportOptions](../../../aspose.pdf/importoptions)
* class [PdfProducer](../../pdfproducer)
* namensraum [Aspose.Pdf.Facades](../../pdfproducer)
* Montage [Aspose.PDF](../../../)

---

## Produce(string, ImportOptions, string) {#produce_7}

Produzieren Sie die PDF-Datei mit der angegebenen Importoption.  Dieses Beispiel zeigt, wie eine PDF-Datei aus einer CGM-Datei erstellt wird.

```csharp
string inputFile = "myImage.cgm";
string outputFile = "myPdf.pdf";
ImportOptions importOptions = new CgmImportOptions();
PdfProducer.Produce(inputStream, importOptions, outputStream);
```

```csharp
public static void Produce(string inputFileName, ImportOptions options, string outputFileName)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputFileName | String | Dateinamen eingeben. |
| options | ImportOptions | Importoption. |
| outputFileName | String | PDF-Stream ausgeben. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception) | Die Ausnahme wird ausgelöst, wenn eine Datei ungültig ist. |
| ArgumentException | Der Name der Eingabe- oder Ausgabedatei ist eine leere Zeichenfolge |

### Siehe auch

* class [ImportOptions](../../../aspose.pdf/importoptions)
* class [PdfProducer](../../pdfproducer)
* namensraum [Aspose.Pdf.Facades](../../pdfproducer)
* Montage [Aspose.PDF](../../../)

---

## Produce(Stream, ImportOptions, Stream) {#produce_2}

Produzieren Sie die PDF-Datei mit der angegebenen Importoption.  Dieses Beispiel zeigt, wie ein PDF-Stream aus einem CGM-Stream erstellt wird.

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

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputStream | Stream | Eingabestrom. |
| options | ImportOptions | Importoption. |
| outputStream | Stream | PDF-Stream ausgeben. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception) | Die Ausnahme wird ausgelöst, wenn eine Datei ungültig ist. |
| ArgumentNullException | Eingabe- oder Ausgabestream ist null. |

### Siehe auch

* class [ImportOptions](../../../aspose.pdf/importoptions)
* class [PdfProducer](../../pdfproducer)
* namensraum [Aspose.Pdf.Facades](../../pdfproducer)
* Montage [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
