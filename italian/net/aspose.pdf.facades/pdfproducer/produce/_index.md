---
title: Produce
second_title: Aspose.PDF per .NET API Reference
description: Produci il flusso PDF utilizzando il formato di importazione specificato.  Questo esempio mostra come produrre stream Pdf da stream CGM.
type: docs
weight: 10
url: /it/net/aspose.pdf.facades/pdfproducer/produce/
---
## Produce(Stream, ImportFormat, Stream) {#produce}

Produci il flusso PDF utilizzando il formato di importazione specificato.  Questo esempio mostra come produrre stream Pdf da stream CGM.

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

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputStream | Stream | Flusso di input. |
| format | ImportFormat | Formato di importazione. |
| outputStream | Stream | Output flusso PDF. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception) | L'eccezione viene generata quando un file non è valido. |
| ArgumentNullException | Il flusso di input o output è nullo |

### Guarda anche

* enum [ImportFormat](../../../aspose.pdf/importformat)
* class [PdfProducer](../../pdfproducer)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdfproducer)
* assemblea [Aspose.PDF](../../../)

---

## Produce(string, ImportFormat, Stream) {#produce_4}

Produci il flusso PDF utilizzando il formato di importazione specificato.  Questo esempio mostra come produrre un flusso Pdf da un file CGM.

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

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputFileName | String | Inserisci il nome del file. |
| format | ImportFormat | Formato di importazione. |
| outputStream | Stream | Output flusso PDF. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception) | L'eccezione viene generata quando un file non è valido. |
| ArgumentNullException | Il flusso di output è nullo |
| ArgumentException | Il nome del file di input è una stringa vuota |

### Guarda anche

* enum [ImportFormat](../../../aspose.pdf/importformat)
* class [PdfProducer](../../pdfproducer)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdfproducer)
* assemblea [Aspose.PDF](../../../)

---

## Produce(Stream, ImportFormat, string) {#produce_1}

Produci il file PDF utilizzando il formato di importazione specificato.  Questo esempio mostra come produrre file Pdf dal flusso CGM.

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

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputStream | Stream | Flusso di input. |
| format | ImportFormat | Formato di importazione. |
| outputFileName | String | Output file PDF |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception) | L'eccezione viene generata quando un file non è valido. |
| ArgumentNullException | Il flusso di input è nullo |
| ArgumentException | Il nome del file di output è una stringa vuota |

### Guarda anche

* enum [ImportFormat](../../../aspose.pdf/importformat)
* class [PdfProducer](../../pdfproducer)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdfproducer)
* assemblea [Aspose.PDF](../../../)

---

## Produce(string, ImportFormat, string) {#produce_5}

Produci il file PDF utilizzando il formato di importazione specificato.  Questo esempio mostra come produrre file Pdf da file CGM.

```csharp
string inputFile = "myImage.cgm";
string outputFile = "myPdf.pdf";
PdfProducer.Produce(inputFile, ImportFormat.Cgm, outputFile);
```

```csharp
public static void Produce(string inputFileName, ImportFormat format, string outputFileName)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputFileName | String | Inserisci il nome del file. |
| format | ImportFormat | Formato di importazione. |
| outputFileName | String | Output file PDF |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception) | L'eccezione viene generata quando un file non è valido. |
| ArgumentException | Il nome del file di input o di output è una stringa vuota |

### Guarda anche

* enum [ImportFormat](../../../aspose.pdf/importformat)
* class [PdfProducer](../../pdfproducer)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdfproducer)
* assemblea [Aspose.PDF](../../../)

---

## Produce(string, ImportOptions, Stream) {#produce_6}

Produci il flusso PDF utilizzando l'opzione di importazione specificata.  Questo esempio mostra come produrre un flusso Pdf da un file CGM.

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

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputFileName | String | Inserisci il nome del file. |
| options | ImportOptions | Opzione di importazione. |
| outputStream | Stream | Output flusso PDF. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception) | L'eccezione viene generata quando un file non è valido. |
| ArgumentNullException | Il flusso di output è nullo |
| ArgumentException | Il nome del file di input è una stringa vuota |

### Guarda anche

* class [ImportOptions](../../../aspose.pdf/importoptions)
* class [PdfProducer](../../pdfproducer)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdfproducer)
* assemblea [Aspose.PDF](../../../)

---

## Produce(Stream, ImportOptions, string) {#produce_3}

Produci il file PDF utilizzando l'opzione di importazione specificata.  Questo esempio mostra come produrre file Pdf dal flusso CGM.

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

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputStream | Stream | Flusso di input. |
| options | ImportOptions | Opzione di importazione. |
| outputFileName | String | Output file PDF. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception) | L'eccezione viene generata quando un file non è valido. |
| ArgumentNullException | Il flusso di input è nullo |
| ArgumentException | Il nome del file di output è una stringa vuota |

### Guarda anche

* class [ImportOptions](../../../aspose.pdf/importoptions)
* class [PdfProducer](../../pdfproducer)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdfproducer)
* assemblea [Aspose.PDF](../../../)

---

## Produce(string, ImportOptions, string) {#produce_7}

Produci il file PDF utilizzando l'opzione di importazione specificata.  Questo esempio mostra come produrre file Pdf da file CGM.

```csharp
string inputFile = "myImage.cgm";
string outputFile = "myPdf.pdf";
ImportOptions importOptions = new CgmImportOptions();
PdfProducer.Produce(inputStream, importOptions, outputStream);
```

```csharp
public static void Produce(string inputFileName, ImportOptions options, string outputFileName)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputFileName | String | Inserisci il nome del file. |
| options | ImportOptions | Opzione di importazione. |
| outputFileName | String | Output flusso PDF. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception) | L'eccezione viene generata quando un file non è valido. |
| ArgumentException | Il nome del file di input o di output è una stringa vuota |

### Guarda anche

* class [ImportOptions](../../../aspose.pdf/importoptions)
* class [PdfProducer](../../pdfproducer)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdfproducer)
* assemblea [Aspose.PDF](../../../)

---

## Produce(Stream, ImportOptions, Stream) {#produce_2}

Produci il file PDF utilizzando l'opzione di importazione specificata.  Questo esempio mostra come produrre stream Pdf da stream CGM.

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

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputStream | Stream | Flusso di input. |
| options | ImportOptions | Opzione di importazione. |
| outputStream | Stream | Output flusso PDF. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception) | L'eccezione viene generata quando un file non è valido. |
| ArgumentNullException | Il flusso di input o output è nullo. |

### Guarda anche

* class [ImportOptions](../../../aspose.pdf/importoptions)
* class [PdfProducer](../../pdfproducer)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdfproducer)
* assemblea [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
