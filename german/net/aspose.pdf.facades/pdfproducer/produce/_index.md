---
title: PdfProducer.Produce
second_title: Aspose.PDF for .NET API Reference
description: PdfProducer-Methode. Erzeugen Sie den PDF-Stream mit dem angegebenen Importformat. Dieses Beispiel zeigt, wie man einen Pdf-Stream aus einem CGM-Stream erzeugt.
type: docs
weight: 10
url: /de/net/aspose.pdf.facades/pdfproducer/produce/
---
## Produce(Stream, ImportFormat, Stream) {#produce}

Erzeugen Sie den PDF-Stream mit dem angegebenen Importformat. Dieses Beispiel zeigt, wie man einen Pdf-Stream aus einem CGM-Stream erzeugt.

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
| inputStream | Stream | Eingangsstream. |
| format | ImportFormat | Importformat. |
| outputStream | Stream | Ausgehender PDF-Stream. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception/) | Die Ausnahme wird ausgelöst, wenn eine Datei ungültig ist. |
| ArgumentNullException | Eingangs- oder Ausgangsstream ist null |

### Siehe auch

* enum [ImportFormat](../../../aspose.pdf/importformat/)
* class [PdfProducer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Produce(string, ImportFormat, Stream) {#produce_4}

Erzeugen Sie den PDF-Stream mit dem angegebenen Importformat. Dieses Beispiel zeigt, wie man einen Pdf-Stream aus einer CGM-Datei erzeugt.

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
| inputFileName | String | Eingabedateiname. |
| format | ImportFormat | Importformat. |
| outputStream | Stream | Ausgehender PDF-Stream. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception/) | Die Ausnahme wird ausgelöst, wenn eine Datei ungültig ist. |
| ArgumentNullException | Ausgangsstream ist null |
| ArgumentException | Eingabedateiname ist eine leere Zeichenfolge |

### Siehe auch

* enum [ImportFormat](../../../aspose.pdf/importformat/)
* class [PdfProducer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Produce(Stream, ImportFormat, string) {#produce_1}

Erzeugen Sie die PDF-Datei mit dem angegebenen Importformat. Dieses Beispiel zeigt, wie man eine Pdf-Datei aus einem CGM-Stream erzeugt.

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
| inputStream | Stream | Eingangsstream. |
| format | ImportFormat | Importformat. |
| outputFileName | String | Ausgehende PDF-Datei |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception/) | Die Ausnahme wird ausgelöst, wenn eine Datei ungültig ist. |
| ArgumentNullException | Eingangsstream ist null |
| ArgumentException | Ausgehender Dateiname ist eine leere Zeichenfolge |

### Siehe auch

* enum [ImportFormat](../../../aspose.pdf/importformat/)
* class [PdfProducer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Produce(string, ImportFormat, string) {#produce_5}

Erzeugen Sie die PDF-Datei mit dem angegebenen Importformat. Dieses Beispiel zeigt, wie man eine Pdf-Datei aus einer CGM-Datei erzeugt.

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
| inputFileName | String | Eingabedateiname. |
| format | ImportFormat | Importformat. |
| outputFileName | String | Ausgehende PDF-Datei |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception/) | Die Ausnahme wird ausgelöst, wenn eine Datei ungültig ist. |
| ArgumentException | Eingabedateiname oder Ausgabedateiname ist eine leere Zeichenfolge |

### Siehe auch

* enum [ImportFormat](../../../aspose.pdf/importformat/)
* class [PdfProducer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Produce(string, ImportOptions, Stream) {#produce_6}

Erzeugen Sie den PDF-Stream mit der angegebenen Importoption. Dieses Beispiel zeigt, wie man einen Pdf-Stream aus einer CGM-Datei erzeugt.

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
| inputFileName | String | Eingabedateiname. |
| options | ImportOptions | Importoption. |
| outputStream | Stream | Ausgehender PDF-Stream. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception/) | Die Ausnahme wird ausgelöst, wenn eine Datei ungültig ist. |
| ArgumentNullException | Ausgangsstream ist null |
| ArgumentException | Eingabedateiname ist eine leere Zeichenfolge |

### Siehe auch

* class [ImportOptions](../../../aspose.pdf/importoptions/)
* class [PdfProducer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Produce(Stream, ImportOptions, string) {#produce_3}

Erzeugen Sie die PDF-Datei mit der angegebenen Importoption. Dieses Beispiel zeigt, wie man eine Pdf-Datei aus einem CGM-Stream erzeugt.

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
| inputStream | Stream | Eingangsstream. |
| options | ImportOptions | Importoption. |
| outputFileName | String | Ausgehende PDF-Datei. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception/) | Die Ausnahme wird ausgelöst, wenn eine Datei ungültig ist. |
| ArgumentNullException | Eingangsstream ist null |
| ArgumentException | Ausgehender Dateiname ist eine leere Zeichenfolge |

### Siehe auch

* class [ImportOptions](../../../aspose.pdf/importoptions/)
* class [PdfProducer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Produce(string, ImportOptions, string) {#produce_7}

Erzeugen Sie die PDF-Datei mit der angegebenen Importoption. Dieses Beispiel zeigt, wie man eine Pdf-Datei aus einer CGM-Datei erzeugt.

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
| inputFileName | String | Eingabedateiname. |
| options | ImportOptions | Importoption. |
| outputFileName | String | Ausgehender PDF-Stream. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception/) | Die Ausnahme wird ausgelöst, wenn eine Datei ungültig ist. |
| ArgumentException | Eingabedateiname oder Ausgabedateiname ist eine leere Zeichenfolge |

### Siehe auch

* class [ImportOptions](../../../aspose.pdf/importoptions/)
* class [PdfProducer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Produce(Stream, ImportOptions, Stream) {#produce_2}

Erzeugen Sie die PDF-Datei mit der angegebenen Importoption. Dieses Beispiel zeigt, wie man einen Pdf-Stream aus einem CGM-Stream erzeugt.

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
| inputStream | Stream | Eingangsstream. |
| options | ImportOptions | Importoption. |
| outputStream | Stream | Ausgehender PDF-Stream. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception/) | Die Ausnahme wird ausgelöst, wenn eine Datei ungültig ist. |
| ArgumentNullException | Eingangs- oder Ausgangsstream ist null. |

### Siehe auch

* class [ImportOptions](../../../aspose.pdf/importoptions/)
* class [PdfProducer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)