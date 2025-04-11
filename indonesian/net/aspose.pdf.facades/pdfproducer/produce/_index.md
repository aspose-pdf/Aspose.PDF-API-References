---
title: PdfProducer.Produce
second_title: Aspose.PDF for .NET API Reference
description: Metode PdfProducer. Menghasilkan aliran PDF menggunakan format impor yang ditentukan. Contoh ini menunjukkan cara menghasilkan aliran Pdf dari aliran CGM
type: docs
weight: 10
url: /id/net/aspose.pdf.facades/pdfproducer/produce/
---
## Produce(Stream, ImportFormat, Stream) {#produce}

Menghasilkan aliran PDF menggunakan format impor yang ditentukan. Contoh ini menunjukkan cara menghasilkan aliran Pdf dari aliran CGM.

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

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| inputStream | Stream | Aliran input. |
| format | ImportFormat | Format impor. |
| outputStream | Stream | Aliran PDF keluaran. |

### Eksepsi

| eksepsi | kondisi |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception/) | Eksepsi ini dilemparkan ketika sebuah file tidak valid. |
| ArgumentNullException | Aliran input atau keluaran adalah null |

### Lihat Juga

* enum [ImportFormat](../../../aspose.pdf/importformat/)
* class [PdfProducer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Produce(string, ImportFormat, Stream) {#produce_4}

Menghasilkan aliran PDF menggunakan format impor yang ditentukan. Contoh ini menunjukkan cara menghasilkan aliran Pdf dari file CGM.

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

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| inputFileName | String | Nama file input. |
| format | ImportFormat | Format impor. |
| outputStream | Stream | Aliran PDF keluaran. |

### Eksepsi

| eksepsi | kondisi |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception/) | Eksepsi ini dilemparkan ketika sebuah file tidak valid. |
| ArgumentNullException | Aliran keluaran adalah null |
| ArgumentException | Nama file input adalah string kosong |

### Lihat Juga

* enum [ImportFormat](../../../aspose.pdf/importformat/)
* class [PdfProducer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Produce(Stream, ImportFormat, string) {#produce_1}

Menghasilkan file PDF menggunakan format impor yang ditentukan. Contoh ini menunjukkan cara menghasilkan file Pdf dari aliran CGM.

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

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| inputStream | Stream | Aliran input. |
| format | ImportFormat | Format impor. |
| outputFileName | String | Nama file PDF keluaran |

### Eksepsi

| eksepsi | kondisi |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception/) | Eksepsi ini dilemparkan ketika sebuah file tidak valid. |
| ArgumentNullException | Aliran input adalah null |
| ArgumentException | Nama file keluaran adalah string kosong |

### Lihat Juga

* enum [ImportFormat](../../../aspose.pdf/importformat/)
* class [PdfProducer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Produce(string, ImportFormat, string) {#produce_5}

Menghasilkan file PDF menggunakan format impor yang ditentukan. Contoh ini menunjukkan cara menghasilkan file Pdf dari file CGM.

```csharp
string inputFile = "myImage.cgm";
string outputFile = "myPdf.pdf";
PdfProducer.Produce(inputFile, ImportFormat.Cgm, outputFile);
```

```csharp
public static void Produce(string inputFileName, ImportFormat format, string outputFileName)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| inputFileName | String | Nama file input. |
| format | ImportFormat | Format impor. |
| outputFileName | String | Nama file PDF keluaran |

### Eksepsi

| eksepsi | kondisi |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception/) | Eksepsi ini dilemparkan ketika sebuah file tidak valid. |
| ArgumentException | Nama file input atau keluaran adalah string kosong |

### Lihat Juga

* enum [ImportFormat](../../../aspose.pdf/importformat/)
* class [PdfProducer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Produce(string, ImportOptions, Stream) {#produce_6}

Menghasilkan aliran PDF menggunakan opsi impor yang ditentukan. Contoh ini menunjukkan cara menghasilkan aliran Pdf dari file CGM.

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

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| inputFileName | String | Nama file input. |
| options | ImportOptions | Opsi impor. |
| outputStream | Stream | Aliran PDF keluaran. |

### Eksepsi

| eksepsi | kondisi |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception/) | Eksepsi ini dilemparkan ketika sebuah file tidak valid. |
| ArgumentNullException | Aliran keluaran adalah null |
| ArgumentException | Nama file input adalah string kosong |

### Lihat Juga

* class [ImportOptions](../../../aspose.pdf/importoptions/)
* class [PdfProducer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Produce(Stream, ImportOptions, string) {#produce_3}

Menghasilkan file PDF menggunakan opsi impor yang ditentukan. Contoh ini menunjukkan cara menghasilkan file Pdf dari aliran CGM.

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

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| inputStream | Stream | Aliran input. |
| options | ImportOptions | Opsi impor. |
| outputFileName | String | Nama file PDF keluaran. |

### Eksepsi

| eksepsi | kondisi |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception/) | Eksepsi ini dilemparkan ketika sebuah file tidak valid. |
| ArgumentNullException | Aliran input adalah null |
| ArgumentException | Nama file keluaran adalah string kosong |

### Lihat Juga

* class [ImportOptions](../../../aspose.pdf/importoptions/)
* class [PdfProducer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Produce(string, ImportOptions, string) {#produce_7}

Menghasilkan file PDF menggunakan opsi impor yang ditentukan. Contoh ini menunjukkan cara menghasilkan file Pdf dari file CGM.

```csharp
string inputFile = "myImage.cgm";
string outputFile = "myPdf.pdf";
ImportOptions importOptions = new CgmImportOptions();
PdfProducer.Produce(inputStream, importOptions, outputStream);
```

```csharp
public static void Produce(string inputFileName, ImportOptions options, string outputFileName)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| inputFileName | String | Nama file input. |
| options | ImportOptions | Opsi impor. |
| outputFileName | String | Nama file PDF keluaran. |

### Eksepsi

| eksepsi | kondisi |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception/) | Eksepsi ini dilemparkan ketika sebuah file tidak valid. |
| ArgumentException | Nama file input atau keluaran adalah string kosong |

### Lihat Juga

* class [ImportOptions](../../../aspose.pdf/importoptions/)
* class [PdfProducer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Produce(Stream, ImportOptions, Stream) {#produce_2}

Menghasilkan file PDF menggunakan opsi impor yang ditentukan. Contoh ini menunjukkan cara menghasilkan aliran Pdf dari aliran CGM.

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

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| inputStream | Stream | Aliran input. |
| options | ImportOptions | Opsi impor. |
| outputStream | Stream | Aliran PDF keluaran. |

### Eksepsi

| eksepsi | kondisi |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception/) | Eksepsi ini dilemparkan ketika sebuah file tidak valid. |
| ArgumentNullException | Aliran input atau keluaran adalah null. |

### Lihat Juga

* class [ImportOptions](../../../aspose.pdf/importoptions/)
* class [PdfProducer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)