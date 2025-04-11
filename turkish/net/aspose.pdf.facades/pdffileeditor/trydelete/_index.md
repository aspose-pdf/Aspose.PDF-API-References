---
title: PdfFileEditor.TryDelete
second_title: Aspose.PDF for .NET API Reference
description: PdfFileEditor metodu. Giriş dosyasından numara dizisi ile belirtilen sayfaları siler ve yeni bir Pdf dosyası olarak kaydeder
type: docs
weight: 400
url: /tr/net/aspose.pdf.facades/pdffileeditor/trydelete/
---
## TryDelete(string, int[], string) {#trydelete_1}

Giriş dosyasından numara dizisi ile belirtilen sayfaları siler, yeni bir Pdf dosyası olarak kaydeder.

```csharp
public bool TryDelete(string inputFile, int[] pageNumber, string outputFile)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| inputFile | String | Giriş dosyası yolu. |
| pageNumber | Int32[] | Giriş dosyasındaki sayfanın indeksi. |
| outputFile | String | Çıkış dosyası yolu. |

### Dönüş Değeri

İşlem başarıyla tamamlandıysa true; aksi takdirde false.

## Açıklamalar

TryDelete metodu, Delete metoduna benzer, ancak TryDelete metodu işlem başarısız olursa bir istisna fırlatmaz.

## Örnekler

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryDelete("input.pdf", new int[] { 2, 3 }, "out.pdf");
```

### Ayrıca Bakınız

* sınıf [PdfFileEditor](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)

---

## TryDelete(Stream, int[], Stream) {#trydelete}

Giriş dosyasından numara dizisi ile belirtilen sayfaları siler, yeni bir Pdf dosyası olarak kaydeder.

```csharp
public bool TryDelete(Stream inputStream, int[] pageNumber, Stream outputStream)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| inputStream | Stream | Giriş dosyası akışı. |
| pageNumber | Int32[] | Giriş dosyasındaki sayfanın indeksi. |
| outputStream | Stream | Çıkış dosyası akışı. |

### Dönüş Değeri

Başarı için true, veya false.

## Açıklamalar

TryDelete metodu, Delete metoduna benzer, ancak TryDelete metodu işlem başarısız olursa bir istisna fırlatmaz.

## Örnekler

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream intputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryDelete(inputStream, new int[] { 2, 3 }, outputStream);
```

### Ayrıca Bakınız

* sınıf [PdfFileEditor](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)


## TryDelete(string, int[], HttpResponse) {#trydelete_3}

Belirtilen sayfaları belgeden siler ve sonucu HttpResponse nesnesine kaydeder.

```csharp
public bool TryDelete(string inputFile, int[] pageNumber, HttpResponse response)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| inputFile | String | Kaynak dosya yolu. |
| pageNumber | Int32[] | Silinmesi gereken sayfa numaralarının dizisi. |
| response | HttpResponse | Sonuç belgesinin saklanacağı yanıt nesnesi. |

### Dönüş Değeri

İşlem başarıyla tamamlandıysa true; aksi takdirde false.

## Açıklamalar

TryDelete metodu, Delete metoduna benzer, ancak TryDelete metodu işlem başarısız olursa bir istisna fırlatmaz.

### Ayrıca Bakınız

* sınıf [PdfFileEditor](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)

---

## TryDelete(Stream, int[], HttpResponse) {#trydelete_1}

Belirtilen sayfaları belgeden siler ve sonucu HttpResponse nesnesine kaydeder.

```csharp
public bool TryDelete(Stream inputStream, int[] pageNumber, HttpResponse response)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| inputStream | Stream | Kaynak belge akışı. |
| pageNumber | Int32[] | Silinecek sayfa numaralarının dizisi. |
| response | HttpResponse | HttpResponse nesnesi |

### Dönüş Değeri

İşlem başarıyla tamamlandıysa true; aksi takdirde false.

## Açıklamalar

TryDelete metodu, Delete metoduna benzer, ancak TryDelete metodu işlem başarısız olursa bir istisna fırlatmaz.

### Ayrıca Bakınız

* sınıf [PdfFileEditor](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)