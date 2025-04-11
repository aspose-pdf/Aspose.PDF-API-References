---
title: PdfProducer.Produce
second_title: Aspose.PDF for .NET API Reference
description: PdfProducer metodu. Belirtilen içe aktarma formatını kullanarak PDF akışını üretin. Bu örnek, CGM akışından Pdf akışı nasıl üretilir gösterir.
type: docs
weight: 10
url: /tr/net/aspose.pdf.facades/pdfproducer/produce/
---
## Produce(Stream, ImportFormat, Stream) {#produce}

Belirtilen içe aktarma formatını kullanarak PDF akışını üretin. Bu örnek, CGM akışından Pdf akışı nasıl üretilir gösterir.

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

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| inputStream | Stream | Giriş akışı. |
| format | ImportFormat | İçe aktarma formatı. |
| outputStream | Stream | Çıkış PDF akışı. |

### İstisnalar

| istisna | durum |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception/) | Bir dosya geçersiz olduğunda istisna fırlatılır. |
| ArgumentNullException | Giriş veya çıkış akışı null |

### Ayrıca Bakınız

* enum [ImportFormat](../../../aspose.pdf/importformat/)
* class [PdfProducer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Produce(string, ImportFormat, Stream) {#produce_4}

Belirtilen içe aktarma formatını kullanarak PDF akışını üretin. Bu örnek, CGM dosyasından Pdf akışı nasıl üretilir gösterir.

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

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| inputFileName | String | Giriş dosya adı. |
| format | ImportFormat | İçe aktarma formatı. |
| outputStream | Stream | Çıkış PDF akışı. |

### İstisnalar

| istisna | durum |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception/) | Bir dosya geçersiz olduğunda istisna fırlatılır. |
| ArgumentNullException | Çıkış akışı null |
| ArgumentException | Giriş dosya adı boş bir dizedir |

### Ayrıca Bakınız

* enum [ImportFormat](../../../aspose.pdf/importformat/)
* class [PdfProducer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Produce(Stream, ImportFormat, string) {#produce_1}

Belirtilen içe aktarma formatını kullanarak PDF dosyasını üretin. Bu örnek, CGM akışından Pdf dosyası nasıl üretilir gösterir.

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

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| inputStream | Stream | Giriş akışı. |
| format | ImportFormat | İçe aktarma formatı. |
| outputFileName | String | Çıkış PDF dosyası |

### İstisnalar

| istisna | durum |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception/) | Bir dosya geçersiz olduğunda istisna fırlatılır. |
| ArgumentNullException | Giriş akışı null |
| ArgumentException | Çıkış dosya adı boş bir dizedir |

### Ayrıca Bakınız

* enum [ImportFormat](../../../aspose.pdf/importformat/)
* class [PdfProducer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Produce(string, ImportFormat, string) {#produce_5}

Belirtilen içe aktarma formatını kullanarak PDF dosyasını üretin. Bu örnek, CGM dosyasından Pdf dosyası nasıl üretilir gösterir.

```csharp
string inputFile = "myImage.cgm";
string outputFile = "myPdf.pdf";
PdfProducer.Produce(inputFile, ImportFormat.Cgm, outputFile);
```

```csharp
public static void Produce(string inputFileName, ImportFormat format, string outputFileName)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| inputFileName | String | Giriş dosya adı. |
| format | ImportFormat | İçe aktarma formatı. |
| outputFileName | String | Çıkış PDF dosyası |

### İstisnalar

| istisna | durum |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception/) | Bir dosya geçersiz olduğunda istisna fırlatılır. |
| ArgumentException | Giriş veya çıkış dosya adı boş bir dizedir |

### Ayrıca Bakınız

* enum [ImportFormat](../../../aspose.pdf/importformat/)
* class [PdfProducer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Produce(string, ImportOptions, Stream) {#produce_6}

Belirtilen içe aktarma seçeneğini kullanarak PDF akışını üretin. Bu örnek, CGM dosyasından Pdf akışı nasıl üretilir gösterir.

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

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| inputFileName | String | Giriş dosya adı. |
| options | ImportOptions | İçe aktarma seçeneği. |
| outputStream | Stream | Çıkış PDF akışı. |

### İstisnalar

| istisna | durum |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception/) | Bir dosya geçersiz olduğunda istisna fırlatılır. |
| ArgumentNullException | Çıkış akışı null |
| ArgumentException | Giriş dosya adı boş bir dizedir |

### Ayrıca Bakınız

* class [ImportOptions](../../../aspose.pdf/importoptions/)
* class [PdfProducer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Produce(Stream, ImportOptions, string) {#produce_3}

Belirtilen içe aktarma seçeneğini kullanarak PDF dosyasını üretin. Bu örnek, CGM akışından Pdf dosyası nasıl üretilir gösterir.

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

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| inputStream | Stream | Giriş akışı. |
| options | ImportOptions | İçe aktarma seçeneği. |
| outputFileName | String | Çıkış PDF dosyası. |

### İstisnalar

| istisna | durum |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception/) | Bir dosya geçersiz olduğunda istisna fırlatılır. |
| ArgumentNullException | Giriş akışı null |
| ArgumentException | Çıkış dosya adı boş bir dizedir |

### Ayrıca Bakınız

* class [ImportOptions](../../../aspose.pdf/importoptions/)
* class [PdfProducer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Produce(string, ImportOptions, string) {#produce_7}

Belirtilen içe aktarma seçeneğini kullanarak PDF dosyasını üretin. Bu örnek, CGM dosyasından Pdf dosyası nasıl üretilir gösterir.

```csharp
string inputFile = "myImage.cgm";
string outputFile = "myPdf.pdf";
ImportOptions importOptions = new CgmImportOptions();
PdfProducer.Produce(inputStream, importOptions, outputStream);
```

```csharp
public static void Produce(string inputFileName, ImportOptions options, string outputFileName)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| inputFileName | String | Giriş dosya adı. |
| options | ImportOptions | İçe aktarma seçeneği. |
| outputFileName | String | Çıkış PDF akışı. |

### İstisnalar

| istisna | durum |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception/) | Bir dosya geçersiz olduğunda istisna fırlatılır. |
| ArgumentException | Giriş veya çıkış dosya adı boş bir dizedir |

### Ayrıca Bakınız

* class [ImportOptions](../../../aspose.pdf/importoptions/)
* class [PdfProducer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Produce(Stream, ImportOptions, Stream) {#produce_2}

Belirtilen içe aktarma seçeneğini kullanarak PDF dosyasını üretin. Bu örnek, CGM akışından Pdf akışı nasıl üretilir gösterir.

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

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| inputStream | Stream | Giriş akışı. |
| options | ImportOptions | İçe aktarma seçeneği. |
| outputStream | Stream | Çıkış PDF akışı. |

### İstisnalar

| istisna | durum |
| --- | --- |
| [InvalidFileFormatException](../../../aspose.pdf/invalidfileformatexception/) | Bir dosya geçersiz olduğunda istisna fırlatılır. |
| ArgumentNullException | Giriş veya çıkış akışı null. |

### Ayrıca Bakınız

* class [ImportOptions](../../../aspose.pdf/importoptions/)
* class [PdfProducer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)