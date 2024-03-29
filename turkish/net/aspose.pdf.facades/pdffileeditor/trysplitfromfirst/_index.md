---
title: TrySplitFromFirst
second_title: Aspose.PDF for .NET API Referansı
description: Pdf dosyasını ilk sayfadan belirtilen konuma böler ve ön kısmı yeni bir dosya olarak kaydeder.
type: docs
weight: 490
url: /tr/net/aspose.pdf.facades/pdffileeditor/trysplitfromfirst/
---
## TrySplitFromFirst(string, int, string) {#trysplitfromfirst_2}

Pdf dosyasını ilk sayfadan belirtilen konuma böler ve ön kısmı yeni bir dosya olarak kaydeder.

```csharp
public bool TrySplitFromFirst(string inputFile, int location, string outputFile)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| inputFile | String | Kaynak Pdf dosyası. |
| location | Int32 | Bölünme noktası. |
| outputFile | String | Çıktı pdf dosyası. |

### Geri dönüş değeri

Başarı için doğru veya yanlış.

### Notlar

TrySplitFromFirst yöntemi, SplitFromFirst yöntemine benzer, ancak TrySplitFromFirst yönteminin işlem başarısız olursa bir istisna oluşturmaması dışında.

### Örnekler

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TrySplitFromFirst("input.pdf", 5, "out.pdf");
```

### Ayrıca bakınız

* class [PdfFileEditor](../../pdffileeditor)
* ad alanı [Aspose.Pdf.Facades](../../pdffileeditor)
* toplantı [Aspose.PDF](../../../)

---

## TrySplitFromFirst(Stream, int, Stream) {#trysplitfromfirst}

Başlangıçtan belirtilen konuma böler ve ön kısmı çıktı Akışına kaydeder.

```csharp
public bool TrySplitFromFirst(Stream inputStream, int location, Stream outputStream)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| inputStream | Stream | Kaynak Pdf dosyası Akışı. |
| location | Int32 | Bölünme noktası. |
| outputStream | Stream | Çıkış dosyası Akış. |

### Geri dönüş değeri

Başarı için doğru veya yanlış.

### Notlar

Bu işlemden sonra akışlar KAPALI DEĞİLDİR. TrySplitFromFirst yöntemi, işlem başarısız olursa TrySplitFromFirst yönteminin bir istisna oluşturmaması dışında, SplitFromFirst yöntemine benzer.

### Örnekler

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
pfe.TrySplitFromFirst(sourceStream, 5, outStream);
```

### Ayrıca bakınız

* class [PdfFileEditor](../../pdffileeditor)
* ad alanı [Aspose.Pdf.Facades](../../pdffileeditor)
* toplantı [Aspose.PDF](../../../)

---

## TrySplitFromFirst(string, int, HttpResponse) {#trysplitfromfirst_3}

Belgeyi ilk sayfadan konuma böler ve sonucu HttpResponse nesnelerine kaydeder.

```csharp
public bool TrySplitFromFirst(string inputFile, int location, HttpResponse response)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| inputFile | String | Kaynak dosya adı. |
| location | Int32 | Bölünme noktası. |
| response | HttpResponse | HttpResponse nesneleri. |

### Geri dönüş değeri

işlem başarıyla tamamlandıysa true ; aksi halde yanlış.

### Notlar

TrySplitFromFirst yöntemi, SplitFromFirst yöntemine benzer, ancak TrySplitFromFirst yöntemi, işlem başarısız olursa bir istisna oluşturmaz.

### Ayrıca bakınız

* class [PdfFileEditor](../../pdffileeditor)
* ad alanı [Aspose.Pdf.Facades](../../pdffileeditor)
* toplantı [Aspose.PDF](../../../)

---

## TrySplitFromFirst(Stream, int, HttpResponse) {#trysplitfromfirst_1}

Belgeyi başlangıçtan belirtilen konuma böler ve sonucu HttpResponse nesnesine depolar.

```csharp
public bool TrySplitFromFirst(Stream inputStream, int location, HttpResponse response)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| inputStream | Stream | Kaynak belge akışı. |
| location | Int32 | Bölünme noktası. |
| response | HttpResponse | Sonucun saklanacağı HttpResponse nesnesi. |

### Geri dönüş değeri

işlem başarıyla tamamlandıysa true ; aksi halde yanlış.

### Notlar

TrySplitFromFirst yöntemi, SplitFromFirst yöntemine benzer, ancak TrySplitFromFirst yöntemi, işlem başarısız olursa bir istisna oluşturmaz.

### Ayrıca bakınız

* class [PdfFileEditor](../../pdffileeditor)
* ad alanı [Aspose.Pdf.Facades](../../pdffileeditor)
* toplantı [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
