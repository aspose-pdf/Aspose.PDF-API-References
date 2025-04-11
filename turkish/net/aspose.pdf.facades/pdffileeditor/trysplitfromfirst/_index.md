---
title: PdfFileEditor.TrySplitFromFirst
second_title: Aspose.PDF for .NET API Reference
description: PdfFileEditor metodu. Pdf dosyasını ilk sayfadan belirtilen konuma böler ve ön kısmı yeni bir dosya olarak kaydeder
type: docs
weight: 460
url: /tr/net/aspose.pdf.facades/pdffileeditor/trysplitfromfirst/
---
## TrySplitFromFirst(string, int, string) {#trysplitfromfirst_1}

Pdf dosyasını ilk sayfadan belirtilen konuma böler ve ön kısmı yeni bir dosya olarak kaydeder.

```csharp
public bool TrySplitFromFirst(string inputFile, int location, string outputFile)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| inputFile | String | Kaynak Pdf dosyası. |
| location | Int32 | Bölme noktası. |
| outputFile | String | Çıktı Pdf dosyası. |

### Dönüş Değeri

Başarı için true, aksi takdirde false.

## Açıklamalar

TrySplitFromFirst metodu, SplitFromFirst metoduna benzer, ancak TrySplitFromFirst metodu işlem başarısız olursa bir istisna fırlatmaz.

## Örnekler

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TrySplitFromFirst("input.pdf", 5, "out.pdf");
```

### Ayrıca Bakınız

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TrySplitFromFirst(Stream, int, Stream) {#trysplitfromfirst}

Başlangıçtan belirtilen konuma böler ve ön kısmı çıktı Stream'inde kaydeder.

```csharp
public bool TrySplitFromFirst(Stream inputStream, int location, Stream outputStream)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| inputStream | Stream | Kaynak Pdf dosyası Stream'i. |
| location | Int32 | Bölme noktası. |
| outputStream | Stream | Çıktı dosyası Stream'i. |

### Dönüş Değeri

Başarı için true, aksi takdirde false.

## Açıklamalar

Stream'ler bu işlemden sonra KAPATILMAZ. TrySplitFromFirst metodu, SplitFromFirst metoduna benzer, ancak TrySplitFromFirst metodu işlem başarısız olursa bir istisna fırlatmaz.

## Örnekler

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
pfe.TrySplitFromFirst(sourceStream, 5, outStream);
```

### Ayrıca Bakınız

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


## TrySplitFromFirst(string, int, HttpResponse) {#trysplitfromfirst_3}

Belgeden ilk sayfadan belirtilen konuma böler ve sonucu HttpResponse nesnelerine kaydeder.

```csharp
public bool TrySplitFromFirst(string inputFile, int location, HttpResponse response)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| inputFile | String | Kaynak dosya adı. |
| location | Int32 | Bölme noktası. |
| response | HttpResponse | HttpResponse nesneleri. |

### Dönüş Değeri

İşlem başarıyla tamamlandıysa true; aksi takdirde false.

## Açıklamalar

TrySplitFromFirst metodu, SplitFromFirst metoduna benzer, ancak TrySplitFromFirst metodu işlem başarısız olursa bir istisna fırlatmaz.

### Ayrıca Bakınız

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TrySplitFromFirst(Stream, int, HttpResponse) {#trysplitfromfirst_1}

Belgeden başlangıçtan belirtilen konuma böler ve sonucu HttpResponse nesnesine kaydeder.

```csharp
public bool TrySplitFromFirst(Stream inputStream, int location, HttpResponse response)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| inputStream | Stream | Kaynak belgenin Stream'i. |
| location | Int32 | Bölme noktası. |
| response | HttpResponse | Sonucun saklanacağı HttpResponse nesnesi. |

### Dönüş Değeri

İşlem başarıyla tamamlandıysa true; aksi takdirde false.

## Açıklamalar

TrySplitFromFirst metodu, SplitFromFirst metoduna benzer, ancak TrySplitFromFirst metodu işlem başarısız olursa bir istisna fırlatmaz.

### Ayrıca Bakınız

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)