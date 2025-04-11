---
title: PdfProducer.Produce
second_title: Aspose.PDF for .NET API Reference
description: Méthode PdfProducer. Produire le flux PDF en utilisant le format d'importation spécifié. Cet exemple montre comment produire un flux Pdf à partir d'un flux CGM
type: docs
weight: 10
url: /fr/net/aspose.pdf.facades/pdfproducer/produce/
---
## Produce(Stream, ImportFormat, Stream) {#produce}

Produire le flux PDF en utilisant le format d'importation spécifié. Cet exemple montre comment produire un flux Pdf à partir d'un flux CGM.

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

| Paramètre | Type | Description |
| --- | --- | --- |
| inputStream | Stream | Flux d'entrée. |
| format | ImportFormat | Format d'importation. |
| outputStream | Stream | Flux PDF de sortie. |

### Exceptions

| exception | condition |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception/) | L'exception est levée lorsqu'un fichier est invalide. |
| ArgumentNullException | Le flux d'entrée ou de sortie est nul |

### Voir aussi

* enum [ImportFormat](../../../aspose.pdf/importformat/)
* class [PdfProducer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Produce(string, ImportFormat, Stream) {#produce_4}

Produire le flux PDF en utilisant le format d'importation spécifié. Cet exemple montre comment produire un flux Pdf à partir d'un fichier CGM.

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

| Paramètre | Type | Description |
| --- | --- | --- |
| inputFileName | String | Nom du fichier d'entrée. |
| format | ImportFormat | Format d'importation. |
| outputStream | Stream | Flux PDF de sortie. |

### Exceptions

| exception | condition |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception/) | L'exception est levée lorsqu'un fichier est invalide. |
| ArgumentNullException | Le flux de sortie est nul |
| ArgumentException | Le nom du fichier d'entrée est une chaîne vide |

### Voir aussi

* enum [ImportFormat](../../../aspose.pdf/importformat/)
* class [PdfProducer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Produce(Stream, ImportFormat, string) {#produce_1}

Produire le fichier PDF en utilisant le format d'importation spécifié. Cet exemple montre comment produire un fichier Pdf à partir d'un flux CGM.

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

| Paramètre | Type | Description |
| --- | --- | --- |
| inputStream | Stream | Flux d'entrée. |
| format | ImportFormat | Format d'importation. |
| outputFileName | String | Fichier PDF de sortie |

### Exceptions

| exception | condition |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception/) | L'exception est levée lorsqu'un fichier est invalide. |
| ArgumentNullException | Le flux d'entrée est nul |
| ArgumentException | Le nom du fichier de sortie est une chaîne vide |

### Voir aussi

* enum [ImportFormat](../../../aspose.pdf/importformat/)
* class [PdfProducer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Produce(string, ImportFormat, string) {#produce_5}

Produire le fichier PDF en utilisant le format d'importation spécifié. Cet exemple montre comment produire un fichier Pdf à partir d'un fichier CGM.

```csharp
string inputFile = "myImage.cgm";
string outputFile = "myPdf.pdf";
PdfProducer.Produce(inputFile, ImportFormat.Cgm, outputFile);
```

```csharp
public static void Produce(string inputFileName, ImportFormat format, string outputFileName)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| inputFileName | String | Nom du fichier d'entrée. |
| format | ImportFormat | Format d'importation. |
| outputFileName | String | Fichier PDF de sortie |

### Exceptions

| exception | condition |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception/) | L'exception est levée lorsqu'un fichier est invalide. |
| ArgumentException | Le nom du fichier d'entrée ou de sortie est une chaîne vide |

### Voir aussi

* enum [ImportFormat](../../../aspose.pdf/importformat/)
* class [PdfProducer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Produce(string, ImportOptions, Stream) {#produce_6}

Produire le flux PDF en utilisant l'option d'importation spécifiée. Cet exemple montre comment produire un flux Pdf à partir d'un fichier CGM.

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

| Paramètre | Type | Description |
| --- | --- | --- |
| inputFileName | String | Nom du fichier d'entrée. |
| options | ImportOptions | Option d'importation. |
| outputStream | Stream | Flux PDF de sortie. |

### Exceptions

| exception | condition |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception/) | L'exception est levée lorsqu'un fichier est invalide. |
| ArgumentNullException | Le flux de sortie est nul |
| ArgumentException | Le nom du fichier d'entrée est une chaîne vide |

### Voir aussi

* class [ImportOptions](../../../aspose.pdf/importoptions/)
* class [PdfProducer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Produce(Stream, ImportOptions, string) {#produce_3}

Produire le fichier PDF en utilisant l'option d'importation spécifiée. Cet exemple montre comment produire un fichier Pdf à partir d'un flux CGM.

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

| Paramètre | Type | Description |
| --- | --- | --- |
| inputStream | Stream | Flux d'entrée. |
| options | ImportOptions | Option d'importation. |
| outputFileName | String | Fichier PDF de sortie. |

### Exceptions

| exception | condition |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception/) | L'exception est levée lorsqu'un fichier est invalide. |
| ArgumentNullException | Le flux d'entrée est nul |
| ArgumentException | Le nom du fichier de sortie est une chaîne vide |

### Voir aussi

* class [ImportOptions](../../../aspose.pdf/importoptions/)
* class [PdfProducer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Produce(string, ImportOptions, string) {#produce_7}

Produire le fichier PDF en utilisant l'option d'importation spécifiée. Cet exemple montre comment produire un fichier Pdf à partir d'un fichier CGM.

```csharp
string inputFile = "myImage.cgm";
string outputFile = "myPdf.pdf";
ImportOptions importOptions = new CgmImportOptions();
PdfProducer.Produce(inputStream, importOptions, outputStream);
```

```csharp
public static void Produce(string inputFileName, ImportOptions options, string outputFileName)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| inputFileName | String | Nom du fichier d'entrée. |
| options | ImportOptions | Option d'importation. |
| outputFileName | String | Flux PDF de sortie. |

### Exceptions

| exception | condition |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception/) | L'exception est levée lorsqu'un fichier est invalide. |
| ArgumentException | Le nom du fichier d'entrée ou de sortie est une chaîne vide |

### Voir aussi

* class [ImportOptions](../../../aspose.pdf/importoptions/)
* class [PdfProducer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Produce(Stream, ImportOptions, Stream) {#produce_2}

Produire le fichier PDF en utilisant l'option d'importation spécifiée. Cet exemple montre comment produire un flux Pdf à partir d'un flux CGM.

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

| Paramètre | Type | Description |
| --- | --- | --- |
| inputStream | Stream | Flux d'entrée. |
| options | ImportOptions | Option d'importation. |
| outputStream | Stream | Flux PDF de sortie. |

### Exceptions

| exception | condition |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception/) | L'exception est levée lorsqu'un fichier est invalide. |
| ArgumentNullException | Le flux d'entrée ou de sortie est nul. |

### Voir aussi

* class [ImportOptions](../../../aspose.pdf/importoptions/)
* class [PdfProducer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)