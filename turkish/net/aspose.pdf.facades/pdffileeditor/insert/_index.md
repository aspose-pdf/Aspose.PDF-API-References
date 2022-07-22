---
title: Insert
second_title: Aspose.PDF for .NET API Referansı
description: Başka bir dosyadan sayfaları bir konumda Pdf dosyasına ekler.
type: docs
weight: 320
url: /tr/net/aspose.pdf.facades/pdffileeditor/insert/
---
## Insert(string, int, string, int, int, string) {#insert_3}

Başka bir dosyadan sayfaları bir konumda Pdf dosyasına ekler.

```csharp
public bool Insert(string inputFile, int insertLocation, string portFile, int startPage, 
    int endPage, string outputFile)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| inputFile | String | Pdf dosyasını girin. |
| insertLocation | Int32 | Giriş dosyasındaki konum. |
| portFile | String | Taşıma pdf dosyası. |
| startPage | Int32 | portFile'da başlangıç pozisyonu. |
| endPage | Int32 | portFile'daki bitiş konumu. |
| outputFile | String | Çıktı pdf dosyası. |

### Geri dönüş değeri

Başarı için doğru veya yanlış.

### Örnekler

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.Insert("file1.pdf", 1, "file2.pdf", 2, 6, "out.pdf");
```

### Ayrıca bakınız

* class [PdfFileEditor](../../pdffileeditor)
* ad alanı [Aspose.Pdf.Facades](../../pdffileeditor)
* toplantı [Aspose.PDF](../../../)

---

## Insert(Stream, int, Stream, int, int, Stream) {#insert}

Başka bir dosyadan sayfaları giriş Pdf dosyasına ekler.

```csharp
public bool Insert(Stream inputStream, int insertLocation, Stream portStream, int startPage, 
    int endPage, Stream outputStream)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| inputStream | Stream | Pdf dosyasının Giriş Akışı. |
| insertLocation | Int32 | Giriş dosyasına konum ekleyin. |
| portStream | Stream | Sayfalar için Pdf dosyası akışı. |
| startPage | Int32 | Hangi sayfadan başlamalı. |
| endPage | Int32 | Hangi sayfada bitecek. |
| outputStream | Stream | Çıkış Akışı. |

### Geri dönüş değeri

Başarı için doğru veya yanlış.

### Örnekler

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream insertedStream = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
pfe.Insert(sourceStream, 1, insertedStream, 2, 6, outStream);
```

### Ayrıca bakınız

* class [PdfFileEditor](../../pdffileeditor)
* ad alanı [Aspose.Pdf.Facades](../../pdffileeditor)
* toplantı [Aspose.PDF](../../../)

---

## Insert(string, int, string, int[], string) {#insert_4}

Başka bir dosyadan sayfaları giriş Pdf dosyasına ekler.

```csharp
public bool Insert(string inputFile, int insertLocation, string portFile, int[] pageNumber, 
    string outputFile)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| inputFile | String | Pdf dosyasını girin. |
| insertLocation | Int32 | Giriş dosyasına konum ekleyin. |
| portFile | String | Pdf dosyasından sayfalar. |
| pageNumber | Int32[] | portFile içinde taşınan sayfa numarası. |
| outputFile | String | Çıktı pdf dosyası. |

### Geri dönüş değeri

Başarı için doğru veya yanlış.

### Örnekler

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.Insert("file1.pdf", 1, "file2.pdf", new int[] { 2, 6 }, "out.pdf");
```

### Ayrıca bakınız

* class [PdfFileEditor](../../pdffileeditor)
* ad alanı [Aspose.Pdf.Facades](../../pdffileeditor)
* toplantı [Aspose.PDF](../../../)

---

## Insert(Stream, int, Stream, int[], Stream) {#insert_1}

Başka bir dosyadan sayfaları giriş Pdf dosyasına ekler.

```csharp
public bool Insert(Stream inputStream, int insertLocation, Stream portStream, int[] pageNumber, 
    Stream outputStream)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| inputStream | Stream | Pdf dosyasının Giriş Akışı. |
| insertLocation | Int32 | Giriş dosyasına konum ekleyin. |
| portStream | Stream | Sayfalar için Pdf dosyası akışı. |
| pageNumber | Int32[] | portFile içinde taşınan sayfa numarası. |
| outputStream | Stream | Çıkış Akışı. |

### Geri dönüş değeri

İşlem başarılı olduysa doğrudur.

### Örnekler

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream insertedStream = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
pfe.Insert(sourceStream, 1, insertedStream, new int[] { 3, 4, 5}, outStream);
```

### Ayrıca bakınız

* class [PdfFileEditor](../../pdffileeditor)
* ad alanı [Aspose.Pdf.Facades](../../pdffileeditor)
* toplantı [Aspose.PDF](../../../)

---

## Insert(string, int, string, int[], HttpResponse) {#insert_5}

Dosyanın içeriğini kaynak dosyaya ekler ve sonucu HttpResponse nesnesine depolar.

```csharp
public bool Insert(string inputFile, int insertLocation, string portFile, int[] pageNumber, 
    HttpResponse response)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| inputFile | String | Kaynak dosya adı. |
| insertLocation | Int32 | İkinci dosyanın ekleneceği sayfa numarası. |
| portFile | String | Eklenecek dosyanın yolu. |
| pageNumber | Int32[] | Eklenecek olan kaynak dosyadaki sayfa numaraları dizisi. |
| response | HttpResponse | Sonucun saklanacağı yanıt nesnesi. |

### Geri dönüş değeri

true yerleştirme başarılı oldu.

### Ayrıca bakınız

* class [PdfFileEditor](../../pdffileeditor)
* ad alanı [Aspose.Pdf.Facades](../../pdffileeditor)
* toplantı [Aspose.PDF](../../../)

---

## Insert(Stream, int, Stream, int[], HttpResponse) {#insert_2}

Belgeyi başka bir belgeye ekler ve sonucu yanıt nesnesine kaydeder.

```csharp
public bool Insert(Stream inputStream, int insertLocation, Stream portStream, int[] pageNumber, 
    HttpResponse response)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| inputStream | Stream | Kaynak belgeyle akış |
| insertLocation | Int32 | Diğer belgenin ekleneceği konum. |
| portStream | Stream | Eklenecek belge. |
| pageNumber | Int32[] | Eklenecek ikinci belgedeki sayfa numaraları dizisi. |
| response | HttpResponse | Sonucun saklanacağı yanıt nesnesi. |

### Geri dönüş değeri

İşlem başarılı olduysa doğrudur.

### Ayrıca bakınız

* class [PdfFileEditor](../../pdffileeditor)
* ad alanı [Aspose.Pdf.Facades](../../pdffileeditor)
* toplantı [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
