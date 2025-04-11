---
title: PdfFileEditor.TrySplitToEnd
second_title: Aspose.PDF for .NET API Reference
description: PdfFileEditor metodu. Belirtilen yerden ayırır ve arka kısmı yeni bir dosya olarak kaydeder
type: docs
weight: 470
url: /tr/net/aspose.pdf.facades/pdffileeditor/trysplittoend/
---
## TrySplitToEnd(string, int, string) {#trysplittoend_1}

Belirtilen yerden ayırır ve arka kısmı yeni bir dosya olarak kaydeder.

```csharp
public bool TrySplitToEnd(string inputFile, int location, string outputFile)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| inputFile | String | Kaynak Pdf dosyası. |
| location | Int32 | Ayırma pozisyonu. |
| outputFile | String | Çıktı Pdf dosyası yolu. |

### Dönüş Değeri

Başarı için true, aksi takdirde false.

## Açıklamalar

TrySplitToEnd metodu, SplitToEnd metoduna benzer, ancak TrySplitToEnd metodu işlem başarısız olursa bir istisna fırlatmaz.

## Örnekler

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TrySplitToEnd("input.pdf", 5, "out.pdf");
```

### Ayrıca Bakınız

* sınıf [PdfFileEditor](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)

---

## TrySplitToEnd(Stream, int, Stream) {#trysplittoend}

Belirtilen yerden ayırır ve arka kısmı yeni bir dosya akışı olarak kaydeder.

```csharp
public bool TrySplitToEnd(Stream inputStream, int location, Stream outputStream)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| inputStream | Stream | Kaynak Pdf dosyası akışı. |
| location | Int32 | Ayırma pozisyonu. |
| outputStream | Stream | Çıktı Pdf dosyası akışı. |

### Dönüş Değeri

Başarı için true, aksi takdirde false.

## Açıklamalar

Akışlar bu işlemden sonra KAPANMAZ, CloseConcatedStreams belirtilmedikçe. TrySplitToEnd metodu, SplitToEnd metoduna benzer, ancak TrySplitToEnd metodu işlem başarısız olursa bir istisna fırlatmaz.

## Örnekler

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TrySplitToEnd(sourceStream, 5, outStream);
```

### Ayrıca Bakınız

* sınıf [PdfFileEditor](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)


## TrySplitToEnd(Stream, int, HttpResponse) {#trysplittoend_1}

Belirtilen yerden ayırır ve arka kısmı HttpResponse nesnesine kaydeder.

```csharp
public bool TrySplitToEnd(Stream inputStream, int location, HttpResponse response)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| inputStream | Stream | Kaynak belge akışı. |
| location | Int32 | Ayırma noktası. |
| response | HttpResponse | HttpResponse nesnesi. |

### Dönüş Değeri

İşlem başarıyla tamamlandıysa true; aksi takdirde false.

## Açıklamalar

TrySplitToEnd metodu, SplitToEnd metoduna benzer, ancak TrySplitToEnd metodu işlem başarısız olursa bir istisna fırlatmaz.

### Ayrıca Bakınız

* sınıf [PdfFileEditor](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)

---

## TrySplitToEnd(string, int, HttpResponse) {#trysplittoend_3}

Belirtilen yerden ayırır ve arka kısmı HttpResponse nesnesine kaydeder.

```csharp
public bool TrySplitToEnd(string inputFile, int location, HttpResponse response)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| inputFile | String | kaynak dosya adı. |
| location | Int32 | Ayırma noktası. |
| response | HttpResponse | HttpResponse nesneleri. |

### Dönüş Değeri

İşlem başarıyla tamamlandıysa true; aksi takdirde false.

## Açıklamalar

TrySplitToEnd metodu, SplitToEnd metoduna benzer, ancak TrySplitToEnd metodu işlem başarısız olursa bir istisna fırlatmaz.

### Ayrıca Bakınız

* sınıf [PdfFileEditor](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)