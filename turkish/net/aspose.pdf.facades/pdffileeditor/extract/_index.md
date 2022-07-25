---
title: Extract
second_title: Aspose.PDF for .NET API Referansı
description: Girdi dosyasından sayfaları çıkarır yeni bir Pdf dosyası olarak kaydeder.
type: docs
weight: 310
url: /tr/net/aspose.pdf.facades/pdffileeditor/extract/
---
## Extract(string, int, int, string) {#extract_3}

Girdi dosyasından sayfaları çıkarır, yeni bir Pdf dosyası olarak kaydeder.

```csharp
public bool Extract(string inputFile, int startPage, int endPage, string outputFile)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| inputFile | String | Pdf dosya yolunu girin. |
| startPage | Int32 | Sayfa numarasına başlayın. |
| endPage | Int32 | Bitiş sayfa numarası. |
| outputFile | String | Çıktı Pdf dosya yolu. |

### Geri dönüş değeri

Başarı için doğru veya yanlış.

### Örnekler

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.Extract("input.pdf", 3, 7, "output.pdf");
```

### Ayrıca bakınız

* class [PdfFileEditor](../../pdffileeditor)
* ad alanı [Aspose.Pdf.Facades](../../pdffileeditor)
* toplantı [Aspose.PDF](../../../)

---

## Extract(string, int[], string) {#extract_4}

Sayı dizisiyle belirtilen sayfaları çıkarır, yeni bir PDF dosyası olarak kaydeder.

```csharp
public bool Extract(string inputFile, int[] pageNumber, string outputFile)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| inputFile | String | Dosya yolunu girin. |
| pageNumber | Int32[] | Giriş dosyasından çıkan sayfa dizini. |
| outputFile | String | Çıktı dosyası yolu. |

### Geri dönüş değeri

İşlem başarılı olduysa doğrudur.

### Örnekler

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.Extract("input.pdf", new int[] { 3, 5, 7 }, "output.pdf");
```

### Ayrıca bakınız

* class [PdfFileEditor](../../pdffileeditor)
* ad alanı [Aspose.Pdf.Facades](../../pdffileeditor)
* toplantı [Aspose.PDF](../../../)

---

## Extract(Stream, int, int, Stream) {#extract}

Girdi dosyasından sayfaları çıkarır, yeni bir Pdf dosyası olarak kaydeder.

```csharp
public bool Extract(Stream inputStream, int startPage, int endPage, Stream outputStream)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| inputStream | Stream | Girdi dosyası Akış. |
| startPage | Int32 | Sayfa numarasına başlayın. |
| endPage | Int32 | Bitiş sayfa numarası. |
| outputStream | Stream | Çıktı Pdf dosyası Akışı. |

### Geri dönüş değeri

Başarı için doğru veya yanlış.

### Örnekler

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
pfe.Extract(sourceStream, 1, 3, 6, outStream);
```

### Ayrıca bakınız

* class [PdfFileEditor](../../pdffileeditor)
* ad alanı [Aspose.Pdf.Facades](../../pdffileeditor)
* toplantı [Aspose.PDF](../../../)

---

## Extract(Stream, int[], Stream) {#extract_1}

Sayı dizisiyle belirtilen sayfaları çıkarır, yeni bir Pdf dosyası olarak kaydeder.

```csharp
public bool Extract(Stream inputStream, int[] pageNumber, Stream outputStream)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| inputStream | Stream | Girdi dosyası Akış. |
| pageNumber | Int32[] | Giriş dosyasından çıkan sayfa dizini. |
| outputStream | Stream | Çıktı dosyası akışı. |

### Geri dönüş değeri

Başarı için doğru veya yanlış.

### Örnekler

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
pfe.Extract(sourceStream, new int[] { 3, 5, 8 }, outStream);
```

### Ayrıca bakınız

* class [PdfFileEditor](../../pdffileeditor)
* ad alanı [Aspose.Pdf.Facades](../../pdffileeditor)
* toplantı [Aspose.PDF](../../../)

---

## Extract(Stream, int[], HttpResponse) {#extract_2}

Belirtilen sayfaları kaynak dosyadan çıkarır ve sonucu HttpResponse nesnesine depolar.

```csharp
public bool Extract(Stream inputStream, int[] pageNumber, HttpResponse response)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| inputStream | Stream | Kaynak belge akışı. |
| pageNumber | Int32[] | Ayıklanacak sayfa numaraları dizisi. |
| response | HttpResponse | Sonucun saklanacağı HttpResponse nesnesi. |

### Geri dönüş değeri

İşlem başarılı olduysa doğrudur.

### Ayrıca bakınız

* class [PdfFileEditor](../../pdffileeditor)
* ad alanı [Aspose.Pdf.Facades](../../pdffileeditor)
* toplantı [Aspose.PDF](../../../)

---

## Extract(string, int[], HttpResponse) {#extract_5}

Belirtilen sayfaları kaynak dosyadan çıkarır ve sonucu HttpResponse nesnesine depolar.

```csharp
public bool Extract(string inputFile, int[] pageNumber, HttpResponse response)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| inputFile | String | Kaynak dosya yolu. |
| pageNumber | Int32[] | Ayıklanacak sayfa numaraları dizisi. |
| response | HttpResponse | Sonucun saklanacağı HttpResponse nesnesi. |

### Geri dönüş değeri

sayfalar başarıyla çıkarıldıysa true .

### Ayrıca bakınız

* class [PdfFileEditor](../../pdffileeditor)
* ad alanı [Aspose.Pdf.Facades](../../pdffileeditor)
* toplantı [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
