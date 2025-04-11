---
title: PdfProducer.Produce
second_title: Aspose.PDF for .NET API Reference
description: PdfProducer metodo. Produrre il fiume PDF utilizzando il formato di importazione specificato. Questo esempio mostra come fare produrre il fiume PDF dal fiume CGM.
type: docs
weight: 10
url: /it/net/aspose.pdf.facades/pdfproducer/produce/
---
## Produce(Stream, ImportFormat, Stream) {#produce}

Produce il flusso PDF utilizzando il formato di importazione specificato. Questo esempio mostra come produrre un flusso Pdf da un flusso CGM.

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
| outputStream | Stream | Flusso PDF di output. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception/) | L'eccezione viene sollevata quando un file è non valido. |
| ArgumentNullException | Il flusso di input o di output è nullo |

### Vedi Anche

* enum [ImportFormat](../../../aspose.pdf/importformat/)
* class [PdfProducer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Produce(string, ImportFormat, Stream) {#produce_4}

Produce il flusso PDF utilizzando il formato di importazione specificato. Questo esempio mostra come produrre un flusso Pdf da un file CGM.

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
| inputFileName | String | Nome del file di input. |
| format | ImportFormat | Formato di importazione. |
| outputStream | Stream | Flusso PDF di output. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception/) | L'eccezione viene sollevata quando un file è non valido. |
| ArgumentNullException | Il flusso di output è nullo |
| ArgumentException | Il nome del file di input è una stringa vuota |

### Vedi Anche

* enum [ImportFormat](../../../aspose.pdf/importformat/)
* class [PdfProducer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Produce(Stream, ImportFormat, string) {#produce_1}

Produce il file PDF utilizzando il formato di importazione specificato. Questo esempio mostra come produrre un file Pdf da un flusso CGM.

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
| outputFileName | String | File PDF di output |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception/) | L'eccezione viene sollevata quando un file è non valido. |
| ArgumentNullException | Il flusso di input è nullo |
| ArgumentException | Il nome del file di output è una stringa vuota |

### Vedi Anche

* enum [ImportFormat](../../../aspose.pdf/importformat/)
* class [PdfProducer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Produce(string, ImportFormat, string) {#produce_5}

Produce il file PDF utilizzando il formato di importazione specificato. Questo esempio mostra come produrre un file Pdf da un file CGM.

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
| inputFileName | String | Nome del file di input. |
| format | ImportFormat | Formato di importazione. |
| outputFileName | String | File PDF di output |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception/) | L'eccezione viene sollevata quando un file è non valido. |
| ArgumentException | Il nome del file di input o di output è una stringa vuota |

### Vedi Anche

* enum [ImportFormat](../../../aspose.pdf/importformat/)
* class [PdfProducer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Produce(string, ImportOptions, Stream) {#produce_6}

Produce il flusso PDF utilizzando l'opzione di importazione specificata. Questo esempio mostra come produrre un flusso Pdf da un file CGM.

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
| inputFileName | String | Nome del file di input. |
| options | ImportOptions | Opzione di importazione. |
| outputStream | Stream | Flusso PDF di output. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception/) | L'eccezione viene sollevata quando un file è non valido. |
| ArgumentNullException | Il flusso di output è nullo |
| ArgumentException | Il nome del file di input è una stringa vuota |

### Vedi Anche

* class [ImportOptions](../../../aspose.pdf/importoptions/)
* class [PdfProducer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Produce(Stream, ImportOptions, string) {#produce_3}

Produce il file PDF utilizzando l'opzione di importazione specificata. Questo esempio mostra come produrre un file Pdf da un flusso CGM.

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
| outputFileName | String | File PDF di output. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception/) | L'eccezione viene sollevata quando un file è non valido. |
| ArgumentNullException | Il flusso di input è nullo |
| ArgumentException | Il nome del file di output è una stringa vuota |

### Vedi Anche

* class [ImportOptions](../../../aspose.pdf/importoptions/)
* class [PdfProducer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Produce(string, ImportOptions, string) {#produce_7}

Produce il file PDF utilizzando l'opzione di importazione specificata. Questo esempio mostra come produrre un file Pdf da un file CGM.

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
| inputFileName | String | Nome del file di input. |
| options | ImportOptions | Opzione di importazione. |
| outputFileName | String | Flusso PDF di output. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception/) | L'eccezione viene sollevata quando un file è non valido. |
| ArgumentException | Il nome del file di input o di output è una stringa vuota |

### Vedi Anche

* class [ImportOptions](../../../aspose.pdf/importoptions/)
* class [PdfProducer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Produce(Stream, ImportOptions, Stream) {#produce_2}

Produce il file PDF utilizzando l'opzione di importazione specificata. Questo esempio mostra come produrre un flusso Pdf da un flusso CGM.

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
| outputStream | Stream | Flusso PDF di output. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception/) | L'eccezione viene sollevata quando un file è non valido. |
| ArgumentNullException | Il flusso di input o di output è nullo. |

### Vedi Anche

* class [ImportOptions](../../../aspose.pdf/importoptions/)
* class [PdfProducer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)