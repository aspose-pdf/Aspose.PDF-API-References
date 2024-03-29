---
title: TryDelete
second_title: Aspose.PDF for .NET API Referansı
description: Girdi dosyasından sayı dizisi ile belirtilen sayfaları siler yeni bir Pdf dosyası olarak kaydeder.
type: docs
weight: 430
url: /tr/net/aspose.pdf.facades/pdffileeditor/trydelete/
---
## TryDelete(string, int[], string) {#trydelete_2}

Girdi dosyasından sayı dizisi ile belirtilen sayfaları siler, yeni bir Pdf dosyası olarak kaydeder.

```csharp
public bool TryDelete(string inputFile, int[] pageNumber, string outputFile)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| inputFile | String | Dosya yolunu girin. |
| pageNumber | Int32[] | Giriş dosyasından çıkan sayfa dizini. |
| outputFile | String | Çıktı dosyası yolu. |

### Geri dönüş değeri

işlem başarıyla tamamlandıysa true ; aksi halde yanlış.

### Notlar

TryDelete yöntemi, İşlem başarısız olursa TryDelete yönteminin bir istisna oluşturmaması dışında, Sil yöntemine benzer.

### Örnekler

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryDelete("input.pdf", new int[] { 2, 3 }, "out.pdf");
```

### Ayrıca bakınız

* class [PdfFileEditor](../../pdffileeditor)
* ad alanı [Aspose.Pdf.Facades](../../pdffileeditor)
* toplantı [Aspose.PDF](../../../)

---

## TryDelete(Stream, int[], Stream) {#trydelete}

Girdi dosyasından sayı dizisi ile belirtilen sayfaları siler, yeni bir Pdf dosyası olarak kaydeder.

```csharp
public bool TryDelete(Stream inputStream, int[] pageNumber, Stream outputStream)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| inputStream | Stream | Girdi dosyası Akış. |
| pageNumber | Int32[] | Giriş dosyasından çıkan sayfa dizini. |
| outputStream | Stream | Çıktı dosyası akışı. |

### Geri dönüş değeri

Başarı için doğru veya yanlış.

### Notlar

TryDelete yöntemi, İşlem başarısız olursa TryDelete yönteminin bir istisna oluşturmaması dışında, Sil yöntemine benzer.

### Örnekler

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream intputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryDelete(inputStream, new int[] { 2, 3 }, outputStream);
```

### Ayrıca bakınız

* class [PdfFileEditor](../../pdffileeditor)
* ad alanı [Aspose.Pdf.Facades](../../pdffileeditor)
* toplantı [Aspose.PDF](../../../)

---

## TryDelete(string, int[], HttpResponse) {#trydelete_3}

Belgeden belirtilen sayfaları siler ve sonucu HttpResponse nesnesine kaydeder.

```csharp
public bool TryDelete(string inputFile, int[] pageNumber, HttpResponse response)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| inputFile | String | Kaynak dosyanın yolu. |
| pageNumber | Int32[] | Silinmesi gereken sayfa numaraları dizisi. |
| response | HttpResponse | Sonuç belgesinin saklanacağı yanıt nesnesi. |

### Geri dönüş değeri

işlem başarıyla tamamlandıysa true ; aksi halde yanlış.

### Notlar

TryDelete yöntemi, İşlem başarısız olursa TryDelete yönteminin bir istisna oluşturmaması dışında, Sil yöntemine benzer.

### Ayrıca bakınız

* class [PdfFileEditor](../../pdffileeditor)
* ad alanı [Aspose.Pdf.Facades](../../pdffileeditor)
* toplantı [Aspose.PDF](../../../)

---

## TryDelete(Stream, int[], HttpResponse) {#trydelete_1}

Belirtilen sayfaları belgeden siler ve sonucu HttpResponse nesnesine kaydeder.

```csharp
public bool TryDelete(Stream inputStream, int[] pageNumber, HttpResponse response)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| inputStream | Stream | Kaynak belge akışı. |
| pageNumber | Int32[] | Silinecek sayfa numaraları dizisi. |
| response | HttpResponse | HttpResponse nesnesi |

### Geri dönüş değeri

işlem başarıyla tamamlandıysa true ; aksi halde yanlış.

### Notlar

TryDelete yöntemi, İşlem başarısız olursa TryDelete yönteminin bir istisna oluşturmaması dışında, Sil yöntemine benzer.

### Ayrıca bakınız

* class [PdfFileEditor](../../pdffileeditor)
* ad alanı [Aspose.Pdf.Facades](../../pdffileeditor)
* toplantı [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
