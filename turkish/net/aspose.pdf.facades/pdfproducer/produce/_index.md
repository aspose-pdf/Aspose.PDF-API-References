---
title: Produce
second_title: Aspose.PDF for .NET API Referansı
description: Belirtilen içe aktarma biçimini kullanarak PDF akışını oluşturun.  Bu örnek CGM akışından Pdf akışının nasıl üretileceğini gösterir.
type: docs
weight: 10
url: /tr/net/aspose.pdf.facades/pdfproducer/produce/
---
## Produce(Stream, ImportFormat, Stream) {#produce}

Belirtilen içe aktarma biçimini kullanarak PDF akışını oluşturun.  Bu örnek, CGM akışından Pdf akışının nasıl üretileceğini gösterir.

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

| Parametre | Tip | Tanım |
| --- | --- | --- |
| inputStream | Stream | Giriş akışı. |
| format | ImportFormat | İçe aktarma biçimi. |
| outputStream | Stream | Çıktı PDF akışı. |

### istisnalar

| istisna | şart |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception) | Bir dosya geçersiz olduğunda istisna atılır. |
| ArgumentNullException | Giriş veya çıkış akışı boş |

### Ayrıca bakınız

* enum [ImportFormat](../../../aspose.pdf/importformat)
* class [PdfProducer](../../pdfproducer)
* ad alanı [Aspose.Pdf.Facades](../../pdfproducer)
* toplantı [Aspose.PDF](../../../)

---

## Produce(string, ImportFormat, Stream) {#produce_4}

Belirtilen içe aktarma biçimini kullanarak PDF akışını oluşturun.  Bu örnek, CGM dosyasından Pdf akışının nasıl üretileceğini gösterir.

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

| Parametre | Tip | Tanım |
| --- | --- | --- |
| inputFileName | String | Dosya adını girin. |
| format | ImportFormat | İçe aktarma biçimi. |
| outputStream | Stream | Çıktı PDF akışı. |

### istisnalar

| istisna | şart |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception) | Bir dosya geçersiz olduğunda istisna atılır. |
| ArgumentNullException | Çıkış akışı boş |
| ArgumentException | Girdi dosyası adı boş bir dizedir |

### Ayrıca bakınız

* enum [ImportFormat](../../../aspose.pdf/importformat)
* class [PdfProducer](../../pdfproducer)
* ad alanı [Aspose.Pdf.Facades](../../pdfproducer)
* toplantı [Aspose.PDF](../../../)

---

## Produce(Stream, ImportFormat, string) {#produce_1}

Belirtilen içe aktarma biçimini kullanarak PDF dosyasını oluşturun.  Bu örnek, CGM akışından Pdf dosyasının nasıl üretileceğini gösterir.

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

| Parametre | Tip | Tanım |
| --- | --- | --- |
| inputStream | Stream | Giriş akışı. |
| format | ImportFormat | İçe aktarma biçimi. |
| outputFileName | String | Çıktı PDF dosyası |

### istisnalar

| istisna | şart |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception) | Bir dosya geçersiz olduğunda istisna atılır. |
| ArgumentNullException | Giriş akışı boş |
| ArgumentException | Çıktı dosyası adı boş bir dizedir |

### Ayrıca bakınız

* enum [ImportFormat](../../../aspose.pdf/importformat)
* class [PdfProducer](../../pdfproducer)
* ad alanı [Aspose.Pdf.Facades](../../pdfproducer)
* toplantı [Aspose.PDF](../../../)

---

## Produce(string, ImportFormat, string) {#produce_5}

Belirtilen içe aktarma biçimini kullanarak PDF dosyasını oluşturun.  Bu örnek, CGM dosyasından Pdf dosyasının nasıl üretileceğini gösterir.

```csharp
string inputFile = "myImage.cgm";
string outputFile = "myPdf.pdf";
PdfProducer.Produce(inputFile, ImportFormat.Cgm, outputFile);
```

```csharp
public static void Produce(string inputFileName, ImportFormat format, string outputFileName)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| inputFileName | String | Dosya adını girin. |
| format | ImportFormat | İçe aktarma biçimi. |
| outputFileName | String | Çıktı PDF dosyası |

### istisnalar

| istisna | şart |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception) | Bir dosya geçersiz olduğunda istisna atılır. |
| ArgumentException | Giriş veya çıkış dosyası adı boş bir dizedir |

### Ayrıca bakınız

* enum [ImportFormat](../../../aspose.pdf/importformat)
* class [PdfProducer](../../pdfproducer)
* ad alanı [Aspose.Pdf.Facades](../../pdfproducer)
* toplantı [Aspose.PDF](../../../)

---

## Produce(string, ImportOptions, Stream) {#produce_6}

Belirtilen içe aktarma seçeneğini kullanarak PDF akışını oluşturun.  Bu örnek, CGM dosyasından Pdf akışının nasıl üretileceğini gösterir.

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

| Parametre | Tip | Tanım |
| --- | --- | --- |
| inputFileName | String | Dosya adını girin. |
| options | ImportOptions | İçe aktarma seçeneği. |
| outputStream | Stream | Çıktı PDF akışı. |

### istisnalar

| istisna | şart |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception) | Bir dosya geçersiz olduğunda istisna atılır. |
| ArgumentNullException | Çıkış akışı boş |
| ArgumentException | Girdi dosyası adı boş bir dizedir |

### Ayrıca bakınız

* class [ImportOptions](../../../aspose.pdf/importoptions)
* class [PdfProducer](../../pdfproducer)
* ad alanı [Aspose.Pdf.Facades](../../pdfproducer)
* toplantı [Aspose.PDF](../../../)

---

## Produce(Stream, ImportOptions, string) {#produce_3}

Belirtilen içe aktarma seçeneğini kullanarak PDF dosyasını oluşturun.  Bu örnek, CGM akışından Pdf dosyasının nasıl üretileceğini gösterir.

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

| Parametre | Tip | Tanım |
| --- | --- | --- |
| inputStream | Stream | Giriş akışı. |
| options | ImportOptions | İçe aktarma seçeneği. |
| outputFileName | String | Çıktı PDF dosyası. |

### istisnalar

| istisna | şart |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception) | Bir dosya geçersiz olduğunda istisna atılır. |
| ArgumentNullException | Giriş akışı boş |
| ArgumentException | Çıktı dosyası adı boş bir dizedir |

### Ayrıca bakınız

* class [ImportOptions](../../../aspose.pdf/importoptions)
* class [PdfProducer](../../pdfproducer)
* ad alanı [Aspose.Pdf.Facades](../../pdfproducer)
* toplantı [Aspose.PDF](../../../)

---

## Produce(string, ImportOptions, string) {#produce_7}

Belirtilen içe aktarma seçeneğini kullanarak PDF dosyasını oluşturun.  Bu örnek, CGM dosyasından Pdf dosyasının nasıl üretileceğini gösterir.

```csharp
string inputFile = "myImage.cgm";
string outputFile = "myPdf.pdf";
ImportOptions importOptions = new CgmImportOptions();
PdfProducer.Produce(inputStream, importOptions, outputStream);
```

```csharp
public static void Produce(string inputFileName, ImportOptions options, string outputFileName)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| inputFileName | String | Dosya adını girin. |
| options | ImportOptions | İçe aktarma seçeneği. |
| outputFileName | String | Çıktı PDF akışı. |

### istisnalar

| istisna | şart |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception) | Bir dosya geçersiz olduğunda istisna atılır. |
| ArgumentException | Giriş veya çıkış dosyası adı boş bir dizedir |

### Ayrıca bakınız

* class [ImportOptions](../../../aspose.pdf/importoptions)
* class [PdfProducer](../../pdfproducer)
* ad alanı [Aspose.Pdf.Facades](../../pdfproducer)
* toplantı [Aspose.PDF](../../../)

---

## Produce(Stream, ImportOptions, Stream) {#produce_2}

Belirtilen içe aktarma seçeneğini kullanarak PDF dosyasını oluşturun.  Bu örnek, CGM akışından Pdf akışının nasıl üretileceğini gösterir.

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

| Parametre | Tip | Tanım |
| --- | --- | --- |
| inputStream | Stream | Giriş akışı. |
| options | ImportOptions | İçe aktarma seçeneği. |
| outputStream | Stream | Çıktı PDF akışı. |

### istisnalar

| istisna | şart |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception) | Bir dosya geçersiz olduğunda istisna atılır. |
| ArgumentNullException | Giriş veya çıkış akışı boş. |

### Ayrıca bakınız

* class [ImportOptions](../../../aspose.pdf/importoptions)
* class [PdfProducer](../../pdfproducer)
* ad alanı [Aspose.Pdf.Facades](../../pdfproducer)
* toplantı [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
