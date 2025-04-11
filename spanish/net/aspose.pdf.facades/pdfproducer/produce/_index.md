---
title: PdfProducer.Produce
second_title: Aspose.PDF for .NET API Reference
description: Método PdfProducer. Produce el flujo PDF utilizando el formato de importación especificado. Este ejemplo muestra cómo producir un flujo Pdf a partir de un flujo CGM
type: docs
weight: 10
url: /es/net/aspose.pdf.facades/pdfproducer/produce/
---
## Produce(Stream, ImportFormat, Stream) {#produce}

Produce el flujo PDF utilizando el formato de importación especificado. Este ejemplo muestra cómo producir un flujo Pdf a partir de un flujo CGM.

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

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputStream | Stream | Flujo de entrada. |
| format | ImportFormat | Formato de importación. |
| outputStream | Stream | Flujo PDF de salida. |

### Excepciones

| excepción | condición |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception/) | La excepción se lanza cuando un archivo es inválido. |
| ArgumentNullException | El flujo de entrada o salida es nulo |

### Ver También

* enum [ImportFormat](../../../aspose.pdf/importformat/)
* class [PdfProducer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Produce(string, ImportFormat, Stream) {#produce_4}

Produce el flujo PDF utilizando el formato de importación especificado. Este ejemplo muestra cómo producir un flujo Pdf a partir de un archivo CGM.

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

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputFileName | String | Nombre del archivo de entrada. |
| format | ImportFormat | Formato de importación. |
| outputStream | Stream | Flujo PDF de salida. |

### Excepciones

| excepción | condición |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception/) | La excepción se lanza cuando un archivo es inválido. |
| ArgumentNullException | El flujo de salida es nulo |
| ArgumentException | El nombre del archivo de entrada es una cadena vacía |

### Ver También

* enum [ImportFormat](../../../aspose.pdf/importformat/)
* class [PdfProducer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Produce(Stream, ImportFormat, string) {#produce_1}

Produce el archivo PDF utilizando el formato de importación especificado. Este ejemplo muestra cómo producir un archivo Pdf a partir de un flujo CGM.

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

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputStream | Stream | Flujo de entrada. |
| format | ImportFormat | Formato de importación. |
| outputFileName | String | Archivo PDF de salida |

### Excepciones

| excepción | condición |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception/) | La excepción se lanza cuando un archivo es inválido. |
| ArgumentNullException | El flujo de entrada es nulo |
| ArgumentException | El nombre del archivo de salida es una cadena vacía |

### Ver También

* enum [ImportFormat](../../../aspose.pdf/importformat/)
* class [PdfProducer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Produce(string, ImportFormat, string) {#produce_5}

Produce el archivo PDF utilizando el formato de importación especificado. Este ejemplo muestra cómo producir un archivo Pdf a partir de un archivo CGM.

```csharp
string inputFile = "myImage.cgm";
string outputFile = "myPdf.pdf";
PdfProducer.Produce(inputFile, ImportFormat.Cgm, outputFile);
```

```csharp
public static void Produce(string inputFileName, ImportFormat format, string outputFileName)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputFileName | String | Nombre del archivo de entrada. |
| format | ImportFormat | Formato de importación. |
| outputFileName | String | Archivo PDF de salida |

### Excepciones

| excepción | condición |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception/) | La excepción se lanza cuando un archivo es inválido. |
| ArgumentException | El nombre del archivo de entrada o salida es una cadena vacía |

### Ver También

* enum [ImportFormat](../../../aspose.pdf/importformat/)
* class [PdfProducer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Produce(string, ImportOptions, Stream) {#produce_6}

Produce el flujo PDF utilizando la opción de importación especificada. Este ejemplo muestra cómo producir un flujo Pdf a partir de un archivo CGM.

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

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputFileName | String | Nombre del archivo de entrada. |
| options | ImportOptions | Opción de importación. |
| outputStream | Stream | Flujo PDF de salida. |

### Excepciones

| excepción | condición |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception/) | La excepción se lanza cuando un archivo es inválido. |
| ArgumentNullException | El flujo de salida es nulo |
| ArgumentException | El nombre del archivo de entrada es una cadena vacía |

### Ver También

* class [ImportOptions](../../../aspose.pdf/importoptions/)
* class [PdfProducer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Produce(Stream, ImportOptions, string) {#produce_3}

Produce el archivo PDF utilizando la opción de importación especificada. Este ejemplo muestra cómo producir un archivo Pdf a partir de un flujo CGM.

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

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputStream | Stream | Flujo de entrada. |
| options | ImportOptions | Opción de importación. |
| outputFileName | String | Archivo PDF de salida. |

### Excepciones

| excepción | condición |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception/) | La excepción se lanza cuando un archivo es inválido. |
| ArgumentNullException | El flujo de entrada es nulo |
| ArgumentException | El nombre del archivo de salida es una cadena vacía |

### Ver También

* class [ImportOptions](../../../aspose.pdf/importoptions/)
* class [PdfProducer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Produce(string, ImportOptions, string) {#produce_7}

Produce el archivo PDF utilizando la opción de importación especificada. Este ejemplo muestra cómo producir un archivo Pdf a partir de un archivo CGM.

```csharp
string inputFile = "myImage.cgm";
string outputFile = "myPdf.pdf";
ImportOptions importOptions = new CgmImportOptions();
PdfProducer.Produce(inputStream, importOptions, outputStream);
```

```csharp
public static void Produce(string inputFileName, ImportOptions options, string outputFileName)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputFileName | String | Nombre del archivo de entrada. |
| options | ImportOptions | Opción de importación. |
| outputFileName | String | Archivo PDF de salida. |

### Excepciones

| excepción | condición |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception/) | La excepción se lanza cuando un archivo es inválido. |
| ArgumentException | El nombre del archivo de entrada o salida es una cadena vacía |

### Ver También

* class [ImportOptions](../../../aspose.pdf/importoptions/)
* class [PdfProducer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Produce(Stream, ImportOptions, Stream) {#produce_2}

Produce el archivo PDF utilizando la opción de importación especificada. Este ejemplo muestra cómo producir un flujo Pdf a partir de un flujo CGM.

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

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputStream | Stream | Flujo de entrada. |
| options | ImportOptions | Opción de importación. |
| outputStream | Stream | Flujo PDF de salida. |

### Excepciones

| excepción | condición |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception/) | La excepción se lanza cuando un archivo es inválido. |
| ArgumentNullException | El flujo de entrada o salida es nulo. |

### Ver También

* class [ImportOptions](../../../aspose.pdf/importoptions/)
* class [PdfProducer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)