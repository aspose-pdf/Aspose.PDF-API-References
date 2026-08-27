---
title: "PdfProducer.Produce"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Metode PdfProducer. Menghasilkan aliran PDF menggunakan format impor yang ditentukan. Contoh ini menunjukkan cara menghasilkan aliran Pdf dari aliran CGM."
type: docs
weight: 10
url: /id/net/aspose.pdf.facades/pdfproducer/produce/
---
## Produce(Stream, ImportFormat, Stream) {#produce}

Hasilkan aliran PDF menggunakan format impor yang ditentukan. Contoh ini menunjukkan cara menghasilkan aliran Pdf dari aliran CGM.

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
| inputStream | Stream | Aliran masukan. |
| format | ImportFormat | Format impor. |
| outputStream | Stream | Aliran PDF keluaran. |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception/) | Pengecualian dilempar ketika file tidak valid. |
| ArgumentNullException | Aliran masukan atau keluaran bernilai null |

### Lihat Juga

* enum [ImportFormat](../../../aspose.pdf/importformat/)
* class [PdfProducer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Produce(string, ImportFormat, Stream) {#produce_4}

Hasilkan aliran PDF menggunakan format impor yang ditentukan. Contoh ini menunjukkan cara menghasilkan aliran Pdf dari file CGM.

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
| inputFileName | String | Nama file masukan. |
| format | ImportFormat | Format impor. |
| outputStream | Stream | Aliran PDF keluaran. |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception/) | Pengecualian dilempar ketika file tidak valid. |
| ArgumentNullException | Aliran keluaran bernilai null |
| ArgumentException | Nama file masukan berupa string kosong |

### Lihat Juga

* enum [ImportFormat](../../../aspose.pdf/importformat/)
* class [PdfProducer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Produce(Stream, ImportFormat, string) {#produce_1}

Hasilkan file PDF menggunakan format impor yang ditentukan. Contoh ini menunjukkan cara menghasilkan file Pdf dari aliran CGM.

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
| inputStream | Stream | Aliran masukan. |
| format | ImportFormat | Format impor. |
| outputFileName | String | File PDF keluaran |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception/) | Pengecualian dilempar ketika file tidak valid. |
| ArgumentNullException | Aliran masukan bernilai null |
| ArgumentException | Nama file keluaran berupa string kosong |

### Lihat Juga

* enum [ImportFormat](../../../aspose.pdf/importformat/)
* class [PdfProducer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Produce(string, ImportFormat, string) {#produce_5}

Hasilkan file PDF menggunakan format impor yang ditentukan. Contoh ini menunjukkan cara menghasilkan file Pdf dari file CGM.

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
| inputFileName | String | Nama file masukan. |
| format | ImportFormat | Format impor. |
| outputFileName | String | File PDF keluaran |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception/) | Pengecualian dilempar ketika file tidak valid. |
| ArgumentException | Nama file masukan atau keluaran berupa string kosong |

### Lihat Juga

* enum [ImportFormat](../../../aspose.pdf/importformat/)
* class [PdfProducer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Produce(string, ImportOptions, Stream) {#produce_6}

Hasilkan aliran PDF menggunakan opsi impor yang ditentukan. Contoh ini menunjukkan cara menghasilkan aliran Pdf dari file CGM.

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
| inputFileName | String | Nama file masukan. |
| options | ImportOptions | Opsi impor. |
| outputStream | Stream | Aliran PDF keluaran. |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception/) | Pengecualian dilempar ketika file tidak valid. |
| ArgumentNullException | Aliran keluaran bernilai null |
| ArgumentException | Nama file masukan berupa string kosong |

### Lihat Juga

* class [ImportOptions](../../../aspose.pdf/importoptions/)
* class [PdfProducer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Produce(Stream, ImportOptions, string) {#produce_3}

Hasilkan file PDF menggunakan opsi impor yang ditentukan. Contoh ini menunjukkan cara menghasilkan file Pdf dari aliran CGM.

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
| inputStream | Stream | Aliran masukan. |
| options | ImportOptions | Opsi impor. |
| outputFileName | String | File PDF keluaran. |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception/) | Pengecualian dilempar ketika file tidak valid. |
| ArgumentNullException | Aliran masukan bernilai null |
| ArgumentException | Nama file keluaran berupa string kosong |

### Lihat Juga

* class [ImportOptions](../../../aspose.pdf/importoptions/)
* class [PdfProducer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Produce(string, ImportOptions, string) {#produce_7}

Hasilkan file PDF menggunakan opsi impor yang ditentukan. Contoh ini menunjukkan cara menghasilkan file Pdf dari file CGM.

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
| inputFileName | String | Nama file masukan. |
| options | ImportOptions | Opsi impor. |
| outputFileName | String | Aliran PDF keluaran. |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception/) | Pengecualian dilempar ketika file tidak valid. |
| ArgumentException | Nama file masukan atau keluaran berupa string kosong |

### Lihat Juga

* class [ImportOptions](../../../aspose.pdf/importoptions/)
* class [PdfProducer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Produce(Stream, ImportOptions, Stream) {#produce_2}

Hasilkan file PDF menggunakan opsi impor yang ditentukan. Contoh ini menunjukkan cara menghasilkan aliran Pdf dari aliran CGM.

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
| inputStream | Stream | Aliran masukan. |
| options | ImportOptions | Opsi impor. |
| outputStream | Stream | Aliran PDF keluaran. |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception/) | Pengecualian dilempar ketika file tidak valid. |
| ArgumentNullException | Aliran masukan atau keluaran bernilai null. |

### Lihat Juga

* class [ImportOptions](../../../aspose.pdf/importoptions/)
* class [PdfProducer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


