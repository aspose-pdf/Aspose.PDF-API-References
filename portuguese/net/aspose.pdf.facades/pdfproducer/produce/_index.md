---
title: PdfProducer.Produce
second_title: Aspose.PDF for .NET API Reference
description: Método PdfProducer. Produza o fluxo PDF usando o formato de importação especificado. Este exemplo mostra como produzir um fluxo Pdf a partir de um fluxo CGM
type: docs
weight: 10
url: /pt/net/aspose.pdf.facades/pdfproducer/produce/
---
## Produce(Stream, ImportFormat, Stream) {#produce}

Produza o fluxo PDF usando o formato de importação especificado. Este exemplo mostra como produzir um fluxo Pdf a partir de um fluxo CGM.

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

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| inputStream | Stream | Fluxo de entrada. |
| format | ImportFormat | Formato de importação. |
| outputStream | Stream | Fluxo PDF de saída. |

### Exceções

| exceção | condição |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception/) | A exceção é lançada quando um arquivo é inválido. |
| ArgumentNullException | O fluxo de entrada ou saída é nulo |

### Veja Também

* enum [ImportFormat](../../../aspose.pdf/importformat/)
* class [PdfProducer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Produce(string, ImportFormat, Stream) {#produce_4}

Produza o fluxo PDF usando o formato de importação especificado. Este exemplo mostra como produzir um fluxo Pdf a partir de um arquivo CGM.

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

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| inputFileName | String | Nome do arquivo de entrada. |
| format | ImportFormat | Formato de importação. |
| outputStream | Stream | Fluxo PDF de saída. |

### Exceções

| exceção | condição |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception/) | A exceção é lançada quando um arquivo é inválido. |
| ArgumentNullException | O fluxo de saída é nulo |
| ArgumentException | O nome do arquivo de entrada é uma string vazia |

### Veja Também

* enum [ImportFormat](../../../aspose.pdf/importformat/)
* class [PdfProducer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Produce(Stream, ImportFormat, string) {#produce_1}

Produza o arquivo PDF usando o formato de importação especificado. Este exemplo mostra como produzir um arquivo Pdf a partir de um fluxo CGM.

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

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| inputStream | Stream | Fluxo de entrada. |
| format | ImportFormat | Formato de importação. |
| outputFileName | String | Arquivo PDF de saída |

### Exceções

| exceção | condição |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception/) | A exceção é lançada quando um arquivo é inválido. |
| ArgumentNullException | O fluxo de entrada é nulo |
| ArgumentException | O nome do arquivo de saída é uma string vazia |

### Veja Também

* enum [ImportFormat](../../../aspose.pdf/importformat/)
* class [PdfProducer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Produce(string, ImportFormat, string) {#produce_5}

Produza o arquivo PDF usando o formato de importação especificado. Este exemplo mostra como produzir um arquivo Pdf a partir de um arquivo CGM.

```csharp
string inputFile = "myImage.cgm";
string outputFile = "myPdf.pdf";
PdfProducer.Produce(inputFile, ImportFormat.Cgm, outputFile);
```

```csharp
public static void Produce(string inputFileName, ImportFormat format, string outputFileName)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| inputFileName | String | Nome do arquivo de entrada. |
| format | ImportFormat | Formato de importação. |
| outputFileName | String | Arquivo PDF de saída |

### Exceções

| exceção | condição |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception/) | A exceção é lançada quando um arquivo é inválido. |
| ArgumentException | O nome do arquivo de entrada ou saída é uma string vazia |

### Veja Também

* enum [ImportFormat](../../../aspose.pdf/importformat/)
* class [PdfProducer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Produce(string, ImportOptions, Stream) {#produce_6}

Produza o fluxo PDF usando a opção de importação especificada. Este exemplo mostra como produzir um fluxo Pdf a partir de um arquivo CGM.

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

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| inputFileName | String | Nome do arquivo de entrada. |
| options | ImportOptions | Opção de importação. |
| outputStream | Stream | Fluxo PDF de saída. |

### Exceções

| exceção | condição |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception/) | A exceção é lançada quando um arquivo é inválido. |
| ArgumentNullException | O fluxo de saída é nulo |
| ArgumentException | O nome do arquivo de entrada é uma string vazia |

### Veja Também

* class [ImportOptions](../../../aspose.pdf/importoptions/)
* class [PdfProducer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Produce(Stream, ImportOptions, string) {#produce_3}

Produza o arquivo PDF usando a opção de importação especificada. Este exemplo mostra como produzir um arquivo Pdf a partir de um fluxo CGM.

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

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| inputStream | Stream | Fluxo de entrada. |
| options | ImportOptions | Opção de importação. |
| outputFileName | String | Arquivo PDF de saída. |

### Exceções

| exceção | condição |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception/) | A exceção é lançada quando um arquivo é inválido. |
| ArgumentNullException | O fluxo de entrada é nulo |
| ArgumentException | O nome do arquivo de saída é uma string vazia |

### Veja Também

* class [ImportOptions](../../../aspose.pdf/importoptions/)
* class [PdfProducer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Produce(string, ImportOptions, string) {#produce_7}

Produza o arquivo PDF usando a opção de importação especificada. Este exemplo mostra como produzir um arquivo Pdf a partir de um arquivo CGM.

```csharp
string inputFile = "myImage.cgm";
string outputFile = "myPdf.pdf";
ImportOptions importOptions = new CgmImportOptions();
PdfProducer.Produce(inputStream, importOptions, outputStream);
```

```csharp
public static void Produce(string inputFileName, ImportOptions options, string outputFileName)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| inputFileName | String | Nome do arquivo de entrada. |
| options | ImportOptions | Opção de importação. |
| outputFileName | String | Arquivo PDF de saída. |

### Exceções

| exceção | condição |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception/) | A exceção é lançada quando um arquivo é inválido. |
| ArgumentException | O nome do arquivo de entrada ou saída é uma string vazia |

### Veja Também

* class [ImportOptions](../../../aspose.pdf/importoptions/)
* class [PdfProducer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Produce(Stream, ImportOptions, Stream) {#produce_2}

Produza o arquivo PDF usando a opção de importação especificada. Este exemplo mostra como produzir um fluxo Pdf a partir de um fluxo CGM.

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

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| inputStream | Stream | Fluxo de entrada. |
| options | ImportOptions | Opção de importação. |
| outputStream | Stream | Fluxo PDF de saída. |

### Exceções

| exceção | condição |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception/) | A exceção é lançada quando um arquivo é inválido. |
| ArgumentNullException | O fluxo de entrada ou saída é nulo. |

### Veja Também

* class [ImportOptions](../../../aspose.pdf/importoptions/)
* class [PdfProducer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)